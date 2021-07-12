# "Entering the Git World: Git 101 with a Github After-flavor"
## Exercise 4 - GitHub Repository Creation

Summary: In this exercise we will create a new repository in github, as well as open a pull request and merge to the main branch.

1. Go to GitHub and login
2. Click on the New repository button, choose the name of your new repository (in our case it's going to be `repo-name`) and click create.
3. Go into your terminal and write the command `git init repo-name` to create the local repository.
4. Get inside the folder with the command `cd repo_name`
5. Create a new file with the command `touch repo_file.txt`
6. Stage that file `git add file_name`
7. Commit the changes `git commit -m "first commit"`
8. Link the remote repository that you created with this one by running the command `git remote add origin https://....git` where the address in https:// is the address of your github repository.
9. Push the changes to the remote repository by running `push -u origin master`
10. With the command `git remote -v` we can see the links to the remore repositories.
11. Create a new branch called experimental with the command `git branch experimental`
12. Do some changes to the repo_file.txt, stage and commit them `git commit -am "some changes"`
13. Run the command `push -u origin experimental` to push everything from this branch remotely.
14. Go into the repository to see the changes we made.
15. Check the two branches.
16. Open a pull request from experimental to master.
17. Squash and merge the changes
18. Go back into your terminal and run the command `git pull` to update your local repository.
