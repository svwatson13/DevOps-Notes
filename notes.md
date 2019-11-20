# Notes

## Bash Commands
### What is bash?
### What are the command for the following:

- where am I? pwd
- where can I go? ls = list short ll = list long
- Go somewhere --> cd
- Go to Main root --> cd /
- Go to User root --> cd ~
- Go back a directory: cd ..
- Create a location: mkdir
- Delete: rm
- Remove location: rmdir <directory name>
- Remove location and all files: rm <director name> -rf
- Create a File: touch
- List everything including hidden files:

## Git
### What is git?
### What are the basic commands?

- How do I start tracking a folder? git init
- How do I add files to track? git add <file>
- Check state of git: git status
- How do I commit files? git commit -m '<name of commit>'
- Add Repository link: git remote add origin https://github.com/swatson2019/<name-of-repository.git
- Push to repository: git push -u origin master
- Make new branch: git checkout -b <new branch name>
- Check what repository links are set up: git remote -v
- Change repository link: git remote set-url <new origin
- Remove git: rm -rf .git
<<<<<<< HEAD
- Adding to previously used repository:
<<<<<<< HEAD
git init
git remote add origin https://github.com/swatson2019/<name-of-repository.git
git pull origin master --allow-unrelated-histories
git add '<file name'
git push -u origin master
=======
git pull origin master --allow-unrelated-histories
git add '<file name>'
git push -u origin master
>>>>>>> 4654dc7174c7a7082b6cacdf63d8d61581a12678
=======
>>>>>>> 5706e7981de7ca03e6fd8c3f6b9fdd5d6b2a8483

## Github
### What is Github?
