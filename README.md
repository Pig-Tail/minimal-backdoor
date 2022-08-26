# minimal-backdoor
A simple C code shellcode

In linux, to compile program:

#Server
gcc server.c -o server

#Client
i686-w64-mingw32-gcc -o backdoor.exe backdoor.c -lwininet -lwsock32
