# Linux Course Automation Tasks (Moodle + CodeRunner)
During my internship, I designed and implemented Linux-related exam preparation tasks for Moodle. The exercises were built using the CodeRunner plugin and included automatic grading, allowing students to receive immediate feedback on their answers.
The tasks covered both standard Linux commands and more advanced pipeline-based commands. The focus areas included file management, process control, permissions, networking tools, log analysis, and system administration.

## Bash / Linux Command Tasks

The exercises included practical command-line tasks such as:

### File and Directory Management
cp, mv, mkdir, rm, pwd, ls -l

### File Content Processing
cat, less, head, tail
wc, sort, uniq
grep, awk

### Combined pipelines such as:
cat | grep
cat | sort | uniq
cat | wc
ls -l | awk

### Permissions and Ownership
chmod
chown

### Process Management
ps -e
killall
sudo

### System and Service Management
systemctl
journalctl
journalctl | grep | tail
journalctl -xe | grep

### Networking and Diagnostics
netstat
tcpdump
traceroute
curl
wget
ip -a

### Package Management and Documentation
dpkg
man

Some tasks validated the result by executing the student's Bash command inside a sandboxed environment and comparing the output to the expected result. Other tasks used Python-based validation logic to check whether the student provided the correct command syntax.
The goal was to simulate real-world Linux usage rather than simple multiple-choice questions.

## C Programming Tasks for Linux
