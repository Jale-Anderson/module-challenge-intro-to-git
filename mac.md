## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? __Git is a coding language, with commadns for local repos and repos from GitHub__
2. What is the difference between Git and GitHub? __Git is the coding language used to work with GitHub, while Github is a online repository hub for developers__
3. Why do we create a branch? __Git Checkout -b 'Firstname-Lastname'__
4. What is the purpose of a Pull Request? __Incorporates changes from a remote repository into the current branch.__
5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
__Git checkout <existing branch>__ alternativly if the branch is not created __Git checkout -b <new branch>__
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
__Git fetch; downloads objects and refs from another repo__, __Git merge; Joins two or more development historites together__
7. What is a merge conflict? __Merge conflicts happen when you merge branches that have competing commits, and Git needs your help to decide which changes to incorporate in the final merge. Git can often resolve differences between branches and merge them automatically.__
8. How do you resolve a merge conflict?
__To resolve a merge conflict, you must manually edit the conflicted file to select the changes that you want to keep in the final merge. There are a couple of different ways to resolve a merge conflict:__

__If your merge conflict is caused by competing line changes, such as when people make different changes to the same line of the same file on different branches in your Git repository, you can resolve it on GitHub using the conflict editor. For more information, see "Resolving a merge conflict on GitHub."
For all other types of merge conflicts, you must resolve the merge conflict in a local clone of the repository and push the change to your branch on GitHub. You can use the command line or a tool like GitHub Desktop to push the change. For more information, see "Resolving a merge conflict on the command line."__
