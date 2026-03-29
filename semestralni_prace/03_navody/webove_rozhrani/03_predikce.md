# Spuštění predikce

Na stránce najděte sekci pro výběr modelu a videa. 

![Otevření sekce pro výběr modelu a videa](../../assets/screenshots/predict/01_section.png)

- **Vyberte variantu modelu** - Pokud jste dříve nahráli natrénovaný model, máte zde možnost zvolit variantu `tuned`. Pokud chcete použít předtrénovaný model, zvolte variantu `pretrained`. 
- **Vyberte model** - Zvolte model, který chcete použít pro predikci.
- **Vyberte video** - Zvolte video, které chcete zpracovat. Pokud zde není žádné video k výběru, je potřeba nejprve nahrát video podle návodu [zde](./01_nahrani_videa.md).
- **Vykreslit každý n-tý snímek** - Toto nastavení určuje jemnost výsledného videa. Výchozí hodnota 5 znamená, že bude vykreslen každý pátý snímek. 
- **Vlastní čára** - Doporučejeme nastavit vlastní polohu čáry pro počítání průchodů. 

## Instrukce pro zvolení vlastní čáry
Klikněte na tlačítko "Vlastní čára" pro rozbalení nabídky pro nastavení čáry. Zde máte možnost nastavit vlastní polohu čáry pro počítání průchodů.

*Poznámka: před načítáním prvního snímku videa proveďte znovunačtení stránky (`CTRL + R`).*

Lze tak učinit dvěma způsoby:
1. **Zadejte souřadnice čáry ručně** - Pokud znáte přesné souřadnice pro začátek a konec čáry, můžete je zadat do příslušných polí. Souřadnice by měly být ve formátu `x,y` (např. `100,200`). Také zadejte rozlišení videa.
2. **Nastavení čáry nad prvním snímkem videa (Doporučené)** - Po kliknutí na tlačítko "Nastavit čáru nad prvním snímkem videa" se načte první snímek zvoleného videa a zobrazí se nástroj pro nastavení čáry. 

![Otevření nastavení pro vlastní čáru](../../assets/screenshots/predict/02_pick_line_1.png) 

Zobrazí se nástroj pro nastavení čáry. Prvním kliknutím označíte místo, kde má čára začínat. Druhým kliknutím označíte místo, kde má čára končit. 

![Nastavení vlastní čáry nad prvním snímkem videa](../../assets/screenshots/predict/03_pick_line_2.png)

Následně kikněte na tlačítko "Požít naklikané body" pro potvrzení nastavení čáry.

## Spuštění

Po nastavení všech parametrů klikněte na tlačítko "Spustit predikci". 
![Spuštění predikce](../../assets/screenshots/predict/04_run.png)

## Průběh predikce

Po spuštění predikce se zobrazí průběh běhu.

![Průběh predikce](../../assets/screenshots/predict/05_running.png)

V horní části se zobrazuje aktuální stav běhu, počet zpracovaných snímků, stav, zařízení na kterém predikce běží, zpracovávané video a uplynulý čas.

Lze také zobrazit detailní logy z běhu, které mohou být užitečné pro kontrolu průběhu.

![Průběh predikce - detail](../../assets/screenshots/predict/06_logs_progress.png)

Po dokončení běhu se stav změní na "dokončeno".
![Dokončení predikce](../../assets/screenshots/predict/07_done.png) 