Simple Shell Alx C Project
Collaborated by Chuku David Chimezie & Nehemiah Kagwari

Description

This project represents the realization of a shell, which was developed as a Milestone Project as part of the ALX Africa Software Engineering program.
Named "The Gates of Shell," this project was undertaken during the first trimester to enhance students' comprehension of advanced shell programming concepts, encompassing processes, system calls, bit manipulation, file management, and error handling.
Functioning as a straightforward UNIX command interpreter, this program emulates the core functionalities of the basic shell (sh).
The entire implementation of this project was accomplished using the C programming language.

COPYRIGHT
Copyright (C) 2024 Chuku David Chimezie & Nehemiah Kagwari 
All rights reserved

Description :
This is a shell written in C. It is based on the Thompson shell.

Environment :
Our shell was tested and built on Ubuntu 20.04.

Features of the Project
Display a prompt and wait for the user to type a command. A command line always ends with a new line.
Handle the comments #
If an executable cannot be found, print an error message and display the prompt again.
Handle errors.
Hndling the “end of file” condition (Ctrl+D)
Hanling the command line with arguments
Handle the PATH
Support the history feature
Support the exit features and the exit status
Handle the Ctrl-C to not terminate the shell
Handling the command seperator ;
Handling && and || logical operators
Handle variable replacements $? and $$
Support the file input
The Builtins to be used
Our shell supports the following built-in commands:

Command	Definition
exit [n]	Exit the shell, with an optional exit status, n.
env	Print the environment.
setenv [var][value]	Set an environment variable and value. If the variable exists, the value will be updated.
alias[name[='value]]	Reads aliases name
unsetenv [var]	Remove an environment variable.
cd [dir]	Change the directory.
help [built-in]	Read documentation for a built-in.
The Installation Process : Getting HSH
You would have to Clone the below repository and compile the files into an executable using the GCC compiler.

https://github.com/GodsonicCodes/simple_shell.git
Comprehend The Basic usage 💡
First and most important you would have to Fork this Repository Learn how to fork repo.
Then you Clone Learn how to clone .
You then Create an executable by running the following command:
gcc -Wall -Werror -Wextra -pedantic *.c -o hsh
From there onward type in the following command and press your enter button.
./hsh
Contributors :
Chuku David Chimezie
Nehemiah Kagwari
