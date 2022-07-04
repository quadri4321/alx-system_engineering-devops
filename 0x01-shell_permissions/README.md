# Script 0x01 for shell permission

Task 0. Script that switches the current user to the user betty
        . You should use exactly 8 characters for your command (+1 character for the new line)
        . You can assume that the user betty will exist when we will run your script

Task 1. Script that prints the effective username of the current user.

Task 2. Script that prints all the groups the current user is part of

Task 3. Script that changes the owner of the file **hello** to the user **betty**

Task 4. Script that creates an empty file called **hello**

Task 5. That adds execute permission to the owner of the file **hello** 
        . The file **hello** will be in the working directory

Task 6. Script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
        . The file hello will be in the working directory

Task 7. Script that adds execution permission to the owner, the group owner and the other users, to the file hello
        . The file hello will be in the working directory
        . You are not allowed to use commas for this script

Task 8. Script that sets the permission to the file hello as follows:
        . Owner: no permission at all
        . Group: no permission at all
        . Other users: all the permissions

Task 9. Script that sets the mode of the file hello to this:
         -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello

Task 10. Script that sets the mode of the file **hello** the same as **olleh’s** mode.
         . The file hello will be in the working directory
         . The file olleh will be in the working directory

Task 11. Script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed

Task 12. Script that creates a directory called **my_dir** with permissions 751 in the working directory

Task 13. Script that changes the group owner to **school** for the file **hello**
         . The file hello will be in the working directory

Task 14. Script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.

Task 15. Script that changes the owner and the group owner of **_hello** to vincent and **staff** respectively.
         . The file _hello is in the working directory
         . The file _hello is a symbolic link

Task 16. Script that changes the owner of the file **hello** to **betty** only if it is owned by the user **guillaume**
         . The file hello will be in the working directory

Task 17. Script that will play the StarWars IV episode in the terminal.
