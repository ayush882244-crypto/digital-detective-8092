# mission 2 - cli practice evidence

this is a sanitized record of commands run in terminal-practice folder

## task 2.1 - inspect and manage files

| command | purpose | observed result |
| --- | --- | --- |
| pwd | print current full path | printed repository working path |
| ls | list entries in current folder | showed files and directories |
| ls -l | show detailed listing | showed permissions sizes and dates |
| cd .. then pwd | move to parent directory | path changed to parent folder |
| mkdir -p terminal-practice/task-2-1 | create practice subfolder | folder created |
| touch terminal-practice/task-2-1/empty.txt | create empty text file | file created with 0 bytes |
| cp terminal-practice/task-2-1/empty.txt terminal-practice/task-2-1/copied.txt | copy file | duplicate file created |
| mv terminal-practice/task-2-1/copied.txt terminal-practice/task-2-1/renamed.txt | rename copied file | renamed to renamed.txt |
| cat terminal-practice/task-2-1/empty.txt | display original file content | no text printed 0 bytes verified |

## task 2.2 - replace append copy and rename
commands run:
printf 'first line: input is processed\n' > notes.txt
printf 'second line: output is displayed\n' >> notes.txt
cat notes.txt
cp notes.txt notes-backup.txt
mv notes-backup.txt notes-archive.txt

cat notes.txt showed both lines:
first line: input is processed
second line: output is displayed

## task 2.3 - listings and a pipe
created .hidden-demo.txt
ls did not show .hidden-demo.txt
ls -lah displayed hidden files with human readable sizes
command used: ls -lah | head -n 5
pipe sent listing output to head which restricted display to first 5 lines

## task 2.4 - package manager
checked homebrew:
brew --version returned homebrew 7.0.10
homebrew automates installing command line tools and handling dependencies
