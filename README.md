# Ascent Training Lab

Aplikacja do treningów i statystyk: siłownia (serie z RIR/RPE, PWS, progres tonażu w %), bieganie, kalorie, plany i dane.
Cała aplikacja to jeden plik `index.html` — bez instalacji i bez serwera.

## Uruchomienie na telefonie (GitHub Pages)

1. Wrzuć zawartość tego folderu do repozytorium na GitHubie (pliki `index.html`, `manifest.webmanifest`, `icon-180.png`, `icon-512.png` w głównym katalogu).
2. W repozytorium: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, gałąź `main`, folder `/ (root)` → **Save**.
3. Po chwili strona będzie pod adresem `https://<twoja-nazwa>.github.io/<nazwa-repo>/`.
4. Na iPhonie otwórz ten adres w **Safari** → przycisk **Udostępnij** → **Do ekranu początkowego**. Aplikacja otworzy się na pełnym ekranie, z ikoną Ascent.

## Dane

Wszystko zapisuje się w pamięci przeglądarki (localStorage, klucz `apex-data`) na danym urządzeniu.
Telefon i komputer mają osobne dane. Usunięcie danych witryny w Safari kasuje też wpisy w aplikacji.
