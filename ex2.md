# "Entering the Git World: Git 101 with a Github After-flavor"
## Exercise 2 - Merge Branches και Conflicts

1. Open the terminal and execute `git init ex2`. That will create a folder with a new git repository.
2. Run the command `cd ex2` to get in that new folder.
3. Create a new file inside the folder with the command  `touch ratings.txt`
4. Add it to the staging changes by running `git add ratings.txt` and commit by running `commit -m "add file"`
5. Run the command `git branch` to see all the existing branches
6. Create a new branch with the name firstratings by running the command `git branch firstratings`
7. Type again the command `git branch` to see your newly created branch
8. To change to that branch type `git checkout firstratings`
9. Edit the file ratings.txt, by opening it with an editor and adding some movie ratings (eg Arrival 10, Interstellar 10, Emoji movie 3) and click save.
10. Type `git status` to see the status of our file.
13. Add your changes to the staging mode by running `git add ratings.txt`
14. Commit the changes with `commit -m "First ratings!"`
15. Return to our previous branch by typing `git checkout master`
16. By chekcign the ratings.txt file we see that our changes are not included in this branch.
17. Type `git merge firstratings` to bring them to this branch.
18. Delete the firstratings branch by running the command `git branch -d firstratings`.
19. Create a new branch and go into that with the following command `git checkout -b moreratings`
20. Add some more movie ratings, save the file and run the command `git commit -am "more ratings!"` to both stage and commit the changes.
21. Return to the master branch with the command `git checkout master` and make some changes to the existing ratings.txt.
22. Stage and commit them by running the command `git commit -am "some editing"`
23. Now we will try to merge the changes we did in the moreratings branch to the master branch by runnign the command `git merge moreratings`
24. And we get a conflict! We have to resolve it. 
25. Go to the ratings.txt file and check the conflicts. 
26. Edit, save the changes you want to keep and run the command `commit -am "resolved conflict"` to commit them.
27. Delete the moreratings branch by running the command `git branch -d moreratings`.
