




## Pred
Vyberte v rozhraní model z nabídky a potom zvolte video, které chcete zpracovat. Zkontrolujte, že odpovídá správná vstupní cesta a že jste vybrali vhodný model pro daný typ dat.

Nastavte čáru pro počítání průchodů. Pokud rozhraní nabízí úpravu čáry nad prvním snímkem videa, upravte ji tak, aby odpovídala místu, přes které mají být průchody sledovány.

Nakonec spusťte predikci a sledujte průběh běhu. Po dobu zpracování nechte aplikaci otevřenou a průběžně kontrolujte, zda se běh nezastavil kvůli chybě v konfiguraci nebo ve vstupních datech.

![Placeholder: výběr modelu a videa](../assets/screenshots/02_vyber_modelu_a_videa.png)
_Doplnit snímek výběru modelu a videa._

![Placeholder: nastavení čáry](../assets/screenshots/03_nastaveni_cary.png)
_Doplnit snímek nastavení čáry pro počítání._

## Kontrola výsledků
Po dokončení běhu otevřete poslední výsledek a zkontrolujte, zda vzniklo anotované video a výsledné počty průchodů. Sledujte, jestli hodnoty dávají smysl vzhledem k obsahu videa a jestli systém správně zaznamenal směry průchodů.

Pokud rozhraní zobrazuje historii běhů nebo detail výsledku, otevřete ji a ověřte, že se vytvořily i očekávané výstupní soubory. Zaměřte se hlavně na soubor `counts.json`, který obsahuje vlastní výsledek počítání.

![Placeholder: zobrazení výsledků predikce](../assets/screenshots/04_vysledky_predikce.png)
_Doplnit snímek výsledků predikce a počtů průchodů._

## Návaznost
- Další část: [CLI predikce a evaluace](./02_cli_predikce_a_evaluace.md)
