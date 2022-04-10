# Managing Branches

## Introduction

The last exercise, you learned how to create and merge branches.
Remember, that branches only separate a state of development and always contain the entire project.
Branches need to be synchronized with each other from time to time in order to include important changes done to a different branch.

Let's say, for example, you have two branches for two different features.
If your group partner find a critical bug and fixes it in his branch, you may want to apply the same changes to your branch as well.
While it is possible to manually copy the fix, git provides multiple tools to simplify this process

## (Optional) Resources for more information

## Setup

For this exercise, you can work alone.
You first need to create two branches that will be used in this exercise (choose the names as you want) and push them to the repository.

## Git Cherrypick

When cherry-picking, you apply a **single** commit from another branch to your current branch.
This is important if you want to synchronize single changes.
Remember, that Branches do not always need to be merged back with the original master and can be an independent development branch.
So if you do not want to merge the entire branch and unwanted changes, cherry-pick is your best option.

First, generate a commit for one of the branches your created (lets call that branch A).
Note the commits hash (commit ID) and swap to the other branch (lets call that one B).

To synchronize the commit, use

> git cherry-pick -x [commit ID]

This will 



## Summary

The git history contains all commits, their authors and exact changes.
You can use it to find out what others changed in the project in order to be up-to-date with the status of the project.
The git history should never be altered!