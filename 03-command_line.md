# Learn command line

Please follow and complete the free online [Command Line Crash Course
tutorial](https://web.archive.org/web/20160708171659/http://cli.learncodethehardway.org/book/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. Each "chapter" focuses on a command. Type the commands you see in the _Do This_ section, and read the _You Learned This_ section. Move on to the next chapter. You should be able to go through these in a couple of hours.

---

###Q1.  Cheat Sheet of Commands  

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do, focused on things that are new, interesting, or otherwise worth remembering.

> > REPLACE THIS TEXT WITH YOUR RESPONSE

---

###Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> > 'ls': list of the file and folders
'ls -a': list of the files and folders and plus the hidden files and folders
'ls -l': from left to write: file Type, file permissions, number of links, owner name, owner group. file size time of the last change, the name of the file or folder.
'ls -lh': same as 'ls -l' but print he file size in a MB... format.
'ls -lah': same as 'ls -lh' but includes hidden files;
'ls -t': sort files and folders by time.
'ls -Glp': high light the folders.  

---

###Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > ls -1; ls -1lG; ls -m; ls -f; ls -fG;

---

###Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > It apply an operation to a set of folder or files.
For instance with the following command we can print a hello to the beginning of each files as being printed on the screen.  ls -1 | xargs -n 1 echo 'Hello'
