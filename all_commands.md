To see the git version:

git —version

To intialize repository:

git init

To see a .git file

ls -a

To track a file :

git add filename or .

To stage:

git commit -m "message"

To see difference before track:

git diff filename

To see difference after track:

git diff —staged filename

To see status:

git status

To see logs or history

git log

To quit from git log

q

To remove file from stage

git rm —cached filename

To remove file from stage and also in local folder

git rm filename

or

git rm -rf filename (for permanently delete a file from your computer)

After delete a file you need to commit a change:

git commit -m "filename deleted"

Unstage the changes that you made: —————-

git reset HEAD

Then remove the file changes: (to get a older version of your code)

git restore filename.ext

To remove commited changes:

git reset —hard commit_address_of_below_one_for_right_one_to_delete