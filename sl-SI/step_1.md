### Prenos NOOBS-a

Uporaba NOOBS-a je najlažji način namestitve sistema Raspbian na SD kartico. Za pridobitev NOOBS-a:

+ Obiščite [www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/)

![Stran za prenos](images/downloads-page.png)

+ Videti bi morali gumb s povezavo do datotek NOOBS. Kliknite povezavo.

![Kliknite na NOOBS](images/click-noobs.png)

+ Najpreprostejša možnost je prenesti zip arhiv datotek.

![Prenesi zip](images/download-zip.png)

### Formatiranje kartice SD

Če SD kartica, na kateri želite namestiti Raspbian, trenutno vsebuje starejšo različico programa Raspbian, boste morda želeli najprej varnostno kopirati datoteke s kartice, saj bodo med tem postopkom izbrisane.

+ Obiščite spletno stran SD Association in prenesite [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) za Windows ali Mac.

+ Sledite navodilom za namestitev programske opreme.

+ Vstavite SD kartico v bralnik pomnilniških kartic računalnika in zabeležite črko pogona, ki ji je dodeljena, npr. `F: /`.

+ V formatu SD Formatter izberite črko pogona za kartico SD in jo formatirajte.

### Razširjenje NOOBS-a iz zip arhiva

Nato boste morali iz zip datoteke NOOBS-a pridobiti datoteke.

+ Pojdite v mapo *Prenosi* in poiščite datoteko zip, ki ste jo prenesli.

+ Izvlecite datoteke in odprite Raziskovalec / Explorer / Finder.

### Kopiranje datotek

+ Zdaj odprite nov Raziskovalec / Explorer / Finder in se pomaknite do SD kartice. Najbolje je, da oba okna postavite drug ob drugem.

+ Izberite vse datoteke iz mape *NOOBS* in jih povlecite na kartico SD.

![kopiranje v sistemu windows](images/copy3.png)

![kopiranje v sistemu macos](images/macos_copy.png)

+ Izvrzite SD kartico.

### Zaganjanje NOOBS-a

+ Ko so datoteke kopirane, microSD kartico vstavite v Raspberry Pi in ga priključite v vir napajanja.

+ Namestitveni program vam bo ponudil izbiro operacijskih sistemov. Izberite **Raspbian**in nato kliknite **Namesti / Install**.

![namestitev](images/install.png)

+ V opozorilnem pogovornem oknu kliknite **Da / Yes** in nato sedite in se sprostite. Namestitev bo trajala nekaj časa.

![nameščanje](images/installing.png)

+ Ko bo Raspbian nameščen, kliknite **OK** in Raspberry Pi se bo znova zagnal, nato pa se bo zagnal Raspbian.

![nameščen](images/installed.png)