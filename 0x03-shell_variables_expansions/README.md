 0- alias ls="rm *" Create a script that creates an alias Name: ls Value: rm *

 1- echo "hello $USER" a script that prints hello user, where user is the current Linux user

 2- PATH=$PATH:/action Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program

 3- echo $PATH | tr ":" "\n" | wc -l  a script that counts the number of directories in the PATH.

 4- printenv a script that lists environment variables.

 5- set | less a script that lists all local variables and environment variables, and functions

 6- BEST=School a script that creates a new local variable Name: BEST Value: School

 7- export BEST=School a script that creates a new global variable Name: BEST Value: School

 8- echo $(($TRUEKNOWLEDGE+128))  a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE

 9- echo $(($POWER/$DIVIDE)) a script that prints the result of POWER divided by DIVIDE, followed by a new line.

 10- echo $(($BREATH**$LOVE))  a script that displays the result of BREATH to the power LOVE

 11- echo $((2#$BINARY))  a script that converts a number from base 2 to base 10 The number in base 2 is stored in the environment variable BINARY
 
 12- echo {a..z}{a..z} | tr ' ' '\n' | grep -v "oo" a script that prints all possible combinations of two letters, except oo.

 13- printf "%0.2f\n" $NUM a script that prints a number with two decimal places, followed by a new line The number will be stored in the environment variable NUM 

 14- printf "%x\n" $DECIMAL a script that converts a number from base 10 to base 16 The number in base 10 is stored in the environment variable DECIMAL

 15- tr 'A-Za-z' 'N-ZA-Mn-Za-m'  a script that encodes and decodes text using the rot13 encryption. Assume ASCII.

 16- paste - - | cut -f1  a script that prints every other line from the input, starting with the first line

 17- printf '%o\n' $(( 5#$( echo $WATER | tr water 01234) + 5#$( echo $STIR | tr stirr. 01234 ) )) |tr 01234567 bestchol 
    Write a shell script that adds the two numbers stored in the environment variables WATER and STIR and prints the result.

WATER is in base water
STIR is in base stir.
