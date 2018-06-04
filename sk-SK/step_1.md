### Sťahovanie NOOBS

Použitie NOOBS je najjednoduchší spôsob nainštalovania Raspbian na vašu SD kartu. Ak chcete získať kópiu NOOBS:

+ Navštívte [www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/)

![Stránka na prevzatie](images/downloads-page.png)

+ Mali by ste vidieť rámček s odkazom na súbory NOOBS. Kliknite na odkaz.

![Kliknite na NOOBS](images/click-noobs.png)

+ Najjednoduchšou možnosťou je prevziať zip archív súborov.

![Stiahnuť zip](images/download-zip.png)

### Formátovanie karty SD

Ak má SD karta, na ktorú chcete nainštalovať Raspbian, v súčasnosti staršiu verziu Raspbian, možno budete chcieť najskôr zálohovať súbory z karty, pretože budú počas tohto procesu prepísané.

+ Navštívte webovú stránku združenia SD a stiahnite si [SD formátovač 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) pre systém Windows alebo Mac.

+ Pri inštalácii softvéru postupujte podľa pokynov.

+ Vložte kartu SD do čítačky kariet SD alebo počítača a poznačte si písmeno, ktoré je priradené, napr. `F: /`.

+ V SD formátovači vyberte písmeno jednotky pre SD kartu a naformátujte ju.

### Extrakcia NOOBS zo zip archívu

Ďalej budete musieť extrahovať súbory z archívu zip NOOBS, ktorý ste stiahli z webovej stránky Raspberry Pi.

+ Prejdite do priečinka *načítania* a nájdite súbor, ktorý ste stiahli.

+ Extrahujte súbory a nechajte otvorené okno Explorer / Finder.

### Kopírovanie súborov

+ Teraz otvorte ďalšie okno Explorer / Finder a prejdite na kartu SD. Najlepšie je umiestniť dve okná vedľa seba.

+ Vyberte všetky súbory zo zložky *NOOBS* a presuňte ich na kartu SD.

![windows copy](images/copy3.png)

![kópia macos](images/macos_copy.png)

+ Vysuňte kartu SD.

### Zavádzanie z NOOBS

+ Po skopírovaní súborov vložte kartu microSD do vášho Raspberry Pi a zapojte Pi do zdroja napájania.

+ Po načítaní inštalátora vám ponúkne možnosť výberu. Začiarknite políčko **Raspbian**a potom kliknite na **Install**.

![inštalovať](images/install.png)

+ Kliknite **Áno** v dialógovom okne varovanie, a potom sedieť a relaxovať. Bude to chvíľu trvať, ale Raspbian sa nainštaluje.

![inštalácia](images/installing.png)

+ Keď bol Raspbian nainštalovaný, kliknite na **OK** a vaša Raspberry Pi sa reštartuje a Raspbian sa potom spustí.

![nainštalovaný](images/installed.png)