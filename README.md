# Ranní rutina — Síla každý den

Jednostránková webová aplikace v HTML/CSS/JavaScriptu. Nepotřebuje instalaci ani server.

## Spuštění lokálně
Otevři `index.html` v prohlížeči.

## Publikování na GitHub Pages
1. Vytvoř na GitHubu nový veřejný repozitář, například `ranni-rutina`.
2. Nahraj do něj soubor `index.html` (a tento README, pokud chceš).
3. Otevři **Settings → Pages**.
4. V části **Build and deployment** vyber **Deploy from a branch**.
5. Vyber větev `main` a složku `/(root)`, potom klikni na **Save**.
6. Po chvíli bude web dostupný na adrese podobné `https://TVUJ-UCET.github.io/ranni-rutina/`.

## Funkce
- Denní 30minutový plán: rozcvička, běh, silový okruh a protažení.
- Body XP, úrovně, odměny a série tréninků.
- Kalendář s historií dokončených dnů.
- Postupně rostoucí počet opakování a čas planku (obtížnost se zvyšuje po každých 3 dokončených trénincích).
- Export dat do JSON a možnost resetovat postup.

## Ukládání dat
Pokrok se ukládá do `localStorage` daného prohlížeče a zařízení. Export si můžeš uložit jako zálohu. Obtížnost se zvyšuje po každých 3 dokončených trénincích, ne jen podle data v kalendáři.
