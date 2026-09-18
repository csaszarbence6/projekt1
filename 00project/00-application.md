Név: Császár Bence
Neptun: WD7TOP
ID: 2026-LG-01

Többsávos podcast-videószerkesztő

A brief értelmezése
A projekt célja, hogy egy többsávos podcast és videószerkesztő alkalmazást hozzak létre. Ebben az alkalmazásban a hangfájlokat és videófájlokat lehetne szinkronizálni résztvevőkhöz, 
kivágni a nem kívánt részeket és egy előnézetet készítene, ami könnyítené a munkánkat.

Miért én lennék alkalmas erre a projektre?
A videószerkesztés évek óta a személyes hobbim felhasználói oldalról, amit nagyon szeretek csinálni. Emiatt kifejezetten érdekel, hogy azok a vágóprogramok, 
amiket a mindennapokban használok, hogyan épülnek fel a háttérben. Az egyetemen elsajátított és a félév során megszerzett tudásomat szeretném egy olyan gyakorlati projekten kamatoztatni, ami tényleg motivál.

Releváns tapasztalat és előzmények
Eddigi tanulmányaim során C és Python nyelvben már programoztam. Ezen kívül foglalkoztam webfejlesztéssel, adatbázisokkal és SQL-el is. 
A git használatban is van némi tapasztalatom. Saját weboldalt is szerkesztettem már és a videószerkesztéssel pedig felhasználói oldalról foglalkoztam nagyon sokat.

Tervezett megközelítés
A kiírásnak megfelelően egy asztali alkalmazást készítek Electron segítségével, TypeScript és React alapon. A webes tapasztalataimra építve React komponensekből építem fel a többsávos idővonalat, 
ahol a fájlokat résztvevőkhöz lehet rendelni, mozgatni és vágni.
Az előnézetnél a böngésző beépített HTML5 videólejátszóját és a Web Audio API-t használom a hangsávok keverésére, a hangerő állítására és a pan–zoom beállítások kezelésére.
Mivel a renderelésnek a kliens gépén kell történnie, a háttérben FFmpeg-et hívok meg: ez a timeline-on megadott vágások alapján helyben összerakja a kész MP4 videót vagy a külön hangsávot. 
A projektek adatait és a bejelentkezést egy egyszerű Node.js backenddel és egy relációs adatbázissal (pl. PostgreSQL vagy SQLite) kezelem, a kódot pedig Gitben vezetem.

Kezdeti terv
1. Az Electron + TypeScript + React asztali környezet és a Git repó felállítása.
2. A médiafájlok betöltésének, a résztvevőkhöz rendelésnek és a közös nullpontos szinkronizációnak a kidolgozása.
3. A többsávos idővonal (timeline) felületének megépítése a klipek vágásához és mozgatásához.
4. Az előnézeti motor megvalósítása (a kiválasztott sávok valós idejű megjelenítése, hangerőkezelés, pan–zoom).
5. A helyi exportálási folyamat kialakítása FFmpeg segítségével (kész videó és külön audió kimenet).
6. A Node.js backend és az adatbázis elkészítése a felhasználók és a projektállapotok perzisztens tárolásához.
7. Hibakezelés implementálása (hibás vagy nem támogatott médiafájlok és meghiúsult renderelés lekezelése).
8. Tesztelés, kódátnézés és a dokumentáció elkészítése.
