# git
https://stackoverflow.com/questions/8775850/how-do-i-add-files-and-folders-into-github-repos


You can add files using git add, example 
git add README
git add <folder>/*
or even 
git add *

Then use 
git commit -m "<edit>"

to commit files

Finally 
git push -u

origin master to push files.

When you make modifications run 
git status

which gives you the list of files modified, add them using 
git add *

for everything or you can specify each file individually, then 
git commit -m <message>

and finally, 
git push -u origin master
