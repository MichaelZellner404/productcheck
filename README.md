# ProduktCheck - Produktbewertungs-Website

Eine einfache, aber leistungsstarke Web-App zum Bewerten von Produkten mittels Barcode-Scanning.

## Features

✅ **Barcode-Upload**: Lade Bilder von Barcodes hoch (per Klick oder Drag & Drop)  
✅ **Produkt-Erkennung**: Automatische Erkennung bereits hochgeladener Produkte  
✅ **Prozent-Bewertungssystem**: Bewerte Produkte von 0-100%  
✅ **Mehrfach-Bewertungen**: Füge weitere Bewertungen zu bestehenden Produkten hinzu  
✅ **Produktinformationen**: Speichere Preise, Beschreibungen und Details  
✅ **Offline-fähig**: Alle Daten werden lokal im Browser gespeichert  

## Installation auf GitHub Pages

### Schritt 1: Repository erstellen
1. Gehe zu [GitHub](https://github.com) und melde dich an
2. Klicke auf "New Repository"
3. Gib einen Namen ein (z.B. "produktcheck")
4. Wähle "Public" (für GitHub Pages kostenlos)
5. Klicke auf "Create repository"

### Schritt 2: Datei hochladen
1. Klicke in deinem neuen Repository auf "Add file" → "Upload files"
2. Lade die `index.html` Datei hoch
3. Klicke auf "Commit changes"

### Schritt 3: GitHub Pages aktivieren
1. Gehe zu "Settings" in deinem Repository
2. Scrolle runter zu "Pages" im linken Menü
3. Bei "Source" wähle "Deploy from a branch"
4. Bei "Branch" wähle "main" und Ordner "/ (root)"
5. Klicke auf "Save"

### Schritt 4: Website aufrufen
Nach wenigen Minuten ist deine Website unter folgender URL verfügbar:
```
https://[dein-username].github.io/[repository-name]/
```

Beispiel: `https://maxmustermann.github.io/produktcheck/`

## Verwendung

1. **Neues Produkt**: 
   - Lade ein Foto des Barcodes hoch
   - Fülle die Produktinformationen aus
   - Schreibe deine erste Bewertung
   - Wähle deine Bewertung mit dem Schieberegler (0-100%)

2. **Bestehendes Produkt**:
   - Lade ein Foto des gleichen Barcodes hoch
   - Die Website zeigt automatisch das gespeicherte Produkt an
   - Klicke auf "Eigene Bewertung hinzufügen"

3. **Durchschnittsbewertung**:
   - Wird automatisch aus allen Bewertungen berechnet
   - Sichtbar auf der Produktseite

## Technische Details

- **Reine Frontend-Lösung**: Keine Server oder Datenbank nötig
- **LocalStorage**: Daten werden lokal im Browser gespeichert
- **Responsive Design**: Funktioniert auf Desktop und Mobilgeräten
- **Barcode-Simulation**: Verwendet Image-Hash (für echte App: Barcode-Scanner-Library integrieren)

## Hinweise

⚠️ **Datenspeicherung**: Alle Daten werden lokal im Browser gespeichert. Bei Löschen des Browser-Caches gehen die Daten verloren.

⚠️ **Barcode-Erkennung**: Die aktuelle Version verwendet einen simulierten Barcode-Scanner. Für eine produktive App sollte eine echte Barcode-Scanner-Library wie QuaggaJS oder ZXing integriert werden.

## Zukünftige Erweiterungen

- Integration echter Barcode-Scanner-Library
- Cloud-Speicherung für geräteübergreifenden Zugriff
- Produktbilder zusätzlich zum Barcode
- Export/Import-Funktion
- Suchfunktion für Produkte
- Kategorisierung

## Lizenz

MIT License - Frei verwendbar für persönliche und kommerzielle Projekte

---

Made with ❤️ for product lovers
