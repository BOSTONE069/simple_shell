Simple shell project README file

# Simple Shell

## Description
This is a simple UNIX command line interpreter that replicates functionalities of the shell.

## Installation
1. Clone this repository in your terminal.

2. Compile with the following flags:

```
simple_shell$ gcc -Wall -Werror -Wextra -pedantic *.c -o hsh
```

3. Run program.

```
simple_shell$ ./hsh
```

After successful compilation, the shell is launched and ready for both interactive and non-interactive executions.

### Interactive Mode
Run program and wait for the prompt `$` to appear. From there, type desired commands. Exit program with the exit command or `Ctrl+D`.

### Non-Interactive Mode
From command line, use `echo` command and pipe into the program like so:

```bash
simple_shell$ echo "command" | ./hsh
```


