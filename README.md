# repository-to-mirror
```
echo "# repository-to-mirror" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:itsazzad/repository-to-mirror.git
git remote -v
git remote add --mirror=push mirror ssh://git@bitbucket.org/itsazzad/mirrored.git
git remote -v
cat .git/config
git push -u origin master
git push
git push mirror
```
