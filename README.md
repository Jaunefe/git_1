# git_tutorial
learn to use git (git tutorial)

GIT

console commands
git init (Start a project)

git add <file> (add the files from working area to staging area)

git status (to know where are the project)

git commit (send the files from the staging area to the repository)

git push ( To send your files to the remote repository)

git pull ( update all the changes from all the colaborates)

git clone (To get a local copy from the project)

three states

working directory

        (git add)--->
        
                    stagging area
                    
                        (git commit)--->
                        
                                    repository.
                                    


git add

    add files to the git (stagging area)
    
git commit

    Send changes to the repository
    
git status

    show status branch and files status
    
git log

    Shows all the versions and comments of the project.
    
git checkout -- filename.dot 

    Deletes changes in the file
    
git diff filename-dot  

    -show diferences between the version files.
    
    
Add a directory for test that will be ignored by git.


    1.- Create a directory where the test files live and it will be ignored by 
    git (remember git will ignore empty directories, so write at lest one file)
    
    2.- Write in the root directory of the project a file named ".gitignore"
    
    3.- Edit that file adding the name of the directories that will be ignored
    
    4.-Git detects the changes thru the status command if some changes have 
    occurred in the ignored directories. You will see in the console that 
    something changes in the .gitignore file you can commit this changes that 
    will haven´t any effect on the ignored files, but has been reported

Commit from cli

    git commit -m "Mesage, what about the change"
    
Branching

git branch 

    shows the branches available and in which branch you are
    

git branch  branchName

   starts a new branch using the name assigned with a snapshot of the master
   
git checkout branchName

    Close the current branch, and opens the branch that has the name provided
    
git add .

    Add all the files in the current directory.
