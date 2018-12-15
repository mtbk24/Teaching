# github-help

1. Make a directory in the Github folder.
2. Move to that directory.
3. Run the following, where NAME is the directory (or repository) name:
echo "# NAME" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/mtbk24/Teaching.git
git push -u origin master