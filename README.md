#Navigation terminal
**cd** ->change directory
- cd ~ ->change directory to home
- cd .. ->change directory back one directory
**ls** ->display what is in current directory with short list
**l** ->display complete file information in the directory
**pwd** ->print working directory, displays where you are in the system
**open** ->command will open a file in default program or directory in finder

#File Manipulation
**man** -> will pull up manual for commands
- `man [command here]` -> will pull up manual for commands
**|** -> pipe will execute command on left first then execute command on right
- `[command here] | [second command here]` -does not work for every command
**>** -> redirects output to a File
- `echo 'text to add' > [File name]` - output directed into file. Will overwrite whats in there.
- `echo 'text to add' >> [File name]` - output appended into file.
**mkdir** -> create new directory from current position
**touch** -> create new file within current directory
**mv** -> move files
-`mv [current file name] [new file name]` -- will rename the file
-`mv [current file name] ./newdirectory/[new file name]` -- will move the file and rename
-`mv [current file name] ./newdirectory` -- will move the file into the listed directory
`.` - means current directory
`..` - means parent directory
**rm** -> removes files or directories -- cannot undo.
-`rm [file name]` -- removes file from system
-`rm -r [directory name]` -- removes directory and all subsequent files
`q`-> quit
ctrl c - quit something...
**grep** -> will search through documents for strings
- `cat [file name] | grep 'string to search'` -- will search contents of file and return if grep string found
- `-n` -- will display line number of found string
- `-A [number here]` -- will display trailing number of lines specified
- `-B [number here]` -- will display preceding number of lines specified
**cat** ->concatenate, or print to terminal, or show in terminal, reads a file(s) and outputs to terminal
- `cat [file name]` -- displays text in files
- `cat [file name] [file name] ....` -- will display file contents of all files selected in order

#Git commands
**git init** -> this will add a local git repository to a directory
**git status** -> this will show files that are untracked or tracked for next commit
**git add** -> will add files to staging for next commit
- `git add [file name]` - will add individual file to staging
- `git add -A` - will add all files to staging
- `git add .` - same as above
**git commit** -> takes staged files and creates save point / commit number
- `git commit -m 'enter in MEANINGFUL commit message'`
**git log** -> shows full log of all commits to master branch
**git checkout** -> creates a new branch
- `git checkout - b [branch name]` -creates a new branch and switches to that branch
- 'git checkout [branch name]' - switches to that branch
- 'git checkout [master]' - switches to master
