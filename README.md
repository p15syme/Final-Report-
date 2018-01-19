# Τελική Αναφορά
## Αριστοτέλης Συμεωνίδης
### ΑΜ: Π2015178
#### e-mail: p15syme@ionio.gr
##### https://github.com/p15syme/mm 
##### https://github.com/p15syme/Super-Mario/tree/mas
##### https://p15syme.github.io/Super-Mario/

## Σύνοψη:
  Δημιουργήθηκε το παίχνιδι Super Mario. Αρχικά, ο χρήστης μπορεί να επιλέξει να παίξει μία από τις δύο πίστες. Επίσης, ενημερώνει τον χρήστη τι χρειάζεται να κάνει για παίξει σωστά το παιχνίδι. Στη συνέχεια, ο χρήστης παίζει με τα βελάκια ,όπως στο κλασσικό Super Mario. Όταν φτάσει το σκορ των 14.000 πόντων και πατήσει Enter πάει στο δεύτερο επίπεδο. Στη συνέχεια, όταν φτάσει σε ένα συγκεκριμένο σκορ, το οποίο δεν είναι γνωστό και πατήσει Enter, κερδίζει το παιχνίδι, όπου και εμφανίζεται ένα μήνυμα στην οθόνη.
  
## Εισαγώγη:
  
Στα πλαίσια του μαθήματος των Πολυμέσων, το οποίο ανήκει στον  Ε' εξάμηνο του κύκλου σπουδών του Τμήματος Πληροφορικής στο Ιόνιο Πανεπιστήμιο, έφτιαξα την παρούσα εργασία, της οποίας η θεματική ήταν η δημιουργία ενός παιχνιδιού Super Mario. Παρακάτω, δίνεται η διαδικάσια, οιδυσκολίες αλλά και τα αποτελέσματα με την οποία ολοκληρώθηκαν και τα τέσσερα ζητούμενα παραδοτέα. 

## Επιλογή Εργαλείων: 

Για την ανάπτυξη του παιχνιδιού χρησιμοποίησα αρχικά το github, όπου βάζοντας όλο το υλικό -εικόνες, ήχους, πηγαίο κώδικα- το παιχνίδι τρέχει online. Έπειτα, για την ανάπτυξη του πηγαίου κώδικα χρησιμοποίησα το Sublime Text, σε συνδυασμό με τα εργάλεια για προγραμματιστές που διαθέτει το πρόγραμμα περιήγησης Mozilla Firefox. Τα εργάλεια του Mozilla Firefox, χρησιμοποιήθηκαν για να γίνει το debugging στον πηγαίο κώδικα. Επιπλέον, χρησιμοποιήθηκε το πρόγραμμα επεξεργασίας εικόνων GIMP, για την δημιουργία τόσο των καινούργιων εχθρών, που ζητήθηκαν στο δεύτερο και τρίτο παραδοτέο, αλλά και για την δημιουργία των κουμπιών τα οποία χρησιμοποιούνται για την επιλογή επιπέδου στο αρχίκο μενού. Τέλος, για την δημιουργία των δύο επιπέδων, στα οποία παίζει ο χρήστης χρησιμοποιήθηκε το πρόγραμμα Tiled.

## Διαδικασία Ανάπτυξης:

Αρχικά, δημιουργήθηκε η αναφορά, που ζητούσε το link του παιχνιδιού στην αναφορά. Πιάνοντας το δεύτερο παραδοτέο, χρειάστηκε να μελετηθεί ο δωσμένος πηγαίος κώδικας, έτσι ώστε να γίνουν σωστά όλες οι μετατροπές που ζητούνται. Έτσι, στη συνέχεια, χρησιμοποιώντας το πρόγραμμα Tiled, αλλά και την εικόνα super_mario_tiles, οπου διέθετε τα tiles για την πίστα δημιούργησα μία καινούργια. Στη συνέχεια, χρησιμοποιώντας το GIMP, άλλαξα την αμφίεση του Super Mario και των νομισμάτων. Τέλος, τροποποιώντας τον πηγαίο κώδικα, προσέθεσα τα score, bonus και ζωές. Έπειτα, για το τρίτο παραδοτεό, αλλάζοντας πάλι τον πηγαίο κώδικα, προσέθεσα καινούργιους εχθρούς, και έδωσα την δυνατότητα στον παίκτη να κάνει teleport σε συγκεκριμένο σημείο στη πίστα. Το menu, δημιουργήθηκε με το background χρώμα, δύο κουμπιά από τα οποία επιλέγει κανείς σε ποια πίστα θέλει να παίξει, αλλά και από κάποιους τίτλους. Το animation στο τέλος της πίστας δεν δημιουργήθηκε. Για το τέταρτο παραδοτεό, και πάλι αλλάχθηκε ο πηγαίος κώδικας, με τέτοιο τρόπο έτσι ώστε μόλις φτάνει το στόχο για της πρώτης πίστας, με το πάτημα του πλήκτρου enter να παιρνάει στη δεύτερη πίστα. Δίνονται και ενδεικτικά κομμάτια του κώδικα που μπήκανε για την εκπόρευση των παραδοτέων, Παρακάτω, στο τμήμα των ενδεικτικών οθόνων, παρατίθενται πληθώρα εικόνων, σχολιασμένοι κατάλληλα για να γίνει αντιληπτό, που έγιναν οι αλλαγές. 

```
var Ajump = new Audio ('audio/jump.wav');
var Acoin = new Audio ('audio/coin.wav');
var Astomp = new Audio ('audio/stomp.wav');
var Amariodie = new Audio ('audio/mariodie.wav');
var Aworldmusic = new Audio ('audio/worldmusic.mp3');
var Abowser = new Audio ('audio/bowser.wav');
```
```
var score = 0;
var scoreText;
scoreText = game.add.text (16, 14, 'Score: 0', {fontSize: '12px', fill: '#000'});
scoreText.fontWeight = 'bold';
scoreText.fixedToCamera = true;
var lives = 4;
var livesText;
livesText = game.add.text(180, 14, 'Lives : 4', { font: '12px Arial', fill: '#000'});
livesText.fontWeight = 'bold';
livesText.fixedToCamera = true;
```
```
mons = game.add.group();
mons.enableBody = true;
map.createFromTiles(12, null, 'mon', 'stuff', mons);
mons.callAll('animations.add', 'animations', 'walk', [ 0, 1 ],
		1, true);
mons.callAll('animations.play', 'animations', 'walk');
mons.setAll('body.bounce.x', 1);
mons.setAll('body.velocity.x', -30);
mons.setAll('body.gravity.y', 500);
```
```
mons = game.add.group();
mons.enableBody = true;
map.createFromTiles(12, null, 'mon', 'stuff', mons);
mons.callAll('animations.add', 'animations', 'walk', [ 0, 1 ],
		1, true);
mons.callAll('animations.play', 'animations', 'walk');
mons.setAll('body.bounce.x', 1);
mons.setAll('body.velocity.x', -30);
mons.setAll('body.gravity.y', 500);
```

## Ενδεικτικές Οθόνες:

#### Παραδοτέο 1:
  https://github.com/p15syme/mm 
  
#### Παραδοτέο 2:


### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/p15syme/Final-Report-/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
