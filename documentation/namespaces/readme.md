# Namespace-Definitionen

Dieses Verzeichnis enthält kontrollierte Vokabulare und ergänzende
Begriffsdefinitionen der Stand der Technik Bibliothek. Sie dienen der
einheitlichen Beschreibung, Kategorisierung und Verknüpfung
maschinenlesbarer Inhalte.

## Inhalt

| Datei | Beschreibung |
| --- | --- |
| `action_words.csv` | Handlungs- und Tätigkeitsverben |
| `basethreats.csv` | Grundlegende Gefährdungen |
| `documentation_guidelines.csv` | Empfehlungen zur Dokumentation |
| `effort_level.csv` | Aufwandsstufen |
| `modal_verbs.csv` | Modalverben und der damit ausgedrückte Grad der Verpflichtung |
| `practices.csv` | Praktiken und Vorgehensweisen |
| `result.csv` | Sonstige in Anforderungen verwendete Begriffe |
| `security_level.csv` | Sicherheitsniveaus |
| `security_targets.csv` | Schutzziele |
| `security_targets_levels.csv` | Wirkungsstufen einer Anforderung auf ein Schutzziel |
| `tags.csv` | Schlagwörter und thematische Kennzeichnungen |
| `target_object_categories.csv` | Zielobjektkategorien |
| `topics.csv` | Themen zur Untergliederung von Praktiken |
| `dependency.txt` | Definition einer Abhängigkeit zwischen Anforderungen |
| `enhancement.txt` | Definition einer Verbesserung einer Anforderung |
| `related.txt` | Definition einer Verwandtschaft zwischen Anforderungen |

Im Ergebnisfeld der Satzschablone darf Freitext verwendet werden. Ein Begriff
wird nur dann in `result.csv` aufgenommen, wenn er weder im Duden noch in der
deutschen Wikipedia definiert ist oder hier mit einer abweichenden Bedeutung
verwendet wird. Das Vokabular dient daher als Glossar und nicht als
abschließende Liste zulässiger Feldinhalte.

## Dateiformate

Die CSV-Dateien sind UTF-8-kodiert, verwenden ein Komma als Trennzeichen und
enthalten jeweils eine Kopfzeile. Ihre Spalten richten sich nach dem
jeweiligen Namespace. Soweit vorhanden, werden Begriffe und Querverweise über
UUIDs eindeutig zugeordnet.

Die TXT-Dateien enthalten ergänzende Begriffsdefinitionen als UTF-8-kodierten
Text.

## Zweck

Die Namespace-Dateien unterstützen eine konsistente und nachvollziehbare
Modellierung der Inhalte innerhalb der Stand der Technik Bibliothek.
