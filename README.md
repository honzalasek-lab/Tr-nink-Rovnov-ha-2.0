Trénink & Rovnováha 2.0
Webová aplikace pro sledování domácího silového tréninku, doplňkových sportů (lezení, badminton, kolo), regenerace a výkonnostního progresu. Běží čistě v prohlížeči (`index.html`) a ukládá data lokálně do `localStorage` pod klíčem `trenink_rovnovaha_v2`.
Jak to nahrát na GitHub a spustit přes GitHub Pages
Vytvoř nový repozitář na GitHubu
Jdi na github.com/new.
Zadej název (např. `trenink-rovnovaha`), zvol Public a klikni na Create repository.
Nahraj soubory
V novém repozitáři klikni na Add file → Upload files.
Nahraj `index.html`, `README.md` a `CHANGELOG.md` (hlavní stránka musí mít v kořeni repozitáře název přesně `index.html`).
Klikni na Commit changes.
Zapni GitHub Pages
V repozitáři otevři Settings → Pages.
V sekci Build and deployment → Branch vyber větev `main` a složku `/ (root)`, poté klikni na Save.
Po cca 1 minutě bude aplikace dostupná na adrese `https://<tvoje-uzivatelske-jmeno>.github.io/<nazev-repozitare>/`.
Záloha, migrace a sdílení dat
Data se automaticky ukládají do `localStorage` pod klíčem `trenink_rovnovaha_v2`. Starší data z `trenink_rovnovaha_v1` nebo `trenink_rovnovaha_state` se při prvním otevření převedou a deduplikují.
Pro zálohu nebo přenos mezi zařízeními použij v záložce Nastavení tlačítka Export JSON a Import JSON.
Tlačítko ✦ Export / Sdílet do Gemini připraví čitelný souhrn aktivit a regenerace za zvolené období.
