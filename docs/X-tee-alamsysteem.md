---
title: X-tee alamsüsteemi abi
---

## Kuidas muuta X-tee alamsüsteemi andmeid RIHAs?

### Eeltegevused

- Mine [RIHA avalehele](https://www.riha.ee/) ja vajuta "Logi sisse"
- Kontrolli paremalt ülalt, mis rollis oled. Valitud peaks olema asutus, mille alla soovid alamsüsteemi registreerida. Vajadusel vaheta enda rolli, vajutades üleval paremas nurgas enda nime peale.
  - kui sinuga pole seotud ühtegi asutust, vaata juhendit [siit](/RIHA-oigused-haldamine) 

### Uue alamsüsteemi kirjeldamine
*X-tee toodangukeskkonna alamsüsteem tuleb RIHAs registreerida enne registreerimistaotluse esitamist turvaserveris.*

- Vajuta avalehel X-teega liitumise kastis [Alustan](https://www.riha.ee/Kirjelda/Uus)
- Lisa uue alamsüsteemi andmed
  - Nimi – Mis alamsüsteemiga on tegu? (nimes võiks sisalduda „X-tee alamsüsteem“)
  - Lühinimi – kujul *asutuse registrikood – nimetus*. Lühinimi võib sisaldada ainult ladina tähti (mitte täpitähti), numbreid, punkti ja miinusmärki; näiteks *12345678-panesiiamidagi*. Lühinime nimetuse osas soovitame väljendada alamsüsteemi eesmärki: näiteks lühinimi *12345678-klient* märgiks asutuse poolt teiste infosüsteemide teenuste tarbimiseks loodavat alamsüsteemi. Soovitame ka vältida tarkvara-spetsiifilisi nimetusi.
**Juhime tähelepanu**, et lühinimega seotakse hilisem X-tee andmeteenuste kasutus, selle muutmine pärast kasutuselevõttu võib need seosed lõhkuda.
  - Infosüsteemi eesmärk – Miks alamsüsteem luuakse? Kes majutab turvaserverit? Milliste infosüsteemidega on alamsüsteem seotud?
  - Salvesta ja **täienda kirjeldust**

### X-tee alamsüsteemi kirjelduse täiendamine

- Infosüsteemi märksõnade lahtrisse kirjuta *X-tee alamsüsteem*
  - [Andmeteenuseid vahendava alamsüsteemi](https://moodle.ria.ee/mod/page/view.php?id=382) korral kirjuta märksõnade väljale lisaks *Andmeteenuste vahendamine* ja lisa dokumentatsiooni plokki **andmeteenuste vahendamise kord** ([loe, mida kord peab sisaldama](https://www.riigiteataja.ee/akt/127092016004?leiaKehtiv#para13lg2))
- Vali dokumentatsiooni ploki ülaosast MUUDA ning vajadusel lisa viited tehnilisele dokumentatsioonile
  - Eraõiguslik X-tee liige, kelle infosüsteem ei ole avaliku teabe seaduse tähenduses andmekogu ja kelle infosüsteemi ei kasutata avaliku teenuse osutamiseks, peab dokumentatsiooni plokki lisama ettevõtte esindusõigusliku isiku digitaalselt allkirjastatud [nõuetele vastavuse kinnituse](https://github.com/e-gov/RIHA-Help/raw/master/docs/xtee_nouetele_vastavus_kinnitus.pdf). Volitatud esindusõiguse puhul lisa DigiDoc konteinerisse enne allkirjastamist ka volikiri või lisa volikiri eraldi failina.
  - Lisa dokument manusena > vali faili liik _Nõuetele vastavuse kinnitus_ > LISA > SALVESTA
- Vali kontaktide ploki ülaosast MUUDA ning lisa kontaktisikud: alamsüsteemi toimimise eest vastutav füüsiline isik ja alamsüsteemi teenindava turvaserveri administraatori kontaktandmed
  - Kirjuta nimi ja meiliaadress (mõlemad kohustuslikud) > LISA > SALVESTA
  - _Kontaktisikuid näevad vaid sisselogitud kasutajad_
  - _Kontaktisikutele saadetakse iga kuu alamsüsteemi kasutusraport, mis näitab kes ja kui palju alamsüsteemi on kasutanud ning kas ja kui palju alamsüsteemist päringuid teistesse alamsüsteemidesse välja läheb (rohkem infot leiab [raportite lugemisjuhendist](https://github.com/ria-ee/X-Road-opmonitor/blob/master/docs/user_guide/ug_reports_et.md))._
- **X-tee alamsüsteem on RIHAs registreeritud**, kui tema staatuseks on märgitud *Kasutusel* ja märksõna väljal on *X-tee alamsüsteem* ja/või *Andmeteenuste vahendamine*

Alamsüsteemi kirjelduse korrektsust RIHAs (ja andmeteenuste vahendamisel ka andmeteenuste vahendamise korra vastavust nõuetele)  kontrollib X-tee keskus pärast seda, kui oled ka turvaserveri liidesest esitanud selle sama alamsüsteemi X-teel registreerimise taotluse. [Loe X-tee rakendusjuhise peatükist 4.2, kuidas seda teha](https://moodle.ria.ee/mod/page/view.php?id=288). **X-tee keskus ei registreeri sellist alamsüsteemi, mida pole RIHAs või mille kirjeldus pole RIHAs täielik.**

Kui X-tee keskus tuvastab RIHAs alamsüsteemi kirjelduses puuduse, siis algatab ta RIHAs arutelu (alamsüsteemile märgitud kontaktisikut teavitatakse e-kirjaga), milles kirjeldab leitud puudused ja selgitab kuidas neid kõrvaldada (kirjeldust muuta saab organisatsiooni RIHA kirjeldaja). Turvaserveri liidesest esitatud alamsüsteemi registreerimise taotlus rahuldatakse pärast seda, kui alamsüsteemi omanik on kõrvaldanud arutelus kirjeldatud puudused.

### X-tee alamsüsteemide haldamine

- Kõik sinu asutuse poolt registreeritud alamsüsteemid ja infosüsteemid leiad [Minu infosüsteemide](https://www.riha.ee/Kirjelda) nimekirjast
