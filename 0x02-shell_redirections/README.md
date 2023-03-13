-echo "Hello World"  a script that prints “Hello, World

-echo "\"(Ôo)'" a script that displays a confused smiley "(Ôo)' \ for  print spcial sympols

-cat /etc/passwd Display the content of the /etc/passwd file

-cat /etc/passwd /etc/hosts Display the content of /etc/passwd and /etc/hosts

-tail /etc/passwd Display the last 10 lines of /etc/passwd

-head /etc/passwd Display the first 10 lines of /etc/passwd

-head -3 iacta  a script that displays the third line of the file iacta.

-echo "Best School" > \\\*\\\\"'\"Best School\"\\'\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\) script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line

-ls -la > ls_cwd_content  a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content

-tail -1 iacta >> iacta Write a script that duplicates the last line of the file iacta

-find . -type f -name "*.js" -delete a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders

-find . -type d ! -path . | wc -l a script that counts the number of directories and sub-directories in the current directory

-ls -t . | head a script that displays the 10 newest files in the current directory.

-sort | uniq -u a script that takes a list of words as input and prints only words that appear exactly once

-egrep "root" /etc/passwd Display lines containing the pattern “root” from the file /etc/passwd

-egrep -c "bin" /etc/passwd Display the number of lines that contain the pattern “bin” in the file /etc/passwd

-egrep -A 3 "root" /etc/passwd Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd

-egrep -v "bin" /etc/passwd Display all the lines in the file /etc/passwd that do not contain the pattern “bin”

-egrep ^[[:alpha:]] /etc/ssh/sshd_config Display all lines of the file /etc/ssh/sshd_config starting with a letter

-tr 'Ac' 'Ze' Replace all characters A and c from input to Z and e respectively

-tr -d cC a script that removes all letters c and C from input.

-rev a script that reverse its input.

-cut -d ':' -f 1,6 /etc/passwd | sort a script that displays all users and their home directories, sorted by users

-find . -empty | rev | cut -d '/' -f 1 | rev a command that finds all empty files and directories in the current directory and all sub-directories

-find -type f -name "*.gif" -printf "%f\n" | rev | cut -d '.' -f 2- | rev | LC-ALL=C sort -f
a script that lists all the files with a .gif extension in the current directory and all its sub-directories

-echo $(cut -c1 | tr -d " \n")  a script that decodes acrostics that use the first letter of each line

- tail -n +2 | cut -f -1 | sort -k 1 | uniq -c | sort -rnk 1 | head -11 | rev | cut -d ' ' -f -1 | r
ev a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests 
