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

> > pwd, mkdir dirname, rm -r, touch filename, rm filname.ext, mv file1 file2, ls -A, cp filename new_directory_name

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

> > 'ls' lists all the files in the current directory

> > 'ls -a' displays all files, including hidden giles

> > 'ls -l' displays the files in long format listing, with permissions

> > 'ls -lh' lists the long format in a readable file size

> > 'ls -lah' does long format listing for all entries in a readable size

> > 'ls -t' lists the files with the newest first

> > 'ls -Glp' color codes the output of entries printed in long format without owner info

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > 'ls -R' displays subdirectories

> > 'ls -u' gives files by access time

> > 'ls -x' gives files as rows across the sreen

> > 'ls -laR'

> > 'ls -m'

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > xargs reads the data from standard inputs and performs commands given by arguments

> > 'echo 'hi' | xargs mkdir' creates a folder named hi in the directory

 

