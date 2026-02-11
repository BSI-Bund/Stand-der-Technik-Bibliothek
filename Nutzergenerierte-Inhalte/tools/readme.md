# Tools der Stand-der-Technik-Bibliothek

Diese Sammlung enthält Werkzeuge zur Erstellung, Verwaltung und Dokumentation von **Systemsicherheitsprofilen (SSP)** im Kontext nutzergenerierter Inhalte. Die Tools sind webbasiert (HTML/JS) und ermöglichen einen durchgängigen Workflow von der Planung bis zur Zertifizierung.

Und es gibt auch eine Anwendung den Anwenderkatalog zu betrachten: [GSpp-Viewer.html](./GSpp-Viewer.html).

---

## Workflow-Übersicht

Der Prozess ist modular aufgebaut. Die folgende Grafik verdeutlicht das Zusammenspiel der einzelnen Werkzeuge:



### 1. Blaupausen erstellen (Optional)
Mit dem [Blaupausen-Generator](./blaupausen_generator.html) können Vorlagen für Sicherheitsanforderungen erstellt werden.
* **Status:** Funktional, aber derzeit noch nicht direkt im SSP-Generator importierbar.
* **Tracking:** [Issue #24](https://github.com/AG-3-Nutzergenerierte-Inhalte/Stand-der-Technik-Bibliothek/issues/24)

### 2. SSP Struktur generieren
Basierend auf den Anforderungen wird mit dem [SSP-Generator](./ssp_generator.html) das Grundgerüst des Systemsicherheitsprofils erstellt.

### 3. Risikoanalyse integrieren
Die spezifische Risikoanalyse für das System wird mit dem [Risikoanalyse-Tool](./risikoanalyse_profil_erstellen.html) durchgeführt und in das SSP eingebunden.

### 4. SSP finalisieren & Export
Im Tool [SSP-Ausfüllen](./ssp_ausfuellen.html) werden alle verbleibenden Details dokumentiert. Das Ergebnis wird als **JSON-Datei** gespeichert, um die Interoperabilität zu gewährleisten.

---

## Übersicht der Tools

| Schritt | Werkzeug | Status | Beschreibung |
| :--- | :--- | :--- | :--- |
| 1 | [Blaupausen-Generator](./blaupausen_generator.html) | `Optional` | Erstellung von Vorlagen für Sicherheitskontrollen. |
| 2 | [SSP-Generator](./ssp_generator.html) | `Aktiv` | Generierung der SSP-Grundstruktur. |
| 3 | [Risikoanalyse-Profil](./risikoanalyse_profil_erstellen.html) | `Aktiv` | Erstellung und Einbau von Risikoprofilen. |
| 4 | [SSP-Ausfüllen](./ssp_ausfuellen.html) | `Aktiv` | Datenpflege und JSON-Export des fertigen SSP. |

---

## Roadmap & Geplante Erweiterungen

Die folgenden Komponenten befinden sich derzeit in der Planung, um den Zertifizierungszyklus zu schließen:

* **5. Audit & Assessment Results (AR):** Ein Tool zur Durchführung von Audits (intern/extern). Es dient der Feststellung von Gaps und der Erstellung der Assessment Results.
* **6. Plan of Action and Milestones (POA&M):** Automatisierte Ableitung von Maßnahmenplänen und Meilensteinen aus den im Audit (AR) identifizierten Schwachstellen.

---

## Technische Hinweise

* **Datenschutz:** Alle Tools arbeiten rein clientseitig. Es werden keine Daten an einen Server übertragen; die Speicherung erfolgt lokal über den JSON-Export.
* **Beiträge:** Fehler oder Verbesserungsvorschläge können über die [GitHub Issues](https://github.com/AG-3-Nutzergenerierte-Inhalte/Stand-der-Technik-Bibliothek/issues) gemeldet werden.
