# Git Commands for updating local repo to online 
```bash
git add [file name] # file single file specifically
git add -A # appends all the files in current_dir/local repo
git commit origin [Branch] #Master branch is always deployable so trail/training code on sub branches 
git push
```
# Git Cloning a Repo.
### Type 1
git clone [repo address](https://github.com/DSPavan/PyClassNotes.git)
> To update the local repo with online changes made to original repo 
git pull origin [Branch] # master, development
### Type 2
If you are having an empty repo with or without related to the cloning directory but you can link that directory like this  
git init #it is initilisation of git with local directory

> linking folder and  online git
```
git remote add upstream https://github.com/DSPavan/PyClassNotes.git
git pull origin master
```
    
