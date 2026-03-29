# Semestrální práce z předmětu Psaní dokumentace 

V rámci semestrální práce byl vytvořen koncept a dva návody pro software spojený s bakalářskou prací „Obrazová detekce návštěvníků na Jizerské magistrále“. 

## Cílové skupiny
### Správci Jizerské magistrály
- Potřebují znát návštěvnost trasy a mít jednodušší přehled o počtu lidí. 
- Už podobný software používají. 
- Program budou používat ve vnitřních podmínkách na obrazovce monitoru. 

### Oponent
Potřebuje si řešení snadno spustit, ověřit a pochopit princip fungování i evaluace.

## Koncept
### Cíl řešení
- Stručné představení problému a důvodu vzniku aplikace.
- Vymezení, co má software uživateli přinést.

### Popis projektu
- Velmi stručný přehled projektu `counter` a jeho hlavní funkce.
- Vazba na bakalářskou práci a použitou doménu.

### Vstupy a výstupy
- Vstupní video, zvolená čára a model.
- Výstupy ve formě počtů průchodů, logů a volitelně anotovaného videa.

### Hlavní části systému
- Predikční pipeline.
- Evaluace výsledků.
- Webové rozhraní pro obsluhu a kontrolu běhu.

### Omezení a předpoklady
- Závislost na připravených datech a konfiguraci.
- Rozdíl mezi laděnými a předtrénovanými modely.

## Návody

### Jak spustit vyhodnocení webové rozhraní pro provedení predikce na videu
#### Předpoklady
- Co musí být v prostředí připraveno.
- Jaké soubory a složky musí být dostupné.

#### Spuštění aplikace
- Instalace závislostí.
- Pomocí uv primárně, pomocí Dockeru jako alternativa.
- Spuštění Streamlit rozhraní.

#### Práce v rozhraní
- Výběr modelu a videa.
- Nastavení čáry pro počítání.
- Spuštění predikce a sledování průběhu.

#### Kontrola výsledků
- Kde najít výsledné soubory.
- Jak zobrazit anotované video a počty průchodů.

### Jak spustit predikci na videu a evaluovat výsledky proti předpočítané referenční hodnotě
#### Předpoklady
- Připravené video a ground truth.
- Zkontrolované konfigurační soubory.

#### Spuštění predikce z příkazové řádky
- Úprava `predict.yaml` a výběr modelu.
- Spuštění příkazu pro predikci.

#### Kontrola výstupů predikce
- Ověření `counts.json` a dalších výstupů běhu.
- Kontrola, že existují výsledky pro všechna videa.

#### Spuštění evaluace
- Nastavení `eval.yaml`.
- Spuštění evaluace nad vytvořeným během.

#### Interpretace výsledků
- Kde najít metriky a CSV přehledy.
- Jak porovnat model s referenční hodnotou.

## Shrnutí
- Zhodnocení přínosu vytvořené dokumentace.
- Stručné zhodnocení použitelnosti pro správce a oponenta.

## Přílohy
- Odkazy na repozitář, konfigurace a ukázkové výstupy.

