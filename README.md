# Semestrální práce

V rámci semestrální práce z předmětu Psaní dokumentace byl vytvořen koncept a dva návody pro software spojený s bakalářskou prací „Obrazová detekce návštěvníků na Jizerské magistrále".

Tato složka rozděluje práci do menších částí tak, aby se v ní dalo snadno orientovat. Nejprve vymezuje cílové skupiny a základní koncept řešení, potom nabízí dva praktické návody a nakonec uzavírá dokument shrnutím.

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
#### Spuštění uživatelského rozhraní
```bash
git clone git@github.com:janhorak58/counter.git
cd counter
uv sync
uv run counter-ui
```

### Video návod
Podívejte se na krátký video návod od spuštění rozhraní po kontrolu výsledků.

[![Video návod: Jak spustit webové rozhraní pro provedení predikce na videu](./assets/thumbnail.png)](./assets/navod.mov)

Podrobný postup je popsán v [návodu k webovému rozhraní](./03_navody/webove_rozhrani/index.md).

## Obsah
- [Úvod a cílové skupiny](./01_uvod/01_cilove_skupiny.md)
- [Koncept](./02_koncept/01_cil_reseni.md)
- [Návod: webové rozhraní pro predikci](./03_navody/webove_rozhrani/index.md)
- [Návod: evaluace výsledků](./03_navody/02_evaluace.md)
- [Shrnutí](./04_zaver/01_shrnuti.md)
