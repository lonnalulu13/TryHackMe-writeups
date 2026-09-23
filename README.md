# TryHackMe-writeups
Linux Fundamentals part1
**Platform**: [TryHackMe](https://tryhackme.com/room/linuxfundamentalspart1)  
**Difficulty**: Info  
**Completed**: September 22, 2026  

## Skills Practiced
- Basic Linux navigation
- File system exploration using the terminal
- Searching for files and content
- Understanding special character operators
## Tools / Commands Used
- `whoami` – shows the current user
- `echo` – prints text to the terminal
- `ls` – lists files and directories
- `cd` – changes directory
- `cat` – displays file contents
- `pwd` – prints the current working directory
- `find` – searches for files by name
- `grep` – searches for text inside files

## Walkthrough / Notes

### Navigation Basics
- `whoami` → tells you which user you are logged in as
- `pwd` → shows your current location in the file system
- `ls` → lists the contents of the current directory
- `cd foldername` → moves into a directory
- `cd ..` → moves up one directory
### Viewing Files
- `cat filename` → displays the contents of a file
- You can also combine commands:  
  `cd folder1 && cat filename`

### Searching
- `find . -name "filename"` → searches for a file by name starting from the current directory
- `grep "text" filename` → searches for specific text inside a file

## Key Takeaways
In this room I learned the essential Linux commands needed to navigate the file system, view files, and search for information using the terminal. These are fundamental skills for any cybersecurity role that involves working with Linux systems.

## Disclaimer
This write-up is for educational purposes only. All work was completed in the official TryHackMe lab environment.
