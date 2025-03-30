# Git commands and usage examples

<!-- General Command -->

create git folder: mkdir
select folder: cd
new branch rename: git branch -m <name>
show all item in that folder: ls
if it is a part of our repo: git status
show short status: git status --short
stage a file: git add <filename>
stage all files: git add --all or git add -A
stag for that directory and it's subdirectory: git add .
add without deleted: git add *
only selected all file: git add *.<extension>
commit: git commit -m "here goes message"
commit directly : git commit -a -m ""
reset commit to before stage: git reset HEAD~
reset deleted file with file: git reset --hard
git delete: git rm <file> git rm <filename> -f
see commit history: git log
See all the available options for the specific command: git command -help
jump the end: shift:g
exit: q
make any file: touch <filename.extention>
which location: pwd
back forward: cd ../

<!-- Note -->

Short status flags are:

    ?? - Untracked files
    A - Files added to stage
    M - Modified files
    D - Deleted files

<!-- Branch Command -->
