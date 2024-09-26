# github-guide
rm -rf .git ==Delete Git Version History: All the version history, branches, commit logs, and any tracking of changes will be lost.
git init
git add .
git commit -m"message" (virtually)

git remote remove origin == remove current origin 
git remote add origin <repo url>
git push -u origin main/master(make actual changes to the git)


=====merging========
git add .
git commit
git checkout main
git merge anuz


====conflict======
git status(to see the conflicted file eg:log/templates/blog/test.html)
git checkout --theirs blog/templates/blog/test.html
OR
git checkout --ours blog/templates/blog/test.html
git add blog/templates/blog/test.html
 git commit
