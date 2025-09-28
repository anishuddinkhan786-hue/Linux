# How to check the present working directory 
 ```bash
 pwd - present working directory
```

# How to check system date and time 

```bash
    anish@ANISH:~$ date
    Sun Sep 28 12:35:05 UTC 2025
    anish@ANISH:~$ date +%D
    09/28/25
    anish@ANISH:~$ date +%T
    12:35:24
    anish@ANISH:~$ date +%H:%M:%S
    12:35:52
    anish@ANISH:~$ date +%dd:%mm:%yyyy
    28d:09m:25yyy
    anish@ANISH:~$ date +%d:%m:%y
    28:09:25
```

#how to display files in current location
```bash
    ls & ls -lt
```

#human readable 
```bash
    ls -lh
```

#clear 
```bash
    clear & ctrl+L
```
#create a folder or directory 
```bash
    mkdir demo
```
#remove a folder
```bash
    rmdir demo
```
#create a file
```bash
    touch demo.txt
```
#write in a file
```bash
    nano demo.txt
    Ctrl+O -> save
    Enter
    Ctrl+X -> Exit
```
#display content of a file
```bash
    cat demo.txt
```
#read a file & search
```bash
    less demo.txt
    P,N,Q,shift+G->last line
    /->forward, ?->backward
```
