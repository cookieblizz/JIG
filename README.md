<img width="273" height="473" alt="{4497061B-E9AB-4ADE-AEAB-BF880D987C5B}" src="https://github.com/user-attachments/assets/e2a878b1-f055-49f0-88fb-a37a119697b2" /># JIG - By Cookieblizz

JIG is a very easy coding language, inspired by Lua and Python

## OFFICIAL COMMANDS

### 1. ' text '
The ' text ' command works just like the print command.
Example:
``` JIG
text: " hello world " 
```

### 2. ' repeat '
The ' repeat ' command repeats lines of code a specified amount of times
Example:
``` JIG
repeat: 5
| text: " hello world "
```

### 3. ' searchfor '
The ' searchfor ' command searches for a specific variable / line of code
Example:
``` JIG
searchfor:(text: " hello world ")
```

### 4. ' if '
The ' if ' command executes only if a certain condition is true, uses only a = for simplicity
Example:
``` JIG
if: X = 5
| then text: " hello world "

if: X > 5
| then text: " hi "

if X < 5
| then text: " what's up "
```
### 5. ' wait '
The ' wait ' command is used to delay the execution of another command
Example:
``` JIG
wait(2)
| text: " hello world "
```

### NESTING
In JIG, ' | ' is used for nesting, it works like the indent line from Roblox Studio etcetera...

REMINDER: This coding language is still a WIP (Work In Progress)

- By Cookieblizz
