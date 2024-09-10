The Bash Command Line
=====================

![*Tux, the Linux penguin*](tux.png)

This tutorial makes you familiar with **bash**, the Linux command line. You will learn to:

* navigate directories
* manipulate files
* execute programs

If you have no previous experience with Unix-like
systems or know a few commands but would like to know more, this tutorial is for you.

### Prerequisites

*This tutorial was prepared for Ubuntu Linux, but it works on MacOS,
Cygwin and the Git bash as well, given that Python 3 is installed on
your system.*

----

## Goal

In this tutorial, you will be looking for a word with 22 characters:

![](solution.png)

All characters are hidden in the exercises below.

## Preparations

* clone the repository or download the code as a ZIP file
* locate the  `exercises/` folder
* open a `bash` terminal

![](preparations.png)

----

## 1. Directories and files


### 1.1. Navigating directories

The **first character** is hidden in a file somewhere in the *exercise1* directory tree. Look through subdirectories until you find one with the name `solution_1.1` and list its contents.

### 1.2. Show a hidden file

Some files are not visible immediately. The **second character**, is in the same directory as the first one, but in a hidden file.

### 1.3. Execute a program

Go back to the directory `exercise_1/directoryB/`. When listing its contents, you should see a **shell script file** `program.sh`. To find the **third character**, you need to execute the program.

### 1.4. Find out how big a file is

Go to the folder `exercise_1/directoryC/`. To find **the fourth character**, you need to find out how big the text file in the directory is.

To obtain the fourth character look up the file size in the [Table of
printable ASCII
characters](https://en.wikipedia.org/wiki/ASCII#Printable_characters):

![](ASCII-Table-wide.svg)

*ASCII Table, Public Domain*

----

## 2. Edit text files

Please go back to the top directory of the tutorial material. Then, change to the directory `exercise_2`.

### 2.1. See what is in a text file

In the directory *exercise\_2/*, you will find a text file *solution\_2.1.txt*. The **fifth character** is inside that file.

### 2.2. Edit text files

To get **character number six**, you will need to create a text file in the `exercise_2` directory. On Ubuntu, you can do this using the editor `nano`.

**To exit nano, type Ctrl-X**

Create a text file with the characters you have found so far.

The **sixth character** is the one you need to press to save a file in
`nano`.

----

## 3. Copy and remove files

Please go to the directory exercise\_3.

### 3.1. Create a directory and copy a file to it.

To find **characters seven and eight**, you need to create a subdirectory named *solution* in `exercise_3/` and copy the files from the `part1/` and `part2/` folders into it. Then, look at the files in the soltion folder.

### 3.2. Removing files

In the `data` directory, all files with an `Y` need to be deleted. Use Wildcards to delete the files. To get **characters nine and ten**, look at the files that remain after deleting all that contain a `Y`.

----

## 4. Process text data

Please go to the directory exercise\_4.

### 4.1. comparing two files

There are two different versions of a quote, `ai.txt`, and `artificial_intelligence.txt`. The **11th character** of the solution is the single character in which the
two files differ. Do not do this manually but use a command.

### 4.2. Sorting a text file

The **12th character** of the solution is the first character of the last word in the file elephant.txt when all lines are sorted alphabetically.

### 4.3. Finding words in a text file

To find the **13th character**, search for the word **fire** in the file `datascience.txt` and take the **first** character of the output. Do not do this manually but use a command.

----

## 5. Unzip files

Please go to the directory exercise\_5.

### 5.1. unzipping archives

The **14th and 15th character** of the solution are in a multiply
wrapped archive in the exercise\_5 directory.

----

## 6. Command-line tools

Please go to the directory `exercise_6`.

### 6.1. Changing file access rights

To see **characters 16+17** of the solution, make the program `permissions.sh` executable. Then execute it.

### 6.2. How much disk space have I left?

To obtain the **18th character**, check out the version of the Unix utility program to find out empty disk space.

The solution is the last character of the programs first authors' first name.

### 6.3. Set an environment variable

To install some programs, it is necessary to set so-called environment
variables.

To obtain the **19th character**, you need to set the variable *GIVEME* to the value **SOLUTION**.

Find out the **characters position in the alphabet** by getting the number of bytes in the value of the GIVEME variable.

### 6.4. Check whether you have internet

The **20th character** is the `ping` option that sets the maximum number of requests sent. Check the documentation in the manpages.

### 6.5. Managing processes

Use the Linux equivalent of the Windows Task Manager to display currently running programs.

The **last two characters** of the solution are the first two characters
of the second word in the line containing the column labels.

----

### License

**© 2024 Dr. Kristian Rother**

This tutorial is published under the Creative Commons Attribution
Share-alike License 4.0

You can find the full sources on
[<https://github.com/krother/bash_tutorial>](https://github.com/krother/bash_tutorial).

### Acknowledgements

Thanks to many students for using the tutorial in practice and finding bugs. Thanks to `@zulcas` for contributing bugfixes.

I thank Janusz M. Bujnicki, Allegra Via, Pedro Fernandes and Joachim
Jacob for their help with testing and reviewing the material. Further
thanks go to the German Academic Exchange Service (DAAD) for financial
support.

### Contact

`kristian.rother@posteo.de`