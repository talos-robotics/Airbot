<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en" lang="en"><head>





  
  <meta http-equiv="content-type" content="text/html;charset=utf-8" />

  
  <meta name="generator" content="Geany 1.32" /></head><body>
<div style="text-align: left; font-family: Courier New,Courier,monospace;"><br />
<div style="text-align: center;">&nbsp;<img style="width: 256px; height: 256px;" src="https://avatars0.githubusercontent.com/u/57757898?s=460&amp;v=4" alt="center" /> </div>
</div>

<pre style="font-family: Courier New,Courier,monospace;">	<h1 style="text-align: center;">Ανάλυση ατμοσφαιρικής ρύπανσης</h1><h1 style="text-align: center;">με δειγματοληπτικό έλεγχο</h1><h1 style="text-align: center;">(The Airbot project)</h1><h3><big>Σενάριο δραστηριότητας</big></h3>Αριθμός μαθητών: 9<br />Αριθμός Ομάδων: 3<br />Αριθμός ατόμων ανά ομάδα: 3<br />Είδος  δραστηριότητας: Ομαδοσυνεργατική<br />Ρόλοι: Δεν υπάρχουν διακριτοί ρόλοι στην ομάδα.<br />Ηλικιακή ομάδα: 12-15<br /><br /><h3><big>Φάση προετοιμασίας</big></h3>Οι μαθητές θα πρέπει να: <br />    • Διερευνήσουν στο διαδίκτυο και να ανακαλύψουν τους ρύπους της ατμόσφαιρας.<br />    • Συντάξουν ένα έντυπο όπου θα περιγράφουν τους σημαντικότερους ατμοσφαιρικούς ρύπους.<br />    • Να αναζητήσουν στο διαδίκτυο πληροφορίες για τους αισθητήρες που θα χρησιμοποιήσουμε.<br /><br /><h3><big>Φάση σχεδιασμού</big></h3>Οι μαθητές θα πρέπει να: <br />    • Να αναζητήσουν στο διαδίκτυο πληροφορίες για τη συνδεσμολογία των αισθητήρων με το Arduino.<br />    • Να αναζητήσουν στο διαδίκτυο πληροφορίες για τις προδιαγραφές των αισθητήρων.<br />    • Να δημιουργήσουν στο Fritzing τις παραπάνω συνδεσμολογίες.<br /><br /><br /><h3><big>Φάση υλοποίησης</big></h3>Οι μαθητές θα πρέπει να:<br />    • Δημιουργήσουν τις φυσικές συνδέσεις των υλικών τους με τους αισθητήρες.<br />    • Να προγραμματίσουν το Arduino χρησιμοποιώντας το περιβάλλον Mblock έτσι ώστε να παίρνουν τιμές από τους αισθητήρες.<br /><br /><h3><big>Φάση Δοκιμών</big></h3>Οι μαθητές θα πρέπει να:<br />    • Δοκιμάσουν τον εξοπλισμό τους και να επιβεβαιώσουν τη σωστή λειτουργία του.<br /><br /><br /><h3><big>Υλικά</big></h3><table style="width: 100%;" border="1">
  <tbody><tr>
    <th>ΠΟΣΟΤΗΤΑ</th>
    <th>ΕΙΔΟΣ</th>
    <th>ΚΟΣΤΟΣ</th>
    <th>Σχόλια</th>
  </tr>
  <tr align="center">
    <td>3</td>
    <td>ARDUINO UNO</td>
    <td>75</td>
    <td>Θα δημιουργηθούν 4 διαφορετικά υποσυστήματα</td>
  </tr>
  <tr align="center">
    <td>1</td>
    <td>Waveshare Environmental Sensor - BME280</td>
    <td>10</td>
    <th><br /></th>
  </tr>
  <tr align="center">
    <td>1</td>
    <td>CCS811 Air Quality Sensor Breakout - VOC &amp; eCO2</td>
    <td>25</td>
    <th><br /></th>
  </tr>
  <tr align="center">
    <td>1</td>
    <td>Waveshare Dust Sensor</td>
    <td>16</td>
    <th><br /></th>
  </tr>
  <tr align="center">
    <td>2</td>
    <td>Μετεωρολογικά μπαλόνια</td>
    <td>13</td>
    <th><br /></th>
  </tr>
  <tr align="center">
    <td>3</td>
    <td>Waveshare Micro SD Storage Board</td>
    <td>14,7</td>
    <th><br /></th>
  </tr>
  <tr align="center">
    <td><br /></td>
    <td>Σύνολο</td>
    <td>153,7</td>
    <th><br /></th>
  </tr>
</tbody></table> <br /><h3><big>Αναλυτική περιγραφή</big></h3>Οι μαθητές αφού ασχοληθούν με τους παράγοντες που δημιουργούν την ατμοσφαιρική ρύπανση,<br />θα δημιουργήσουν ένα σταθμό μέτρησης της ατμοσφαιρικής ρύπανσης.<br />Το σύστημα θα αποτελείτε από τρία επιμέρους υποσυστήματα, τα οποία θα έχουν κατανεμηθεί, 1 σε κάθε ομάδα, για υλοποίηση. <br />Τα συστήματα αυτά θα τοποθετηθούν σε μετεωρολογικά μπαλόνια, όπου θα είναι δεμένα με σπάγκο<br />και θα ανέβουν σε περίπου 100 – 200 μέτρα έτσι ώστε να αρχίσουν να παίρνουν μετρήσεις.<br /><br />Αυτή η διαδικασία θα γίνει σε 3 διαφορετικές περιοχές. <br />    1. Περιοχή με καμένα δέντρα<br />    2. Στο κέντρο της πόλης<br />    3. Περιοχή κατάμεστη από πράσινο σε μεγάλο ύψος<br />Οι μετρήσεις θα μελετηθούν από τους μαθητές και θα βγουν τα αντίστοιχα συμπεράσματα.<br /><br /></pre>

<div style="text-align: center; font-family: Courier New,Courier,monospace;">
<h4><big><big><big><span style="font-weight: bold; text-decoration: underline;">Πλατφόρμες που
χρησιμοποιήθηκαν </span></big></big></big></h4>
<div style="text-align: left;"><br />
Όλα τα διαδυκτιακά εργαλεία που χρησιμοποιήσαμε ανοίκουν στο Πανελληνιο
σχολικό δίκτυο.<br />
Δημιουργήθηκαν λογαριασμοί μαθητών για να μπορέσουν να συνδέονται στο
Πανελληνιο σχολικό δίκτυο.<br />
<br />
<p style="margin-bottom: 0cm; line-height: 100%; text-align: left;"><small><small>
<font style="font-size: 24pt;" size="6"><small><small><b>Πλατφόρμες
εργασίας</b></small></small></font></small></small></p>
<dl>
  <dt><small><small><font style="font-size: 18pt;" size="5"><small><small><b>Ηλεκτρονική
τάξη:</b> https://eclass.sch.gr</small></small></font></small></small></dt>
  <dt><small><small><font style="font-size: 18pt;" size="5"><small><small><b>Πλατφόρμα
τηλεδιασκέψεων:</b> https://meeting.sch.gr</small></small></font></small></small></dt>
  <dt><small><small><font style="font-size: 18pt;" size="5"><small><small><b>Ομαδοσυνεργατικά
έγγραφα:</b> https://grafis.sch.gr</small></small></font></small></small></dt>
  <dt><small><small><font style="font-size: 18pt;" size="5"><small><small><b>Ηλεκτρονικό
ταχυδρομείο:</b> https://webmail.sch.gr</small></small></font></small></small></dt>
  <dt><small><small><font style="font-size: 18pt;" size="5"><small><small><b>Υπηρεσία
Επικοινωνίας:</b></small></small></font><font style="font-size: 18pt;" size="5"><small><small> </small></small></font><font style="font-size: 18pt;" size="5"><small><small>https://www.uc.sch.gr</small></small></font></small></small></dt>
</dl>
<br />
<div style="text-align: center; text-decoration: underline;">
<h4><big style="font-weight: bold;"><big><big>Εργαλεία ΕΛΛΑΚ που
χρησιμοποιήθηκαν</big></big></big></h4>
<div style="text-align: left;">
<ul>
  <li>Libreoffice</li>
  <li>Mblock</li>
  <li>Arduino IDE</li>
  <li>Fritzing</li>
</ul>

</div>
</div>
</div>
</div>

<div style="text-align: center; font-family: Courier New,Courier,monospace;">
<h3><big style="font-family: Times New Roman,Times,serif;"><big>Θα χρειαστεί να μεταφορτώσετε</big></big><br />
</h3>
<h3 style="text-align: left; font-family: Times New Roman,Times,serif;"><span style="font-weight: normal;">1) <a href="/libs-extensions/The%20airbot%20extension%20mblock%20Ver%201.mext">Τα blocks που δημιούργησε ο εκπαιδευτικός πληροφορικής για τον ευκολότερο προγραμματισμό σε mblock.</a></span><br />
</h3>
<h3 style="text-align: left;"><span style="font-weight: normal; font-family: Times New Roman,Times,serif;">2) <a href="/libs-extensions/arduino%20ide%20libraries.zip">Τις βιβλιοθήκες που θα χρησιμοποιήσουμε στο Arduino IDE.</a></span><br />
</h3>
<h3><big style="font-weight: bold;"><big><big>Θεωρητικό μέρος</big></big></big></h3>

<div style="text-align: left;">

<h3 style="text-decoration: underline;"><font color="#000000"><font style="font-size: 12pt;" size="3">Τι
είναι η ατμοσφαιρική ρύπανση</font></font></h3>
Ατμοσφαιρική ρύπανση είναι η ρύπανση της ατμόσφαιρας , δηλαδή η
προσθήκη ουσιών ( ρυπών ) στην ατμόσφαιρα που υπό φυσιολογικές συνθήκες
δεν θα υπήρχαν . Στη σύγχρονη εποχή ,συχνά η ρύπανση είναι αποτέλεσμα
της ανθρώπινης δραστηριότητας .
<h4 style="text-decoration: underline;"><font color="#000000"><font style="font-size: 12pt;" size="3">Κύριες
πηγές εκπομπής ατμοσφαιρικών ρύπων</font></font></h4>
<ul>
  <li>Η ατμοσφαιρική ρύπανση
δημιουργείται από </li>
  <li>Τα μεταφορικά μέσα (αυτοκίνητα, λεωφορία, αεροπλάνα,
μηχανάκια, φορτηγά)</li>
  <li>Τα νοικοκυριά</li>
  <li>Το ηλεκτρικό ρεύμα</li>
  <li>Την βιομηχανία </li>
  <li>Απορρυπαντικά, σπρέι</li>
  <li>Εργοστάσια καίγοντας
λιγνίτη και ορυκτά παράγουν καυσαέρια ρυπαίνοντας έτσι την ατμόσφαιρα.</li>
  <li>κ.ά.</li>
</ul>
<span style="font-size: 12pt; color: rgb(0, 0, 0);">
<h1 style="text-decoration: underline;"><font color="#000000"><font style="font-size: 12pt;" size="3">Βασικοί
ατμοσφαιρικοί ρύποι</font></font></h1>
Υπάρχουν 6 κύριοι ατμοσφαιρικοί ρύποι:<br />
<br />
<ul>
  <li><span style="font-weight: bold;">Οξείδια του αζώτου:</span>με τον
όρο οξείδια του αζώτου ορίζονται οι ενώσεις του αζώτου με το οξυγόνο σε
διάφορες αναλογίες </li>
  <li><span style="font-weight: bold;">Μονοξείδιο του άνθρακα:</span>το
μονοξείδιο του άνθρακα είναι ένα από τα
οξείδια του άνθρακα και παράγεται από την μερική καύση του άνθρακα.</li>
  <li><span style="font-weight: bold;">Διοξείδιο του θείου:</span>το
διοξείδιο του θείου ανήκει στην οικογένεια των
σουλφιδίων , αέρια των οποίο κύριο χαρακτηριστικό είναι ότι είναι
διαλυτά στο νερό</li>
  <li><span style="font-weight: bold;">Όζον:</span>με τον όρο όζον
ορίζουμε το τριατομικό οξυγόνο , αέριο που κατά
κύριο λόγο εκλύεται στην ατμόσφαιρα&nbsp; ως παράγωγο χημικών
αντιδράσεων
μέσα στην ίδια την ατμόσφαιρα&nbsp; </li>
  <li><span style="font-weight: bold;">Μόλυβδος:</span>ο μόλυβδος είναι
μέταλλο που συναντάται τόσο στο φυσικό
περιβάλλον όσο και στα προιόντα ή τα κατάλοιπα της βιομηχανικής
παραγωγής&nbsp; </li>
  <li><span style="font-weight: bold;">Αιωρούμενα σωματίδια:</span> ο
όρος σωματίδιο περιγράφει τα διάφορα σωματίδια που βρίσκονται στην
ατμόσφαιρα</li>
  <li><span style="font-weight: bold;">Το όζον (χημικός τύπος: Ο3:</span>
είναι ένα ανοιχτό μπλε αέριο με χαρακτηριστική πικάντικη οσμή. Είναι
ένα αλλοτρόπιο οξυγόνο που είναι πολύ λιγότερο σταθερό από το διατομικό
αλλοτρόπιο Ο2, διασπώντας στην χαμηλότερη ατμόσφαιρα σε 02 ή διοξείδιο.
Το όζον σχηματίζεται από διοξείδιο με τη δράση υπεριώδους φωτός (UV)
και ηλεκτρικών εκκενώσεων εντός της ατμόσφαιρας της Γης. Παρουσιάζεται
σε πολύ χαμηλές συγκεντρώσεις καθ 'όλη τη διάρκεια της τελευταίας, με
την υψηλότερη συγκέντρωση να είναι υψηλή στο στρώμα όζοντος της
στρατόσφαιρας, η οποία απορροφά το μεγαλύτερο μέρος της υπεριώδους (UV)
ακτινοβολίας του Ήλιου.<br />
    <br />
Η οσμή του όζοντος θυμίζει χλώριο και είναι ανιχνεύσιμη από πολλούς
ανθρώπους σε συγκεντρώσεις μόλις 0,1 ppm στον αέρα. Η δομή του Ο3 του
όζοντος προσδιορίστηκε το 1865. Το μόριο αργότερα αποδείχθηκε ότι έχει
μια κυρτή δομή και είναι διαμαγνητική. Σε κανονικές συνθήκες, το όζον
είναι ένα ανοιχτό μπλε αέριο που συμπυκνώνεται σε προοδευτικά
κρυογονικές θερμοκρασίες σε ένα σκούρο μπλε υγρό και τελικά ένα
ιώδες-μαύρο στερεό. Η αστάθεια του όζοντος σε σχέση με το πιο κοινό
διοξυγόνο είναι τέτοια που το συμπυκνωμένο αέριο και το υγρό όζον
μπορούν να αποσυντεθούν εκρηκτικά σε υψηλές θερμοκρασίες ή με γρήγορη
θέρμανση στο σημείο βρασμού. Συνεπώς χρησιμοποιείται εμπορικά μόνο σε
χαμηλές συγκεντρώσεις.<br />
    <br />
Το όζον είναι ένα ισχυρό οξειδωτικό (πολύ περισσότερο από το διοξείδιο)
και έχει πολλές βιομηχανικές και καταναλωτικές εφαρμογές που
σχετίζονται με την οξείδωση. Ωστόσο, το ίδιο υψηλό οξειδωτικό δυναμικό
προκαλεί τη βλάβη του όζοντος στους βλεννογόνους και αναπνευστικούς
ιστούς στα ζώα και επίσης στους ιστούς σε φυτά, πάνω από τις
συγκεντρώσεις περίπου 100 ppb. Ενώ αυτό κάνει το όζον έναν ισχυρό
αναπνευστικό κίνδυνο και ρύπο κοντά στο έδαφος, μια υψηλότερη
συγκέντρωση στη στιβάδα του όζοντος (από δύο έως οκτώ ppm) είναι
ευεργετική, εμποδίζοντας το φθορό UV φως να φθάσει στην επιφάνεια της
Γης.<br />
  </li>

</ul>
<br />
<h1 style="text-decoration: underline;"><font color="#000000"><font style="font-size: 12pt;" size="3">Κύριες
επιπτώσεις των βασικών ατμοσφαιρικών
ρύπων</font></font></h1>
<span style="font-weight: bold; font-style: italic;">Επιπτώσεις στην
υγεία</span><br />
<br />
Οι ατμοσφαιρικοί ρύποι προκαλούν πρόωρους θανάτους, λόγω λοιμώξεων του
αναπνευστικού, ιδιαίτερα σε παιδιά.<br />
<br />
<ul>
  <li>Τα οξείδια του αζώτου που μπορεί να προκαλέσουν καρκινογένεση
μέσω των ελευθέρων ριζών, της δημιουργίας φλεγμονών και των βιολογικών
μεταλλάξεων.</li>
  <li>Το διοξείδιο του θείου που μπορεί να προκαλέσει προβλήματα στην
καρδιά και στους πνεύμονες.</li>
  <li>Το μονοξείδιο του άνθρακα που μπορεί να έχει επιπτώσεις στο αίμα,
στον εγκέφαλο και στην καρδιά.<br />
Επιπλέον, το πολύ μονοξείδιο του άνθρακα ζαλίζει, προκαλεί πονοκέφαλο
και κούραση.</li>
  <li>Το όζον παρόλο που όταν δεν βρίσκεται στην τροπόσφαιρα (το στρώμα
της ατμόσφαιρας στο οποίο ζούμε) μας προστατεύει, όταν βρίσκεται στην
τροπόσφαιρα, μπορεί να προκαλέσει ερεθισμούς στο αναπνευστικό σύστημα,
στα μάτια, στη μύτη, στον λαιμό και δυσλειτουργία στους πνεύμονες .</li>
  <li>Το βενζόλιο προκαλεί καρκίνο και βλάβες στο νευρικό σύστημα.</li>
</ul>
&nbsp;&nbsp;<br />
<span style="font-weight: bold; font-style: italic;">Επιπτώσεις στο
περιβάλλον</span><br />
<br />
<ul>
  <li>Το διοξείδιο του θείου προκαλεί μετά από μακροχρόνια έκθεση όξινη
απόθεση, που είναι επικίνδυνο για οικοσυστήματα.</li>
  <li>Από ατμοσφαιρικούς ρύπους που εκλύονται από την ατελή καύση,
προκαλείται το φαινόμενο του Θερμοκηπίου δηλαδή υπερθέρμανση της γης
που έχει ως αποτέλεσμα να λιώνουν οι πάγοι και να κινδυνεύουν πολλά ζώα.</li>
  <li>Προκαλείται όξινη βροχή που προσβάλλει τα δάση και
&nbsp;μετατρέπει &nbsp;το μάρμαρο σε &nbsp;γύψο.</li>
  <li>Η τρύπα του όζοντος προκαλείται από τη χρήση χλωροφθορανθράκων
που υπάρχουν στα ψυκτικά και στα σπρέι.</li>
  <li>Τα οξείδια του αζώτου, προκαλούν το φωτοχημικό νέφος στις
μεγαλουπολεις</li>
</ul>

</span>
<h1><span style="font-size: 12pt; color: rgb(0, 0, 0);">
</span></h1><h1 style="text-decoration: underline;"><big><big><font color="#000000"><font style="font-size: 12pt;" size="3"><big><big>Ποιοί
αισθητήρες θα χρησιμοποιηθούν;</big></big></font></font></big></big></h1>

<span style="font-size: 12pt; color: rgb(0, 0, 0);">
<h2><small><small><span style="font-size: 12pt; color: rgb(0, 0, 0);"><big><big><big><span style="font-weight: bold; text-decoration: underline;">BME 280</span></big></big></big></span></small></small></h2>
<h2><span style="font-size: 12pt; color: rgb(0, 0, 0);">
</span></h2>
<span style="font-size: 12pt; color: rgb(0, 0, 0);">
<p style="border: medium none ; line-height: 11.75pt; margin-top: 0pt; margin-bottom: 7.99999pt; font-weight: bold;" class=""><span style="font-weight: normal;">
</span></p>
<p style="border: medium none ; line-height: 11.75pt; margin-top: 0pt; margin-bottom: 7.99999pt; font-weight: bold;" class=""><span style="font-weight: normal;">Γενικές πληροφορίες<br />
Σύνδεση με το Arduino
</span></p>
<p style="border: medium none ; line-height: 11.75pt; margin-top: 0pt; margin-bottom: 7.99999pt;" class=""><span style="font-size: 12pt; color: rgb(0, 0, 0);">Ο
αισθητήρας BME280 και κατασκευάζεται από τη BOSCH. Χρησιμοποιείται
εύκολα διότι δεν χρειάζεται επιπλέον εξαρτήματα για να λειτουργήσει.
Μπορεί να μετρήσει με ακρίβεια 
</span></p>
<ul>
  <li><span style="font-size: 12pt; color: rgb(0, 0, 0);">υψόμετρο</span></li>
  <li><span style="font-size: 12pt; color: rgb(0, 0, 0);">βαρομετρική
πίεση ( πίεση της ατμόσφαιρας στη γη)</span></li>
  <li><span style="font-size: 12pt; color: rgb(0, 0, 0);">υγρασία
(0% εώς 100</span><span style="font-size: 12pt; color: rgb(0, 0, 0);">%)
    
    </span></li>
  <li><span style="font-size: 12pt; color: rgb(0, 0, 0);">θερμοκρασία
(από -40</span><span style="font-size: 12pt; color: rgb(0, 0, 0); vertical-align: super;">0</span><span style="font-size: 12pt; color: rgb(0, 0, 0);">C
εώς 85</span><span style="font-size: 12pt; color: rgb(0, 0, 0); vertical-align: super;">ο</span><span style="font-size: 12pt; color: rgb(0, 0, 0);">C)
.</span></li>
</ul>
</span></span><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);" /></span></span>
<h1 style="text-decoration: underline;"><font><font><font><font><font><font><font color="#000000"><font style="font-size: 12pt;" size="3">Τρόπος
σύνδεσης με το Arduino (εικόνα απο το
Fritzing)</font></font></font></font></font></font></font></font></h1>
<img style="width: 1000px; height: 562px;" alt="bme280" src="images/bme280_bb.png" /><br />
<br />
<h1 style="text-decoration: underline;"><font><font><font><font><font><font><font><font><font><font><font><font><font><font><font color="#000000"><font style="font-size: 12pt;" size="3">Το πρόγραμμα στο mblock</font></font></font></font></font></font></font></font></font></font></font></font></font></font></font></font></h1>

<img style="width: 714px; height: 441px;" alt="bme" src="images/bme280.png" /><br />
<span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);">

</span>
<h2><span style="font-size: 12pt; color: rgb(0, 0, 0);">
<p><big><big><span dir="auto"><span style="font-weight: bold; text-decoration: underline;">Dust Sensor
(GP2Y1010AU0F | GP2Y1014AU0F )</span></span></big></big></p>
<p><br />
<big><big><span dir="auto"><span style="font-weight: bold; text-decoration: underline;" /></span></big></big></p>
</span></h2>
<span style="font-size: 12pt; color: rgb(0, 0, 0);">
</span>
<p><big>Το GP2Y1010AU0F
της Sharp είναι ένας αισθητήρας οπτικής ποιότητας της ατμόσφαιρας,
σχεδιασμένος να ανιχνεύει σωματίδια σκόνης. Μια δίοδος εκπομπής
υπέρυθρης ακτινοβολίας και φωτοτρανζίστορ τοποθετούνται διαγώνια σε
αυτήν τη συσκευή, ώστε να επιτρέπει την ανίχνευση του ανακλώμενου φωτός
της σκόνης στον αέρα. Είναι ιδιαίτερα αποτελεσματικό στην ανίχνευση
πολύ λεπτών σωματιδίων όπως ο καπνός τσιγάρων και χρησιμοποιείται
συνήθως στα συστήματα καθαρισμού του αέρα.</big></p>

<span style="font-size: 12pt; color: rgb(0, 0, 0);">
</span><span style="font-size: 12pt; color: rgb(0, 0, 0);"><p>Ο αισθητήρας έχει
πολύ χαμηλή κατανάλωση ρεύματος (μέγιστο 20mA, τυπικό 11mA) και μπορεί
να τροφοδοτηθεί με έως 7VDC. Η έξοδος του αισθητήρα είναι μια αναλογική
τάση ανάλογη προς τη μετρούμενη πυκνότητα σκόνης, με ευαισθησία 0.5V /
0.1mg / m3.<big><big><span dir="auto"><small><small><span style="text-decoration: underline; font-weight: normal;" /></small></small><span style="font-weight: bold; text-decoration: underline;" /></span></big></big></p></span><span style="font-size: 12pt; color: rgb(0, 0, 0);">
</span><big><big><span style="font-weight: bold; font-style: italic;">ΧΑΡΑΚΤΗΡΙΣΤΙΚΑ</span></big></big><br />
<big>Τύπος Αισθητήρα: Σκόνης<br />
Τυπική Τάση Εισόδου: 7VDC<br />
Ρεύμα Λειτουργίας: 20mA<br />
Διασύνδεση: Αναλογική<br />
Πρωτόκολλο Eπικοινωνίας: Χωρίς</big><br />
<span style="font-size: 12pt; color: rgb(0, 0, 0);">
<p><big><big><span dir="auto"><span style="font-weight: bold; text-decoration: underline;" /></span></big></big></p>
</span><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);">
<h1 style="text-decoration: underline;"><font><font><font color="#000000"><font style="font-size: 12pt;" size="3">Τρόπος
σύνδεσης με το Arduino (εικόνα απο το
Fritzing)</font></font></font></font></h1>

<span style="font-size: 12pt; color: rgb(0, 0, 0);">
<p><span dir="auto" /></p>
<img style="width: 500px; height: 367px;" alt="dust sensor" src="images/dust.jpg" /><br />

</span>
<h2><span style="font-size: 12pt; color: rgb(0, 0, 0);">
</span></h2></span></span></span></span>
<h1 style="text-decoration: underline;"><font><font><font><font><font><font><font><font><font><font><font><font><font><font><font color="#000000"><font style="font-size: 12pt;" size="3">Το πρόγραμμα στο mblock</font></font></font></font></font></font></font></font></font></font></font></font></font></font></font></font></h1>

<span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);">
<h1 style="text-decoration: underline;"><img style="width: 422px; height: 496px;" alt="dustsensor" src="images/dust%20final.png" /><br />
</h1>
<h1 style="text-decoration: underline;"><small><small>Adafruit CCS811
Air Quality Sensor</small></small></h1>


</span></span><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><big><span style="font-weight: normal;">Αυτός ο
αισθητήρας είναι ένας αισθητήρας αερίων που μπορεί να
ανιχνεύσει ένα ευρύ φάσμα πτητικών οργανικών ενώσεων (VOCs) και
προορίζεται για την παρακολούθηση της ποιότητας του αέρα. Υπάρχει
επίσης ένα θερμίστορ που μπορεί να χρησιμοποιηθεί για τον υπολογισμό
της τοπικής
θερμοκρασίας περιβάλλοντος.<br />
Το CCS811
διαθέτει έναν «τυπικό» αισθητήρα MOX θερμής πλάκας, καθώς και έναν
μικρό μικροελεγκτή που ελέγχει την ισχύ στην πλάκα, διαβάζει την
αναλογική τάση και παρέχει μια διασύνδεση I2C από την οποία διαβάζεται.Το μέρος
αυτό θα μετρήσει τη συγκέντρωση CO2) σε μια περιοχή από 400 έως
8192 μέρη ανά εκατομμύριο (ppm) και η συγκέντρωση TVOC (Total Volatile
Organic Compound) εντός εύρους από 0 έως 1187 μέρη ανά δισεκατομμύριο
(ppb). Επίσης, η AMS συνιστά να τρέχετε αυτόν τον αισθητήρα για 48
ώρες, όταν τον παραλάβετε για να το "στρώσετε", και στη συνέχεια 20 λεπτά
επιθυμητή λειτουργία κάθε φορά που χρησιμοποιείται ο αισθητήρας. Αυτό
συμβαίνει επειδή τα επίπεδα ευαισθησίας του αισθητήρα θα αλλάξουν κατά
την πρώιμη χρήση. <br />
</span></big></span><span style="font-size: 12pt; color: rgb(0, 0, 0);"><big><span style="font-weight: normal;" /></big></span></span><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><big><span style="font-weight: normal;"><br />
</span></big></span></span><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><big><span style="font-weight: normal;"><big><span style="font-weight: bold; font-style: italic;">ΧΑΡΑΚΤΗΡΙΣΤΙΚΑ</span></big><br /><small>
Τύπος Αισθητήρα: Αερίων<br />

Τυπική Τάση Εισόδου:3.3VDC - 5VDC<br />

Ρεύμα Λειτουργίας: 30mA<br />

Διασύνδεση:Ψηφιακή<br />

Πρωτόκολλο Eπικοινωνίας: I2C</small></span></big></span></span><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><big><span style="font-weight: normal;"><br />
</span><span style="font-weight: normal;" /></big><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);">
<h1 style="text-decoration: underline;"><font><font><font color="#000000"><font style="font-size: 12pt;" size="3">Τρόπος
σύνδεσης με το Arduino<br />
</font></font></font></font></h1>
<br />
<span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);">
</span><br />
<span style="font-size: 12pt; color: rgb(0, 0, 0);"><img style="width: 300px; height: 473px;" alt="ccs811" src="images/ccs811.jpg" /><br />
<br />
</span></span></span></span></span></span></span></span></span></span></span></span></span>
<h1 style="text-decoration: underline;"><font><font><font><font><font><font><font><font><font><font><font><font><font><font><font color="#000000"><font style="font-size: 12pt;" size="3">Το πρόγραμμα στο mblock</font></font></font></font></font></font></font></font></font></font></font></font></font></font></font></font></h1>

<img style="width: 413px; height: 451px;" alt="ccs811" src="images/ccs811.png" /><br />
<span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);">
</span></span></span><br />
<h1 style="text-decoration: underline;"><big>MQ 131</big></h1>
<h1><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);" /></span></span></h1>
<span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><br />
Συμπαγής πλακέτα με βάση τον αισθητήρα MQ-131. Εξοπλισμένο με υψηλή
ευαισθησία και πολύ γρήγορο χρόνο απόκρισης, αυτός ο αισθητήρας είναι
σε θέση να ανιχνεύσει τη συγκέντρωση του όζοντος (10 ~ 1000ppb) στον
αέρα του περιβάλλοντος. Το ευαίσθητο υλικό του αισθητήρα είναι το
διοξείδιο του κασσίτερου (SnO2), το οποίο έχει χαμηλή αγωγιμότητα, όταν
ο αέρας είναι καθαρός στο περιβάλλον, ενώ είναι υψηλότερος παρουσία
όζοντος.<br />
<br />
Η πλακέτα έχει ένα trimmer για να ρυθμίσετε την τιμή κατωφλίου, την
αναλογική έξοδο και την ψηφιακή έξοδο (TTL), την κατάσταση LED για την
παροχή ρεύματος και το σήμα εξόδου.<br />
<br />
Η ψηφιακή έξοδος μπορεί να συνδεθεί απευθείας με μικροελεγκτή. Η
αναλογική έξοδος παρέχει τάση (0-5 VDC) που αυξάνεται με την αύξηση της
συγκέντρωσης του όζοντος στον αέρα.<br />
<br />
Τροφοδοσία: 5 VDC, διαστάσεις (mm): 31,85x19,65x33. Μπορεί να χρησιμοποιηθεί με Arduino ή άλλο μικροελεγκτή.<br />
<br />
<br />
</span></span></span></span></span></span></span><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><big><span style="font-weight: normal;"><big><span style="font-weight: bold; font-style: italic;">ΧΑΡΑΚΤΗΡΙΣΤΙΚΑ</span></big></span></big></span></span><br />
<span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);">
<br />
<br />
</span></span></span></span></span></span></span>
<table style="border-collapse: collapse; border-spacing: 2px; max-width: 100%; background-color: transparent; width: 815px; margin-bottom: 16px; color: rgb(51, 51, 51); font-size: 13px; font-style: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px;">
<tbody style=""><tr style=""><td class="span-7 col-md-4 last" style="padding: 7px; position: static; min-height: 1px; float: none; width: 262px; display: table-cell; line-height: 17px;"><label id="param_2193" style="margin: 0px 0px 0px 5px; font-weight: 400;">Τύπος αισθητήρα</label></td><td class="span-10 col-md-8 last" style="padding: 7px; position: static; min-height: 1px; float: none; width: 521px; display: table-cell; line-height: 17px;">αερίου</td></tr><tr class="odd" style="background: rgb(247, 248, 249) none repeat scroll 0% 50% ! important; -moz-background-clip: -moz-initial ! important; -moz-background-origin: -moz-initial ! important; -moz-background-inline-policy: -moz-initial ! important;"><td class="span-7 col-md-4 last" style="padding: 7px; position: static; min-height: 1px; float: none; width: 262px; display: table-cell; line-height: 17px;"><label id="param_1404" style="margin: 0px 0px 0px 5px; font-weight: 400;">Ανιχνευμένο αέριο</label></td><td class="span-10 col-md-8 last" style="padding: 7px; position: static; min-height: 1px; float: none; width: 521px; display: table-cell; line-height: 17px;">O3</td></tr><tr style=""><td class="span-7 col-md-4 last" style="padding: 7px; position: static; min-height: 1px; float: none; width: 262px; display: table-cell; line-height: 17px;"><label id="param_1397" style="margin: 0px 0px 0px 5px; font-weight: 400;">Εύρος μετρήσεων</label></td><td class="span-10 col-md-8 last" style="padding: 7px; position: static; min-height: 1px; float: none; width: 521px; display: table-cell; line-height: 17px;">10...1000ppm</td></tr><tr class="odd" style="background: rgb(247, 248, 249) none repeat scroll 0% 50% ! important; -moz-background-clip: -moz-initial ! important; -moz-background-origin: -moz-initial ! important; -moz-background-inline-policy: -moz-initial ! important;"><td class="span-7 col-md-4 last" style="padding: 7px; position: static; min-height: 1px; float: none; width: 262px; display: table-cell; line-height: 17px;"><label id="param_2390" style="margin: 0px 0px 0px 5px; font-weight: 400;">Σειρά</label></td><td class="span-10 col-md-8 last" style="padding: 7px; position: static; min-height: 1px; float: none; width: 521px; display: table-cell; line-height: 17px;">MQ-131</td></tr></tbody>
</table>
<br />
<span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);">
</span></span></span><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);">
<h1 style="text-decoration: underline;"><font><font><font color="#000000"><font style="font-size: 12pt;" size="3">Τρόπος
σύνδεσης με το Arduino </font></font></font></font></h1>
<img style="width: 1043px; height: 654px;" alt="mq131" src="/images/mq131.jpg" /><br />
<span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);">
<br />
<br />
</span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);" /></span></span></span></span></span></span></span></span></span></span></span>
<h1 style="text-decoration: underline;"><font><font><font><font><font><font><font color="#000000"><font style="font-size: 12pt;" size="3">Το πρόγραμμα στο mblock<br />
</font></font></font></font></font></font></font></font></h1>
<img style="width: 712px; height: 505px;" alt="mq131" src="/images/mq131%20final%20working.png" /><br />
<span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><br />
<h1 style="text-decoration: underline;"><font color="#000000"><font style="font-size: 12pt;" size="3">Πώς
θα αποθηκεύσουμε τα δεδομένα;</font></font></h1>Τα
δεδομένα θα τα αποθηκεύσουμε χρησιμοποιόντας ένα sd module σε κάθε
arduino.Ο τρόπος σύνδεσης με το arduino παρουσιάζεται παρακάτω. Αφού συγκεντρώσουμε τα στοιχεία απο όλες τις κάρτες
sd θα τα επεξεργαστούμε συγκεντρωτικά.<br />
<br />

<h1 style="text-decoration: underline;"><font color="#000000"><font style="font-size: 12pt;" size="3">Τρόπος
σύνδεσης με το Arduino (εικόνα απο το
Fritzing)</font></font></h1><img style="width: 1000px; height: 701px;" alt="sd" src="images/sd_bb.png" /><br />
<br />
</span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span><span style="font-size: 12pt; color: rgb(0, 0, 0);">
<h2><small><small><big><big><big><small><small><span style="font-size: 12pt; color: rgb(0, 0, 0);"><big><big><big><span style="font-weight: bold; text-decoration: underline;">Φωτογραφίες<br />
</span></big></big></big></span></small></small></big></big></big></small></small></h2>
<span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);" /></span></span></span></span></span></span></span></span></span></span></span></span></span>
<h1 style="text-decoration: underline;"><font><font><font color="#000000"><font style="font-size: 12pt;" size="3">Η διαδικασία κατασκευής και προγραμματισμού<br />
</font></font></font></font></h1>
<br />
<br />
<table style="text-align: left; width: 100%;" border="1" cellpadding="2" cellspacing="2">
  <tbody>
    <tr>
      <td style="vertical-align: top;"><img style="width: 400px; height: 300px;" alt="im1" src="photos/IMG_20200228_145803.jpg" /></td>
      <td style="vertical-align: top;"><img style="width: 400px; height: 300px;" alt="im2" src="photos/IMG_20200228_145821.jpg" /></td>
      <td style="vertical-align: top;"><img style="width: 400px; height: 300px;" alt="im3" src="photos/IMG_20200228_145827.jpg" /></td>
    </tr>
    <tr>
      <td style="vertical-align: top;"><img style="width: 400px; height: 300px;" alt="im4" src="photos/IMG_20200228_145841.jpg" /></td>
      <td style="vertical-align: top;"><img style="width: 400px; height: 300px;" alt="im5" src="photos/IMG_20200228_145852.jpg" /></td>
      <td style="vertical-align: top;"><img style="width: 400px; height: 300px;" alt="im6" src="photos/IMG_20200228_145919.jpg" /></td>
    </tr>
    <tr>
      <td style="vertical-align: top;"><img style="width: 400px; height: 300px;" alt="im7" src="photos/IMG_20200228_145924.jpg" /></td>
      <td style="vertical-align: top;"><img style="width: 400px; height: 300px;" alt="im8" src="photos/IMG_20200306_143752.jpg" /></td>
      <td style="vertical-align: top;"><img style="width: 400px; height: 300px;" alt="im9" src="photos/IMG_20200306_143803.jpg" /></td>
    </tr>
    <tr>
      <td style="vertical-align: top;"><img style="width: 400px; height: 300px;" alt="im10" src="photos/IMG_20200306_143809.jpg" /></td>
      <td style="vertical-align: top;"><img style="width: 400px; height: 300px;" alt="im11" src="photos/IMG_20200306_143829.jpg" /></td>
      <td style="vertical-align: top;"><img style="width: 400px; height: 300px;" alt="im13" src="photos/IMG_20200306_143839.jpg" /></td>
    </tr>
    <tr>
      <td style="vertical-align: top;"><img style="width: 400px; height: 300px;" alt="im14" src="photos/IMG_20200306_143842.jpg" /></td>
      <td style="vertical-align: top;"><img style="width: 250px; height: 333px;" alt="im15" src="photos/IMG_20200306_143848.jpg" /></td>
      <td style="vertical-align: top;"><img style="width: 250px; height: 333px;" alt="im16" src="photos/IMG_20200306_143930.jpg" /></td>
    </tr>
    <tr>
      <td style="vertical-align: top;"><img style="width: 400px; height: 300px;" alt="im17" src="photos/IMG_20200306_143940.jpg" /></td>
      <td style="vertical-align: top;"><img style="width: 400px; height: 300px;" alt="im18" src="photos/IMG_20200306_143948.jpg" /></td>
      <td style="vertical-align: top;"><img style="width: 400px; height: 300px;" alt="im19" src="photos/IMG_20200306_144011.jpg" /></td>
    </tr>
    <tr>
      <td style="vertical-align: top;"><img style="width: 400px; height: 300px;" alt="im20" src="photos/IMG_20200306_144334.jpg" /></td>
      <td style="vertical-align: top;"><img src="photos/IMG_20200306_144736.jpg" alt="im22" style="width: 250px; height: 333px;" /></td>
      <td style="vertical-align: top;"><img style="width: 250px; height: 333px;" alt="im23" src="photos/IMG_20200306_144759.jpg" /></td>
    </tr>
    <tr>
      <td style="vertical-align: top;"><img src="photos/IMG_20200306_145453.jpg" alt="im24" style="width: 200px; height: 356px;" /></td>
      <td style="vertical-align: top;"><img style="width: 250px; height: 333px;" alt="im25" src="photos/IMG_20200306_145520.jpg" /></td>
      <td style="vertical-align: top;"><img style="width: 250px; height: 333px;" alt="im26" src="photos/IMG_20200306_150749.jpg" /></td>
    </tr>
    <tr>
      <td style="vertical-align: top;"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><img style="width: 400px; height: 300px;" alt="im27" src="photos/IMG_20200221_145031.jpg" /></span></span>
      </td>
      <td style="vertical-align: top;"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><img style="width: 400px; height: 300px;" alt="im28" src="photos/IMG_20200221_145041.jpg" /></span></span>
      </td>
      <td style="vertical-align: top;"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><img style="width: 400px; height: 300px;" alt="im29" src="photos/IMG_20200221_145049.jpg" /></span></span>
      </td>
    </tr>
    <tr>
      <td style="vertical-align: top;"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><img style="width: 400px; height: 300px;" alt="im30" src="photos/IMG_20200221_145057.jpg" /></span></span>
      </td>
      <td style="vertical-align: top;"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><img style="width: 400px; height: 300px;" alt="im31" src="photos/IMG_20200221_145103.jpg" /></span></span>
      </td>
      <td style="vertical-align: top;"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><img style="width: 250px; height: 333px;" alt="im32" src="photos/IMG_20200221_145150.jpg" /></span></span>
      </td>
    </tr>
  </tbody>
</table>
<span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><br />
</span></span></span></span></span></span></span></span></span></span></span></span></span></span></span></span><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);" /></span></span></span></span></span></span></span></span></span></span></span></span>
<h1 style="text-decoration: underline;"><font><font><font color="#000000"><font style="font-size: 12pt;" size="3">Η τελική κατασκευή</font></font></font></font></h1>

<table style="text-align: left; width: 100%;" border="1" cellpadding="2" cellspacing="2">
  <tbody>
    <tr>
      <td style="vertical-align: top;"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><img style="width: 250px; height: 333px;" alt="im33" src="photos/IMG_20200721_114752.jpg" /></span></span>
      </td>
      <td style="vertical-align: top;"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><img style="width: 250px; height: 333px;" alt="im34" src="photos/IMG_20200721_120545.jpg" /></span></span></span></span></span>
      </td>
      <td style="vertical-align: top;"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><img style="width: 250px; height: 333px;" alt="im35" src="photos/IMG_20200722_174813.jpg" /></span></span></span></span></span>
      </td>
      
      
    </tr>
    <tr>
      <td style="vertical-align: top;"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><img style="width: 250px; height: 333px;" alt="im36" src="photos/IMG_20200722_174827.jpg" /></span></span></span></span></span>
      </td>
      <td style="vertical-align: top;"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><img style="width: 250px; height: 333px;" alt="im37" src="photos/IMG_20200723_140644.jpg" /></span></span></span></span></span>
      </td>
      <td style="vertical-align: top;"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><img style="width: 250px; height: 333px;" alt="im38" src="photos/IMG_20200723_140653.jpg" /></span></span></span></span></span>
      </td>
      
      
    </tr>
    <tr>
      <td style="vertical-align: top;"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><img style="width: 250px; height: 333px;" alt="im39" src="photos/IMG_20200723_140719.jpg" /></span></span></span></span></span>
      </td>
      <td style="vertical-align: top;"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><br />
</span></span></span></span></span>
      </td>
      <td style="vertical-align: top;"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><span style="font-size: 12pt; color: rgb(0, 0, 0);"><br />
</span></span></span></span></span>
      </td>
      
      
    </tr>
  </tbody>
</table>
<br />
<br />
</span></span></span><span style="font-size: 12pt; color: rgb(0, 0, 0);">
<h2><small><small><big><big><big><small><small><big><big><big><small><small><big><big><big><small><small><span style="font-size: 12pt; color: rgb(0, 0, 0);"><big><big><big><span style="font-weight: bold; text-decoration: underline;">Μετρήσεις και Αποτελέσματα<br />
</span></big></big></big></span></small></small></big></big></big></small></small></big></big></big></small></small></big></big></big></small></small></h2>
Οι μετρήσεις που θα καταγραφούν μέσα στις κάρτες sd θα αποθηκευτούν σε
ένα αρχείο .csv έτσι ώστε να μπορούμε να τα κάνουμε εισαγωγή με εύκολο
τρόπο στο πρόγραμμα calc του libre office και να δημιουργήσουμε
γραφήματα των μετρήσεων.<br />
<br />
<table style="text-align: left; width: 100%;" border="1" cellpadding="2" cellspacing="2">
  <tbody>
    <tr>
      <td style="vertical-align: top; font-weight: bold; text-align: center;">Περιοχή μέτρησης<br />
      </td>
      <td style="vertical-align: top; font-weight: bold; text-align: center;">Ημ/νια-ώρα<br />
&nbsp;μέτρησης<br />
      </td>
      <td style="vertical-align: top; font-weight: bold; text-align: center;">Υψόμετρο<br />
      </td>
      <td style="vertical-align: top; font-weight: bold; text-align: center;">Θερμοκρασία<br />
      </td>
      <td style="vertical-align: top; font-weight: bold; text-align: center;">Υγρασία<br />
      </td>
      <td style="vertical-align: top; font-weight: bold; text-align: center;">Ατμ. πίεση<br />
      </td>
      <td style="vertical-align: top; font-weight: bold; text-align: center;">Αρχείο csv<br />
      </td>
      <td style="vertical-align: top; font-weight: bold; text-align: center;">Γράφημα<br />
      </td>
    </tr>
    <tr>
      <td style="vertical-align: top;"><img style="width: 220px; height: 440px;" alt="loca" src="photos/Screenshot_20200724-170919.png" /><br />
      </td>
      <td style="vertical-align: top;"><br />
      </td>
      <td style="vertical-align: top;"><br />
      </td>
      <td style="vertical-align: top;"><br />
      </td>
      <td style="vertical-align: top;"><br />
      </td>
      <td style="vertical-align: top;"><br />
      </td>
      <td style="vertical-align: top;"><br />
      </td>
      <td style="vertical-align: top;"><br />
      </td>
    </tr>
    <tr>
      <td style="vertical-align: top;"><img style="width: 220px; height: 440px;" alt="locb" src="photos/Screenshot_20200724-171000.png" /><br />
      </td>
      <td style="vertical-align: top;"><br />
      </td>
      <td style="vertical-align: top;"><br />
      </td>
      <td style="vertical-align: top;"><br />
      </td>
      <td style="vertical-align: top;"><br />
      </td>
      <td style="vertical-align: top;"><br />
      </td>
      <td style="vertical-align: top;"><br />
      </td>
      <td style="vertical-align: top;"><br />
      </td>
    </tr>
    <tr>
      <td style="vertical-align: top;"><img style="width: 220px; height: 440px;" alt="locc" src="photos/Screenshot_20200724-171102.png" /><br />
      </td>
      <td style="vertical-align: top;"><br />
      </td>
      <td style="vertical-align: top;"><br />
      </td>
      <td style="vertical-align: top;"><br />
      </td>
      <td style="vertical-align: top;"><br />
      </td>
      <td style="vertical-align: top;"><br />
      </td>
      <td style="vertical-align: top;"><br />
      </td>
      <td style="vertical-align: top;"><br />
      </td>
    </tr>
  </tbody>
</table>
<br />
</span></span></span></span></span></div>
</div>

</body></html>