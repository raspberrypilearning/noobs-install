### Preuzimanje NOOBS-a

Korištenje NOOBS-a najlakši je način za instalaciju Raspbian operacijskog sustava na SD karticu. Za dobivanje kopije NOOBS-a:

+ Posjeti [www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/)

![Stranica za preuzimanje](images/downloads-page.png)

+ Trebali biste vidjeti okvir s poveznicom na NOOBS datoteke. Klikni na poveznicu.

![Kliknite NOOBS](images/click-noobs.png)

+ Najjednostavniji način je preuzimanje zip datoteke.

![Preuzmite zip](images/download-zip.png)

### Formatiranje SD kartice

Ako SD kartica na koju želiš instalirati Raspbian trenutačno ima stariju verziju programa, možda ćeš prvo trebati sigurnosno kopirati datoteke s kartice. U protivnom će datoteke biti izbrisane tijekom instalacije.

+ Posjeti web stranicu SD Association i preuzmi [SD Formatter 5.0.1](https://www.sdcard.org/downloads/formatter_4/index.html) za Windows ili Mac.

+ Slijedi upute za instalaciju softvera.

+ Umetnite svoju SD karticu u čitač SD kartica na računalu ili laptopa i zabilježite dodijeljeno slovo pogona, npr. `F: /`.

+ U programu SD Formatter odaberite slovo pogona za SD karticu i formatirajte ga.

### Izvlačenje NOOBS iz zip arhive

Zatim ćete morati izdvojiti datoteke iz arhive zipa NOOBS koje ste preuzeli s web stranice Raspberry Pi.

+ Idite na mapu *Downloads* i pronađite zip datoteku koju ste preuzeli.

+ Izvadite datoteke i zadržite otvoreni prozor Explorer / Finder.

### Kopiranje datoteka

+ Sada otvorite još jedan prozor Explorer / Finder i idite na SD karticu. Najbolje je postaviti dva prozora jedan do drugoga.

+ Odaberite sve datoteke iz mape *NOOBS* i povucite ih na SD karticu.

![kopiranje sustava Windows](images/copy3.png)

![mako kopirati](images/macos_copy.png)

+ Izvadite SD karticu.

### Dizanje iz NOOBS-a

+ Nakon što su datoteke kopirane, umetnite mikro SD karticu u svoj maleni Pi i priključite Pi u izvor napajanja.

+ Bit će vam ponuđena mogućnost izbora kada je instalater umetnut. Provjerite okvir za **Raspbian**, a zatim kliknite **Instaliraj**.

![instalirati](images/install.png)

+ Kliknite **Da** u dijaloškom okviru upozorenja, a zatim se opustite. Potrajat će neko vrijeme, ali će Raspbian instalirati.

![instaliranje](images/installing.png)

+ Kad je instaliran Raspbian, kliknite **OK** i vaš malina Pi će se ponovno pokrenuti i Raspbian onda će dignuti.

![instaliran](images/installed.png)