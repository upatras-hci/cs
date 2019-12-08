
# COLLABORATION TECHNOLOGIES-HCI

Ονοματεπώνυμο: Σπυρίδων Ανισέτο Κατσαμπίρης Σαλγαδο

Α.Μ: 236078

## 1o Παραδοτέο (Δημιουργία Βιογραφικού)
Για την πραγματοποίηση του πρώτου παραδοτέου, επιλέχθηκε το 6ο από τα διαθέσιμα templates. Αρχικά έγινε fork σε δικό που repository και στην συνέχεια ακολουθώντας τις οδηγίες που είχε δημιουργησα το CV.
To link του CV είναι https://spiroskatsampiris.github.io/markdown-cv/.
To link του repository είναι https://github.com/spiroskatsampiris/markdown-cv/tree/gh-pages

## 2ο Παραδοτέο (Δημιουργία Βιογραφικού με χρήση Jekyll, pandoc, pdf)
Για την υλοποίηση του ερωτήματος αυτού, δημιουργήθηκε ένα αρχείο process.sh στο οποίο έχουμε την εξής εντολή 

pandoc https://spiroskatsampiris.github.io/markdown-cv/ -f html-native_divs -o cv.pdf --pdf-engine=xelatex

Η παραπάνω εντολή εκτελείται τοπικά και χρησιμοποιεί ως pdf engine το xelatex
Επιπλέον, προστέθηκε στο html αρχείο η δυνατότητα να κατεβάσει κάποιος το pdf του βιογραφικού σημειώματος, το οποίο δημιουργήθηκε με την παραπάνω εντολή. 
