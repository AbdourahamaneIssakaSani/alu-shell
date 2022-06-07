## 0-iam_betty
switche the current user to the user betty
## 1-who_am_i
print the effective username of the current user
## 2-groups
print all the groups the current user is part of
## 3-new_owner
change the owner of the file `hello` to the user `betty`
## 4-empty
create an empty file called `hello`
## 5-execute
add execute permission to the owner of the file `hello`
## 6-multiple_permissions
add execute permission to the owner and the group owner, and read permission to other users, to the file `hello`
## 7-everybody
add execution permission to the owner, the group owner and the other users, to the file `hello`
## 8-James_Bond
set the permission to the file `hello` as follows:
- Owner: no permission at all
- Group: no permission at all
- Other users: all the permissions
## 9-John_Doe
set the mode of the file `hello` to `-rwxr-x-wx`
## 10-mirror_permissions
set the mode of the file `hello` the same as `olleh`’s mode:
- The file `hello` will be in the working directory
- The file `olleh` will be in the working directory
## 11-directories_permissions
add execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
