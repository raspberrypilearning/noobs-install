### Prenos NOOBS-a

NOOBS omogoča najbolj enostaven način namestitve sistema Raspbian na SD kartico. Za pridobitev NOOBS-a:

+ Obiščite [www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/)

![Stran za prenos](images/downloads-page.png)

+ Videti bi morali gumb s povezavo do datotek NOOBS. Kliknite povezavo.

![Kliknite na NOOBS](images/click-noobs.png)

+ Najbolj enostavna možnost je, da prenesete zip arhiv datotek.

![Prenesi zip](images/download-zip.png)

### Formatiranje SD kartice

Če SD kartica, na kateri želite namestiti Raspbian, trenutno vsebuje starejšo različico tega, boste morda želeli najprej varnostno kopirati datoteke s kartice, saj bodo med tem postopkom izbrisane.

+ Obiščite spletno stran SD Association in prenesite [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) za Windows ali Mac.

+ Sledite navodilom za namestitev programske opreme.

+ Vstavite SD kartico v bralnik pomnilniških kartic računalnika in si zapomnite črko pogona, ki ji je dodeljena, npr. `F: /`.

+ V programu SD Formatter izberite črko pogona SD kartice in jo formatirajte.

### Razširjanje NOOBS-a iz zip arhiva

V naslednjem koraku boste morali razširiti datoteke iz NOOBS zip arhiva, ki ste ga pred tem prenesli iz Spletne strani Rasberry Pi.

+ Pojdite v mapo *Prenosi* in poiščite datoteko zip, ki ste jo prenesli.

+ Razširite datoteke in pustite odprto okno Raziskovalec / Explorer / Finder, ki se ob tem pojavi.

### Kopiranje datotek

+ Odprite še en Raziskovalec / Explorer / Finder in poiščite SD kartico. Najbolje je, da oba okna postavite drug ob drugem.

+ Izberite vse datoteke iz mape *NOOBS* in jih povlecite na kartico SD.

![kopiranje v sistemu windows](images/copy3.png)

![kopiranje v sistemu macos](images/macos_copy.png)

+ Izvrzite SD kartico.

### Zaganjanje iz NOOBS-a

+ Potem ko so datoteke prekopirane, vstavite microSD kartico v svoj Raspberry Pi in ga priključite na vir napajanja.

+ Namestitveni program vam bo ponudil izbor operacijskih sistemov. Označite **Raspbian**in nato kliknite **Namesti / Install**.

![namestitev](images/install.png)

+ V oknu z opozorilom kliknite **Da / Yes**, nato pa sedite in se sprostite. Namestitev bo trajala nekaj časa.

![nameščanje](images/installing.png)

+ Ko bo Raspbian nameščen, kliknite **OK** in Raspberry Pi se bo znova zagnal, nato pa se bo zagnal Raspbian.

![nameščen](images/installed.png)