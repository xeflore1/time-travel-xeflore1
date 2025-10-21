Through this lab I feel that I became more comfortable with the process of creating and merging branches, along with resolving merge conflicts. 

One mistake I made was pushing to a new branch that didn't already have a history using the command:

    git push

I resolved this using the command:

    git push --set-upstream origin <branch-name>

Another mistake I made was working with branches that were created on an outdated version of main, to update these branches I used the commands: 

    git fetch origin
    git rebase origin/main
