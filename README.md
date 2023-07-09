# lil shell

## Bash/Zsh Features:

-   Directory manipulation, with the **pushd**, **popd**, and **dirs** commands.
-   Job control, including the **fg** and **bg** commands and the ability to stop jobs with CTRL-Z.
-   Brace expansion, for generating arbitrary strings.
-   Tilde expansion, a shorthand way to refer to directories.
-   Aliases, which allow you to define shorthand names for commands or command lines.
-   Command history, which lets you recall previously entered commands.
-   Command-line editing, allowing you to use vi-style editing commands on your command lines.
-   Key bindings that allow you to set up customized editing key sequences.

## Stages:

### 1. Read input

### 2. Making syscalls

### 3. Running a program

### 4. Forking a new process/waiting

### 5. Builtins

### 6. Pipelines

### 7. Job control

-   [job control reference](https://www.gnu.org/software/libc/manual/html_node/Implementing-a-Shell.html)

### Next:

-   IO redirection to/from files
-   Redirecting other file descriptors
-   Redirecting to other file descriptors
-   Environment variable expansion
-   Setting environment variables on child processes
-   Another built-in: export
-   Signal handling
-   Globbing
-   Running a command in the background
-   screen?

## References:

-   [shell workshop](https://github.com/kamalmarhubi/shell-workshop)
-   [dash](https://git.kernel.org/pub/scm/utils/dash/dash.git/tree/src/TOUR)
-   [bash architecture](https://aosabook.org/en/v1/bash.html)
-   [termios I](https://blog.nelhage.com/2009/12/a-brief-introduction-to-termios/)
-   [termios II](https://blog.nelhage.com/2009/12/a-brief-introduction-to-termios-termios3-and-stty/)
-   [termios III](https://blog.nelhage.com/2010/01/a-brief-introduction-to-termios-signaling-and-job-control/)
-   [building your own shell](https://www.cipht.net/2017/10/17/build-your-own-shell.html)
-   [a shell in go](https://simjue.pages.dev/post/2018/07-01-go-unix-shell/)
-   [tcl & expect](https://core.tcl-lang.org/expect/index)
