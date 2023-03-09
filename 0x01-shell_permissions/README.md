su betty - switches the current user to the user betty.
whoami - script that prints the effective username of the current user.
groups - a script that prints all the groups the current user is part of.
chown betty hello - changes the owner of the file hello to the user betty.
touch hello - a script that creates an empty file called hello.
chmod u+x hello - adds execute permission to the owner of the file hello
6-multiple_permissions - script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
chmod ugo+x hello - adds execution permission to the owner, the group owner and the other users, to the file hello
chmod 007 hello - no permission to the owner and the group, but gives all permissions to other users
chmod 751 hello - sets the mode of the file hello to -rwxr-x-wx
chmod $(stat -c "%a" olleh) hello - sets the mode of the file hello the same as olleh’s mode
find . -type d -exec chmod ugo+x {} + - adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
mkdir -m 751 my_dir - creates a directory called my_dir with permissions 751 in the working directory.
chgrp school hello - a script that changes the group owner to school for the file hello
chown -R vincent:staff ./* -  changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
chown vincent:staff _hello - changes the owner and the group owner of _hello to vincent and staff respectively.
[ "$(stat -c %U hello)" = "guillaume" ] chown betty hello - changes the owner of the file hello to betty only if it is owned by the user guillaume.
telnet towel.blinkenlights.nl - play the StarWars IV episode in the terminal.
