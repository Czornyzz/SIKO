[README.md](https://github.com/user-attachments/files/29417852/README.md)
# Kalkulator SIKO — M-210F (PWA)

Aplikacja webowa do strzelania i kierowania ogniem artylerii naziemnej (M-210F / Grad / WR-40).
Działa offline; po dodaniu do ekranu początkowego iPhone/iPad uruchamia się jak natywna apka.

## Publikacja na GitHub Pages
1. Utwórz publiczne repozytorium (np. `siko`).
2. **Add file → Upload files** → wgraj wszystkie pliki z tego folderu → **Commit**.
3. **Settings → Pages → Source: Deploy from a branch → Branch: `main` / `(root)` → Save**.
4. Adres: `https://twoj-login.github.io/siko/`.

## Instalacja na iPhone
Otwórz adres w **Safari** → **Udostępnij** → **Dodaj do ekranu początkowego** → **Dodaj**.
Uruchom raz z internetem; dalej działa offline.

## Pliki
- `index.html` — strona główna (kopia kalkulatora)
- `kalkulator_SIKO.html` — kalkulator
- `manifest.json`, `sw.js` — manifest PWA i obsługa offline
- `icon_180/192/512.png` — ikony aplikacji
