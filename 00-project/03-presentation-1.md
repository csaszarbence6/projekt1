---
project_outline: "[[00-project/01-project-outline]]"
---

<!-- @slide Címlap -->

<!-- @set-align center -->

<!-- @space -->

# Többsávos podcast-videószerkesztő

**Császár Bence**

Neptun: WD7TOP

Témavezető: Laborci Gergely

Projektazonosító: 2026-LG-01

<!-- @space -->

---

<!-- @slide Probléma -->

# Probléma

A podcastfelvételek gyakran több különálló hang- és videóforrásból állnak. Ezek összehangolása, a nem kívánt részek kivágása, valamint annak meghatározása, hogy az egyes időpontokban melyik résztvevő hangja és képe jelenjen meg, időigényes lehet.

A projekt célja egy olyan többsávos podcast-videószerkesztő létrehozása, amely egy közös idővonalon teszi lehetővé a források szinkronizálását, a vágást, a hangsávok keverését és a videók kiválasztását.

---

<!-- @slide Célfelhasználók -->

# Célfelhasználók

<!-- @columns 2 4 -->

## Podcastkészítők

- Több hang- és videóforrás kezelése.
- A résztvevők felvételeinek szinkronizálása.
- A podcast egyszerűbb összeállítása és vágása.

<!-- @col-break -->

## Tartalomgyártók

- A hallható és látható sávok idővonalon történő kezelése.
- A nem kívánt részek kivágása.
- A kész videó exportálása.

---

<!-- @slide Tervezett hatókör -->

# Tervezett hatókör

- Hang- és videóforrások hozzáadása egy projekthez.
- A források résztvevőkhöz rendelése és szinkronizálása.
- A nem kívánt részek kivágása az idővonalon.
- A hallható hangsávok és látható videósávok meghatározása.
- Több hangsáv keverése és a hangerő beállítása.
- Előnézet és kliensoldali renderelés.
- A projekt és a szerkesztési adatok mentése.

---

<!-- @slide A projekt korlátai -->

# Mi nem része a projektnek?

- Teljes körű, általános célú videószerkesztő készítése.
- Intro- és outrovideók készítése.
- Összetett, általános vizuális utómunka.
- Több videó egyidejű megjelenítése az első változat kötelező funkciójaként.

**Fókusz:** a podcastfelvételek szinkronizálása, vágása, hangsávjainak kezelése és a végső videó előállítása.

---

<!-- @slide Kezdeti felhasználói utak -->

# Kezdeti felhasználói utak

1. A felhasználó létrehoz egy projektet.
2. Hozzáadja a szükséges hang- és videóforrásokat.
3. A forrásokat hozzárendeli a résztvevőkhöz.
4. Szinkronizálja a felvételeket a közös idővonalon.
5. Kivágja a nem kívánt részeket.
6. Meghatározza az adott időpontokban hallható hangsávokat és látható videókat.
7. Ellenőrzi az összeállítást az előnézetben.
8. Elindítja a kész videó renderelését és exportálását.

---

<!-- @slide Technikai megközelítés -->

# Kezdeti technikai megközelítés

A projekt egyik fontos feladata a megfelelő médiafeldolgozási technológia kiválasztása.

- A szerkesztési műveleteket egy közös idővonal írja le.
- A források szinkronizálásához időbeli eltolásokat kell kezelni.
- Az előnézetnek követnie kell az idővonalon beállított vágásokat és sávválasztásokat.
- A renderelést a tervek szerint a felhasználó saját eszközén kell elvégezni.
- A technológiai döntéseket a támogatott formátumok, a teljesítmény és a megvalósíthatóság vizsgálata alapján kell meghozni.

---

<!-- @slide Következő lépések -->

# Következő lépések

1. A médiafeldolgozási technológiák összehasonlítása.
2. A projekt- és forrásadatok adatmodelljének kialakítása.
3. A hang- és videóforrások betöltésének megvalósítása.
4. A közös idővonal és a szinkronizálás kialakítása.
5. A vágás és a hangsávok kiválasztásának megvalósítása.
6. Az előnézet és a kliensoldali renderelés prototípusának elkészítése.
7. A projekt mentésének, visszatöltésének és a hibakezelésnek a tesztelése.
