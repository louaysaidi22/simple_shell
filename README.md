# Simple_shell

This project challenged us to Create our own Simple shell

## Description


This Is A rebuild of the simple UNIX command interpreter (shell).


###  Compilation

Our shell will be compiled with this command:

```bash
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh
```
<br/>
List of allowed functions and system calls<br/>
chdir (man 2 chdir)<br/>
close (man 2 close)<br/>
closedir (man 3 closedir)<br/>
execve (man 2 execve)<br/>
exit (man 3 exit)<br/>
_exit (man 2 _exit)<br/>
fflush (man 3 fflush)<br/>
fork (man 2 fork)<br/>
free (man 3 free)<br/>
getcwd (man 3 getcwd)<br/>
getline (man 3 getline)<br/>
getpid (man 2 getpid)<br/>
isatty (man 3 isatty)<br/>
kill (man 2 kill)<br/>
malloc (man 3 malloc)<br/>
open (man 2 open)<br/>
opendir (man 3 opendir)<br/>
perror (man 3 perror)<br/>
read (man 2 read)<br/>
readdir (man 3 readdir)<br/>
signal (man 2 signal)<br/>
stat (xstat) (man 2 stat)<br/>
lstat (lxstat) (man 2 lstat)<br/>
fstat (__fxstat) (man 2 fstat)<br/>
strtok (man 3 strtok)<br/>
wait (man 2 wait)<br/>
waitpid (man 2 waitpid)<br/>
wait3 (man 2 wait3)<br/>
wait4 (man 2 wait4)<br/>
write (man 2 write)<br/>


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
