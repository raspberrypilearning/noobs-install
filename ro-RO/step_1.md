### Descărcarea NOOBS

Folosind NOOBS este cel mai simplu mod de a instala Raspbian pe cardul SD. Pentru a obține o copie a NOOBS:

+ Vizitați [www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/)

![Pagina de descărcări](images/downloads-page.png)

+ Ar trebui să vedeți o casetă cu un link către fișierele NOOBS. Apasă pe link.

![Faceți clic pe NOOBS](images/click-noobs.png)

+ Cea mai simplă opțiune este să descărcați arhiva zip a fișierelor.

![Descărcați zip](images/download-zip.png)

### Formatarea cardului SD

Dacă cardul SD pe care dorești să instalezi Raspbian are în prezent o versiune mai veche de Raspbian, poți să faci mai întâi copia de rezervă a fișierelor de pe card, deoarece acestea vor fi suprascrise în timpul acestui proces.

+ Accesați site-ul web al Grupurilor SD și descărcați [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) pentru Windows sau Mac.

+ Urmați instrucțiunile pentru a instala programul.

+ Introduceți cardul SD în cititorul de carduri SD al computerului sau al laptopului și notați litera de unitate alocată acestuia, de exemplu `F: /`.

+ În formatatorul SD, selectați litera unității pentru cardul SD și formatați-o.

### Extragerea NOOBS din arhiva zip

Apoi, va trebui să extrageți fișierele din arhiva zip NOOBS pe care ați descărcat-o de pe site-ul Raspberry Pi.

+ Accesați dosarul *Descărcări* și găsiți fișierul zip pe care l-ați descărcat.

+ Extrageți fișierele și păstrați fereastra rezultată Explorer/Finder deschisă.

### Copierea fișierelor

+ Deschideți acum o altă fereastră Explorer/Finder și navigați pe cardul SD. Cel mai bine este să poziționați cele două ferestre una lângă alta.

+ Selectați toate fișierele din dosarul *NOOBS* și glisați-le pe cardul SD.

![copie windows](images/copy3.png)

![copie macos](images/macos_copy.png)

+ Scoateți cardul SD.

### Porniți de pe NOOBS

+ Odată ce fișierele au fost copiate, introduceți cardul microSD în Raspberry Pi și conectați dispozitivul Pi la o sursă de alimentare.

+ V-a trebui să faceți o alegere, atunci când programul de instalare a fost încărcat. Ar trebui să bifați caseta pentru **Raspbian**, apoi faceți clic pe **Install**.

![instalare](images/install.png)

+ Faceți clic pe **Da** din dialogul de avertizare, și apoi așteptați. Va dura ceva timp, dar Raspbian se va instala.

![Instalarea](images/installing.png)

+ Odată Raspbian a fost instalat, faceți clic pe **OK** și Raspberry Pi va reporni iar sistemul de operate Raspbian va rula.

![instalat](images/installed.png)