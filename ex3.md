# "Entering the Git World: Git 101 with a Github After-flavor"
## Exercise 3 - Rebasing

1. Open the terminal and run the command `git init ex3` to create the ex3 git repository and folder.
2. Get into that folder by running `cd ex3`
3. Create a file inside that folder with the command `touch bands.txt`
4. Stage the changes with `git add bands.txt`
5. Commit them with `commit -m "add file"`.
6. Create a new branch with the name addbands `git branch addbands`
7. Get into that branch by running `git checkout addbands`
8. Edit the bands.txt file with a text edit, add some bands (e.g. muse, sum41, the beatles) and click save.
9. Stage your changes with the command `git add bands.txt`
10. Commit the changes with `commit -m "added bands"`
11. Return to the master branch `git checkout master`
12. Bring the changes from the addbands branch to master by running `git rebase addbands`
13. Delete the addbands branch by writing `git branch -d addbands`
