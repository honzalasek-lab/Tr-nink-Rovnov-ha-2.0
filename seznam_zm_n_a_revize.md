# Changelog — Trénink & Rovnováha 2.0

## Revize a opravy kvality kódu a logiky

- **Kompletní a souvislá klientská logika (`index.html`):** Doplněny a sjednoceny všechny vykreslovací, stavové a interakční funkce pro záložky *Trénink*, *Regenerace*, *Progres* a *Nastavení* včetně časovače pauz a modálních oken.
- **Migrace a deduplikace dat:** Zajištěn bezpečný převod ze starších klíčů (`trenink_rovnovaha_v1`, `trenink_rovnovaha_state`) do `trenink_rovnovaha_v2` s odstraněním duplicitních záznamů podle `id`.
- **Návrhová dvojitá progrese:** Doporučení pro navýšení zátěže nebo změnu varianty se zobrazuje pouze jako návrh po opakovaném splnění horní hranice opakování s rezervou (RIR) a čistou technikou, bez automatického přepisování uživatelských voleb.
- **Přesnější popisky a omezení:** Odstraněny podstrčené výchozí hodnoty tělesné hmotnosti a zpřesněny popisky u orientačních výpočtů (session-RPE, odhad 1RM a orientační součet sérií).