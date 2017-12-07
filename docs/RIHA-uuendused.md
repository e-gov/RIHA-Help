---
title: Mis on RIHAs uut?
---

## 7. detsember 2017 

### Infosüsteemide seosed

Infosüsteemide vahel on võimalik seoseid lisada, et tuua välja infosüsteemi ülem- ja alamsüsteemid. Funktsionaalsus võimaldab lisada seose näiteks andmekogu ning selle teenuseid vahendava X-tee alamsüsteemi vahel.
Seose lisamisel tekib infosüsteemidele link, millele vajutades saab otse vastava infosüsteemi detailvaatesse liikuda. Seose eemaldamisel kaob see link mõlema infosüsteemi kirjeldusest.

  ![Infosüsteemide seostamine](assets/images/data/relations.gif "Infosüsteemide seostamine")

Enne 1. novembrit olnud infosüsteemide seosed on samuti vanast RIHAst uude üle kantud - neid käsitsi lisada pole vaja.

### Märksõnade alusel otsimine

Lisandunud on otsingu sooritamine märksõna alusel, mis võimaldab kiirelt üles leida näiteks kõik X-tee alamsüsteemid sisestades otsingusõnaks 'X-tee alamsüsteem'

Lisaks on võimalik infosüsteemide detailvaates ka märksõnale klikkida, mille järel sooritatakse RIHA kataloogist vastava märksõnaga otsing.

  ![Märksõna otsimine](assets/images/data/tag-search.gif "Märksõna alusel otsimine")

### Otsingu parameetrid on nähtavad URLis

Otsingu parameetrid on nüüd nähtavad ka URLis, mis võimaldab otsingut jagada näiteks enda kolleegiga, kes saab lingile liikudes sooritada kiirelt sama otsingu.

### Infosüsteemile hinnangu küsimine

Kui infosüsteemi omanik on kirjeldamise lõpetanud ning soovib sellele saada kooskõlastust, siis saab ta seda hindajate tagasiside plokis teha. Kasutajal on võimalik valida, millises infosüsteemi etapis kooskõlastust on vaja ning arutelu salvestamisel jõuab vastav soov kõigi RIHA hindajate postkasti.

![Tagasiside küsimine](assets/images/data/submit-for-review.gif "Hindajatelt tagasiside küsimine")

Kooskõlastamise algatamise arutelusid saavad sulgeda ainult Riigi Infosüsteemi Ameti hindajad. Täpsem info kooskõlastamiste ja RIHA arutelude kohta leiab [RIHA hindamise abiinfost](RIHAs-hindamine).


### E-maili teavitused uutest aruteludest ja kommentaaridest

Kui infosüsteemile lisatakse hindajate tagasiside plokki uus arutelu, siis saadetakse kõigile infosüsteemi RIHAs olevatele kontaktidele selle kohta teavitus.
Kui ühtegi kontakti pole infosüsteemile lisatud, siis teavitusi välja ei saadeta.

Kui infosüsteemi omanik küsib RIHA hindajatelt tagasisidet, siis saadetakse kõigile RIHA hindajatele selle kohta teavitus.

Kui arutelu alla lisatakse uusi kommentaare, siis saavad kõik arutelus osalejad (sh arutelu algataja) selle kohta teavituse.

### Sessiooni lõppemise teavitus

Kui kasutaja on hoidnud pikalt RIHA lehekülge lahti ilma selles toiminguid sooritamata, siis teavitatakse kasutajat 5 minutit enne sessiooni lõppu. Kuni sessiooni lõppemiseni on võimalik kasutajal valida, kas soovib RIHA kasutamist autenditult jätkata või mitte. Jätkamisel pikendatakse kasutaja sessiooni. Loobumisel logitakse kasutaja süsteemist välja.

Kui sessioon juba on lõppenud, siis logitakse kasutaja süsteemist automaatselt välja ning näidatakse ka sellekohast teavitust.


## 1. november 2017

Toimus uue RIHA keskkonna avaldamine. [Vaata ka RIHA infopäeva video ülekannet](https://www.youtube.com/watch?v=K9lLS-7hpGw).

Uue RIHA peamised erinevused vanast RIHAst on välja toodud [uue RIHA muutuste abiinfos](uus-riha).

Vanast RIHAs kanti üle sellised infosüsteemid, mis oli **sisestamisel, asutatud või kasutusel staatusega**. Juurdepääsupiiranguga infosüsteemide puhul kanti üle vaid avalik teave. Infosüsteemide andmetest viidi üle võimalikult palju infot ning osaliselt toimus ka konverteerimine nende uuele tähendusele. Üle viidi järgmised infosüsteemide andmed:

- Nimi
- Lühinimi
- Staatus
  - kasutusele võtmise kuupäev
    - **kui infosüsteemi kasutusele võtmise aeg oli vanas RIHAs täidetud, siis viidi see üle 'kasutusel' staatusega olenemata läbitud/läbimata kooskõlastustest**
- **Vastutav töötleja -> omanik**
  - registrikood
  - nimi
- Infosüsteemi eesmärk
- Infosüsteemi URL -> avalik kasutajaliides
- X-tee liidestumise staatus (vastavalt vana RIHA kategooriale 'liidestatud/liidestatakse x-teega')
  - liidestumise kuupäev
- Infosüsteemi RIHA kirje tekitamise aeg
- Infosüsteemi viimase muudatuse aeg
- **Viimase ebaõnnestunud kooskõlastusringi mittekooskõlastamise otsused ja kommentaarid -> Hindajate tagasiside**
- Andmekoosseisu jaotisesse **üles laaditud** juurdepääsupiiranguta **andmeobjektide fail**
  -  käsitsi tehtud andmekoosseisu muudatused uues RIHAs ei kajastu
- Tehnilise dokumentatsiooni jaotises olevad juurdepääsupiiranguta failid ja veebiviited
- Infosüsteemi alusdokumendid -> Õigusaktid
  - Õigusaktide nimetused
  - URLid
- Infosüsteemi kontaktid, kellele oli lisatud email