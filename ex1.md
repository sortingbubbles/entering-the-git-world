# "Entering the Git World: Git 101 with a Github After-flavor"
## Exercise 1 - To-Do List

Summary: In this exercise we will create our first local repository!

1. Open a terminal app
2. Create a new folder with the name *ex1* by executing `mkdir ex1`
3. Get in that folder by executing `cd ex1`
4. After entering in the folder we created type `git init` and click enter.
5. Create a new file with the name todolist.txt by typing `touch todolist.txt`
6. Without closing the terminal, find that file from Finder and open it with a text editor of your choice.
7. Write one line to the todolist.txt (e.g. Tidy room) and click save.
8. Go back to the terminal and write `git status` to see that your changes are being tracked by git.
9. Stage your changes by writing `git add todolist.txt` or `git add .`
10. Check again the status of your project by typing `git status`.
11. Commit your changes by typing `git commit -m "morning to-do".
12. Go back to the text editor and add one more todo in a new line (e.g. wash dishes) and click save.
13. Go to the editor and write `git diff` to see the changes between the staging and working directories.
14. You can use the `git log` command to see the previous commits.
15. To discard the working changes and not stage them we can execute `git checkout -- .`.
16. Now go back to the editor, delete the line that you added initially and stage the changes by executing `git add .`.
17. To go back from the staged changes to what we had before we can run the command `git reset`. Now the changes are no longer in staging mode, but in working.
18. To discard the changes and return to our starting point we can type again `git checkout -- .`
