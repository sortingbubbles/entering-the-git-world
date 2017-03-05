# "Entering the Git World: Git 101 with a Github After-flavor"
## Άσκηση 4η - Δημιουργία GitHub Repository

Περίληψη: Σε αυτή την άσκηση θα κάνουμε το πρώτο μας repository στο GitHub, θα δημιουργήσσυμε νέο branch, θα ανοίξουμε pull request και θα κάνουμε merge στο master.

1. Ανοίγουμε την σελίδα του GitHub και κάνουμε είσοδο
2. Δημιουργόυμε το πρώτο μας repository. New Repository
3. Στο terminal γράφουμε την εντολή `git init repo-name` για να δημιουργήσουμε νέο τοπικό repository
4. Μεταφερόμαστε στον φάκελο του repository με την εντολή `cd repo_name`
5. Δημιουργούμε ένα νέο αρχείο και γράφουμε ότι θέλουμε
6. Τώρα το προσθέτουμε στην staging area με την εντολή `git add file_name`
7. Κάνουμε το πρώτο μας commit με την εντολή `git commit -m "first commit"`
8. Στην συνέχεια θα προσθέσουμε remote origin του repository μας στο GitHub με την εντολή `git remote add origin https://....git`
9. Και τέλος κάνουμε `push -u origin master`
10. Με την εντολή `git remote -v` μπορούμε να δούμε τις "συνδέσεις" μας
11. Φτιάχνουμε ένα νέο branch με το όνομα experimental
12. Κάνουμε κάποιες αλλαγές στο αρχείο και τις κάνουμε commit.
13. Κάνουμε `push -u origin experimental`
14. Πάμε να δούμε το repository μας στο github
15. Βλέπουμε τα 2 branches
16. Κάνουμε pull request και merge
17. Επιστρέψουμε στο master branch
18. Κάνουμε pull για να έρθουν οι αλλαγές και τοπικά.
