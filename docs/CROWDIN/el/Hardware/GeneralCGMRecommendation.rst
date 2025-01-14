Γενικές συστάσεις CGM
**************************************************

CGM υγιεινή
==================================================

Όποιο σύστημα CGM χρησιμοποιείτε, εάν πρόκειται να χρησιμοποιήσετε τη βαθμονόμηση με βάση το αίμα, τότε υπάρχουν κάποιες πολύ σαφείς κανόνες που πρέπει να εφαρμόσετε, ανεξάρτητα από το αν χρησιμοποιείτε το λογισμικό CGM DIY ή τις επίσημες εφαρμογές. 

* Βεβαιωθείτε ότι τα χέρια και το κιτ είναι καθαρά.
* Προσπαθήστε να βαθμονομήσετε όταν έχετε μια σειρά από κουκίδες με ένα επίπεδο βέλος (συνήθως είναι αρκετά 15-30 λεπτά)
* Αποφύγετε τη βαθμονόμηση όταν τα επίπεδα γλυκόζης κινούνται προς τα επάνω ή προς τα κάτω. 
* Κάνετε "αρκετές" βαθμονομήσεις - στις επίσημες εφαρμογές, θα σας ζητηθεί μία ή δύο φορές ανά ημέρα. Σε συστήματα DIY πρέπει να είστε προσεκτικοί για τη συνέχιση χωρίς βαθμονομήσεις.
* Αν είναι δυνατόν, βαθμονομήστε με μερικές από τις μετρήσεις σας σε χαμηλότερο εύρος (4-5mmol / l ή 72-90mg / dl) και μερικές σε ελαφρώς υψηλότερο επίπεδο (7-9mmol / l ή 126-160mg / dl) καθώς αυτό παρέχει μια καλύτερη περιοχή για τη βαθμονόμηση σημείου / κλίσης.

Ρυθμίζοντας τον αισθητήρα(G6)
==================================================

Κατά τη ρύθμιση του αισθητήρα, συνιστάται να μην πιέσετε τον εισαγωγέα πολύ έντονα για να αποφύγετε την αιμορραγία. Το νήμα του αισθητήρα δεν πρέπει να έρχεται σε επαφή με το αίμα.

Αφού ρυθμίσετε τον αισθητήρα, ο πομπός μπορεί να κουμπώσει στο στήριγμα του αισθητήρα. Προσοχή! Πρώτο κλικ στην πλατεία πλευρά και στη συνέχεια πιέστε προς τα κάτω την στρογγυλή πλευρά.

Αντιμετώπιση προβλημάτων 
==================================================

Προβλήματα σύνδεσης
--------------------------------------------------

Η σύνδεση Bluetooth ενδέχεται να διαταραχθεί από άλλες κοντινές συσκευές Bluetooth, όπως μετρητές γλυκόζης αίματος, ακουστικά, δισκία ή συσκευές κουζίνας, όπως φούρνοι μικροκυμάτων ή κεραμικές εστίες. Στην περίπτωση αυτή, το xdrip δεν εμφανίζει τιμές BG. When bluetooth connection is restabilised the data is backfilled.

Σφάλματα αισθητήρα
--------------------------------------------------
Εάν εμφανιστούν επαναλαμβανόμενα σφάλματα αισθητήρων, επιλέξτε μια διαφορετική περιοχή σώματος για να ρυθμίσετε τον αισθητήρα σας. Το νήμα του αισθητήρα δεν πρέπει να έρχεται σε επαφή με το αίμα. 

Συχνά ένα "σφάλμα αισθητήρα" μπορεί να διορθωθεί με άμεση ενυδάτωση και μασάζ γύρω από τον αισθητήρα!

Παράξενες τιμές
--------------------------------------------------
Προσπαθήστε να αλλάξετε τις ρυθμίσεις για αποκλεισμό θορύβου σε xdrip (Ρυθμίσεις - Ρυθμίσεις μεταξύ εφαρμογών - Αποκλεισμός θορύβου).π.χ. "Αποκλεισμός πολύ υψηλού θορύβου".  Δείτε επίσης την ενότητα `Εξομάλυνση δεδομένων BG <../ Χρήση /Smoothing-Blood-Glucose-Data-in-xDrip.html>`_.

Negative Sensor Age
--------------------------------------------------
.. image:: ../images/Troubleshooting_SensorAge.png
  :alt: Negative sensor age

This occurs if there is either a double "CGM Sensor Insert" entry in `actions tab / menu <../Configuration/Config-Builder.html#actions>`_ or a sensor insert with wrong date. Go to treatments tab > careportal and delete the wrong entry.
