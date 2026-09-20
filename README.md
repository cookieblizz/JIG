# JIG - By Cookieblizz

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

### 6. ' stop '
The ' stop ' command is used to stop the execution of another command after a specified amount of time
Example:
``` JIG
stop(2
| text: " hello world "
```

### 7. ' start '
The ' start ' command is used to start the execution of a command
Example:
``` JIG
start
! text: " hello world "
```

### 7. ' delete '
The ' delete ' command is used to delete commands after a specified amount of time
Example:
``` JIG
delete(after5)
| text: " hello world "
```

### 8. ' add '
The ' add ' command is used to add the execution of another command after a specified amount of time
Example:
``` JIG
add(5)
| text: " hello world "
```

### 9. ' otherwise '
The ' otherwise ' command is used with the ' if ' command
Example:
``` JIG
if X < 5
| then text: " hello world "
| otherwise text: " hi "
```


### NESTING
In JIG, ' | ' is used for nesting, it works like the indent line from Roblox Studio etcetera...

REMINDER: This coding language is still a WIP (Work In Progress)

- By Cookieblizz
