1) git init
2) git add filename
3) git commit -m "message"

1) git pull
2) git reset filename
3) git reset commitname
4) The double dashes reduces any ambiguity in case the branch and file name are the same, and in case the file name begins with a single dash.
5) If you make errors that break the code, or want to merge changes that someone else has made instead of using any changes you have made, you may want to revert back to a previous commit.

1) git branch -b branchname
2) git checkout branchname
3) You should work on a branch other than master so that master can be maintained as a fully functional working version of your product.

1) git merge should be used when you want to add changes that you have made on a separate branch to the master branch.  You would use git merge when you are the owner of the master and the one working on the branch.  If you are not maintaining the master, or there are multiple people working on the code it may make sense to submit a pull request instead of forcing a merge yourself.
2) git push origin master
