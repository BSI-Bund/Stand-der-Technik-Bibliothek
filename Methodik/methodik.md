                                                                                                                                                    Diskussionspapier zur Modernisierung der Methodik-Grundschutz \++ 

Datum: Januar 2026

	

Änderungshistorie

| *Version* | *Datum* | *Name* | *Beschreibung* |
| ----- | ----- | ----- | ----- |
| 0.1 | 01.07.2025 | BSI | Erstellung des ersten Entwurfs |
| 0.2 | 26.08.2025 | BSI | Konkretisierung auf der Grundlage der BSI internen Kommentierung |
| 0.3 | 27.0820.25 | BSI | Einarbeitung Kommentare |
| 0.4 | 27.08.2025 | BSI | Ergänzung und QS |
| 0.5 | 04.09.2025 | BSI | BSI interne Kommentierung  |
| 0.6 | 15.10.2025 | BSI | Einarbeitung Kommentare \+ Neuausrichtung Strukturmodellierung |
| 0.7 | 05.12.2025 | BSI | Einarbeitung Kommentare, Verschlankung und Umstrukturierung der Kapitel, Entfall von Beispielen |
| 0.7.1 | 05.12.2025 | BSI | Ausarbeitung Assetmodellierung |
| 0.7.2 | 05.12.2025 | BSI | Einarbeitung Kommentare S 1 und S 3 |
| 0.7.3 | 06.01.2026 | BSI | Umstrukturierung des Kapitels 4 Anforderungsanalyse und Einarbeitung der Kommentierungen der Community aus Version 0.7  Zusätzliche wurde der Begriff Kompendium-GS++ gestrichen |
| 0.8 | 07.01.2026 | BSI | Einarbeitung Kommentare Community |

*Tabelle 1: Änderungshistorie*

Bundesamt für Sicherheit in der Informationstechnik   
Postfach 20 03 63  
53133 Bonn  
Tel.: \+49 22899 9582- 0  
Stand-der-Techink@bsi.bund.de  
Internet: [https://www.bsi.bund.de](https://www.bsi.bund.de)  
© Bundesamt für Sicherheit in der Informationstechnik 2025

Inhalt
# Einleitung und Zielsetzung
## Hintergrund und Motivation

Die Entwicklung des Grundschutz++ (GS++) ist ein konsequenter Schritt in der Evolution des Grundschutzes des BSI als Reaktion auf die sich wandelnde Informationssicherheitslandschaft. Basierend auf umfangreichen praktischen Erfahrungen und dem Feedback zahlreicher Anwenderinnen und Anwender wurden in der bisherigen IT-Grundschutz-Methodik verschiedene Herausforderungen identifiziert. 

Dieses Dokument beschreibt den Prozess der Methodik-Grundschutz++ und gibt somit eine Anleitung ein ISMS für die eigene Institution aufzubauen und fortzuentwickeln. Es enthält aber keine Erläuterungen oder Beispiele zur Umsetzung.
## Zielgruppen und Anwendungsbereiche

Die Methodik-GS++ richtet sich an ein breites Spektrum von Institutionen und berücksichtigt deren unterschiedliche Ausgangslagen, Ressourcen und Bedürfnisse:

**Kleine Institutionen** profitieren von einem schlanken Einstieg in das systematische Informationssicherheitsmanagement. Die Methodik ermöglicht es, mit begrenzten personellen und zeitlichen Ressourcen ein Sicherheitsniveau gemäß Stand der Technik (SdT) zu etablieren. Langfristig empfehlen wir die toolgestützte Umsetzung.

**Mittlere Institutionen** können durch teilweise Automatisierung und skalierbare Prozesse effizienter arbeiten. Die Methodik unterstützt sowohl den manuellen als auch den teilautomatisierten Betrieb des ISMS und bietet praxisorientierte Ansätze für den schrittweisen Ausbau des Sicherheitsniveaus.

**Große Institutionen** mit komplexen IT-Landschaften können durch weitreichende Automatisierungsmöglichkeiten und die nahtlose Integration mit bestehenden Management- und Sicherheitssystemen erhebliche Effizienzgewinne erzielen. Die Methodik unterstützt verteilte Zuständigkeiten und ist auf große Informationsverbünde anwendbar.

Die Methodik-GS++ ist branchenübergreifend konzipiert und berücksichtigt sowohl die Anforderungen der Wirtschaft als auch die der öffentlichen Verwaltung. 
## Konzeptstruktur

Das vorliegende Diskussionspapier zur Methodik-GS++ stellt eine Basisversion mit allen notwendigen und relevanten Grundinformationen dar, welche das methodische Vorgehen zur Etablierung und Umsetzung eines Informationssicherheitsmanagementprozesses erforderlich macht.

Dieses Basisdokument kann in Kombination mit weiteren Layern, welche als eine Ergänzung einzelner Teilaspekte der Basisversion zu sehen sind, verwendet werden. Jeder Layer betrachtet dabei einen ganz spezifischen Aspekt der Erweiterung. So wird der Technik-Layer konkrete Informationen zum Umgang mit der Bildung von Anforderungspaketen auf Basis der in OSCAL vorhandenen Techniken erläutern. Die Kombination der Basisversion mit dem Technik-Layer soll den Umgang der Anwendung der Methodik-GS++ mittels Blaupausen verständlich beschreiben. Zusätzlich zum Technik-Layer ist angedacht einen Beispiel-Layer zu generieren, der einzelne Passagen der Basisversion mit Beispielen hinterlegt und somit für Verständlichkeit in unterschiedlichen Kontexten sorgt.

Neben diesen Layerdokumenten, welche in einer Art Overlaykonzept miteinander kombiniert werden können wird es weitere ergänzende Dokumente und Hilfsmittel geben. Hierzu zählen das Dokument zur Risikoanalyse, Curriculum für Schulungen und Migrationsleitfäden.
## Überblick über den Sicherheitsprozess nach GS++

Der Prozess der Methodik-GS++ enthält folgende Prozessschritte, die jeweils Praktiken in der Stand-der-Technik-Bibliothek entsprechen:

* Prozessschritt 1 – Erhebung und Planung – (Plan, Praktik: Governance und Compliance)  
* Prozessschritt 2 – Anforderungsanalyse (Plan, Praktik: Strukturmodellierung)  
* Prozessschritt 3 – Realisierung (Do, Praktik: Umsetzung)  
* Prozessschritt 4 – Überwachung (Check, Praktik: Monitoring und Evaluation)  
* Prozessschritt 5 – Verbesserung (Act, Praktik: Verbesserung)

Folgende Abbildung gibt einen Überblick über die Prozessschritte der Methodik-GS++ und die zugehörigen ISMS-Praktiken.
### Überblick Prozessschritt 1 – Erhebung und Planung

Der Prozessschritt 1 ermöglicht, dass Informationssicherheitsstrategien mit den übergeordneten Zielen der Institution und regulatorischen Anforderungen im Einklang stehen. Sie vereint die strategische Steuerung der Informationssicherheit mit der systematischen Identifikation und Integration externer sowie interner Anforderungen.

Dieser Prozessschritt definiert den strategischen Rahmen für die Informationssicherheit und beantwortet die Fragen nach dem 'Was' und 'Warum' von Anforderungen. Die Einbindung der Institutionsleitung in wichtige Entscheidungen zur Informationssicherheit ist somit gewährleistet und stellt sicher, dass alle relevanten gesetzlichen, regulatorischen und vertraglichen Vorgaben identifiziert und berücksichtigt werden.

Während der Prozessschritt 1 – „Erhebung und Planung“ die strategische Ausrichtung und die Anforderungen definiert, übernehmen die Prozessschritte 2 und 3 die konkrete Ausgestaltung.
### Überblick Prozessschritt 2 – Anforderungsanalyse

Der Prozessschritt 2 bildet die Grundlage für eine systematische Analyse der Informationssicherheit einer Institution. Die Prozessschritte bauen aufeinander auf, können aber iterativ oder parallel abgearbeitet werden.

Dabei werden zunächst die für den Geltungsbereich relevanten Geschäftsprozesse identifiziert. Diese werden anschließend ihrer Kritikalität nach priorisiert. Mit dem wichtigsten Geschäftsprozess beginnend erfolgt die Erfassung der für den Prozess relevanten Assets, welche anschließend den entsprechenden Zielobjekten zugeordnet werden.

Mit diesen Informationen ausgestattet kann die Zusammenstellung passender Anforderungen anhand der betroffenen Praktiken und Zielobjekte beginnen. Dabei wird ein Anforderungspaket für den Informationsverbund als Ganzes, für das ISMS relevante Prozesse anhand von Praktiken, sowie Listen für die einzelnen Zielobjekte erstellt.

Ziel des Prozessschrittes 2 ist es, ein individuelles Anforderungspaket für die Institution zu generieren. Mit der Zuordnung einzelner Praktiken und Zielobjekte erfolgt eine Auswahl von Anforderungen auf der Grundlage des vorgegebenen Sicherheitsniveaus. Eine Erweiterung des Anforderungspakets durch spezifische Anforderungen erhöht die Flexibilität. Für diese Anforderungen ist eine Risikobetrachtung erforderlich.

Der Prozessschritt 2 liefert essentielle Eingangsdaten für die nachgelagerten Prozessschrittes und ermöglicht eine zielgerichtete und risikoorientierte Planung von Anforderungen und Maßnahmen.
### Überblick Prozessschritt 3 – Realisierung

Der Prozessschritt 3 sorgt für die systematische Planung, Umsetzung und Dokumentation von Anforderungen bzw. der Maßnahmen, die aus Prozessschritt 2 und der Risikobewertung abgeleitet wurden. Sie stellt sicher, dass identifizierte Sicherheitsanforderungen effektiv in die organisatorischen und technischen Prozesse integriert werden.

Dieser Prozessschritt 3 umfasst die detaillierte Planung von Maßnahmen, die Festlegung von Zuständigkeiten und Zeitplänen sowie die Bereitstellung notwendiger Ressourcen. Zudem beinhaltet sie die Nachverfolgung der Umsetzung und die Dokumentation der umgesetzten Anforderungen und Maßnahmen.

Während der Prozessschritt 2 die notwendigen Anforderungen identifiziert und der Prozessschritt 4 die Wirksamkeit der Maßnahmen überprüft, konzentriert sich Prozessschritt 3 auf die effiziente und effektive Realisierung der erforderlichen Maßnahmen.
### Überblick Prozessschritt 4 – Überwachung

Der Prozessschritt 4 stellt durch regelmäßige Überwachung und systematische Bewertung sicher, dass die implementierten Anforderungen wirksam sind und die Sicherheitsziele der Institution erreicht werden. Er liefert Erkenntnisse über den aktuellen Sicherheitszustand und identifiziert Verbesserungspotentiale.

Im Rahmen dieses Prozessschrittes werden regelmäßige Sicherheitsaudits, kontinuierliches Monitoring von Sicherheitsereignissen sowie periodische Überprüfungen und Bewertungen des ISMS durchgeführt. 

Die Ergebnisse des Prozessschrittes 4 fließen direkt in den Prozessschritt 5 ein, wo konkrete Maßnahmen zur Behebung identifizierter Schwachstellen und zur kontinuierlichen Verbesserung des ISMS abgeleitet werden.
### Überblick Prozessschritt 5 – kontinuierliche Verbesserung

Der Prozessschritt 5 gewährleistet die kontinuierliche Weiterentwicklung und Optimierung des ISMS. Er nutzt die Erkenntnisse aus dem Monitoring und der Evaluation, um die Wirksamkeit der Maßnahmen zu erhöhen.

Dieser Prozessschritt umfasst die Planung und Umsetzung von Korrektur- und Vorbeugungsmaßnahmen. Ziel ist es, eine kontinuierliche Verbesserung zu etablieren, der flexibel auf neue Bedrohungen und veränderte Rahmenbedingungen reagieren kann.

Der Prozessschritt 5 gibt Impulse für Verbesserungen und Weiterentwicklung am ISMS gibt. Er stellt sicher, dass das ISMS dynamisch bleibt und sich an veränderte Anforderungen und Bedrohungen anpasst.
### Überblick PDCA Zyklus

Alle 5 Prozesseschritte der Methodik-GS++ durchlaufen zyklisch einen Kreislauf zur kontinuierlichen Verbesserung bestehend aus den Phasen PLAN, DO, CHECK, ACT:
# Grundlegende Begriffe
## Anforderungen

Anforderungen beschreiben, was getan werden muss, um ein bestimmtes Sicherheitsniveau bezüglich der Informationssicherheit zu erreichen. Diese behandeln organisatorische, personelle, infrastrukturelle und technische Bereiche. Wie die Anforderungen im konkreten Fall erfüllt werden können, ist in entsprechenden Maßnahmen beschrieben. Im englischen Sprachraum wird für Anforderungen häufig der Begriff „control“ verwendet.

Das Modalverb einer Anforderung gibt an, welchen Pflichtcharakter sie hat, d.h. ob es sich um eine MUSS-, SOLLTE- oder KANN-Anforderung handelt. 

Für die Anforderungen gelten folgende Definitionen:

* MUSS → verpflichtend, keine Abweichung erlaubt (entspricht „MUST“[^1]).

* SOLLTE → in der Regel verpflichtend, Abweichung in begründeten Ausnahmefällen möglich   
  (entspricht „SHOULD“).

* KANN → optional, je nach Situation sinnvoll, aber nicht notwendig (entspricht „MAY“). 
## Assets

Als Assets werden alle materiellen oder immateriellen Werte der Institution bezeichnet, die für einen bestimmten Zweck, besonders zur Erreichung von Geschäftszielen, benötigt werden. 
## Geltungsbereich

Der Geltungsbereich beschreibt wo und für wen das ISMS gilt. Der Geltungsbereich (Scope) beschreibt den formalen und organisatorischen Umfang, in dem das ISMS angewendet wird. Der Geltungsbereich grenzt klar ab, welche Bereiche durch das ISMS geschützt und gesteuert werden und welche nicht.
## Informationssicherheitsmanagementsystem (ISMS)

Das Informationssicherheitsmanagementsystem ist eine erforderliche Planungs-, Lenkungs- und Kontrollaufgabe um einen ganzheitlichen Prozess für die Informationssicherheit aufzubauen. Dabei handelt es sich um einen kontinuierlichen Prozess, dessen Strategien und Konzepte ständig auf ihre Leistungsfähigkeit und Wirksamkeit zu überprüfen und bei Bedarf fortzuschreiben sind.
## Informationsverbund

Als Informationsverbund ist die Gesamtheit von infrastrukturellen, organisatorischen, personellen und technischen Objekten zu verstehen, die der Aufgabenerfüllung in einem bestimmten Anwendungsbereich der Informationsverarbeitung dienen. Ein Informationsverbund kann dabei als Ausprägung die gesamte Institution oder einzelne Bereiche, die durch organisatorische Strukturen oder gemeinsame Geschäftsprozesse bzw. Anwendungen gegliedert sind, umfassen.
## Maßnahmen

Als Maßnahmen werden alle Aktionen bezeichnet, die dazu dienen, um Sicherheitsrisiken zu steuern und um diesen entgegenzuwirken. Sie beschreiben, wie Anforderungen erfüllt werden. Dies schließt sowohl organisatorische, als auch personelle, technische oder infrastrukturelle Maßnahmen ein.
## Praktiken

Praktiken bündeln Anforderungen nach Tätigkeiten, deren Zuständigkeit bestimmten Rollen zuordbar sind. Dies ermöglicht eine schnelle Zuordnung von Anforderungen zu Prozessen und zuständigen Personen oder Rollen, die für die Umsetzung führend verantwortlich sind. Jede Anforderung ist in genau eine Praktik einsortiert.

Praktiken lassen sich unterteilen in:

* ISMS-Praktiken  
* Organisatorische Praktiken  
* Technische Praktiken

Die ISMS-Praktiken sind übergreifend. Sie bauen einen Plan-Do-Check-Act-Zyklus (PDCA-Zyklus) des Managementsystems auf, der die fortlaufende Kontrolle und Verbesserung über alle Bereiche hinweg gewährleistet.
## Schutzbedarf

Der Schutzbedarf beschreibt, wie stark Geschäftsprozesse, Informationen oder Systeme geschützt werden müssen. Er ergibt sich aus den Auswirkungen auf 

* Vertraulichkeit,  
* Integrität und   
* Verfügbarkeit.

Der Schutzbedarf legt das angemessene Schutzniveau fest und bildet die Grundlage für die Auswahl geeigneter Anforderungen. Der Schutzbedarf im Grundschutz++ teilt sich in die Kategorien „normal“ und „hoch“.
## Sicherheitsleitlinie 

Die Sicherheitsleitlinie ist ein zentrales Dokument für die Informationssicherheit einer Institution. In ihr wird beschrieben, für welche Zwecke, mit welchen Mitteln und mit welchen Strukturen Informationssicherheit innerhalb der Institution hergestellt werden soll. Sie beinhaltet die von der Institution angestrebten Informationssicherheitsziele sowie die verfolgte Sicherheitsstrategie. Die Sicherheitsleitlinie beschreibt damit auch über die Sicherheitsziele das angestrebte Sicherheitsniveau in einer Behörde oder einem Unternehmen.
## Sicherheitsniveau

Sicherheitsniveau indiziert die Erfüllung von Sicherheitszielen, durch umgesetzte organisatorische, technische und personelle Anforderungen. 

Es wird zwischen zwei Sicherheitsniveaus unterschieden: 

* normal (Stand der Technik) und   
* erhöhtes Sicherheitsniveau.
## Zielobjekte

Zielobjekte sind Teile des Informationsverbunds, denen im Rahmen der Modellierung Anforderungen zugeordnet werden können. Zielobjekte können dabei physische und logische Objekte sein.
## Informationssicherheitseinstufung

tdb
# Prozessschritt 1 – Erhebung und Planung

Die Erhebung und Planung bilden das Fundament der Methodik. In diesem Prozessschritt werden die organisatorischen und rechtlichen Rahmenbedingungen für das Informationssicherheitsmanagement geschaffen. Im Fokus steht dabei die Verankerung der Informationssicherheit in der Institution durch die Festlegung klarer Strukturen, Rollen und Zuständigkeiten.

Auf der Basis des Managementrahmens, welcher sich aus den Zielen, Leitlinien, Rollen, Verantwortlichkeiten Dokumentationen und dem kontinuierlichem Verbesserungsprozess ergibt, wird der Informationsverbund des ISMS festgelegt.

Als Ergebnis dieses Prozessschrittes liegt eine organisatorische und strategische Grundlage vor, auf der die weiteren Prozessschritte aufbauen können. Die getroffenen Entscheidungen und geschaffenen Strukturen prägen maßgeblich die Ausrichtung und Wirksamkeit des gesamten ISMS der Institution.

Ziel ist ein Verständnis über Zweck und Grenzen des zu betrachtenden Geltungsbereiches und eine sinnvolle und eindeutige Abgrenzung des ISMS.
## Festlegung des Kontextes der Institution 

Die Festlegung des Kontextes der Institution bildet den Ausgangspunkt für die Gestaltung eines ISMS. Dieser Prozess umfasst die systematische Analyse und Dokumentation aller internen und externen Faktoren, die einen Einfluss auf die Informationssicherheitsziele und \-strategie der Institution haben.

Der externe Kontext umfasst eine Vielzahl von Faktoren, die von außen auf die Institution einwirken:

* Gesellschaftliche und kulturelle Faktoren, die die Erwartungen an die Institution prägen

* Rechtliche und regulatorische Rahmenbedingungen auf nationaler und internationaler Ebene

* Technologische Entwicklungen und deren Auswirkungen auf die Informationssicherheit

* Wirtschaftliche Bedingungen im relevanten Marktumfeld

* Ökologische und physische Umweltbedingungen am Standort der Institution 

Der interne Kontext bezieht sich auf die institutionseigenen Faktoren:

* Institutionsstrategien, Werte und Institutionsziele

* Institutionsstruktur mit Hierarchien, Abteilungen und Zuständigkeitsbereichen

* Etablierte Prozesse und Arbeitsabläufe

* Vorhandene IT-Infrastruktur und Informationssysteme

* Institutionskultur und Einstellungen zur Sicherheit

Die systematische Analyse und Dokumentation des Kontextes schafft ein umfassendes Verständnis der Rahmenbedingungen und liefert wichtige Erkenntnisse für das ISMS. Sie hilft bei der Identifikation von Risiken und stellt sicher, dass das ISMS auf die individuellen Gegebenheiten der Institution abgestimmt ist.
## Analyse der interessierten Parteien

Die Analyse der interessierten Parteien (Stakeholder) identifiziert systematisch alle Personen, Gruppen oder Institutionen, die ein berechtigtes Interesse an der Informationssicherheit der Institution haben oder von dieser betroffen sind. Das Verständnis ihrer Anforderungen, Erwartungen und potentiellen Einflüsse ist entscheidend für die Ausrichtung und Akzeptanz des ISMS.

Ein Verfahren zur Ermittlung der interessierten Parteien und ihrer Bedürfnisse und Erwartungen an das ISMS muss festgelegt und durchgeführt werden. 

Dabei sind folgende Aspekte zu berücksichtigen:

* Externe interessierte Parteien wie Kunden, Dienstleister, Geschäftspartner, Gesetzgeber, Aufsichtsbehörden und die Öffentlichkeit identifizieren, 

* interne interessierte Parteien wie Institutionsleitung, Mitarbeitende, Führungskräfte und Personalvertretungen berücksichtigen,

* die spezifischen Anforderungen und Erwartungen jeder Stakeholder-Gruppe systematisch erfassen,

* die Relevanz und Priorität der identifizierten Anforderungen bewerten und

* festlegen, welche dieser Anforderungen als verbindliche Verpflichtungen in das ISMS aufgenommen werden.

Die Analyse der interessierten Parteien bildet eine wichtige Grundlage für die Ausgestaltung des ISMS. Sie trägt dazu bei, dass das ISMS nicht nur technische Aspekte, sondern auch die vielfältigen organisatorischen und menschlichen Faktoren berücksichtigt, die für den Erfolg der Informationssicherheit maßgeblich sind. Die regelmäßige Überprüfung und Aktualisierung dieser Analyse stellt sicher, dass das ISMS relevant und wirksam bleibt, auch wenn sich die Stakeholder-Landschaft verändert.
## Festlegung des Geltungsbereichs

Die Festlegung des Geltungsbereichs bildet die Grundlage für die Einführung und Weiterentwicklung des ISMS. 

Der Geltungsbereich beschreibt, wo und für wen das ISMS gilt. Er legt den formalen und organisatorischen Umfang (Scope) fest, in dem das ISMS angewendet wird. Damit definiert er die Grenzen der institutionellen Verantwortung für Informationssicherheit. Der Geltungsbereich wird auf Grundlage des institutionellen Kontextes, der gesetzlichen, regulatorischen und vertraglichen Anforderungen sowie der strategischen Ziele der Institution festgelegt. Er umfasst alle relevanten Institutionseinheiten, Geschäftsprozesse, Standorte und IT-Systeme, die im Rahmen des ISMS betrachtet werden sollen.

Bei der Festlegung sind insbesondere folgende Fragen zu klären:

Formale und organisatorische Abgrenzung

* Welche Institutionsbereiche, Geschäftsprozesse und Tätigkeiten gehören zum Geltungsbereich?

Infrastrukturelle Abgrenzung:

* Welche Standorte und Systeme liegen innerhalb des Geltungsbereichs?  
* Welche externen Partner oder Dienstleister sind in das ISMS einzubeziehen?  
* Welche Bereiche sind bewusst nicht Bestandteil des Geltungsbereichs?

Der Geltungsbereich ist von der Institutionsleitung zu genehmigen und verbindlich zu dokumentieren.

Eine eindeutige Definition ist notwendig, um den Anwendungsrahmen des ISMS transparent darzustellen und die nachfolgenden Schritte, insbesondere die Festlegung des Informationsverbunds, gezielt durchführen zu können. 

Aus der Festlegung des Geltungsbereichs müssen die relevanten Geschäftsprozesse hervorgehen, da diese die Grundlage für die Schutzbedarfsfeststellung bilden. 
## Definition und Abgrenzung des Informationsverbunds 

Die präzise Definition und Abgrenzung des Informationsverbunds ist eine grundlegende Voraussetzung für ein wirksames ISMS. Während der Geltungsbereich den formalen Rahmen vorgibt, stellt der Informationsverbund die inhaltlich-technische Abbildung dieses Bereichs dar. Er umfasst die Gesamtheit aller informationsverarbeitenden Systeme, Prozesse und Komponenten, die innerhalb des festgelegten Geltungsbereichs betrachtet werden. Der Informationsverbund beschreibt damit die tatsächliche Struktur der Informationsverarbeitung in der Institution. In der Praxis kann es in einem Geltungsbereich auch mehrere Informationsverbünde geben.

Er bildet die Grundlage für die Schutzbedarfsfeststellung, die Modellierung sowie die Ableitung geeigneter Maßnahmen. Die Definition des Informationsverbundes erfolgt auf Basis des zuvor analysierten Kontextes und der Anforderungen der interessierten Parteien sowie der daraus abgeleiteten Ziele. Dabei müssen folgende Dimensionen klar dokumentiert werden: 

Organisatorische und personelle Abgrenzung:

* Welche Institutionsbereiche, Rollen und Personen gehören zum Informationsverbund?

Technische Abgrenzung:

* Welche Anwendungen, Systeme und Netze sind Bestandteil des Informationsverbundes?

* Wo verlaufen die technischen Grenzen und wie sind Schnittstellen zu externen Systemen gestaltet?

* Welche Betriebsanteile werden an externe Parteien outgesourced bzw. welche Cloud-Dienste werden genutzt?

Infrastrukturelle Abgrenzung:

* Welche Standorte, Gebäude und Räumlichkeiten gehören zum Informationsverbund?

Zusätzlich sind die Schnittstellen des Informationsverbunds zu externen Prozessen und Systemen eindeutig zu dokumentieren – sowohl organisatorisch als auch technisch und infrastrukturell.

Eine klare und nachvollziehbare Abgrenzung des Informationsverbunds stellt sicher, dass innerhalb des definierten Geltungsbereichs alle relevanten Informationswerte, Strukturen und Abhängigkeiten erfasst werden. Sie ermöglicht eine zielgerichtete Anwendung von Maßnahmen und unterstützt die Wirksamkeit des ISMS.
## Informationssicherheitseinstufung

Die Informationssicherheitseinstufung dient der systematischen Identifikation des Schutzbedarfs von Geschäftsprozessen und verarbeiteten Informationen. Hierbei wird zwischen dem Schutzbedarf „normal“ und „hoch“ unterschieden. Der prozessorientierte Ansatz stellt die Verbindung zwischen Geschäftsprozessen und Informationen in den Vordergrund.

Das Vorgehen bei der Informationssicherheitseinstufung umfasst folgende Teilschritte:

1. Identifizierung der Geschäftsprozesse und/oder der darin verarbeiteten Informationen, welche bei der Festlegung des Geltungsbereiches erfasst wurden.

2. Identifizierung des Schutzbedarfs der Geschäftsprozesse oder Informationen anhand der Kritikalität von Auswirkungen auf die Geschäftsziele.
### Identifikation der Geschäftsprozesse

In einem ersten Schritt werden die Geschäftsprozesse erfasst, die für den Geltungsbereich relevant sind. Hierbei kann oft auf bestehende Prozesslandkarten und Managementsysteme zurückgegriffen werden. Dabei sind sowohl Kernprozesse als auch Hilfsprozesse zu erfassen. Besteht noch keine Prozessübersicht in der Institution, so können die technischen und organisatorischen Praktiken als Ausgangsvorschlag für relevante Hilfsprozesse herangezogen werden. Bitte beachten Sie dabei, dass die Praktiken des Grundschutz++ nicht die Kernprozesse der Institution enthalten, da die Geschäftsziele von Institution zu Institution sehr unterschiedlich gestaltet sein können.
### Identifizierung des Schutzbedarfs

Zusätzlich sollte, in Absprache mit der Institutionsleitung, unter Berücksichtigung der Geschäftsziele eine erste Einstufung für die kritischen Geschäftsprozesse und Informationsarten vorgenommen werden. Diese dient als Orientierungsrahmen für die Priorisierung bei der Modellierung im Prozessschritt 2 und der Umsetzung. Die Einstufung erfolgt dabei in den Stufen „normal“ oder „erhöht“. 

Die Einstufung richtet sich nach der Bedeutung des Geschäftsprozess für die Geschäftsziele oder den gesetzlichen Auftrag der Institution. 

Priorität für die weitere Abarbeitung hat zunächst der wichtigste Geschäftsprozess, d.h. derjenige Geschäftsprozess, dessen Informationsschutz für den Fortbestand der Institution von essentieller Bedeutung ist. Die Entscheidung darüber, welcher Geschäftsprozess am wichtigsten ist, obliegt der Institutionsleitung.
### Geschäftsprozesse mit erhöhtem Schutzbedarf

Hier hat zunächst der wichtigste Geschäftsprozess, d.h. derjenige Geschäftsprozess, dessen Informationsschutz für den Fortbestand der Institution von essentieller Bedeutung ist, Priorität. Die Entscheidung darüber, welche Geschäftsprozesse am wichtigsten sind, obliegt der Institutionsleitung. Droht bei einer Verletzung der Vertraulichkeit, Integrität oder Verfügbarkeit von Informationen in diesem Geschäftsprozess ein existenzbedrohender finanzieller oder existenzbedrohender Reputationsschaden, so ist der Prozess als erhöht einzustufen. Das gleiche gilt, wenn ein Geschäftsprozess oder eine Information, als (VS-)Vertraulich eingestuft wird. 

Wird bei einem Geschäftsprozess ein erhöhter Schutzbedarf identifiziert ist für den betroffenen Geschäftsprozess eine dedizierte Risikoanalyase durchzuführen. Das Ergebnis der Schutzbedarfsfeststellung ist eine Übersicht des Schutzbedarfs der zu verarbeitenden Informationen, sowie der Relevanz der Geschäftsprozesse. Dabei ist der in Prozessschritt 1 ermittelte Kontext zu berücksichtigen, insbesondere wenn externe Vorgaben zum Schutz von Informationswerten bestehen. 
## Entwicklung einer Sicherheitsleitlinie (inkl. Sicherheitsstrategie) 

Die Sicherheitsleitlinie definiert die grundlegende Ausrichtung und die Ziele der Informationssicherheit in der Institution. Sie stellt die Verbindung zwischen den übergeordneten Unternehmenszielen und den konkreten Anforderungen her und schafft einen verbindlichen Rahmen für alle Aktivitäten im Bereich der Informationssicherheit.

Es sind z.B. folgende Aspekte zu berücksichtigen:

* Festlegen von Zielen für die Informationssicherheit  
  Auf Basis der identifizierten Rahmenbedingungen müssen konkrete und messbare Ziele (SMART) für die Informationssicherheit definiert werden. Diese Ziele sollten einen klaren Bezug zu den Geschäftszielen der Institution aufweisen und die Anforderungen der interessierten Parteien berücksichtigen.

* Festlegung einer Sicherheitsstrategie  
  Eine grundlegende Strategie zur Erreichung der definierten Ziele für die Informationssicherheit sollte verankert werden. Die Strategie beschreibt den übergeordneten Ansatz und die Prinzipien.

* Verpflichtung der Institutionsleitung   
  Die Verpflichtung der Institutionsleitung zur Informationssicherheit muss formal verankert werden. Diese Verpflichtung umfasst die Übernahme der Gesamtverantwortung, die Bestätigung und Überwachung der Informationssicherheitsziele im Hinblick auf die Institutionsziele sowie die aktive Förderung des ISMS. Die Förderung des ISMS erfolgt durch die aktive Beteiligung an Führungsentscheidungen, Bestätigung der Informationssicherheitsorganisation, die Unterstützung bei der Integration des ISMS, die Bereitstellung angemessener finanzieller und personeller Ressourcen sowie die Förderung der kontinuierlichen Verbesserung.

* Erstellung und Freigabe einer Sicherheitsleitlinie  
  Eine für die Institution passende Sicherheitsleitlinie zur Informationssicherheit muss dokumentiert werden. Die Sicherheitsleitlinie sollte die Gesamtverantwortung und Verpflichtung der Institutionsleitung, die Informationssicherheitsziele, die Informationssicherheitsstrategie, die Benennung der Rollen und Zuständigkeiten sowie die Verpflichtung zur kontinuierlichen Verbesserung enthalten. Die Freigabe der Sicherheitsleitlinie durch die Institutionsleitung muss dokumentiert werden, beispielsweise durch eine formelle Unterschrift.

Die Sicherheitsleitlinie ist ein zentrales Dokument, welches an alle Mitarbeitenden kommuniziert werden muss. Sie dient als Orientierung für alle sicherheitsrelevanten Entscheidungen und Aktivitäten und fördern ein gemeinsames Verständnis der Bedeutung und Ausrichtung der Informationssicherheit.
## Implementierung des Compliance-Managements 

Die systematische Erfassung und Verwaltung von Compliance-Verpflichtungen für Informationssicherheit bilden die Grundlage für deren wirksame Umsetzung und kontinuierliche Überwachung.

Es sind folgende Aspekte zu berücksichtigen:

* Rechtskataster, Gesetze und Anforderungskataloge analysieren.

* Zuständiger Compliance Stellen, oder vergleichbarer Ansprechpartner, sollte angehören werden.

* Gesetzliche Verpflichtungen, welche die Verarbeitung von Informationen durch die Institution betreffen, sollten dokumentiert werden.

* Vertragliche Verpflichtungen sollten zusammengestellt werden.

Vertragliche Verpflichtungen umfassen alle Pflichten, die sich aus rechtlich bindenden Vereinbarungen ergeben, unabhängig davon, ob diese als Vertrag bezeichnet werden oder nicht (hierzu zählen unter anderem Dienstleistungsverträge, Lizenzvereinbarungen, Service Level Agreements (SLAs) und Vertraulichkeitsvereinbarungen).

Ein gut strukturiertes Compliance-Management stellt sicher, dass gesetzliche und vertragliche Vorgaben nicht nur bekannt sind, sondern auch bei der Sicherheitskonzeption berücksichtigt werden. Dies minimiert Compliance-Risiken und schafft gleichzeitig Transparenz über die externen und internen Anforderungen, die das ISMS erfüllen muss.
## Sicherheitsorganisation und Rollen 

Eine effektive Sicherheitsorganisation mit definierten Rollen und Zuständigkeiten ist die organisatorische Grundlage eines erfolgreichen ISMS. Sie stellt sicher, dass alle Aspekte der Informationssicherheit angemessen abgedeckt und mit den notwendigen Ressourcen und Kompetenzen ausgestattet sind.

 Es sind folgende Aspekte zu berücksichtigen:

* Festlegung von Rollen und Zuständigkeiten  
  Die Rollen im Rahmen des ISMS müssen mit den notwendigen Qualifikationen, Aufgaben und Befugnissen festgelegt und zugewiesen werden. Eine zentrale Rolle ist dabei die oder der „Informationssicherheitsbeauftragte“ (ISB), dessen Position, Aufgaben und Befugnisse klar zu definieren sind. Die Rolle des ISB sollte im besten Fall eine Stabstelle sein und zur Vermeidung von Interessenkonflikten nicht unter dem IT-Leiter verortet werden.   
  Für alle relevanten Rollen müssen Stellvertreterregelungen etabliert werden, um eine kontinuierliche Handlungsfähigkeit zu gewährleisten.

* Vermeidung von Interessenskonflikten  
  Bei der Festlegung von Rollen und Zuständigkeiten müssen Maßnahmen zur Vermeidung von Interessenskonflikten verankert werden. Insbesondere ist die Zuordnung konkurrierender Rollen (z. B. ausführender und prüfender oder freigebender Rollen) zu vermeiden. Dies kann durch eine geeignete Etablierung von Rollen in der Aufbauorganisation oder durch zusätzliche Kontrollen erreicht werden.

* Festlegung einer Sicherheitsorganisation  
  Die Sicherheitsorganisation für die Institution muss mit den festgelegten Rollen, Zuständigkeiten sowie relevanten Gremien verankert werden. Ziel ist es, alle relevanten Bereiche eines ISMS sowie die wichtigen Schnittstellen zu anderen Bereichen vollständig und wirksam in der Institution abzubilden.

* Sicherstellung der Qualifikation  
  Ein Verfahren zur Sicherstellung der Qualifikation von Rollen- und Verantwortungsträgern muss verankert werden. Für jeden Rollen- und Verantwortungsträger müssen die erforderlichen Anforderungen und Fähigkeiten festgelegt sein.

Die Sicherheitsorganisation sollte in einem Organigramm oder einer ähnlichen Darstellung dokumentiert werden, dass die Beziehungen zwischen den verschiedenen Rollen, ihre Zuständigkeiten, Verantwortlichkeiten und Berichtswege klar darstellt. Diese Dokumentation dient als Referenz für alle Mitarbeiter und unterstützt die effektive Kommunikation und Koordination in Sicherheitsfragen.
## Dokumentation und Kommunikation 

Eine strukturierte Dokumentation und effektive Kommunikation sind wesentliche Elemente eines funktionierenden ISMS. Sie gewährleisten, dass alle relevanten Informationen verfügbar, aktuell und für die jeweiligen Zielgruppen zugänglich sind. Das Thema Dokumentation und Kommunikation ist oft ein übergeordnetes Thema in einer Organisation. Das ISMS sollte sich daran anlehnen bzw. kann sich im Optimalfall komplett mit übernommen werden.

Es sind folgende Aspekte zu berücksichtigen:

* Festlegung der Kommunikation  
  Die relevanten Vorgaben zur internen und externen Kommunikation müssen verankert werden. Für die relevante Kommunikation im Rahmen eines ISMS sind die Eckpunkte (Wer, Was, Wann, Wo und Warum.) festzulegen. Dies beinhaltet die Identifikation der relevanten Behörden und der relevanten Kontakte sowie die Festlegung von Zuständigkeiten für die Kommunikation. Ein besonderer Fokus liegt auf dem externen Austausch zur Informationssicherheit, um andere Perspektiven wahrzunehmen und von Erfahrungen zu profitieren. Hierzu können beispielsweise Branchenverbände, Fachforen oder andere Einrichtungen genutzt werden.

* Kommunikation im Projektmanagement   
  Ein Verfahren zur Etablierung der Informationssicherheit in das Projektmanagement sollte verankert werden. Die relevanten Sicherheitsorgane werden an bestimmten Punkten im Verlauf eines sicherheitsrelevanten Projekts, wie beispielsweise bei der Einführung eines neuen IT-Systems oder einer neuen Software, eingebunden. Es wird festgelegt, zu welchen Zeitpunkten eine Beteiligung des ISBs erfolgen soll.

* Dokumentenlenkung  
  Ein Verfahren zur Lenkung mindestens aller für das ISMS direkt und indirekt relevanten Dokumente muss eigerichtet und verankert werden. Ziel dieses Verfahrens ist die Sicherstellung der Nachvollziehbarkeit über den gesamten Lebenszyklus eines Dokuments. Dies beinhaltet die Erstellung bzw. Übernahme der Dokumente mit Titel, Autor, Dokumenteneigentümer, Sicherheitsklassifikation, Erstelldatum sowie einheitlichen Formaten. Weiterhin umfasst es die Steuerung mit einem Änderungsmanagement (Versionierung), einer einheitlichen Veröffentlichung, einer angemessen geschützten Ablage und ggf. auch Archivierung sowie einer kontrollierten Rücknahme veralteter Dokumente.

* Vorgehensweisen und Regelungen  
  Die Verfahren des ISMS sowie die Zuständigkeiten müssen dokumentiert werden. Der Umfang der Dokumentation ist dem Umfang der Institution angemessen zu gestalten. Die Verfahren beinhalten insbesondere das Risikomanagement, die Etablierung von Änderungen im ISMS, die Dokumentenlenkung, die Leistungsbewertung und Auditierung, kontinuierliche Verbesserung sowie reaktive Verfahren (Sicherheitsvorfallbehandlung, Notfallmanagement). In kleineren Institutionen kann dies in einem überschaubaren Dokument erfolgen, während in größeren Institutionen entsprechend detailliertere Prozessbeschreibungen erforderlich sein können. Die Freigabe der Verfahren für das ISMS durch die Institutionsleitung sollte dokumentiert werden.

Eine strukturierte Dokumentation und zielgerichtete Kommunikation unterstützen nicht nur die Compliance, sondern fördern auch das Bewusstsein für Informationssicherheit in der Institution und erleichtern die kontinuierliche Verbesserung des ISMS. Sie sind daher unverzichtbare Komponenten eines wirksamen Governance- und Compliance-Frameworks.
## Festlegung und Freigabe der Vorgehensweise 

Um das ISMS wirksam umzusetzen, müssen jedoch auch die Verfahren und Zuständigkeiten des ISMS klar dokumentiert und auf die Größe sowie Komplexität der Institution abgestimmt sein.

Im Folgenden werden die zentralen Themenfelder beschrieben, die für ein funktionierendes ISMS berücksichtigt werden müssen:

* Festlegen von Vorgehensweisen   
  Zu den zu dokumentierenden Verfahren gehören insbesondere das Risikomanagement, das Änderungsmanagement im ISMS, die Dokumentenlenkung, die Leistungsbewertung und Auditierung, die kontinuierliche Verbesserung sowie reaktive Verfahren wie Sicherheitsvorfallbehandlung und Notfallmanagement. Der Umfang der Dokumentation richtet sich nach der Größe der Institution. In kleineren Institutionen kann ein einziges Dokument ausreichend sein. In größeren Institutionen kann es sein, dass detaillierte Prozesse und Rollenbeschreibungen erforderlich sind.  
* Freigabe von Vorgehensweisen   
  Die Freigabe der ISMS-Verfahren erfolgt durch die Institutionsleitung. Diese Freigabe sollte dokumentiert werden, um Verbindlichkeit und Nachvollziehbarkeit sicherzustellen.  
* Freigabe des Managementberichts  
  Eine Autorisierung durch die Institutionsleitung der anzustrebenden Aktionen ist zwingend erforderlich.
## Festlegung Risikomanagement 

Das Risikomanagement stellt sicher, dass Risiken systematisch identifiziert, eingeschätzt, bewertet und behandelt werden. Die Festlegung einheitlicher Kriterien für Kritikalität, Risikoeinschätzung, Risikobewertung und Risikoakzeptanz, sowie die Rolle des Risikoeigentümers sorgen für Transparenz und Verbindlichkeit. Durch die Einbindung der Institutionsleitung – insbesondere bei Freigaben und bei der Schutzbedarfsfeststellung – wird das Risikomanagement strategisch verankert und erhält die notwendige Durchsetzungskraft. So wird Informationssicherheit nicht nur operativ, sondern auch auf organisatorischer und leitender Ebene gesteuert.

Es sind folgende Aspekte zu berücksichtigen:

* Methodik für das Risikomanagement  
  Für das Risikomanagement muss eine einheitliche Methodik verankert werden. Diese Methodik muss den Kontext der Institution und die Anforderungen interessierter Parteien sowie die hieraus abgeleiteten Ziele berücksichtigen. Die Methodik kann frei gewählt werden, muss jedoch für Informationssicherheitsrisiken geeignet sein.

* Risikoeigentümer  
  In der Methodik für das Risikomanagement muss die Rolle des Risikoeigentümers mit den notwendigen Aufgaben verankert werden. Der Risikoeigentümer trägt die Verantwortung für die Behandlung von Risiken. Er verfügt über die Befugnis, Entscheidungen über eine geeignete Risikobehandlung zu treffen.

* Kritikalitätskriterien  
  Einheitliche Kriterien für die Kritikalität (Schutzbedürftigkeit) von Geschäftsprozessen und Informationen müssen in der Risikomanagementmethodik verankert werden. Diese Kriterien bilden eine einheitliche Grundlage für die Schutzbedarfsfeststellung.

* Risikoappetit  
  Die Institutionsleitung sollte eine erste grundlegende Einstufung der Schutzbedürftigkeit seiner wesentlichen Geschäftsprozesse und Informationen vornehmen. Diese Einstufung berücksichtigt die Geschäftsziele und dient als Orientierungsrahmen für die Auswahl der Anforderungen. Die Einstufung erfolgt in den Stufen „normal(-SdT)“ und „erhöht“. 

* Kriterien für die Risikobeurteilung 	  
  Für die Risikobeurteilung müssen einheitliche Kriterien in der Risikomanagementmethodik verankert werden. Dazu gehören die Eintrittswahrscheinlichkeit, die Schadenshöhe und die Definition von Risikokategorien. Diese Kriterien gewährleisten eine konsistente und nachvollziehbare Beurteilung.

* Kriterien für die Risikoakzeptanz  
  Einheitliche Kriterien für die Risikoakzeptanz müssen verankert werden. Diese Kriterien legen fest, wann Risiken akzeptiert werden dürfen. Sie legen auch fest, wann Risiken zwingend behandelt werden müssen.

* Freigabe des Risikomanagements   
  Die von der Institutionsleitung freigegebenen Verfahren, Rollendefinitionen und Kriterien des Risikomanagements müssen dokumentiert werden, um Nachvollziehbarkeit und Verbindlichkeit sicherzustellen.
# Anforderungsanalyse

Die Anforderungsanalyse verknüpft die übergreifenden Rahmenbedingungen des ISMS mit den konkreten Anforderungen an die Informationssicherheit im Einzelnen, die in den ISMS, organisatorischen und technischen Praktiken zu finden sind.

Ziel ist es, für den konkreten Informationsverbund und seine Bestandteile die jeweils relevanten Anforderungen zu generieren und in einem Anforderungspaket zusammen zu stellen. Dieses Anforderungspaket ist exakt auf den Informationsverbund zugeschnitten und bildet die Basis für die spätere Umsetzung.

**Hinweis**

**Bei der Erstellung des individuellen Anforderungspaketes gibt es verscheide Wege die Anforderungen aus der SdT-Bibliothek zusammen zu stellen. Je nach Größe der Institution, dem Schutzbedarf, den strategischen Zielen (z.B. Zertifizierung) oder externen Vorgaben kann unterschiedlich bei der Modellierung unterschiedliche vorgegangen werden.**

**Das im folgende beschreiben Verfahren ist die Standardvorgehensweise, die auch ohne weiter Hilfsmittel durchgeführt werden kann.**

Bei der Durchführung diese Prozessschritt 2 kann parallel vorgegangen werden. So kann beispielsweise für bereits erfasste Assets das Mapping auf Zielobjektklassen vorgenommen werden und ein passendes Anforderungspaket erstellt werden. Kommen später neue Assets und damit Zielobjektklassen hinzu, so können diese parallel ergänzt werden. 
## Erstellung eines Anforderungspaket 

Das Anforderungspaket enthält alle Anforderungen, die für den betrachteten Informationsverbund und den priorisierten Geschäftsprozesse relevant sind sowie wenn erforderlich zusätzlichen Anforderungen. 

Das Anforderungspaket entsteht durch die Modellierung von Anforderungen auf zwei Ebenen.

Anforderungen-GS++ dies sind:

* Anforderungen aus den ISMS-Praktiken  
* Anforderungen mit Zielobjektbezug   
* Anforderungen ohne Zielobjektbezug. 

und zusätzlichen Anforderungen:

* aus anderen Verpflichtungen   
* neue ergänzende Anforderungen die nicht im GS++ enthalten sind  
* für höheren Schutzbedarf

Die Grafik gibt eine Übersicht über die Anforderungsmodellierung.
## ISMS-Anforderungen des Infoformationsverbundes 

Die Anforderungen der ISMS-Praktiken sind übergreifend und keinem einzelnen Zielobjekt zugewiesen. Sie bauen den PDCA-Zyklus des Managementsystems auf und gelten deshalb einmalig für den gesamten Informationsverbund.

1. Alle Anforderungen der ISMS-Praktiken werden ohne weitere Selektion auf den Informationsverbund modelliert.  
2. Sie werden als „verbundweite Anforderungen“ im Anforderungspaket geführt, da sie Governance-, Steuerungs-, Kontroll- und Verbesserungsprozesse definieren. 

Die ISMS-Anforderungen aus den fünf Praktiken Governance und Compliancen, Strukturmodellierung, Umsetzung und Verbesserung bilden den Kern des Anforderungspaketes für den Informationsverbund.
## Asset-Modellierung 

Die Asset-Modellierung ist der zentrale Schritt, um den zuvor festgelegten Informationsverbund strukturiert und nachvollziehbar in sicherheitsrelevante Bestandteile zu zerlegen. Ziel ist es, die für den betrachteten Geschäftsprozess relevanten Assets zu identifizieren, zu dokumentieren und so zu modellieren, dass daraus automatisiert oder manuell passende Anforderungen abgeleitet werden können.

Die Asset-Modellierung fokussiert auf jene Assets, die im Rahmen der priorisierten Geschäftsprozesse Informationen verarbeiten, speichern, übertragen oder deren Schutz unterstützen.

Die Asset-Modellierung dient damit als Brücke zwischen der realen Struktur der Institution und der Systematik des Grundschutz++. Sie stellt sicher, dass Anforderungen nicht abstrakt, sondern entlang konkreter Objekte und Verantwortlichkeiten zugeordnet werden können.

Die Asset-Modellierung erfolgt in folgenden Teilschritten:

1. Erfassung aller relevanten Assets   
2. Zielobjektmapping  
   Zuordnung der Assets auf eine oder mehrere passende Zielobjektkategorien, 

Ergebnis dieses Schritts ist eine modellierte Asset-Zielobjekt-Struktur, die als Grundlage für die Anforderungsmodellierung und die spätere Umsetzung dient.
### Erfassung relevanter Assets

Für die Modellierung weiterer Anforderungen aus den Grundschutz++ werden die für den Geschäftsprozess relevanten Assets identifiziert und dokumentiert. Die Erfassung orientiert sich an der Priorisierung aus der Schutzbedarfsfeststellung. 	  
Im ersten Durchgang bzw. PDCA-Zyklus ist es ausreichend, die Assets zu erfassen, die für den wichtigsten Geschäftsprozess erforderlich sind. Weitere Geschäftsprozesse und zugehörige Assets können iterativ in nachfolgenden Zyklen oder parallel ergänzt werden.

Bei der Erfassung ist auf Vollständigkeit innerhalb des betrachteten Geschäftsprozesses zu achten. Durch die zyklische und somit wiederkehrende Abarbeitung der einzelnen Prozessschritte dieses Dokumentes wird die Betrachtung der vollständigen Asseterfassung innerhalb des Geschäftsprozesses geschärft. 

Relevante Assets können insbesondere sein:

* Informationswerte  
* IT-Systeme und Anwendungen (System Assets)  
* Netz- und Kommunikationskomponenten  
* Infrastrukturelle und physische Assets  
* Personelle und organisatorische Assets

Für die Dokumentation kann auf vorhandene Assetdaten/-register und digitale erfasste Systemdaten zurückgegriffen werden. 

Für jedes Asset sollten folgende Informationen festgehalten werden:

* eindeutige Bezeichnung/ID  
* kurze Beschreibung und Zweck  
* Zuordnung zu Geschäftsprozess(en)  
* verantwortliche Rolle bzw. Asset-Owner  
* ggf. Standort bzw. logische Einordnung (Netz, Anwendungskontext etc.)  
* ggf. vorhandene Abhängigkeiten zu anderen Assets

Die Erfassung ist so zu gestalten, dass neue Assets oder Änderungen am Bestand jederzeit nachgetragen werden können. Damit wird die Modellierung konsistent erweitert und gepflegt.
### Mapping des Assets auf die Zielobjektkategorien

Jedes der relevanten Assets wird anschließend einem oder mehreren Zielobjektkategorien zugeordnet. Dies erfolgt anhand der Definitionen der Zielobjektkategorien.  

Zielobjektkategorien sind standardisierte Klassen von Bestandteilen des Informationsverbunds, für die im Grundschutz++ beschriebenen Anforderungen. Durch das Mapping werden Assets damit in die Systematik des GS++ überführt.

Die Zuordnung erfolgt anhand der Definitionen der Zielobjektkategorien. Für jedes Asset ist zu prüfen, welche Kategorie(n) seine Funktion und seinen Einsatz im Geschäftsprozess am besten abbilden. Dabei gelten folgende Grundsätze:

* Ein Asset kann mehreren Zielobjektkategorien zugeordnet werden, wenn es mehrere Funktionen erfüllt.  
* Die Zuordnung erfolgt funktionsorientiert, nicht nur nach technischen Merkmalen. Entscheidend ist, wie das Asset im Geschäftsprozess wirkt.  
* Fehlende oder schwer zuordenbare Assets werden im Rahmen der vereinfachten Risikobewertung betrachtet, um sicherzustellen, dass auch hierfür Anforderungen bzw. Maßnahmen abgeleitet werden können.

Die Zuordnung kann toolgestützt erfolgen, wenn Zielobjektkategorien maschinenlesbar hinterlegt sind. Bei manueller Zuordnung ist die Entscheidung nachvollziehbar zu dokumentieren (z. B. durch kurze Begründung oder Verweis auf Definition der Zielobjektkategorie).

Ergebnis dieses Schritts ist eine Zielobjekt-Liste je Asset, welche die Grundlage für die spätere Ableitung der Anforderungen bildet.
## Anforderungsmodellierung auf die Assets 

Bei der Modellierung der Assets auf Anforderungen des Grundschutz++ wird wie folgt vorgegangen: 

1. Modellierung der Anforderung aus den Zielobjektkategorien auf die zugeordneten Assets und Ergänzung des Anforderungspaketes

2. Vererbung von Anforderungen übergeordneter Zielobjektkategorien entsprechend der Zielobjekthierarchie und Ergänzung des Anforderungspaketes

3. Konsolidierung und Redundanzprüfung des Anforderungspaketes 

4. Modellierung zielobjektloser Anforderungen und Ergänzung des Anforderungspaketes
### Modellierung der Anforderungen mit Zielobjekt

Nun werden die Anforderungen aus dem Grundschutz++ auf die identifizierten Zielobjekte modelliert. Gemäß dem Schutzbedarf der Institution für den Geschäftsprozess, werden die Anforderungen mit entsprechendem Sicherheitsniveau gewählt. 

| Schutzbedarf  | Sicherheitsniveau |
| :---: | :---: |
| normal | normal (Stand der Technik) |
| hoch | erhöht |

	Tabelle

Die modellierten Anforderungen bilden das individuelle Anforderungspaket des festgelegten Informationsverbund in Bezug auf den ausgewählten Geschäftsprozess.
### Vererbung von Zielobjektkategorien

Im nächsten Schritt werden die zuvor zugeordneten Zielobjektkategorien um diejenigen Kategorien erweitert, die in der Zielobjekthierarchie übergeordnet sind. Hintergrund ist, dass Anforderungen nicht nur auf die „Blatt-Zielobjekte“ (direkt zugeordnete Kategorien), sondern auch auf deren konzeptionelle Oberknoten wirken. Dadurch wird sichergestellt, dass übergreifende Anforderungen konsistent berücksichtigt werden.

Die Vererbung erfolgt entlang der Zielobjekthierarchie:

1. Für jedes zugeordnete Zielobjekt werden alle Elternknoten bis zur Wurzel einbezogen.  
2. Die Vererbung ist deterministisch, da die Zielobjekthierarchie fest definiert ist.  
3. Eine Automatisierung der Vererbung ist möglich und empfohlen, wenn die Hierarchie maschinenlesbar vorliegt.

Die Vererbung kann dazu führen, dass sich Zielobjektkategorien mehrfach ergeben; diese sind konsolidiert zu betrachten, um redundante Anforderungen zu vermeiden.

Ergebnis dieses Schritts ist ein vollständiges Zielobjekt-Set je Asset, bestehend aus direkt zugeordneten Zielobjektkategorien und vererbten Oberkategorien. Dieses Set bildet die Grundlage für die Anforderungsmodellierung.

Tbd: Versionierung der Hierarchie einfügen
### Konsolidierung und Redundanzprüfung

Wenn Anforderungen durch mehrere vererbte Zielobjekte identisch auf ein Asset wirken, werden sie nur einmal geführt. So bleibt das Anforderungspaket schlank und umsetzbar.

Ergebnis ist pro Asset ein vollständiger Satz an Anforderungen, der alle organisatorischen, technischen, personellen und infrastrukturellen Vorgaben enthält, die zur Erreichung des Sicherheitsniveaus erforderlich sind. Diese Anforderungen ergänzen das Anforderungspaket.
### Modellierung zielobjektloser Anforderungen

Einige technische und organisatorische Anforderungen, sind keinem Zielobjekt zugeordnet. Diese Anforderungen sind nicht automatisch immer relevant, sondern werden geschäftsprozessbezogen bewertet.

1. Relevanzentscheidung je zielobjektloser Anforderung	  
   Für jede Anforderung ohne Zielobjekt wird entschieden, ob sie für den Geschäftsprozess bzw. die zugehörigen Assets erforderlich ist. Maßstab ist hier wiederum das Sicherheitsniveau sowie die konkrete Nutzung für den Geschäftsprozess.  
2. Zuordnung auf betroffene Assets  
   Relevante zielobjektlose Anforderungen werden den entsprechenden Assets zugewiesen und damit in das Anforderungspaket integriert.   
3. Nicht relevante bzw. modellierte Anforderungen werden, mit kurzer Begründung, dokumentiert, um Nachvollziehbarkeit bei einem späteren Audit bzw. Zertifizierung zu sichern.   
4. Erweiterung des Anforderungspaket um die zielobjektlosen Anforderungen
## Anforderungsergänzung auf Grund externer Verpflichtungen 

Dieser Schritt ergänzt das Anforderungspaket, um Anforderungen, die sich aus dem individuellen Compliance-Umfeld der Institution ergeben. Die Integration von externen Compliance-Verpflichtungen stellt sicher, dass alle relevanten gesetzlichen und vertraglichen Pflichten berücksichtigt werden, die erfasst wurden. Die in Prozessschritt 1 im Compliance-Management identifizierten und dokumentierten 

* gesetzlichen Verpflichtungen, welche die Verarbeitung von Informationen durch die Institution betreffen   
* vertraglichen Verpflichtungen mit Relevanz für die Informationsverarbeitung

bilden die Grundlage der Betrachtung. 

Dabei ist wie folgt vorzugehen:

1. Identifikation von Anforderungen auf der Grundlage der externen Verpflichtungen  
2. Modellierung von Anforderungen in Bezug auf dies Verpflichtung  
3. Konsolidierung und Redundanzprüfung des Anforderungspaketes   
4. Integration dieser Anforderungen in das Anforderungspaket, soweit sie nicht bereits darin enthalten sind.

Die Integration dieser Anforderungen trägt dazu bei, dass die spätere Umsetzung aller relevanten externen Vorgaben berücksichtigt und Compliance-Risiken minimiert werden. Dies ist besonders wichtig in stark regulierten Branchen oder bei Institutionen mit komplexen vertraglichen Beziehungen.

Die Dokumentation der Compliance-Anforderungen sollte so gestaltet sein, dass Veränderungen im regulatorischen oder vertraglichen Umfeld leicht erkannt und in die Modellierung integriert werden können. Dies unterstützt die kontinuierliche Anpassung und Verbesserung des ISMS an neue Compliance-Anforderungen.
## Anforderungsergänzung von neuen Anforderungen  

Falls es für Assets oder Themen im Grundschutz++ derzeit noch Anforderungen gibt, können dies von der Institution erstellt werden.

Die Anforderungsmodellierung für Assets ohne Anforderungen umfasst folgende Schritte: 

1. Identifikation und Dokumentation von Assets, für die es keine Grundschutz++ Anforderungen gibt. 

   2. Es ist nachvollziehbar zu begründen, warum die Anforderungen des Grundschutz++ nicht ausreichen.

   3. Erstellung von neuen Anforderungen in Bezug auf die Schutzziele (Vertraulichkeit, Integrität und Verfügbarkeit), für diese Assets.  

   4. Erweiterung des Anforderungspaket um die neuen Anforderungen.

Das Ergebnis der Anforderungsmodellierung für Assets ohne Anforderungen ist eine Dokumentation von Anforderungen und tragen zur Risikominimierung bei. 

Diese neuen Anforderungen fließen in die Erstellung des Anforderungspakets ein.
## Risikobetrachtung

Die Methodik des GS++ sieht vor, dass bei Erfüllung aller im Prozess heranzuziehender und zu beachtender Anforderungen keine separate Risikoanalyse gemacht werden muss. Der Grundschutz++ ist allumfassend und basierend auf den G0-Gefährdungen und legt somit das „Stand der Technik“ Sicherheitsniveau zu Grunde.  

Sollte eine Veränderung des vorgegeben SdT-Sicherheitsniveaus vorgenommen wird ist dies immer mit eine entsprechende Risikoanalyse zu hinterlegen.
### Risikoanalyse bei hohem Schutzbedarf 

Tbd: Überarbeitung

Für Geschäftsprozesse, die einen erhöhten Schutzbedarf aufweisen, ist eine vertiefende Risikoanalyse erforderlich. Diese geht über die vereinfachte Risikobewertung hinaus und analysiert detailliert die Risiken für besonders schützenswerte Assets und Geschäftsprozesse.

Die vertiefende Risikoanalyse umfasst folgende Aspekte:

* Durchführung einer vertieften Risikoanalyse für Geschäftsprozesse mit erhöhtem Schutzbedarf, z. B. nach BSI Standard 200-3 oder ISO 27005  
* Identifikation zusätzlicher Anforderungen bzw. Maßnahmen, um dem erhöhten Schutzbedarf gerecht zu werden  
* Dokumentation und Freigabe der Risikobehandlungsentscheidungen durch die Risikoeigentümer (i.A. die Institutionsleitung)  
* Konsolidierung der ergänzenden Anforderungen bzw. Maßnahmen aus der Risikoanalyse in das Anforderungspaket 

Die Methode für die vertiefende Risikoanalyse kann frei gewählt werden, sollte jedoch für Informationssicherheitsrisiken angemessen und geeignet sein. Die Entscheidungen zur Risikobehandlung sollten durch die Risikoeigentümer getroffen und dokumentiert werden. Das Ergebnis der vertiefenden Risikoanalyse ist ein detailliertes Verständnis der Risiken für Geschäftsprozesse mit erhöhtem Schutzbedarf, sowie zusätzlicher Anforderungen und Maßnahmen, die diese Risiken angemessen adressieren. Diese Ergebnisse werden in das Anforderungspaket integriert, das als Grundlage für die Umsetzung dient.
###  Wirksamkeitsprüfung 

tbd: Wirksamkeit über Restrisiken definieren
### Anforderungsergänzungen bei hohem Schutzbedarf

Die Anforderungsmodellierung für Anforderungen bei hohem Schutzbedarf folgende Schritte: 

1. Identifikation und Dokumentation der Anforderungen (Ergebnis der Risikobetrachtung). 

   2. Auswahl der Anforderungen mit Sicherheitsniveau erhöht aus dem Grundschutz++.

      3. Ggf. Erstellung von neuen Anforderungen in Bezug auf die Schutzziele (Vertraulichkeit, Integrität und Verfügbarkeit), um den Schutzbedarf zu erfüllen.  

      4. Erweiterung des Anforderungspaket um die Anforderungen für hohem Schutzbedarf.
## Gestaltungsentscheidungen

Durch die bisherigen Schritte wurde ein Anforderungspaket erstellt, mit dem die Institution ein zum Geltungsbereich passendes ISMS etablieren kann. Bevor mit der Umsetzung begonnen wird, gilt es nun noch zentrale Gestaltungsentscheidungen zu treffen. 

Parameter sind variabel gestaltbare Elemente innerhalb einer Anforderung, die Editoren, Auditoren und Anwendern Spielräume aufzeigen und zur automatisierten Prüfung genutzt werden können. Sie ermöglichen es, Anforderungen an spezifische Kontexte anzupassen. Sollte für ein Zielobjekt aus unterschiedlichen Vorgaben unterschiedliche Parametereinstellungen gefordert werden ist immer die die sicherste Einstellung zu wählen.
### Verteilung der führenden Zuständigkeiten

Jede Praktik enthält im Abschnitt „Grundlagen“ eine Anforderung zur Zuweisung einer Zuständigkeit zu bestimmten Personen oder Rollen. Durch das Setzen dieser Parameter wird festgelegt, welche Personen oder Rollen die führende Zuständigkeit für den zugeordneten Prozess erhalten. 

Dies wirkt sich auch auf das Anforderungspaket für Zielobjekte aus: Hier ist die Zuständigkeit für jede Anforderung anhand ihrer Praktik erkennbar. Potentiell bieten die Anforderungen weitere Möglichkeiten zur Flexibilisierung.
### Weitere Parameter

Bei manchen Anforderungen wird es eine Auswahl an möglichen einsetzbaren Werten geben, durch andere Normen und Standards vorgegeben sein können.

Eine Übersicht über alle verfügbaren Parameter kann man hier finden: Link einfügen zu GitHub
# Prozessschritt 3 \- Realisierung

Während der Realisierung werden die zuvor identifizierten Anforderungen in die Praxis überführt. Diese umfasst sowohl die Überprüfung des aktuellen Umsetzungsstatus als auch die Planung und Realisierung noch ausstehender Anforderungen. Grundalge hierfür ist das Anforderungspaket.

Der Umsetzungsprozessschritt beinhaltet folgende Aspekte:

* Die systematische Überprüfung des Umsetzungsstatus aller Anforderungen aus dem modellierten Anforderungspaket  
* Die Bewertung nicht umgesetzter Anforderungen mittels Risikoanalyse  
* Die strukturierte Planung und Priorisierung von Maßnahmen zur Erfüllung offener Anforderungen  
* Die Zuweisung von Zuständigkeiten und realistischen Umsetzungsfristen  
* Die Etablierung eines Freigabeverfahrens für die Umsetzungsplanung und den Umgang mit Ausnahmen  
* Die systematische Nachverfolgung des Umsetzungsfortschritts und die Überprüfung der Wirksamkeit umgesetzter Maßnahmen

Das Ergebnis dieses Prozessschrittes ist die kontrollierte Realisierung des Anforderungspaketes durch geeignete Maßnahmen sowie eine transparente Dokumentation des Umsetzungsstatus. Durch die klare Zuordnung von Verantwortlichkeiten und die systematische Fortschrittsverfolgung wird eine strukturierte und nachhaltige Umsetzung gewährleistet. Output dieses Prozessschritts ist der dokumentierte Umsetzungsstand sowie eine Maßnahmenplan.
## Überprüfung des Umsetzungsstatus 

Die Überprüfung des Umsetzungsstatus bildet den Ausgangspunkt der Umsetzung und dient der systematischen Erfassung des aktuellen Umsetzungsstands aller Anforderungen aus dem im Rahmen der Anforderungsanalyse erstellten Anforderungspakets. Dieser Schritt liefert ein klares Bild davon, welche Anforderungen bereits erfüllt sind und wo Handlungsbedarf besteht.

Bei der Überprüfung des Umsetzungsstatus gilt:

1. Für jede Anforderung muss der aktuelle Umsetzungsstatus vollständig überprüft werden  
2. Der Umsetzungsstatus einer Anforderung kann grundsätzlich nur „umgesetzt“ („ja“) oder „nicht umgesetzt“ („nein“) sein  
3. Eine Anforderung gilt nur als umgesetzt, wenn die Anforderungen selbst umgesetzt ist, sowie alle in Abhängigkeit stehenden Anforderungen umgesetzt sind. 

Für nicht umgesetzte jedoch für den Geschäftsprozess relevante Anforderungen (MUSS und SOLLTE) ist eine Risikoanalyse durchzuführen.

Die Überprüfung des Umsetzungsstatus sollte nach einem strukturierten Verfahren erfolgen, das eine konsistente Bewertung aller Anforderungen sicherstellt. Je nach Größe und Komplexität der Institution können unterschiedliche Methoden zum Einsatz kommen, von Interviews und Dokumentenprüfungen bis hin zu automatisierten Konfigurationsprüfungen und technischen Scans.

Der Prozessschritt 3 soll für die systematische Planung, Umsetzung und Dokumentation von Maßnahmen auf Basis der Anforderungen, die in Prozessschritt 2 abgeleitet wurden, sorgen. Der Prozessschritt soll sicherstellen, dass identifizierte Sicherheitsanforderungen durch effektive Maßnahmen umgesetzt werden.
## Bewertung fehlender Umsetzungen 

Die Bewertung der Restrisiken, die aus allen nicht umgesetzten Anforderungen resultieren, ist ein wichtiger Schritt zur Einschätzung der aktuellen Risikosituation und zur Priorisierung von Maßnahmen. Sie ermöglicht eine fundierte Entscheidungsfindung über den Umgang mit identifizierten Lücken. In manchen Fällen ist auch möglich die nicht Umsetzung der Anforderung nachvollziehbar zu begründen.

Die Restrisikobewertung muss in Form einer Risikoanalyse durchgeführt und nachgewiesen werden. Restrisikobewertung in einfacher strukturierter Übersicht können als Grundlage für die Priorisierung und Planung der Maßnahmen herangezogen werden, jedoch nicht für zertifizierungsrelevante Aspekte.
## Umsetzungsplanung und Priorisierung 

Die Umsetzungsplanung und Priorisierung transformiert die identifizierten Lücken in einen strukturierten Handlungsplan. Dieser Schritt ist entscheidend, um die verfügbaren Ressourcen effizient einzusetzen und die wichtigsten Risiken vorrangig zu adressieren.

Die Umsetzungsplanung umfasst folgende Aspekte:

* Festlegung konkreter Maßnahmen für die Umsetzung nicht erfüllter Anforderungen aus dem Anforderungspaket  
* Priorisierung der festgelegten Maßnahmen auf Basis der Risikoanalyse und weiterer relevanter Faktoren wie Abhängigkeiten und Ressourcenverfügbarkeit, sowie dem Aufwand  
* Berücksichtigung von Synergien zwischen Maßnahmen, die mehrere Anforderungen gleichzeitig adressieren können  
* Prüfung, ob ähnliche Defizite in anderen Bereichen bestehen und gemeinsame Lösungen entwickelt werden können

Die Priorisierung der Maßnahmen sollte nach klaren Kriterien erfolgen. Es sollten folgende Elemente berücksichtigt werden:

* Eine Priorisierung der Umsetzung muss auf Basis einer geeigneten Bewertung verankert werden, wobei die Maßnahmen zur Behandlung von Risiken höchste Priorität erhalten sollten.  
* Neben dem Risikopotenzial sollten auch Faktoren wie Umsetzungsaufwand, verfügbare Ressourcen und Abhängigkeiten in die Priorisierung einfließen.  
* Auch die strategische Bedeutung für die Unternehmensziele und mögliche Quick-Wins mit hoher Sichtbarkeit und Akzeptanz sollten berücksichtigt werden.

Das Verfahren zur Umsetzungsplanung sollte für die Institution angemessen sein und auf ihre eigenen Gegebenheiten und Prozesse abgestimmt sein. Für kleinere Institutionen kann eine einfachere Planung ausreichen, während größere und komplexere Institutionen ein detaillierteres Planungsverfahren benötigen.

Das Ergebnis der Umsetzungsplanung ist ein strukturierter und priorisierter Maßnahmenplan, der als Leitfaden für die systematische Verbesserung des Sicherheitsniveaus dient.
## Zuständigkeiten und Umsetzungsfristen 

Die eindeutige Festlegung von Zuständigkeiten und realistischen Umsetzungsfristen ist entscheidend für die erfolgreiche Realisierung des Maßnahmenplans. Dieser Schritt überführt die geplanten Maßnahmen in verbindliche Aufgaben mit klaren Verantwortlichkeiten und zeitlichen Vorgaben.

Bei der Festlegung von Zuständigkeiten und Fristen sind folgende Aspekte zu beachten:

* Für die effektive Umsetzung sind klare Zuständigkeiten und realistische Zeitpläne unerlässlich.  
* Die Zuständigen für die Umsetzung der Priorisierungen müssen eindeutig zugewiesen werden, wobei die zugewiesenen Personen oder Teams über die erforderlichen Kompetenzen und Ressourcen verfügen sollten.   
* Für jede umzusetzende Maßnahme muss ein realistisches Zieldatum festgelegt werden, das den Umfang, die verfügbaren Ressourcen und mögliche Abhängigkeiten berücksichtigt.  
* Die Zuweisung von Zuständigkeiten sollte in Abstimmung mit den betroffenen Bereichen erfolgen, um Akzeptanz und Kommittent zu fördern.  
* Fristen müssen den Umfang der Maßnahme, verfügbare Ressourcen und mögliche Abhängigkeiten berücksichtigen.

Die Zuweisung von Zuständigkeiten sollte in Abstimmung mit den betroffenen Bereichen und Personen erfolgen, um die Akzeptanz und das Kommittent zu fördern. Die festgelegten Zuständigkeiten und Fristen sollten in geeigneter Form dokumentiert werden, beispielsweise in einem Projektmanagement- oder Ticketsystem.

Insbesondere bei komplexeren Maßnahmen kann es sinnvoll sein, sowohl eine fachliche als auch eine operative Verantwortung zu definieren und bei Bedarf Teilaufgaben mit eigenen Verantwortlichkeiten und Fristen zu bilden.
## Freigabeverfahren und Ausnahmemanagement 

Die Freigabeprozesse gewährleisten die formale Absicherung von Entscheidungen und den kontrollierten Umgang mit Abweichungen von den Anforderungen.

Freigabeverfahren und Ausnahmemanagement umfassen folgende Aspekte:

* die Freigabe der Umsetzungsplanung muss durch die Risikoeigentümer dokumentiert werden  
* die Kenntnisnahme des Restrisikos durch die Risikoeigentümer sollte dokumentiert werden  
* Ausnahmegenehmigungen für Compliance-Verpflichtungen müssen durch eine zuständige Person oder Rolle autorisiert werden  
* jede Ausnahmegenehmigung muss mit einer nachvollziehbaren Begründung dokumentiert werden

Bei Zielkonflikten zwischen verschiedenen Verpflichtungen müssen diese gegeneinander abgewogen (Risikoeinschätzung) und bei Bedarf Ausnahmegenehmigungen eingeholt werden. Zur Entscheidungsfindung kann eine Risikoabschätzung vorgenommen werden, die die potenziellen Auswirkungen unterschiedlicher Handlungsoptionen bewertet.

Die Dokumentation von Ausnahmegenehmigungen ist besonders wichtig, um rechtlich bedeutsame Entscheidungen zur Informationsverarbeitung später nachvollziehen und gegebenenfalls anpassen zu können. Über Ausnahmegenehmigungen entscheidet die Leitung. Diese Dokumentation muss nicht zwingend separat erfolgen, sondern kann in bestehende Systeme wie CMDBs, Aktenverzeichnisse, Commit-Messages oder Ticketsysteme integriert werden.

Ein strukturiertes Freigabe- und Ausnahmemanagement schafft Rechtssicherheit und Transparenz und stellt sicher, dass Abweichungen von Anforderungen bewusst und kontrolliert erfolgen.
## Fortschrittsverfolgung der Realisierung

Die systematische Nachverfolgung des Umsetzungsfortschritts ist entscheidend, um den Erfolg der Umsetzung zu gewährleisten und bei Bedarf korrigierend einzugreifen. Diese regelmäßige Überwachung sichert die nachhaltige Verbesserung des Sicherheitsniveaus.

Für eine effektive Fortschrittsverfolgung muss ein Verfahren zur systematischen Nachverfolgung der Maßnahmenumsetzung verankert werden. Dieses Verfahren sollte folgende Elemente umfassen:

* ein Verfahren für die systematische Nachverfolgung der Maßnahmenumsetzung 

* ein Verfahren zur kontinuierlichen Fortschreibung des Umsetzungsplans, um auf veränderte Bedingungen oder neue Erkenntnisse reagieren zu können

* Dokumentation des aktuellen Umsetzungsstands und etwaiger Abweichungen vom Plan

* Frühzeitige Identifikation von Hindernissen oder Verzögerungen 

* Eskalationspfade für Maßnahmen, die nicht planmäßig umgesetzt werden können

* Regelmäßige Statusberichte an Verantwortliche und das Management (z.B. im Managementbericht)

Die Fortschrittsverfolgung sollte in regelmäßigen Abständen erfolgen und den aktuellen Status jeder Maßnahme transparent dokumentieren. Bei Verzögerungen oder Problemen sollten frühzeitig geeignete Gegenmaßnahmen ergriffen werden.

Die Fortschreibung des Umsetzungsplans gewährleistet, dass dieser aktuell bleibt und neue Erkenntnisse, veränderte Rahmenbedingungen oder angepasste Prioritäten berücksichtigt werden (siehe Prozessschritt 7). Der Plan sollte als lebendes Dokument betrachtet werden, das regelmäßig überprüft und angepasst wird.
## Wahrung von Compliance in der Umsetzung 

Die regelmäßige Überprüfung und Aktualisierung der Compliance-bezogenen Prozesse und Anweisungen stellt sicher, dass sie aktuell und wirksam bleiben, auch wenn sich die regulatorischen Anforderungen ändern. Diese kontinuierliche Anpassung ist ein wesentlicher Bestandteil eines lebendigen und effektiven Compliance-Managements innerhalb des ISMS. (siehe Prozessschritt 1\)

Es ist ein Verfahren zu definieren (z.B. Prüflisten oder Auditierung) wie Compliance im Umsetzungsprozess überprüft werden.
# Prozessschritt 4 \- Überwachung

Der Prozessschritt der Überwachung dient der regelmäßigen Überwachung und Bewertung des ISMS und der umgesetzten Maßnahmen. Die zugrundeliegenden Anforderungen in der Praktik Monitoring und Evaluation sind entscheidend, um die Wirksamkeit des ISMS zu gewährleisten und eine fundierte Grundlage für Verbesserungsentscheidungen zu schaffen.

Die zentralen Elemente sind:

* die Etablierung von Verfahren zur systematischen Messung und Bewertung der ISMS-Leistung  
* die regelmäßige und anlassbezogene Überwachung der Einhaltung von Compliance-Anforderungen  
* die Planung und Durchführung eines strukturierten Auditprogramms mit risikoorientierten internen Audits  
* die Anwendung einheitlicher Bewertungsschemata und die Erstellung aussagekräftiger Auditberichte  
* die regelmäßige Durchführung von Managementbewertungen zur Überprüfung der Eignung, Angemessenheit und Wirksamkeit des ISMS. Die Ergebnisse der Managementbewertung sollten in einem Managementbericht dokumentiert werden.  
* die Implementierung geeigneter Monitoring-Methoden und \-tools zur frühzeitigen Erkennung von Sicherheitsvorfällen und Schwachstellen  
* die regelmäßige Verifikation des Anforderungspaketes auf seine Aktualität und Angemessenheit

Die folgende Abbildung zeigt die Fragestellungen auf, die in diesem Prozessschritt beantwortet werden.

Das Ergebnis dieses Prozessschrittes ist ein umfassendes Bild des aktuellen Sicherheitsstatus, das sowohl technische wie organisatorische Aspekte berücksichtigt. Die gewonnenen Erkenntnisse fließen direkt in die Praktik Verbesserung ein und bilden die Grundlage für fundierte Managemententscheidungen.
## Leistungsbewertung des ISMS 

Die systematische Leistungsbewertung des ISMS ist von grundlegender Bedeutung, um den Erfolg der umgesetzten Anforderungen zu messen, Schwachpunkte zu identifizieren und kontinuierliche Verbesserungen zu ermöglichen. Sie liefert die notwendigen Informationen für fundierte Managemententscheidungen und sichert die langfristige Wirksamkeit des ISMS.

Für eine effektive Leistungsbewertung müssen Verfahren und Regelungen zur Messung und Bewertung der ISMS-Leistung verankert werden. 

Diese Verfahren sollten verschiedene Perspektiven und Informationsquellen berücksichtigen:

* Die Überprüfung der Umsetzung von Maßnahmen zur Behandlung von Auditergebnissen und zur kontinuierlichen Verbesserung stellt sicher, dass identifizierte Schwachstellen behoben und Optimierungspotenziale genutzt werden.  
* Die Auswertung von Maßnahmen aus der Nachbereitung von Sicherheitsvorfällen ermöglicht es, aus Vorfällen zu lernen und wiederkehrende Probleme durch geeignete präventive Maßnahmen zu vermeiden.   
* Die Auswertung der Gefährdungslage in Bezug auf aktuelle Veränderungen ermöglicht eine proaktive Anpassung an neue Bedrohungen und stellt sicher, dass die Institution auf veränderte Risiken reagieren kann.  
* Die Auswertung des Umsetzungsplans in Bezug auf den Fortschritt, die Einhaltung oder Überschreitung von Umsetzungsdaten und inhaltliche Korrektheit gibt Aufschluss über den aktuellen Status der Umsetzung.

Die Leistungsbewertung des ISMS sollte in regelmäßigen Abständen sowie anlassbezogen, u.a. bei Aktualisierungen von Anforderungen in der Stand der Technik Bibliothek durchgeführt werden und alle relevanten Aspekte des Informationssicherheitsmanagements umfassen. Die Ergebnisse sollten strukturiert dokumentiert und an die relevanten Stakeholder kommuniziert werden, um die kontinuierliche Verbesserung des ISMS zu unterstützen.
## Überwachung der Compliance 

Die systematische Überwachung der Einhaltung von gesetzlichen, regulatorischen und vertraglichen Verpflichtungen (Compliance) ist ein zentraler Aspekt des Monitorings und der Evaluation. Sie dient der Vermeidung rechtlicher Konsequenzen, finanzieller Verluste und Reputationsschäden durch Compliance-Verstöße.

Im Rahmen der Compliance-Überwachung sollte die Einhaltung von Verpflichtungen regelmäßig sowie anlassbezogen überprüft werden. Dies umfasst:

* Regelmäßige Kontrollen zur Überprüfung der Einhaltung dokumentierter gesetzlicher und vertraglicher Anforderungen  
* Anlassbezogene Überprüfungen bei Änderungen des regulatorischen Umfelds, bei Hinweisen auf mögliche Verstöße oder nach durchgeführten Änderungen in relevanten Systemen oder Prozessen  
* Identifikation von Compliance-Lücken und deren systematische Dokumentation  
* Entwicklung und Umsetzung von Maßnahmen zur Schließung identifizierter Compliance-Lücken

Die Überwachungsaktivitäten sollten risikoorientiert erfolgen, wobei besonderes Augenmerk auf Bereiche mit hoher rechtlicher Relevanz oder potenziell schwerwiegenden Konsequenzen bei Verstößen gelegt werden sollte. Die Ergebnisse der Compliance-Überwachung sollten dokumentiert und in den kontinuierlichen Verbesserungsprozess eingespeist werden.

Eine effektive Compliance-Überwachung erfordert eine enge Zusammenarbeit zwischen der Informationssicherheitsorganisation und anderen relevanten Funktionen wie der Rechtsabteilung, dem Datenschutzbeauftragten, BCM-Beauftragter und den Fachverantwortlichen für branchenspezifische Vorschriften. Diese Zusammenarbeit gewährleistet eine umfassende Abdeckung aller relevanten Compliance-Aspekte.
## Auditprogramm und \-durchführung[^2]

Ein systematisches Auditprogramm (intern) ist ein wesentliches Instrument zur unabhängigen Überprüfung und Bewertung der Wirksamkeit des ISMS.

Für den Aufbau und die Durchführung eines wirksamen Auditprogramms sind folgende Elemente erforderlich:

* Ein Verfahren zum Aufbau und zur Pflege eines oder mehrerer Auditprogramme muss verankert werden, dass die systematische Planung, Durchführung und Nachverfolgung von Audits ermöglicht.  
* Die Planung der internen Audits im Auditprogramm muss risikoorientiert erfolgen und dokumentiert werden. Dabei sollte sichergestellt werden, dass die Effektivität und Effizienz aller angewandten Praktiken mindestens einmal sinnvoll geprüft werden.  
* Ein Verfahren zur Auswahl von fachlich geeigneten und unabhängigen Auditoren muss etabliert werden, um die Objektivität und Qualität der Audits zu gewährleisten. Die Auditoren sollten über die erforderlichen Kenntnisse und Erfahrungen verfügen und von den zu auditierenden Bereichen unabhängig sein.  
* Für jedes durchzuführende Audit sollten Auditpläne dokumentiert werden, die folgende Elemente enthalten: Auditziele, Auditumfang, Auditkriterien, zu auditierende Standorte, eingesetzte Auditmethoden, Rollen und Zuständigkeiten.  
* Audits müssen in angemessenem Umfang durchgeführt werden, um aussagekräftige Ergebnisse zu liefern, ohne übermäßige Ressourcen zu binden.

Die Durchführung von Audits sollte nach einem strukturierten Prozess erfolgen, der die Vorbereitung, Durchführung, Berichterstattung und Nachverfolgung umfasst. Der Prozess sollte flexible Methoden wie Interviews, Dokumentenprüfungen, Beobachtungen oder Stichproben ermöglichen, die je nach Auditgegenstand und \-ziel angemessen kombiniert werden können.

Ein gut konzipiertes und durchgeführtes Auditprogramm liefert wertvolle Erkenntnisse über die Wirksamkeit des ISMS und bildet eine wichtige Grundlage für die kontinuierliche Verbesserung der Informationssicherheit.
## Bewertungsschemata und Auditberichte 

Die Erstellung aussagekräftiger Auditberichte auf Basis einheitlicher Bewertungsschemata ist entscheidend für die Wirksamkeit des Auditprozesses und die Vergleichbarkeit der Ergebnisse. Ein strukturiertes Vorgehen in diesem Bereich fördert die Objektivität der Bewertung und erleichtert die Kommunikation und Nachverfolgung der Feststellungen.

Für eine effektive Bewertung und Berichterstattung sind folgende Elemente zu etablieren:

* Ein einheitliches Bewertungsschema für Feststellungen in Audits sollte verankert werden, um die konsistente Bewertung und Vergleichbarkeit von Auditergebnissen sicherzustellen.  
* Auditergebnisse müssen in strukturierten Berichten dokumentiert werden, die eine klare und nachvollziehbare Darstellung der Feststellungen, ihrer Bewertung und der empfohlenen Maßnahmen enthalten. Die Berichte sollten sowohl für das Management als auch für die fachlich Verantwortlichen verständlich sein.  
* Die Auditberichte sollten neben den identifizierten Schwachstellen auch positive Feststellungen enthalten, um ein ausgewogenes Bild zu vermitteln und Best Practices zu fördern.  
* Eine angemessene Kommunikation der Auditergebnisse an alle relevanten Stakeholder muss sichergestellt werden, um das Bewusstsein für identifizierte Risiken zu schärfen und die Umsetzung von Verbesserungsmaßnahmen zu fördern.

Das Bewertungsschema und die Struktur der Auditberichte sollten an die Größe und Komplexität der Institution angepasst sein. Während in kleineren Institutionen einfachere Schemata und Berichtsformate ausreichend sein können, benötigen größere und komplexere Institutionen oft differenziertere Ansätze, um die verschiedenen Aspekte und Ebenen der Informationssicherheit angemessen zu erfassen und zu bewerten.

Eine transparente und konsistente Bewertung und Berichterstattung schafft eine solide Grundlage für die Nachverfolgung von Feststellungen und die kontinuierliche Verbesserung des ISMS.
## Managementbewertungen 

Die Ergebnisse der Managementbewertung sollten in einem Managementbericht dokumentiert und in konkrete Entscheidungen und Maßnahmen zur Weiterentwicklung des ISMS überführt werden. Diese bilden die Grundlage für die strategische Ausrichtung der Informationssicherheit und fließen in die Planung der Ressourcen und Prioritäten für den kommenden Berichtszeitraum ein.

Die regelmäßige Durchführung von Managementbewertungen fördert die kontinuierliche Aufmerksamkeit der Institutionsleitung für das Thema Informationssicherheit und stellt sicher, dass das ISMS nicht nur operativ funktioniert, sondern auch strategisch ausgerichtet bleibt und die Ziele der Institution unterstützt. Sie schafft zudem einen formalen Rahmen für die Dokumentation wichtiger Entscheidungen zur Informationssicherheit, was besonders bei späteren Audits oder im Falle von Sicherheitsvorfällen von Bedeutung sein kann.
## Monitoringmethoden und \-tools 

Effektive Monitoring-Methoden und \-tools sind essentiell, um die regelmäßige Überwachung der Informationssicherheit zu gewährleisten und frühzeitig auf Sicherheitsvorfälle, Schwachstellen und neue Risiken reagieren zu können. Sie bilden die technische und methodische Grundlage für eine proaktive Informationssicherheit.

Im Rahmen des Monitorings müssen folgende Verfahren verankert werden:

* Ein Verfahren zur Erkennung von Sicherheitsvorfällen, das die frühzeitige Identifikation und Meldung von Vorfällen ermöglicht. Dies kann von manuellen Prozessen bis hin zu automatisierten Erkennungssystemen reichen, je nach Größe und Komplexität der Institution.  
* Ein Verfahren für den Umgang mit Schwachstellen und ihre Berücksichtigung im Risikomanagement. Dieses Verfahren sollte die systematische Identifikation, Bewertung, Behandlung und Nachverfolgung von Schwachstellen umfassen.  
* Ein Verfahren für die Erfassung und die Reaktion auf aktuelle Risiken und ihre Berücksichtigung im Risikomanagement, um neu auftretende Bedrohungen zeitnah zu adressieren.  
* In größeren Institutionen oder bei erhöhtem Schutzbedarf können spezialisierte Tools die Überwachung unterstützen:  
  * Security Information and Event Management (SIEM) Systeme für die zentrale Sammlung, Korrelation und Analyse von Sicherheitsereignissen aus verschiedenen Quellen  
  * Intrusion Detection/Prevention Systeme (IDS/IPS) zur Erkennung und Abwehr verdächtiger Netzwerkaktivitäten  
  * Vulnerability Management Systeme zur systematischen Identifikation und Behandlung von Schwachstellen  
  * Configuration Monitoring Tools zur Überwachung von Konfigurationsänderungen in Systemen und Anwendungen

Die Implementierung dieser Monitoring-Methoden und \-tools sollte an die individuellen Bedürfnisse und Möglichkeiten der Institution angepasst sein. Während kleinere Institutionen mit einfacheren Lösungen arbeiten können, benötigen größere und komplexere Umgebungen oft umfassendere und stärker automatisierte Ansätze.

Die gewonnenen Monitoring-Daten sollten systematisch ausgewertet und für verschiedene Zwecke genutzt werden, darunter die Erstellung von Kennzahlen und Berichten, die Früherkennung von Sicherheitsrisiken, die Unterstützung der Incident Response und die kontinuierliche Verbesserung des ISMS.
## Verifikation der Anforderungen 

Die regelmäßige Verifikation der Aktualität der Anforderungen ist für die Aufrechterhaltung des Sicherheitsniveaus wichtig. Im Aspekt des Monitorings und der Evaluation, muss sichergestellt werden, dass die gewählten Anforderungen weiterhin für den Informationsverbund angemessen und aktuell sind. Dieser Prozess hilft, die Modellierung des ISMS an veränderte Bedingungen anzupassen und die Wirksamkeit des Sicherheitskonzeptes zu gewährleisten.

Die Verifikation sollte folgende Aspekte umfassen:

* Das Anforderungspaket sollte regelmäßig (i.A. jährlich, je nach Organisationsgröße, Parameter und Prüftiefe) in Hinblick auf die Modellierung überprüft werden, um ihre Aktualität und Angemessenheit zu bewerten.  
* Bei der Überprüfung sollten veränderte Geschäftsprozesse, neue IT-Komponenten, organisatorische Änderungen und externe Faktoren wie neue regulatorische Anforderungen oder veränderte Bedrohungslandschaften sowie neue Anforderungen im Grundschutz++ und die Zielobjekt-Hierarchie berücksichtigt werden.  
* Die Überprüfung sollte in Abstimmung mit den zuständigen Bereichen erfolgen, um sicherzustellen, dass alle relevanten Perspektiven einbezogen werden.  
* Bei Bedarf sollten Anpassungen der Auswahl der Anforderungen vorgenommen werden, um den aktuellen Anforderungen gerecht zu werden.

Die Verifikation dient nicht nur der Aktualisierung des ISMS-Modells, sondern auch als Qualitätssicherungsmaßnahme. Sie stellt sicher, dass die grundlegende Struktur des ISMS mit den tatsächlichen Gegebenheiten der Institution übereinstimmt und dass keine relevanten Anforderungen übersehen werden.

Die Ergebnisse der Verifikation sollten dokumentiert und bei Bedarf in die kontinuierliche Verbesserung des ISMS einbezogen werden. Wenn signifikante Anpassungen erforderlich sind, können diese zu einer Neumodellierung oder Erweiterung des Anforderungspakets führen, was wiederum den gesamten Zyklus der Strukturmodellierung und Umsetzung beeinflusst.

Das Monitoring und die Evaluation sind entscheidend für die Wirksamkeit und kontinuierliche Verbesserung des ISMS. Durch die systematische Leistungsbewertung, die Überwachung der Compliance, ein strukturiertes Auditprogramm, aussagekräftige Bewertungsschemata und Berichte, regelmäßige Managementbewertungen, effektive Monitoring-Methoden und eine Verifikation wird sichergestellt, dass das ISMS seinen Zweck erfüllt und sich dynamisch an veränderte Anforderungen anpassen kann.

Die in diesem Prozessschritt gewonnenen Erkenntnisse bilden die Grundlage für die kontinuierliche Verbesserung des ISMS und unterstützen die Institution dabei, ein angemessenes Sicherheitsniveau zu erreichen und aufrechtzuerhalten. Sie liefern zudem wichtige Informationen für strategische Entscheidungen zur Weiterentwicklung der Informationssicherheit und zur Ausrichtung an den Geschäftszielen der Institution.
# Prozessschritt 5 – kontinuierliche Verbesserung 

Die kontinuierliche Verbesserung schließt den PDCA-Zyklus der Methodik-GS++ ab und stellt sicher, dass die Informationssicherheit stetig weiterentwickelt wird. In diesem Prozessschritt werden Erkenntnisse aus der Überwachung in konkrete Verbesserungsmaßnahmen umgesetzt.

Die kontinuierliche Verbesserung umfasst:

* die systematische Analyse von Nicht-Konformitäten hinsichtlich ihrer Ursachen und möglichen Wiederauftretens  
* die Identifikation und Bewertung von Verbesserungspotenzialen unter Berücksichtigung der damit verbundenen Risiken  
* die Einleitung angemessener Korrekturmaßnahmen zur Beseitigung von Fehlerursachen und Maßnahmen zur Nutzung von Verbesserungspotenzialen  
* die risikoorientierte Priorisierung von Verbesserungsmaßnahmen und die eindeutige Zuweisung von Zuständigkeiten  
* die systematische Nachverfolgung des Umsetzungsfortschritts und die Überprüfung der Wirksamkeit der Verbesserungen  
* die Bewertung der erreichten Verbesserung und ihre Auswirkung auf das Gesamtsicherheitsniveau  
* die Etablierung und Anwendung eines strukturierten Verfahrens zur Behandlung von Compliance-Verstößen

Als Ergebnis dieses Prozessschrittes werden identifizierte Schwachstellen beseitigt, Verbesserungspotenziale genutzt und das ISMS kontinuierlich an veränderte Rahmenbedingungen angepasst.
## Umgang mit Nicht-Konformitäten

Der systematische Umgang mit Nicht-Konformitäten ist ein zentraler Bestandteil des kontinuierlichen Verbesserungsprozesses. Nicht-Konformitäten – also Abweichungen von definierten Anforderungen, Standards oder Erwartungen – stellen wichtige Indikatoren für Verbesserungspotenzial dar und müssen strukturiert behandelt werden, um die Wirksamkeit des ISMS zu steigern.

Im Rahmen des kontinuierlichen Verbesserungsprozesses muss eine Methode zur Überprüfung von Nicht-Konformitäten hinsichtlich ihrer Ursachen und möglichen Wiederauftretens verankert werden. Diese Methode sollte folgende Aspekte umfassen:

* eine systematische Erfassung und Dokumentation aller identifizierten Nicht-Konformitäten, unabhängig davon, ob sie durch interne Audits, externe Prüfungen, Vorfälle oder im Rahmen des regulären Betriebs entdeckt wurden,  
* eine gründliche Ursachenanalyse, die nicht nur die unmittelbaren, sondern auch die grundlegenden Ursachen der Nicht-Konformität identifiziert (Root-Cause-Analysis),  
* eine Bewertung der Wahrscheinlichkeit des Wiederauftretens und der potenziellen Auswirkungen bei erneutem Auftreten,  
* eine Überprüfung, ob ähnliche Nicht-Konformitäten in anderen Bereichen der Institution bestehen oder auftreten könnten und  
* eine Analyse, inwieweit die Nicht-Konformität auf systemische Schwächen im ISMS hinweist und ob grundlegende Anpassungen des ISMS erforderlich sind.

Die Nicht-Konformitäten sollten hinsichtlich der Notwendigkeit zur Anpassung des ISMS überprüft werden. Nicht jede Nicht-Konformität erfordert strukturelle Änderungen am ISMS; einige können durch isolierte Korrekturmaßnahmen behoben werden. Bei wiederholten oder systematischen Nicht-Konformitäten sollten jedoch die zugrundeliegenden Prozesse, Richtlinien oder Verantwortlichkeiten überprüft und bei Bedarf angepasst werden.

Ein wirksamer Umgang mit Nicht-Konformitäten fördert die Lernkultur innerhalb der Institution und hilft, wiederkehrende Probleme zu vermeiden. Die transparente Dokumentation und Kommunikation der Ergebnisse unterstützt zudem die Sensibilisierung für Informationssicherheitsaspekte und die kontinuierliche Verbesserung des gesamten ISMS.
## Identifikation von Verbesserungspotenzialen 

Die Identifikation von Verbesserungspotenzialen ist ein wesentlicher Treiber für die kontinuierliche Weiterentwicklung des ISMS. Im Gegensatz zum reaktiven Umgang mit Nicht-Konformitäten zielt dieser Ansatz darauf ab, auch ohne vorangegangene Probleme oder Abweichungen Optimierungsmöglichkeiten zu erkennen und zu nutzen.

Eine Methode zur Überprüfung und Bewertung von Verbesserungspotenzialen unter Berücksichtigung von Risiken sollte verankert werden. Diese Methode beinhaltet typischerweise:

* die Bewertung des Umfelds der Institution (z. B. Bewertung der Gefährdungslage), um frühzeitig auf veränderte externe Faktoren reagieren zu können und neue Ansätze zur Risikominimierung zu identifizieren,  
* die systematische Auswertung des Umsetzungsplans, um Erkenntnisse über Effizienz und Effektivität der bisherigen Maßnahmenplanung und \-umsetzung zu gewinnen,  
* die Analyse von Auditergebnissen nicht nur hinsichtlich identifizierter Schwachstellen, sondern auch in Bezug auf mögliche Prozessoptimierungen und Best Practices,  
* die Auswertung von Sicherheitsvorfällen, um über die unmittelbare Behebung hinaus langfristige Verbesserungen zu initiieren und  
* die Berücksichtigung von Ad-hoc-Eingaben (z. B. Vorschläge von Mitarbeitern, neue technologische Entwicklungen), die akute Verbesserungspotenziale aufzeigen können.

Bei der Bewertung von Verbesserungspotenzialen ist eine risikoorientierte Herangehensweise wichtig. Nicht jede Verbesserungsmöglichkeit bietet denselben Mehrwert für die Institution.   
Die Bewertung sollte daher folgende Aspekte berücksichtigen:

* das Potenzial zur Risikoreduktion  
* den erwarteten Ressourcenaufwand  
* die strategische Bedeutung für die Informationssicherheitsziele  
* mögliche Synergien mit anderen Verbesserungsmaßnahmen oder Projekten  
* die Nachhaltigkeit der Verbesserung

Die systematische Identifikation und Bewertung von Verbesserungspotenzialen fördert eine zukunftsorientierte Sicherheitskultur und unterstützt die Institution dabei, ihr ISMS kontinuierlich an neue Anforderungen und Möglichkeiten anzupassen. Sie ist ein wesentlicher Bestandteil eines lebenden ISMS, das sich proaktiv weiterentwickelt, anstatt nur auf Probleme zu reagieren.
## Korrektur- und Verbesserungsvorschläge 

Auf Basis der identifizierten Nicht-Konformitäten und Verbesserungspotenziale müssen angemessene Korrektur- und Verbesserungsvorschläge entwickelt und umgesetzt werden. Diese Vorschläge bilden den aktiven Teil des kontinuierlichen Verbesserungsprozesses und überführen die gewonnenen Erkenntnisse in konkrete Handlungen in den anstehenden Durchführungszyklen (PDCA).

Bei der Entwicklung von Korrekturen zur Beseitigung von Fehlerursachen sollten folgende Aspekte berücksichtigt werden:

* Die Korrekturen müssen die identifizierten Grundursachen adressieren und nicht nur die Symptome beheben.  
* Die Korrekturen sollten angemessen und verhältnismäßig sein, also in einem sinnvollen Verhältnis zum Risiko oder zur Bedeutung der Nicht-Konformität stehen.  
* Die Korrekturen sollten nachhaltig wirken und wiederkehrende Probleme verhindern.  
* Je nach Ursache können unterschiedliche Arten von Korrekturen erforderlich sein:  
  * Organisatorische Anpassungen wie die Überarbeitung von Prozessen, Richtlinien oder Zuständigkeiten  
  * Personelle Anpassungen wie Schulungen, Sensibilisierung oder in schwerwiegenden Fällen disziplinarische Schritte  
  * Infrastrukturelle Änderungen wie bauliche Anpassungen oder Verbesserungen der physischen Sicherheit  
  * Technische Anpassungen an Hardware, Software oder Netzwerkinfrastruktur  
  * Strategische Korrekturen, die eine Entscheidung oder Unterstützung der Institutionsleitung erfordern

Für Verbesserungen zur Nutzung identifizierter Potenziale sollte ein ähnlich strukturierter Ansatz verfolgt werden. Diese Korrekturen zielen nicht primär auf die Behebung von Problemen, sondern auf die proaktive Weiterentwicklung des ISMS. Sie können beispielsweise folgende Bereiche adressieren:

* Optimierung von Prozessen und Abläufen im ISMS  
* Einführung neuer oder verbesserter Technologien und Methoden  
* Stärkung der Sicherheitskultur und des Sicherheitsbewusstseins  
* Erweiterung des Anwendungsbereiches des ISMS  
* Verbesserung der Integration des ISMS in andere Managementsysteme und Geschäftsprozesse

Sowohl Korrekturen als auch Verbesserungen sollten sorgfältig geplant, dokumentiert und nachverfolgt werden (siehe Proessschritt 1). Die angemessene Ressourcenausstattung und die klare Zuweisung von Verantwortlichkeiten sind dabei entscheidende Erfolgsfaktoren.
## Korrektur- und Verbesserungsplan

Die systematische Priorisierung und Umsetzung der identifizierten Korrekturen und Verbesserungen ist entscheidend für einen effektiven kontinuierlichen Verbesserungsprozess. Angesichts begrenzter Ressourcen müssen Institutionen sicherstellen, dass die wichtigsten Änderungen zuerst umgesetzt werden und alle Aktivitäten koordiniert ablaufen.

Dabei sollte die Korrektur und Verbesserungsplanung direkt in die Umsetzungsplan und mit einfließen. (siehe Prozessschritte 3 Realisierung).

Die festgelegten Korrekturen, Verbesserungen, Zuständigkeiten und Fristen sollten in geeigneter Form dokumentiert werden, beispielsweise in einem Projektmanagement- oder Ticketsystem. Bei komplexeren Änderungen kann es sinnvoll sein, sowohl eine fachliche als auch eine operative Verantwortung zu definieren und bei Bedarf Teilaufgaben mit eigenen Verantwortlichkeiten und Fristen zu bilden.

Eine transparente Kommunikation des Korrektur- und Verbesserungsplans an alle Beteiligten fördert das gemeinsame Verständnis und die Akzeptanz. Regelmäßige Statusberichte und Updates (z.B. im Managementbericht), helfen den Fortschritt zu überwachen und bei Bedarf frühzeitig gegenzusteuern.

Die Priorisierung und Umsetzung von Korrekturen und Verbesserungen stellen sicher, dass die kontinuierliche Verbesserung nicht nur theoretisch bleibt, sondern zu konkreten und messbaren Fortschritten führt. Sie unterstützt die Institution dabei, ihre begrenzten Ressourcen optimal einzusetzen und die größtmögliche Wirkung im Sinne der Informationssicherheit zu erzielen.
## Fortschrittsverfolgung und Wirksamkeitsprüfung 

Eine systematische Fortschrittsverfolgung und Wirksamkeitsprüfung ist unverzichtbar, um den Erfolg der kontinuierlichen Verbesserung zu gewährleisten und bei Bedarf rechtzeitig nachsteuern zu können. Dieser Prozess schließt die Lücke zwischen der Planung und Umsetzung von Maßnahmen einerseits und der Bewertung ihrer tatsächlichen Wirkung andererseits.

Neben der reinen Fortschrittsverfolgung ist die Überprüfung der Wirksamkeit umgesetzter Maßnahmen von entscheidender Bedeutung. Während die Fortschrittsverfolgung (siehe Prozessschritt 3 Fortschrittsverfolgung der Realisierung) prüft, ob eine Maßnahme wie geplant umgesetzt wurde, bewertet die Wirksamkeitsprüfung, ob die Maßnahme auch den beabsichtigten Effekt erzielt hat. Hierfür sollten folgende Aspekte berücksichtigt werden:

* Definition klarer, messbarer Kriterien für die Wirksamkeit jeder Maßnahme  
* Durchführung gezielter Tests, Audits oder Überprüfungen nach Abschluss der Umsetzung  
* Bewertung, ob die identifizierten Nicht-Konformitäten tatsächlich beseitigt oder die angestrebten Verbesserungen erreicht wurden  
* Dokumentation der Ergebnisse der Wirksamkeitsprüfung

Ein Verfahren zur kontinuierlichen Fortschreibung des Umsetzungsplans muss ebenfalls verankert werden. Dieses sollte sicherstellen, dass der Plan regelmäßig überprüft und bei Bedarf angepasst wird, um auf veränderte Bedingungen, neue Erkenntnisse oder unerwartete Herausforderungen zu reagieren. Die Fortschreibung kann umfassen:

* Anpassung von Zeitplänen und Ressourcenzuweisungen  
* Neubewertung von Prioritäten  
* Ergänzung neuer Maßnahmen oder Streichung nicht mehr relevanter Maßnahmen  
* Integration von Erkenntnissen aus der Wirksamkeitsprüfung

Die Fortschrittsverfolgung und Wirksamkeitsprüfung stellt sicher, dass der kontinuierliche Verbesserungsprozess zu messbaren und nachhaltigen Fortschritten führt. Sie schafft Transparenz über den aktuellen Status und unterstützt die Institution dabei, ihre Ressourcen optimal einzusetzen und den Erfolg ihrer Verbesserungsbemühungen zu demonstrieren.
## Bewertung der erreichten Verbesserung 

Die systematische Bewertung der erreichten Verbesserungen ist ein wesentlicher Schritt, um den Erfolg des kontinuierlichen Verbesserungsprozesses zu messen und zukünftige Entwicklungen zu steuern. Sie schafft Transparenz über die erzielten Fortschritte und ermöglicht eine fundierte Entscheidungsfindung für die weitere Entwicklung des ISMS.

Für eine strukturierte Bewertung sollte ein Verfahren zur Bewertung der umgesetzten Verbesserungspotenziale hinsichtlich der Risiken verankert werden. 

Dieses Verfahren sollte folgende Aspekte umfassen:

* Eine risikoorientierte Beurteilung der Wirkung umgesetzter Verbesserungsmaßnahmen auf das Gesamtrisiko der Institution.  
* Eine Analyse des Verhältnisses zwischen investierten Ressourcen und erzielten Verbesserungen (Return on Security Investment).  
* Eine Bewertung des Beitrags der Verbesserungen zur Erreichung der strategischen Informationssicherheitsziele.  
* Eine Überprüfung der Nachhaltigkeit der erzielten Verbesserungen.

Ein zentrales Element der Bewertung ist die transparente Darstellung des Sicherheitsniveaus der Institution. Diese sollte so gestaltet sein, dass sie für verschiedene Zielgruppen, insbesondere für die Institutionsleitung, verständlich und aussagekräftig ist. 

Dazu können beispielsweise folgende Instrumente eingesetzt werden:

* Grafische Darstellungen des Sicherheitsniveaus in verschiedenen Bereichen  
* Kennzahlen und KPIs zur Messung des Sicherheitszustands  
* Vergleiche mit Branchen-Benchmarks oder Standards  
* Trendanalysen zur Visualisierung der Entwicklung über die Zeit

Ein besonderer Fokus sollte auf der Trendanalyse im Vergleich zu vorherigen Bewertungen liegen. Diese ermöglicht es, die Entwicklung des Sicherheitsniveaus über längere Zeiträume zu verfolgen und frühzeitig Verbesserungen oder Verschlechterungen zu erkennen. Folgende Aspekte sind dabei relevant:

* Konsistente Bewertungsmethodik über verschiedene Zeitpunkte hinweg, um Vergleichbarkeit zu gewährleisten  
* Berücksichtigung veränderter Rahmenbedingungen oder neuer Anforderungen bei der Interpretation von Trends  
* Analyse von Korrelationen zwischen umgesetzten Maßnahmen und beobachteten Veränderungen des Sicherheitsniveaus  
* Identifikation von Bereichen mit positiver oder negativer Entwicklung als Grundlage für zukünftige Prioritätensetzung

Im Ergebnis ist das Sicherheitsniveau der Institution transparent dargestellt und Trends in der Entwicklung (insbesondere auch durch die Vergleichbarkeit mit vorigen Bewertungen) werden deutlich. Diese Informationen bilden eine wichtige Grundlage für strategische Entscheidungen im Bereich der Informationssicherheit und ermöglichen eine kontinuierliche Anpassung und Verbesserung des ISMS.
## Behandlung von Compliance-Verstößen 

Die systematische Behandlung von Compliance-Verstößen trägt dazu bei, die Einhaltung regulatorischer, vertraglicher und interner Anforderungen sicherzustellen. Ein strukturierter Umgang mit Verstößen hilft ähnliche Vorfälle in Zukunft zu vermeiden.

Ein Verfahren zur Behandlung von Verstößen sollte verankert werden, das folgende Elemente umfasst:

* Klare Definition, was als Verstoß gilt und wie verschiedene Arten von Verstößen kategorisiert werden  
* Festlegung von Melde- und Eskalationswegen für erkannte oder vermutete Verstöße  
* Systematischer Prozess zur Untersuchung und Dokumentation von Verstößen  
* Entscheidungsfindung über angemessene Reaktionen und Konsequenzen  
* Nachverfolgung der Umsetzung beschlossener Maßnahmen

Die Reaktionen auf Verstöße sollten verhältnismäßig und angemessen sein. Dabei sind stets die Rechte und Freiheiten der Betroffenen zu berücksichtigen, insbesondere die Verhältnismäßigkeit.

Neben der unmittelbaren Reaktion auf Verstöße sollten Prozesse zur Vermeidung künftiger Verstöße etabliert werden. Dazu gehören:

* Analyse der Ursachen des Verstoßes (organisatorisch, technisch, menschlich)  
* Identifikation von Verbesserungspotenzialen in Prozessen, Schulungen oder Kontrollen  
* Umsetzung präventiver Maßnahmen wie verbesserte Schulungskonzepte, technische Sicherheitsmechanismen oder Prozessänderungen  
* Sensibilisierung relevanter Mitarbeitergruppen für typische Compliance-Risiken

Bei schwerwiegenden Verstößen oder komplexen rechtlichen Fragestellungen sollte rechtliche Expertise hinzugezogen werden. Dies kann durch interne Rechtsabteilungen oder externe Rechtsberater erfolgen und dient dazu, rechtlich korrekte und angemessene Entscheidungen zu treffen sowie mögliche rechtliche Konsequenzen für die Institution zu minimieren.

Eine strukturierte und angemessene Behandlung von Compliance-Verstößen fördert die Entwicklung einer positiven Sicherheits- und Compliance-Kultur in der Institution. Sie zeigt, dass Regelverstöße ernst genommen werden, stellt aber gleichzeitig sicher, dass der Fokus auf Lernen und Verbesserung liegt und nicht ausschließlich auf Sanktionen. 
# Glossar 

*Perspektivisch Kapitel 2 „Grundlegende Begriffe“ hier \+ Erweiterungen ähnlich IT-GS Glossar*

[^1]:  Die Modalverben werden ähnlich dem RFC 2119 aber im deutschen Kontext angewandt. 

[^2]:  Der Begriff Auditprogramm seht synonym z.B. Revisionsprogramme.
