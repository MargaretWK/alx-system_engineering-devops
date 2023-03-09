`0-iam_betty` switches the current user to the user betty

`1-who_am_i` print the effective username of the current user

`2-groups` print all the groups the current user is part of

`3-new_owner` changes the owner of the file hello to the user betty

`4-empty` creates an empty file called hello

`5-execute` execute permission to the owner of the file hello

`6-multiple_permissions` adds execute permission to the owner and the group owner, and read permission to other users, to the file hello

`7-everybody` adds execution permission to the owner, the group owner and the other users, to the file hello

`8-James_Bond` sets the permission to the file hello as follows:Owner has no permission at allGroup has no permission at all and Other users have  all the permission

`9-John_Doe` sets the mode of the file hello to -rwxr-x-wx

`10-mirror_permissions` copy permission or set the mode of the file hello as the same as olleh’s mode

`11-directories_permissions` adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users and regular files should not be changed

`12-directory_permissions` creates a directory called my_dir with permissions 751 in the working directory.

`13-change_group` changes the group owner to school for the file hello

`100-change_owner_and_group` changes the owner to vincent and the group owner to staff for all the files and directories in the working directory