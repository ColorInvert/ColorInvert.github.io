# Bash, and the command line


Bash is the command line language used for linux systems, which at large, allows you to create/modify/delete files and directories, install and uninstall programs, run programs and applications, all with only a text line interface as opposed to any form of GUI like a modern desktop. Below I describe the three most important navigational commands.

#### PWD
Print Working Directory. Upon typing this command and hitting enter, the command line will respond with the directory you are currently located in. Without a GUI to assist, it can be hard to know exactly where you are, so this, combined with the two commands below are vital for successful navigation of your filesystem.

#### LS

LiSt. provides you with a list of all of the folders and files present in the directory you are in.(Your working directory, as mentioned above) Vital for figuring out where to go next from where you are currently.

#### CD
Change Directory. This command accepts arguments, and allows you to navigate your working directory (where you are) to another location. if ls gave the response of `myprojects   games` and you wanted to navigate to `myprojects` then your command would be `cd myprojects` To back out of the `myprojects` directory, you can use `cd ..` to go up one level, which would bring you back to where you started.


### A few interesting quirks of Linux, and other things I have noticed while reading tutorials

>Literally everything on linux, including your hardware such as your keyboard, mouse and monitor, are files. In addition to this, file extensions do not exist. Any file extensions included will be ignored by the system, as it instead opts to look inside the file to determine what variety it is instead.

>ls will not show you everything by default, as linux does use hidden files. providing the optional argument `ls -a` (LiSt -All) will make list show hidden files in addition to the non hidden ones.

>Linux has a built in manual! the `man` (MANual) command, with an argument in the form of another command will provide you with a response telling you what the command is used for.

>- [A link to Ryanstutorials cheat sheet for further reading](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)

#### [Back To Main Page.](https://colorinvert.github.io/reading-notes/)