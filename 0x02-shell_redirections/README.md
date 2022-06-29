#!/bin/bash
echo Hello, World- it prints "Hello, World", followed by a new line to the standard output
echo "\"(Ôo)'"- it displays a confused smiley
cat /etc/passwd -delete- it displays the content of the /etc/passwd file
cat /etc/passwd /etc/hosts- it displays the content of /etc/passwd and /etc/host
tail /etc/passwd-it displays the last 10 lines of /etc/passwd
echo Best School > '\*\\'"'"'"Best School"\'"'"'\\*$\?\*\*\*\*\*:)'-it creates a file containing the text best school ending by a new line
ls -la > ls_cwd_content-it writes into the file the result of the command. if the file already exists, it should overwrite it. if the file doesn't exist, create it
tail -n 1 iacta >> iacta-it duplicates the last line of the file
find . -type f -name "*.js" -delete-it deletes all regular files(not the directories) with a extension that are present in the current directory and its subfolders
find ./* -type d | wc -l-it counts the number of directories and sub-directories in the current directory. the current and parent directories should not be taken into account. hidden directories should be counted
ls -t -1 | head-it displays the 10 newest files in the current directory
sort | uniq -u-it takes a list of words as input and prints only words that appear exactly once. input format: one line, one word. output format: one line, one word. words shoulld be sorted
grep -e "root" /etc/passwd- it display lines containing the pattern from the file
grep -c "bin" /etc/passwd-it display the number of lines that contain the pattern in the file
grep -A 3 "root" /etc/passwd-it display lines containing the pattern and 3 lines after them in the file
grep -v "bin" /etc/passwd-it display all the lines in the file that do not contain the pattern
grep ^[a-zA-Z] /etc/ssh/sshd_config-it display all lines of the file starting with a letter include capital letters as well
tr A Z | tr c e- it replace all characters and from input to and respectively
tr -d c | tr -d C-it removes all letters from input
cut -d":" -f1,6 /etc/passwd | sort-it displays all users and their home directories, sorted by users. based on the file
