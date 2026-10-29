# Veriyö Live · Ubuntu

Ubuntu-ohjeet [Veriyö Live -sovellukseen](https://github.com/Jakke77/Veriyo-Live).
Varsinainen ohjelma, lähdekoodi ja Ubuntu- sekä Windows-paketit ovat samassa
päärepossa. Tämä repo kokoaa Ubuntu-käytön ohjeet ja linkit.

## Asennus

Lataa päärepon [uusimmasta julkaisusta](https://github.com/Jakke77/Veriyo-Live/releases/latest)
`veriyo-live_…_all.deb` ja asenna se Ubuntun paketinasentimella tai päätteessä:

```bash
sudo apt install ./veriyo-live_0.4.2_all.deb
```

Sovellus löytyy nimellä **Veriyö Live**. Taustan vaihtaminen tarvitsee kirjautuneen
Ubuntu GNOME -istunnon. Komento: `veriyo-live`.

## Maisemat ja taivasteemat

Versio 0.4.2 korjaa GNOMEn taustojen sekoittumisen ja sisältää kolme maisemaa sekä neljä taivasteemaa:

- **Metsien puro:** virtaavaa vettä, sumua ja liikkuvaa kasvillisuutta.
- **Varjoruusujen puutarha:** goottilainen kasvihuone, ruusuja ja leijuvia terälehtiä.
- **Viimeinen majakka:** kiertävä valokeila, vieras meri, rengasplaneetta ja kaukainen varjo.

- **Pohjantähden tähtitaivas:** kirkkaat tähdet sijainnin ja oikean ajan mukaan.
- **Kuun kulkureitti:** oikea kuunvaihe, päivän reitti ja arvioidut nousu- ja laskuajat.
- **Veri Ajan taivaankoneisto:** seitsemän kehää ja 777 päivän vuoden mukaan muuttuva hehku.
- **Hiljainen avaruus:** kuvitteellinen planeetta, leijuvia kappaleita ja liikkuvaa sumua.

Ne sisältyvät sovellukseen ja toimivat ilman lisäpakettia tai verkkoyhteyttä.
GNOME näyttää koristeellisen liikkeen omilla taustakuvasiirtymillään. Tähtien ja
Kuun tiedot päivittyvät valitulla aikavälillä. Lukituskuva on pysäytyskuva.

Pohjantähden tähtitaivas ja Kuun kulkureitti katsovat pohjoiseen: zeniitti on
ylhäällä, länsi vasemmalla ja itä oikealla. Koko taivas ei mahdu tähän näkymään;
näkymän ulkopuolella olevasta Kuusta kerrotaan erikseen. Kuunvaihe ja nousu-
ja laskuajat näkyvät edelleen.

Maisemien aamu-, päivä-, ilta- ja yövalaistus seuraavat valitun aikavyöhykkeen
paikallista kellonaikaa. GNOME virkistää valaistuksen valitulla aikavälillä;
1 minuutti antaa tiheimmän päivityksen. **Nopeutettu esikatselu** näyttää
vuorokauden minuutissa muuttamatta työpöydän aikaa.

## GNOMEn taustojen sekoittumisen korjaus (0.4.2)

Vanha versio saattoi sekoittaa eri teemojen kuvia samassa animaatiossa, vaikka
satunnaisvaihdon väliksi oli valittu 26 minuuttia. Uusi versio tekee jokaisen
kuvasarjan omiin tiedostoihinsa, jotta GNOMEn välimuisti ei palauta edellisen
teeman kuvia. Nykyinen ja edellinen sarja säilyvät; vanhemmat siivotaan vasta
onnistuneen vaihdon jälkeen.

Sulje vanha ohjelma ilmoitusalueen **Lopeta**-valinnalla, asenna uusi DEB ja
paina **Ota elävä tausta käyttöön**. Nykyiset asetukset, valitut taustat ja
asennettu Ubuntu-kuvapaketti säilyvät. Satunnaisvaihdon aikaväli määrää teeman
vaihdon; saman teeman tietojen päivitys ei arvo uutta taustaa.

## Satunnaisvaihto

**Vaihda satunnainen tausta nyt** vaihtaa käynnissä olevan taustan tai valitsee
pysäytettynä esikatselun. **Valitse mukaan tulevat taustat…** avaa rastitettavan
luettelon, jossa voit rajata arvonnan omiin suosikkeihin. Ubuntu-versiot tarvitsevat
asennetun kuvapaketin. Nykyistä taustaa ei arvota heti uudelleen.

**Vaihda taustaa satunnaisesti** vaihtaa taustaa 1, 5, 15, 26 tai 60 minuutin välein,
kun tausta on otettu käyttöön. Valitse vähintään kaksi käytettävissä olevaa taustaa,
jos haluat jatkuvaa vaihtelua. Pysäytys pysäyttää myös satunnaisvaihdon; palautus
säilyttää alkuperäisen taustan useiden vaihtojen jälkeenkin.

## Ubuntun oletustaustakuvakokoelma

45 Ubuntu-version oletustaustaa vuosilta 4.10–26.10 esitellään
**taustakuvakokoelmana**. Niihin ei luvata havaittavaa animaatiota.

Lataa päärepon julkaisuista **Ubuntu-Live-Pack-1.0.0.zip**, valitse sovelluksessa
**Ubuntun oletustaustat → Asenna Ubuntu-kuvat…**, valitse ZIP ja sitten
**Ubuntu-versio → Ota taustakuva käyttöön**. Tiedoston vanha nimi säilyy
yhteensopivuuden vuoksi. Jo asennettua kuvapakettia ei tarvitse asentaa uudelleen.

Kuvien alkuperäiset tekijä- ja lisenssitiedot sisältyvät kuvapakettiin.
Ubuntu ja sen tavaramerkit kuuluvat Canonicalille.

[Käyttöohjeet ja rajat](https://github.com/Jakke77/Veriyo-Live#readme) ·
[Julkaisut](https://github.com/Jakke77/Veriyo-Live/releases)
