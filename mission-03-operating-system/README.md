# mission 3 - understand the operating system

## 1 task / objective
explore operating system details running processes storage usage paths and permissions

## 2 work completed
gathered operating system information and process data
checked disk storage and active user account
analyzed absolute vs relative paths and file permissions
documented six key operating system responsibilities

## 3 commands / tools used
- uname -srm: display os kernel name release and architecture
- whoami: show current active user account
- df -h: show available and used disk storage
- ps aux: show running processes and pid values
- ls -l: inspect file permissions

## 4 my understanding

### task 3.1 - operating system exploration
| information explored | what it tells you | your observation (privacy-safe) |
| --- | --- | --- |
| operating system / system details | kernel name release version and cpu architecture | darwin 27.2.0 arm64 |
| current account identity | username of active logged in account | [redacted] |
| available and used storage | total disk space used space and available space | 460gi total 13gi used 368gi available on root disk |
| system activity snapshot | list of active processes cpu usage and memory | processes running with pid cpu and memory columns |

### task 3.2 - understand processes
- what is a process:
  a program currently loaded into memory and running
- what does the pid column represent:
  process id which is a unique number assigned by os to manage each running program
- two examples of processes running on computer:
  terminal app and browser app

### task 3.3 - paths and permissions
- difference between absolute and relative path:
  absolute path starts from root / and gives the full path to a file
  relative path starts from current working directory
- examples from assignment folder:
  absolute path example: /users/[redacted]/digital-detective-8092/mission-03-operating-system
  relative path example: mission-03-operating-system/README.md
- file permission table:
| permission | meaning | example |
| --- | --- | --- |
| r - read | allows reading file content | viewing a text file |
| w - write | allows modifying or saving file | editing a text file |
| x - execute | allows running file as program or entering directory | running a script |
- file observation:
  practice file has permissions rw-r--r-- so owner has read and write permissions but not execute

### task 3.4 - operating system responsibilities
| os responsibility | your explanation | example |
| --- | --- | --- |
| process management | schedules and controls running programs | switching cpu between open apps |
| memory management | allocates ram to apps and frees it when closed | giving memory to browser tabs |
| device management | manages input and output hardware devices using drivers | sending print commands to printer |
| file management | organizes data into files and folders on disk | creating saving and renaming files |
| user interface / shell | provides gui or cli for user to give commands | terminal cli or macos desktop gui |
| security and permissions | controls access rights and protects files from unauthorized users | prompting for password when installing apps |

## 5 difficulties faced
understanding the permission letters rw-r--r--

## 6 how i resolved them
learned that the first three letters represent owner permissions next three represent group and last three represent others

## 7 evidence / files
- system commands output documented in this readme

## 8 commit details
commit message: document operating system and file management
