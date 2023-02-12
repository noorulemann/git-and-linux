
# GitHub and its some Important Commands

Git is a version control system for software development. It allows developers to keep track of changes made to the code, collaborate with others, and revert back to previous versions if needed. Here are some important and commonly used Git commands:
1.	**git clone** : This command is used to clone a remote repository to your local machine.
2.	**git init**: This command initializes an empty Git repository in the current directory.
3.	**git add**: This command adds a file to the staging area, preparing it for a commit.
4.	**git commit**: This command saves changes to the local repository.
5.	**git push**: This command sends changes to the remote repository.
6.	**git pull**: This command retrieves updates from the remote repository and merges them into the local repository.
7.	**git branch**: This command creates or lists branches in the repository.
8.	**git checkout**: This command switches between branches or restores files to a specific version.
9.	**git merge**: This command combines two branches into a single branch.
10.	**git log**: This command displays the commit history for the repository.
11.	**git status**: This command displays information about the current state of the repository, including any changes that have been made to the files and whether they have been staged for a commit.
12.	**git tag**: A tag is essentially a label that you can apply to a commit, so you can easily find it later. There are two types of tags in Git: 1-lightweight tags and 2-annotated tags.
Lightweight tags are simple pointers to a specific commit. They are created using the git tag command, followed by the name you want to give the tag.
Annotated tags are more powerful than lightweight tags, as they contain additional information, such as a tag message, the tagger's name, and the date the tag was created. To create an annotated tag, you use the -a option with the git tag command.
13.	**git show**: This command displays the details of a specific tag, including the tag message, tagger information, and the commit it points to.
14.	**git revert**: This command is used in Git to undo changes to a repository. Specifically, it creates a new commit that undoes the changes made in a specified commit. This allows you to undo changes while preserving the repository's history.
15.	**git stash**: This command is used in Git to temporarily save changes that have been made to a repository, without committing them to the repository's history. This is useful when you need to switch to a different branch to work on a different task, but you don't want to commit the changes you've made to the current branch.<br>
## GitHub Action
GitHub Actions are automated processes that you can set up in a GitHub repository. Here are some common uses of GitHub Actions:
1.	**Continuous Integration (CI)**: This allows you to automatically build and test your code with every push to the repository.
2.	**Continuous Deployment (CD)**: This allows you to automatically deploy your code to production when certain conditions are met.
3.	**Automated Release Management**: This allows you to automate the process of creating and publishing releases.
To use GitHub Actions, you need to create a workflow file in the .github/workflows directory of your repository. The workflow file is written in YAML and defines the steps that should be taken when the workflow is triggered.

## Linux and its some important commands

Linux is a powerful and versatile operating system that provides a wide range of commands for users to manage and control their system. Here are some of the most commonly used Linux commands:
1.	**ls** - lists the files and directories in a directory
2.	**cd** - changes the current working directory
3.	**pwd** - displays the current working directory
4.	**mkdir** - creates a new directory
5.	**rmdir** - removes an empty directory
6.	**touch** - creates a new file
7.	**cp** - copies files or directories
8.	**mv** - moves or renames files or directories
9.	**rm** - deletes files or directories
10.	**cat** - displays the contents of a file
11.	**less** - displays the contents of a file one page at a time
12.	**grep** - searches for a pattern in a file
13.	**chmod** - changes the permissions of files or directories
14.	**chown** - changes the owner of files or directories
15.	**find** - searches for files or directories based on specific criteria
16.	**gzip** - compresses or decompresses files
17.	**tar** - creates or extracts archive files
18.	**ssh** - secure shell client for logging into a remote machine
19.	**scp** - secure file copy between two systems
20.	**top** - displays information about the system's resources and processes
These are just a few of the many Linux commands available. Each command has specific options and syntax that you can learn more about by reading the manual pages (man command).
