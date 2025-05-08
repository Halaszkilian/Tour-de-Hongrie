# Tour de Hongrie Weboldal Fejlesztés

Ez a feladat a Tour de Hongrie weboldal fejlesztésére vonatkozik, ahol különböző módosításokat kell végezni a meglévő HTML, CSS és JavaScript fájlokon, hogy azok megfeleljenek a leírt követelményeknek.

## Feladatok

### 1. HTML módosítások (`tourdehongrie.html`)
1. **Karakterkódolás és nyelv beállítása:**
   - Állítsa be a karakterkódolást UTF-8-ra.
   - Állítsa be a nyelvet magyarra.
   - A böngésző címsora jelenítse meg a „Tour de Hongrie” szöveget.

2. **Hivatkozások hozzáadása:**
   - A fejrészben (head) helyezze el a hivatkozásokat a `tdh.css` stíluslapra és a `tdh.js` JavaScript fájlra a meglévő hivatkozások után.

3. **Menü módosítása:**
   - A második menüpontban módosítsa a szöveget „41. Tour de Hongrie”-ról „2020”-ra.

4. **A Tour de Hongrie története blokk módosítása:**
   - A második oszlop képe alá illessze be az 1964-es verseny célfotóját (`cel1964.jpg`), amelynek forrása a `cel1964.jpg` képfájl.
   - A kép alá írjon egy bekezdést „Célfotó az 1964-es versenyen” szöveggel.
   - Ha a kép nem tölthető be, vagy fölé visszük az egeret, akkor a „Befutó 1964-ben” szöveg jelenjen meg.
   - A beillesztett képet formázza `kiskep` osztály alkalmazásával.
   - A bekezdést formázza `kepfelirat` osztály alkalmazásával.

5. **2020-as Tour de Hongrie blokk módosítása:**
   - Az első oszlopban található „Média” alcím alatti bekezdés szövegét jelenítse meg.
   - A szövegen belül a „YouTube csatornáján” kifejezéshez készítsen egy új lapon megnyíló hivatkozást.
   - A blokk második oszlopának tetején található térkép feletti bekezdést alakítsa 3-as szintű címsorrá.

6. **Magyar sikerek blokk módosítása:**
   - A blokk oszlopainak arányát módosítsa 5:2:5-ről 4:4:4-re.
   - Állítsa be a csúszka formátumú beviteli mező szélsőértékeit 1-re és 41-re.
   - A beviteli mező értékének változásakor a `frissit()` JavaScript függvényt hívja meg.
   - Az „Időszalag” alcím utáni számozott felsorolást formázza a `helyezes` osztály alkalmazásával.

### 2. CSS módosítások (`tdh.css`)
1. **Címsorok formázása:**
   - A 2-es szintű címsorokat formázza félkövér betűstílussal.

2. **Kép formázása:**
   - A `kiskep` osztály szelektorát bővítse úgy, hogy a szegély sarkai 15px-es sugárban legyenek lekerekítve.

3. **Háttérkép és margó beállítása:**
   - A `row` osztály szelektorát bővítse úgy, hogy a háttérkép a `fatyol.png` legyen, és a belső margó 20px-es legyen.

### 3. JavaScript módosítások (`tdh.js`)
1. **Frissítés függvény módosítása:**
   - A `frissit()` függvényt bővítse úgy, hogy a dokumentum `sorszam` azonosítójú elemében frissüljön a kiválasztott verseny sorszáma.

2. **Listaelem függvény módosítása:**
   - A `listaelem` függvény módosításával a magyar eredmények dőlt kiemelés helyett félkövér kiemeléssel jelenjenek meg.

---

## Eszközök
- **HTML**: Weboldal struktúra módosítása.
- **CSS**: Oldal stílusának módosítása.
- **JavaScript**: Dinamikus funkciók hozzáadása.

## A feladat megoldásának lépései
1. Módosítsa a `tourdehongrie.html` fájlt az utasításoknak megfelelően.
2. Alakítsa a `tdh.css` fájlt a stílus változtatásokhoz.
3. Frissítse a `tdh.js` fájlt a JavaScript funkciókhoz.
4. Tesztelje a weboldalt, hogy minden módosítás megfelelően működjön.

### Felhasználható fájlok:
- `tourdehongrie.html` - Weboldal HTML fájlja.
- `tdh.css` - Weboldal stíluslapja.
- `tdh.js` - Weboldal JavaScript fájlja.
- `cel1964.jpg` - Kép az 1964-es versenyről.
- `fatyol.png` - Háttérkép.

---

A módosítások elvégzése után a weboldalnak az új követelmények szerint kell működnie. Ne felejtse el ellenőrizni, hogy minden hivatkozás és funkció megfelelően működik.
