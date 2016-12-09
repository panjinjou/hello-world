"Hello, I am awesome!"

pwd
ls
mkdir hello-world
cd hello-world
git init
git config user.name "Joel Perry"
git config user.email "jinjou@yahoo.com"
git config user.username "panjinjou"
git config -l
touch "readme.txt"
cat "readme.txt"

These commands must be executed each time:
git status
git add "readme.txt"
git commit -m "readme.txt"

git remote add origin/upstream/<RemoteName> https://github.com/panjinjou/hello-world.git
git remote set-url origin/upstream/<RemoteName> https://github.com/panjinjou/hello-world.git

git push origin master

"This file is awesome!"
