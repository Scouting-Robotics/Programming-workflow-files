
# Programming Workflow Exercise

## Commit message Analysis
Before starting this exercise, create a new branch called practice/[first name]

1. Look at the previous commit messages in this repo. Find an example of a good commit message and a bad one. Quote the messages below, and explain why they are good or bad. 

    *[your answer here]*

2. Commit your answer

3. Notice in the changes window there is now an option called "publish branch". Press that button, then when it finishes open the repository on Github.
    1. Select the branches button. ![GitHub branch](assets/github_branch.png) Your branch should now be listed. 
    2. Select that branch, then open exercise.md in the brower. You should see the answer you added under question 1. 

4. Checkout main again, then create a new branch from main. Name this branch practice/[last name]
5. Answer below based on whether you are working in a codespace or on your computer:
    1. Where are you working on this file? _____
    2. Is where you are working on this file a clone of the repo? Why or why not?
6. Commit your answer to question 4.
7. pull your practice/[first name] branch into this branch. (use either pull from in vscode or the command line.)

 ### Note:
You may get an error that looks something like this:

        You have divergent branches and need to specify how to reconcile them.
        You can do so by running one of the following commands sometime before your next pull:

            git config pull.rebase false  # merge
            git config pull.rebase true   # rebase
            git config pull.ff only       # fast-forward only

__If you do, run "git config pull.rebase false" to use a merge, and then try again.__

7. After the pull, you should see your answer to question 1 in this document. 
8. Go to the source control tab and open the graph section. You should see something that looks like this: ![git branch](assets/git_branch.png) 
   This shows the commits made in your practice/<first name> branch, which have now been added to your practice/<last name> branch. Why do you think git adds that history into a branch when merging? 
    *Your answer*

9.  Commit your answer to question 8, then push your branch.
10. create a pull request from your branch to the main branch of your repo. (when choose the base branch, you will see two entries, one for [Your github name]/Programming-workflow-files, and one for ScoutingRobotics/Programming-workflow files. Make sure to choose your repository)