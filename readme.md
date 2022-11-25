#HI


first we initialize a folder creating a git file
using
                           git init

we can add  file s    for to be added into next commit via
   
                           git add readme.md

we can check status of all changes  that are commitable 

                           git status 

we can commit by  (where -m is a message)
                           git commit -m "added readme.md"

once after first commit changes are made if we check the status of the  file there the maded changes will be shown    so we need to add the folder again to make it commitable
                            git add readme.md         
                             !!!!OR!!!!!
                            git add .         #this basically  adds every changes made in the repository
<<<<<<< HEAD
 creating branches for not messing up the master branch

                             git checkout -b newbranch
=======
 before there is  branches that i created so inorder to merge  
>>>>>>> master
                 to merge we use 

                 git merge  master           #it can be master or  any branch


now connecting our local with the cloud repo   we use 
                git add new origin https://github.com/RoysYB/gitlearning.git

now we push our code to the repo (origin : specify which branch,  -u tells to store these settings ie  to store this in the  master branch   so after first time we only need to type   git push and it will be pushed into  master automatically     )
                  
                              git push -u origin master                                        

                              