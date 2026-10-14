
---
name: "Császár Bence"
neptun: "WD7TOP"
id: "2026-LG-01"
github: "https://github.com/csaszarbence6/projekt1"
github_project: "https://github.com/users/csaszarbence6/projects/1"
---

# Többsávos podcast-videószerkesztő

A projekt lényege egy olyan asztali alkalmazás készítése, amellyel több külön rögzített hang- és videóforrásból lehet podcastot összeállítani. A forrásokat közös idővonalra kell igazítani, majd megadni, hogy az egyes részekben melyik hang hallatszódjon, és melyik videó jelenjen meg. A cél nem egy általános videóvágó készítése, hanem a többszereplős podcastok szerkesztésének egyszerűsítése.

## Célok

- **Elsődleges cél:** Több hang- és videóforrásból egyetlen, szerkesztett podcast készítése.
- **Célfelhasználók:** Podcastkészítők, akik a résztvevőkről külön felvételeket készítenek.
- **Sikerkritérium:** A felhasználó forrásokat tud hozzáadni, szinkronizálni, kivágásokat és hangsávokat állítani, előnézetet nézni, majd videót vagy csak hangot exportálni.
- **Fejlesztőkörnyezet:** Tervezetten Electron, React és TypeScript; a médiafeldolgozás lehetséges eszköze az FFmpeg.
- **Adattárolás:** A projekt és a szerkesztési beállítások később is visszaállíthatók legyenek.

## Hatókör

### Benne van a hatókörben

- Projekt létrehozása, mentése és újranyitása.
- Hang- és videófájlok hozzáadása, résztvevőkhöz rendelése.
- Források kézi szinkronizálása közös idővonalra.
- Nem kívánt részek kivágása.
- Annak beállítása, hogy egy-egy szakaszban mely hang- és videósávok aktívak.
- Hangerő állítása és több hangsáv keverése.
- Videósávok alapértelmezett pan–zoom beállítása, valamint ennek idővonalas felülírása.
- Előnézet és helyi export.

### Nincs benne a hatókörben

- Automatikus hangalapú szinkronizálás.
- Automatikus feliratgenerálás és arckövetés.
- Komplex vizuális effektek és professzionális színkorrekció.
- Felhőben futó videó-renderelés.

## Jegyzetek

Elsőként az alapvető szerkesztési folyamatot kell megvalósítani. A támogatott formátumokat és a nagyobb fájlok kezelését a kiválasztott technológiákkal végzett tesztek alapján lehet pontosítani. Fontos, hogy a projekt újranyitásakor a vágások, a szinkroneltolások és a sávbeállítások is megmaradjanak.

A médiafeldolgozás és az export a felhasználó gépén történik. A végleges technológiai döntést a specifikációban összehasonlított lehetőségek és egy egyszerű prototípus alapján kell meghozni.
