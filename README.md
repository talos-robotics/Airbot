<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en" lang="en"><head>
  
  <meta http-equiv="content-type" content="text/html;charset=utf-8" />

  
  <meta name="generator" content="Geany 1.32" />

</head><body>
<div style="text-align: left; font-family: monospace;"><br />
<div style="text-align: center;">&nbsp;<img style="width: 256px; height: 256px;" src="https://avatars0.githubusercontent.com/u/57757898?s=460&amp;v=4" alt="center" /> </div>
</div>

<pre style="font-family: monospace;">	<h1 style="text-align: center;">Ανάλυση ατμοσφαιρικής ρύπανσης</h1><h1 style="text-align: center;">με δειγματοληπτικό έλεγχο</h1><h1 style="text-align: center;">(The Airbot project)</h1><h3><big>Σενάριο δραστηριότητας</big></h3>Αριθμός μαθητών: 9<br />Αριθμός Ομάδων: 3<br />Αριθμός ατόμων ανά ομάδα: 3<br />Είδος  δραστηριότητας: Ομαδοσυνεργατική<br />Ρόλοι: Δεν υπάρχουν διακριτοί ρόλοι στην ομάδα.<br />Ηλικιακή ομάδα: 12-15<br /><br /><h3><big>Φάση προετοιμασίας</big></h3>Οι μαθητές θα πρέπει να: <br />    • Διερευνήσουν στο διαδίκτυο και να ανακαλύψουν τους ρύπους της ατμόσφαιρας.<br />    • Συντάξουν ένα έντυπο όπου θα περιγράφουν τους σημαντικότερους ατμοσφαιρικούς ρύπους.<br />    • Να αναζητήσουν στο διαδίκτυο πληροφορίες για τους αισθητήρες που θα χρησιμοποιήσουμε.<br /><br /><h3><big>Φάση σχεδιασμού</big></h3>Οι μαθητές θα πρέπει να: <br />    • Να αναζητήσουν στο διαδίκτυο πληροφορίες για τη συνδεσμολογία των αισθητήρων με το Arduino.<br />    • Να αναζητήσουν στο διαδίκτυο πληροφορίες για τις προδιαγραφές των αισθητήρων.<br />    • Να δημιουργήσουν στο Fritzing τις παραπάνω συνδεσμολογίες.<br /><br /><br /><h3><big>Φάση υλοποίησης</big></h3>Οι μαθητές θα πρέπει να:<br />    • Δημιουργήσουν τις φυσικές συνδέσεις των υλικών τους με τους αισθητήρες.<br />    • Να προγραμματίσουν το Arduino χρησιμοποιώντας το περιβάλλον Mblock έτσι ώστε να παίρνουν τιμές από τους αισθητήρες.<br /><br /><h3><big>Φάση Δοκιμών</big></h3>Οι μαθητές θα πρέπει να:<br />    • Δοκιμάσουν τον εξοπλισμό τους και να επιβεβαιώσουν τη σωστή λειτουργία του.<br /><br /><br /><h3><big>Υλικά</big></h3><table style="width: 100%;" border="1">
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
    <td>Θα δημιουργηθούν 3 διαφορετικά υποσυστήματα</td>
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
</tbody></table> <br /><h3><big>Αναλυτική περιγραφή</big></h3>Οι μαθητές αφού ασχοληθούν με τους παράγοντες που δημιουργούν την ατμοσφαιρική ρύπανση,<br />θα δημιουργήσουν ένα σταθμό μέτρησης της ατμοσφαιρικής ρύπανσης.<br />Το σύστημα θα αποτελείτε από τρία επιμέρους υποσυστήματα, τα οποία θα έχουν κατανεμηθεί, 1 σε κάθε ομάδα, για υλοποίηση. <br />Τα συστήματα αυτά θα τοποθετηθούν σε μετεωρολογικά μπαλόνια, όπου θα είναι δεμένα με σπάγκο<br />και θα ανέβουν σε περίπου 100 – 200 μέτρα έτσι ώστε να αρχίσουν να παίρνουν μετρήσεις.<br /><br />Αυτή η διαδικασία θα γίνει σε 3 διαφορετικές περιοχές. <br />    1. Περιοχή με καμένα δέντρα<br />    2. Στο κέντρο της πόλης<br />    3. Περιοχή κατάμεστη από πράσινο σε μεγάλο ύψος<br />Οι μετρήσεις θα μελετηθούν από τους μαθητές και θα βγουν τα αντίστοιχα συμπεράσματα.<br /><br /><br /></pre>

<div style="text-align: center; font-family: monospace;">
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
<br />
</div>
</div>
</div>
</div>

<div style="text-align: center; font-family: monospace;">
<h3><big style="font-weight: bold;"><big><big>Θεωρητικό μέρος</big></big></big></h3>
<div style="text-align: left;">
<ul>
  <br />
</ul>
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
  <li><span style="font-weight: bold;">Αιωρούμενα σωματίδια:</span>ο
όρος σωματίδιο περιγράφει τα διάφορα σωματίδια που βρίσκονται στην
ατμόσφαιρα </li>
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
<br />
<h1 style="text-decoration: underline;"><font color="#000000"><font style="font-size: 12pt;" size="3">Ποιοί
αισθητήρες θα χρησιμοποιηθούν;</font></font></h1>
<br />
<p style="border: medium none ; line-height: 11.75pt; margin-top: 0pt; margin-bottom: 7.99999pt; font-weight: bold; text-decoration: underline;" class=""><big><big>BME280</big></big></p>
<p style="border: medium none ; line-height: 11.75pt; margin-top: 0pt; margin-bottom: 7.99999pt; font-weight: bold;" class=""><span style="font-weight: normal;">Γενικές πληροφορίες<br />
Σύνδεση με το Arduino<br />
</span></p>
<p style="border: medium none ; line-height: 11.75pt; margin-top: 0pt; margin-bottom: 7.99999pt;" class=""><span style="font-size: 12pt; color: rgb(0, 0, 0);">Ο
αισθητήρας BME280 και κατασκευάζεται από τη BOSCH. Χρησιμοποιείται
εύκολα διότι δεν χρειάζεται επιπλέον εξαρτήματα για να λειτουργήσει.
Μπορεί να μετρήσει με ακρίβεια <br />
</span></p>
<ul>
  <li><span style="font-size: 12pt; color: rgb(0, 0, 0);">υψόμετρο</span></li>
  <li><span style="font-size: 12pt; color: rgb(0, 0, 0);">βαρομετρική
πίεση ( πίεση της ατμόσφαιρας στη γη)</span></li>
  <li><span style="font-size: 12pt; color: rgb(0, 0, 0);">υγρασία
(0% εώς 100</span><span style="font-size: 12pt; color: rgb(0, 0, 0);">%)
    <br />
    </span></li>
  <li><span style="font-size: 12pt; color: rgb(0, 0, 0);">θερμοκρασία
(από -40</span><span style="font-size: 12pt; color: rgb(0, 0, 0); vertical-align: super;">0</span><span style="font-size: 12pt; color: rgb(0, 0, 0);">C
εώς 85</span><span style="font-size: 12pt; color: rgb(0, 0, 0); vertical-align: super;">ο</span><span style="font-size: 12pt; color: rgb(0, 0, 0);">C)
.</span></li>
</ul>
<br />
<p><big><big><span dir="auto"><span style="font-weight: bold; text-decoration: underline;">Dust Sensor
(GP2Y1010AU0F | GP2Y1014AU0F )</span></span></big></big></p>
<p><span dir="auto" /></p>
<br />
<br />
<h1 style="text-decoration: underline;"><small><small>Adafruit CCS811
Air Quality Sensor</small></small></h1>
<br />
<br />
<h1 style="text-decoration: underline;"><font color="#000000"><font style="font-size: 12pt;" size="3">Τι
μετρήσεις παίρνει;</font></font></h1>
<h1 style="text-decoration: underline;"><font color="#000000"><font style="font-size: 12pt;" size="3">Τρόπος
σύνδεσης με το Arduino (εικόνα απο το
Fritzing)</font></font></h1>
<h1 style="text-decoration: underline;"><font color="#000000"><font style="font-size: 12pt;" size="3">Tι
τιμές περιμένω να μου επιστρέψει ο
αισθητήρας;</font></font></h1>
<h1 style="text-decoration: underline;"><font color="#000000"><font style="font-size: 12pt;" size="3">Πώς
θα αποθηκεύσουμε τα δεδομένα;</font></font></h1>
<h1 style="text-decoration: underline;"><font color="#000000"><font style="font-size: 12pt;" size="3">Τρόπος
σύνδεσης με το Arduino (εικόνα απο το
Fritzing)</font></font></h1>
<ul>
  <br />
</ul>
<br />
</span></div>
</div>

</body></html>