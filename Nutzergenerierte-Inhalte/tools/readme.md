# Tools der Stand-der-Technik-Bibliothek

Diese Sammlung enthält Werkzeuge zur Erstellung, Verwaltung und Dokumentation von **Systemsicherheitsprofilen (SSP)** im Kontext nutzergenerierter Inhalte. Die Tools sind webbasiert (HTML/JS) und ermöglichen einen durchgängigen Workflow von der Planung bis zur Zertifizierung.

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

# Roadmap & Geplante Erweiterungen

Die folgenden Komponenten befinden sich derzeit in der Planung, um den Zertifizierungszyklus zu schließen:

* **4. Plan of Action and Milestones (POA&M):** Automatisierte Ableitung von Maßnahmenplänen und Meilensteinen aus den im Audit (AR) identifizierten Schwachstellen.

---

## Technische Hinweise

* **Datenschutz:** Alle Tools arbeiten rein clientseitig. Es werden keine Daten an einen Server übertragen; die Speicherung erfolgt lokal über den JSON-Export.
* **Beiträge:** Fehler oder Verbesserungsvorschläge können über die [GitHub Issues](https://github.com/AG-3-Nutzergenerierte-Inhalte/Stand-der-Technik-Bibliothek/issues) gemeldet werden.
