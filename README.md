# common-git-commands
Common Git Commands I would like to remember or have handy, without having to parse google.
Really this is likes notes for me, but if I help newbies I'd be very happy :-)


## You **NEED** to Know
### git init
- first, make sure you have git installed...FTLOG
- this will initialize git to control the files of your current directory.
- E.G. cd c:/Users/HLBoun/Documents/Coding
    - "git init" will setup git in the /Coding/ folder
### git add -A
- adds **all** files to be ready for commit. Useful when you start a new project.
### git add .
- adds all changed files to be ready for commit
### git commit -m "Put message here SIX SEVEN"
- commits your code **locally** with a short message
### git remote add https://github.com/HLBoun/RepoNameHere
- links a remote repo to your local git repository
- essential for vim users *and* any type of professionality
- Obviously, you would change the link to be *your* repo. 
### git push -u origin main
- -u flag means set upstream
- pushes code **AFTER** committing it locally
- **IMPORTANT** origin can be a different name, like a variable. Origin is common though.

## You **SHOULD** know
### git clone https://github.com/HLBoun/common-git-commands
- Clones a repository at your current directory (in terminal...these are all temrinal commands)
- if you have a project you've started on your desktop, and have **never** touched on your laptop. Start with this on your laptop
### git pull
- updates your local repo to match whatever is in your remote repo
- *if i can remember*, I do this before I start writing code in a preestablished local repo
### git branch
- tells what local branch you are in, and shows other branches.
### git branch <name>
- creates a new branch locally
### git checkout <branch name>
- switches your local branch
### git log
- shows chronological list or commit history
- important for knowing if *you* are the one that messed up

## Pocket Mousekatools
### git switch --orphan <branch name>
- creates an orphan branch. Good for making a release branch with **no prior commit history**



