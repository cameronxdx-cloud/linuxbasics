# Chapter 1 Notes 

# Getting Started:
- Installed Git - Git is a tool that helps you keep track of changes in your files and collaborate with others on projects. It saves different versions of your files so you can go back to an earlier version if needed, and it allows multiple people to work on the same project without overwriting each other’s work
- Created linuxbasic directory on local machine (mkdir)
- Created linuxbasics repo in github
- Ran these commands:
    - git init #this initializing the folder
    - git add .  #this adds all contents in that folder
    - git commit -m "inital commit" #adds all files to branch
    - git branch -M main #this sets the branch name
    - git remote add origin https://gitgub.com/cameronxdx/(example.git)  #adds a remote called origin to the remote repo url specified
    - git pull https://github.com/cameronxdx-cloud/azure-cloud-resume-challenge.git main --allow-unrelated-histories (only add if they are unrelated
    - git push -u origin main #this pushes to the branch
- Deployed Kalilinux VM


# Terms:
* Binaries - files that can executed residing in the /usr/bin or usr/sbin directory that allows you to run programs and commands
    - ps 
    - cat 
    - ls 
    - ifconfig
* Case sensitivity - always lower case 
* Directory - Organization of folder/files structures
* root - administrator/superuser
* Script - commands run by interpreters like Python, converting each line to source code, and are commonly used in hacking tools
* Shell - is the command line interpreter that interprets the comand line input and instructs the operation system perform any tasks
* Kernel - controls the hardware to interact with applications
* Distros - is a collection of programs combined with the linux kernel to make up a Linux-based operating system 
* Boot Loader - is a program that boots the operating system. Ex: GRUB and ISOLINUX
* Service - is a program that runs as a backupground process 


# Filesystem Structure:
![alt text](image.png)
- /root The home directory of the all-powerful root user
- /etc Generally contains the Linux configuration files—files that control when and how programs start up
- /home The user’s home directory
- /mnt Where other filesystems are attached or mounted to the
filesystem
- /media Where CDs and USB devices are usually attached or mounted
to the filesystem
- /bin Where application binaries (the equivalent of executables in
Microsoft Windows or applications in macOS) reside
- /lib Where you’ll find libraries (shared programs that are similar to
Windows DLLs)

# Basic Linux Commands:
- pwd - print working directory returns your location within the directory structures
- whoami - displays the username of the current user
- cd change directory
- cd .. goes back a directory 
    - You would use .. to move up one level.
    - You would use ../.. to move up two levels.
    - You would use ../../.. to move up three levels, and so on.
- ls list contents of a directory 
- ls -l long listing with more information on about the files and directories such as permissions, file size, and last modified 
- ls -la Some files in Linux are hidden and won’t be revealed by a simple ls or
ls -l command. To show hidden files, add a lowercase –a
- --help, -h, -? Nearly every command, application, or utility has a dedicated help file in
Linux that provides guidance for its use. many applications support all 3, there’s no guarantee the application you’re using will 
- man A manual for most applications by typing before the command to provide with more information of the command or application 
- locate (application) this will go through your entire
filesystem and locate every occurrence of that word.
- whereis (application) locating binary files 
- which only returns the location of the binaries in the 'path' varaiable in Linux
- 'Path' holds the directories in which the operating system looks for the commands you execute at the command line
- find basic syntax directory options expression. kali >find / -type f -name apache2. First I state the directory in which to start the search, in this case / .
Then I specify which type of file to search for, in this case f for an ordi-
nary file . Last, I give the name of the file I’m searching for, in this case
apache2 w.
