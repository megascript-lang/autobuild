# Autobuild
Autobuild automatically generates build scripts for programs on Unix-like systems and Windows in their native shells!

Example usage: https://www.youtube.com/watch?v=QNtPEdqj7dU

# Syntax

### Variables!

Variables. Enough said.

```
VAR VARIABLE1 = ls
COMMAND VARIABLE1
```

### If Statements!

Autobuild has conditional branches!

```
IF OS = FreeBSD
VAR FIRST_COMMAND = echo hi!
ELSEIF OS = Windows_NT
VAR FIRST_COMMAND = echo(hi!
END
```

### User Input!

Getting user input is simple in Autobuild!

```
GET INPUT VARIABLE2 Enter name:
VAR COMMAND1 = Hello,
COMMAND COMMAND1 SPACE VARIABLE2
```

### Modes!

You can add argument modes just like with Makefile!

```
MODES clean
VAR COMMAND1 = rm installer.sh
COMMAND COMMAND1
MODES install
VAR COMMAND2 = ./installer.sh
COMMAND COMMAND2
```
