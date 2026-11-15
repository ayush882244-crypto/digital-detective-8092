# mission 2 - become comfortable with the terminal

## 1 task / objective
learn basic terminal commands navigate directories manage practice files and understand flags pipes and package managers

## 2 work completed
practiced navigation and file commands in terminal
created terminal-practice folder and edited text files
compared directory listing flags and used command piping
checked package manager version

## 3 commands / tools used
- pwd: print working directory
- ls: list directory contents
- cd: change directory
- mkdir: create directory
- touch: create empty file
- cp: copy file
- mv: move or rename file
- cat: display file content
- head: display first few lines of input
- brew: macos package manager

## 4 my understanding

### task 2.1 - basic terminal operations
| operation / command name | what it does | what i observed |
| --- | --- | --- |
| current-directory display (pwd) | shows full path of working folder | printed full path of repository folder |
| directory listing (ls) | lists files and folders | printed names of folders and files |
| detailed listing (ls -l) | lists files with permissions sizes and dates | showed columns of permissions sizes and timestamps |
| change directory (cd ..) | moves to parent directory | path changed to parent folder |
| create directory (mkdir) | creates a new folder | new directory appeared in folder listing |
| create empty file (touch) | creates a blank file | empty file created with 0 bytes |
| copy file (cp) | makes a duplicate of file | second file created with same contents |
| move / rename file (mv) | moves or renames file | file renamed to new name |
| display file contents (cat) | prints file content to terminal | contents of text file printed in terminal |

### task 2.2 - safe file changes
questions answered:
- difference between replacing a file's contents and adding text to the end:
  replacing with > overwrites the entire file while adding with >> appends text to the end without deleting old content
- difference between copying a file and moving a file:
  copying makes a duplicate and keeps original file while moving renames or moves file without keeping original copy
- what information does the current-directory display provide:
  it provides the exact complete path from root to current working directory
- why is a directory-listing operation useful:
  it allows you to see all files and folders present before making changes

### task 2.3 - flags and pipes
- normal listing vs flags:
  ls only shows names of visible files while ls -lah shows hidden files starting with dot permissions human readable sizes and timestamps
- pipes:
  command used: ls -la | head -n 5
  the pipe symbol takes output from the left command and sends it as input to the right command
  left command generates detailed file list and right command filters it to show only top 5 lines

### task 2.4 - package managers
package managers automate installing updating and removing software from command line
they resolve dependencies automatically so users do not need manual installers
homebrew version 7.0.10 is installed on this mac

## 5 difficulties faced
understanding the difference between overwriting with > and appending with >>

## 6 how i resolved them
tested both in terminal-practice folder and verified with cat

## 7 evidence / files
- terminal-practice/practice.txt
- terminal-practice/practice_renamed.txt

## 8 commit details
commit message: complete terminal and file management mission
