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
