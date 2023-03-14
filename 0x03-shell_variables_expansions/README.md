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
