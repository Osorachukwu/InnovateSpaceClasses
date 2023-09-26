Generally use gitBash for everthing as opposed to powershell

git init - to intialize git on your project
git pull origin main ...used to update your version of the code on github(main branch) 
git pull origin dev ...used to pull from a branch called dev
git push origin main ...used to push your code to the main
git branch osora ...creating my own branch named osora
git branch -a ...to check the branches
git checkout osora ...to cd into a branch with the name osora
git add .   _git stagging used to commit all the files that you have changed soemthing inside, but to stage a particular file use git add src/App.jsx
git commit -m "Text" ...inside the double qoutes the text is where you drop a comment for your commit


NOTE: 
Before you push, first pull from main. Also push directly to that your own branch not the main 
!!!pull requests are used to ask the adim to pull your code that you've pushed into your   branch to the main, this si done on gitHub
!!!to see other peoples branches you have to pull them e.g git pull origin pinky
!!! if you pull someones code e.g git pull origin pinky you'll get a merging error message, with options click on accept both, then make a merge request


