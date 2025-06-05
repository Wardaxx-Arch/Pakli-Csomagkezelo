# pakli

**pakli** egy egyszerű Linux parancssoros eszköz, amely különböző parancsokat tartalmaz egy saját, szórakoztató CLI-élményhez.

## 📦 Telepítés

1. Klónozd a repót:

```bash
git clone https://github.com/Wardaxx/pakli.git
cd pakli
```

2. Futtasd a telepítő scriptet:

```bash
bash install.sh
```

Ez bemásolja a `pakli` parancsot a `/usr/local/bin/` mappába, így bárhonnan elérhetővé válik.

## 🧾 Használat

A help megjelenítéséhez:

```bash
pakli -h
```

Ha csak `pakli`-t írsz be, akkor is a help szöveg jelenik meg.

Példa parancs:

```bash
pakli -Ss keresett_kifejezes
```

## 🔄 Frissítés

A legfrissebb verzió eléréséhez:

```bash
pakli update
```

Ez automatikusan letölti a legújabb verziót a GitHub-ról és újratelepíti.

## 📁 Tartalom

- `pakli` – maga a parancs script
- `paklihelp.txt` – súgó / help szöveg
- `install.sh` – telepítő script

## ❗ Figyelmeztetés

A parancs sudo-jogosultságokat igényelhet egyes telepítési lépésekhez.

## 📜 Licenc

MIT License
