#!/bin/bash
su betty- it switches the current user betty
whoami-it prints the effective username of the current user
groups-it prints all the groups the current user is part of
sudo chown betty hello- it changes the owner of the file hello to the user betty
touch hello-it creates an empty file
chmod u+x hello-it adds execute permission to the owner of the file
chmod +114 hello-it adds execute permission to the owner and the group owner, and read permission to other users, to the file hello. the file hello will be in the working directory
