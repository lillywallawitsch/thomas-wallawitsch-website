# Website Thomas Wallawitsch

Statische Website ohne Build-Schritt: `index.html`, `styles.css` und die Bilder in `assets/`.

## Lokal starten

Im Terminal in diesen Ordner wechseln und einen lokalen Server starten:

```sh
cd website-thomas-wallawitsch
python3 -m http.server 8000
```

Dann im Browser öffnen: http://localhost:8000

Alternativ einfach `index.html` per Doppelklick im Browser öffnen.

## Anpassen

- Farben und Abstände: Variablen oben in `styles.css` (`--accent` ist die Akzentfarbe)
- Inhalte: direkt in `index.html`
- Bilder: in `assets/` ersetzen, Dateinamen beibehalten

## Vor der Veröffentlichung

- Impressum und Datenschutzerklärung ergänzen (Pflicht für öffentliche Websites in Deutschland)
- Die Schrift Inter liegt lokal in `assets/fonts/`, es werden keine externen Dienste geladen.
