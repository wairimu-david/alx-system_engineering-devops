# Shell, basics

In this project, I underwent an introductory crash course in the Shell. I
learned how to navigate directories using `cd`, `pwd`, `ls`, how to look
around using `ls`, `less`, and `file`, and how to manipulate files with `cp`,
`mv`, `rm`, and `mkdir`. Further, I practiced working with the `type`, `which`,
`help`, and `man` commands, implementing wildcards, reading man pages,
creating links, and using keyboard shortcuts in Bash.

## Tasks :page_with_curl:

* **0. Where am I?**
  * [0-current_working_directory](./0-current_working_directory): Bash script that
  prints the absolute pathname of the current working directory.

* **1. What’s in there?**
  * [1-listit](./1-listit): Bash script that displays the contents list of current directory.

* **2. There is no place like home**
  * [2-bring_me_home](./2-bring_me_home): Bash script that changes the working directory to the
  user's home directory.

* **3. The long format**
  * [3-listfiles](./3-listfiles): Bash script that displays current directory contents in
  long format.

* **4. Hidden files**
  * [4-listmorefiles](./4-listmorefiles): Bash script that displays current directory contents,
  including hidden files, using long format.

* **5. I love numbers**
  * [5-listfilesdigitonly](./5-listfilesdigitonly): Bash script that displays current directory
  contents, including hidden files, as follows:
    * Long format.
    * User and group ID's displayed numerically.

* **6. Welcome  **
  * [6-firstdirectory](./6-firstdirectory): Bash script that creates a directory named `my_first_directory`
  in the `/tmp/` directory.

* **7.Betty in my first directory  **
  * [7-movethatfile](./7-movethatfile): Bash script that moves the file `betty` from `/tmp/` to
  `/tmp/my_first_directory`.

* **8. Bye bye Betty**
  * [8-firstdelete](./8-firstdelete): Bash script that deletes the file `betty` in `/tmp/my_first_directory`.

* **9. Bye bye My first directory **
  * [9-firstdirdeletion](./9-firstdirdeletion): Bash script that deletes the directory `my_first_directory`
  in the `/tmp` directory.

* **10. Back to the future**
  * [10-back](./10-back): Bash script that changes the working directory to the previous one.

* **11. Lists**
  * [11-lists](./11-lists): Bash script that lists all files, including hidden files, in the
  current directory, parent of the working directory, and `/boot` directory, using long format.

* **12. File type**
  * [12-file_type](./12-file_type): Bash script that prints the type of the file named
  `iamafile` located in the `/tmp` directory.

* **13. We are symbols, and inhabit symbols**
  * [13-symbolic_link](./13-symbolic_link): Bash script that creates a symbolic link to `/bin/ls`,
  named `__ls__`.

* **14. Copy HTML files**
  * [14-copy_html](./14-copy_html): Bash script that copies all HTML files from the current
  working directory to the parent of the working directory, but only those that
  did not exist in the parent directory or were newer than the versions in the parent working directory.
