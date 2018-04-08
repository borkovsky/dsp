# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> >
pwd
mkdir
rm -r (remove recursively, vs. rm X to remove a file X)
touch data.txt (creates a new file inside a working directory)
rm
mv
ls -a
cp
alias
grep
sed

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`
`ls -Glp`  

> > 
ls: lists files in the working directory 
ls -a: lists **all** files in the working directory, including hidden ones
ls -l: lists contents of a directory in long format 
ls -lh: list contents of a directory with unit suffixes (Byte, Kilobyte, Megabyte, Gigabyte, Terabyte and Petabyte)
ls -lah: lists all files in the working directory, including hidden ones, in long format, 
ls -t: orders files and directories by the time they were last modified.  
ls -Glp: list all lcontents of a directory in long format, plus write a slash ( '/' ) after and colorize each filename if that file is a directory

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > 
ls -R: also displays subdirectories
ls -u: displays files by the file access tie
ls -g: displays the long format, but without the owner's name
ls -d: displays only directories
ls -m: displays files as comma separated values

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> >
Xargs is useful for building and executing command lines from standard input. For example, you can use them to find something the directories by combining `find` to search for files or directories and then use xargs to operate on the results.


 

