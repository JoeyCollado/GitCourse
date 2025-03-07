# GitCourse
# Refinement of GIT fundamentals and Version Control
# Mastering git commands

# Git commands
git init

git add .

git commit -m "comment"

git branch -M main

git remote add origin https://github.com/JoeyCollado/GitCourse.git

git pull origin main --rebase

git push origin main

# Git LFS

git lfs install

git lfs track "*.png"

cat .gitattributes

*.glb filter=lfs diff=lfs merge=lfs -text

git add .gitattributes directory/.png

git commit -m "Added file"


