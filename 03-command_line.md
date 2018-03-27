# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path		
pwd
* creating a directory		
mkdir
* deleting a directory		
rm -r
* creating a file using `touch` command       
touch love.txt
* deleting a file      
rm
* renaming a file      
mv old-filename new-filename
* listing hidden files      
bls -a
* copying a file from one directory to another      
  cp source dest

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  


---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
list all the files
`ls -a`   includes hidden ones
`ls -l`   in long form
`ls -lh`  shows sizes in human readable format
`ls -lah`  includes hidden ones
`ls -t`  Sort with the primary key being time modified
`ls -Glp`  
in a long listing, don't print group names
list one file per line
append / indicator to directories



---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

-a	Displays all files.
-l  use a long listing format
-al
ls-lh shows sizes in human readable format
-d	Displays only directories.
du -sh show size of one file/dirctionary


---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > build and execute commands from standard input. It converts input from standard input into arguments to a command.

Some commands such as grep and awk can take input either as command-line arguments or from the standard input. 

However, others such as cp and echo can only take input as arguments, which is why xargs is necessary.

 

