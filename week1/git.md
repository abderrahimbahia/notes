## Git vs Git Bash vs Github
- Git - version control, keep track of changes, allow for collaboration
- Gitbash - an interface for using Git, we can use Git Bash to enter Git commands, but it's not the only place we can enter Git commands
    - We can also use GitBash for Linux/Unix commands
- Github is a place to host our code, projects, or anything else. We don't have to use Github with Git, there other alternatives (Gitlab, etc.)

## Github
- Repository - a collection of code
    - Usually only one project in a repository or even one part of a project
    - Normally, we don't put multiple projects in one repo
    - In our case, we'll have a repo for notes, demos, exercies, projects, etc.
    - can be public or private
- Organization - a group of repos
    - I have an organiation set up for this training that contains, or will contain multiple repos

## Git Commands
- git clone - take a repo that exists on Github or somewhere else and copy it onto my local machine
    - git clone https://github.com/Revature-Training-1302/notes is going to clone the contents from that repo onto my local computer
- cd or change directory so that we're inside of the repo
- we should said some blue text that says "(main)", this means we're on the main branch
    - We'll get into branches later but just keep in mind that this tells us we are inside of the repo
- Make any changes we want to the code
    - In our case, we added the notes files from earlier today
    - We also made a week1 folder
- Once we're done making these changes, we cant to push the changes back up to Github (or whatever website)
    - git status - lets us see the status of our files and folders
    - git add - stage our files, move our files from unstages to staged
        - git add os.md would take os.md from unstaged to staged
        - git add . - add everything that you changed to staged

