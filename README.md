# Rozcestník Gold Worlds 2027

Jednostránkový web, na který vede QR kód z letáku. Bude hostovaný na GitHub Pages.

## Jak změnit odkazy

V souboru `index.html` najdi blok `const LINKS = { ... }` (je hned nahoře) a doplň adresy do uvozovek.
Prázdné `""` znamená, že tlačítko ukazuje „Již brzy“ a nedá se na něj kliknout.

- `email` se píše jen jako adresa, bez `mailto:`.
- Hotel lze rezervovat přes web (`https://...`), nebo e-mailem (`mailto:rezervace@hotel.at`).
- Rezervační kódy hotelů jsou v `const CODES`.

## Jazyky

Stránka má přepínač EN / DE / CZ. Automaticky se otevře v jazyce telefonu, jinak v angličtině.
Texty jsou v bloku `const T` (en / de / cs).

## Co na stránce je

Odpočet do zahájení, registrace, oficiální informace, dva hotely s rezervačním kódem a tlačítkem pro kopírování, kyvadlová doprava, Worlds Sightseeing Tour, oficiální song, kontakt, Facebook a Instagram.
