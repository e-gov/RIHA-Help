---
title: Muutused uues RIHAs
---

## Mida ei ole enam RIHAs võimalik teha?

### Kooskõlastamiseks esitamine

- Uues RIHAs ei toimu pärast infosüsteemi kirjeldamist selle kooskõlastamiseks esitamine. Kõik kooskõlastajad saavad automaatselt iga päev teavitusi uutest infosüsteemidest ning vaatavad kirjeldusi üle.
- Kui infosüsteemil on puudusi, siis annavad kooskõlastajad sellest infosüsteemi juures teada lisades uue arutelu, milles kirjeldatud puudused tuleb infosüsteemi omanikul kõrvaldada
- Arutelusid saab tekitada igal ajahetkel, ka siis kui infosüsteem on juba ammu kasutusele võetud

### Klassifikaatorid

- Uues RIHAs ei ole klassifikaatoreid ning seetõttu puudub ka koht, kus klassifikaator infosüsteemiga siduda

### Sõnastikud

- Uues RIHAs sõnastikke ei ole, ning seetõttu ei ole võimalik valdkondade sõnastikke
  - vaadata
  - üles laadida
  - andmekoosseisuga siduda

### X-tee teenused

- Uues RIHAs on ainult infosüsteemide ning X-tee alamsüsteemide kirjed, täpsemat infot X-tee teenuste kohta uus RIHAs ei ole
- Teenuseid otsida ning nende WSDL-e vaadata RIHA vahendusel ei saa
- Teenuste kirjeldusi inimloetaval kujul on võimalik lisada infosüsteemi dokumentatsiooni alla

X-tee alamsüsteemide teenuste ning WSDL-ide kuvamiseks tekitatakse X-tee kataloog, mis hakkab kuvama andmeid automatiseeritult. Nii ei ole vaja kasutajatel eraldi teenuste WSDL-e RIHAsse kirja panna või neid üles loetleda.

### X-tee sertifikaatide taotlemine

- X-tee versioon 6-s ei väljasta sertifikaate RIA ning seetõttu ei ole ka uues RIHAs sertifikaatide taotlemise funktsionaalsust

### X-tee teenuse avamise taotlemine

- Et RIHAs puuduvad X-tee teenused, siis ei ole RIHAs ka funktsionaalsust, et esitada avaldus teenuste kasutamiseks
- Teenuse kasutamise lepivad kokku osapooled omavahel valides selleks kanaliks näiteks e-posti või muu klienditeeninduskanali


## Mis on uues RIHAs erinev kui vanas RIHAs?

### Infosüsteemi staatus

Infosüsteemide staatused ei kajastanud vanas RIHAs väga tihti infosüsteemi reaalset olekut: oli infosüsteeme, mis olid mitmeid aastaid kasutusel, kuid vana RIHA näitas staatust, kuhuni infosüsteemiga RIHAs jõutud oli, näiteks 'asutamine kooskõlastatud'. See ei kuvanud lõpuks riigi infosüsteemist adekvaatset pilti.

- Uues RIHAs määrab kasutaja ise enda infosüsteemi reaalse oleku. Selleks on uues RIHAs kaks staatust: 'Süsteemi staatus' ja 'Arenduse staatus'. 
- Süsteemi staatused on : asutamisel, kasutusel, lõpetatud. See näitab süsteemi reaalset olekut ning on kasutaja poolt kergesti muudetav.
- Arendamise staatus on määratav jah/ei vormis: kas infosüsteem on aktiivses arenduses või infosüsteem ei ole arenduses. Kui infosüsteemi arendatakse aktiivselt, siis on see staatus indikatsiooniks, et on lähitulevikus oodata muudatusi ka RIHA kirjelduses (näiteks andmetes või tehnilises dokumentatsioonis).

![Infosüsteemi staatused](assets/images/data/staatused.png "Infosüsteemi staatused uues RIHAs")

### Kooskõlastamine

- Uues RIHAs ei ole võimalust kooskõlastajatel anda hinnangut 'kooskõlastan'. Selle asemel on uues kontseptsioonis kasutusel vastupidine funktsionaalsus
- Kui infosüsteemil on puudusi, siis annavad kooskõlastjad sellest infosüsteemi juures teada lisades uue arutelu, milles kirjeldatud puudused tuleb infosüsteemi omanikul kõrvaldada

![Hindajate tagasiside](assets/images/data/hindajate-tagasiside.png "Hindajate tagasiside uues RIHAs")

- Hinnanguid saavad RIHA kooskõlastajad igal ajahetkel infosüsteemidele anda
- Iga infosüsteem on kooskõlas just nii kaua kuni ükski kooskõlastaja pole sellele aktiivset arutelu tekitanud
- Aktiivsete arutelude kõrval on võimalik vaadata ka suletud arutelusid, mis näitavad, millised puudused on aja jooksul infosüsteemi juures lahendatud

### Andmete koosseis

- Uues RIHAs on andmekoosseisu kirjeldamine tehtud vähem aeganõudvaks
- Käsitsi on infosüsteemi omanikul vaja kirjeldada kuni 10 objektina, milliseid põhiandmeid infosüsteem sisaldab. See on kui äriline vaade, mis annab infosüsteemi uurivale kasutajale kohe ülevaate, millist infot infosüsteemis hoitakse

![Infosüsteemi andmete äriline vaade](assets/images/data/andmed-ylevaade.png "Infosüsteemi andmete äriline vaade")

- Lisaks ärilisele vaatele on võimalik üles laadida infosüsteemi detailse koosseisu. See dokument on vaja esitada kas .csv või .xmi failina.   
  - Faili struktuuri RIHA rakendus rangelt ei kontrolli, kuid sisaldama peaks see infot, millised andmed on põhiandmed, millised on tehnilised andmeväljad ning millised andmed küsitakse teistest infosüsteemidest
  - Üles laaditava dokumendi puhul soovitame kasutada struktuuri, mida olete ka vanas RIHAs andmekoosseisu üleslaadimisel kasutanud