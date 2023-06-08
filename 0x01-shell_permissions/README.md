su betty : switch current user to user betty
whoami : print effective username of current user
group : print all groups the current user is part of
sudo chown betty hello : changing owner of file to user betty
touch hello : Created empty file hello
chmod u+x : Add execute permissio to owner of file
chmod ug+x.o+r : Give user and group execute permission and other only the read permission
chmod ug0+x : Give all users the execute command
chmod 007 hello : Give all permissions to users and none for the owner and group
chmod 753 hello : Give all permissions to owner reand and execute to group and write and execute to users
chmod --reference=olleh hello : Mirror permissions
chmod -R ugo+x . : Giving permissions to all subdirectories in the current directory
mkdir -m 751 my_dir : Create a directory my_dir and assign permissions 751
chgrp school hello : Change group for file hello
chown vincent:staff * : changes the owner to vincent and the group owner to staff for all the files and directories in the working directory
chown -h vincent:staff _hello : changes the owner and the group owner of _hello to vincent and staff respectively. Hello is a symbolic link
chown --from=guillaume betty hello :changes the owner of the file hello to betty only if it is owned by the user guillaume.
telnet towel.blinkenlights.nl :plays starwars IV episoe inside the terminal

