# turnaj
automatické výpočty pro fotbalový turnaj
zadej týmy
vyplň skore
vše se dopočítá samo



Single round

Generates each pairing only once, no duplicates.

✅ Head-to-head tie-breaker
When teams are tied on points, it ranks them by:

Head-to-head points (mini-table among tied teams)
Head-to-head goal difference
Head-to-head goals for
Overall goal difference
Overall goals for
Team name

Postup
Otevři https://tjsrepy1718.github.io/turnaj/admin.html a vyplň/změň data, která chceš v turnaji aktualizovat.

Klikni na Vygenerovat zápasy, pokud jsi měnil týmy nebo plán turnaje.

vyplň skóre/střelce

Klikni na export pro GIT — stáhne se soubor public-data.json.

V GitHubu (https://github.com/tjsrepy1718/turnaj) nahraj ten nový public-data.json do stejné složky, kde je index.html. vždycky se musí jmenovat "public-data.json"

Jak to nahrát na GitHub
Na GitHubu otevři repo a použij Add file → Upload files nebo přímo editaci souboru přes webové rozhraní.

Vyber nový public-data.json.

Potvrď commit změny.

Co aktualizovat pokaždé
Kdykoliv změníš týmy, výsledky nebo střelce v admin.html, musíš znovu kliknout na export pro GIT.

Starý public-data.json pak v repu přepiš novým souborem.

index.html pak při načtení vezme nová data z public-data.json.

výsledky pro rodiče jsou tady https://tjsrepy1718.github.io/turnaj/



