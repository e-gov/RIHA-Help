---
title: Muutused uues RIHAs
---

## Mida saab uues RIHAs teha?

Uues RIHAs saavad:
- kõik kasutajad infosüsteeme otsida ja vaadata
- infosüsteemi omanikud oma infosüsteeme kirjeldada (sh X-tee alamsüsteeme registreerida), muuta ning kooskõlastajatega suhelda
- kooskõlastajad infosüsteemidele tagasisidet anda

## Mis on uues RIHAs erinev kui vanas RIHAs?

### Infosüsteemi staatus

Infosüsteemide staatused ei kajastanud vanas RIHAs väga tihti infosüsteemi reaalset olekut: oli infosüsteeme, mis olid mitmeid aastaid kasutusel, kuid vana RIHA näitas staatust, milleni RIHAs infosüsteemiga jõutud oli, näiteks 'asutamine kooskõlastatud'. See ei kuvanud riigi infosüsteemist adekvaatset pilti.

- Uues RIHAs määrab kasutaja ise enda infosüsteemi reaalse oleku. Selleks on uues RIHAs kaks staatust: 'Süsteemi staatus' ja 'Arenduse staatus'. 
- Süsteemi staatused on asutamisel, kasutusel ja lõpetatud. See näitab süsteemi reaalset olekut ning on kasutaja poolt kergesti muudetav.
- Arendamise staatus on määratav jah/ei vormis: kas infosüsteem on aktiivses arenduses või infosüsteem ei ole arenduses. Staatus "aktiivses arenduses" väljendab seda, et infosüsteemi arendatakse aktiivselt ning lähitulevikus on oodata muudatusi ka RIHA kirjelduses (näiteks andmetes või tehnilises dokumentatsioonis).

![Infosüsteemi staatused](assets/images/data/staatused.png "Infosüsteemi staatused uues RIHAs")

### Kooskõlastamine

- Uues RIHAs on kooskõlastamise asemel välja toodud vastupidine: infosüsteemide puudused, mis avanevad kohe **hindajate tagasiside** avatud arutelude vaates
- Kui infosüsteemil on puudusi, siis annavad kooskõlastajad sellest infosüsteemi juures teada, lisades uue arutelu, milles kirjeldatud puudused tuleb infosüsteemi omanikul kõrvaldada
- Kooskõlastamiseks esitamine toimub uue arutelu lisamisega, mille alla on võimalik kooskõlastajatel positiivseid otsuseid anda. Lähemalt loe [RIHAs hindamise abiinfost](https://abi.riha.ee/RIHAs-hindamine)

![Hindajate tagasiside](assets/images/data/hindajate-tagasiside.png "Hindajate tagasiside uues RIHAs")

- Aktiivsete arutelude kõrval on võimalik vaadata ka suletud arutelusid, mis näitavad, millised infosüsteemi puudused on aja jooksul lahendatud

### Andmete koosseis

- Uues RIHAs on andmekoosseisu kirjeldamine tehtud vähem aeganõudvaks
- Käsitsi on infosüsteemi omanikul vaja kirjeldada kuni 10 objektiga, milliseid põhiandmeid infosüsteem sisaldab. See on kui äriline vaade, mis annab infosüsteemi uurivale kasutajale kohe ülevaate, millist infot infosüsteemis hoitakse.

![Infosüsteemi andmete äriline vaade](assets/images/data/andmed-ylevaade.png "Infosüsteemi andmete äriline vaade")

- Lisaks ärilisele vaatele tuleb üles laadida infosüsteemi detailne andmete koosseis. See dokument on vaja esitada kas .csv või .xmi failina.
  - Faili struktuuri RIHA rakendus rangelt ei kontrolli, kuid sisaldama peaks see infot, millised andmed on põhiandmed, millised on tehnilised andmeväljad ning millised andmed küsitakse teistest infosüsteemidest
  - Üles laaditava dokumendi puhul soovitame kasutada struktuuri, mida olete ka vanas RIHAs andmekoosseisu üleslaadimisel kasutanud


## Mida ei ole enam RIHAs võimalik teha?

### Klassifikaatorid

Uues RIHAs puudub klassifikaatorite moodul. Kõik senised klassifikaatorid võib leida [vanast RIHAst](https://vana.riha.ee), sealsamas saab ka lisada, muuta ja kooskõlastada klassifikaatoreid. Uues RIHAs tuleb infosüsteemi omanikul lisada kasutatavad klassifikaatorid vastava infosüsteemi dokumentatsiooni plokis viidetena vanas RIHAs kirjeldatud klassifikaatoritele (nt [Kasutatav klassifikaator: EHAK2018v2](https://vana.riha.ee/riha/main/kla/eesti_haldus-_ja_asustusjaotuse_klassifikaator_2018v1_ver20)). RIA kaardistab koos Statistikaametiga klassifikaatorite haldamise klienditeekonda ning ühtlasi tuleb üle vaadata kõik seni Statistikaameti poolt kooskõlastatud klassifikaatorid (st eristada klassifikaatorid loenditest).

### Sõnastikud

8 aastaga on registreeritud ainult 16 sõnastikku ja kirjeldatud 1105 terminit (võrdluseks, et RIHAs on kirjeldatud ligikaudu 85 000 andmeobjekti). Uues RIHAs sõnastikke ei ole, kuna sõnastike loomiseks ja kasutamiseks pole avalikus sektoris olnud piisavat motivatsiooni ja ressurssi. Seetõttu ei ole võimalik valdkondade sõnastikke:
  - vaadata
  - üles laadida
  - andmekoosseisuga siduda
  
Küll aga on võimalik piiratud aja jooksul tutvuda seniste sõnastike ja terminitega vanas RIHAs.

### X-tee teenused

- Uues RIHAs on ainult infosüsteemide ning X-tee alamsüsteemide kirjed, täpsemat infot X-tee teenuste kohta uues RIHAs ei ole
- Teenuseid otsida ning nende WSDL-e vaadata RIHA vahendusel ei saa
- Teenuste kirjeldusi inimloetaval kujul on võimalik lisada infosüsteemi dokumentatsiooni plokki

X-tee alamsüsteemide kataloog teenuste ja WSDL kirjeldustega asub aadressil [https://www.x-tee.ee/catalogue/EE](https://www.x-tee.ee/catalogue/EE). Kataloog on genereeritud metapäringute _getWsdl_ tulemustest RIA monitooringu turvaserveri poolt kõigist X-tee alamsüsteemidest, kuvatakse X-tee toodangu-, test- ja arenduskeskkonna (EE, ee-test, ee-dev) andmeid.

### X-tee sertifikaatide taotlemine

Kuna X-tee versioonis 6 ei väljasta sertifikaate RIA, vaid vastav sertifitseerimisteenuse osutaja, siis ei ole ka uues RIHAs sertifikaatide taotlemise funktsionaalsust realiseeritud.

### X-tee teenuse avamise taotlemine

- Et RIHAs puuduvad X-tee teenused, siis ei ole RIHAs ka funktsionaalsust, et esitada avaldust teenuste kasutamiseks
- Teenuse kasutamise lepivad kokku osapooled omavahel valides selleks kanaliks näiteks e-posti või muu klienditeeninduskanali
