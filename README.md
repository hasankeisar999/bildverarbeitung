# Bildverarbeitung — GitHub Pages

Diese README erklärt kurz, wie du die vorhandene Datei `bildverarbeitung.html` über GitHub Pages öffentlich zugänglich machst.

1) Repository auf GitHub erstellen
- Gehe zu https://github.com und erstelle ein neues Repository (z. B. `bildverarbeitung`).

2) Lokale Dateien committen und pushen
Öffne PowerShell im Projekt-Ordner und führe aus (ersetze `USERNAME` und `REPO`):

```powershell
git init
git add .
git commit -m "Add site and README"
git branch -M main
git remote add origin https://github.com/USERNAME/REPO.git
git push -u origin main
```

3) GitHub Pages aktivieren
- Öffne das Repository auf GitHub → Settings → Pages.
- Wähle Branch `main` und `Root` (/) als Ordner → Save.

4) URL der Seite
- Wenn die Seite eine `index.html` im Root hat: `https://USERNAME.github.io/REPO/`.
- Wenn die Datei `bildverarbeitung.html` heißt: `https://USERNAME.github.io/REPO/bildverarbeitung.html`.

5) Optional: Direkt unter Root erreichbar
- Benenne `bildverarbeitung.html` in `index.html` um und pushe erneut, dann ist die Seite unter der Root-URL erreichbar.

6) Commit & Push nach Änderungen
```powershell
git add .
git commit -m "Update site"
git push
```

Bei Fragen oder wenn ich den Commit/Push für dich ausführen soll, sag Bescheid.