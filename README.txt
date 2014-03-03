git-push-branch is a command-line tool that automates a very common
action when you are working with git branches. Suppose your flow of
working with Git is like:

 1) Checkout a remote branch, or create a new branch that is pushed to
    a remote.

 2) Write code and commit to your local repository.

 3) git push to the remote.

Step 3 is normally done via the command:

  git push -u origin <branch_name>

... which is a lot of typing, in particular if you employ the good
practice of using long descriptive branch names, and if you (like me)
are often working with multiple branches.

git-push-branch automates this. It determines the current branch, and
pushes it to the remote. By default it asks you to verify the branch
before pushing (to make sure you are pushing to where you think you
are).

LICENSE

This software is in the public domain.

AUTHOR

Aaron Maxwell - amax AT redsymbol DOT net
