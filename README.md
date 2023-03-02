# WeMakeDevs is OP

- Kunal Kushwaha says that this community is amazing.
- Kunal made this change
- I love MLH
- More power to kunal. love the work which your are doing for the community.
- Anirudh Sharma finds the Community Classroom initiative really great!
-Cool Explanation!!!
new line

when you clone a repository then only the master branch will be downloaded to the local but 
try downloading the zip file then we will be able to download the specific branch.
But in general trying to clone a specific branch is bad practice cuz it may have bugs since it is not the main branch and is not production level
this causes your code to break if the branch you downloaded from has bugs.
But even so if you want to download a specific branch then do:
git clone <url> (this will donwload the main branch)
now git branch -a (this will show all the branches present in the remote)
now git checkout <branch_name>(branch_name at remote) this will create a new branch at local tracking the origin/new_branch at remote.
