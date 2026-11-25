# mission 3 - operating systems processes paths and permissions

## task and objective
explore operating system environment running processes storage paths and file permissions and explain os responsibilities

## work completed
- inspected os version active account disk space and system uptime
- viewed process list identified pid column and examples of running applications
- navigated between mission folder and evidence subfolder comparing absolute and relative paths
- inspected file permissions on practice file
- documented six core os responsibilities

observations are in evidence/system-inspection.md and table is in os-responsibilities.md

## commands and tools used
uname whoami df uptime ps pwd cd ls

## understanding
operating system manages computer resources such as cpu memory disk and devices
processes are active programs identified by unique pid numbers
absolute paths start from root / while relative paths start from working directory
permission letters r w x show read write and execute rights for owner group and others

## difficulties and how resolved
file permissions: reading `rwx` letters in `ls -l` was confusing at first, resolved by splitting them into owner, group, and others
PROCESS list: finding specific apps in `ps` output took time, reolved by checking the pid and command columns carefully

## evidence and files
- [system inspection evidence](evidence/system-inspection.md)
- [os responsibilities table](os-responsibilities.md)
- [practice file inspected](../terminal-practice/notes.txt)

## commit details
- commit message: complete os and file permisions mission
- published branch: main
