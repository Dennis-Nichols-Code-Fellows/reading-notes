# Class 2 - The Coder's Computer

These notes cover an introduction to **text editors** and **the command line interface (CLI)**.

## [Choosing a text editor](https://codefellows.github.io/code-102-guide/curriculum/class-02/Choosing-A-Text-Editor--The-Older-Coder.pdf)

In this article by 'The Older Coder' on *Medium* the author lays out some ideas for how to choose between different text editors.

The first and perhaps main point is that **the best text editor is the one you are most comfortable using** while still being able to perform all required tasks.

Important features in a text editor:

1. Code completion -> auto closing of tags, html/css shorthand, etc.
2. Syntax highlighting -> allows one to distinguish elements of a language like html from the content itself, improves legibility.
3. Variety of themes (such as 'dark' themes to give your eyes a break)
4. Includes a healthy library of extensions -> additional software that can make the editor more powerful down the road.

## The Command Line Interface (CLI)

### Basic Reading Notes

[The Command Line](https://ryanstutorials.net/linuxtutorial/commandline.php)

- The CLI (also called the terminal) is a powerful alternative to a GUI
- Both input and output are text-based
- Different OSs have different means of accessing the CLI
- The window interface represents the terminal to you is called the *shell*
- A popular shell is called *Bash*
- Article ends with pointing out that there are shortcuts available to make the CLI more easy to navigate.

[Basic Navigation](https://ryanstutorials.net/linuxtutorial/navigation.php)

- Covers basic commands for navigating through your computer's file structure using the CLI (more detail in the cheatsheet).
- Additional options for some commands (such as ls) are discussed
- Filepaths (absolute and relative) are explained

Key concepts:
**Relative path** A file or directory location relative to where we currently are in the file system.
**Absolute path** A file or directory location in relation to the root of the file system.

[About Files](https://ryanstutorials.net/linuxtutorial/aboutfiles.php)

- Within linux, everything is a file.
- Linux is *extentionless*. Instead of using extensions to determine file types, it just looks inside.
- Linux is case sensitive.
- File names with spaces in between need to be quoted or include escape characters (\).

### CLI cheatsheet

1. `pwd` -> print working directory -> the 'you are here' command

2. `ls` -> 'lists' the files and other directories within the current directory.

3. `cd` -> change directory -> move from one folder to the next, or several folders away with modifications to the command.
