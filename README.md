# Pull Request Practice Repo
One of the big benefits of Git is getting to have multiple people working on different parts of an app at once, and using an organized system to review each other's code and merge those changes together. This exercise will walk you through the workflow you'll be using in group projects and for your own future work.

## All About Git branches
Git "branches" allow you to have different "versions" of your codebase simultaneously. You can have a clean, working version of your code on your `master` branch, and then go to a new branch to work on writing a new feature. Once you're sure the new feature is working and hasn't broken anything, you can merge those changes into your `master` branch (as will be described below!).

When you have multiple people working on the same project, each person should be doing their work in their own branch. Once someone is finished with their current piece of work, they can push all their changes up to the remote repository on Github.com and make a pull request.

A pull request is basically something on Github that says "here are a bunch of changes to our code that I made! I would like those changes to be merged into the `master`	 branch so that they take effect as part of our main code base." (The phrase "pull request" can be thought of as "I am asking the owner of this project to pull in my changes".) It's a nicely-collected set of changes that your whole team can review, and together you can decide whether the changes are ready to merge into your primary code base.

## Basic Workflow
1. Initialize git: `git init`
2. Make first commit: `git add .` --> `git commit -m "initial commit`
3. Add to repositoriy: `git remote add origin <YOUR REMOTE REPO URL>` --> `git push origin master`
4. Make a branch: `git checkout -b <YOUR BRANCH NAME>`
5. Make changes to branch and save
6. Commit your changes
7. Push your changes to remote repo: `git push origin <YOUR BRANCH NAME>`
8. Pull branches on github and merge branches
