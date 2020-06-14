# Choosing a Text Editor

Anything that allows a user to type is a text editor, such as word processors and even simple pre-installed programs like Wordpad. But when it comes to coding, a developer will want to look for one that has these features, according to [The Older Coder](https://codefellows.github.io/code-102-guide/curriculum/class-02/Choosing-A-Text-Editor--The-Older-Coder.pdf):
1. ) code completion; 
2. ) syntax highlighting; 
3. ) a variety of themes (to reduce eye strain and fatigue); and 
4. ) extensions (one recommended extension is called **Emmet** which is shorthand and helps with code completion).

There are many text editors to choose from and which to use is often a matter of preference. In this class we'll use VS Code.

An **IDE, or Integrated Development Environment**, will include a text editor as well as a file manager, compiler and debugger. VS Code is not considered an IDE.

# Using a Terminal

A terminal is a command line interface. It reminds me of the old days of DOS, where everything you want to do on the computer has to be typed in as a command, no point and click in a GUI!

   ### The Command Line

Commands are entered at the prompt, followed by a space and then options and arguments.

Options typically start with a dash.

Bash in Unix is an example of a terminal shell. {Honestly I have no idea what this means but it's what I wrote in my notes.}

   ### Basic Navigation

You can navigate to a particular location by using paths. Paths can be referred to using either **absolute** reference to the root directory, or **relative** reference to the working directory.

The root directory is denoted by /

Absolute paths always begin with / but relative paths do not.

The pwd command is useful for figuring where you are if you get lost.

   ### About Files

In Unix, *everything* is a file, including files, folders, keyboard, monitor, you name it. In this OS, file extensions don't really have meaning and are not required but can be used. Unix figures out what type of file it is by looking at its contents, not at an extension. Also, everything is case sensitive so you can end up with different files just by changing the case of a letter. 
 Be careful!
 
*Hidden files* begin with .

# “Cheat sheet” for basic terminal usage:
command | description
--- | ---
| cd [name] | change the directory |
cd .. | go up one level in the directory
ls [options] [location] | lists the items in a directory
ls -l | long listing
ls /directoryname | lists the items in the directory called directoryname
ls -a | lists hidden files as well as others
mkdir | makes a directory (a folder)
rmdir | removes a directory
rm -R | removes nested directories
file [path] | I forget what this does, didn't take good notes
touch [filename.extension] | create a file
pwd | print working directory
~ | shortcut for the home directory
. | shortcut for the current directory
.. | shortcut for the 'parent' directory
../../ | shortcut for the 'grandparent' directory (etc. use as many as needed)
code .  opens VS Code editor
open [filename] | opens a file
cp [olddir/oldfile] [newdir/newfile]  | copies a file to a new location
mv [filename] [path/to/new/file/location] | moves a file; can also be used for renaming a file
clear | Clear the Terminal screen of all previous commands
help [command] | Get help for a command

Up and down arrows cycle through the last commands to help reduce typing them each time.

\ is an escape character that nullifies the meaning of the following character. You could use this, for example, to have the terminal ignore a space in a filename.

[Here](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/cd) is a list of other commands for Windows.

