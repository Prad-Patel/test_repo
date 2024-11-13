echo "# test_repo" >> README.md
git init
git add README.md
git commit -m "first commit!"
git branch -M main
git remote add origin https://github.com/Prad-Patel/test_repo.git
git push -u origin main
