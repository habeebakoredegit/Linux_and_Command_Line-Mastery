# Linux_and_Command_Line-Mastery

## 1. Linux File System Navigation

1. Print the current working directory using `pwd` .

This task was implemented as shown in the image below.
![](./img/001-pwd.png)

2. List all files (including hidden ones) in the home directory with `ls -la` .

This task was implemented as shown in the image below.
![](./img/002-ls-la.png)

3. Change directories into `/etc` and list its contents.

This task was implemented as shown in the image below.
![](./img/003a-cd-etc.png)

![](./img/003b-ls.png)

4. Navigate back to the home directory using relative paths.

This task was implemented as shown in the image below.
![](./img/004-home.png)

5. Use `cd` to toggle beteen the previous and present directories.

This task was implemented as shown in the image below.
![](./img/005-cd-.png)

6. Display absolute path of the `bash` binary using `whereis bash` .

This task was implemented as shown in the image below.
![](./img/006-bash.png)

7. Use `find / -type f -name "passwd"` to locate a file in the system.

This task was implemented as shown in the image below.
![](./img/007-find.png)

![](./img/007b-find-sudo.png)

8. Print directory tree structure using `tree /home/labuser` (after installing `tree`).

This task was implemented as shown in the image below.
![](./img/008-tree.png)

9. Use `du -sh *` to summarize disk usage in the current directory.

This task was implemented as shown in the image below.
![](./img/009-du-sh.png)

10. Use `file` command to check type of `/etc/hosts` .

This task was implemented as shown in the image below.
![](./img/010-file-type.png)

11. Count number of directories in `/etc` using `ls -l | grep ^d | wc -l` .

This task was implemented as shown in the image below.
![](./img/011-count.png)

12. Verify symbolic path of `/bin/sh` using `ls -l /bin/sh` .

This task was implemented as shown in the image below.
![](./img/012-verify-path.png)



## 2. Linux Program Management

1. Update system repositories using `sudo apt update`.

This task was implemented as shown in the image below.
![](./img/1-sudo-apt-update.png)

2. Install `tree` , `nano` , and `nginx` via `sudo apt install -y`.

This task was implemented as shown in the image below.
![](./img/2-sudo-apt-install-y.png)

3. Check versions of installed programs (`tree --version` , `nginx -v`).

This task was implemented as shown in the image below.
![](./img/3-check-version.png)

4. Verify installation paths with `which tree` and `whereis nginx` .

This task was implemented as shown in the image below.
![](./img/4-verify-paths.png)

5. Create and edit a sample text file using `sudo nano test.txt` .

This task was implemented as shown in the images below.
![](./img/5-a-create-nano.png)

![](./img/5-b-edit-nano.png)

6. Display directory structure using `tree /etc/nginx` .

This task was implemented as shown in the image below.
![](./img/6-tree.png)

7. Start nginx service using `sudo systemctl start nginx` .

This task was implemented as shown in the image below.
![](./img/7-start-nginx.png)

8. Enable nginx to start at boot `sudo systemctl enable nginx` .

This task was implemented as shown in the image below.
![](./img/8-enable-nginx.png)

9. Check nginx service status using `sudo systemctl status nginx` .

This task was implemented as shown in the image below.
![](./img/9-nginx-status.png)

10. Verify if nginx is listening on port 80 using `sudo ss -tuln | grep 80` .

This task was implemented as shown in the image below.
![](./img/10-verify-nginx.png)

11. Uninstall and reinstall one package `sudo apt remove tree && sudo apt install tree` .

This task was implemented as shown in the image below.
![](./img/11-remove-install.png)

12. Search for available versions of a package using `apt-cache search nano` .

This task was implemented as shown in the image below.
![](./img/12-search-package.png)

## 3. Linux File Management

1. Create a directory `testdir` using `mkdir testdir` .

This task was implemented as shown in the image below.
![](./img/3-001-mkdir.png)

2. Create an empty file `example.txt` using `touch` .

This task was implemented as shown in the image below.
![](./img/3-002-touch.png)

3. Write content into the file using `echo "Hello Linux" > example.txt` .

4. Append new content using `echo "Learning Devops" >> example.txt` .

This task was implemented as shown in the image below.
![](./img/3-004-append.png)

5. View the file contents using `cat example.txt` .

This task was implemented as shown in the image below.
![](./img/3-005-cat.png)

6. Create a nested directory with `mkdir -p logs/archive` .

This task was implemented as shown in the image below.
![](./img/3-006-nested.png)

7. Copy a file into another location using `cp example.txt logs/` .

This task was implemented as shown in the image below.
![](./img/3-007-cp.png)

8. Rename the file with `mv example.txt example_renamed.txt` .

This task was implemented as shown in the image below.
![](./img/3-008-rename.png)

9. Remove a file using `rm example_renamed.txt` .

This task was implemented as shown in the image below.
![](./img/3-009-rm.png)

10. Remove an empty directory using `rmdir emptydir` .

This task was implemented as shown in the image below.
![](./img/3-010-rmdir.png)

11. Use `head` and `tail` to preview the top/bottom of a file.

This task was implemented as shown in the images below.
![](./img/3-011a-head.png)

![](./img/3-011b-tail.png)

12. Use `stat example.txt` to check metadata (permission, size, etc.).

This task was implemented as shown in the image below.
![](./img/3-012-stat.png)

13. Count number of lines in the file using `wc -l example.txt` .

This task was implemented as shown in the image below.
![](./img/3-013-count.png)

14. Create multiple files in one command: `touch file{1..5}.log` .

This task was implemented as shown in the image below.
![](./img/3-014-multiple.png)

15. Use `ls -lh` to display human-readable file sizes.

This task was implemented as shown in the image below.
![](./img/3-015-human-readable.png)


## 4. Linux File Ownership & Permissions

1. View current file permissions using `ls -l example.txt` .

This task was implemented as shown in the image below.
![](./img/4-001-permission.png)

2. Change permissions to `644` using `chmod 644 example.txt`.

This task was implemented as shown in the image below.
![](./img/4-002-change-permission.png)

3. Add execute permission using symbolic mode (`chmod u+x example.txt`).

This task was implemented as shown in the image below.
![](./img/4-003-add-exe.png)

4. Remove group write permission (`chmod g-w example.txt`).

This task was implemented as shown in the image below.
![](./img/4-004-rm-perm.png)

5. Change file owner to current user using `sudo chown labuser example.txt`.

This task was implemented as shown in the image below.
![](./img/4-005-change-owner.png)

6. Change file group using `sudo chgrp labuser example.txt`.

This task was implemented as shown in the image below.
![](./img/4-006-change-grp.png)

7. Set recursive permissions on a directory (`chmod -R 755 testdir`).

This task was implemented as shown in the image below.
![](./img/4-007-rec-perm.png)

8. Verify permissions with `stat example.txt`.

This task was implemented as shown in the image below.
![](./img/4-008-verify-perm.png)

9. Set default permissions using `umask` and test file creation.

This task was implemented as shown in the image below.
![](./img/4-009-umask.png)

10. Create a shared directory for group collaboration.

This task was implemented as shown in the image below.
![](./img/4-010-shared-dir.png)

11. Assign sticky bit to `/tmp/shared` and test deletion rights.

This task was implemented as shown in the image below.
![](./img/4-011a-stickybit.png)

![](./img/4-011b-test-del.png)

12. Assign SGID bit to `/usr/local/scripts` and create a file inside it.

This task was implemented as shown in the image below.
![](./img/4-012-sgid.png)

13. Change file ownership to another user and verify (`sudo chown root example.txt`).

This task was implemented as shown in the image below.
![](./img/4-013-chown.png)

14. Compare numeric vs symbolic permissions (`chmod 777` vs `chmod ugo+rwx`).

This task was implemented as shown in the image below.
![](./img/4-014-compare-perm.png)

15. Explore permission inheritance in subdirectories.

This task was implemented as shown in the image below.
![](./img/4-015-perm-inher.png)

