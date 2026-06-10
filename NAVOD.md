# Jak nainstalovat Baseball app na iPad

## Co je v tomto balíčku
- `index.html` — hlavní app
- `manifest.json` — PWA konfigurace
- `sw.js` — service worker (offline podpora)
- `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` — ikonky

---

## Krok 1 — Vytvoř GitHub účet (zdarma)
Jdi na https://github.com a zaregistruj se (nebo se přihlas).

## Krok 2 — Vytvoř nový repozitář
1. Klikni na zelené tlačítko **New** (nebo + vpravo nahoře)
2. Název: `hrosi-baseball` (nebo cokoliv)
3. Nastav na **Public**
4. Zaškrtni **Add a README file**
5. Klikni **Create repository**

## Krok 3 — Nahraj soubory
1. V repozitáři klikni na **Add file → Upload files**
2. Přetáhni VŠECHNY soubory z tohoto balíčku:
   - index.html
   - manifest.json
   - sw.js
   - icon-192.png
   - icon-512.png
   - apple-touch-icon.png
3. Klikni **Commit changes**

## Krok 4 — Zapni GitHub Pages
1. Jdi do **Settings** (ozubené kolo nahoře vpravo)
2. V levém menu klikni na **Pages**
3. Pod "Branch" vyber `main` a složku `/ (root)`
4. Klikni **Save**
5. Za 1–2 minuty se zobrazí URL ve tvaru:
   `https://tvoje-jmeno.github.io/hrosi-baseball`

## Krok 5 — Přidej na iPad
1. Na iPadu otevři Safari a jdi na tu URL
2. Klikni na ikonu **Sdílet** (čtverec se šipkou nahoru)
3. Klikni na **Přidat na plochu**
4. Název nech "Baseball" nebo "Hroši"
5. Klikni **Přidat**

✅ Hotovo! Ikonka je na ploše, app se otevírá bez adresního řádku a funguje offline.
Nastavení hráče (jméno, číslo, kategorie) se uloží a pamatuje.

---

## Alternativa — Netlify (ještě jednodušší, bez účtu)
1. Jdi na https://app.netlify.com/drop
2. Přetáhni celou složku s těmito soubory
3. Dostaneš URL okamžitě (např. https://random-name.netlify.app)
4. Pokračuj od Kroku 5 výše

