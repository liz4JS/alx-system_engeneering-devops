#!/bin/bash
su betty- it switches the current user betty
whoami-it prints the effective username of the current user
groups-it prints all the groups the current user is part of
sudo chown betty hello- it changes the owner of the file hello to the user betty
touch hello-it creates an empty file
chmod u+x hello-it adds execute permission to the owner of the file
chmod +114 hello-it adds execute permission to the owner and the group owner, and read permission to other users, to the file hello. the file hello will be in the working directory
chmod +x hello-it adds execution permission to the owner, the group owner and the other users, to the file
chmod 007 hello-it sets the permission to the file hello as follows; owner:no permission at all. group:no permission at all. other users:all the permissions
chmod 753 hello-it sets the mode of the file hello to this: the file hello will be in the working directory. you are not allowed to use commas for the script
chmod --reference=olleh hello-it sets the mode of the file hello the same as olleh's mode. the file hello will be in the working directory. the file olleh will be in the working directory
