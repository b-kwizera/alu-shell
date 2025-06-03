# Shell I/O Redirections and Filters

## 0-hello_world
This script prints "Hello, World" followed by a new line to the standard output.
### 1-confused_smiley
Prints the string `"(Ôo)'\` to standard output, including quotes and special characters.
### 2-hellofile
Displays the content of the `/etc/passwd` file using `cat`.
8-cwd_state: Writes the output of ls -la into ls_cwd_content (overwrites or creates it)
9-duplicate_last_line: Appends a duplicate of the last line of iacta to the same file
10-no_more_js: Deletes all regular .js files in the current directory and its subdirectories
12-newest_files: Displays the 10 newest regular files in the current directory
13-unique: Prints only the words that appear exactly once from a list, sorted alphabetically
14-findthatword: Displays lines containing the pattern 'root' from /etc/passwd
15-countthatword: Displays the number of lines containing 'bin' in /etc/passwd
16-whatsnext: Display lines with 'root' and 3 lines after them from /etc/passwd
17-hidethisword: Display lines not containing 'bin' from /etc/passwd
18-letteronly: Display lines starting with a letter from /etc/ssh/sshd_config
19-AZ: Replace all A and c with Z and e in input
20-hiago: Remove all letters c and C from input
21-reverse: Reverse the input using rev command
22-users_and_homes: List users and home directories from /etc/passwd, sorted by user
23-empty_casks: Find and list all empty files and directories by filename
24-gifs: List all .gif files (hidden included), names only, sorted case-insensitively
25-acrostic: Extracts and prints the first letter of each line from stdin (acrostic decoder)
26-the_biggest_fan: Extracts host field from TSV logs, counts requests, sorts by frequency, and displays top 11 hosts
