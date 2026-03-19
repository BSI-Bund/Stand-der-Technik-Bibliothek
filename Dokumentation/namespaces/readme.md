# BSI Stand der Technik — Namespace-Definitionen

Dieses Verzeichnis enthält die **Namespace-Definitionsdateien** des *BSI Stand der Technik*-Frameworks.
Jede CSV-Datei definiert ein spezifisches kontrolliertes Vokabular (Namespace), das zur Beschreibung, Kategorisierung und Verknüpfung von Elementen innerhalb des Frameworks dient.

## 📁 Inhalt

Jede CSV-Datei entspricht einem eigenen Namespace:

| Datei                            | Beschreibung                                                          |
| -------------------------------- | --------------------------------------------------------------------- |
| `documentation_guidance.csv`     | Definitionen zu empfohlenen Dokumentationen                           |
| `result.csv`                     | Definitionen zu sonstigen in Anforderungen verwendeten Begriffen*     |
| `action_words.csv`               | Definitionen zu Handlungs- bzw. Tätigkeitsverben                      |
| `modal_verbs.csv`                | Definitionen zu Modalverben (Grad der Verpflichtung oder Möglichkeit) |
| `practices.csv`                  | Definitionen zu Praktiken oder Vorgehensweisen                        |
| `security_level.csv`             | Definitionen zu Sicherheitsniveaus                                    |
| `effort.csv`                     | Definitionen zu Aufwandsstufen                                        |
| `tags.csv`                       | Definitionen zu Schlagwörtern oder thematischen Labels                |
| `topics.csv`                     | Definitionen zu Themen (= Untergliederung von Praktiken)              |
| `target_object_categories.csv`   | Definitionen zu Zielobjektkategorien (z. B. IT-Systeme, Anwendungen)  |

(*) Anders als bei den anderen Namespace-Dokumenten darf im Ergebnis-Feld Freitext innerhalb der Satzschablone verwendet werden. Im Ergebnis verwendete Begriffe werden nur dann in der ergebnis.csv aufgenommen, wenn der Begriff weder im Duden noch in der deutschen Wikipedia definiert ist oder eine von der allgemeinen Definition abweichende Definition verwendet wird. Dies dient als Glossar zum Verständnis der Inhalte, nicht zu Validierung der erlaubten Feldinhalte. Dabei gilt ein Begriff auch dann als durch Duden oder Wikipedia definiert, wenn es sich um einen zusammengesetzten Begriff handelt, dessen Bestandteile alle bereits definiert sind.

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
