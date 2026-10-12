# Válec

Nekonečné točení válcem pro uklidnění prstů. Webová aplikace na plochu mobilu.

## Nahrání na GitHub (poprvé)
1. github.com → vpravo nahoře **+** → **New repository**. Název např. `valec`, nech **Public**, klikni **Create repository**.
2. Na stránce nového repozitáře klikni na odkaz **uploading an existing file**.
3. Do okna přetáhni **obsah** rozbalené složky (index.html, manifest.webmanifest, sw.js, README.md a celou složku `icons`), ne složku samotnou.
4. Dole **Commit changes**.
5. **Settings** → v levém menu **Pages** → Branch: `main`, složka `/ (root)` → **Save**.
6. Za 1–2 minuty běží na `https://<tvuj-ucet>.github.io/valec/` (odkaz se objeví nahoře na stránce Pages).

## Aktualizace
Repozitář → **Add file → Upload files** → přetáhni změněné soubory → **Commit changes**. Stejné názvy se přepíšou.
Kdyby telefon ukazoval starou verzi, zavři aplikaci a otevři ji znovu (případně dvakrát).

## Na plochu telefonu
- **Android / Chrome:** menu ⋮ → *Přidat na plochu* / *Instalovat aplikaci*.
- **iPhone / Safari:** Sdílet → *Přidat na plochu*.

## Úpravy
Materiály, jejich chování a zvuk jsou na začátku skriptu v `index.html` v poli `MATERIALS`
(`mass` = setrvačnost, `k` = odpor po puštění, `c` = jak rychle dodrhne, `snd` = zvuk).
Po změně zvyš `VERSION` v `sw.js`.
