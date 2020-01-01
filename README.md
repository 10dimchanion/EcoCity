# Οικολογική πόλη (EcoCity)
Το θέμα της συμμετοχής μας έχει να κάνει με μια πόλη που αγαπά το περιβάλλον  κ χρησιμοποιεί την τεχνολογία για να το προστατεύει.
Στα πλαίσια αυτής της πόλης θα υπάρχουν οι παρακάτω αυτοματισμοί:
* Έξυπνα φώτα που ανάβουν όταν υπάρχει κίνηση στο δρόμο αλλιώς παραμένουν κλειστά.
* Σύστημα πυρανίχνευσης που μας ειδοποιεί για την παρουσία καπνού στα πάρκα κ δάση της πόλης
* Σύστημα αυτόματου ποτίσματος που λαμβάνει υπόψη την υγρασία του εδάφους καθώς κ την πρόγνωση του καιρού πριν ποτίσει
* Ηλιακό πάρκο της πόλης που ηλεκτροδοτεί όλους αυτούς τους αυτοματισμούς 

Η βασική αρχιτεκτονική της έξυπνης οικολογικής πόλης μας στηρίζεται σε μικροελεγκτές που με τη βοήθεια αισθητήρων καταλαβαίνουν τι γίνεται γύρω τους και αντιδρούν κατάλληλα στο εκάστοτε ερέθισμα.
Έτσι όταν ο πιεζοηλεκτρικός μετατροπέας πατηθεί απο ένα αυτοκίνητο που πλησιάζει το arduino ανάβει τα φώτα.
Ο μηχανισμός πυρανίχνευσης βασίζεται σε ένα αισθητήρα καπνού που ειδοποιεί το arduino για τον κίνδυνο πυρκαγιάς για να χτυπήσει ο συναγερμός.
Το esp 8266 διαβάζει την υγρασία του εδάφους με τον αισθητήρα υγρασίας κ αφού ελέγξει κ την προβλεψη του καιρού μπαίνοντας στο διαδίκτυο, αποφασίζει αν πρέπει να ανοίξει την ηλεκτροβάνα κ να ποτήσει. 
Τέλος η ηλιακή μας κυψέλη φορτίζει 2 μπαταρίες λιθίου ώστε όλοι αυτοί οι αυτοματισμοί να λειτουργούν με ανανεώσιμες πηγές ενέργειας. 



Για την υλοποίηση των παραπάνω μηχανισμών χρειαζόμαστε την ακόλουθη λίστα υλικών:
* 1 arduino uno 
* 1 esp8266
* 1 αισθητήρα υγρασίας εδάφους
* 1 αισθητήρα ανίχνευσης καπνού 
* 1 buzzer
* 1 ηλεκτροβάνα 
* 1 ηλιακή κυψέλη με κύκλωμα φόρτισης μπαταρίας λιθίου
* 2 μπαταρίες λιθίου 3,7 volts
* λαμπάκια led
* 1 πιεζοηλεκτρικό μετατροπέα
* 1 τρανζίστορ
* 1 φωτοαντισταση 
