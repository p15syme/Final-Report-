# Τελική Αναφορά
## Αριστοτέλης Συμεωνίδης
### ΑΜ: Π2015178
#### e-mail: p15syme@ionio.gr
###### https://github.com/p15syme/mm 
###### https://github.com/p15syme/Super-Mario/tree/mas
###### https://p15syme.github.io/Super-Mario/

## Σύνοψη:
  Δημιουργήθηκε το παίχνιδι Super Mario. Αρχικά, ο χρήστης μπορεί να επιλέξει να παίξει μία από τις δύο πίστες. Επίσης, ενημερώνει τον χρήστη τι χρειάζεται να κάνει για παίξει σωστά το παιχνίδι. Στη συνέχεια, ο χρήστης παίζει με τα βελάκια ,όπως στο κλασσικό Super Mario. Όταν φτάσει το σκορ των 14.000 πόντων και πατήσει Enter πάει στο δεύτερο επίπεδο. Στη συνέχεια, όταν φτάσει σε ένα συγκεκριμένο σκορ, το οποίο δεν είναι γνωστό και πατήσει Enter, κερδίζει το παιχνίδι, όπου και εμφανίζεται ένα μήνυμα στην οθόνη.
  
## Εισαγώγη:
  
Στα πλαίσια του μαθήματος των Πολυμέσων, το οποίο ανήκει στον  Ε' εξάμηνο του κύκλου σπουδών του Τμήματος Πληροφορικής στο Ιόνιο Πανεπιστήμιο, έφτιαξα την παρούσα εργασία, της οποίας η θεματική ήταν η δημιουργία ενός παιχνιδιού Super Mario. Παρακάτω, δίνεται η διαδικάσια, οιδυσκολίες αλλά και τα αποτελέσματα με την οποία ολοκληρώθηκαν και τα τέσσερα ζητούμενα παραδοτέα. 

## Επιλογή Εργαλείων: 

Για την ανάπτυξη του παιχνιδιού χρησιμοποίησα αρχικά το github, όπου βάζοντας όλο το υλικό -εικόνες, ήχους, πηγαίο κώδικα- το παιχνίδι τρέχει online. Έπειτα, για την ανάπτυξη του πηγαίου κώδικα χρησιμοποίησα το Sublime Text, σε συνδυασμό με τα εργάλεια για προγραμματιστές που διαθέτει το πρόγραμμα περιήγησης Mozilla Firefox. Τα εργάλεια του Mozilla Firefox, χρησιμοποιήθηκαν για να γίνει το debugging στον πηγαίο κώδικα. Επιπλέον, χρησιμοποιήθηκε το πρόγραμμα επεξεργασίας εικόνων GIMP, για την δημιουργία τόσο των καινούργιων εχθρών, που ζητήθηκαν στο δεύτερο και τρίτο παραδοτέο, αλλά και για την δημιουργία των κουμπιών τα οποία χρησιμοποιούνται για την επιλογή επιπέδου στο αρχίκο μενού. Ακολούθως, για την δημιουργία των δύο επιπέδων, στα οποία παίζει ο χρήστης χρησιμοποιήθηκε το πρόγραμμα Tiled. Τέλος, όλα κινήθηκαν γύρω από το εργαλείο του phaser, μέσω του οποίου χρησιμοποιήθηκαν οι βιβλιοθήκες και οι συναρτήσεις του και μέσω της γλώσσα προγραμματισμού javascpript, αναπτύχθηκε ο πηγαίος κώδικας του Super Mario.

## Διαδικασία Ανάπτυξης:

Αρχικά, δημιουργήθηκε η αναφορά, που ζητούσε το link του παιχνιδιού στην αναφορά. Πιάνοντας το δεύτερο παραδοτέο, χρειάστηκε να μελετηθεί ο δωσμένος πηγαίος κώδικας, έτσι ώστε να γίνουν σωστά όλες οι μετατροπές που ζητούνται. Έτσι, στη συνέχεια, χρησιμοποιώντας το πρόγραμμα Tiled, αλλά και την εικόνα super_mario_tiles, οπου διέθετε τα tiles για την πίστα δημιούργησα μία καινούργια. Στη συνέχεια, χρησιμοποιώντας το GIMP, άλλαξα την αμφίεση του Super Mario και των νομισμάτων. Τέλος, τροποποιώντας τον πηγαίο κώδικα, προσέθεσα τα score, bonus και ζωές. Έπειτα, για το τρίτο παραδοτεό, αλλάζοντας πάλι τον πηγαίο κώδικα, προσέθεσα καινούργιους εχθρούς, και έδωσα την δυνατότητα στον παίκτη να κάνει teleport σε συγκεκριμένο σημείο στη πίστα. Το menu, δημιουργήθηκε με το background χρώμα, δύο κουμπιά από τα οποία επιλέγει κανείς σε ποια πίστα θέλει να παίξει, αλλά και από κάποιους τίτλους. Το animation στο τέλος της πίστας δεν δημιουργήθηκε. Για το τέταρτο παραδοτεό, και πάλι αλλάχθηκε ο πηγαίος κώδικας, με τέτοιο τρόπο έτσι ώστε μόλις φτάνει το στόχο για της πρώτης πίστας, με το πάτημα του πλήκτρου enter να παιρνάει στη δεύτερη πίστα. Δίνονται και ενδεικτικά κομμάτια του κώδικα που μπήκανε για την εκπόρευση των παραδοτέων. Για το κομμάτι που ζητάει τα δύο συνεχόμενα επίπεδα, δημιουργήθηκαν τρείς καινουύργιες συναρτήσεις. Οι ```main()```, ```level1()``` και ```level2()```. Με την συνάρτηση ```main()``` ξεκινάει το παιχνίδι, όπου δίνει το menu του παιχνιδιού και να επιλέξει μεταξύ των δύο κουμπιών. Η πρώτη πίστα βρίσκεται στην συνάρτηση ```level1()``` και η δεύτερη στη συνάρτηση ```level2()``` . Μέσα στον κώδικα, όταν καλείται σε συγκεκριμένα σημεία η κάθε συνάρτηση φορτώνει και η συγκεκριμένη πίστα. Παρακάτω, στο τμήμα των ενδεικτικών οθόνων, παρατίθενται πληθώρα εικόνων, σχολιασμένοι κατάλληλα για να γίνει αντιληπτό, που έγιναν οι αλλαγές. 

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
```
function main() {
	game.stage.backgroundColor = '#5c94fc';		
	titleText = game.add.text (25, 29, 'Super Mario', {fontSize: '35px', fill: '#cc0000'});
	titleText.fontWeight = 'bold';		
	subtitle = game.add.text (1, 200, 'Score 14.000 Points or More and Press Enter to Proceed into Level 2.', {fontSize: '9px', fill: '#410574'});
	subtitle.fontWeight = 'bold';
	subtitle2 = game.add.text (70, 190, 'Press Space to Teleport.', {fontSize: '9px', fill: '#b83249'});
	subtitle2.fontWeight = 'bold';
	game.paused = true;
	reset();
}
```
```
if (this.spaceKey.isDown && !game.teleport) {
    player.body.position.x = 1632;
    player.body.position.y = 0;
    game.teleport = true;
}
```
## Ενδεικτικές Οθόνες:

###### Η πίστα 1 -level1()- Tiled:
![tm1](https://user-images.githubusercontent.com/22681573/35130701-f4b8a8a8-fcca-11e7-81b8-3561bcc5cbca.png)
###### Η πίστα 2 -level2()- Tiled:
![tm2](https://user-images.githubusercontent.com/22681573/35130791-590b3fdc-fccb-11e7-8cee-5c60e16aa910.png)
###### Στιγμιότυπα του παιχνιδιού:
![scrn2](https://user-images.githubusercontent.com/22681573/35130902-ee3aa96c-fccb-11e7-949d-dd7900951765.png)
![scrn1](https://user-images.githubusercontent.com/22681573/35130901-ee03c2d0-fccb-11e7-8f4b-a50d1bb15f92.png)
![scrn3](https://user-images.githubusercontent.com/22681573/35130903-ee687db0-fccb-11e7-9089-ae4ec92eb179.png)
![scrn4](https://user-images.githubusercontent.com/22681573/35130964-36bffa16-fccc-11e7-9bf5-a6bc92cb714c.png)
![scrn5](https://user-images.githubusercontent.com/22681573/35131166-2b95ce30-fccd-11e7-9661-8031b0d1f47e.png)

## Συμπεράσματα:

Συμπερασματικά, η εργασία για την δημιουργία ενός παιχνίδιου Super Mario, ήταν αρκετά ενδιαφέρουσα, καθώς μέσω αυτής θα κλιθείς να μάθεις τη γλώσσα προγραμματισμού javascript -σε αρχάριο βαθμό- αλλά και το εργαλείο του phaser. Έπειτα, μαθαίνεις πως να αναπτύσσεις ένα πρόγραμμα μέσα από το github, αλλά και ενσωματώνοντας το σε μία ιστοσελίδα μέσω της HTML. Επιπλέον, ένα ακόμα ενδιαφέρον κομμάτι της, ήταν η δημιουργία μίας ιστοσελίδας για την τελική αναφόρα μέσα από το git-hub. Τέλος, η εργασία αποτέλεσε έναν ωραίο τρόπο εκμάθησης όλων των παραπάνω αλλά και της δημιουργίας της ανάδρασης του χρήστη με το παιχνίδι μέσω των ήχων της εικόνας αλλά και του πληκτρολογίου με του οποίου ο χρήστης αλληλεπιδρά με το παιχνίδι.
