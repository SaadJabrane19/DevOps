mkdir Task1
cd Task1
echo "hello World!" > README.md
git add .
git commit -m "first commit"
git push
git brach dev
git checkout dev
touch testfile.txt
git add testfile.txt
git commit -m "testfile"
git push --set-upstream origin dev
git branch SaadJbr-new_feature
git status
echo "# Ignore node_modules directory" > .gitignore
echo "node_modules/" >> .gitignore
echo "" >> .gitignore
echo "# Ignore log files" >> .gitignore
echo "*.log" >> .gitignore
echo "" >> .gitignore
echo "# Ignore compiled files" >> .gitignore
echo "*.class" >> .gitignore
echo "" >> .gitignore
echo "# Ignore environment files" >> .gitignore
echo ".env" >> .gitignore
git add .gitignore
git commit -m "add .gitignore file"
git push
git checkout SaadJbr-new_feature
echo "my name is saad" >> README.md
git commit -m "README.md changes"
git revert HEAD
git log
git log > log.txt
git branch -D SaadJbr-new_feature