# 0x01. Shell, permissions
This reaadme file will describe what each script in this directory does

## 0-iam_betty
Create a script that switches the current user to the user ``` betty ```
- You should use exactly 8 characters for your command(+1 charachter for the new line).
- You can assume that the user ``` betty ``` will exist when we run your script.
## 1-who_am_i
Write a script that prints the effective username of the current user.
## 2-goups
Write a script that prints all the groups the current user is part of.
- Note: depending on the user, you will get a different output.
## 3-new_owner
Write a script that changes the owner of the file ``` hello ``` to the user ``` betty ```.
## 4-empty
Write  a script that creates an empty file called ``` hello ```.
## 5-excute
Write a script that adds execute permission to the owner of the file ``` hello ```.
## 6-multiple_permissions
Write a script that adds excute permission ot the owner and the groups owner, and read permission to other users, to the file ``` hello ```.
## 7-everybody
Write a script that adds excution permission to the owner, the group owner and the other users, to the file ``` hello ```.
## 8-james_bond
Write a script taht sets the permission to the file ``` hello ``` as follows: 
- Owner: no permission at all.
- Group: no permission at all.
- Other users: all permissions.
The file ``` hello ``` will be in the working directory You are not allowed to use commas for this script.
## 9-John_Doe
Write a script that sets the mode of the file hello to this:
``` -rxxr-x-wx 1 julien julien 23 sep 20 14:25 hello ```
## 10-mirror_permissions
Write a script that sets the mode of the file ``` hello ``` the same as ``` olleh ```'s mode.
- Note: the mode of ```olleh ``` will not always be 664. Make sure you script works for any mode.
## 11-directories_permissions
Create a script that adds execute permissionu to all subdirectories of the **current directory** for the owner the group owner and all the others and all others users.
Regular files should not be changed.
## 12-directory_permissions
Create a script that create a directory called ``` my dir ``` with permissions 751 in the working directory.
## 13-change_group
Write a script that changes the group  owner to ``` school ``` for the file ``` hello ```.
## 100-change_owner_and_group
Write a script that changes the owner to ```vincent``` and the group owner to ``` staff ``` for all the files and directories in the working directory.
## 101-symbolic_link_permissions
Write a script that changes the owner and the group owner of ``` _hello ``` to ``` vincent ``` and ``` staff ``` respectively.
## 102-if_only
Write a script that changes the owner of the file ``` hello ``` to ``` betty ``` only if it is owned by the user ``` guillaume ```.
## 103-Star_Wars
Write a script that will play the StarWars IV episode in the terminal.
