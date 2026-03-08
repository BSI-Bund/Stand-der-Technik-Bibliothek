# Tools der Stand-der-Technik-Bibliothek

Diese Sammlung enthält Werkzeuge zur Erstellung, Verwaltung und Dokumentation von **Systemsicherheitsprofilen (SSP)** im Kontext nutzergenerierter Inhalte. Die Tools sind webbasiert (HTML/JS) und ermöglichen einen durchgängigen Workflow von der Planung bis zur Zertifizierung und dem Abarbeiten der Festellungen.

Und es gibt auch eine Anwendung den Anwenderkatalog zu betrachten: [GSpp-Viewer.html](./GSpp-Viewer.html).

---

## Workflow-Übersicht

# Workflow-Übersicht: G++ Compliance Management

Der Prozess folgt einer klaren Kette von der Modellierung über die Umsetzung bis hin zur finalen Prüfung.

### 1. Modellierung mit dem [Blaupausen-Generator](./blaupausen_generator.html)
In dieser Phase legen Sie das Fundament für Ihren Informationsverbund.
* **Profil-Erstellung**: Das Tool generiert ein OSCAL-Profil auf Basis des gewählten ISMS-Typs.
* **Asset-Management**: Sie integrieren Muster-Assets oder laden eigene Zielobjekte direkt aus der GitHub-Bibliothek.
* **Risikoanalyse**: Die Anwendung enthält ein integriertes Risikomanagement inklusive der Erstellung von Custom Controls.
* **Tailoring**: Sie passen Anforderungstexte und Parameter (z. B. Fristen oder Rollen) bereits hier an die lokale Situation an.
* **Export**: Sie erhalten die Blaupause als Profil und einen darauf basierenden Muster-SSP.

### 2. Grundschutzcheck mit [SSP-Ausfüllen](./ssp_ausfuellen.html)
Hier dokumentieren Sie die tatsächliche Umsetzung der Maßnahmen im Betrieb.
* **Umsetzungsstatus**: Sie erfassen den Status (z. B. "umgesetzt", "geplant") sowie Verantwortliche und Termine für jedes Control.
* **Workspace-Konzept**: Sie können begonnene Arbeiten jederzeit speichern und durch Laden der bearbeiteten JSON-Datei fortsetzen.
* **AI-Assistent**: Die Anwendung nutzt KI-Unterstützung für tiefere Einblicke:
    * **Verständnis**: Erklärungen helfen, komplexe Control-Texte zu interpretieren.
    * **Risikofokus**: Die KI zeigt Gefahren bei Nicht-Umsetzung auf.
    * **Referenzierung**: Das Tool mappt Anforderungen auf die BSI Grundschutz Edition 2023.

### 3. Audit & Reporting mit [Assessment Plan & Results](./pruefung_ap_ar.html)
Die letzte Phase dient der formalen Prüfung und dem Nachweis der Compliance.
* **Prüfplanung (AP)**: Sie erstellen einen Assessment Plan, der Zeitpläne, Assessoren und die gewählten Prüfmethoden (Dokumentenprüfung, Interview, Test) festlegt.
* **Durchführung**: Sie bewerten die im SSP dokumentierte Umsetzung und halten Befunde (satisfied/not-satisfied) fest.
* **KI-Audit-Support**: 
    * **Befundvorschlag**: Die KI analysiert den SSP-Eintrag und schlägt eine Bewertung vor.
    * **Reifegrade**: Der Assistent generiert Prüfungshandlungen für verschiedene Reifegrade.
* **Ergebnis-Export (AR)**: Sie generieren die formalen Assessment Results (AR) als Beleg für die Wirksamkeit Ihres ISMS.

### 4. Feststellungen Abarbeiten: [POA&M-Generator](./abarbeiten_POAM_generator.html)
Das Tool überführt ungelöste Mängel in einen verbindlichen Maßnahmenplan, damit keine Sicherheitslücke unbehandelt bleibt.
* **Mängel-Import**: Sobald du die Assessment Results lädst, übernimmt die Anwendung automatisch alle nicht erfüllten Controls.
* **Meilenstein-Planung**: Du legst detaillierte Phasenpläne fest, damit die Sanierung der Schwachstellen termingerecht erfolgt.
* **Dashboard**: Du behältst überfällige Deadlines und den allgemeinen Fortschritt der Mängelbeseitigung permanent im Blick.

# Kurzanleitung: Informationsverbund erstellen (Modellieren, Strukturanalyse, Risiko Analyse - OSCAL Blaupausen Generator)

### 1. Metadaten festlegen
* Trage Titel, Version und Zweck deiner Blaupause ein.
* Das Tool übernimmt diese Angaben direkt in die Metadaten des späteren OSCAL-Profils.

### 2. ISMS & Assets wählen
* Wähle ein Basis-ISMS (Standard oder Enhanced), um die Pflicht-Controls zu laden.
* Importiere Muster-Assets aus der GitHub-Bibliothek, wodurch die App deren Anforderungen automatisch extrahiert.

### 3. Tailoring (Anpassung)
* Nutze den Button "⚙️ Modify", um Parameter-Werte innerhalb der Controls zu definieren.
* Ergänze eigene Texte am Anfang oder Ende der Original-Anforderungen, um lokale Besonderheiten abzubilden.
* Füge zusätzliche Control-IDs bei Bedarf manuell hinzu.

### 4. Risikoanalyse durchführen
* Erstelle Risiko-Einträge und ordne diese entweder dem gesamten System oder spezifischen Assets zu.
* Verknüpfe mitigierende Maßnahmen aus dem Katalog oder erstelle eigene "Custom Controls".

### 5. OSCAL-Paket exportieren
* Aktiviere optional das Häkchen für den Muster-SSP (System Security Plan).
* Klicke auf "Paket generieren", um die resultierenden JSON-Dateien für Profil und SSP herunterzuladen.

# Kurzanleitung: Anforderungen Ausfüllen (Basissicherheitscheck - OSCAL SSP Editor & Workspace)

Dieses Tool dient der detaillierten Bearbeitung von **System Security Plans (SSP)**. Es ermöglicht die Dokumentation der Umsetzung von Sicherheitsmaßnahmen (Controls) für spezifische Komponenten.

### 1. Workspace initialisieren
* **SSP laden**: Lade deine zentrale SSP-JSON-Datei hoch.
* **Assoziierte Dateien**: Lade Profile, Kataloge oder Komponenten-Definitionen hoch, um den Workspace mit Inhalten (Anforderungstexten, Parametern) zu füllen.
* **Status-Check**: Das Tool zeigt im Bereich "Ressourcen-Status" an, ob alle referenzierten Dateien korrekt geladen wurden oder ob Quellen fehlen.

### 2. KI-Assistent konfigurieren (Optional)
* Hinterlege einen **Gemini API Key**, um intelligente Unterstützung zu erhalten.
* Definiere einen **System Kontext** (z. B. "Wir sind ein KRITIS-Unternehmen"), damit die KI-Vorschläge auf deine Organisation zugeschnitten sind.
* Du kannst generierte KI-Antworten exportieren und importieren, um sie ohne erneute API-Kosten zu teilen.

### 3. Navigation & Filter
* Nutze die **Globalen Filter**, um Controls nach Umsetzungsstatus (z. B. "Offen", "Geplant"), Kritikalität (CIA) oder Dokumentationspflicht zu sortieren.
* Die **Suche** erlaubt das schnelle Auffinden von Control-IDs oder Stichworten über alle Komponenten hinweg.

### 4. Umsetzung dokumentieren (Implementation)
* **Status & Details**: Wähle pro Maßnahme den Umsetzungsstatus und trage Bearbeiter sowie Datum ein.
* **Reifegrade**: Wähle bei Bedarf vordefinierte Umsetzungs-Level (Statements) aus, um die Beschreibung automatisch zu füllen.
* **KI-Features**:
    * **Umsetzungsvorschlag**: Generiert konkrete Praxisbeispiele.
    * **Risikoanalyse**: Zeigt Gefahren bei Nicht-Umsetzung auf.
    * **Edition 2023**: Mappt die G++ Maßnahme auf das klassische IT-Grundschutz-Kompendium.

### 5. Parameter & Risiken
* **Parameter**: Trage Werte für Platzhalter (z. B. Zeitfristen, Rollen) direkt ein. Das Tool erkennt, ob Werte aus dem Profil übernommen oder lokal überschrieben wurden.
* **Risikoanalyse**: Das Tool extrahiert identifizierte Risiken aus dem SSP und verknüpft sie direkt mit den mitigierenden Maßnahmen.

### 6. Speichern
* Klicke auf **SSP speichern**, um das vollständig ausgefüllte Sicherheitskonzept als OSCAL-konforme JSON-Datei herunterzuladen.

# Kurzanleitung: Audit Planen und Durchführen (OSCAL Assessment Plan & Results Generator)

Dieses Tool dient der Auditierung und Prüfung von Sicherheitskonzepten. Es transformiert einen System Security Plan (SSP) in formale Prüfpläne (**Assessment Plan**) und dokumentiert die Ergebnisse (**Assessment Results**) im OSCAL-Format.

### 1. Import & Initialisierung
* **SSP laden**: Importiere deine ausgefüllte `*_SSP-edited.json`. Das Tool extrahiert automatisch alle Controls, den Umsetzungsstatus und die beteiligten Komponenten.
* **Katalog & Defs**: Die Anwendung lädt im Hintergrund den Grundschutz++ Katalog sowie externe Komponentendefinitionen (Defs), um Reifegrade und Prüfhinweise anzuzeigen.
* **Session laden**: Über die "Session laden"-Funktion kannst du einen bereits begonnenen Prüfprozess jederzeit fortsetzen.

### 2. Rahmenbedingungen festlegen
* **Metadaten & Assessor**: Hinterlege Titel, Version und die Kontaktdaten des Prüfers.
* **Zeitplan & Methodik**: Definiere den Prüfzeitraum sowie die *Rules of Engagement* (ROE) und die angewandte Audit-Methodik.
* **Tasks**: Erstelle spezifische Aufgaben oder Meilensteine für das Audit-Team.

### 3. Durchführung der Prüfung (Audit)
* **Scope-Management**: Wähle aus, welche Controls geprüft werden. Du kannst einzelne Maßnahmen ein- oder ausschließen.
* **Prüfmethoden**: Weise jedem Control eine oder mehrere Methoden zu: **EX** (Examine/Dokumentenprüfung), **IN** (Interview) oder **TE** (Test).
* **Befunde erfassen**: Dokumentiere für jedes Control:
    * **Status**: Erfüllt (satisfied), Nicht erfüllt (not-satisfied) oder Sonstiges.
    * **Beobachtung**: Beschreibe deine Feststellungen während der Prüfung.
    * **Risiko**: Formuliere bei Nicht-Erfüllung das resultierende Risiko.

### 4. KI-Audit-Assistenz
* **Befundvorschlag (🤖)**: Die KI analysiert den SSP-Eintrag sowie die Reifegrade und schlägt einen passenden Prüfbefund vor.
* **Control-Erklärung (📖)**: Die KI erläutert die Anforderung, definiert 5 Reifegrade und schlägt konkrete Prüfungshandlungen (Nachweise, Fragen, Tests) vor.

### 5. Export der Ergebnisse
* **Session speichern**: Sichere den aktuellen Arbeitsstand inklusive aller KI-Analysen in einer Session-Datei.
* **AP exportieren**: Erzeuge den *Assessment Plan*, der den Prüfumfang und die geplanten Aktivitäten beschreibt.
* **AR exportieren**: Erzeuge die *Assessment Results*, die alle Befunde, Beobachtungen und Risiken für das offizielle Reporting enthalten.

# Kurzanleitung: Beheben der Feststellungen (OSCAL POA&M Generator)

Dieses Werkzeug schließt die Lücke zwischen der Feststellung von Mängeln und ihrer systematischen Behebung. Es überführt die Ergebnisse aus dem Assessment direkt in einen verbindlichen Maßnahmenplan.

### 1. Datenimport und Initialisierung
* **AR laden**: Importieren Sie die Datei `*_AR.json`, um alle Befunde in den POA&M zu überführen.
* **Automatische Erfassung**: Die Anwendung identifiziert sofort alle als "nicht erfüllt" (not-satisfied) markierten Befunde und legt dafür POA&M-Items an.
* **Session-Verwaltung**: Speichern Sie Ihren Arbeitsstand regelmäßig als Session-Datei, um die Planung später nahtlos fortzusetzen.

### 2. Metadaten und Zuständigkeiten
* **Verantwortlichkeiten**: Hinterlegen Sie Namen und E-Mail der verantwortlichen Personen, etwa des ISSO oder System Owners.
* **Stammdaten**: Passen Sie Titel und Version des Plans an, wobei das Tool den Systemnamen bereits aus dem AR übernimmt.

### 3. Maßnahmenplanung und Überwachung
* **Priorisierung**: Ordnen Sie jeder Maßnahme eine Priorität (Hoch, Mittel, Niedrig) zu, um die Ressourcensteuerung zu optimieren.
* **Status-Tracking**: Verfolgen Sie den Fortschritt von "Offen" über "In Arbeit" bis hin zum Abschluss.
* **Fristenmanagement**: Setzen Sie Deadlines für jede Aufgabe. Das Dashboard warnt Sie visuell bei Überfälligkeit.
* **Abweichungen**: Dokumentieren Sie Begründungen für Risikoakzeptanz oder genehmigte Abweichungen direkt am betroffenen Item.

### 4. KI-gestützte Sanierung (🤖)
* **Vorschlag zur Behebung**: Die KI analysiert Anforderung und Risiko, um einen konkreten Text für die Mängelbeseitigung zu formulieren.
* **Meilenstein-Planer**: Lassen Sie die KI einen zeitlichen Phasenplan mit konkreten Meilensteinen für die Umsetzung erstellen.

### 5. Export
* **POA&M-Datei**: Generieren Sie die finale `*_POAM.json`. Diese enthält alle Maßnahmen, Meilensteine und Risikoprotokolle im OSCAL-Standard.

---
# Daten-Management-Guide: Die OSCAL-Toolchain

Verwalte deine OSCAL-Daten wie einen Staffellauf. Jedes Werkzeug übergibt den Stab an das nächste, damit deine Compliance-Kette lückenlos bleibt.

---

## 1. Die Ordnerstruktur
Trenne die Phasen deines Projekts konsequent. Lege vier nummerierte Verzeichnisse an, da diese Struktur den Lebenszyklus deines Informationsverbunds widerspiegelt.

* **01_Modellierung**: Reserviere diesen Ordner für Profile und initiale SSPs aus dem Blaupausen-Generator.
* **02_Umsetzung**: Speichere hier deinen aktiv bearbeiteten SSP sowie die zugehörigen KI-Cache-Exporte.
* **03_Audit**: Dieses Verzeichnis nimmt den Assessment Plan (AP), die Assessment Results (AR) und die Audit-Sessions auf.
* **04_Sanierung**: Hier verwaltest du den Plan of Action and Milestones (POA&M) und die Sanierungs-Sessions.

---

## 2. Der Dateifluss (Input/Output-Matrix)

Halte dich strikt an diese Übergabepunkte. Falls du die Namen der exportierten JSON-Dateien manuell änderst, riskierst du kaputte interne Referenzen (href) innerhalb des Workspace.

| Phase | Werkzeug | Input | Output (Beispielname) |
| :--- | :--- | :--- | :--- |
| **1. Modell** | Blaupausen-Generator | (Katalog-URL) | `*_Profile.json`, `*_SSP.json` |
| **2. Umsetzung** | SSP-Ausfüllen | `*_SSP.json` + `*_Profile.json` | `*_SSP-edited.json` |
| **3. Audit** | Assessment Plan/Results | `*_SSP-edited.json` | `*_AP.json`, `*_AR.json` |
| **4. Sanierung** | POA&M Generator | `*_AR.json` | `*_POAM.json` |

---

## 3. Goldene Regeln für den Workspace

* **Sessions sind Pflicht**: Nutze im Audit- und POA&M-Tool konsequent die Funktion **Session speichern**. Nur die Session-Datei enthält deine gesamten Bearbeitungsstände inklusive aller Kommentare und KI-Analysen.
* **KI-Cache sichern**: Exportiere im SSP-Tool regelmäßig deinen KI-Cache. Du vermeidest dadurch, dass bei einem Browser-Reset bereits generierte KI-Antworten verloren gehen und Kosten für eine erneute Anfrage verursachen.
* **Referenz-Integrität**: Lade im Audit-Tool zwingend die `*_SSP-edited.json`, damit die Anwendung die dokumentierten Umsetzungsdetails gegen den Katalog prüfen kann.
* **Keine manuellen Datei-Eingriffe**: Bearbeite die JSON-Dateien niemals händisch in einem Texteditor. Nutze ausschließlich die grafischen Editoren, um die OSCAL-Konformität zu wahren.
---

## Technische Hinweise

* **Datenschutz:** Alle Tools arbeiten rein clientseitig. Es werden keine Daten an einen Server übertragen; die Speicherung erfolgt lokal über den JSON-Export.
* **Beiträge:** Fehler oder Verbesserungsvorschläge können über die [GitHub Issues](https://github.com/AG-3-Nutzergenerierte-Inhalte/Stand-der-Technik-Bibliothek/issues) gemeldet werden.
