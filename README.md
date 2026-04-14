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
Otevři repo tjsrepy1718/turnaj na GitHubu.

Klikni na Add file → Upload files. Přes webové rozhraní GitHubu můžeš nové soubory přidat i přepsat existující.

Nahraj do rootu repozitáře tyto soubory:

index.html

public-data.json

admin.html

Pokud už tam některý z nich je, nech ho přepsat novou verzí a potvrď změny commitem. GitHub web interface změny uloží do branch po kliknutí na Commit changes.

Otevři Settings → Pages.

V části Build and deployment nastav:

Source = Deploy from a branch

Branch = main

Folder = / (root)

Ulož nastavení přes Save. GitHub Pages pak bude publikovat web přímo z hlavní větve a kořene repozitáře.

Počkej chvíli na nasazení. GitHub Pages může po commitu nebo změně nastavení potřebovat krátký čas na deploy.

Veřejný odkaz pro rodiče bude:

https://tjsrepy1718.github.io/turnaj/

Tvůj admin odkaz bude:

https://tjsrepy1718.github.io/turnaj/admin.html

Kdykoli budeš chtít aktualizovat data:

otevři admin.html

uprav výsledky

stáhni nový public-data.json

v repu přepiš jen public-data.json

klikni na Commit changes

Rodičům posílej pouze hlavní veřejný odkaz, ne admin.html. Tím zůstane veřejná stránka fakticky jen ke čtení.
