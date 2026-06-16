# Vzdělávací projekty – web pro GitHub/Netlify

Hotový statický web pro prezentaci vzdělávacích programů:

- Finanční gramotnost v praxi
- Práva studentům
- Projekty
- Pro školy
- Kontakt

## Nasazení na GitHub Pages

1. Vytvoř nový repozitář.
2. Nahraj všechny soubory ze složky do rootu repozitáře.
3. V Settings → Pages nastav deploy z větve `main` a složky `/root`.

## Nasazení na Netlify

1. Přetáhni celou složku nebo ZIP do Netlify.
2. Formulář v `kontakt/index.html` je připravený na Netlify Forms (`data-netlify="true"`).
3. Po prvním deployi zkontroluj, že se formulář objevil ve Forms.

## Úpravy před ostrým spuštěním

- V `sitemap.xml` a `robots.txt` nahraď `https://example.cz/` za skutečnou doménu.
- Doplň reálný e-mail / telefon do kontaktu, pokud je chceš zveřejnit.
- Přidej fotky z přednášek, jakmile budou k dispozici.
- Doporučený název domény: něco jako `vzdelavaciprojekty.cz`, `pravastudentum.cz` nebo subdoména pod Marvonixem.

## Struktura

```
index.html
style.css
script.js
assets/
programy/
  financni-gramotnost.html
  prava-studentum.html
pro-skoly/
projekty/
kontakt/
```
