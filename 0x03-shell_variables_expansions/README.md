{alias ls="rm *"} = Create a script that creates an alias. Name: ls, Value: rm *

{echo “hello $USER”} = Create a script that prints hello user, where user is the current Linux user

{export PATH=$PATH:/action} = Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program

{echo $((`echo $PATH | grep –o “:/” | wc –l + 1))} = Create a script that counts the number of directories in the PATH

{printenv} = Create a script that lists environment variables

{set} = Create a script that lists all local variables and environment variables, and functions

{BEST = “school”} = Create a script that creates a new local variable. Name: BEST, Value: School

{export BEST =school} = Create a script that creates a new global variable. Name: BEST, Value: School

{echo $ (($TRUE KNOWLEDGE +128))} = Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line

{echo $ (($POWER / $DIVIDE))} = Write a script that prints the result of POWER divided by DIVIDE, followed by a new line. POWER and DIVIDE are environment variables

{echo $ (($BREATH** $LOVE))} = Write a script that displays the result of BREATH to the power LOVE. BREATH and LOVE are environment variables
The script should display the result, followed by a new line

{echo  $ ((2 # BINARY)0)} = Write a script that converts a number from base 2 to base 10.The number in base 2 is stored in the environment variable BINARY.
The script should display the number in base 10, followed by a new line

{echo {a..z}{a..z} | tr “ ” ”\n” | grep –v “00”} = Create a script that prints all possible combinations of two letters, except oo. Letters are lower cases, from a to zOne combination per line. The output should be alpha ordered, starting with aa. Do not print oo. Your script file should contain maximum 64 characters

{print f ‘ % . 2f ‘ $ NUM | sort} = Write a script that prints a number with two decimal places, followed by a new line. The number will be stored in the environment variable NUM. 

{print f ‘ % x | n ‘ $DECIMAL} = Write a script that converts a number from base 10 to base 16.The number in base 10 is stored in the environment variable DECIMAL. The script should display the number in base 16, followed by a new line

{tr ‘ echo {a..z} | tr –d ‘ “ ‘ echo {n..z} $ echo {a..m} | tr –d ‘ “ ‘ | tr ‘ echo {A..Z} | tr –d ‘ “ ‘ echo {n..z} $ (echo {A..M}) | tr –d ‘ “ ‘} = Write a script that encodes and decodes text using the rot13 encryption. Assume ASCII.

{perl –lne ‘print if $ .% 2 ==1’} = Write a script that prints every other line from the input, starting with the first line

{echo $ (print f % 0 $ (( $ (( 5 # $ (echo $ WATER | tr ‘ water ’ ‘01234’ ‘))) + $ ((5 # s (echo $ STIR | tr ‘stir.’ ‘01234’ ))))) | tr ‘01234567’ ‘bestchol’)} = Write a shell script that adds the two numbers stored in the environment variables WATER and STIR and prints the result. WATER is in base water. STIR is in base stir. The result should be in base bestchol

