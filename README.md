# Git Assignment - actually-not-an-username

1. What is an issue?:

    An issue is an **artifact** which allows us to track work needed to complete or that is related to a project, for example track features, change requests, bugs, user stories, etc.

1. What is a pull request?
    
    A pull request is a mechanism used to do code-review and merge code from the working branch (generally related to an issue) into the development or even the production codebase used to release to production.

1. Describe the steps to open a pull request?
    
    In order to create a pull request you should: 
    1. Create an origin branch (as I mentioned in the previous point generally related to an issue),.
    1. Do our changes. 
    1. Stage the changes.
    1. Commit the changes.
    1. Push the changes to the branch.
    1. In the GitHub UI do click on Pull Request menu. 
    1. Click on new PR, and select the target branch as the branch that your code should be merged into, and the origin as the branch where you did wrote and commited your changes, and hit create.
 
1. Describe the steps to add a collaborator to a repository (share write permissions)

    1. Go to the settings page of the repo in GH.
    1. Go to Collaborators tab.
    1. Do click on add people.
    1. Find the collaborator username/email.
    1. Do click on add <user> to the repository.
    
1. What is the difference between git and GitHub?

    Git is the code versioning system and GitHub is an UI layer that works over Git.

1. What does git diff do?
    
    Shows the differences that are currently written in the repository files which are not yet staged, against the latest version in the repo (either staged or commited)

1. What is the main branch?
    
    Is the base branch for a repo, it is often used to diferentiate between the code that is released to production and other feature branches.

1. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
    
    No, the best practice is to use Git flow, set different branches and commit to the main branch only using pull requests.