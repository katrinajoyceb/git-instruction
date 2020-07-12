# How To: Make a commit to a repository using the Mac OS Terminal
This is how you commit a change to a github repository.

## Requirements
1. Beginner Github user
2. Some knowledge of the Terminal

## Clone your repository
### Find the url for the repository you want to work with. 
You can usually find the url on your browser search bar, or by clicking on the 'Code' button on the Github page. 
![git clone](https://github.com/katrinajoyceb/git-instruction/blob/master/picture/01.png)
### Using the terminal, clone the project to your local directory using this git command:
```
git clone <url-to-your-repo>
```
![git clone](https://github.com/katrinajoyceb/git-instruction/blob/master/picture/03.png)

## Go to directory 
### To list all of the items in your current directory, use the command:
```
ls
```
![git clone](https://github.com/katrinajoyceb/git-instruction/blob/master/picture/06.png)
Here you can see that the project you have just cloned is the folder *git-instructions*, in the example's case.
### To go to the directory of your project, use the command:
```
cd <name-of-your-project>
```
![git clone](https://github.com/katrinajoyceb/git-instruction/blob/master/picture/cd.png)

## Create a file
Now that you're inside of the project, you can create files or modify files. 
### Create a file by using the command:
```
touch <name-of-file>
```
You can verify if you've made the file by using the **ls** command. 
![git clone](https://github.com/katrinajoyceb/git-instruction/blob/master/picture/08.png)


## Or modify a file
If you want to modify a file,
### Edit a file by using the command:
```
vi <name-of-file>
```
This allows you to modify a file using the built in text editor within the Terminal. 
![git clone](https://github.com/katrinajoyceb/git-instruction/blob/master/picture/11.png)

## Add files to be commited
After you've done all of the changes, you will want to add these files to so they can be commited. 
### You can check the status of your files by using the git command: 
```
git status
```
![git clone](https://github.com/katrinajoyceb/git-instruction/blob/master/picture/Screen%20Shot%202020-07-11%20at%2011.08.40%20PM.png)
You can see that the new files you've made are untracked and won't be commited. 
### You can change their status to tracked by using the git command: 
```
git add .
```
(add explanation for .)
![git clone](https://github.com/katrinajoyceb/git-instruction/blob/master/picture/Screen%20Shot%202020-07-11%20at%2011.08.50%20PM.png)

## Create a commit message
It's good to provide a short message about the change that you are commiting into the repository. 
### You can add a message by using the git command: 
```
git commit -m "your-message-here"
```
![git clone](https://github.com/katrinajoyceb/git-instruction/blob/master/picture/Screen%20Shot%202020-07-11%20at%2011.09.21%20PM.png)

## Push your commit to repo
### After that, you can finally push your changes into the repository!
```
git push 
```
![git clone](https://github.com/katrinajoyceb/git-instruction/blob/master/picture/Screen%20Shot%202020-07-11%20at%2011.09.45%20PM.png)

## Done! 
### Check the Github page to view your changes.
![git clone](https://github.com/katrinajoyceb/git-instruction/blob/master/picture/Screen%20Shot%202020-07-11%20at%2011.09.59%20PM.png)
