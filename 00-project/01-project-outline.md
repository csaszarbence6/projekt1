
---
name: "Császár Bence"
neptun: "WD7TOP"
id: 2026-LG-01
github: "https://github.com/csaszarbence6/projekt1"
github_project: ""
---

# Többsávos podcast-videószerkesztő

A podcastfelvételek gyakran különálló hang- és videóforrásokból állnak. Egy videóforrás saját hangsávot is tartalmazhat, ezért a végső produkcióban külön kell meghatározni, hogy az egyes időszakokban melyik résztvevő hangja hallható és melyik videója látható. A projekt célja egy asztali többsávos podcast-videószerkesztő készítése, amely szinkronizált forrásfelvételekből állít elő videó- vagy csak hangot tartalmazó kimenetet.

A felhasználó a forrásokat résztvevőkhöz rendeli, közös idővonalon szinkronizálja, megadja a kivágandó részeket, majd meghatározza az egyes időszakokban aktív hang- és videósávokat. Az alkalmazás előnézetet biztosít, a projekt- és szerkesztési adatokat tartósan tárolja, a renderelést pedig a felhasználó saját eszközén végzi.

## Célok

- **Elsődleges cél:** Olyan működő asztali alkalmazás készítése, amellyel több hang- és videóforrásból podcast állítható össze, majd helyben exportálható.
- **Célfelhasználók / érintettek:** Podcastkészítők, akik külön rögzített résztvevői hang- és videófelvételeket szeretnének egyetlen produkcióvá szerkeszteni.
- **Mérhető sikerkritériumok:** A felhasználó projektet hozhat létre és menthet; legalább egy hang- és egy videóforrást hozzáadhat; a forrásokat szinkronizálhatja; kivágásokat, hangsáv-választást, hangerőt és pan–zoom beállítást adhat meg; előnézetet nézhet; videó- és csak hangot tartalmazó kimenetet készíthet; a projekt újranyitásakor a szerkesztési állapot helyreáll.
- **Technikai irány:** TypeScript-alapú asztali kliens, tervezetten Electron és React használatával; előnézethez HTML médiaelemek és Web Audio API; helyi rendereléshez FFmpeg; tartós projektadatokhoz SQLite vagy más indokolt helyi tárolási megoldás.
- **Korlátok:** Az előnézet és a renderelés a kliens eszközén történik. A szerver — ha szükséges a fiókokhoz — nem dolgozza fel a hang- és videóanyagot. A titkok, tokenek és személyes vagy éles adatok nem kerülhetnek a Git-repozitóriumba.

## Hatókör

### Benne van a hatókörben

- Felhasználói fiókok és projektek kezelése.
- Hang- és videóforrások hozzáadása, metaadataik kezelése és résztvevőkhöz rendelése.
- Kézi szinkronizáció közös időbeli nullponthoz.
- Idővonalon megadott kivágások és szakaszonkénti hang-/videósáv-választás.
- Több hangsáv keverése és sávonkénti hangerőállítás.
- Videósávonkénti alapértelmezett pan–zoom beállítás és idővonalas felülírás.
- Előnézet, helyi videó-renderelés és csak hangot tartalmazó export.
- Projekt- és szerkesztési adatok tartós tárolása, validáció és hibakezelés.
- Git-alapú verziókezelés és tesztelés.

### Nincs benne a hatókörben az első változatban

- Általános célú, professzionális videó-utómunka.
- Intro/outro készítése és összetett vizuális effektek.
- Professzionális színkorrekció.
- Automatikus feliratgenerálás és automatikus arckövetés.
- Automatikus, hangjel alapján történő szinkronizáció.
- Több videó egyidejű megjelenítése előre definiált elrendezésekben; ez opcionális bővítés.

## Jegyzetek

Az első megvalósítás a kötelező szerkesztési folyamatra koncentrál: források kezelése, kézi szinkronizáció, idővonal, hangkeverés, pan–zoom, előnézet és helyi export. A médiafeldolgozási technológiákat prototípussal kell ellenőrizni, különös tekintettel a kodektámogatásra, a hosszú fájlok memóriaigényére és az előnézet, illetve az export eredményének egyezésére.

A pontosan támogatott formátumokat és a teljesítményhatárokat tesztelés után kell rögzíteni; mérés nélkül nem vállalunk konkrét maximális fájlméretet vagy garantált renderelési sebességet.
