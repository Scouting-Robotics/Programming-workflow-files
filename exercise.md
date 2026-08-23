
# Programming Workflow Exercise

## Commit message Analysis

1. Look at the previous two commit messages in this repo. briefly explain below which commit message is a good and which is bad, and why.

<your answer here>

2. Commit your answer

3. Notice in the changes window there is now an option called "publish branch". Press that button, then when it finishes open the repository on Github.
    a. Select the branches button. ![GitHub branch](assets/github_branch.png) Your branch should now be listed. 
    b. Select that branch, then open exercise.md in the brower. You should see the answer you added under question 1. 

3. Go back and create a new branch from main. Name this branch practice/<last name>
4. Answer below based on whether you are working in a codespace or on your computer:
    a. Where are you working on this file? _____
    b. Is where you are working on this file a clone of the repo? Why or why not?
5. Commit your answer to question 4.
6. pull your practice/<first name> branch into this branch. (use either pull from in vscode or the command line.)

 ### Note:
You may get an error that looks something like this:
        hint: You have divergent branches and need to specify how to reconcile them.
        hint: You can do so by running one of the following commands sometime before
        hint: your next pull:
        hint:
        hint:   git config pull.rebase false  # merge
        hint:   git config pull.rebase true   # rebase
        hint:   git config pull.ff only       # fast-forward only
If you do, run "git config pull.rebase false" to use a merge, and then try again.

7. After the pull, you should see your answer to question 1 in this document. 
8. Go to the source control tab and open the graph section. You should see something that looks like this: ![git branch](assets/git_branch.png) This shows the commits made in your practice/<first name> branch, which have now been added to your practice/<last name> branch. Why do you think git adds that history into a branch when merging? 
    Your answer:


9. Commit your answer to question 8, then push your branch.
10. create a pull request from your branch to the main branch of your repo. (when choose the base branch, you will see two entries, one for [Your github name]/Programming-workflow-files, and one for ScoutingRobotics/Programming-workflow files. Make sure to choose your repository)