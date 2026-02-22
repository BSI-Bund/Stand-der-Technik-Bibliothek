# Tools der Stand-der-Technik-Bibliothek

Diese Sammlung enthält Werkzeuge zur Erstellung, Verwaltung und Dokumentation von **Systemsicherheitsprofilen (SSP)** im Kontext nutzergenerierter Inhalte. Die Tools sind webbasiert (HTML/JS) und ermöglichen einen durchgängigen Workflow von der Planung bis zur Zertifizierung.

Und es gibt auch eine Anwendung den Anwenderkatalog zu betrachten: [GSpp-Viewer.html](./GSpp-Viewer.html).

---

## Workflow-Übersicht

Der Prozess ist sehr einfach:

1. Modellierung mit [Blaupausen-Generator](./blaupausen_generator.html)
  * Erstellt ein Blaupause Profil
  * Das SSP dazu
  * Muster-Assets oder die eignen richtigen Assets
  * Risikoanalyse inkl Custom Controls ist enthalten
  * Anpassung der Controls (Text und Parameter) eingebaut

2. Grundschutzcheck mit [SSP-Ausfüllen](./ssp_ausfuellen.html) durchführen
   * Nach Ausfüllen abspeichern
   * Wenn man weiter daran arbeiten wil, einfach die eben gespeicherte Datei öffnen.
   * ist eine AI-enabled Anwendung:
     * man kann fragen wie das Control zu verstehen ist
     * welche Risiken bestehen
     * welche Anforderungen aus der BSI Grundschutz Edition 2023 einen bezug zu diesem Control haben

*Die anderen Dateien sind zwischenschritte, einfach Ignorieren.*

## Roadmap & Geplante Erweiterungen

Die folgenden Komponenten befinden sich derzeit in der Planung, um den Zertifizierungszyklus zu schließen:

* **3. Audit & Assessment Results (AR):** Ein Tool zur Durchführung von Audits (intern/extern). Es dient der Feststellung von Gaps und der Erstellung der Assessment Results.
* **4. Plan of Action and Milestones (POA&M):** Automatisierte Ableitung von Maßnahmenplänen und Meilensteinen aus den im Audit (AR) identifizierten Schwachstellen.

---

## Technische Hinweise

* **Datenschutz:** Alle Tools arbeiten rein clientseitig. Es werden keine Daten an einen Server übertragen; die Speicherung erfolgt lokal über den JSON-Export.
* **Beiträge:** Fehler oder Verbesserungsvorschläge können über die [GitHub Issues](https://github.com/AG-3-Nutzergenerierte-Inhalte/Stand-der-Technik-Bibliothek/issues) gemeldet werden.
