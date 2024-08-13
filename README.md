# LearningGit
# git
learning how to use git
git clone https://github.com/Pragya-12112001/git.git // https
ls
ls -a // to see  hidden files
git status // to check modification or new files (untracked files)

ADD & COMMIT
git add . // to add all files
git add filename // to add specific file

git commit -m "some message"   // to commit with a message

PUSH
git push origin master // to push to remote repository. 

INIT used to create new repo
git init // Initialized empty Git repository 

git remote add origin https://github.com/Pragya-12112001/git.git // uploading files from local to github

git remote -v // to verify origin

git branch // to check branch
git branch -M main //to rename branch

git checkout branch name // to navigate from one branch to another

git checkout -b branch name // to create new branch
git checkout -d branch name // to delete a branch

MEARGING CODE
git diff branch name // to compare commits, branches, files & more
git merge branch name // to merge branch into current branch

PULL COMMAND
git pull origin branch name // to pull from remote repository