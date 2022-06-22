#Create a project with Git 

#Open Git Bash Here 

mkdir <Directory> #mkdir git

cd <Directory> #cd git/

git init <new Directory> #folder we need to work on(git init Project)

cd <new Directory> #cd Project

ls -al

git status

vi <filename.file extension> #vi Project.txt

git status

git add <filename.file extension> #git add Project.txt

git status

git commit -m " " #git commit -m "A new repo from scratch"

git status

#Pushing the local commits to the remote repository on GitHub using https code

#login to github

#Click New

#Type repository name

#Description (Optional)

#Repository Visibility-Public(choose)
                       Internal
                       Private

#Select Initialize this repository with a README

#Click create repository

#Click code in the created repository and copy https link

#In Bash,

git remote add origin <HTTPS link>

git remote -v

git pull origin master

git pull origin master --allow-unrelated-histories

git push origin master

 
