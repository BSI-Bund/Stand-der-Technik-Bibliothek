# Komponenten

Eine [OSCAL-Komponentendefinition](https://pages.nist.gov/OSCAL-Reference/models/v1.1.3/component-definition/) enthält eine Sammlung von Komponenten. Jede Komponente in einer Komponentendefinition beschreibt, wie eine bestimmte Implementierung einer Hardware, Software, eines Dienstes, einer Richtlinie, eines Prozesses oder einer Prozedur bestimmte Vorschriften aus einem oder mehreren OSCAL-Katalogen oder -Profilen unterstützen oder implementieren kann.

Durch die Veröffentlichung eines Komponentensatzes in einer Komponentendefinition können Produkt- und Serviceanbieter, Richtlinien- und Prozessverantwortliche und andere Personen Informationen über die Implementierung von Anforderungen für ein von ihnen verwaltetes Zielobjekt austauschen. So können Lösungsbeschreibungen für das Thema in System-Sicherheitspläne (SSP) der Institution importiert werden. Diese Informationen können dann bei der technischen oder organisatorischen Implementierung verwendet werden. So muss sich nicht jede Institution die Lösungen "aus den Fingern saugen", die sie zur Umsetzung von Vorschriften einsetzen möchte, sondern kann auf Konzepte und Vorlagen aufbauen.

Es ist wichtig zu beachten, dass Komponentendefinitionen keine _tatsächlichen_ Implementierungen sind; vielmehr _beschreiben_ Komponentendefinitionen eine Implementierung, die innerhalb eines Informationssystems eingesetzt werden kann. Beispielsweise könnte eine Komponente zur Transportverschlüsselung die Information "SSH über TLS 1.3 wird eingesetzt" enthalten. Somit dienen Komponentendefinitionen als **Referenzen** mit Inhalten, die (z. B. im SSP OSCAL-Modell) zur Entwicklung umfassender und konsistenter Implementierungen (wieder-)verwendet werden können. Sie ersetzen aber nicht das Handeln der für die Informationssicherheit verantwortlichen Stelle.

Mögliche Beispiele:
- TLS-Konfiguration
- Apache Webserver
- Debian Linux Betriebssystem Konfiguration
- Schulung für Endanwender

Das US-amerikanische NIST hat auch eine [Anleitung zum Erstellen einer Komponentendefinition](https://pages.nist.gov/OSCAL/learn/tutorials/implementation/simple-component-definition/) veröffentlicht.