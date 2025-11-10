# Hilfsdateien für die Anforderungs- und Kontroll-Zuordnung

Dieses Verzeichnis enthält "reduzierte" Versionen der primären Kontrollkataloge, die für die Verarbeitung durch generative KI-Modelle optimiert sind. Der Hauptzweck dieser Dateien ist es, die Token-Anzahl zu reduzieren, um eine effizientere und kostengünstigere Analyse zu ermöglichen.

Alle Beschreibungen in den Dateien sind auf die ersten 150 Zeichen gekürzt.

## Zweck

Diese Dateien dienen als zentraler Kontext für einen umfangreichen, manuell ausgeführten KI-Job, dessen Ziel es ist, die "Prozessbausteine" den entsprechenden Kontrollen zuzuordnen. Der reduzierte Inhalt stellt sicher, dass das KI-Modell die relevantesten Informationen erhält, ohne durch überflüssige Details abgelenkt zu werden.

## Dateibeschreibungen

Die Dateien liegen im Markdown-Tabellenformat vor.

### `gpp_stripped.md`

Diese Datei enthält eine reduzierte Liste aller Kontrollen aus dem Grundschutz++ Kompendium.

- **Format:**
  | ID | name | description | UUID (only for G++ controls!) |
  |---|---|---|---|

### `bsi_2023_stripped.md`

Diese Datei enthält eine reduzierte Liste der BSI IT-Grundschutz-Anforderungen aus der Edition 2023. Die Liste ist gefiltert und enthält nur Anforderungen, die zu den technischen Bausteinen gehören (SYS, INF, IND, APP, NET).

- **Format:**
  | ID | name | description |
  |---|---|---|

### `bsi_2023_stripped_ISMS.md`

Diese Datei enthält die BSI IT-Grundschutz-Anforderungen, die zu den Prozessbausteinen gehören. Sie werden separat aufgeführt, um eine gezielte Verarbeitung zu ermöglichen.

- **Format:**
  | ID | name | description |
  |---|---|---|
