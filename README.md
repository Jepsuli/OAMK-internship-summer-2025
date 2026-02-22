# Linux Course Automation Tasks (Moodle + CodeRunner)
During my internship, I designed and implemented Linux-related exam preparation tasks for Moodle. The exercises were built using the CodeRunner plugin and included automatic grading, allowing students to receive immediate feedback on their answers.
The tasks covered both standard Linux commands and more advanced pipeline-based commands. The focus areas included file management, process control, permissions, networking tools, log analysis, and system administration.

## Bash / Linux Command Tasks
The exercises included practical command-line tasks such as:<br>

File and directory management (cp, mv, mkdir, rm, ls -l)<br>
Text processing and pipelines (grep, awk, sort, uniq, wc)<br>
Permissions and ownership (chmod, chown)<br>
Process management (ps, killall)<br>
System services and logs (systemctl, journalctl)<br>
Networking tools (netstat, tcpdump, curl, wget)<br>
Package management (dpkg)<br>

Some tasks validated the result by executing the student's Bash command inside a sandboxed environment and comparing the output to the expected result. Other tasks used Python-based validation logic to check whether the student provided the correct command syntax.
The goal was to simulate real-world Linux usage rather than simple multiple-choice questions.<br>

## C Programming Tasks for Linux
In addition to Bash exercises, I implemented C programming tasks focused on Linux system-level programming. These tasks were also automatically graded using CodeRunner.
The student’s function implementation was embedded into a predefined test program, compiled with strict flags (-Wall -Werror), and executed automatically to verify correctness.

Topics included:
File access checks (access, R_OK)<br>
File size and permissions handling<br>
Directory operations (mkdir, directory listing)<br>
Process management (fork, PID, UID)<br>v
Executing shell commands<br>
System uptime retrieval<br>

This project combined Linux system administration, systems programming, and automation into a scalable and production-ready exam environment.
