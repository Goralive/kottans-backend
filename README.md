# kottans-backend

## Git
Finished during the frontend course.
[Git](https://github.com/Goralive/kottans-frontend/blob/master/task_git_collaboration/git_VS.png)
>I'm using in everyday routine and don't afraid to make mistakes. 

## Unix Shell
Codeacademy finished while frontend course.
Read articles 
[CLI](https://github.com/Goralive/kottans-frontend/blob/master/task_linux_cli/codeacademy_cli_git.png)
>Setup fedora and start to use shell. Don't use root :D

## Git Collaboration
Finished while front end course
[Git collaboration](https://github.com/Goralive/kottans-frontend/blob/master/task_git_collaboration/Git_coloboration.png)
>Using in every day work. Making code reviews

## Memory Management
What's going to happen if program reaches maximum limit of stack ?
>Will be stack overflow and program will fail

What's going to happen if program requests a big (more then 128KB) memory allocation on heap ?
>Heap will increace memory allocation via calling the system call brk() to make a room for the requested block

What's the difference between Text and Data memory segments ?
>Text segment - is  only read-only memory area and stores all of your code.
>Data segment - holds the contents for static variables initialized in source code. This memory area is not anonymous.

After proc/maps
```
5ed94f74000-55ed94f76000 r--p 00000000 fd:00 1704271                    /usr/bin/cat
55ed94f76000-55ed94f7b000 r-xp 00002000 fd:00 1704271                    /usr/bin/cat
55ed94f7b000-55ed94f7e000 r--p 00007000 fd:00 1704271                    /usr/bin/cat
55ed94f7e000-55ed94f7f000 r--p 00009000 fd:00 1704271                    /usr/bin/cat
55ed94f7f000-55ed94f80000 rw-p 0000a000 fd:00 1704271                    /usr/bin/cat
55ed96896000-55ed968b7000 rw-p 00000000 00:00 0                          [heap]
7fbbb0a13000-7fbbbd9bd000 r--p 00000000 fd:00 1704390                    /usr/lib/locale/locale-archive
7fbbbd9bd000-7fbbbd9df000 r--p 00000000 fd:00 1714834                    /usr/lib64/libc-2.29.so
7fbbbd9df000-7fbbbdb2c000 r-xp 00022000 fd:00 1714834                    /usr/lib64/libc-2.29.so
7fbbbdb2c000-7fbbbdb78000 r--p 0016f000 fd:00 1714834                    /usr/lib64/libc-2.29.so
7fbbbdb78000-7fbbbdb79000 ---p 001bb000 fd:00 1714834                    /usr/lib64/libc-2.29.so
7fbbbdb79000-7fbbbdb7d000 r--p 001bb000 fd:00 1714834                    /usr/lib64/libc-2.29.so
7fbbbdb7d000-7fbbbdb7f000 rw-p 001bf000 fd:00 1714834                    /usr/lib64/libc-2.29.so
7fbbbdb7f000-7fbbbdba7000 rw-p 00000000 00:00 0 
7fbbbdba7000-7fbbbdba8000 r--p 00000000 fd:00 1714827                    /usr/lib64/ld-2.29.so
7fbbbdba8000-7fbbbdbc8000 r-xp 00001000 fd:00 1714827                    /usr/lib64/ld-2.29.so
7fbbbdbc8000-7fbbbdbd0000 r--p 00021000 fd:00 1714827                    /usr/lib64/ld-2.29.so
7fbbbdbd1000-7fbbbdbd2000 r--p 00029000 fd:00 1714827                    /usr/lib64/ld-2.29.so
7fbbbdbd2000-7fbbbdbd3000 rw-p 0002a000 fd:00 1714827                    /usr/lib64/ld-2.29.so
7fbbbdbd3000-7fbbbdbd4000 rw-p 00000000 00:00 0 
7ffd1d9b9000-7ffd1d9db000 rw-p 00000000 00:00 0                          [stack]
7ffd1d9e1000-7ffd1d9e4000 r--p 00000000 00:00 0                          [vvar]
7ffd1d9e4000-7ffd1d9e5000 r-xp 00000000 00:00 0                          [vdso]
ffffffffff600000-ffffffffff601000 r-xp 00000000 00:00 0                  [vsyscall]
```

Heap - `55ed96896000-55ed968b7000`
Stack - `7ffd1d9b9000-7ffd1d9db000`
MMS - `7fbbbd9df000-7fbbbdb2c000`

For now it's pretty hard for me, and I should re-read about MMS. But it's pretty interesting. Maybe some article is preety hard to undestand)
