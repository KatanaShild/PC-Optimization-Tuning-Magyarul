# Gaming PC Optimization Guide

> **Ne tweakelj vakon. Értsd meg, mérd meg, és a saját gépedhez optimalizálj.**

## Mi ez?

Ez a dokumentáció egy magyar nyelvű, mérésalapú útmutató PC-k és laptopok játékra történő optimalizálásához.

Nem egy újabb „100 Windows tweak, amitől +50 FPS-ed lesz” lista szeretne lenni.

A cél az, hogy ne csak azt mutassa meg, **mit állíts át**, hanem azt is, hogy:

* mit változtatsz meg,
* mi történik a háttérben,
* miért lehet ennek hatása a teljesítményre,
* mikor érdemes alkalmazni,
* hogyan tudod megmérni a hatását,
* milyen eredményt várhatsz,
* és mikor érdemes inkább visszavonni a módosítást.

## Nincs univerzális optimalizálás

Két látszólag ugyanolyan gépen sem feltétlenül működik ugyanaz a beállítás.

A hardver, a hűtés, a BIOS, a Windows-verzió, a driverek, az energiaellátás, a háttérfolyamatok, a játék motorja és maga a játékterhelés is befolyásolhatja az eredményt.

Ezért itt nem az a cél, hogy minden gépen ugyanazokat a beállításokat alkalmazzuk.

**A cél egy olyan módszer megtanításak, amellyel mindenki meg tudja találni, hogy a saját rendszerén mi működik és mi nem.**

## Mérj, mielőtt változtatsz

Egy optimalizálás csak akkor nevezhető optimalizálásnak, ha bizonyítható, hogy a rendszer jobb lett tőle.

Ezért a dokumentáció alapelve:

**Baseline → Mérés → Módosítás → Újramérés → Összehasonlítás**

Ha egy tweak után magasabb lett az átlag FPS, de közben romlott a frametime vagy az 1% low, akkor nem tekintjük automatikusan sikeresnek a módosítást.

## Fokozatosan haladunk

Az optimalizálás nem egyetlen nagy változtatás.

A dokumentáció az egyszerűbb és könnyebben visszafordítható módosításoktól halad a mélyebb, összetettebb és nagyobb kockázatú beállítások felé.

A cél egyszerű: kihozni a fenevadat a gépedből. Megkeresni, mi fogja vissza, és kihozni belőle azt, amire valójában képes.

## Mire számíthatsz?

A dokumentáció fő területei:

1. **Power** – energiagazdálkodás és teljesítményprofilok
2. **CPU** – processzor, scheduling és boost viselkedés
3. **GPU** – grafikus processzor és driverbeállítások
4. **Hálózat** – latency, packet loss és hálózati optimalizálás
5. **RAM** – memóriahasználat és memóriakezelés
6. **Játék konfiguráció** – játék- és engine-specifikus beállítások
7. **SSD/HDD** -maximális sebbeség elérése és életartalmának növelése

Később további területek is bekerülhetnek, például operációs rendszerrel, hardverjavítással, hibakereséssel vagy diagnosztikával kapcsolatos anyagok.

## A legfontosabb szabály

**Ne azért módosíts valamit, mert valaki azt mondta, hogy jobb lesz.**

Először értsd meg, mit csinál.

Ezután mérd meg a saját rendszereden.

Majd az eredmény alapján dönts.

Ez a projekt erről szól.

