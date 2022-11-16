# simple_shell
This project is the largest so far in our ALX program.
Using C programming language, we develop our own Shell.

### Description
The shell is a command-line interpreter or shell that provides a command line user interface
for Unix-like operating systems. The shell is both an interactive command language and a 
scripting language, and is used by the operating system to control the execution of the system
using shell scripts.

### Installation
You can install the simple shell cloning this repo:
```sh
$ git clone https://github.com/rodasbest/simple_shell.git
```
Next you can compile the files with this command:
```sh
$ gcc -Wall -Werror -Wextra -pedantic *.c -o hsh
```
finally you can run our Shell writing:
```sh
./hsh
```
### Files

| File Name | Description |
| ------ | ------ |
| main.c | Executes programs, verify the locations and handles all functions. |
| _exit.c | The exit built-in function |
| _getenv.c |Function to gets an environment variable |
| _open_help.c |Function to print env and help |
| builtin_commands.c | Handle all built-ins |
| counters.c | function to count delims of string |
| exec.c | Executes programs, verify the locations and handles all functions |
| frees.c | functions to free memory |
| utilities.c | Contain 5 functions: _strcat (Concatenates two strings),  _strlen (Co
    unts the length of a string), _strcmp (Compares two strings), _strdup (Duplicate a st 
    ring), _atoi (Convert a string to an integer). |
| more_utilities.c | 2 more functions: _putchar ()writes the character c to stdout),
	    _puts (Prints a string) |
| remove_new_line.c | function to remove a new line char from string |
| shell.h | Libraries and prototypes of functions |
| signal_handler.c | handle the Ctrl + C |
| tokenize.c | function to extract tokens from string |


### Built with
This project was built and development with:
- `C programming language:` is a general-purpose, procedural computer programming language
       supporting structured programming, lexical variable scope, and recursion, while a static 
       type system prevents unintended operations.
- `VirtualBox:` VirtualBox is a general-purpose full virtualizer for x86 hardware, targeted
                at server, desktop and embedded use.
- `Vagrant:` Managing virtual machine environments.
- `Ubuntu 20.04 LTS:` Operating system tester and working.
- `GCC:` GNU Compiler version 9.4.0

# Authors
- Rodas Alemseged - Development and documentation
