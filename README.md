## What are branches, anyway?

While no one can explain it better than the [git documentation](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell) itself, I'll try and condense what branches are in simple term.

Branches can be thought of as separate versions of the base branch - oftentimes called `main`. (though under the hood they're quite a bit more than that!) They allow us to work on things like files, or adding features, all without changing or messing up the `main` branch. 

## How to branch?

  1. To create a new branch, we can use the command: `git branch <BRANCH NAME>`. You can verify it was create by using the command `git branch` where you should see an output similar to this: 
  
  ![image](https://user-images.githubusercontent.com/114439245/220814519-333c2d98-ece7-4877-98e3-35337a0730a2.png)

  2. Now, to switch to that branch, we can use the `git checkout <BRANCH NAME>` command. You should see an output like this: 
  
  ![image](https://user-images.githubusercontent.com/114439245/220814600-8a1e6b5a-e553-40e6-9465-5a1da2385c3c.png)

  3. We can verify the switch worked by using that `git branch` command again, which should show us an output like this:
  
  ![image](https://user-images.githubusercontent.com/114439245/220814439-847be2b8-1d95-44d9-96c1-2cfe13769aeb.png)
  
## All in one command!

If we wanted to create a new branch and switch to it (check it out) we can use the command: `git checkout -b <BRANCH_NAME>`!
  
  
## New commands!

You can use the new command: `git switch <TARGET BRANCH>` to swap to an already existing branch!

You can also use the `git switch -c <TARGET BRANCH>` to create, and then switch to the created branch. This process is the same as `git checkout -b <TARGET BRANCH>`. 

The `-c` flag in the `git switch -c <NEW BRANCH>` stands for `--create`, makes sense right?!

## Conclusion

Hopefully know you understand how to create branches and swap between them!

