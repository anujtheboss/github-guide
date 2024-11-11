# github-guide
```bash
rm -rf .git ==Delete Git Version History: All the version history, branches, commit logs, and any tracking of changes will be lost.
git init
git add .
git commit -m"message" (virtually)
```
```bash
git remote remove origin == remove current origin 
git remote add origin <repo url>
git push -u origin main/master(make actual changes to the git)
```

## merging
```bash
git add .
git commit
git checkout main
git merge anuz
```

## conflict
```bash
git status(to see the conflicted file eg:log/templates/blog/test.html)
git checkout --theirs blog/templates/blog/test.html
```
### OR
```bash
git checkout --ours blog/templates/blog/test.html
git add blog/templates/blog/test.html
 git commit
```
## a table of contents
- [about](#about)
- [installation](#installation)
- [usage](#usage)
- [features](#features)
## the table of information
| name | rollno | faculty|
|------|--------|--------|
| ram  |   3    | science|
| shyam|   5    |commerce|
| hari |   6    |english |
## some pictures
<img src="https://static.businessinsider.com/image/5484d9d1eab8ea3017b17e29/image.jpg" width='500' />

