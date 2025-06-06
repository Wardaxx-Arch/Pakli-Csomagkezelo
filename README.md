# Pakli - Egyszerű Arch alapú csomagkezelő

Ez egy egyszerű, könnyen használható csomagkezelő script Fedora, Debian, és Arch stb... alapú disztribúciók számára, amely automatikusan kezeli a rendszer csomagkezelőjét.

---

## Funkciók

- Rendszer frissítése (`pakli -Syu`)
- Csomag keresése (`pakli -Ss keresőszó`)
- Csomag telepítése (`pakli -S csomagnevek`)
- Csomag eltávolítása (`pakli -R csomagnevek`)
- Csomagkezelő frissítése a GitHub-ról (`pakli -Update`)
- Súgó megjelenítése (`pakli -h`)
- Program Letöltése Githubról (`pakli -git`)
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
pakli -git                 # Github repo letöltése
