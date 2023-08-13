# Linux practice project

## Table of content
- Objective of the project
- Instructions to follow
- Implementation of the commands  
- Summary


The purpose of this project is to familiarize self with the various commands used in Linux for freshers.

## Instructions to follow to complete this project

  - Have a virtual box machine installed in your computer
  - Have a Linux account

# Implementation

## Sudo command: 
Sudo represents either 'substitute user do' or 'super user do' which allows one to have root priviledges. to explain futher, this command allows the current user to conitinue using their account but with root priviledges. There are some certain commands or software download that as a standard user, one cannot install such applications on linux machine because it is set set by default. This is where sudo command comes in. When using sudo command, it will request for authentication from the user which is the user's password.

   <p>How to run sudo command:

   - Using the syntax 'sudo apt upgrade'

   - The output is as in the link

   https://github.com/Ijfine/darey.io-projects/blob/main/sudo.jpg

   

## pwd command: 
This is the command that shows the full path of current/working directory. It writes to standard output of the full path name of users current directory. It has two arguments as follows:
- -L or --logical - prints symlinks.
- -P or --physical - displays physical directory without any symlinks.

It uses the syntax "pwd"

The output becomes as in the links below:

https://github.com/Ijfine/darey.io-projects/blob/main/pwd.jpg

https://github.com/Ijfine/darey.io-projects/blob/main/pwd%20(2).jpg



## cd command: 
This command is used to change from the current directory to different directories in the system. 

The syntax used is "cd (file name)" 

See below link for the output 

https://github.com/Ijfine/darey.io-projects/blob/main/cd.jpg


## ls command: 
This command is used to list the contents inside a directory. It has options such as: 
  - -R - gives a recursive listing which includes the contents of all subdirectories.
  - -a - lists all files including hidden files.
  - -lh - lists files in an easy readable format.
  - -t - lists files in order of the time when they were last modified.

  Examples on how to use the command is in the links below:

  https://github.com/Ijfine/darey.io-projects/blob/main/ls.jpg

  https://github.com/Ijfine/darey.io-projects/blob/main/ls%202.jpg

  

  ## locate command: 
  This is the command one can use to find a file or directory. Most of the linux system do not have locate command so if it is not on your linux system, install it first before you can use it.

  The syntax for the command is:

  locate *filename

  The output becomes

https://github.com/Ijfine/darey.io-projects/blob/main/locate.jpg





 ## grep command: 
 This command searches a file for a particular pattern of characters, and shows all the lines that contain that pattern.

 The syntax to use:

 *grep character filename*

 For example, I used grep work sound

 sound is the file name while work is 
 the pattern I want to find.
 
Below link shows the output of the command

https://github.com/Ijfine/darey.io-projects/blob/main/grep.jpg


## ping command: 
ping is a command used to test the connectivity and reachability of a host on an internet server. 

To check if I can reach bing.com on my linux system, I used the syntax *ping bing.com*. Find the output in the below link.

https://github.com/Ijfine/darey.io-projects/blob/main/ping.jpg


## wget command: 
This is a cooamnd that makes it possible to download files from the internet. It is non-interactive which means it can work inbackground when the user is not logged in. It supports the HTTP, HTTPS, FTP and FTPS internet protocols.

To use it, I entered (*wget https://wordpress.org/latest.zip*)

The outcome is as in the below link

https://github.com/Ijfine/darey.io-projects/blob/main/wget.jpg



## man command:
man command is used to show the user manual of any command that can be run on the terminal. It includes a command description, applicable options, flags, examples and other informative sections.

To use it, simply type '*man the command*' For example, *man ls* (ls been the command)

Find in the below link the output 

 https://github.com/Ijfine/darey.io-projects/blob/main/man.jpg

 
## alias command
This command is used to provide a string value that replaces a command name. It lets you create shortcuts for long commands, which makes it easier to remember and use. 

- To create a shortcut for *ls*, I used syntax *alias l='ls'*

- To delete the created shorcut or to unalias it, I used *unalias -a ls*

Below link shows the outcome of the command

https://github.com/Ijfine/darey.io-projects/blob/main/alias.jpg
     


## Summary
Linux includes a large number of commands which are very essential to learn as a beginner. Once you learn all the Linux commands, it works the same in all Linux distribution.