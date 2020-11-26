# Simple Shell :trophy:

## Description
In this project, we create a ***simple shell*** that must have the same behavior of sh shell in input and error.

## Resourses :books:
- https://intranet.hbtn.io/concepts/64
- https://www.geeksforgeeks.org/making-linux-shell-c/
- https://brennan.io/2015/01/16/write-a-shell-in-c/

## How To Start :hammer_and_wrench:
1. Clone the repo:
```
$ git clone https://github.com/kiba0510/simple_shell
```
2. Compile the file with:
```
$ gcc -Wall -Werror -Wextra -pedantic *.c -o simple_shell
```

3. Execute it with:
```
$ ./simple_shell
```

## How To Use :computer:
In ***INTERACTIVE MODE***:
$ <command> <flags> <argument>
  - Ex:
  ```$ echo Hello World! ```
  - Output:
  ```Hello World! ```
  
In ***NON-INTERACTIVE MODE***
$ echo <commands and arguments> | ./simple_shell
  - Ex: 
  ```
  $ echo "ls -l" | ./simple_shell
  ```
  - Output:
  ```
  total 140
-rw-rw-r-- 1 vagrant vagrant 505 Nov 25 19:44 0_principal_header.h
(...)
  ```

## Commands 
***Command***               ***Description***
     exit         Exit Program
     env          Display Enviroment Variables
    setenv        Set environment variable value or create a new one
   unsetenv       Delete environment variable
