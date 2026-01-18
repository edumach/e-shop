
#  💾 Nákup na e-shopu

Živá ukázka: [https://php.edumach.cz/eshop.php](https://php.edumach.cz/eshop.php)

Zákazník si na e-shopu objednává zboží (pro jednoduchost v náhodné hodnotě 100&nbsp;-&nbsp;800&nbsp;Kč). Pokud si objedná 3 a více kusů (náhodný interval 1&nbsp;-&nbsp;6), bude mít slevu 20&nbsp;% z ceny. Skript vypíše celkovou cenu a případně výši slevy a cenu po slevě. Pokud celková cena po slevě bude nejméně 2000&nbsp;Kč, vypíše zelený text "Máte dopravu zdarma!", jinak platí 100&nbsp;Kč za dopravu.

## Příprava

1. Přihlas se **v terminálu** na server TuX a přesuň se do adresáře `~/www`
2. Gitem naklonuj repozitář `https://github.com/edumach/e-shop`
3. Tím vznikne adresář `~/www/e-shop/`
    ```
    $ cd www
    $ git clone https://github.com/edumach/e-shop
    cd e-shop
    ```
4. Zkontroluj funkčnost webu na URL `https://tux.panska.cz/~10XPrijmeniJ/e-shop`

## Logika kódu

1. Vygeneruj kusovou cenu v intervalu 100 - 800.
2. Vygeneruj počet kusů v intervalu 1 - 6.
3. Spočítej a vypiš celkovou cenu.
4. Pokud je nárok na 20% slevu:
   - vypočítej ji a vypiš,
   - vypiš také cenu po slevě.
5. Pokud cena po slevě překročí 2000:
   - vypiš zeleně "Máte dopravu zdarma",
   - jinak cenu včetně dopravného. 

Konečná cena bude vždy **zvýrazněna**. 


##  Odevzdání

Skript bude správně počítat výsledné hodnoty podle zadání. 

