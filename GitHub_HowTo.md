# Git Commands for updating local repo to online 
```bash
- git add [file name] # file single file specifically
  - git add -A # appends all the files in current_dir/local repo
- git commit origin [Branch] #Master branch is always deployable so trail/training code on sub branches 
- git push
```
# Git Cloning a Repo.
1. git clone [repo address](https://github.com/DSPavan/PyClassNotes.git)
> To update the local repo with online changes made to original repo 

If you are having an empty repo with or without related to the cloning directory but you can link that directory like this  
>
```bash
git remote add upstream [git HTTPS URL](https://github.com/DSPavan/PyClassNotes.git)
git pull upstream master
```
    