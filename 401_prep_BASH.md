# Code 401 Prepwork - Linux CLI notes

## The Command Line

The CLI is an alternative to the GUI for accessing files and performing operations on your computer.

Commands are typed into an interface within the terminal known as the shell. There are many different shells that you can choose from - in this tutorial the shell is BASH but we are taught to install zsh in class.

## Basic navigation

One of the most common uses of a CLI is for simply navigating through your file system.

The command **pwd** tells you which directory you are currently in.

The command **ls** tells you what files or other directories can be accessed from your current working directory.

The command **cd** lets you change the working directory.

### Relative path tips

**~** is the symbol for home directory.
**.** refers to the current working directory.
**..** refers to the parent directory.

## More about files

Everything is a file.

Linux is extensionless - instead of relying on extensions to tell it file types, it just examines the files itself and determines their types.

Linux is case sensitive - be careful about this with file naming.

For file names that have spaces - either the whole name needs to be in quotes or the space needs to be escaped.

## Manual pages

Use the command **man** **\<command to look up>** to find information about different commands.

You can also do a keyword search by adding the **-k** option to the command.

## File manipulation

Use **mkdir** to make a new directory. Use it with the **p** option to ensure necessary parent directories are created.

USe **rmdir** to delete a directory.

We can use **touch** to create a new file - note that this is a side effect of the command, not its main functionality.

Use **cp** to copy a file or directory.
You need to specify both the source and destination paths.
To copy a directory and all of its contents, you need to specify the the **r** option (for recursive).

You can use **mv** to move a file or directory in a similar manner to the copy command, but you don't need to use the **r** option.
You can use **mv** to rename a file by simply specifying the destination as the same path as the source but with a different file name.

Use the **rm** command to delete a file, use it with the **r** option to delete a directory with all its contents. Pair this with the **i** option to get a prompt for deleting each file in the directory.

## [Cheatsheet](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)

