# Pilotierung Grundschutz++

Der **Grundschutz++** ist eine umfassende Überarbeitung des bisherigen IT-Grundschutzes des Bundesamtes für Sicherheit in der Informationstechnik (BSI). Ziel dieser Weiterentwicklung ist es, die Inhalte zu modernisieren und den Aufwand für die Umsetzung eines Informationssicherheitsmanagementsystems (ISMS) zu reduzieren—insbesondere durch die Automatisierung wesentlicher Prozesse. 

-----

## Anleitung zum Öffnen der OSCAL-Dateien 

Diese Anleitung zeigt Ihnen, wie Sie die bereitgestellten OSCAL-Dateien (im JSON- und XML-Format) herunterladen und mit einem kompatiblen Werkzeug betrachten können.

Die OSCAL-Dateien werden in zwei Varianten zur Verfügung gestellt: einmal ohne Signatur und einmal mit einer Signatur. Die signierten Dateien stehen im Unterordner `(signed)` zur Verfügung.

Inhaltlich unterscheiden sich beide Varianten **nicht** von einander und können als identisch angesehen werden. Die signierten OSCAL-Dateien sind durch eine Signatur gekennzeichnet, die Programmen hilft die richtige Zeichencodierung leichter zu erkennen, ohne dass sie bspw. bei XML-Dateien den XML-Prolog interpretieren müssen und damit insgesamt Vorteile zur verbesserten Fehlervermeidung bei der Verarbeitung von Unicode-Daten plattformübergreifend bieten. Es gilt zu beachten, dass beim Stand der Technik nicht alle Programme signierte OSCAL-Dateien problemlos akzeptieren.

### Schritt 1: OSCAL-Dateien herunterladen

Sie können die OSCAL-Dateien direkt von diesem GitHub-Repository herunterladen. Die Dateien liegen in den Formaten **JSON** (`.json`) und **XML** (`.xml`) vor.

1.  **Wählen Sie ein Dateiformat aus:** Die Dateien werden in den Formaten json und xml bereitgestellt. Klicken Sie auf die gewünschte Datei links im Verzeichnisbaum.
2.  **Laden Sie die Rohfassung herunter:** Klicken Sie auf der sich öffnenden Seite auf den Button **"Raw"**. Klicken Sie anschließend mit der rechten Maustaste in das Browserfenster und wählen Sie "Speichern unter...", um die Datei lokal auf Ihrem Computer zu sichern.

-----

### Schritt 2: OSCAL-kompatible Anwendung verwenden

Kompendien können mit beliebigen JSON- oder XML-kompatiblen Anwendungen geöffnet werden. Um die heruntergeladenen Dateien in einem benutzerfreundlichen Format zu betrachten, empfehlen wir die Nutzung eines spezialisierten [OSCAL-Werkzeugs](https://oscal.io/tools/#:~:text=OSCAL%20Viewer,Geoffrey%20Borough) je nachdem wofür Sie die Datei verwenden möchten.

## Weiterführende Informationen

Für weitere Informationen besuchen Sie die [Webseiten für den IT-Grundschutz](https://www.bsi.bund.de/DE/Themen/Unternehmen-und-Organisationen/Standards-und-Zertifizierung/IT-Grundschutz/it-grundschutz_node.html) des BSI.
