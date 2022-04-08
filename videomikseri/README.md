# Videomikseri

Videomikseriä käytetään kameran videosignaalin siirtoon tietokoneelle.

Aseta ensin [kamera](../kamera/README.md) käyttökuntoon.

## Videomikserin käyttöön tarvitaan
* virtajohdo
* mini USB-johto
* SDI-kaapeli
* (kamera)

### videomikseri takaa
<p align="center">
  <img src="back.svg">
</p>

### videomikseri edestä
<p align="center">
  <img src="front.jpg">
</p>

## Videomikserin käyttö
1. Kiinnitä virtajohto laitteen takaosaan. <span style="color:red">❶</span>
2. Kiinnitä USB-johto takaosan `USB WEBCAM` -porttiin ja liitä johdon toinen pää tietokoneeseen.
3. Kiinnitä SDI-kaapeli takaosan `SDI IN` -porttiin. Halutessasi voit käyttää vaihtoehtoisesti HDMI-kaapelia, kytke kaapeli `HDMI IN` -porttiin.
4. Valitse kaapelia vastaava kanava laitteen etuosasta. SDI-kaapelilla valitse kanava 1 ja HDMI-kaapelilla kanava 2. 

### Käyttö tietokoneella
 * Videomikseri näkyy automaattisesti tietokoneella `BLACKMAGIC` -nimisenä web-kamerana.
 * OBS-ohjelmassa saat lisättyä videomikserin seuraavasti:
    1. Valitse *Lähteet (sources)* -> *Lisää* -> *??*.
    2. Valitse *Luo uusi* ja anna nimeksi `videomikseri`.
    3. Valitse *Laite*-kohtaan `????` ja paina *OK*.
    4. Videomikseri toimii web-kamerana OBS-ohjelmassa.
 * Teams-ohjelmassa valitse käytettäväksi web-kameraksi `sdfkjds`.

