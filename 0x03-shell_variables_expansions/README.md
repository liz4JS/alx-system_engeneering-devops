#!/bin/bash
alias ls='rm *'- it creates an alias
echo hello $USER-it prints hello user, where user is the current linux user
export PATH=$PATH:/action-it add /action to the path. /action should be the last directory the shell looks into when looking foe a program
echo $PATH | tr : "\n" | wc -l-it script that counts the number of directories in the path
