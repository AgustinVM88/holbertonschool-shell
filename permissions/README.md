0-iam_betty: switches the current user to the user betty
1-who_am_i: Prints the effective username of the current user.
2-groups: prints al the groups the current user is part of
3-new_owner: changes the owner of the file hello to the user betty.
4-empty: create an empty file called hello.
5-execute: adds execute permission to the owner of the file hello.
6-multiple_permissions: adds execute permissions to the owner and the group owner, and read permission to other users, to the file hello.
7-everybody: adds execution permission to the owner, group owner and other users to the file hello.
8-James_Bond: sets the permission to the file hello as follows: owner- no permission ar all; group- no permission at all; other users- all the permissions.
9-John_Doe: sets the mode of the file hello to this: -rwxr-x-wx
10-mirror_permissions: sets the mode of the file hello the same as olleh's mode.
11-directories_permissions: adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
12-directory_permissions: creates a directory called my_dir with permissions 751 in the working directory
13-change_group: changes the group owner to the school for the file hello
14-change_owner_and_group: changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
15-symbolic_link_permissions: changes the owner and the group owner fo _hello to vincent and staff respectively. the file _hello is in the working directory and is a symbolic link
16-if_only: changes the owner of the hello to vincent only if is owned by the user guillaume.
