# "Entering the Git World: Git 101 with a Github After-flavor"
## Άσκηση 5η - Forking & Cloning

1. Πηγαίνουμε στο repository του osem https://github.com/openSUSE/osem
2. Κάνουμε click αριστερά στο κουμπί Fork και δημιουργούμε ένα αντίγραφο του repository στο λογαριασμό μας
3. Αντιγράφουμε τη διεύθυνσή του repository
4. Κάνουμε clone για να το κατεβάσουμε τοπικά
5. Γράφουμε `git remote -v' για να δούμε τις απομακρυσμένες μας συνδέσεις
6. Προσθέτουμε τη σύνδεση για το original repository του osem με την εντολή `git remote add upstream https://github.com/openSUSE/osem.git'
7. Γράφουμε ξανά `git remote -v` και βλέπουμε ότι μπήκε και η νεά σύνδεση
8. Κάνουμε μερικές αλλαγές σε ένα αρχείο
9. Κάνουμε commit και push