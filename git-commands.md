
git clone [github url] 
git status 					# to see the status of the files
git add [file name] 				# moves files to staging, this is not required however but good practice
git commit -m "[comments for the commit]"
git push origin 				# to send the committed files to the source control


Branching
git branch [new branch name] #? create on server and then git fetch --all, then git branch --track [branch name] origin/master
git checkout [branch name] #switches you to the branch.
# make you changes
git add --all
git commit -m "comments" #? then git status, git rebase
git push origin [branch name]
# new branch now in remote (github)

? on remote create a new pull request

git checkout master # switch to master branch
git merge [branch name]
git push origin master
