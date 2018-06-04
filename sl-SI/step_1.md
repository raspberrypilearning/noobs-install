### Prenos NOOBS-a

Uporaba NOOBS-a je najlažji način namestitve programa Raspbian na kartico SD. Za pridobitev kopije NOOBS-a:

+ Obiščite [www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/)

![Stran za prenos](images/downloads-page.png)

+ Videti bi morali polje s povezavo do datotek NOOBS. Kliknite povezavo.

![Kliknite na NOOBS](images/click-noobs.png)

+ Najpreprostejša možnost je prenesti zip arhiv datotek.

![Prenesi zip](images/download-zip.png)

### Oblikovanje kartice SD

Če SD kartica, na kateri želite namestiti Raspbian, trenutno vsebuje starejšo različico programa Raspbian, boste morda želeli najprej varnostno kopirati datoteke s kartice, saj bodo med tem postopkom prepisani.

+ Obiščite spletno stran SD Association in prenesite [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) za Windows ali Mac.

+ Sledite navodilom za namestitev programske opreme.

+ Vstavite kartico SD v bralnik pomnilniških kartic računalnika ali laptopa in zabeležite črko pogona, ki ji je dodeljena, npr. `F: /`.

+ V formatu SD Formatter izberite črko pogona za kartico SD in jo formatirajte.

### Izvleček NOOBS iz zip arhiva

Nato boste morali iz datoteke NOOBS zip arhivirati datoteke, ki ste jih prenesli s spletne strani Raspberry Pi.

+ Pojdite v mapo *Prenosov* in poiščite datoteko zip, ki ste jo prenesli.

+ Izvlecite datoteke in odprite okno Explorer / Finder.

### Kopiranje datotek

+ Zdaj odprite novo okno Explorer / Finder in se pomaknite do kartice SD. Najbolje je, da oba okna namestite drug ob drugem.

+ Izberite vse datoteke iz mape *NOOBS* in jih povlecite na kartico SD.

![okno kopiranje](images/copy3.png)

![macos copy](images/macos_copy.png)

+ Izvržite SD kartico.

### Booting iz NOOBS

+ Ko so datoteke kopirane, vstavite kartico micro SD v vašo Raspberry Pi in priključite Pi v vir napajanja.

+ Ponudnik vam bo ponudil izbiro, ko bo nalagal namestitveni program. Potrdite polje za **Raspbian**in nato kliknite **Namesti**.

![namestite](images/install.png)

+ V opozorilnem pogovornem oknu kliknite **Da** in nato sedite in se sprostite. To bo trajalo nekaj časa, toda Raspbian bo namestil.

![nameščanje](images/installing.png)

+ Ko je bil nameščen program Raspbian, kliknite **OK** in se bo vaš Raspberry Pi znova zagnal, nato pa se bo razširil program Raspbian.

![nameščen](images/installed.png)