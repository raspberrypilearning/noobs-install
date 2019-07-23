### Descărcarea NOOBS

Cea mai simplă cale de a instala Raspbian pe cardul SD este NOOBS. Pentru a obține o copie a NOOBS:

+ Vizitează [www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/)

![Pagina de descărcări](images/downloads-page.png)

+ Ar trebui să vezi o casetă cu un link către fișierele NOOBS. Apasă pe link.

![Apasă pe NOOBS](images/click-noobs.png)

+ Cea mai simplă opțiune este să descarci arhiva zip a fișierelor.

![Descarcă zip](images/download-zip.png)

### Formatarea cardului SD

Dacă cardul SD pe care dorești să instalezi Raspbian are în prezent o versiune mai veche de Raspbian, ar fi bine să faci mai întâi o copie de rezervă a fișierelor de pe card, deoarece acestea vor fi șterse în timpul acestui proces.

+ Accesează site-ul web al SD Association și descarcă [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) pentru Windows sau Mac.

+ Urmează instrucțiunile pentru a instala programul.

+ Introdu cardul de memorie SD în cititorul de carduri SD al computerului sau al laptopului și ține minte litera de unitate alocată acestuia, de exemplu `F:/`.

+ În SD Formatter, selectează litera unității pentru cardul SD și formateaz-o.

### Extragerea NOOBS din arhiva zip

Apoi, va trebui să extragi fișierele din arhiva zip NOOBS pe care ai descărcat-o de pe site-ul Raspberry Pi.

+ Accesează dosarul *Descărcări* și caută fișierul zip pe care l-ai descărcat.

+ Extrage fișierele și păstrează fereastra Explorer/Finder deschisă.

### Copierea fișierelor

+ Deschide acum o altă fereastră Explorer/Finder și navighează pe cardul SD. Cel mai bine este să poziționezi cele două ferestre una lângă alta.

+ Selectează toate fișierele din dosarul *NOOBS* și copiază-le pe cardul SD.

![copie windows](images/copy3.png)

![copie macos](images/macos_copy.png)

+ Scoate cardul SD.

### Pornirea NOOBS

+ Odată ce fișierele au fost copiate, introdu cardul microSD în Raspberry Pi și conectează dispozitivul Pi la o sursă de alimentare.

+ Va trebui să faci o alegere atunci când programul de instalare a fost încărcat. Bifează caseta pentru **Raspbian**, apoi apasă pe **Install**.

![instalare](images/install.png)

+ Apasă pe **Yes** din dialogul de avertizare, apoi așteaptă. Va dura ceva timp până când Raspbian se va instala.

![Instalarea](images/installing.png)

+ Odată ce Raspbian a fost instalat, apasă pe **OK** și Raspberry Pi va reporni iar sistemul de operate Raspbian va rula.

![instalat](images/installed.png)