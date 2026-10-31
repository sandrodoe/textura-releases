# Textura

Ein lokales Studio für professionelle Romanentwicklung von **easyARTZ.de – Alessandro Dönicke**.

[Neueste Version herunterladen](https://github.com/sandrodoe/textura-releases/releases/latest)

## Installation

**Update von 0.7.0/0.7.1:** Bitte die aktuelle DMG einmal manuell installieren. In diesen Versionen konnte macOS die Bestätigung für „Installieren und neu starten“ stillschweigend abbrechen. Ab 0.7.2 erscheint die Bestätigung direkt in Textura. Vor dem Austausch Bücher speichern und Textura selbst beenden; die lokale Bibliothek bleibt erhalten.

Der erste Installer unterstützt **Apple Silicon (M1 und neuer), macOS 13.5 oder neuer**. Die DMG aus dem neuesten Release herunterladen, öffnen und Textura.app in Programme ziehen. Die App ist noch nicht Apple-notarisiert; macOS kann deshalb eine Sicherheitsbestätigung verlangen. Weitere Plattformen folgen über die getrennte Build-Pipeline.

## Funktionen

- Bücherbibliothek mit gespeichertem Arbeitsstand und Buchgedächtnis.
- Grundidee, Figuren und Beziehungen, Universum, Kapitelplanung und Manuskript.
- Lokale Speicherung und frühere Buchstände.
- EPUB, DOCX, Markdown, TXT, JSON und druckbares HTML/PDF.
- Optionale KI-Unterstützung für Schreiben, Lektorat, Analyse, Illustrationen und Cover.

## Automatische Updates

Die native App prüft beim Start und alle sechs Stunden auf neue Versionen. Update-Pakete werden signiert geprüft. Die Installation mit Neustart erfolgt nach deiner Bestätigung. Bücher bleiben außerhalb des Programmbundles in der lokalen Bibliothek erhalten.

Ältere Installationen ohne eingebauten Updater müssen einmal über den aktuellen Installer aktualisiert werden. `latest.json`, `.tar.gz` und `.sig` sind Dateien für den automatischen Updater. Zur manuellen Installation die `.dmg` verwenden.

Dieses Repository enthält öffentliche Installer und Update-Dateien. Der Quellcode wird in einem separaten privaten Repository entwickelt. Bücher, API-Schlüssel und private Signaturschlüssel werden hier nicht veröffentlicht.

Website und weitere Anbieterangaben: [easyARTZ.de](https://easyartz.de)
