git --version

git config --global user.name "{{NAME}}"
git config --global user.email "{{EMAIL}}"

git init

git status

git add {{FILENAME}}

git add .

git commit -m "{{MESSAGE}}"

git remote add origin {{URL}}

git push origin {{BRANCH=master}}