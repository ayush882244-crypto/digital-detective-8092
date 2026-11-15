# mission 3 - system inspection evidence

this record summarizes observations from system inspection commands

## task 3.1 - os account storage and activity
- os details: darwin 27.2.0 arm64 (macos)
- active account: [redacted]
- root volume storage: 460gi total 13gi used 368gi available
- system activity: uptime checked showing active user session and low load averages

## task 3.2 - processes and pids
running processes inspected using ps:
- safari browser: application process
- text editor / terminal: user application process
- windowserver: background system process
pid is the process identifier number given by os to identify each running program

## task 3.3 - paths and permissions
- absolute path example: /users/[redacted]/digital-detective-8092/mission-03
- relative path to root: mission-03/README.md
- relative path to subfolder: evidence/system-inspection.md
file permissions on terminal-practice/notes.txt:
permissions: -rw-r--r--
owner has read and write permissions (rw-) without execute
group and others have read only permissions (r--)
