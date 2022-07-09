#!/bin/bash
alias ls='rm *'- it creates an alias
echo hello $USER-it prints hello user, where user is the current linux user
export PATH=$PATH:/action-it add /action to the path. /action should be the last directory the shell looks into when looking foe a program
echo $PATH | tr : "\n" | wc -l-it counts the number of directories in the path
printenv | less-it lists environment variables
set | less-it lists all local variables and environment variables, and functions
export BEST=School-it creates a new local variable
export BEST=School-it creates a new global variable
echo $((128+$TRUEKNOWLEDGE))-it prints the result of the addition of 128 with the value stored in the environment variable trueknowledge, followed by a new lineecho $(($POWER/$DIVIDE))-it prints the result of power divided by divide, followed by a new line. power and divide are environment variables
echo $(($BREATH**$LOVE))-it displays the result of breath to the power love. breath and love are environment variebles. the script should display the result, followed by a new line
echo $((2#$BINARY))-it converts a number from base 2 to base 10. the number in base 2 is stored in the environment variable binary. the script should display the number in base 10, followed by a new line
