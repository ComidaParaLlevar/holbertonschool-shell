0-iam_betty script changes the current user to the user betty.
1-who_am_i script prints the effective username of the current user.
2-groups script prints all the groups the current user is part of.
3-new_owner script changes the owner of the file hello to the user betty.
4-empty script creates an empty file called hello.
5-execute script adds execute permission to the owner of file hello.
6-multiple_permissions script adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
7-everybody script that adds execution permission to the owner, the group owner and the other users, to the file hello.
8-James_Bond script that sets the permission to the file hello as follows:Owner: no permission at all, Group: no permission at all, Other users: all the permissions.
9-John_Doe script that sets the mode of the file hello to -rwxr-x-wx.
10-mirror_permissions script mirrors olleh's permissions on hello file.
11-directories_permissions script adds execute permissions to all subdirectories of the current directory for the owner, the group and all other users. Regular files not changed.
12-directory_permissions script creates a directory called my_dir with permissions 751 in the working directory.
13-change_group script changes the group owner to school for the file hello.
14-change_owner_and_group script changes the owner and the group owner to staff for all the files and directories in the working directory.
15-symbolic_link_permissions script changes the owner of _hello to vincent and staff respectively.
16-if_only script changes the owner of the file hello to vincent only if its owned by user guillaume.

