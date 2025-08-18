hell, init files, variables and expansions

## 0. Create an alias
The script `0-alias` is a bash script that creates an alias named `ls` with the value `rm *`. When the script is sourced, typing `ls` will execute `rm *`, deleting all files in the current working directory


## 1. Hello you
The script `1-hello_you` is a bash script that prints "hello user", where "user" is the current Linux username..

## 2. The path to success is to take massive, determined action
The script `2-path` adds the directory `/action` to the end of the `PATH` environment variable. The new directory will be the last one the shell checks when looking for a program.

## 3. If the path be beautiful, let us not ask where it leads
The script `3-paths` counts the number of directories contained in the `PATH` environment variable and prints the result. It correctly handles cases where multiple or empty colons are present.


## 4. Global variables
The script `4-global_variables` lists all the environment variables of the current session.


## 5. Local variables
The script `5-local_variables` lists all local variables, environment variables, and shell functions.

## 6. Local variable
The script `6-create_local_variable` creates a new local variable named `BEST` with the value `School`.


## 7. Global variable
The script `7-create_global_variable` creates a new global variable named `BEST` with the value `School`.

## 8. True Knowledge
The script `8-true_knowledge` prints the result of 128 added to the value of the environment variable `TRUEKNOWLEDGE`.

## 9. Divide and rule
The script `9-divide_and_rule` prints the result of the environment variable `POWER` divided by the environment variable `DIVIDE`.


## 10. Love is anterior to life...
The script `10-love_exponent_breath` displays the result of the environment variable `BREATH` to the power of the environment variable `LOVE`.

## 11. There are 10 types of people...
The script `11-binary_to_decimal` converts a number from base 2 to base 10. The number to be converted is stored in the environment variable `BINARY`.


## 12. Combinations
The script `12-combinations` prints all possible combinations of two lowercase letters from `a` to `z`, except for `oo`. The output is alpha-ordered, with one combination per line.


## 13. Floats
The script `13-print_float` prints a number stored in the environment variable `NUM` with exactly two decimal places.


## 14. Decimal to Hexadecimal
The script `100-decimal_to_hexadecimal` converts a number from base 10 to base 16. The number to be converted is stored in the environment variable `DECIMAL`.


## 15. rot13
The script `101-rot13` encodes and decodes text using the ROT13 cipher. It reads from standard input and writes the result to standard output.


## 16. The eggs of the brood need to be an odd number
The script `102-odd` prints every other line from the standard input, starting with the first line.


## 17. Water and Stir
The script `103-water_and_stir` adds two numbers stored in the `WATER` and `STIR` environment variables. The numbers are represented in custom bases ("water" and "stir") and the result is printed in a third custom base ("bestchol").
