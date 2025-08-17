hell, init files, variables and expansions

## 0. Create an alias
The script `0-alias` is a bash script that creates an alias named `ls` with the value `rm *`. When the script is sourced, typing `ls` will execute `rm *`, deleting all files in the current working directory


## 1. Hello you
The script `1-hello_you` is a bash script that prints "hello user", where "user" is the current Linux username..

## 2. The path to success is to take massive, determined action
The script `2-path` adds the directory `/action` to the end of the `PATH` environment variable. The new directory will be the last one the shell checks when looking for a program.

## 3. If the path be beautiful, let us not ask where it leads
The script `3-paths` counts the number of directories contained in the `PATH` environment variable and prints the result. It correctly handles cases where multiple or empty colons are present.
