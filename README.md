# TestGit

### *git init* :
The **'git init'** command is used to initialize a new Git repository in a directory. When you run **git init** in a specific directory, it sets up the necessary data structures and files required for Git to start tracking changes to your project files.

Here's what happens when run git init:

1.  Creation of the Git Directory: The command creates a new hidden directory named ".git" in the root directory of your project. This directory contains all the internal Git metadata and the database that tracks changes.

2.  Initializing a Repository: The ".git" directory is initialized with the necessary files, including a template configuration file and an empty object database.

3.  Default Branch Creation: A default branch named "master" is created, which serves as the starting point for your project's version history. In recent versions of Git, the default branch may be called "main" instead of "master" based on your Git configuration.

Once you have executed git init, the directory where you ran the command becomes a Git repository. You can now use other Git commands to track changes, create branches, commit modifications, and collaborate with others.

It's important to note that git init is typically used only once in a specific directory to initialize a repository. If you run git init in a directory that is already a Git repository, it will have no effect or overwrite the existing repository's data.
