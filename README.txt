export PS1="%m@ %1~ %#"

echo "# robodora" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/sarasaraokaki/robodora.git
git push -u origin main

git remote add origin https://github.com/sarasaraokaki/robodora.git
git branch -M main
git push -u origin main