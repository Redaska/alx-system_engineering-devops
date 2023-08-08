General
When you type a command like $ ls -l *.txt, you're interacting with the shell, a command-line interface. The shell executes the ls command with the options -l (long format) for listing details and *.txt for listing all .txt files in the current directory.

Shell Initialization Files
/etc/profile sets up system-wide shell settings.
/etc/profile.d contains additional system-wide scripts for customization.
~/.bashrc holds personalized configurations for the Bash shell.
Variables
Local variables are limited to a specific scope (function or script).
Global variables are accessible across the entire shell session.
Reserved variables (e.g., $HOME, $PATH, $PS1) serve special purposes.
Create, update, and delete shell variables using variable=value, variable=new_value, and unset variable.
Reserved Variables
$HOME points to the user's home directory.
$PATH defines directories for executable files.
$PS1 determines the shell prompt appearance.
Special Parameters
Special parameters like $? represent the exit code of the previous command.

Expansions
Expansions allow you to manipulate and substitute text.
Single quotes preserve literal values, while double quotes allow variable expansion.
Command substitution executes a command and replaces it with its output.
Shell Arithmetic
Perform arithmetic operations using expressions like $((x + y)).

The Alias Command
Create aliases with alias alias_name='command'.
List aliases using alias or alias alias_name.
Temporarily disable an alias using \command_name.

