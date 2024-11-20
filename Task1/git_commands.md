mkdir Task1<br>
cd Task1<br>
echo "hello World!" > README.md<br>
git add .<br>
git commit -m "first commit"<br>
git push<br>
git branch dev<br>
git checkout dev<br>
touch testfile.txt<br>
git add testfile.txt<br>
git commit -m "testfile"<br>
git push --set-upstream origin dev<br>
git branch SaadJbr-new_feature<br>
git status<br>
echo ".*" > .gitignore<br>
echo "!.gitignore" >> .gitignore<br>
git add .gitignore<br>
git commit -m "add .gitignore file"<br>
git push<br>
git checkout SaadJbr-new_feature<br>
echo "my name is saad" >> README.md<br>
git commit -m "README.md changes"<br>
git revert HEAD<br>
git log<br>
git log > log.txt<br>
git branch -D SaadJbr-new_feature<br>