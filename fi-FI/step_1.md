### NOOBS: n lataaminen

NOOBS: n käyttö on helpoin tapa asentaa Raspbian SD-kortille. Jotta saat kopion NOOBS: stä:

+ Käy [www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/)

![Lataussivu](images/downloads-page.png)

+ Etsi laatikko, jossa on linkki NOOBS-tiedostoihin. Napauta linkkiä.

![Napauta NOOBS](images/click-noobs.png)

+ Yksinkertaisin vaihtoehto on ladata tiedostojen zip-arkisto.

![Lataa zip](images/download-zip.png)

### SD-kortin alustaminen

Jos SD-kortti, johon haluat asentaa Raspbianin tällä hetkellä on vanhempi Raspbian-versio, voit halutessasi varmuuskopioida tiedostot kortilta ensin, koska ne korvataan tämän prosessin aikana.

+ Käy SD Associationin verkkosivuilla ja lataa [SD Formatter 4.0](https://www.sdcard.org/downloads/formatter_4/index.html) Windowsille tai Macille.

+ Asenna ohjelmisto noudattamalla ohjeita.

+ Aseta SD-kortti tietokoneeseen tai kannettavan tietokoneen SD-kortinlukijaan ja kirjoita sille osoitetun aseman kirjain, esim. `F: /`.

+ Valitse SD Formatter -ohjelmassa SD-kortille aseman kirjain ja alusta se.

### NOOBS: n purku zip-arkistosta

Seuraavaksi sinun on purettava tiedostot NOOBS zip-arkistosta, jonka olet ladannut Raspberry Pi -sivustosta.

+ Siirry *Downloads* kansioon ja etsi lataamasi zip-tiedosto.

+ Pura tiedostot ja pidä auennut Explorer/Finder-ikkuna auki.

### Tiedostojen kopiointi

+ Avaa nyt uusi Explorer / Finder-ikkuna ja siirry SD-kortille. On parasta sijoittaa kaksi ikkunaa vierekkäin.

+ Valitse kaikki tiedostot *NOOBS* -kansiosta ja vedä ne SD-kortille.

![windows kopio](images/copy3.png)

![macos kopio](images/macos_copy.png)

+ Poista SD-kortti.

### Käynnistys NOOBS: stä

+ Kun tiedostot on kopioitu, aseta micro SD-kortti Raspberry Pi:hin ja kytke Pi virtalähteeseen.

+ Sinulle tarjotaan valinnanvaraa, kun asennusohjelma on ladannut. Valitse ruutu **Raspbian**ja valitse sitten **Asenna**.

![asenna](images/install.png)

+ Valitse varoitusikkunasta **Kyllä** ja istu odottamaan ja rentoudu. Kestää jonkin aikaa, kun Raspbian asentuu.

![asentaa](images/installing.png)

+ Kun Raspbian on asennettu, valitse **OK** ja Raspberry Pi käynnistyy uudelleen ja Raspbian käynnistyy.

![asennettu](images/installed.png)