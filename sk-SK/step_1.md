### Stiahnutie NOOBS

Najjednoduchší spôsob, ako nainštalovať Raspbian na vašu SD kartu, je pomocou NOOBS. Ak chcete získať kópiu NOOBS:

+ Navštívte stránku [www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/)

![Stránka na prevzatie](images/downloads-page.png)

+ Mali by ste vidieť rámček s odkazom na súbory NOOBS. Kliknite na odkaz.

![Kliknite na NOOBS](images/click-noobs.png)

+ Najjednoduchšou možnosťou je stiahnuť zip archív so súbormi.

![Stiahnuť zip](images/download-zip.png)

### Formátovanie SD karty

Ak sa na SD karte, na ktorú chcete nainštalovať Raspbian, nachádza staršia verzia Raspbian-u, možno budete chcieť najskôr zálohovať súbory z karty, pretože budú počas tohto procesu prepísané.

+ Navštívte webovú stránku SD Association a stiahnite si [SD Formatter](https://www.sdcard.org/downloads/formatter_4/index.html) pre systém Windows alebo Mac.

+ Postupujte podľa pokynov na inštaláciu softvéru.

+ Vložte SD kartu do čítačky SD kariet vášho počítača alebo laptopu a poznačte si písmeno jednotky, ktoré jej bolo priradené, napr. `F: /`.

+ V aplikácii SD Formatter vyberte písmeno jednotky SD karty a naformátujte ju.

### Rozbalenie NOOBS zo zip archívu

Ďalej budete musieť rozbaliť súbory zo zip archívu NOOBS, ktorý ste stiahli z webovej stránky Raspberry Pi.

+ Prejdite do priečinka *Stiahnutých súborov* a nájdite zip súbor, ktorý ste stiahli.

+ Rozbaľte súbory a nechajte otvorené okno aplikácie Prieskumník/Finder.

### Kopírovanie súborov

+ Otvorte nové okno aplikácie Prieskumník/Finder a prejdite na SD kartu. Najlepšie je umiestniť obe okná vedľa seba.

+ Označte všetky súbory z priečinku *NOOBS* a presuňte ich na SD kartu.

![kopírovanie v systéme Windows](images/copy3.png)

![kopírovanie v systéme MacOS](images/macos_copy.png)

+ Vysuňte SD kartu.

### Zavádzanie z NOOBS

+ Po prekopírovaní súborov vložte micro SD kartu do vášho Raspberry Pi a zapojte Pi do zdroja napájania.

+ Po načítaní vám inštalátor ponúkne možnosť výberu. Začiarknite políčko **Raspbian** a kliknite na tlačidlo **Inštalovať**.

![inštalovať](images/install.png)

+ Kliknite na tlačidlo **Áno** v dialógovom okne s upozornením a potom sa už len pohodlne posaďte a relaxujte. Bude to chvíľu trvať, ale Raspbian sa nainštaluje.

![inštalácia](images/installing.png)

+ Keď sa Raspbian nainštaluje, kliknite na tlačidlo **OK** a vaše Raspberry Pi sa reštartuje a následne sa spustí Raspbian.

![nainštalované](images/installed.png)