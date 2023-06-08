#alx-system_engineering-devops 
## 0x00-shell_basics

### Scripts

* 0-current_working_directory --->> Prints the absolute path name of the current working directory.

* 1-listit --->> Display the contents list of your current directory.

* 2-bring_me_home --->> Changes the working directory to the user’s home directory.

* 3-listfiles --->> Display current directory contents in a long format.

* 4-listmorefiles --->> Display current directory contents, including hidden files (starting with ``.``). Use the long format.

* 5-listfilesdigitonly ---> Display current directory contents.
	- Long format
	- with user and group IDs displayed numerically
	- And hidden files (starting with ``.``)

* 6-firstdirectory --->> Create a script that creates a directory named ``my_first_directory`` in the ``/tmp/`` directory.

* 7-movethatfile --->> Move the file ``betty`` from ``/tmp/`` to ``/tmp/my_first_directory``.
	- Example 
	```sh
	 $ ./7-movethatfile
	 $ ls /tmp/my_first_directory/
	 betty
	 $
	```

* 8-firstdelete --->> Delete the file betty.
	- The file betty is in /tmp/my_first_directory
	- Example
	```sh
	 $ ./8-firstdelete
	 $ ls /tmp/my_first_directory/
	 $
	```

* 9-firstdirdeletion ---> Delete the directory ``my_first_directory`` that is in the ``/tmp`` directory.
	- Example
	```sh
	 $ ./9-firstdirdeletion
	 $ file /tmp/my_first_directory
	 /tmp/my_first_directory: cannot open /tmp/my_first_directory (No such file or directory)
	 $
	```

* 10-back --->> changes the working directory to the previous one.   

* 11-lists --->> Lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the ``/boot`` directory (in this order), in long format.

* 12-file_type --->> Prints the type of the file named ``iamafile``. The file ``iamafile`` will be in the ``/tmp`` directory when we will run your script.

* 13-symbolic_link --->> Create a symbolic link to ``/bin/ls``, named ``__ls__``. The symbolic link  is in the current working directory.
	- Example
	```sh
	 ubuntu@ip-172-31-63-244:/tmp/sym$ ls -la
	 total 144
 	 drwxrwxr-x  2 ubuntu ubuntu   4096 Sep 20 03:24 .
 	 drwxrwxrwt 12 root   root   139264 Sep 20 03:24 ..
	 ubuntu@ip-172-31-63-244:/tmp/sym$./13-symbolic_link
	 ubuntu@ip-172-31-63-244:/tmp/sym$ ls -la
	 total 144
	 drwxrwxr-x  2 ubuntu ubuntu   4096 Sep 20 03:24 .
	 drwxrwxrwt 12 root   root   139264 Sep 20 03:24 ..
	 lrwxrwxrwx  1 ubuntu ubuntu      7 Sep 20 03:24 __ls__ -> /bin/ls
	```

* 14-copy_html --->> Copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

	You can consider that all HTML files have the extension ``.html``

* 100-lets_move --->> Moves all files beginning with an uppercase letter to the directory ``/tmp/u``.

	You can assume that the directory ``/tmp/u`` will exist when we will run your script.

* 101-clean_emacs --->> Deletes all files in the current working directory that end with the character ``~``.

* 102-tree --->> Create a script that creates the directories ``welcome/``, ``welcome/to/`` and ``welcome/to/school`` in the current directory.

	You are only allowed to use two spaces (and lines) in your script, not more.

* 103-commas --->> lists all the files and directories of the current directory, separated by commas ``(,)``.

* school.mgc --->> Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.
