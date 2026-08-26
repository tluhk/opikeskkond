# Git ja GitHubi parimad praktikad

Selles teemas õpime tundma parimaid praktikaid Git'i ja GitHubi kasutamiseks. Uurime Git'i ja GitHubi parimaid praktikaid ning õpime, kuidas neid tarkvaraarendusprojektis rakendada.

![Git-i parimad praktikad](Git-Best-Practices.webp)

Pildi allikas: Dall-E by OpenAI

- [Git ja GitHubi parimad praktikad](#git-ja-githubi-parimad-praktikad)
  - [Õpiväljundid](#õpiväljundid)
  - [Git'i parimad praktikad](#giti-parimad-praktikad)
  - [GitHubi parimad praktikad](#githubi-parimad-praktikad)

## Õpiväljundid

Pärast selle teema läbimist suudate:

- kirjeldada parimaid praktikaid Git'i ja GitHubi kasutamiseks;
- rakendada Git'i ja GitHubi parimaid praktikaid tarkvaraarendusprojektis.

_Git'i_ ja _GitHubi_ tõhus kasutamine hõlmab enamat kui ainult käskude ja tööriistade tundmist. Parimate praktikate järgimine tagab, et arendusprotsess on sujuv, projekti ajalugu jääb puhtaks ja meeskonnaliikmete koostöö on tõhus.

Siin on ülevaade parimatest praktikatest nii Git'i kui ka GitHubi jaoks:

## Git'i parimad praktikad

1. **`commit`-i tihti, tõuka harvem:**
   - Tee sagedasi, väiksemaid `commit`-e, mis hõlmavad ühte loogilist muudatust (nt vea parandamine või funktsiooni lisamine). See muudab ajaloo mõistmise ja probleemide isoleerimise lihtsamaks.
2. **Kirjuta tähendusrikkaid `commit`-i sõnumeid:**
   - Alusta lühikese, kirjeldava pealkirjaga. Kui on vaja rohkem detaile, lisa põhjalik kirjeldus eraldi `Description` osas. See aitab teistel arendajatel mõista, miks muudatus tehti ja kuidas see mõjutab koodibaasi
3. **Kasuta harusid:**
   - Ära tööta ilma vajaduseta otse `main` haruga. Kasuta iga uue funktsiooni, veaparanduse või kodutöö lahenduse jaoks eraldi haru, kui ülesanne nõuab muudatuste esitamist Pull Request'i kaudu. Vanemates projektides võib peaharu nimi olla `master`.
   - Kustuta harud pärast nende ühendamist, et hoida hoidla puhas.
4. **Väldi avaldatud ajaloo muutmist:**
   - Kui `commit`-id on harusse tõugatud, väldi ajalugu ümberkirjutavate käskude kasutamist (nt `rebase` või `force push`), välja arvatud juhul, kui oled täiesti kindel, mida teed.
5. **Sünkroniseeri regulaarselt:**
   - Tõmba sageli peahoidlast, et integreerida muudatused ja lahendada konfliktid varakult.
6. **Lahenda konfliktid viivitamatult:**
   - Käsitle ja lahenda ühendamiskonfliktid kohe, kui need tekivad.
7. **Kasuta `.gitignore` faili:**
   - Lisa failid, mida ei peaks hoidlas olema (nt saladused, vahemälu, logifailid), `.gitignore` faili.
8. **Varunda:**
   - Kuigi Git on versioonikontrollisüsteem, on hea praktika omada hoidla varukoopiaid, eriti kui git on lokaalselt majutatud.

## GitHubi parimad praktikad

1. **Kasuta kirjeldavaid hoidla nimesid:**
   - Nimed peaksid andma vihje projekti eesmärgi või sisu kohta.
2. **Lisa `README.md`:**
   - Alati lisa oma hoidlatesse `README.md` fail. See peaks selgitama projekti, kuidas seda seadistada, kuidas paigaldada projekti sõltuvusi, kuidas projektis saab kaasa aidata ja muud asjakohast teavet. Pane tähele, et `README.md` nimi on kirjutatud suurte tähtedega.
3. **Kasuta `Issue`-de ja Pull Requestide malle:**
   - Mallid juhendavad kaastöötajaid esitama vajaliku teabe, kui luuakse `Issue`-id või `Pull Request`-e.
4. **Kaitse oma peaharu:**
   - Kasuta haru kaitse reegleid, et tagada, et `main` harule ei saaks otse tõugata, ja nõua enne ühendamist `pull requestide` ülevaatamist (_review_). Vanemates projektides võib kaitstav peaharu olla `master`.
5. **Kasuta silte:**
   - Organiseeri `Issue`-d ja `Pull Requestid`-id siltidega (nt `bug`, `enhancement`).
6. **Koodi ülevaatused:**
   - Vaata `Pull Request`-id enne ühendamist üle. See aitab parandada koodi kvaliteeti ja järjepidevust, sest muudatusi on vaadanud rohkem kui üks inimene.
7. **Suhtle kogukonnaga:**
   - Vasta `Issue`-dele ja `Pull Request`-idele õigeaegselt. Tänage ja julgustage kaastöötajaid, isegi kui nende panust projekti ei lisata.
8. **Kasuta GitHub Actions:**
   - Automatiseerige testimise, ehitamise ja juurutamise protsessid `GitHub Actions`-iga.
9. **Hoidke isikuandmed repositooriumist väljas:**
   - Ärge kunagi salvestage tundlikku teavet nagu **paroolid**, **API võtmed** või **saladused** oma hoidlatesse. Kasutage selleks GitHubi saladuste funktsiooni või väliseid tööriistu, nagu keskkonnamuutujad.
10. **Vaadake regulaarselt üle load ja juurdepääsud:**
    - Veenduge, et ainult vajalikel kaastöötajatel oleks juurdepääs teie hoidlale.

Nende parimate praktikate järgimine tagab, et teie Git'i ja GitHubi kasutamine on tõhus, teie projekti ajalugu jääb mõttekaks ja korraldatuks ning koostöö on sujuv ja produktiivne.
