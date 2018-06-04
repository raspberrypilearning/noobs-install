### NOOBS: n lataaminen

NOOBS: n käyttö on helpoin tapa asentaa Raspbian SD-kortille. Jotta saat kopion NOOBS: stä:

+ Käy [www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/)

![Lataussivu](images/downloads-page.png)

+ Sinun pitäisi nähdä laatikko, jossa on linkki NOOBS-tiedostoihin. Napsauta linkkiä.

![Napsauta NOOBS](images/click-noobs.png)

+ Yksinkertaisin vaihtoehto on ladata tiedostojen zip-arkisto.

![Lataa zip](images/download-zip.png)

### SD-kortin alustaminen

Jos SD-kortti, johon haluat asentaa Raspbianin tällä hetkellä on vanhempi Raspbian-versio, voit halutessasi varmuuskopioida tiedostoja kortilta ensin, koska ne korvataan tämän prosessin aikana.

+ Käy SD Associationin verkkosivuilla ja lataa [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) Windowsille tai Macille.

+ Asenna ohjelmisto noudattamalla ohjeita.

+ Aseta SD-kortti tietokoneeseen tai kannettavan tietokoneen SD-kortinlukijaan ja kirjoita sille osoitetun aseman kirjain, esim. `F: /`.

+ Valitse SD Formatter -ohjelmassa SD-kortille aseman kirjain ja alusta se.

### NOOBS: n purku zip-arkistosta

Seuraavaksi sinun on purettava tiedostot NPSPS-arkistosta, jonka olet ladannut Raspberry Pi -sivustosta.

+ Siirry *Downloads* kansioon ja etsi lataamasi zip-tiedosto.

+ Pura tiedostot ja säilytä Resurssienhallinta / Etsijä-ikkuna auki.

### Tiedostojen kopiointi

+ Avaa nyt uusi Explorer / Finder-ikkuna ja siirry SD-kortille. On parasta sijoittaa kaksi ikkunaa vierekkäin.

+ Valitse kaikki tiedostot *NOOBS* -kansiosta ja vedä ne SD-kortille.

![ikkunat kopioida](images/copy3.png)

![macos kopio](images/macos_copy.png)

+ Poista SD-kortti.

### Käynnistys NOOBS: stä

+ Kun tiedostot on kopioitu, aseta mikro-SD-kortti vadelmillesi Pi ja kytke Pi-liitin virtalähteeseen.

+ Sinulle tarjotaan valinnanvaraa, kun asennusohjelma on ladannut. Tarkista ruutu **Raspbian**ja valitse sitten **Asenna**.

![Asentaa](images/install.png)

+ Valitse varoitusikkunasta **Kyllä** ja istu sitten takaisin ja rentoudu. Se vie jonkin aikaa, mutta Raspbian asentaa.

![asennus](images/installing.png)

+ Kun Raspbian on asennettu, valitse **OK** ja Raspberry Pi käynnistyy uudelleen ja Raspbian sitten käynnisty.

![asennetut](images/installed.png)