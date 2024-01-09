#What is version control?
Version control is a system of keeping track of changes made to a file over time which makes previous versions of the file easily recalled or retrieved. VCS Version control systems allow developers to keep track of changes made to our code over time, also allows us to undo mistakes and even collaborate with other developers on code.

##Explain difference between git and github
1. GIT is the most popular VCS Version control system today. It was created by Linus Trovalds and was deployed in 2005. It is designed to help developers keep track of their code and, efficiently handle projects on very different scales with speed and efficiency.

2. GITHUB is a web-based hosting service for git repositories. It makes Git more user-friendly and also provides a platform for developers to share code with others.

###List 3 other github alternatives
Three Other alternatives for github include gitlab, AWS ode commit, and bit bucket.

####Explain the difference between git fetch and git pull,
1. Git Fetch command is used to fetch all changes from the remote repository to the local repository without making any changes to the current working directory. In order to effect these changes in out cwd we use the git merge command.

2. Git Pull command is used to fetch all changes from the remote repository to the current working directory, automatically trying to merge them into our current working directory. It is the combination of git fetch and git merge commands.

#####Explain in simple terms git rebase and the command for it
Rebasing in Git is a process of integrating a series of commits on top of another commit base. It adds or put on top all the commits of a branch and onto to the commits of a new branch. 
-Command:
`git rebase master branch_x`
The command above takes the commits of the master branch the head of branch_x

######Explain in simple terms git cherry-pick and the command for it
git cherry-pick simply takes a commit from one branch and applies it to another branch like, but not as, rebase.
-Command:
`git cherry-pick<commit-hash>`
where commit-hash is a unique identifer for all commits made geneated by git.
