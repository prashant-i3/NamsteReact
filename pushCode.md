# command when new repo generate
echo "# NamsteReact" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/prashant-i3/NamsteReact.git
git push -u origin main

# command when you have to push code on github
git remote add origin https://github.com/prashant-i3/NamsteReact.git
git branch -M main
git push -u origin main