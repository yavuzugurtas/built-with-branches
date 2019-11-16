## Incremental Development with Branches

> these changes were made on ```master``` before merging ```header-footer```

This is a simple little website to practice using git branches and incremental development.

> these changes were made on ```master``` before merging ```main-text```

Can you replicate it exactly?  Not just the code, but the branches and commits!

Learning to create and merge branches is only the beginning.  The trickier and more important skill is lining up your branches with the steps of incremental development.

> these changes were made on ```master``` before merging ```interesting-links```

If you're having trouble visualizing the branches in this repository, try taking a look at [the network visualization](https://help.github.com/en/articles/viewing-a-repositorys-network) in the "insights" tab.

> these changes were made on ```master``` after merging ```aside-info```

But wait!  How are forks different from branches?  It's true that these are very similar, but the difference is important.
* Forks allow different github users to store their own copy of an entire GitHub repository and work on the project without effecting the main repository.
* Branches allow one user to make changes in their repository (fork) without effecting the master branch.

So a simple way to understand the difference at first is that forks have the same purpose as branches, but at a higher level.
* Repositories are cloned: when you clone a repository from GitHub it will copy that project into a new folder on your computer
* Branches are pulled: when you pull a branch from GitHub it will create a new branch _inside_ the folder you have already cloned

This will take some practice to really wrap your head around and that's totally normal!

> these changes were made on ```master``` before merging ```final-touches```

### Exercises

Before starting the exercises make sure to fork this repository and clone the repository locally from your fork.

#### Add some trees

- Create a new branch called ```trees``` and checkout that branch.
- Add a ```section``` above the ```footer``` with some pictures (```<img />```) of your favourite trees.
- Commit and push the changes.
- Checkout the ```master``` branch.
- Merge the ```trees``` branch into the ```master``` branch.
- Push the merge to the remote ```master```

#### Combining trees

*please complete the exercise above this first*

- Checkout the ```master```
- Merge in the changes from the ```extra-info```
- You should get a conflict right now. Why ? Because a commit on the ```extra-info``` branch also added a section of trees.
- Resolve the conflict and make sure to only have 1 ```section``` of trees. 
- Push the result.

That's all the words for now.

---
---
### <a href="https://hackyourfuture.be" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/63941625-4c7c3d00-ca6c-11e9-9a76-8d5e3632fe70.jpg" width="100" height="100" alt="Hack Your Future: Belgium"></img></a>
