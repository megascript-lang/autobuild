# Autobuild
Autobuild automatically builds programs on Unix-like systems and Windows in their native shells!

# Syntax

### Variables!

```
VAR VARIABLE1 = ls
COMMAND VARIABLE1
```

### If Statements!

```
IF OS = FreeBSD
VAR FIRST_COMMAND = echo hi!
ELSEIF OS = Windows_NT
VAR FIRST_COMMAND = echo(hi!
END
```

### User Input!

```
GET INPUT VARIABLE2 Enter name:
VAR COMMAND1 = Hello,
COMMAND COMMAND1 SPACE VARIABLE2
```
