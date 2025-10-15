# crescendo Music Platform #

Hi All this is our oraganization for crescendo, and it'll mostly be used for all code and assets related to our project. Below is a protocol we should follow when working on this project but other than that lets do our best! 

### Standard Git Protocol ###


**FETCH BEFORE YOU START**

Communication is key for working efficiently, but mistakes happen and we all forget to mention something. Fetch before you start for the day to see if there has been any changes to the repo that you are working on.

EX

`git fetch`

usually followed by

`git pull`

These two commands will get you refreshed with current repository changes and update your local codebase to those changes.





**NEW FEATURES NEW BRANCH**

## USE JIRA BRANCH CREATION FIRST!!! ##

If you can please utilize the create a branch feature of Jira Tasks as that will accomplish the following with minimal steps and be linked to the task in question. Naming convention follows



Keep all work that you are doing on new features and fixes on seperate branches. There will be others 
working on the project with you and we need to maintain decoupled code. So Any feature or fix must have its own branch

EX:

`git branch SCRUM-44-feature-addition-or-bug-fix`

 `git checkout SCRUM-44-feature-addition-or-bug-fix`
 

**For when JIRA branch creation is used**

to utilize the branch you made through the Jira ticket, please use the 'switch' command for git as it will preform the above and link it remote branch tracking 

EX:

`git switch SCRUM-44-feature-addition-or-bug-fix`

> note you don't have to name the branch as such, but you should be descriptive and versioning is commonplace


**COMMIT CHANGES LIKE SAVES**

On any branch you are working on, it pays to have checkpoints in your work. It wont happen often but sometimes you go down the wrong path when writing solutions, and having an easy way to reset your code to previous


**PULL REQUESTS FOR MERGES**

Any completed feature or fix that is finished should have a pull request created such that a peer review can be seen and verified prior to merging into master **
[more about pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)

**MASTER IS PRODUCTION**

The 'master' branch or 'main' branch is the production ready version of our software. No work should be done on this branch... ever. Only merges of verified code should be commited.

