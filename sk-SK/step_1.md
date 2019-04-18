### Stiahnutie NOOBS

Najjednoduchší spôsob, ako nainštalovať Raspbian na tvoju SD kartu, je pomocou NOOBS. Ak chceš získať kópiu NOOBS:

+ Navštív stránku [www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/)

![Stránka na prevzatie](images/downloads-page.png)

+ Mal(a) by si vidieť rámček s odkazom na súbory NOOBS. Klikni na odkaz.

![Klikni na NOOBS](images/click-noobs.png)

+ Najjednoduchšou možnosťou je stiahnuť zip archív so súbormi.

![Stiahnuť zip](images/download-zip.png)

### Formátovanie SD karty

Ak sa na SD karte, na ktorú chceš nainštalovať Raspbian, nachádza staršia verzia Raspbian-u, možno budeš chcieť najskôr zálohovať súbory z karty, pretože budú počas tohto procesu prepísané.

+ Navštív webovú stránku SD Association a stiahni si [SD Formatter](https://www.sdcard.org/downloads/formatter_4/index.html) pre systém Windows alebo Mac.

+ Postupuj podľa pokynov na inštaláciu softvéru.

+ Vlož SD kartu do čítačky SD kariet svojho počítača alebo laptopu a poznač si písmeno jednotky, ktoré jej bolo priradené, napr. `F: /`.

+ V aplikácii SD Formatter vyber písmeno jednotky SD karty a naformátuj ju.

### Rozbalenie NOOBS zo zip archívu

Ďalej budeš musieť rozbaliť súbory zo zip archívu NOOBS, ktorý máš stiahnutý z webovej stránky Raspberry Pi.

+ Prejdi do priečinka *Stiahnutých súborov* a nájdi zip súbor, ktorý máš stiahnutý.

+ Rozbaľ súbory a nechaj otvorené okno aplikácie Prieskumník/Finder.

### Kopírovanie súborov

+ Otvor nové okno aplikácie Prieskumník/Finder a prejdi na SD kartu. Najlepšie je umiestniť obe okná vedľa seba.

+ Označ všetky súbory z priečinku *NOOBS* a presuň ich na SD kartu.

![kopírovanie v systéme Windows](images/copy3.png)

![kopírovanie v systéme MacOS](images/macos_copy.png)

+ Vyber SD kartu.

### Zavádzanie z NOOBS

+ Po prekopírovaní súborov vlož micro SD kartu do svojho Raspberry Pi a zapoj Pi do zdroja napájania.

+ Po načítaní ti inštalátor ponúkne možnosť výberu. Začiarkni políčko **Raspbian** a klikni na tlačidlo **Inštalovať**.

![inštalovať](images/install.png)

+ Klikni na tlačidlo **Áno** v dialógovom okne s upozornením a potom sa už len pohodlne posaď a relaxuj. Bude to chvíľu trvať, ale Raspbian sa nainštaluje.

![inštalácia](images/installing.png)

+ Keď sa Raspbian nainštaluje, klikni na tlačidlo **OK** a tvoje Raspberry Pi sa reštartuje a následne sa spustí Raspbian.

![nainštalované](images/installed.png)