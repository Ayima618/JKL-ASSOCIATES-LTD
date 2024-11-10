…or create a new repository on the command line
echo "# my-second" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Ayima618/my-second.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/Ayima618/my-second.git
git branch -M main
git push -u origin main


========================
git add .
git commit -m "Your commit message"
git push
