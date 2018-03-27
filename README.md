ssh-keygen -t rsa -b 4096 -C "your@email.com"

cd ~/.ssh

cat id_rsa.pub

#copy whole ssh key
#go to https://github.com/settings/
#go to SSH and GPG keys
#Add New ssh key

#Go back to terminal(SSH Clint)
#Go to the dir that you want put on git repository or /dir/file.ext

git init

#To add all file use (add .)
git add .

#To add specific file (filename.ext / *.ext)
git add *.ext

#continue folowing steps
git commit -m "first commit"

git config --global user.email "yourgitemail@address.com"
git config --global user.name "your name"

#Go to github repository and get clone link
git remote add origin "git clone link"

git push -u origin master

###########################################################


###############
#EVERYDAY TASK#
###############

#Go to develop branch
$git checkout develop (Main Branch)

#To fetch update repository to origin
$git fetch 

#To pull update repository to local 
$git pull

#create new brranch 
$git checkout -b newBranchName(Branch Name)

#Update the feature branch with new code
$git checkout develop
$git merge [New Branch Name]

#After Merge

git add .

git commit -m "Update Massage"

git push origin [New Branch Name]

#go to github.com and create pull request and merge your changes.

git checkout devlop

