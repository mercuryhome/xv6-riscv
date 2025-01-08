# lecture 2 

## example code

[code](https://pdos.csail.mit.edu/6.1810/2023/lec/l-overview/)

```bash
# cd xv6-riscv
cd user
head -n 1 echo.c > lec_02.example.md
head -n 1 echo.c >> lec_02.example.md
ls -l ex*.c | awk '{print "head -n 1 " $9}' | sh >> lec_02.example.md
```
// echo.c
// ex1.c: copy input to output.
// ex2.c: create a file, write to it.
// ex3.c: create a new process with fork()
// ex4.c: replace a process with an executable file
// ex5.c: fork then exec
// ex6.c: run a command with output redirected
// ex7.c: communication over a pipe
// ex8.c: communication between two processes
// ex9.c: list file names in the current directory
