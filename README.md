# Pakli - Egyszerű Arch alapú csomagkezelő

Ez egy egyszerű, könnyen használható csomagkezelő script Arch Linux és Arch alapú disztribúciók számára, amely automatikusan kezeli a `pacman` és az `yay` csomagokat.

---

## Funkciók

- Rendszer frissítése (`pakli -Syu`)
- Csomag keresése (`pakli -Ss keresőszó`)
- Csomag telepítése (`pakli -S csomagnevek`)
- Csomag eltávolítása (`pakli -R csomagnevek`)
- Csomagkezelő frissítése a GitHub-ról (`pakli -Update`)
- Súgó megjelenítése (`pakli -h`)

---

## Telepítés

1. Klónozd a repót:
    ```bash
    git clone https://github.com/Wardaxx-Arch/Pakli-Csomagkezelo.git
    cd Pakli-Csomagkezelo
    ```

2. Add futtatási jogosultságot a `pakli` scriptnek:
    ```bash
    chmod +x pakli
    ```

3. Másold a `pakli` scriptet egy PATH-ban lévő helyre, pl.:
    ```bash
    sudo cp pakli /usr/local/bin/
    ```

---

## Használat

```bash
pakli -Syu                 # Rendszer frissítése
pakli -Ss keresőszó        # Csomag keresése
pakli -S csomagnevek       # Csomag(ok) telepítése
pakli -R csomagnevek       # Csomag(ok) eltávolítása
pakli -Update              # Pakli frissítése a GitHub-ról
pakli -h                   # Súgó megjelenítése
