# Practice in the terminal

## The Command Line

In this lesson we learned more commands to use in our terminal. So far I haven't used any options with `ls`. It was interesting to see that you could expand upon the simple `ls` command. We also learned how to find which shell we are using in our terminal. I am currently running zsh.

## Basic Navigation

The start of this lesson was a refresher on the simple commands `pwd` which shows where you are in the terminal and `ls` which shows you what is in the current directory you are in. We then moved to learn a few other options and arguments you can add behind these commands. The next part of this lesson regarded paths.

There are 2 types of paths: Absolute and Relative. Absolute paths specify a location (file or directory) in relation to the root directory. You can identify them easily as they always begin with a forward slash ( / ). Relative paths specify a location (file or directory) in relation to where we currently are in the system. They will not begin with a slash.

There are also shortcuts you can use with paths, as mentioned from the lesson:

- `~` (tilde) - This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents
- `.` (dot) - This is a reference to your current directory. eg in the example above we referred to Documents on line 4 with a relative path. It could also be written as ./Documents (Normally this extra bit is not required but in later sections we will see where it comes in handy).
- `..` (dotdot)- This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory.

Finally we learned some shortcuts on navigating through directories which should make moving through my reading notes and lab directories a bit easier. 

## More About Files

A lot of this lesson was review for me. It covered file extensions and how file names are case sensative. One thing I didn't realize was how to handle file names with spaces in terminal. Single quotes are used for anything with spaces in the name as well as using a backslash as an escape character. Also the lesson showed us using `-a` to locate hidden files.

## Manual Pages

This lesson we learned about manual pages. Manual pages are a set of pages that explain every command available on your system including what they do, the specifics of how you run them and what command line arguments they accept. You can also use the `man -k` to searach for a given term.

## File Manipulation

This lesson was also a decent bit of review. It covered `mkdir` which makes a directory. However, the lesson then showed `mkdir -p` which will make parent directories as needed. `rmdir` can be used to remove a directory. Also creating a blank file was covered using `touch`. Then we were instructed on how to copy a file  or directory using `cp`, moving a file or directory using `mv`, renaming files and directories using `mv` by moving a file/directory and renaming, and how to use `rm -r` to remove non-empty directories.

## Cheat Sheet

The following link is a cheat sheet for Linux commands.

[Cheat Sheet](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)

[Back to Home](../README.md)
