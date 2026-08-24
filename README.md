# GitHub õpikeskkond rakendusinformaatika õppekaval

## Sissejuhatus

Tere tulemast rakendusinformaatika õppekavale!

Praktilistes ainetes kasutame peamise õpikeskkonnana GitHubi. Kuigi GitHub on maailmas tuntud eelkõige tarkvaraarendajate versioonihalduse platvormina, on meie õppekaval sellest kujunenud terviklik õppekeskkond, kus toimub suur osa igapäevasest õppetegevusest.

GitHubis:

- avaldatakse ülesandeid;
- arendatakse lahendusi;
- tehakse meeskonnatööd;
- antakse ja saadakse tagasisidet;
- dokumenteeritakse kogu tööprotsess;
- kujuneb sinu professionaalne portfoolio.

Meie eesmärk ei ole õpetada ainult programmeerimist. Sama oluline on õppida kasutama töövõtteid ja tööriistu, mida kasutatakse igapäevaselt tarkvaraarendusettevõtetes.

---

## GitHubi ökosüsteem

Meie GitHubi keskkond koosneb kolmest organisatsiooni tüübist. Igal neist on oma kindel eesmärk ning koos moodustavad need tervikliku õpikeskkonna.

```text
                   Tallinna Ülikool
                          │
             Instituudi GitHub organisatsioon
                          │
        ┌─────────────────┴─────────────────┐
        │                                   │
 Õppekava organisatsioon              Õppekava organisatsioon
      (RIF26)                              (RIF27)
        │
   ┌────┴──────────────────────────────┐
   │                                   │
Sinu organisatsioon         Kaasüliõpilase organisatsioon
```

---

## 1. Instituudi organisatsioon

Instituudi organisatsioon on kogu õppekava ühine keskkond.

Siin paiknevad näiteks:

- õppematerjalid;
- juhendid;
- näidisprojektid;
- ühised tööriistad;
- avalikud projektid.

Instituudi organisatsioon on koht, kust algab enamik õppetööst. Siit leiad vajalikud materjalid ning juhendid, mida erinevates ainetes kasutatakse.

Seda võib võrrelda ülikooli digitaalse raamatukogu ja tööriistakoguga.

---

## 2. Õppekava organisatsioon

Igal lennul on oma GitHubi organisatsioon.

Näiteks:

**RIF26**

See organisatsioon ei ole mõeldud õppematerjalide hoidmiseks.

Selle peamine eesmärk on toetada kogu lennu ühist tegevust.

Õppekava organisatsioonis asuvad näiteks:

- üliõpilaste nimekiri koos viidetega nende isiklikele organisatsioonidele;
- grupiprojektid;
- ühised arendusprojektid;
- koostööülesanded;
- erinevad katsed ja pilootprojektid, mis puudutavad kogu õppekava või suuremat üliõpilaste rühma.

Lihtsamalt öeldes on see koht, kus kohtuvad kõik ühe lennu üliõpilased ning kus toimub nende ühine praktiline tegevus.

---

## 3. Isiklik organisatsioon

Õpingute alguses saab iga üliõpilane oma GitHubi organisatsiooni.

See on sinu isiklik tööruum ning kõige olulisem osa kogu õppekeskkonnast.

Sinu organisatsioonis paiknevad:

- isiklikud aineprojektid;
- kodused tööd;
- praktilised harjutused;
- katsetused;
- isiklik portfoolio.

Erinevalt tavalisest GitHubi kasutamisest ei tööta sa üksikutes juhuslikes hoidlatest, vaid haldad omaenda organisatsiooni.

See tähendab, et õpid lisaks programmeerimisele ka:

- hoidlate haldamist;
- projektide organiseerimist;
- õiguste haldamist;
- professionaalset töökorraldust.

Sinu organisatsioon jääb sulle alles ka pärast õpinguid ning sellest võib kujuneda oluline osa sinu professionaalsest portfooliost.

---

## Kes omab mida?

Kuigi kõik kolm organisatsiooni asuvad GitHubis, on neil erinevad omanikud ja erinevad eesmärgid.

| Organisatsioon            | Omanik           | Milleks kasutatakse?                                                                  |
| ------------------------- | ---------------- | ------------------------------------------------------------------------------------- |
| Instituudi organisatsioon | Tallinna Ülikool | Õppematerjalid, juhendid, näidisprojektid, ühised tööriistad                          |
| Õppekava organisatsioon   | Tallinna Ülikool | Üliõpilaste nimekiri, grupiprojektid, koostööprojektid ja kogu õppekava ühine tegevus |
| Isiklik organisatsioon    | Üliõpilane       | Isiklikud projektid, kodutööd, praktilised ülesanded ja portfoolio                    |

Selline ülesehitus võimaldab selgelt eristada, millised ressursid kuuluvad ülikoolile ning millised on sinu enda hallata.

---

## Kuidas ülesanded tavapäraselt liiguvad?

Enamik õppeaineid, mis kasutavad GitHubi, kasutavad seda ka koduste ülesannete andmisel ja lahenduste esitamisel. Tavaline töövoog on järgmine:

```text
Õppejõud avaldab ülesande
           │
           ▼
Õpilase organisatsiooni luuakse vastava hoidla alla GitHub Issue
           │
           ▼
Lood lahenduse jaoks uue haru (Branch)
           │
           ▼
Arendad lahendust
           │
           ▼
Teed Commit'id
           │
           ▼
Avad Pull Request'i
           │
           ▼
Lisad õpeataja ülevaatajaks
           │
           ▼
Saad tagasisidet
           │
           ▼
Teed parandused (kui vajalik)
           │
           ▼
Õpetaja kinnitab lahenduse, liites Pull Request'i põhiharuga (Merge)

```

Sellist töövoogu kasutatakse väga paljudes tarkvaraarendusettevõtetes üle maailma. Õpingute jooksul harjud sellega loomulikul viisil ning omandad töövõtted, mida saad hiljem kasutada ka tööelus.

Samas ei ole see ainukene kasutatav töövoog. Sageli kasutame ka lihtsalt GitHub-i Issue-sse lisatavat kommentaari koduse ülesande lahendusena. Näiteks võib koduse ülesande lahenduseks olla arvamus või kirjeldus, mille lisad Issue kommentaarina. Sellisel juhul ei ole vaja luua eraldi haru ega Pull Request'i.

Sellest, kuidas koduste ülesannete lahendusi tavaliselt esitatakse, räägime eraldi koduseid ülesandeid andes ja kirjeldus on tavaliselt ka kirjas koduses ülesandes endas.

Siin tuleb muidugi meeles pidada ka seda, et kõik õpetajad/õppejõud ei kasuta GitHub-i oma õppeainetes.

---

## GitHub Projects

Kodused ülesanded, mis tulevad läbi GitHubi, lisatakse automaatselt ka teie individuaalse organisatsiooniga seotud GitHub Project tahvlile. See võimaldab sul jälgida kõiki oma koduseid ülesandeid ühes kohas.

---

## Miks me kasutame GitHubi?

GitHub võimaldab õppida palju enamat kui ainult koodi haldamist.

Õpingute jooksul õpid:

- kasutama versioonihaldust;
- planeerima ja dokumenteerima oma tööd;
- tegema koostööd teiste arendajatega;
- lahendama konflikte ja ühendama muudatusi;
- vastu võtma ning andma konstruktiivset tagasisidet;
- looma professionaalset arendusportfooliot.

Need oskused on tänapäeva tarkvaraarenduses sama olulised kui programmeerimisoskus.

---

## Mida saad õpingute lõpuks?

Õpingute lõpus ei ole sul ainult läbitud ained.

Sul on olemas ka:

- professionaalselt korraldatud GitHubi organisatsioon;
- kümned tarkvaraprojektid;
- sadade või isegi tuhandete commit'ide ajalugu;
- pull request'id ja koodiülevaated;
- kogemus meeskonnatöös;
- professionaalne portfoolio, mida saad näidata tööandjale.

Meie eesmärk on, et õpingute jooksul kujuneks GitHub sinu igapäevaseks töövahendiks ning samal ajal kasvaks sellest välja usaldusväärne ülevaade sinu teadmistest, oskustest ja arengust.

---

## Discord

Lisaks GitHubile kasutame õppeprotsessi toetamiseks ka Discordi. Discord on suhtlusplatvorm, kus toimub igapäevane suhtlus, küsimuste esitamine ja vastuste saamine. Samuti on Discord integreeritud meie GitHubi õpikeskkonnaga, mis annab meile erinevaid võimalus. Näiteks saad Discordi kaudu teavitusi oma tegemata koduste ülesannete kohta, nende staatuste muutusest (esitatud, vastu võetud jne) ning ka muudest olulistest teadetest.
