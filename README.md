# Setting_Up_Git_In_Ubuntu
Setting your Git and GitHub in Ubuntu

Step 1: Make your GitHub Account on www.github.com

Step 2: Setup your profile

Step 3: Open terminal and run the following commands to link the git to github profile
  1) sudo apt update -> to update the local packages.
  2) git --version -> it will tell you whether you already have git installed or not, if not follow the below steps.
  3) sudo apt install git -> it will install the git and then check the version of git using above command.
  4) git config --global user.name "name" -> it will create a local host of your git which we will connect to main host on github
  5) git config --global user.email "localhost.gmail.com" -> email id used in creating your github account or id you use on your device in which you have git
  6) git config --list -> it will display the username and email-id you enter for using git in ubuntu, verify it properly.
  7) mkdir workspace -> in which you will use the repositories and git cloning.

Step 4: Open the github and then create the repositories and name it also if you want it to make a README.md file of that repo which describes and guides through that repo the nenable the Readme.md option.

Step 5: There will be a code option in green colour above the repo you have made and in that copy the link.

Step 6: Open the workspace, run this command git clone "replace copied url of your repo and remove inverted commas."

Step 7: ls -> to check whether the cloning is done or not, cat README.md to see the content of README file.

Step 8: make a demo python or any programming using touch and and any editor like gedit or nano and save it in same folder in which you want to push it like in demo repo in which README.md is there.

Step 8: run 'git status' -> to check the status of the file in which it will be shown in red colour saying that the file is untracked.

Step 9: to track it use 'git add "file"' and then check the status again the file will be in green colour which means it is now ready to be pushed on github repositories.

Step 10: git commit -m "demo file to add and commit" file is still uncommitted and be done using this command.  Now if you check the status it will say you are 1 step ahead 

Step 11: 
