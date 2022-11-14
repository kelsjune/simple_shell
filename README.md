The project consists in the creation of a simple shell that will allow the user to interact with the system using commands.

It handles the PATH to find the programs it will execute.
Stat() will be used to check if the found file can be executed.
It will use the execve() system call to perform the commands.
The execution of the programs will be done under children processes using fork().
CTRL+C won't close the program, CTRL+D will do.
