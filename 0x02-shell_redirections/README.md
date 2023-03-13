0-hello_world - script that prints “Hello, World”
1-confused_smiley - a script that displays a confused smiley
2-hellofile - Display the content of the /etc/passwd file.
3-twofiles - Display the content of /etc/passwd and /etc/hosts
4-lastlines - Display the last 10 lines of /etc/passwd
5-firstlines - Display the first 10 lines of /etc/passwd
6-third_line - script that displays the third line of the file iacta
7-file -  a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:)' containing the text Best School ending by a new line.
8-cwd_state -  a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
9-duplicate_last_lin - a script that duplicates the last line of the file iacta
10-no_more_js - a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
find . -mindepth 1 -type d | wc -l a script that counts the number of directories and sub-directories in the current directory.
12-newest_files - a script that displays the 10 newest files in the current directory.
sort | uniq -u - a script that takes a list of words as input and prints only words that appear exactly once.
grep root /etc/passwd - Display lines containing the pattern “root” from the file /etc/passwd
grep -c bin /etc/passwd - Display the number of lines that contain the pattern “bin” in the file /etc/passwd
grep -A 3 root /etc/passwd - Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
grep -v bin /etc/passwd - Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
grep ^[[:alpha:]] /etc/ssh/sshd_config - Display all lines of the file /etc/ssh/sshd_config starting with a letter.
