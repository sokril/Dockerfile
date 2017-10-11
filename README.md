# Dockerfile
echo "# Dockerfile" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:sokril/Dockerfile.git
git push -u origin master
