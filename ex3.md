# "Entering the Git World: Git 101 with a Github After-flavor"
## Άσκηση 3η - Rebasing

1. Ανοίγουμε το τερματικό και εκτελούμε την εντολή `git init ex3` για να δημιουργήσουμε κατευθείαν το φάκελο και το repository
2. Μπαίνουμε στο φάκελο με την εντολή `cd ex3`
3. Δημιουργούμε ένα αρχείο μέσα στο φάκελο (πχ bands.txt)
4. Το κάνουμε add στο staging mode με την εντολή `git add bands.txt` και κάνουμε commit με την εντολή `commit -m "add file"`
5. Πληκτρολογούμε την έντολή `git branch`
6. Φτιάχνουμε ένα νέο branch με το όνομα addbands με την εντολή `git branch addbands`
7. Ξαναπληκτρολογούμε την εντολή `git branch` για να δούμε το νέο branch που δημιουργήσαμε
8. Για να αλλάξουμε branch εκτελούμε την εντολή `git checkout addbands`
9. Στη συνέχεια επεξεργαζόμαστε το αρχείο bands.txt, προσθέτοντας σε κάθε σειρά ένα αντικείμενο και από δίπλα την βαθμολογία του (πχ muse)
10. Πληκτρολογούμε την εντολή `git status` για να δούμε τι γίνεται με το αρχείο μας
11. Προσθέτουμε το αρχείο bands.txt σε staging mode με την εντολή `git add bands.txt`
12. Κάνουμε commit τις αλλαγές μας με την εντολή `commit -m "added bands"`
13. Επιστρέφουμε στο αρχικό μας branch με την εντολή `git checkout master`
14. Βλέπουμε ότι οι αλλαγές μας δεν έχουν γίνει στο αρχείο bands.txt, επειδή βρίσκονται σε άλλο branch
15. Με την εντολή `git rebase addbands` φέρνουμε τις αλλαγές του addbands branch στο master!
16. Διαγράφουμε το branch addbands με την εντολή `git branch -d addbands`
