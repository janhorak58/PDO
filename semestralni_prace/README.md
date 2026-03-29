# Semestrální práce

V rámci semestrální práce z předmětu Psaní dokumentace byl vytvořen koncept a dva návody pro software spojený s bakalářskou prací „Obrazová detekce návštěvníků na Jizerské magistrále“.

Tato složka rozděluje práci do menších částí tak, aby se v ní dalo snadno orientovat. Nejprve vymezuje cílové skupiny a základní koncept řešení, potom nabízí dva praktické návody a nakonec uzavírá dokument shrnutím a přílohami.

## Rychlý start

### Požadavky

- [Python 3.10+](https://www.python.org/downloads/)
- [Git](https://git-scm.com/downloads)
- [uv](https://github.com/astral-sh/uv) — správce prostředí pro Python

### Instalace `uv`
#### macOS / Linux
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
``` 
#### Windows (PowerShell)
```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```
#### Spuštění Uživatelského rozhraní
```bash
git clone git@github.com:janhorak58/counter.git
cd counter
uv sync
uv run counter-ui
```

### Video návod
Pro vizuální představu o práci s rozhraním se můžete podívat na tento krátký video návod, který ukazuje základní kroky od spuštění rozhraní až po kontrolu výsledků.


[![Video návod: Jak spustit webové rozhraní pro provedení predikce na videu](./assets/screenshots/01_default_screen.png)](https://youtu.be/wDchsz8nmbo?si=r6Zp693EWs1j6dGG)
podrobný návod pro použití webového rozhraní je k dispozici v části [Jak spustit webové rozhraní pro provedení predikce na videu](./03_navody/webove_rozhrani/index.md).

## Obsah
- [Úvod a cílové skupiny](./01_uvod/01_cilove_skupiny.md)
- [Koncept](./02_koncept/01_cil_reseni.md)
- [Návod: webové rozhraní pro predikci](./03_navody/webove_rozhrani/index.md)
- [Návod: CLI predikce a evaluace](./03_navody/02_cli_predikce_a_evaluace.md)
- [Shrnutí](./04_zaver/01_shrnuti.md)
- [Přílohy](./04_zaver/02_prilohy.md)
