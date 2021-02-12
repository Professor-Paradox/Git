to store the git user name and password in ubuntu 
`git config --global credential.helper store` 
then `git pull`  
the next time you type the username and password git will store them in a text file and use it for future purposes.  

to push changes to remote repository first add the email and name of user commiting the changes.  

`git config --global user.email "<email>"`  
`git config --global user.name "<username>"`  
