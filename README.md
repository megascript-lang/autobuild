# Autobuild
Autobuild automatically builds programs on Unix-like systems and Windows in their native shells!

# Syntax

### If statements

```
IF OS = FreeBSD
VAR FIRST_COMMAND = echo hi!
ELSEIF OS = Windows_NT
VAR FIRST_COMMAND = echo(hi!
END
```
