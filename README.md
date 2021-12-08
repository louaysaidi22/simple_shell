# Simple_shell

This project challenged us to Create our own Simple shell

## Description


This Is A rebuild of the simple UNIX command interpreter (shell).


###  Compilation

Our shell will be compiled with this command:

```bash
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh
```
List of allowed functions and system calls
chdir (man 2 chdir)
close (man 2 close)
closedir (man 3 closedir)
execve (man 2 execve)
exit (man 3 exit)
_exit (man 2 _exit)
fflush (man 3 fflush)
fork (man 2 fork)
free (man 3 free)
getcwd (man 3 getcwd)
getline (man 3 getline)
getpid (man 2 getpid)
isatty (man 3 isatty)
kill (man 2 kill)
malloc (man 3 malloc)
open (man 2 open)
opendir (man 3 opendir)
perror (man 3 perror)
read (man 2 read)
readdir (man 3 readdir)
signal (man 2 signal)
stat (xstat) (man 2 stat)
lstat (lxstat) (man 2 lstat)
fstat (__fxstat) (man 2 fstat)
strtok (man 3 strtok)
wait (man 2 wait)
waitpid (man 2 waitpid)
wait3 (man 2 wait3)
wait4 (man 2 wait4)
write (man 2 write)


### Files and functions:

AUTHORS           execute_line.c          extern.c

hsh               putchar.c               read_line.c

README.md         shell.c                 shell.h

split_line.c      str.c                   man_1_simple_shell

### C recreated functions used  :

Examples:

###### Example 1

$./hsh

$

###### Example 2

$ls


AUTHORS           execute_line.c          extern.c

hsh               putchar.c               read_line.c

README.md         shell.c                 shell.h

split_line.c      str.c                   man_1_simple_shell

$

### Known bugs :

No bugs know. if there is a bug you can contact us in email.

### Annotations



### Authors

* Louay saidi - https://github.com/louaysaidi22

* Aymen Ben Slima - https://github.com/Aymenbs22


###### Project made for Holberton school by Louay saidi and Aymen Ben Slima.
