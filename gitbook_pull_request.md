# Creating a GitBook pull request

These steps explain how to create a pull request for one of our GitBook books. It assumes you're modifying this book, but the commands apply to other books as well.

These commands assume that you have already created a branch in GitBook and made the changes on that branch.

    # First-time setup
    mkdir team
    cd team
    git init
    git remote add gitbook https://git.gitbook.com/material-motion/material-motion-team.git
    git remote add origin git@github.com:material-motion/material-motion-team.git
    
    # Update the gitbook branches
    git fetch gitbook
    # Enter your GitBook email/password
    
    # Create a branch for your GitBook branch
    git checkout -b yourbranch gitbook/yourbranch
    
    # Push the branch to GitHub
    git push origin yourbranch
    
    # Start a pull request on the web ui
