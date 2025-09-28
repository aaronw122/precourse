QUESTIONS

## What are the top 20 commands for mac Command Line Interface (CLI)?
1. cd- change directory. 'cd “path/to/directory/”'
2. ls - listing directory. view contents inside current directory. 
3. open - open files. 'open "filename"'
4. cp - copy file to another directory. cp “filename” “newfilename”
5. mv - move a file. mv “filename” “path/to/new/file/location”
6. touch - create a text file. touch myfile.txt
7. mkdir - create directory. mkdir “path/to/new/directory”
8. rmdir - remove an empty directory. 
9. rm - remove directories with files inside. rm -R “/path/to/root/directory”
10. sudo - execute commands with superuser privileges. (required for some commands) sudo “command”
11. top - lists actively running comptuer processes. 'top'
12. q - quit sub screen, return to terminal
13. clear - clears screen of all previous commands
14. ditto - copy contents of a folder to a new folder
15. whatis - one line description for a command. "whatis mkdir"
16. man - show more info on command. "man mkdir"
17. exit - closes out session in terminal
18. shortcuts run - apple shortcut workflow, skip on opening app. 
19. tmutil startbackiup - backup with time machine. 
20. killall AppName - force quitting apps. i.e. when xcode simulator won't close





## What is the difference between bash and zsh?
- shells are just a way to interact with the command line environment. 
- overtime shells improved with new shortcuts, etc.

bash- default shell on UNIX(MacOS) and Linux
zsh - newer popular shell from 1990 - all features you find in bash, plus more, better completion. bash compatible.


## What is a terminal? A CLI? Why are they synonymous?
CLI and terminal are very closely related.
- terminal: the environmment that emulates a console.
- CLI: interface where you type a commands into.

they are synonymous because CLI is the specific line that you are typing on inside terminal. 

## What is the difference between Terminal, Console, Shell, and Command Line?

terminal: the environmment that emulates a console. 
CLI: interface where you type a commands into.
console: physical terminal. appears to the operating system as a terminal.
shell: command line interpreter. program invoked when you login. never sees output of commands it runs. asks kernel to do work. 
