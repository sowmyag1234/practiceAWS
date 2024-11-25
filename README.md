# practiceAWS
git : Central Repo
local repo : central repo
push : local to central
pull : central to local 

/////////(A)steps to push file or data from local to central repo ::::


install git into local machine 
create any folder and redirect to folder and open gitbash
0/config the user like WHO ARE YOU : git config --global user.name "username"
                                   git config --global user.email "emailID"
1/ create a new file with cmd : touch <filename>
2/ now the new file is not stagged and to track/stage the file : git add <filename> {for one file}
                                                                 git add .          {for all files}
3/ move file to local machine to repo : git commit -m "mesg" <filename> {for one file}
                                        git commit -m "mesg"            {for all files}
4/ check the status of the git : git status

now refresh and check whether file added to central repo or not 



////////////////////steps to pull the code from central to local 
0/ add data into the git 
1/ get the updated code : git pull --rebase
2/ newly added data will clones into local repo 

NOTE: if you want to add any data without getting the updated code it will not allow you to update or add any kind of new data into the folder . 
its day to day mandit to get updated code by doing git pull request.






