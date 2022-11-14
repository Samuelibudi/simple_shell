The simple_shell project was undertaken as a capstone sprint of the C programming sprint under the alx-software engineering course. The idea was to allow students a practical application of the all the concepts so far learned. The project was broken into sample sized tasks that on a whole would build up the shell.

Below is a breakdown of the tasks;

1. Simple shell 0.1 
	
	The task involved involved writing a command line interpreter that would be able to;
		> Display a prompt and wait for the user to type a command.
		> The prompt is displayed again each time a command is executed.
		> The commandlines did not require advanced features at this stage.
		> The command line had to handle errors.
		> Handle end of file (ctrl + D).

2. Simple shell 0.2

	The task involved handling command line arguments.

3. Simple shell 0.3

	In addition to what the commandline was doing in 0.2, the following were added;

		> Handling of PATH
		> fork must not be called if the command does not exist.

4. Simple shell 0.4

	In addition to 0.3, the following were added under this task;

		> Implement the exit built-in, that exits the shell.
		> Usage: exit

5. Simple shell 1.0

	In addition to simple shell 0.4, the following was added for this task;

		> Implement the env built-in, that prints the current environment.

6. Simple shell 0.1.1

	Simple shell 0.1 with the following additions;

		> Writing your own getline function
		> Use a buffer to read many chars at once and call the least possible the read system call
		> Use of static variables

7. Simple shell 0.2.1

	In additon to simple shell 0.2, strtok was removed and implementation was individual.

8. Simple shell 0.4.1

	In addition to simple shell 0.4, the following were added;

		> Handling of arguments for the built in exit
		> Usage:exit status, where status is an integer used to exit the shell.

9. setenv, unsetenv

	This task involved implementing the setenv and unsetenv built in commands.

10. cd

	The task involved implementation of the change directory command.

11. ;

	The task involved involved implementation of command separator handling.

12. && and ||

	The task involved handling of && and || shell logical operators.

13. alias

	Task involved implementation of the alias built in command.

14. Variables

	The task involved handling of variable replacements including $? and $$

15. Comments

	The task involved handling of comments (#)

16. File as input

	The task involved handling of a file as input 
