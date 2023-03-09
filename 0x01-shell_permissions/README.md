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

