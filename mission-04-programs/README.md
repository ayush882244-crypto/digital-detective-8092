# mission 4 - how programs run

## 1 task / objective
create and run a python program and compare how compilers and interpreters execute code

## 2 work completed
created hello.py file and ran it using python 3
completed compiler vs interpreter comparison table
wrote short explanation comparing compilers and interpreters

## 3 commands / tools used
- python3 hello.py: execute python program in terminal

## 4 my understanding

### task 4.1 - python program execution
created hello.py containing print("hello from python")
terminal output confirmed: hello from python

### task 4.2 - compiler vs interpreter comparison
| point | compiler | interpreter |
| --- | --- | --- |
| when translation / execution happens | translates entire source code before running | translates and runs code line by line at runtime |
| typical output | executable binary machine code file | direct execution output on screen |
| one example | c or c++ | python |
| one advantage | runs faster once compiled | easier debugging and testing without rebuild step |

explanation:
a compiler translates the whole program into machine code before running while an interpreter reads and runs code line by line
compiled code executes faster because it is already machine code but needs a build step
interpreted code is easy to test quickly because you do not need to compile before running
python is an interpreted language that runs code directly through the python interpreter

## 5 difficulties faced
understanding whether python uses compiler or interpreter

## 6 how i resolved them
learned that python converts code into bytecode and runs it with an interpreter

## 7 evidence / files
- mission-04-programs/hello.py

## 8 commit details
commit message: compare compilers and interpreters
