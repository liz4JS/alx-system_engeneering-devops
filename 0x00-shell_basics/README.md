pwd- it prints the current working directory
ls- it list the contents of the current directory
cd ~- it changes the working directory to the user's home directory
ls -l- it display the current directory contents in a long format
ls -la- it displays the current directory contents, including hidden files (starting with .) using the long format
ls -la- itdisplays the current directory contents in long format, with user and group IDs displayed numerically and hidden files
mkdir- it creates a new directory
mv /tmp/betty /tmp/my_first_directory- move file(betty) to /tmp/my_first_directory
rm /tmp/my_first_directory/betty- it delete the file betty
rm -r /tmp/my_first_directory- it delete the directory my_first_directory that is in the /tmp directory
cd - - it changes the working directory to the previous one
ls -l -a . .. /boot- it lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format
file /tmp/iamafile-it prints the type of the file named iamafile. the file iamafile will be in the /tmp directory when we will run your script
ln -s /bin/ls ./__ls__-it create a symbolic limk to /bin/ls, named __ls__. the symbolic link should be created in the current working directory
cp -u ./*.html ../-it create a script that copies all the HTML files from the current working directory to the parent of the working directory or were newer than the versions in the parent of the working directory
mv [[:upper:]]* /tmp/u- it moves all files beginning with an uppercase letter to the directory /tmp/u
rm ./*~-it deletes all files in the current working directory that end with character ~
mkdir -p welcome/to/school- it creates the directories welcome/, welcome/to and welcome/to/school
