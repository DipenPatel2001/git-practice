# These are git commands 

# Git init 
This will initialize the repo for your workspace

# Git add 
This will add files that you want to commit to the next version
Note: git add .  (this will commit everything to the next version)

# git status
Shows the status 

# git commit -m "Message"
So this will commit all the changes you have changed for this version. Also type a message so you can keep track of changes

git commit -m "message" --amend    (so this will put your changes in the current commit without creating a new one)

# git log
Git log will show the version history

# git reset
The opposite of git add. It will just remove files from the stagin area

# git checkout -- $filename
This will discard all the changes made to a file

# git checkout <hash>
This will checkout different version of the code
git checkout master  (this can be used to checkout to the latest code of branches)

# git checkout <hash> . 
This will restore the files to the version you have in the hash. This will add these changes in the staging area but will not commit for you

# git log --all --graph
Will show a graph 


