# BSI Stand der Technik — Namespace-Definitionen

Dieses Verzeichnis enthält die **Namespace-Definitionsdateien** des *BSI Stand der Technik*-Frameworks.
Jede CSV-Datei definiert ein spezifisches kontrolliertes Vokabular (Namespace), das zur Beschreibung, Kategorisierung und Verknüpfung von Elementen innerhalb des Frameworks dient.

## 📁 Inhalt

Jede CSV-Datei entspricht einem eigenen Namespace:

| Datei                            | Beschreibung                                                          |
| -------------------------------- | --------------------------------------------------------------------- |
| `dokumentationsempfehlungen.csv` | Definitionen zu empfohlenen Dokumentationen                           |
| `ergebnis.csv`                   | Definitionen zu sonstigen in Anforderungen verwendeten Begriffen*     |
| `handlungsworte.csv`             | Definitionen zu Handlungs- bzw. Tätigkeitsverben                      |
| `modalverb.csv`                  | Definitionen zu Modalverben (Grad der Verpflichtung oder Möglichkeit) |
| `praktiken.csv`                  | Definitionen zu Praktiken oder Vorgehensweisen                        |
| `sicherheitsniveau.csv`          | Definitionen zu Sicherheitsniveaus                                    |
| `stufen.csv`                     | Definitionen zu Aufwandsstufen                                        |
| `tags.csv`                       | Definitionen zu Schlagwörtern oder thematischen Labels                |
| `themen.csv`                     | Definitionen zu Themen (= Untergliederung von Praktiken)              |
| `zielobjekte.csv`                | Definitionen zu Zielobjekten (z. B. IT-Systeme, Anwendungen)          |

(*) Im Ergebnis verwendete Begriffe werden in der ergebnis.csv aufgenommen, wenn der Begriff weder im Duden noch in der deutschen Wikipedia definiert ist oder eine von der allgemeinen Definition abweichende Definition verwendet wird. Dabei gilt ein Begriff auch dann als durch Duden oder Wikipedia definiert, wenn es sich um einen zusammengesetzten Begriff handelt, dessen Bestandteile alle bereits definiert sind.

---

## 📄 Dateiformat

Alle Dateien liegen im **CSV-Format (Comma-Separated Values)** vor und folgen den folgenden Formatvorgaben:

* **Kodierung:** UTF-8
* **Trennzeichen:** `,` (Komma)
* **Kopfzeile:** In jeder Datei vorhanden
* **Spaltenstruktur:** Je nach Namespace unterschiedlich, typischerweise jedoch mit

  * `uuid` — eindeutiger Bezeichner
  * `label` — lesbarer Name
  * `description` — kurze Beschreibung
  * (optional) `parent`, `related` oder andere semantische Felder je nach Namespace

Soweit vorhanden, werden Querverweise zwischen Namespaces über diese UUIDs hergestellt.

---

## 🧭 Zweck

Diese Dateien bilden die **grundlegenden Vokabulare** zur Modellierung, Analyse und Validierung von Sicherheitskonzepten im *BSI Stand der Technik*-Ökosystem.
Sie stellen semantische Konsistenz, Interoperabilität und Nachvollziehbarkeit über alle Vorschriften und Dokumentationen hinweg sicher.
