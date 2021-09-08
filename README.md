# Bash Cheatsheet

__ls__ -- __List directory contents__
> The __ls__ command allows you to quickly view all files wiithin the specified directory.
* Syntax: ls [option(s)] [file(s)]
* Common options: -a, -l
---
__touch__ -- __Creates a file__
> __touch__ is the easiest way to create new file(s), it can also be used to change timestamps on files and/or directories. With __touch__ you can create as many files as you want in a single command.
* Syntax: __touch__ [option(s)] file_name(s)
* Common options: -a, -m, -r, -d
---
__mkdir__ -- __Create a directory__
> __mkdir__ is used to create directories, any number of directories can be created simultaneously which can speed up the process.
* Syntax: __mkdir__ [option(s)] directory_name(s)
* Common options: -m, -p, -v
---
__pwd__ -- __Print working directory__
> __pwd__ is used to print the current directory you're in. For example if you have multiple terminals open and you need to know the directory you're in __pwd__ will tell tell you.
* Syntax: __pwd__ [option(s)]
* Common options: options aren't typically used with __pwd__
---
__cd__ -- __Change directory__
> __cd__ will change the directory you're in so that you can get information, manipulate, read, et., the differnt files and directories in your system.
* Syntax: __cd__ [option(s)] directory
* Common options: options aren't typically used with __cd__
---
__mv__ -- __Move or rename directory__
> __mv__ is used to rename or move directories, without this command you would have to rename each file individually which is tedious. __mv__ allows you to do batch file renaming which can save you loads of time.
* Syntax: __mv__ [option(s)] argument(s)
* Common options: -i, -b
---
__clear__ -- __Clear your terminal window__
> This command is used to clear all previous commands and output from consoles and terminal windows. This keeps your terminal clean and removes the clutter so you can focus on subsequent commands and their output.
* Syntax: __clear__
* Common options: n/a
---
__cp__ -- __Copy files and directories__
> Use this command when you need to back up your files.
* Syntax: __cp__ [option(s)] __current_name__ __new_name__
* Common options: -r, -i, -b
---
__man__ -- __Print manual or get help for a command__
> The __man__ command is your manual and is very useful when you need to figure out what a command does. For example if you didn't know what the command __cat__ does, you could use the __man__ to find that out.
* Syntax: __man__ [option(s)] keyword(s)
* Common options: -w, -f, -b
---
__cat__ -- __Read a file, create a file, and concatenate files__
> __cat__ is one of the more versatile commands and serves three main functions: displaying them, combining copies of them, and creating new ones.
* Syntax: __cat__ [option(s)] [file_name(s)] [-] [file_name(s)]
* Common options: -n
---
