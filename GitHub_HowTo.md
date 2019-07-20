# GIT - A version control system
In software development we make many changes time to time where we add a lot of features and remove any of them and feel like somthing missing after removal and try to add them back which is a pretty confusing process to manage which version of our software has that feature and track spectific change happend a long back.

So all that said GIT comes for your rescue  in this situation but not just for individually handlled project but also for team of people working on projects can also get with the flow without loosing what has changed over night by simple commands and also have a glance at changes made by the messages appended with them.

### Git Cloning a Repo.
## Type 1
git clone https://github.com/RajashekarY/MyLearningNotes.git
> To update the local repo with online changes made to original repo 
git pull origin [Branch] # master, development branches to be cloned from
## Type 2
If you are having an empty repo with or without related to the cloning directory but you can link that directory like this  
git init #it is initilisation of git with local directory

> ### Creating a git Repo. in command line    
> * Make a directory in which you want to store all your project files "The ROOT Directory"
>   * In that ROOT directory enter the following commands
```bash
git init
git remote add upstream https://github.com/RajashekarY/MyLearningNotes.git
git pull origin master
```
    
# Git Commands for updating local repo to online 
```bash
git add [file name] # file single file specifically
git add -A # appends all the files in current_dir/local repo
git commit origin [Branch] #Master branch is always deployable so trail/training code on sub branches 
git push
```
