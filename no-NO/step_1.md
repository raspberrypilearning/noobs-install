### Laste ned NOOBS

Å bruke NOOBS er den enkleste måten å installere Raspbian på ditt SD-kort. For å få tak i en kopi av NOOBS:

+ Besøk [www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/)

![Nedlastingsside](images/downloads-page.png)

+ Du bør se en boks med en lenke til NOOBS-filene. Klikk på lenken.

![Klikk på NOOBS](images/click-noobs.png)

+ Det enkleste alternativet er å laste ned zip-arkivet med filene.

![Last ned zip](images/download-zip.png)

### Formatering av SD-kortet

Hvis SD-kortet du vil installere Raspbian på inneholder en eldre versjon av Raspbian, kan det være lurt å sikkerhetskopiere filene fra kortet først, da de blir overskrevet i løpet av denne prosessen.

+ Besøk nettstedet til SD Association og last ned [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) for Windows eller Mac.

+ Følg instruksjonene for å installere programvaren.

+ Sett inn SD-kortet i datamaskinens eller den bærbare maskinens SD-kortleser og legg merke til stasjonsbokstaven den er tildelt, f.eks. `F: /`.

+ I SD Formatter velger du stasjonsbokstaven for SD-kortet ditt, og formaterer det.

### Pakk ut NOOBS fra zip arkivet

Deretter må du pakke ut filene fra NOOBS zip-arkivet du lastet ned fra Raspberry Pi-nettstedet.

+ Gå til *Nedlastinger* mappen din og finn zip-filen du lastet ned.

+ Pakk ut filene og hold det resulterende Utforsker / Finder-vinduet åpent.

### Kopiere filene

+ Nå åpner du et annet Utforsker/Finder-vindu og navigerer til SD-kortet. Det er best å plassere de to vinduene side ved side.

+ Velg alle filene fra *NOOBS* mappen og dra dem over til SD-kortet.

![windows kopi](images/copy3.png)

![macos kopi](images/macos_copy.png)

+ Løs ut SD-kortet.

### Starte fra NOOBS

+ Når filene er kopiert over, sett inn SD-kortet i din Raspberry Pi, og koble Pi-en til en strømkilde.

+ Du får nå et valg når installasjonsprogrammet har lastet inn. Du bør velge boksen for **Raspbian**, og klikke deretter **Install (Installer)**.

![installere](images/install.png)

+ Klikk **Yes (Ja)** i dialogenboksen, og sett deg tilbake og slapp av. Det tar litt tid, men Raspbian vil installeres.

![installasjon](images/installing.png)

+ Når Raspbian er installert, klikk **OK** og din Raspberry Pi vil starte på nytt og Raspbian vil da starte opp.

![installert](images/installed.png)