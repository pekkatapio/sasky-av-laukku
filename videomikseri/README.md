# video mixeri
käytetään kameran videosignaalin tietokoneeseen siirtoon.
konfiguroi [kamera](../kamera/README.md) ensin.

## vaatii
* SDI kaapelin
* Kameran
* virtajohdon 

### etuosa
<p align="center">
  <img src="front.jpg">
</p>

### takaosa
<p align="center">
  <img src="back.jpg">
</p>

## käyttö
1. Kiinnitä virtajohto laitteen takaosaan.
2. Kiinnnitä SDI johto takaosan `SDI in` porttiin. (halutessasi käytä HDMI johtoa, jolloin mixeristä valitaan kanava 2.)
3. Valitse kanava 1 laitteen etuosasta.
4. Kiinnitä USB johto takaosan `USB WEBCAM` porttiin.
5. Kiinnitä johdon toinen pää tietokoneeseen.
6. Valitse OBS ohjelmassa `sources` -> `video source` -> `blackmagic ...`

