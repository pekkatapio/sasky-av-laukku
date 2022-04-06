# Audiomikseri
Audiomikseriä käytetään mikrofoneista ja muista äänilähteistä tulevien äänien yhdistämiseen ja siirtämiseen tietokoneelle. 

Jos käytät [langatonta vastaanotinta](../vastaanotin/README.md), niin ota se käyttöön ensin.


## Mikserin käyttöön tarvitaan
* virtajohto
* mini USB-johto
* XLR-johdot [vastaanottimesta](../vastaanotin/README.md)


### audiomikseri päältä
<p align="center">
  <img src="top.svg">
</p>

### audiomikseri takaa
<p align="center">
  <img src="rear.png">
</p>

## Audiomikserin käyttö
1. Kytke virtajohto takana olevaan `AC POWER IN` -porttiin.
2. Kytke micro USB-johto takaosan porttiin ja johdon toinen pää tietokoneeseen.
3. Kytke XLR-johdot vasemman yläreunan `LINE IN` -portteihin.
4. Säädä mikserin säätimet lähtökohtaisesti arvoon 0 (osoitin osoittaa suoraan ylös, paitsi COMP-asetus kello 7).
5. Paina oikean alareunan `TO MAIN MIX` -painike ala-asentoon. Ääni siirtyy tietokoneelle, kun tämä nappi on alhaalla. 
6. Jos käytät kondensaattorimikrofoneja, jotka tarvitsevat Phantom-virtaa, niin paina punainen nappi alas. Langattomalla vastaaottimella ja heittomikrofonilla tätä ei tarvita, ne saavat virran omasta virtalähteestään.  
7. Säädä mikrofonien `GAIN`-asetuksia niin, että mikrofoni ottaa puheen selvästi, mutta ääni ei vielä säröydy. Testaa myös kovemmilla äänenvoimakkuuksilla.
8. Säädä alareunan `LEVEL`-asetuksilla kaikki mikserille tulevat äänilähteet keskenään balanssiin.
9. Säädä oikean alareunan `MAIN MIX`-asetuksella tietokoneelle tulevan äänitulon voimakkuutta. 

### Käyttö tietokoneella

 * Audiomikseri näkyy automaattisesti tietokoneella `USB Audio CODEC` -äänitulolaitteena.
 * OBS-ohjelmassa saat lisättyä mikserin seuraavasti:
    1. Valitse *Lähteet (sources)* -> *Lisää* -> *Äänitulo (Microphone input)*.
    2. Valitse *Luo uusi* ja anna nimeksi `audiomikseri`.
    3. Valitse *Laite*-kohtaan `Microphone (USB Audio CODEC)` ja paina *OK*.
    4. Audiomikseri toimii nyt yhtenä äänitulolaitteena OBS-ohjelmassa.
 * Teams-ohjelmassa valitse mikrofoniksi `USB Audio CODEC`. Huomaa, että Teams saattaa automaattisesti määritellä kaiuttimeksi audiomikserin, vaihda kaiutin-kohtaan käyttämäsi kaiutin. 

