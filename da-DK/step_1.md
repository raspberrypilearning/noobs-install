### Download NOOBS

Brug af NOOBS er den nemmeste måde at installere Raspbian på dit SD-kort. For at få fat i en kopi af NOOBS:

+ Besøg [www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/)

![Downloads side](images/downloads-page.png)

+ Du skal se en boks med et link til NOOBS-filerne. Klik på linket.

![Klik på NOOBS](images/click-noobs.png)

+ Den nemmeste mulighed er at downloade zip-arkivet for filerne.

![Download zip](images/download-zip.png)

### Formatering af SD-kortet

Hvis det SD-kort, som du ønsker at installere Raspbian på, har en ældre version af Raspbian på den, kan du først sikkerhedskopiere filerne fra kortet, da de overskrives under denne proces.

+ Besøg SD Association's hjemmeside og download [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) til Windows eller Mac.

+ Følg vejledningen for at installere softwaren.

+ Indsæt dit SD-kort i computerens eller bærbarens SD-kortlæser og noter det drevbogstav der er tildelt det, f.eks. `F: /`.

+ I SD Formatter skal du vælge drevbogstav for dit SD-kort og formatere det.

### Uddragning af NOOBS fra zip arkivet

Derefter skal du udpakke filerne fra NOOBS zip-arkivet, du downloadede fra Raspberry Pi-webstedet.

+ Gå til din *Downloads* mappe og find den zip-fil, du downloadede.

+ Udpak filerne og hold det resulterende Explorer / Finder-vindue åbent.

### Kopiering af filerne

+ Nu åbner du et andet Explorer / Finder-vindue og navigerer til SD-kortet. Det er bedst at placere de to vinduer side om side.

+ Vælg alle filerne fra *NOOBS* mappen og træk dem på SD-kortet.

![Windows kopi](images/copy3.png)

![macos kopi](images/macos_copy.png)

+ Skub SD-kortet ud.

### Opstart fra NOOBS

+ Når filerne er blevet kopieret over, skal du indsætte micro SD-kortet i din Raspberry Pi, og tilslut Pi'en til en strømkilde.

+ Du bliver tilbudt et valg, når installationsprogrammet er indlæst. Du skal markere feltet til **Raspbian**, og derefter klikke **Install**.

![installere](images/install.png)

+ Klik på **Ja** ved advarselsdialogboksen, og læn dig tilbage og slap af. Det tager lidt tid, men Raspbian vil installere.

![installation](images/installing.png)

+ Når Raspbian er installeret, klik på **OK** og din Raspberry Pi genstarter, og Raspbian starter derefter op.

![installeret](images/installed.png)