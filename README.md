 Decision Tree Classifier (Iris Dataset)

 Περιγραφή
Σε αυτό το project χρησιμοποιούμε Decision Tree Classifier για να ταξινομήσουμε το κλασικό Iris dataset.  
Το Decision Tree είναι ένας από τους πιο απλούς και ερμηνεύσιμους αλγορίθμους Machine Learning, ο οποίος μαθαίνει κανόνες if/else για να προβλέπει την κατηγορία ενός δείγματος.

---

 Βήματα
1. Φόρτωση του Iris dataset από το scikit-learn.  
2. Χωρισμός δεδομένων σε training και test set.  
3. Εκπαίδευση DecisionTreeClassifier με μέγιστο βάθος 3.  
4. Υπολογισμός accuracy και classification report.  
5. Οπτικοποίηση Confusion Matrix.  
6. Οπτικοποίηση της δομής του δέντρου.

---

 Αποτελέσματα
- Accuracy: ~97% (μπορεί να διαφέρει ελαφρά ανάλογα το split).  
- Το δέντρο δείχνει καθαρά τους κανόνες που χρησιμοποιεί για να ξεχωρίζει τα είδη Setosa, Versicolor, Virginica.  
- Η Confusion Matrix δείχνει ελάχιστα ή μηδενικά λάθη στην ταξινόμηση.

---

 Τι έμαθα
- Πώς λειτουργεί το Decision Tree: χωρίζει το dataset με βάση τα features και φτιάχνει «κανόνες».  
- Πώς να χρησιμοποιώ train/test split με stratify για ισορροπημένες κλάσεις.  
- Πώς να κάνω evaluation** με accuracy, classification report και confusion matrix.  
- Πώς να οπτικοποιώ το Decision Tree για να καταλάβω τους κανόνες που έμαθε.

---
