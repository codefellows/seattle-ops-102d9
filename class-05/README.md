# Installing Virtualbox with Linux Terminal 

## Overview

In order to effectively utilize Ubuntu Linux as a virtualization server, you'll need to get comfortable using the Linux terminal. While many operations can be performed using the desktop graphical user interface (GUI), basic Linux terminal skills are generally expected of Ops professionals.

## Learning Objectives

### Students will be able to

#### Describe and Define

- Terminal
- Basic Linux terminal navigation commands
- APT

#### Execute

- Perform basic navigation in terminal.
- Manage software packages using the APT package manager.
- Use APT to install Virtualbox and its Extension pack.
- View system specs in terminal.

## Resources

- [Linux command line for beginner](https://ubuntu.com/tutorials/command-line-for-beginners#1-overview){:target="_blank"}
- [Linux Commands for Linux Beginners](https://www.howtouselinux.com/post/linux-commands-for-linux-beginners-cheat-sheet){:target="_blank"}
- [Advanced package tool for Linux](https://www.poftut.com/what-is-apt-advanced-package-tool-for-linux/){:target="_blank"}
- [How to Install Virtualbox on Ubuntu](https://itsfoss.com/install-virtualbox-ubuntu/){:target="_blank"}

## Notes

1. Linux Commands
    - `CTRL+C`
      - is used to break out of a running process or terminate a command.
      - It provides a quick and convenient way to stop a process that might be taking longer than expected.
    - `pwd`
      - stands for "print working directory" and displays the current location in your file system.
      - It is helpful for knowing where you are within the directory structure.
    - `ls`
      - lists the files and directories contained in the current directory.
    - `ls -al`
      - provides more detailed information about the files, such as permissions, ownership, and file sizes.
    - `cd [path]`
      - used to change the directory you are currently in.
      - By specifying the desired path, you can navigate to different directories within the file system.
    - `mkdir [dirname]`
      - used to create a new directory.
      - By specifying a directory name after the command, you can quickly create a new folder.
    - `touch [file name]`
      - is used to create a new file.
      - By specifying a file name after the command, you can create an empty file with that name.
    - `sudo [command]`
      - is used to elevate your command to root or superuser privileges.
      - After entering the sudo command, you will be prompted to enter the root password to execute the command with elevated privileges.
    - `[command name] -[modifier/flag parameter] [target/action parameter]`
      - This is the general syntax for performing an action with a command in the Linux terminal.
      - You can use various commands with specific flags or modifiers to perform different actions on specific targets.