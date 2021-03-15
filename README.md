# Some basic Git commands are:
```
- git init                                           //initialize a git repository

- git status                                         // show the status of all the files in local repo

- git add .                                          // add all the files to the staging area

- git commit -m "your message about this commit"      // commit all the uncommitted files 

- git branch                                        //list all the branches

- git branch branch_name                            //create a branch with name branch_name

- git checkout branch_name                          //checkout the branch, branch_name

- git checkout -b branch_name

- git remote add upstream "link of remote repo"     //to setup upstream for a remote repo to your local repo

- git pull upstream branch_name                     //to pull any branch from the remote repo to your local repo

- git merge branch_name                             //to merge the branch named branch_name to the checked out branch

- git remote add origin "link of your repo"         //to setup origin to your repo on github to the local repo

- git push -u origin branch_name                    // to push any branch to the origin

- git log                                           //list previous commits

- git revert commit_id                              //to uncommit a commit

- git remote -v                                     //list the setups

- git remote set-url origin "link of the repo"      // to reset the origin to yoyr repo on github to the local repo

- git config --global user.name "your-github-username"  //to set the username and email by which you commit the repo
  git config --global user.email "your-github-email"

//to squash number of commits in a single commit  
- git log                                    //show all the previous commmits
- git rebase -i HEAD~<no of commit>         //rebase the commit and change the pick into squash/s
- follow necessary commands
- git push -u origin <branch name> --force
- 
```
