# Here are the steps that i did to do this in Linux

1) Make a repo

2) Make a folder 

3) Create a document inside the folder naed hello and write some lines

4) go inside the folder you make and open shell

git init
git status
git add .
git commit -m "First GIT commit"
git remote add origin "link"
git remote v (shows fetch and push)
git push -u origin master


git branch  {lists branch}
git branch develop
git checkout develop
git status
git push -u origin develop
{for first tie you need to fo this, next tie just git push should be enough}

Make a new file inside the folder, also efit that hellp file

git status (red color)
git add .
git status (shows same in green)
git commit -m "Secon GIT commit"
git push

{So the second file we made and new changes in the first is just in develop}
{now we need to push it in master}

git checkout master
gut rebase develop
git status
git push

---------------------------------------------------------------------------


