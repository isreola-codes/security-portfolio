# Bash basics

A script is a file of commands that run in order, like a recipe.

## The pieces
- The first line, `#!/bin/bash`, tells Linux which program runs the file.
- `chmod +x script.sh` makes it runnable. Without it, I get "Permission denied".
- A **variable** is a labeled box that holds a value, like `name="mrpluto"`. I use it with a `$` in front: `$name`.
- `read name` waits for me to type something and stores it in the variable.
- `if ... else ... fi` makes a decision: the script does one thing if the answer is yes, and another if it is no.

## My scripts
- `hello.sh` prints a greeting, my folder, my username and the date.
- `ask.sh` asks my name, then checks whether `notes.txt` exists and prints "exists" or "missing".

## Why this matters for security
Analysts write scripts that check things for them, like whether a file exists or a setting is wrong, so they don't have to check by hand.
