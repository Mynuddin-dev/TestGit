# TestGit

### *git init* :
The **'git init'** command is used to initialize a new Git repository in a directory. When you run **git init** in a specific directory, it sets up the necessary data structures and files required for Git to start tracking changes to your project files.

Here's what happens when run git init:

1.  Creation of the Git Directory: The command creates a new hidden directory named ".git" in the root directory of your project. This directory contains all the internal Git metadata and the database that tracks changes.

2.  Initializing a Repository: The ".git" directory is initialized with the necessary files, including a template configuration file and an empty object database.

3.  Default Branch Creation: A default branch named "master" is created, which serves as the starting point for your project's version history. In recent versions of Git, the default branch may be called "main" instead of "master" based on your Git configuration.

Once you have executed git init, the directory where you ran the command becomes a Git repository. You can now use other Git commands to track changes, create branches, commit modifications, and collaborate with others.

It's important to note that git init is typically used only once in a specific directory to initialize a repository. If you run git init in a directory that is already a Git repository, it will have no effect or overwrite the existing repository's data.




## **git add :**
The git add command is used to add changes to the staging area in Git. It prepares the changes you want to commit, allowing you to selectively choose which modifications should be included in the next commit.

***The basic syntax of the git add command is:***


`git add <file>`\

Here, <file> represents the name or path of the file you want to add to the staging area.

*Here are a few common use cases and variations of the git add command:*


To add a specific file to the staging area, you can use:
```
git add filename.txt
This command adds the file named filename.txt to the staging area.
```

Adding Multiple Files:
You can add multiple files to the staging area by specifying their names or paths, separated by spaces:
```
git add file1.txt file2.txt file3.txt
This command adds file1.txt, file2.txt, and file3.txt to the staging area.
```

Adding All Modified Files:
To add all modified files (excluding untracked files) to the staging area, you can use the -u option:
```
git add -u
This command stages all the modifications made to existing tracked files.
```

Adding All Files (Including Untracked Files):
If you want to add all modified and untracked files to the staging area, you can use the . or --all option:
```
git add .
or
git add --all
These commands stage all modifications to existing tracked files as well as any new untracked files.
```

After using git add to stage the changes, you can proceed to commit the changes using the git commit command.