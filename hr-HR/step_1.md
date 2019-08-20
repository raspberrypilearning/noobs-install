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

+ Umetni svoju SD karticu u čitač SD kartice na računalu ili laptopu i zapamti dodijeljeno slovo pogona, npr. `F: /`.

+ U programu SD Formatter odaberi slovo pogona za SD karticu i formatiraj ju.

### Raspakiravanje NOOBS-a iz zip arhive

Sada moraš raspakirati datoteke iz NOOBS zip arhive koju si preuzeo s Raspberry Pi web stranice.

+ Otvori mapu *Preuzimanja (Downloads)* i pronađi preuzetu zip datoteku.

+ Raspakiraj datoteke i ostavi prozor Explorer/Finder otvoren.

### Kopiranje datoteka

+ Sada otvori još jedan Explorer/Finder prozor i pronađi SD karticu. Najbolje je postaviti prozore jedan do drugoga.

+ Odaberi sve datoteke iz mape *NOOBS* i povuci ih u SD karticu.

![kopiranje sustava Windows](images/copy3.png)

![mako kopirati](images/macos_copy.png)

+ Izvadi SD karticu.

### Pokretanje NOOBS-a

+ Nakon što su datoteke kopirane, umetni mikro SD karticu u svoj Raspberry Pi i priključi Pi u izvor napajanja.

+ Bit će ti ponuđena mogućnost izbora nakon što se instalacijski program učita. Označi kućicu za **Raspbian**, a zatim klikni **Instaliraj (Install)**.

![instalirati](images/install.png)

+ Klikni **Da (Yes)** u dijaloškom okviru, a zatim sjedni i opusti se. Potrajat će neko vrijeme, ali Raspbian će se instalirati.

![instaliranje](images/installing.png)

+ Kad je Raspbian instaliran, klikni **OK** i tvoj će se Raspberry Pi, skupa s Raspbianom, ponovno pokrenuti.

![instaliran](images/installed.png)