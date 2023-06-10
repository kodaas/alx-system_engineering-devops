#alx-system_engineering-devops 
## 0x01-shell_permissions

### Scripts

* 0-iam_betty --->> Switches the current user to the user ``betty``.

	- You should use exactly 8 characters for your command (+1 character for the new line)
	- You can assume that the user ``betty`` will exist when we will run your script

* 1-who_am_i --->> Prints the effective username of the current user.

	- Example
	```sh
	 julien@ubuntu:/tmp/h$ ./1-who_am_i
	 julien
	 julien@ubuntu:/tmp/h$ 
	```

* 2-groups --->> Prints all the groups the current user is part of.

	- Example
	```sh
	 julien@ubuntu:/tmp/h$ ./2-groups
	 julien adm cdrom sudo dip plugdev lpadmin sambashare
	 julien@ubuntu:/tmp/h$ 
	```

* 3-new_owner --->> Changes the owner of the file ``hello`` to the user ``betty``.

* 4-empty --->> Creates an empty file called ``hello``.

* 5-execute --->> Adds execute permission to the owner of the file ``hello``.

* 6-multiple_permissions --->> adds execute permission to the owner and the group owner, and read permission to other users, to the file ``hello``.

*  7-everybody --->> Adds execution permission to the owner, the group owner and the other users, to the file ``hello``

* 8-James_Bond --->> Sets the permission to the file ``hello`` as follows:

	- Owner: no permission at all
	- Group: no permission at all
	- Other users: all the permissions

* 9-John_Doe ---> sets the mode of the file ``hello`` to this:
	```sh 
	 -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello 
	```

* 10-mirror_permissions --->> Sets the mode of the file ``hello`` the same as ``olleh``’s mode.

* 11-directories_permissions --->> Adds execute permission to all subdirectories of the *current directory* for the owner, the group owner and all other users.

* 12-directory_permissions --->> creates a directory called ``my_dir`` with permissions 751 in the working directory.

* 13-change_group --->> Changes the group owner to ``school`` for the file ``hello``

* 100-change_owner_and_group --->> Changes the owner to ``vincent`` and the group owner to ``staff`` for all the files and directories in the working directory.

* 101-symbolic_link_permissions ---> Changes the owner and the group owner of ``_hello`` to ``vincent`` and ``staff`` respectively.

* 102-if_only --->> Changes the owner of the file ``hello`` to ``betty`` only if it is owned by the user ``guillaume``.

* 103-Star_Wars --->> Play the StarWars IV episode in the terminal.
