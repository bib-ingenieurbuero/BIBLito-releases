# BIB Lito für Windows – Downloads

Hier stehen die fertigen Versionen von **BIB Lito für Windows**, der Büroversion der iPhone-App „BIB Lito“
(Beweissicherung, Mängel und Tickets) der Bassam Ingenieurbüro für Bauwesen GmbH.
Die neueste Version steht immer unter **[Releases → Latest](../../releases/latest)**.

## Installieren

1. Unter [Releases → Latest](../../releases/latest) die Datei **`BIBLito-win-Setup.exe`** herunterladen.
2. Doppelklick auf die Datei. Die Installation läuft nur für den angemeldeten Benutzer und braucht
   **keine Administratorrechte**. Danach gibt es „BIB Lito“ auf dem Desktop und im Startmenü.
3. Erscheint die blaue Meldung **„Der Computer wurde durch Windows geschützt“** (SmartScreen):
   auf **„Weitere Informationen“** klicken, dann auf **„Trotzdem ausführen“**.
   Die Meldung kommt, weil das Programm (noch) nicht mit einem gekauften Zertifikat signiert ist.

Voraussetzung: Windows 10 (Version 2004 oder neuer) oder Windows 11, 64 Bit. .NET muss nicht installiert sein.

## Aktualisieren

Automatisch. Die installierte Version sucht beim Start im Hintergrund nach einer neuen Version und lädt sie
herunter. Danach erscheint oben im Fenster „Version X ist verfügbar“ mit der Wahl
**„Jetzt neu starten“** oder **„Beim Beenden installieren“**. Von Hand: Menü **Hilfe › Nach Updates suchen**.
Die installierte Version steht unter **Hilfe › Info**.

## Portable Version

**`BIBLito-portable.exe`** ist eine einzelne Datei ohne Installation, z. B. für einen USB-Stick oder einen
fremden Rechner. Sie aktualisiert sich **nicht** selbst – neue Versionen bitte hier wieder herunterladen
oder die Setup-Version nutzen.

## Dateiformat .biblito

Projekte werden als `.biblito`-Datei gespeichert (ein ZIP mit Projektdaten, Plänen und Fotos) – dieselbe
Datei, die die iPhone-App exportiert und importiert. Wird eine Datei aus einer älteren Programmversion zum
ersten Mal gespeichert, legt BIB Lito vorher eine Sicherungskopie daneben:
`<Name>.vor-<alte Version>.biblito`.

## Keine Daten in der Cloud

Alle Projekte bleiben auf Ihrem Rechner. BIB Lito hat kein Konto und überträgt keine Projektdaten.
Die einzige Internetverbindung ist die Suche nach Updates in diesem Repository.

Der Quellcode ist nicht öffentlich; hier liegen nur die fertigen Programme.
