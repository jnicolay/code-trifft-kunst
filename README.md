# Klingende Bilder – GitHub Pages Fallback

Statische Webseite für einen JavaScript-Workshop ohne ESP32. Die drei virtuellen Pads spielen standardmäßig Sinustöne. Die Teilnehmenden laden eigene MP3/WAV/M4A-Dateien hoch, ändern den JavaScript-Code und testen direkt im Browser.

## Veröffentlichen

1. Auf GitHub neues **öffentliches** Repository erstellen (z. B. `klingende-bilder`).
2. Die Datei `index.html` in das **Hauptverzeichnis** des Repositories hochladen (`Add file` → `Upload files` → `Commit changes`). ZIP nicht ungepackt hochladen!
3. `Settings` → `Pages` → `Build and deployment` → `Deploy from a branch` → `main` → `/(root)` → `Save`.
4. Danach die in GitHub Pages angezeigte Adresse öffnen (typisch `https://BENUTZERNAME.github.io/klingende-bilder/`).

## Workshop

- `Audio einschalten` drücken, dann Pads ausprobieren.
- Eigene Dateien hochladen – Auswahl ist nur temporär im Browser.
- In `function beruehrung(flaeche)` die drei Fälle ändern und `Programm starten` drücken.
- Code lokal im Browser speichern oder als JS-Datei herunterladen.

## Technische Grenzen

- Kein ESP32 notwendig oder verbunden. Dies ist **nur** die Browser-Simulation.
- Kein Upload von Audio an GitHub: Audiodateien bleiben auf dem jeweiligen Gerät; bei Neuladen neu auswählen.
- Code-Speicherung via localStorage hängt von Browser und Gerät ab.
- MP3/WAV breit unterstützt; M4A je nach Browser und Codec; direkte Mikrofonaufnahme ist hier nicht eingebaut.
- Im Editor eingegebener JavaScript-Code wird lokal ausgeführt. Nur eigenen bzw. vertrauenswürdigen Code verwenden.
