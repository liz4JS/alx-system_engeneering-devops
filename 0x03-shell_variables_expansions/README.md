#!/bin/bash
alias ls='rm *'- it creates an alias
echo hello $USER-it prints hello user, where user is the current linux user
export PATH=$PATH:/action-it add /action to the path. /action should be the last directory the shell looks into when looking foe a program
echo $PATH | tr : "\n" | wc -l-it counts the number of directories in the path
printenv | less-it lists environment variables
set | less-it lists all local variables and environment variables, and functions
export BEST=School-it creates a new local variable
export SCHOOL=Best-it creates a new global variable
