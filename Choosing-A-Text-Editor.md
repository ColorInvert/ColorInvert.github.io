# Choosing a text editor



##### While picking a text editor may seem like a daunting task, it ultimately boils down to personal preference, as many text editors intended for coding share many features with each other.


A few of the things that a code-focused text editor will tend to provide you with include:

- Some degree of automated formatting, such as automatic indentation for nested commands, creating brackets, commas, and parentheses for you, and other such things.
- Context-aware color highlighting of text, which is known as **Syntax Highlighting** where certain types of segments of your code, such as integers, or variables, or arguments are given their own color coding, to make them identifiable at a glance.
- Color customization, and font size/choice options for the editor itself, which are often called **Themes** including glorious, eye-strain-relieving **darkmode.**
- Support for **Extensions** which are additional modifications to the text editor that you can apply for added features and assists, depeding on the type of work you do, or what languages you tend to work in.

Computers also come with a text editor, but it's generally not recommended to use those for the sake of programming. You will be missing out on all of the features listed above, and the editor itself will not make any attempts to assist you or recognize and autofill commands.

A Text Editor is different from an **Integrated Development Environment.** (IDE) An IDE has features for file management, debugging, and compiling, so IDEs are recommended only if you know precisely what you will be working, and deploying, in terms of language and final product.

The Git editor for assembling markdown pages on-site is in itself a text editor as well, albiet a rather rudimentary one.



## On Terminal Navigation

#### This is a brief cheat sheet for navigating via the terminal

- `cd` Short for **change directory.** Your main tool for filesystem navigation. using `cd` alone with no arguements will always return you to your home directory, or **root**. Navigation to other directories can be done a number of ways, but I prefer to simply use `cd directoryname` to move one step at a time. Slower, but keeps me aware of where I am at any given moment. Navigation can be done with relative directory navigation (as above) or absolute, where you instead type `cd /home/user/documents` to specify a precise folder.

- `pwd` Short for **print working directory.** Will show you the current folder in which you are located.

- `ls` Short for **List.** Will display the full list of contents of the directory in which you are currently in. Can accept arguments, like `ls -l` which will create a more verbose and detailed listing of your directory, highlighting filetype, creation date, and more. the arguement `/directoryname` will provide a list of all contents of the listed directory. `ls -l /directoryname` will do both, providing a verbose list of all contents.

#### additional cd tricks

- `~` is a shortcut for your home directory, so `cd ~` will take you there. `cd` with zero arguments does that too though.
- `.` is a shortcut for "current directory." so if you're in the directory "files" and you want to transfer to the deeper directory "documents" `cd ./documents` will work.
- `..` is a shortcut for "parent directory." or in other words, "Above by one level." `cd ../` will take you out of your current folder, and bring you one step closer to your root directory.

## On Linux and Files.

#### Everything in Linux is a file.

#### Everything in Linux is Case Sensitive.
a file called `text` and a file called `Text` are regarded as different, and if you do a command that includes improper capitalization, then the command will fail.

also:

#### File Extensions Do Not Exist

You can have file extensions in the names, but the data for what linux treats the file as is embedded in the file itself. Changing a written extension on the file will not actually change the file in any capacity apart from it being named differently now.

#### Handling Spaces

If a directory has a space in it, then doing `cd cool essays` will return the error that the directory "cool" does not exist. this can be worked around by adding `"` around the name of the directory, like so: `cd "cool essays"`

### [Back To Main Page.](https://colorinvert.github.io/reading-notes/)
