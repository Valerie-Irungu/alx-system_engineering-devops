su switches current user to the other user
whoami prints the effective username of the current user
groups lists all the groups the current user is part of
sudo chown betty hello changes the owner of the hello file to the user betty
touch hello creates an empty file called hello
chmod 744 hello adds execute permission to the owner
chmod 754 hello adds execute permission to the owner,group owner and read permission to other users
chmod a+x hello adds execution permission to the owner, group owner and other users to the file hello
chmod 007 hello adds execution permission to others only
chmod 753 hello sets the mode of the file hello
chmod --reference olleh hello sets mode of the hello file same as that of olleh's
chmod -R a+x ./ executes permission to all subdirectories
create directory my_dir with permissions 751
changes the group owner to school for the file hello
changes the owner to vincent and group to staff
changes the file's owner to betty if the owner is gulliname