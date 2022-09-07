# SHELL REDIRECTION

0. Script 0: 0-hello_world - prints “Hello, World”, followed by a new line to the standard output
1. Script 1: 1-confused_smiley - displays a confused smiley "(Ôo)'
2. Script 2: 2-hellofile - displays the content of the /etc/passwd file
3. Script 3: 3-twofiles - displays the content of /etc/passwd and /etc/hosts
4. Script 4: 4-lastlines - displays the last 10 lines of /etc/passwd
5. Script 5: 5-firstlines - displays the first 10 lines of /etc/passwd
6. Script 6: 6-third_line - displays the third line of the file iacta(found in the current directory)
7. Script 7: 7-file - creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
8. Script 8: 8-cwd_state - writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it
9. Script 9: 9-duplicate_last_line - duplicates the last line of the file iacta
10. Script 10: 10-no_more_js - deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders
11. Script 11: 11-directories - counts the number of directories and sub-directories in the current directory
12. Script 12: 12-newest_files - displays the 10 newest files in the current directory. Displays One file per line and output sorted from the newest to the oldest
13. Script 13: 13-unique - Create a script that takes a list of words as input and prints only words that appear exactly once.
* Input format: One line, one word
* Output format: One line, one word
* Words should be sorted
14. Script 14: 14-findthatword - display lines containing the pattern “root” from the file /etc/passwd
15. Script 15: 15-countthatword - display the number of lines that contain the pattern “bin” in the file /etc/passwd
16. Script 16: 16-whatsnext - display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd
17. Script 17: 17-hidethisword - display all the lines in the file /etc/passwd that do not contain the pattern “bin”
18. Scrip 18: 18-letteronly - display all lines of the file /etc/ssh/sshd_config starting with a letter
19. Script 19: 19-AZ - replaces all characters A and c from input to Z and e respectively
20. Script 20: 20-hiago - removes all letters c and C from input
21. Script 21: 21-reverse - script that reverse its input
22. Script 22: 22-users_and_homes -  displays all users and their home directories, sorted by users. Based on the the /etc/passwd file
23. Script 23: 100-empty_casks - Write a command that finds all empty files and directories in the current directory and all sub-directories.
	* Only the names of the files and directories should be displayed (not the entire path)
	* Hidden files should be listed
	* One file name per line
	* The listing should end with a new line
	* You are not allowed to use basename, grep, egrep, fgrep or rgrep
24. Script 24: 101-gifs -  lists all the files with a .gif extension in the current directory and all its sub-directories.
	* Hidden files should be listed
	* Only regular files (not directories) should be listed
	* The names of the files should be displayed without their extensions
	* The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay)
	* One file name per line
	* The listing should end with a new line
	* You are not allowed to use basename, grep, egrep, fgrep or rgrep
25. Script 25: 102-acrostic - script that decodes [acrostics](https://en.wikipedia.org/wiki/Acrostic) that use the first letter of each line
	* The ‘decoded’ message has to end with a new line
	* You are not allowed to use grep, egrep, fgrep or rgrep
