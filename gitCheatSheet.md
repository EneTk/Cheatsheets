Git
git config --global user.name "EneTk"
git config --global user.email "173016082+EneTk@users.noreply.github.com"
git init (creates .git in current dir)

git add filename (adds the file)
git add --all (adds everything in dir)
git commit -m "comment" (commit new files)
git commit -a -m "comment" ( commit updated/modified files)

git status ( check repo) // git status --short (shows status with flags 
    ?? - Untracked files
    A - Files added to stage
    M - Modified files
    D - Deleted files
 )
git log ( view history)

git help --all ( lists all commands)
git commit -help ( lists commit commands)

git branch branchname ( creates a branch named branchname)
git branch ( shows all branches)
git checkout branchname (switches to the branchname branch)

In cases i need to make something in one branch but dont want to disturb other branches, i can switch to an emergency branch
git checkout -b emergency-fix
fixing things
git add fixed.file

To merge we go to 
git checkout master
git merge emergency-fix
git branch -d emergency-fix ( to delete the branch)
more on branch merging on : https://www.w3schools.com/git/git_branch_merge.asp?remote=github


Git and Github;

git remote add origin https://github.com/EneTk/Cheatsheets.git
git remote set-url origin "path/to/github/repository"
git branch -M main
git push --set-upstream origin main ( needs to be used only one, later on "git push origin" is enough)


Pull/fetch from github
git fetch origin

check logs
git log origin/master
git diff origin/master ( check diffs)

git pull origin ( fetch + merge )







Ostalo


code *.txt (vsc opens file) 
