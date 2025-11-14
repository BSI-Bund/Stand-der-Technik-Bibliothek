| ID | name | description | UUID (only for G++ controls!) |
|---|---|---|---|
| UMS.1.3 | Anweisung zur Einhaltung | Umsetzung für Nutzende MUSS diese zur Einhaltung der dokumentierten Verpflichtungen anweisen. | 4d5eddd3-8727-42ab-9ac1-e406ae305180 |
| ARCH.2.1 | Netzsegmente | Architektur für Netze SOLLTE eine Unterteilung des internen Netzes in Netzsegmente unter Berücksichtigung der Anforderungen der Institution und des Sc | ec31da4c-f5bd-43f5-b94f-f0fb7a5e1a18 |
| ARCH.2.2 | Einschränkung von Verbindungen zwischen Segmenten | Architektur für Netze SOLLTE Verbindungen zwischen Netzsegmenten anhand von {{ insert: param, arch.2.2-prm1 }} einschränken. | 6ff2de76-4a01-42cc-a794-1a6ec9313f46 |
| ARCH.2.2.1 | Externe Netzanschlüsse | Architektur für Netze SOLLTE Verbindungen über externe Netzanschlüsse einschränken. | 56a54bba-30a4-478f-8464-bc5194cae49f |
| ARCH.2.2.2 | Gastnetz | Architektur für Netze SOLLTE Verbindungen zwischen Gastnetz und internem Netz einschränken. | 73c9c122-d3f6-42f9-a6f1-6b454a8b1853 |
| ARCH.2.2.3 | Segmentierung von Servern und Clients | Architektur für Hostsysteme SOLLTE Verbindungen von und zu Clients einschränken. | 8af42e9e-5340-4690-9567-88a5309aee3a |
| ARCH.2.2.4 | VoIP-Netz | Architektur für Netze KANN eine oder mehreren separate Netzdomänen zur Trennung von Daten- und VoIP-Kommunikation installieren. | 02cac8a8-60e3-481d-96bf-3fa484afea78 |
| ARCH.2.2.5 | OT-Systeme | Architektur für OT-Systeme SOLLTE für diese ein oder mehrere separate Netzsegmente installieren. | 43badc07-0172-4666-9a72-0c0289b7f540 |
| ARCH.2.2.6 | Demilitarisierte Zone | Architektur für Netze SOLLTE eine demilitarisierte Zone installieren. | f9e8c80d-0043-42ac-a71b-73ff1e6cad50 |
| ARCH.2.2.7 | Management-Netz | Architektur für Netze SOLLTE ein oder mehrere Management-Netze installieren. | d02f23d0-9c15-4811-838f-6440ee744334 |
| ARCH.2.2.8 | Segmentierung von Test und Betrieb | Architektur für Netze SOLLTE Verbindungen zwischen Testumgebungen und Betrieb einschränken. | 53ea67c4-1ee1-47f3-abc2-0f2462c57cd1 |
| ARCH.2.2.9 | Segmentierung von IPV4 und IPv6 | Architektur für IT-Systeme SOLLTE Verbindungen zwischen IPv4 und IPv6 einschränken. | dabbb234-5678-456b-8db4-4c7ac9ed1e12 |
| ARCH.2.2.10 | Drucker-Netz | Architektur für Drucker SOLLTE Verbindungen von und zu anderen Systemen einschränken. | 48013e9f-7f90-495c-8cbd-aaf33f5060fb |
| ARCH.2.2.11 | Mikrosegmentierung | Architektur für IT-Systeme KANN Verbindungen zu allen anderen IT-Systemen einschränken. | 193a28ca-0382-4998-874d-4c08b6326f26 |
| ARCH.2.2.12 | Physische Segmentierung | Architektur für Netze KANN den physischen Zugang auf diese einschränken. | 8629ffa8-91c9-4ed3-b7b7-922aba672ab4 |
| ARCH.2.3 | Netzplan | Architektur für Netze SOLLTE einen Netzplan einschließlich interner Segmente, externer Netzanschlüsse und deren Verwendungszweck dokumentieren. | 7630e7d2-883b-4697-9b7a-b212dfa5666d |
| ARCH.2.4 | Topologieüberwachung | Architektur für Netze SOLLTE die Einhaltung der Netzarchitektur {{ insert: param, arch.2.4-prm1 }} überprüfen. | f97736f7-f2c7-4366-a996-7e28512972de |
| ARCH.3.1 | Netzabdeckung | Architektur für WLANs SOLLTE die Netzabdeckung testen. | 57639fa6-7898-4ad8-91c5-cc77106e0d02 |
| ARCH.3.2 | Einschränkung in Sicherheitsbereichen | Architektur für WLANs KANN in Sicherheitsbereichen die Ausstrahlung einschränken. | 0ecd6068-4509-4cb5-bf12-b35076cc88e3 |
| ARCH.3.3 | SSIDs | Architektur für WLANs SOLLTE institutionsspezifische SSIDs aktivieren. | 06d3eb79-4326-4bd8-87c0-9808909d29c7 |
| ARCH.3.4 | Verschlüsselung | Architektur für WLANs SOLLTE die Netzanbindung {{ insert: param, arch.3.4-prm1 }} verschlüsseln. | 45bb11ba-1018-430e-be4f-7cae54407f3c |
| ARCH.4.1 | Netzzugangskontrolle | Architektur für Interne Netzsegmente SOLLTE den Zugriff von IT-Systemen auf das Netzsegment im Einklang mit den zugehörigen Anforderungen des Identitä | 9ec9762e-c115-4e56-8b45-b88a872f47ce |
| ARCH.4.1.1 | Dynamische Netzzugangskontrolle | Architektur für Interne Netzsegmente SOLLTE den Zugriff von IT-Systemen auf das Netzsegment anhand {{ insert: param, arch.4.1.1-prm1 }} im Einklang mi | fec4fcdf-13e7-4a32-a3e1-52dce90ea1d7 |
| ARCH.4.1.2 | Quarantäne | Architektur für Interne Netzsegmente KANN ein Quarantänenetz für nicht authentifizierte IT-Systeme installieren. | 5f97efff-4db1-4b26-8ab9-4521108e5c0c |
| ARCH.4.2 | Autorisiertes Routing | Architektur für Netze SOLLTE Routing-Verbindungen durch {{ insert: param, arch.4.2-prm1 }} autorisieren. | 77aebab8-462b-4849-aaa2-9c939af5e1dc |
| ARCH.4.3 | Authentifizierung von Routingprotokollen | Architektur für Netze SOLLTE Änderungen an Routing-Tabellen im Einklang mit den zugehörigen Anforderungen des Identitäts- und Berechtigungsmanagements | 739ad3ad-cbbc-4809-9f20-1c59e85c864b |
| ARCH.5.1 | Einschränkung und Inspektion von Verbindungen | Architektur für Netze SOLLTE Verbindungen zwischen IT-Systemen einschränken. | 025c298a-7c8d-441d-b9d5-a1422556c6e1 |
| ARCH.5.1.1 | Blockieren anfälliger Netzprotokolle | Architektur für Netze SOLLTE anfällige Netzwerkprotokolle blockieren. | b4977fc1-727c-41c8-a397-f84ba68fc11a |
| ARCH.5.1.2 | Netzbasierte Angriffe | Architektur für Netze SOLLTE bekannte netzbasierte Angriffsmethoden blockieren. | 09d37d0c-fda7-4f38-9aa6-f8cbae7d878d |
| ARCH.5.1.3 | TCP-basierte Angriffe | Architektur für Netze SOLLTE bekannte TCP-basierte Angriffsmethoden blockieren. | cc1cf52d-6be3-4e7d-a5c0-6ecce6c282b1 |
| ARCH.5.1.4 | UDP-basierte Angriffe | Architektur für Netze SOLLTE bekannte UDP-basierte Angriffsmethoden blockieren. | d2b4e523-ee05-47ae-8d5e-95f30015dce2 |
| ARCH.5.1.5 | Deaktivierung von Split Tunneling | Architektur für Externe Netzanschlüsse SOLLTE Split Tunneling blockieren. | 7ff5e3bc-64e8-4487-a77a-c4897f97431d |
| ARCH.5.1.6 | Blockieren direkter Management-Verbindungen | Architektur für Externe Netzanschlüsse SOLLTE Verbindungen zu Management-Schnittstellen blockieren. | 9e1420ba-9cc0-4d0d-a127-36881c1b90e5 |
| ARCH.5.1.7 | Edge-Routing | Architektur für Externe Netzanschlüsse SOLLTE dynamische Routingprotokolle blockieren. | b9019268-f8d4-4820-b744-2c79c31ce75a |
| ARCH.5.1.8 | Inspektion verschlüsselter Verbindungen | Architektur für Externe Netzanschlüsse SOLLTE den Inhalt unverschlüsselter und verschlüsselter Verbindungen basierend auf der Art des Inhalts einschrä | 657f0690-9aaf-42fb-8474-3986a22277c8 |
| ARCH.5.1.9 | Filterung von DNS | Architektur für Externe Netzanschlüsse SOLLTE unerwünschte Inhalte in DNS-Verbindungen einschränken. | 4938a7c4-fdbb-4ca8-a33c-87d177d25f8b |
| ARCH.5.1.10 | Webfilterung | Architektur für Externe Netzanschlüsse SOLLTE den Zugriff auf Webinhalte anhand von {{ insert: param, arch.5.1.10-prm1 }} einschränken. | 327ca27d-e60f-47d1-8840-5bcb09340030 |
| ARCH.5.1.10.1 | Bekannte schädliche Inhalte | Architektur für Externe Netzanschlüsse SOLLTE bekannte schädliche Inhalte einschränken. | 3eb3dc59-6fdb-41d2-80da-65490c0156d7 |
| ARCH.5.1.10.2 | Bekannte illegale Inhalte | Architektur für Externe Netzanschlüsse SOLLTE bekannte illegale Inhalte einschränken. | c776fdb1-92b7-4f11-be53-41104fdd71f7 |
| ARCH.5.1.10.3 | Speicherdienste | Architektur für Externe Netzanschlüsse SOLLTE Speicherdienste einschränken. | 205d7828-80e7-4f02-963c-582a8a38eb4d |
| ARCH.5.1.11 | P-A-P-Struktur | Architektur für Externe Netzanschlüsse SOLLTE eine P-A-P-Struktur für eingehende und ausgehende Verbindungen installieren. | bd23cb10-ab1e-42b2-81bc-b7c1705fb16a |
| ARCH.5.2 | Produktdiversität | Architektur für Externe Netzanschlüsse KANN für die Filterung diverse Produkte unterschiedlicher Hersteller für eingehende und ausgehende Verbindungen | 32682181-5136-4d4b-8466-3fd3a1d3b03c |
| ARCH.5.3 | Blockieren direkter öffentlicher Verbindungen | Architektur für IT-Systeme SOLLTE direkte Verbindungen von diesen ins öffentliche Netz blockieren. | b94287af-31a1-4500-a8da-89583fdaef92 |
| ARCH.6.1 | Kontrollierte Verbindungsführung | Architektur für Externe Netzanschlüsse KANN eine  {{ insert: param, arch.6.1-prm1 }} kontrollierte Verbindungsführung für Weitverkehrsverbindungen akt | acd884af-7aad-470c-bfcf-216cff90e9be |
| ARCH.6.2 | Verschlüsselung von Weiterverkehrsverbindungen | Architektur für Externe Netzanschlüsse SOLLTE Verbindungen ins Weitverkehrsnetz nach {{ insert: param, arch.6.2-prm1 }} verschlüsseln. | 1999335e-7d66-4dc5-8960-8115234e8e23 |
| ARCH.7.1 | Dedizierte Server | Architektur für Anwendungen SOLLTE Serverdienste ausschließlich auf für die Anwendung dedizierten Hostsystemen platzieren. | dbc89a40-82e3-48c7-9422-ce8f874ca1cf |
| ARCH.7.2 | Dedizierte Hardware | Architektur für Hostsysteme KANN diese auf dedizierter Hardware platzieren. | 85fe83c0-ac96-43c8-b2a9-98059b801b73 |
| ARCH.7.3 | Entwicklungs- und Testumgebungen | Architektur für Virtualisierungslösungen SOLLTE Entwicklungs- und Testumgebungen nicht auf produktiven Hostsystemen platzieren. | 15bdb341-c907-4daa-9e39-1dc3777ef9bc |
| ARCH.8.1 | Redundanz im Kernnetz | Architektur für Netze SOLLTE für das Kernnetz redundante Netzkomponenten installieren. | 37f932b2-e132-4bf0-b8c3-eed73eadc680 |
| ARCH.8.2 | Redundante TK-Anbindung | Architektur für Externe Netzanschlüsse KANN redundante TK-Anbindungen für eingehende und ausgehende Verbindungen installieren. | 11904e1d-22f5-4855-b2b4-5b82a423c2d7 |
| ARCH.8.3 | Redundante Server | Architektur für Anwendungen KANN für die Funktionsfähigkeit der Anwendung erforderliche Server-Systeme redundant installieren. | d1a0c0ac-dc2e-4d90-b67d-b76eec256915 |
| ARCH.9.1 | Dimensionierung der Netzanbindung | Architektur für Netze SOLLTE eine bedarfsgerechte Netzanbindung installieren. | 82cfd8da-b3d8-4b87-8770-f39aaf7de728 |
| ARCH.9.2 | Lastverteilung | Architektur für Anwendungen KANN eine {{ insert: param, arch.9.2-prm1 }} automatische Lastverteilung aktivieren. | 50e54872-271e-41b4-b54a-50e9ebab82bd |
| ARCH.9.3 | Automatische Skalierung | Architektur für Anwendungen KANN eine automatische Skalierung der von der Anwendung verwendeten Computerinstanzen anhand von {{ insert: param, arch.9. | bbfa749a-99a4-4ff3-9cce-5ceeb3162596 |
| ARCH.9.4 | Content Delivery Network | Architektur für Anwendungen KANN ein Content Delivery Network installieren. | 4b5b81aa-fe5f-47f5-a081-136145f7ccc9 |
| ARCH.9.5 | Schutz gegen volumetrische DoS-Angriffe | Architektur für Netze KANN Schutzmaßnahmen gegen volumetrische DoS-Angriffe aktivieren. | ac441ef0-08de-40c4-b600-8be20d8a55b1 |
| SENS.2.1 | Schutzziele | Sensibilisierung für Nutzende SOLLTE zu den Schutzzielen Verfügbarkeit, Vertraulichkeit und Integrität sensibilisieren. | 3d48b1b4-4896-456f-8c7b-46e0b63a1e68 |
| SENS.2.2 | Meldewege | Sensibilisierung für Nutzende SOLLTE zu den Meldewegen und Informationsquellen bei Fragen informieren. | 08dde2c0-4676-493f-bf6f-71453113b852 |
| SENS.2.3 | Verschlüsselung und Signatur | Sensibilisierung für Nutzende von Anwendungen SOLLTE zur Bedienung von Verschlüsselungs- und Signaturfunktionen sensibilisieren. | a3f929a6-2655-4532-84c5-5c985de579bf |
| SENS.2.4 | Nutzung unautorisierter Assets | Sensibilisierung für Nutzende SOLLTE die Nutzung unautorisierter Assets untersagen. | 1ca19eb8-f4a2-42b5-85f1-ce96fce606bf |
| SENS.2.4.1 | Verbindung unautorisierter IT-Systeme | Sensibilisierung für Nutzende SOLLTE die Verbindung unautorisierter IT-Systeme mit internen Netzen oder Schnittstellen untersagen. | 06cf0eba-817a-4dfb-8e8b-b51044cb5a90 |
| SENS.2.5 | Zuständigkeitsbereiche | Sensibilisierung für Nutzende SOLLTE zu Schutzbedarf und Schnittstellen in ihrem Zuständigkeitssbereich sensibilisieren. | 2392c7c3-0d1f-4e7e-9a21-ffca2bf54798 |
| SENS.2.6 | Umgehung von Sicherheitsfunktionen | Sensibilisierung für Nutzende SOLLTE gegen die Umgehung von Sicherheitsfunktionen sensibilisieren. | 875e5c3d-64e7-403c-bfc7-456200e5e661 |
| SENS.2.7 | Änderung von Konfigurationen | Sensibilisierung für Nutzende SOLLTE gegen die unautorisierte Änderung sicherheitsrelevanter Konfigurationen sensibilisieren. | e849100d-2282-4c6a-b1c6-c6ec3999f9dc |
| SENS.2.8 | Melden von Ereignissen | Sensibilisierung für Nutzende SOLLTE zum Melden von sicherheitsrelevanten Ereignissen anweisen. | fd77e4dd-401d-4b06-a297-bfeded7d53ef |
| SENS.2.8.1 | Melden von Fehler- und Warnmeldungen | Sensibilisierung für Nutzende SOLLTE zum Melden von Fehler- und Warnmeldungen sensibilisieren. | 143c39e7-3bee-42e6-9876-dc55973f2ed4 |
| SENS.3.1 | Schadprogramme | Sensibilisierung für Nutzende SOLLTE gegen die Risiken von Schadprogrammen sensibilisieren. | f5f8738d-0c08-4b55-a01a-e8883d6401c8 |
| SENS.3.2 | Öffnen verdächtiger Dateien | Sensibilisierung für Nutzende KANN zum Öffnen verdächtiger Dateien ausschließlich auf einem isolierten IT-System (Sandbox) sensibilisieren. | fbe194d0-d93c-4fdd-ab18-33df5558e8db |
| SENS.3.3 | Umwandeln verdächtiger Dateien | Sensibilisierung für Nutzende KANN zum Umwandeln verdächtiger Dateien in ein nicht-ausführbares Format vor der weiteren Verwendung sensibilisieren. | 8b0d3acb-43d2-460d-bd40-adeb68400c2f |
| SENS.4.1 | Personengebundene Authentisierungsmittel | Sensibilisierung für Nutzende SOLLTE zum Umgang mit Authentisierungsmitteln im Einklang mit den zugehörigen Anforderungen des Identitäts- und Berechti | fbdb73ce-38c5-466f-84a3-218a7d73eda9 |
| SENS.4.1.1 | Verdeckte Eingabe | Sensibilisierung für Nutzende SOLLTE zur verdeckten Eingabe von Zugangsdaten sensibilisieren. | 78719bfb-2d5c-492f-ba02-fc10a0bdf361 |
| SENS.4.1.2 | Untersagung von Passwort Recycling | Sensibilisierung für Nutzende SOLLTE die Wiederverwendung von Passwörtern untersagen. | 0573247f-65f3-4768-9d27-6c9c0f42c6cd |
| SENS.4.1.3 | Wahl von Passwörtern | Sensibilisierung für Nutzende SOLLTE zur Wahl ausreichend komplexer Passwörter sensibilisieren. | 48c3a712-943d-403e-8e04-cfc11d92a387 |
| SENS.4.1.4 | Passwörter nur im Passwortmanager | Sensibilisierung für Nutzende SOLLTE das Speichern oder Aufschreiben von Passwörtern außerhalb von Passwort-Managern untersagen. | 7734048a-d797-49f0-87e6-f9c08ce5f5e7 |
| SENS.4.1.5 | Biometrische Authentifikation | Sensibilisierung für Nutzende SOLLTE gegen die Fälschbarkeit von biometrischen Authentifizierungsmerkmalen sensibilisieren. | 9065b5b9-cf47-40c1-9238-0f3e2f912fb9 |
| SENS.4.1.6 | Keine Weitergabe personengebundener Authentisierungsmittel | Sensibilisierung für Nutzende SOLLTE die Weitergabe von personengebundenen Authentisierungsmitteln untersagen. | b25f3f5e-0738-4794-b130-cc9a1e29084f |
| SENS.4.2 | Mehrfachnutzung von Zugängen | Sensibilisierung für Nutzende SOLLTE gegen die Nutzung eines Zugangskontos durch mehrerere Personen sensibilisieren. | 4ee04b8f-c620-4fe0-aa8d-928407cbbd2d |
| SENS.4.3 | Abmelden nach Nutzung | Sensibilisierung für Nutzende SOLLTE zum Abmelden nach Nutzung sensibilisieren. | 53963d32-edfa-47d4-99ef-1fcb41f00aa8 |
| SENS.5.1 | Datenablage | Sensibilisierung für Nutzende SOLLTE zum Einhalten einer strukturierten Datenablage sensibilisieren. | 283ea65f-9ace-452c-a2be-38a5c58d3fb3 |
| SENS.5.2 | Weitergabe von Informationen | Sensibilisierung für Nutzende von Informationen SOLLTE zu den Voraussetzungen der Weitergabe von Informationen sensibilisieren. | a59c2b01-6240-49ef-b608-a9e3d07476c6 |
| SENS.5.3 | Weitergabe von Erreichbarkeiten | Sensibilisierung für Nutzende KANN die Veröffentlichung oder Weitergabe von Erreichbarkeiten an unbefugte Dritte untersagen. | 8469fae0-3bd3-41d2-a323-af26619e62d2 |
| SENS.5.4 | Rest- und Zusatzdaten | Sensibilisierung für Nutzende SOLLTE zur Vermeidung oder Entfernung von Rest- und Zusatzdaten vor dem Versand sensibilisieren. | ff7cc34b-1d15-42f0-8d2d-2c9dd77d6474 |
| SENS.5.5 | Löschfristen | Sensibilisierung für Nutzende SOLLTE zum Löschen oder Vernichten nach Ablauf der festgelegten Löschfristen anweisen. | 7aed1f72-5233-44dd-8531-b23337c89691 |
| SENS.5.6 | Papiervernichtung | Sensibilisierung für Nutzende SOLLTE zum Vernichten vertraulicher Dokumente nach Ablauf der Löschfrist sensibilisieren. | 72ed03a1-0f7d-49af-ab2b-39a1b73e9b49 |
| SENS.6.1 | Scan angenommener Wechseldatenträger | Sensibilisierung für Nutzende SOLLTE zum Virenscan angenommener Wechseldatenträger anweisen. | a2cc232d-ff51-45f0-bfe3-be82d53ca390 |
| SENS.6.2 | Verschlüsselung | Sensibilisierung für Nutzende SOLLTE zum Verschlüsseln von Wechseldatenträgern anweisen. | ff90bcf5-8c4a-4329-b453-6e77b235687d |
| SENS.7.1 | Spezifische Sensibilisierung | Sensibilisierung für Nutzende SOLLTE zu zielobjektspezifischen Schutzmaßnahmen zielgruppengerecht sensibilisieren. | d988364a-6e20-4f5f-ae5c-dacae6b26cd6 |
| SENS.7.2 | Virenscan | Sensibilisierung für Nutzende von Interpersoneller Kommunikation SOLLTE zum Virenscan von Dateien aus externen Quellen sensibilisieren. | b791d70f-b022-4a9e-bcf1-e4406c441981 |
| SENS.7.3 | Automatische Antworten | Sensibilisierung für Nutzende von Interpersoneller Kommunikation SOLLTE gegen die Ausgabe vertraulicher Daten durch AutoReply-Funktionen sensibilisier | 534179b0-fccb-42b5-95b3-e0d5a1778dec |
| SENS.7.4 | SPAM - Löschen oder Melden | Sensibilisierung für Nutzende von Interpersoneller Kommunikation SOLLTE zum Löschen oder Melden von SPAM sensibilisieren. | 93be24dd-88cd-4b1a-b86a-45febc987a4c |
| SENS.7.5 | SPAM - Nichtbeantwortung | Sensibilisierung für Nutzende von Interpersoneller Kommunikation SOLLTE zum Nichtbeantworten von SPAM sensibilisieren. | 0711ec2e-61da-4448-bcc8-464b41154ff1 |
| SENS.7.6 | SPAM - Links | Sensibilisierung für Nutzende von Interpersoneller Kommunikation SOLLTE gegen das Öffnen von Links in SPAM sensibilisieren. | bee9f242-644f-40f5-be85-a699c8c383eb |
| SENS.7.7 | SPAM - Anhänge | Sensibilisierung für Nutzende von Interpersoneller Kommunikation SOLLTE gegen das Öffnen von Anhängen in SPAM sensibilisieren. | 5003cefa-020f-445f-8e23-4add09f63a47 |
| SENS.7.8 | Gefälschte E-Mails | Sensibilisierung für Nutzende von E-Mailn SOLLTE zum Erkennen von gefälschten E-Mails sensibilisieren. | 94709673-e417-4e77-be9e-b17f47cce437 |
| SENS.7.9 | Aktive Inhalte | Sensibilisierung für Nutzende von Office-Anwendungen SOLLTE zur Überprüfung aktiver Inhalte vor der Aktivierung sensibilisieren. | d4253a3f-ba3b-4446-b6cc-bfbd9285eb27 |
| SENS.7.10 | Trennen nicht benötigter Anschlüsse | Sensibilisierung für Nutzende von Virtualisierungslösungen SOLLTE zum Trennen nicht benötigter Verbindungen zwischen Host und virtuellem Gast sensibil | 2e5be22a-6fc5-49b3-ae53-66dc4105e058 |
| SENS.7.11 | Heimliche Aufzeichnung | Sensibilisierung für Nutzende von VK-Anwendungen SOLLTE gegen die heimliche Bild- oder Tonaufzeichnung bei einer Videokonferenz sensibilisieren. | e5552e03-45ba-4bd4-8022-c4d46eb1c856 |
| SENS.7.12 | Öffentliche WLANs | Sensibilisierung für Nutzende von Endgeräten SOLLTE gegen die Risiken der Nutzung öffentlicher WLANs sensibilisieren. | 172adca9-01ae-4e68-815d-eff8157dab27 |
| SENS.7.13 | Unverschlüsselte WLANs | Sensibilisierung für Nutzende von Endgeräten SOLLTE gegen die Risiken der Nutzung unverschlüsselter WLANs sensibilisieren. | b0c8ba84-b24f-4209-a739-ea13c2aea349 |
| SENS.7.14 | Unautorisierte WLANs | Sensibilisierung für Nutzende von Endgeräten KANN die Nutzung unautorisierter WLANs untersagen. | 007d7888-bcc0-4595-b448-f178962c609f |
| SENS.7.15 | Social Engineering Anrufe | Sensibilisierung für Nutzende von TK-Anwendungen SOLLTE gegen Social Engineering Anrufe sensibilisieren. | 6f6dcfa4-7c22-4e39-a1a2-c88ed0e9ee74 |
| SENS.7.16 | Mailbox-PIN und Co. | Sensibilisierung für Nutzende von TK-Anwendungen SOLLTE zur Vergabe eigener Zugangsdaten zum Zugriff auf Aufzeichnungen sensibilisieren. | 9721c369-8d8a-4c8f-9a32-3e25b2003359 |
| SENS.7.17 | Unverschlüsseltes Telefonieren | Sensibilisierung für Nutzende von TK-Anwendungen SOLLTE gegen die Kommunikation über unverschlüsselte Telekommunikationsverbindungen sensibilisieren. | 789dbb4e-30fe-46ce-822c-06965e00f9c8 |
| SENS.7.18 | Mobiltelefone in Sicherheitsbereichen | Sensibilisierung für Nutzende von Mobiltelefonen KANN das Mitführen von Mobiltelefonen in Sicherheitsbereichen untersagen. | d657ce0c-6970-4955-9452-d538a3fded99 |
| SENS.7.19 | Unverschlüsselte SMS oder MMS | Sensibilisierung für Nutzende von Mobiltelefonen KANN den Versand von SMS oder MMS untersagen. | 99a4ed67-648c-4dfb-8fcf-2ce1b8a907db |
| SENS.7.20 | Authentifzierung von Gesprächspartnern | Sensibilisierung für Nutzende von Informationen SOLLTE zur Authentifizierung von Gesprächspartnern vor der Weitergabe von Informationen sensibilisiere | 820687b2-4447-455d-9c9f-236c7333db82 |
| SENS.7.21 | Rechtsunsicherheit von Faxen | Sensibilisierung für Nutzende von Faxen SOLLTE gegen die Rechtsunsicherheit bei Empfang oder Versand von Faxen sensibilisieren. | 19a80332-263d-421d-927c-2d99ad0ce9c0 |
| SENS.7.22 | Unverschlüsselte Faxleitungen | Sensibilisierung für Nutzende von Faxen SOLLTE gegen die Risiken der unauthentisierten und unverschlüsselten Faxnutzung sensibilisieren. | 6de76a23-9301-4203-9561-c56f459b8a1f |
| SENS.7.23 | Geolokation | Sensibilisierung für Nutzende von Endgeräten SOLLTE über Standortbestimmungsfunktionen von mobilen Endgeräten sensibilisieren. | 48be8fcc-4642-42b6-8a53-b8baf85f6b2a |
| SENS.7.24 | Zertifikatswarnungen | Sensibilisierung für Nutzende von Webbrowsern SOLLTE gegen das unautorisierte Übergehen einer Zertifikatswarnung bei der Webnutzung sensibilisieren. | 777774af-92c0-41ee-8f3e-953b88ffd800 |
| SENS.7.25 | Zugang zum Fahrzeug | Sensibilisierung für Nutzende von Fahrzeugen SOLLTE zu Schutzmaßnahmen vor dem Zugang Unbefugter zu Fahrzeugen sensibilisieren. | 9cb473cd-cf71-4fe4-9ccd-b527f1a353ab |
| SENS.8.1 | Risiken der Nutzung von mobilen Endgeräten | Sensibilisierung für Nutzende von Endgeräten SOLLTE gegen Risiken der Nutzung von mobilen Endgeräten sensibilisieren. | d3d8d31b-bbc8-4e63-9f09-4dc19897323c |
| SENS.8.2 | Schließen von Türen und Fenstern | Sensibilisierung für Nutzende von Gebäuden SOLLTE zum Verschließen von Fenstern und Türen beim Verlassen von Räumlichkeiten anweisen. | 2a761948-b26a-4e19-8a9d-75f78ac19811 |
| SENS.8.3 | Mitbringen von IT-Systemen | Sensibilisierung für Nutzende KANN das Mitbringen unautorisierter IT-Systeme untersagen. | 6988844b-ed26-4ad3-83f6-ba5cf223070b |
| SENS.8.4 | Begleitung Externer | Sensibilisierung für Mitarbeitende von Standorten KANN zur Begleitung von Externen anweisen. | 1f0a8e0c-33cd-407a-9579-e2dcc6d46515 |
| SENS.8.4.1 | Beaufsichtigung Externer | Sensibilisierung für Mitarbeitende von Standorten SOLLTE zur Beaufsichtigung von Externen in sensiblen Bereichen anweisen. | 2b9cec51-f841-4ba6-b50d-29c1c2f2c21d |
| SENS.8.5 | Verwahrung Intern | Sensibilisierung für Nutzende von Räumen SOLLTE zur sicheren Verwahrung von IT-Systemen und Datenträgern sensibilisieren. | a5504b88-679b-418b-ab9e-5741317f29ff |
| SENS.8.6 | Rückgabe nicht mehr benötigter Assets | Sensibilisierung für Nutzende SOLLTE zur Rückgabe nicht mehr benötigter Assets anweisen. | 857f189a-5ede-47d6-89d5-faff63d736d2 |
| SENS.8.7 | Brandschutz | Sensibilisierung für Mitarbeitende SOLLTE zur korrekten Verwendung bereitgestellter Brandschutz-Hilfsmittel sensibilisieren. | 37823d46-59ad-487b-bba1-5917c017c625 |
| SENS.8.8 | Wasserschutz | Sensibilisierung für Mitarbeitende KANN zur korrekten Verwendung bereitgestellter Wasserschutz-Hilfsmittel sensibilisieren. | 75859261-aa48-4faf-9489-3d875e585f9d |
| SENS.9.1 | Verarbeitung in der Öffentlichkeit | Sensibilisierung für Nutzende SOLLTE gegen die Verarbeitung von vertraulichen Informationen in der Öffentlichkeit sensibilisieren. | 4d8775fd-52b0-491f-b0ce-7a8ceaba4819 |
| SENS.9.2 | Vorsicht vor Mithören | Sensibilisierung für Nutzende SOLLTE gegen das Abhören von Gesprächen beim mobilen Arbeiten sensibilisieren. | bd43cb07-83d9-4105-9039-3dba57a180e9 |
| SENS.9.3 | Verwahrung außer Haus | Sensibilisierung für Nutzende SOLLTE zur Verwahrung von IT-Systemen und Datenträgern beim mobilen Arbeiten anweisen. | 65a6dd9c-baab-49b8-8d28-ee4cab5b52a9 |
| SENS.9.4 | Mobile Arbeit mit Dokumenten | Sensibilisierung für Nutzende SOLLTE über den sicheren Umgang mit analogen Dokumenten beim mobilen Arbeiten sensibilisieren. | 4e9f2d62-dfe7-43a6-abb7-3c2e12df08b6 |
| SENS.9.5 | Mitnahme zur mobilen Arbeit | Sensibilisierung für Nutzende SOLLTE gegen die Mitnahme nicht erforderlicher IT-Systeme und Datenträger sensibilisieren. | 3c678c4b-a10d-4f6d-ab63-d34cd84ecefe |
| SENS.9.6 | Mitnahme ins Ausland | Sensibilisierung für Nutzende KANN die Mitnahme nicht erforderlicher IT-Systeme und Datenträger bei Auslandsreisen untersagen. | 2181d821-efad-48d7-9c12-7c1aad40bfb1 |
| SENS.9.7 | Reise- und Sicherheitshinweise | Sensibilisierung für Nutzende SOLLTE zu Reise- und Sicherheitshinweisen des Auswärtigen Amtes bei Auslandsreisen ins außereuropäische Ausland sensibil | 3b4e6be6-5648-468f-bc05-89191c9cdd90 |
| SENS.10.1 | Grundprinzipien der Systemadministration | Sensibilisierung für Administrierende SOLLTE zu den Grundprinzipien der sicheren Administration sensibilisieren. | 27a41327-328d-4213-a39b-fe549f241921 |
| SENS.10.2 | Umgang mit privilegierten Berechtigungen | Sensibilisierung für Administrierende SOLLTE zum Umgang mit privilegierten Berechtigungen sensibilisieren. | df690f55-b161-42fd-8cdb-383a553dddfe |
| SENS.10.3 | Systemadministration - Sicherheitsvorfälle | Sensibilisierung für Administrierende SOLLTE zu Verfahren und Regelungen bei Sicherheitsvorfällen sensibilisieren. | 019ea9a4-70dd-4e10-adfa-37467144aca3 |
| SENS.10.4 | Systemadministration - Strukturierte Verkabelung | Sensibilisierung für Administrierende von Netzen SOLLTE zur strukturierten Verkabelung sensibilisieren. | fd852545-bf6f-4e5b-adc0-e169cc0548fa |
| SENS.10.5 | Systemadministration - Internetnutzung | Sensibilisierung für Administrierende SOLLTE gegen den Internetzugriff über ein Administrationskonto sensibilisieren. | 888c76ab-d8f0-42ff-a791-8a31f17f6ad0 |
| SENS.11.1 | Sensibilisierung der Institutionsleitung | Sensibilisierung für Institutionsleitung SOLLTE zur Bedeutung der Informationssicherheit für den Schutz der Geschäftsprozesse sensibilisieren. | 72f91d4a-67c7-4e93-a9b8-a4bb1157e4a6 |
| SENS.11.2 | Führen als Vorbild | Sensibilisierung für Führungskräfte SOLLTE zu ihrer Vorbildfunktion bei der Informationssicherheit sensibilisieren. | c5032864-bc5c-4f60-a136-9b10aa2f3f10 |
| SENS.11.3 | Whaling | Sensibilisierung für Führungskräfte SOLLTE gegen gezielte Angriffe auf Führungskräfte sensibilisieren. | e8b12560-18b1-4e31-955a-68804003008b |
| SENS.12.1 | Hohe Risiken | Sensibilisierung für Nutzende KANN gegen die in der Risikoanalyse festgestellten hohen Risiken sensibilisieren. | f1191c38-3df5-4cc4-adfd-46863a2671a8 |
| NOT.3.3 | Sensibilisierung zum Vorgehen im Notfall | Notfallplanung für Nutzende SOLLTE zur Vorgehensweise in Notfällen und Krisen sensibilisieren. | eaee617b-d2db-48b3-8042-67098ad56bc5 |
| NOT.4.2 | Sicherung des Systems | Notfallplanung für IT-Systeme SOLLTE deren Datensicherung {{ insert: param, not.4.2-prm1 }} ausführen. | a77c3a5e-44fc-482c-974a-e4d9dc7cd255 |
| NOT.4.3 | Sicherung der Anwendung | Notfallplanung für Anwendungen SOLLTE deren Datensicherung {{ insert: param, not.4.3-prm1 }} ausführen. | dcfb7d28-71df-45f4-ada5-a284415e8c90 |
| NOT.4.4 | Automatische Datensicherung | Notfallplanung für Daten SOLLTE die Datensicherung durch {{ insert: param, not.4.4-prm1 }} ausführen. | 20fa9557-7db9-4367-9592-35ca5d8e8be7 |
| NOT.4.5 | Archivierung langfristig benötigter Daten | Notfallplanung für Daten SOLLTE die Archivierung langfristig benötigter Daten {{ insert: param, not.4.5-prm1 }} ausführen. | 90012325-5827-4ad9-bee7-6877a37cecfe |
| NOT.4.5.1 | Zum Archiv gehörende Assets | Notfallplanung für Daten SOLLTE die Archivierung von Assets, die zur Verwendung von archivierten Daten erforderlich sind, {{ insert: param, not.4.5.1- | 5fda3188-8ad6-4981-953c-975696be1bfc |
| NOT.4.5.2 | Zum Archiv gehörende Dokumentation | Notfallplanung für Daten SOLLTE die Archivierung von Dokumentationen, die zur Verwendung von archivierten Daten erforderlich sind, {{ insert: param, n | c8feda1f-4d2c-4831-9822-04be256e9e51 |
| NOT.4.13 | Datensouveränität | Notfallplanung für Outsourcing SOLLTE die Datensicherung von Daten, die bei einem Dienstleister verarbeitet werden, nach {{ insert: param, not.4.13-pr | 13789041-edcf-4270-a8d1-49bdd0d54ab4 |
| NOT.4.14 | Offline-Kopie | Notfallplanung für Daten SOLLTE eine Offline-Kopie {{ insert: param, not.4.14-prm1 }} ausführen. | 3772a701-e5d0-4aee-a393-ad539482eb72 |
| NOT.4.16 | Test der Datensicherung | Notfallplanung für Daten SOLLTE den Erfolg der Datensicherung {{ insert: param, not.4.16-prm1 }} überprüfen. | 09fe99af-64b5-478f-80c0-c4ea6f6d4561 |
| NOT.4.16.1 | Test der Wiederherstellung | Notfallplanung für Daten SOLLTE die Wiederherstellung mindestens anhand von repräsentativen Stichproben {{ insert: param, not.4.16.1-prm1 }} überprüfe | 77286239-41b4-49e0-86f7-1b64364d9759 |
| NOT.4.17 | Anwendungstest | Notfallplanung für Anwendungen KANN deren Funktionsfähigkeit nach Wiederherstellung {{ insert: param, not.4.17-prm1 }} überprüfen. | 97025637-17d4-48fc-ace6-67f20e7ccee6 |
| ASST.2.1.1 | Informationsverantwortung | Informationen und Assets für Daten SOLLTE die Zuständigkeit für deren Verarbeitung {{ insert: param, asst.2.1.1-prm1 }} zuweisen. | eae7145a-228e-47ca-9a09-7a4a3b74ac55 |
| ASST.2.2.1 | Aufdecken unautorisierter IT-Systeme | Informationen und Assets für Netze SOLLTE das Aufdecken unautorisierter IT-Systeme verankern. | 02a49908-868b-45de-9ce5-56cb230ab8ee |
| ASST.2.3.1 | Autorisierung von Anwendungen | Informationen und Assets für IT-Systeme SOLLTE die Nutzung von Anwendungen auf diesen durch {{ insert: param, asst.2.3.1-prm1 }} autorisieren. | 3d12c2e5-94bd-48d2-bf9c-a5797e4f0378 |
| ASST.2.3.2 | Software Bill of Materials (SBOM) | Informationen und Assets für Anwendungen SOLLTE die Software Bill of Materials (SBOM) dokumentieren. | ddd9f433-8d27-4ed5-9061-e77fc9564dbc |
| ASST.2.4 | Klassifizierung | Informationen und Assets für Daten SOLLTE diese einer Schutzbedarfsklasse zuweisen. | 41530972-ff04-4df0-a2b5-8bab6859becb |
| ASST.3.1 | Nutzungsvereinbarungen | Informationen und Assets für Nutzende SOLLTE diese zu den Regelungen der Nutzung von Informationen und anderen Assets anweisen. | ec6bc7aa-7f8c-4cb1-a564-73e39401051f |
| ASST.3.1.1 | Weitergabe von Informationen | Informationen und Assets für Nutzende SOLLTE zur Weitergabe von Informationen nur bei Erforderlichkeit anweisen. | 32afe7a4-d3d4-43d2-a37b-8ecd45ea69f5 |
| ASST.3.1.1.1 | Entfernung nicht erforderlicher Rest- oder Zusatzdaten | Informationen und Assets für Daten SOLLTE die Entfernung nicht erforderlicher Rest- oder Zusatzdaten verankern. | 5316fe85-7996-41dc-a475-4d5cfeda250c |
| ASST.3.3 | Kennzeichnung ohne vertrauliche Daten | Informationen und Assets für IT-Systeme SOLLTE Kennzeichnung ohne vertrauliche Daten verankern. | e6bdfec9-97ef-405a-a90f-e5b63f900e21 |
| ASST.3.4 | Tainting | Informationen und Assets für Daten KANN eine Markierung durch eingebettete Daten oder Funktionen zur Wiedererkennung zuweisen. | 11c6919e-1dac-4816-9b42-88218c04c62b |
| ASST.3.5 | Verifikation | Informationen und Assets für Informationen KANN die Korrektheit anhand anderer Informationsquellen testen. | fdf57ca0-77d0-4725-9709-19c0f1082a31 |
| ASST.3.6 | Pseudonymisierung | Informationen und Assets für Informationen KANN die Pseudonymisierung vor der Weitergabe verankern. | 6c943ac9-6cd1-4fd2-98b0-6bef3f492022 |
| ASST.3.7 | Anonymisierung | Informationen und Assets für Informationen KANN die Anonymisierung vor der Weitergabe verankern. | 09e9470c-c4d4-466a-9629-5efa6ddb4cd8 |
| ASST.3.8 | Aktualisierung | Informationen und Assets für Daten KANN deren Aktualisierung verankern. | 9d95707e-8cb2-4442-a202-14d2442920ff |
| ASST.3.9 | Autorisierung von Datenlokationen | Informationen und Assets für Daten SOLLTE Datenlokationen durch {{ insert: param, asst.3.9-prm1 }} autorisieren. | 52eee4a3-f5cf-444d-ad0c-9c83c693481b |
| ASST.3.10 | Autorisierung von Systemen | Informationen und Assets für Daten SOLLTE für die Informationsverarbeitung verwendete Systeme durch {{ insert: param, asst.3.10-prm1 }} autorisieren. | 65e6f130-1000-47a4-a551-386d23f6f188 |
| ASST.3.10.1 | Autorisierung von Peripheriegeräten | Informationen und Assets für Daten SOLLTE auch Peripheriegeräte autorisieren. | 75a9c947-c417-4dc7-a942-c27340f20ade |
| ASST.3.11 | Autorisierung von Personen oder Institutionen | Informationen und Assets für Daten SOLLTE den Zugriff von Personen oder Institutionen im Einklang mit den zugehörigen Anforderungen zum Identitäts- un | 523f8482-4664-41ac-b131-6525c5cfa255 |
| ASST.3.12 | Lagerung physischer Assets | Informationen und Assets für Administrierende SOLLTE zur Lagerung physischer Assets in einem dazu vorgesehenen Lager anweisen. | b820e891-c4b8-4673-abec-d3c6d51522d2 |
| ASST.4.1 | Autorisierung von Schnittstellen | Informationen und Assets für Daten KANN Schnittstellen, über die Informationen ausgetauscht werden, durch {{ insert: param, asst.4.1-prm1 }} autorisie | ddfc1b03-9014-4317-a7bb-09980b234457 |
| ASST.4.2 | Vertraulichkeit und Integrität beim Transport | Informationen und Assets für Daten SOLLTE Vertraulichkeit und Integrität beim Transport verankern. | 5ac7299f-708d-4a07-886f-1dd1228526c7 |
| ASST.4.4 | Nachweis des Zugangs | Informationen und Assets für Daten KANN einen Nachweis des Zugangs protokollieren. | 7d11d172-7a6a-41ce-a4a6-733cbc34b874 |
| ASST.4.5 | Vereinbarungen zum Austausch | Informationen und Assets für Daten SOLLTE Regelungen zum Transfer verankern. | c419af7f-3559-42d5-bb68-be72eac2c509 |
| ASST.5.1 | Wartungsbedarf dokumentieren | Informationen und Assets für IT-Systeme SOLLTE den Wartungsbedarf für Systemkomponenten und die zum Betrieb erforderliche Infrastruktur dokumentieren. | 432cc626-f971-493b-b983-9bad32ed84e0 |
| ASST.5.2 | Geregelte Wartungen | Informationen und Assets für IT-Systeme SOLLTE die Wartung {{ insert: param, asst.5.2-prm1 }} ausführen. | f4508940-fad1-49ff-b7f7-d6612790f145 |
| ASST.5.3 | Autorisierung von Wartungen | Informationen und Assets für IT-Systeme KANN Wartungen durch {{ insert: param, asst.5.3-prm1 }} autorisieren. | 59a96eb8-75ad-420d-aab5-4d448f5c12ae |
| ASST.5.4 | Behandlung als Änderungen und Tests | Informationen und Assets für IT-Systeme SOLLTE zur Wartung erforderliche Änderungen im Einklang mit den Verfahren und Regelungen zum Management von Än | 45437d44-0d0c-402f-934a-5cb48552b203 |
| ASST.5.5 | Wartungsfenster | Informationen und Assets für IT-Systeme SOLLTE bei voraussichtlichen Verfügbarkeiteinschränkungen durch bevorstehende Wartungen die Nutzenden über Dau | afaa993d-da28-4f69-93a0-41cb472e8e42 |
| ASST.5.6 | Wartung durch Externe | Informationen und Assets für Mitarbeitende KANN bei Wartungen, die von Externen ohne Sicherheitsüberprüfung vorgenommen werden, zur Beaufsichtigung du | bcf1c916-4509-4461-b9a7-08803a4e96b1 |
| ASST.5.7 | Dokumentation von Wartungen | Informationen und Assets für IT-Systeme SOLLTE Wartungen mit Asset, Anlass, Zeitpunkt, Beteiligten, durchgefürten Maßnahmen und Ergebnissen dokumentie | a2ecedcb-3515-4d40-b4d3-b745142af15b |
| ASST.6.3 | Konformitätsprüfung | Informationen und Assets für IT-Systeme KANN eine Konformitätsprüfung bei Rücknahme ausführen. | f3ccc5ee-2b5d-47a0-80cb-3ad5b510b50d |
| ASST.6.4 | Zurücksetzen auf Ausgangszustand | Informationen und Assets für IT-Systeme SOLLTE bei Rücknahme das Zurücksetzen auf Ausgangszustand ausführen. | 0ca16c9c-e998-420b-9006-417e155d30d6 |
| ASST.7.1 | Nicht mehr benötigte Anwendungen | Informationen und Assets für Anwendungen SOLLTE eine Deinstallation nicht mehr benötigter Anwendungen ausführen. | dd5c811a-37c3-450f-b391-029bbe503afa |
| ASST.7.2 | Aufbewahrungs- und Löschfristen | Informationen und Assets für Daten SOLLTE die Aufbewahrung für {{ insert: param, asst.7.2-prm1 }} verankern. | 2574ffa3-fa96-4eed-8a9a-e67216d499d9 |
| ASST.7.2.1 | Langfristige Archivierung | Informationen und Assets für Daten KANN die langfristige Archivierung mindestens für {{ insert: param, asst.7.2.1-prm1 }} verankern. | d26539e6-62c3-469a-87f3-87ab15fd9213 |
| ASST.7.3 | Geregeltes Löschen oder Vernichten | Informationen und Assets für Daten SOLLTE diese bei Erreichen der Aufbewahrungs- und Löschfrist löschen. | 7dc77e01-b62b-4e7f-bb4c-d9c67551d8fa |
| ASST.7.3.1 | Standardisierte Vernichtung | Informationen und Assets für Daten SOLLTE ein standardisiertes Verfahren zur Vernichtung bei Veräußerung nach {{ insert: param, asst.7.3.1-prm1 }} ver | 93178616-6931-48e6-aee7-d51742868d4f |
| ASST.7.3.2 | Löschverfahren | Informationen und Assets für Daten SOLLTE Löschverfahren verankern. | aeea856c-cbc3-47a2-bc60-56515be30f12 |
| ASST.7.3.3 | Zugelassene Löschanwendungen | Informationen und Assets für Daten KANN die Daten durch eine zugelassene Löschanwendung löschen. | 2fe24be6-1c6b-4a72-8f40-263e1cffc815 |
| ASST.7.4 | Wiederherstelltest | Informationen und Assets für Daten KANN einen Wiederherstelltest ausführen. | 08759519-9e68-4c39-964e-e2461161b8cc |
| ASST.7.5 | Vernichtungseinrichtungen | Informationen und Assets für Standorte KANN Vernichtungseinrichtungen installieren. | 85366b94-56c1-4c46-a34b-52b96d7ab1d4 |
| TEST.2.2 | Folgenabschätzung | Änderungen und Tests für Administrierende SOLLTE zu einer strukturierten Folgenabschätzung vor wesentlichen Änderungen anweisen. | fcba1d19-78ec-4d60-8760-f34c081c2386 |
| PERS.3.1 | Dienst- oder Arbeitsvertrag | Personal für Mitarbeitende SOLLTE die vertrauliche Behandlung von Betriebs- und Geschäftsgeheimnissen im Dienst- oder Arbeitsvertrag vereinbaren. | 6d824928-418e-4e14-bbfc-e2f60d14d816 |
| PERS.3.2 | Verfahrensanweisungen | Personal für Mitarbeitende SOLLTE explizit zur Einhaltung von Verfahrensanweisungen bei Neuzugang anweisen. | 2bd3c14a-de1c-436e-9400-3ae619ab9b9a |
| PERS.3.3 | Betriebs- und Geschäftsgeheimnisse | Personal für Mitarbeitende SOLLTE zum Umgang mit definierten Betriebs- und Geschäftsgeheimnissen bei Neuzugang anweisen. | 6f72a6a1-b8fc-42e4-b0aa-479b2ad48f40 |
| PERS.3.7 | Einarbeitung | Personal für Mitarbeitende SOLLTE eine Einarbeitung bei Neuzugang ausführen. | 5c23386c-7f57-436a-9906-9b34d4f94462 |
| PERS.4.1 | Qualifikationsbedarf | Personal für Mitarbeitende SOLLTE den Bedarf an Qualifikationsmaßnahmen anhand der Aufgaben {{ insert: param, pers.4.1-prm1 }} überprüfen. | 9c551357-437f-4662-a8b5-0fac98831755 |
| PERS.4.2 | Rollenspezifische Schulungen und Sensibilisierungen | Personal für Nutzende SOLLTE rollenspezifische Schulungen und Sensibilisierungen im Einklang mit den Anforderungen der Praktik Sensibilisierung bei Ne | f5c0d014-bafa-4672-ad7d-fdb1fb16f3c4 |
| PERS.4.2.1 | Produktspezifische Schulungen und Sensibilisierungen | Personal für Administrierende SOLLTE produktspezifische Schulungen zum Umgang mit administrativen Werkzeugen bei Neuzugang und dem Einsatz neuer IT-Pr | 5fa63606-a580-4995-a17e-41f05197ee2c |
| PERS.6.1 | Weggang | Personal für Nutzende SOLLTE eine Vorgehensweise für den Weggang verankern. | 3ad14c05-a8e1-45de-99bf-c3eecd11f3ae |
| PERS.6.1.1 | Entzug von Berechtigungen | Personal für Nutzende SOLLTE bei Weggang den unverzüglichen Entzug aller Zugriffsrechte im Einklang mit den Regelungen und Verfahren zum Berechtigungs | 4954a1d6-d1b5-4e95-9d74-a697e6030a14 |
| PERS.6.1.2 | Neubesetzung | Personal für Mitarbeitende SOLLTE bei Weggang frei gewordene Zuständigkeiten zuweisen. | 8c13947a-ea68-496e-8cdb-c5b807739cc2 |
| BES.1.3 | Lieferanten- und Dienstleisterverzeichnis | Beschaffungsmanagement für Einkäufe SOLLTE alle direkten Zulieferer und Dienstleister inklusive der jeweiligen Kontaktdaten und den bezogenen Lieferun | d02f25dc-07c0-4470-a43d-31d34bcf5af4 |
| BES.1.3.1 | Gesamte Lieferkette | Beschaffungsmanagement für Einkäufe KANN die gesamte Lieferkette inklusive der jeweiligen Unterauftragnehmer und deren Kontaktdaten dokumentieren. | 4aa61c74-cb3e-42ee-8217-ed9cabe74c3b |
| BES.1.4 | Outsourcing-Strategie | Beschaffungsmanagement für Outsourcing KANN eine Strategie mit Zielen, Chancen und Risiken des Outsourcings verankern. | 302952ea-72e1-4104-9cbb-678717a267db |
| BES.1.4.1 | Freigabe der Strategie | Beschaffungsmanagement für Outsourcing SOLLTE die Strategie durch die Institutionsleitung autorisieren. | 235c1c4a-c202-4d06-8391-254cac868ec2 |
| BES.1.5 | Autorisierung des Bereitstellungsmodells | Beschaffungsmanagement für Cloud-Dienste SOLLTE für jeden Cloud-Dienst das Bereitstellungsmodell durch {{ insert: param, bes.1.5-prm1 }} autorisieren. | 6d50b322-84b8-4c9b-bd2a-0b48d6b61847 |
| BES.1.6 | Dokumentation des Bereitstellungsmodells | Beschaffungsmanagement für Cloud-Dienste SOLLTE für jeden Cloud-Dienst das gewünschte Bereitstellungsmodell mit Ausführung der geteilten Verantwortlic | 43e11ef1-4161-444d-ba0d-0fed61d31dd8 |
| BES.1.7 | Vereinbarung der geteilten Verantwortung | Beschaffungsmanagement für Cloud-Dienste SOLLTE für jeden Cloud-Dienst mit dem Anbieter die geteilte Verantwortung vereinbaren. | 6cc29c32-b75a-4a6f-b260-1e5038f37866 |
| BES.2.1 | Erfassung des Bedarfes | Beschaffungsmanagement für Einkäufe SOLLTE den Bedarf anhand einer Leistungsbeschreibung oder einer Umsetzungsstrategie dokumentieren. | 0c2aa136-750b-4213-aa8a-1911537934e6 |
| BES.2.1.1 | Verwendungszweck | Beschaffungsmanagement für IT-Produkte SOLLTE den Verwendungszweck dokumentieren. | 419911b0-2fc0-4f2c-898d-062b9466c35d |
| BES.2.1.2 | Geschäftsprozessprofile | Beschaffungsmanagement für Outsourcing KANN Geschäftsprozessprofile für (Teil-)Prozesse, die ausgelagert werden, mit Funktion, verarbeiteten Informati | cf24172d-d505-4960-b580-ccea153e1abe |
| BES.2.1.3 | Systemvoraussetzungen | Beschaffungsmanagement für Anwendungen SOLLTE Systemvoraussetzungen dokumentieren. | 84f323b8-6090-4c5c-9ca4-48869567d624 |
| BES.2.1.4 | Kompatibilität | Beschaffungsmanagement für Einkäufe SOLLTE den Bedarf für die Kompatibilität mit der bestehenden Infrastruktur im Hinblick auf die Schnittstellen, die | 4625c5ac-57d7-404c-9ab3-620b724b36b8 |
| BES.2.1.5 | Lizenzierung | Beschaffungsmanagement für Anwendungen SOLLTE für den geplanten Einsatzzeitraum erforderliche Lizenzen dokumentieren. | 44fc68cb-5ee8-44aa-83ff-be56342c99dc |
| BES.2.1.6 | Support- und Wartungsverträge | Beschaffungsmanagement für IT-Produkte SOLLTE den Bedarf an Support- und Wartungsverträgen basierend auf dem Schutzbedarf für Verfügbarkeit dokumentie | 0cdd35ea-188d-4731-99e3-27b5dbe8eca6 |
| BES.2.2 | Dokumentation des Rechtsraums und der Datenlokation | Beschaffungsmanagement für Cloud-Dienste SOLLTE Rechtsraum und Datenlokation dokumentieren. | d4001ad1-3cac-4b4c-b075-dae3a8678a65 |
| BES.2.3 | Vereinbarung des Rechtsraums und der Datenlokation | Beschaffungsmanagement für Cloud-Dienste KANN Rechtsraum und Datenlokation mit dem Anbieter vereinbaren. | 00330bf7-9ed8-4606-bf6c-2657e7c47c61 |
| BES.2.4 | Anhörung Nutzender | Beschaffungsmanagement für Einkäufe SOLLTE Nutzende bei der Bedarfserfassung anhören. | d61dea6e-ac0f-42a9-8801-857fed920d50 |
| BES.2.5 | Anhörung Adminstrierender | Beschaffungsmanagement für Einkäufe SOLLTE Administrierende bei der Bedarfserfassung anhören. | 64a8bc51-2358-41c0-820d-d306f71d13ad |
| BES.2.6 | Outsourcing auf Grundlage der Geschäftsprozessprofile | Beschaffungsmanagement für Outsourcing KANN Outsourcingverträge auf Grundlage der Geschäftsprozessprofile durch die Leitung autorisieren. | 5b865e92-14ed-47a0-ae5f-219e5ef7b09b |
| BES.3.1 | Klassifizierung von Lieferantenbeziehungen | Beschaffungsmanagement für Einkäufe SOLLTE Lieferantenbeziehungen einer Klasse zuweisen. | 5d268fc9-f0f7-4d5d-ade2-68b6910070db |
| BES.3.2 | Auswahlkriterien | Beschaffungsmanagement für Einkäufe SOLLTE die Auswahl von Lieferanten anhand von Kriterien zu ihrer Verlässlichkeit verankern. | 3f92f682-56ae-447b-996e-a4b5f4bd8963 |
| BES.3.2.1 | Zertifizierte Lieferanten | Beschaffungsmanagement für Einkäufe KANN die Auswahl von Lieferanten anhand von Zertifikaten, Testaten oder Vergleichbarem verankern. | 66e8a313-c8cf-48e2-b04e-98013c2c9243 |
| BES.3.2.2 | Quellendiversifikation | Beschaffungsmanagement für Einkäufe KANN die Auswahl von Lieferanten anhand ihrer Fähigkeit, ihre Bezugsquellen zu diversifizieren und die Bindung an  | 6d1954f0-d3b8-4c4b-84bc-b0586d0d6476 |
| BES.3.3 | Unzuverlässige Lieferanten | Beschaffungsmanagement für Einkäufe SOLLTE die Beschaffung aus einer unbekannten oder unzuverlässigen Quelle untersagen. | 4bcaa246-3ee4-4d39-9998-d9ce1f5faf44 |
| BES.4.1 | Klassifizierung von Beschaffungsvorhaben | Beschaffungsmanagement für Einkäufe SOLLTE dem Beschaffungsvorhaben eine Klasse zuweisen. | 0e95983d-3def-4ce0-a037-31ed7dbc9ef8 |
| BES.4.2 | Dokumentation der Beschaffungskriterien | Beschaffungsmanagement für Einkäufe SOLLTE {{ insert: param, bes.4.2-prm1 }} für die Beschaffung dokumentieren. | 91319f26-75c0-476c-b544-aedd4dbf6e14 |
| BES.4.3 | Beschaffung anhand der Kriterien | Beschaffungsmanagement für Einkäufe SOLLTE die Beschaffung anhand der festgelegten Kriterien verankern. | f8089693-7d13-4f0e-b9a0-98102f685d74 |
| BES.4.4 | Vertragsvorlage für Outsourcing | Beschaffungsmanagement für Outsourcing SOLLTE Kriterien für Outsourcing-Dienstleistungen in einer standardisierten Richtlinie für Verträge dokumentier | 5e9bc675-aaa4-48eb-a7c2-5ab27fff09c4 |
| BES.4.5 | Security by Design | Beschaffungsmanagement für Einkäufe SOLLTE Security by Design vereinbaren. | 90462e6d-fc7a-4bf6-bffb-5f005d89aa7c |
| BES.4.5.1 | Entwicklung nach einem Sicherheitslebenszyklus | Beschaffungsmanagement für IT-Produkte KANN Nachweise zur Entwicklung nach einem Sicherheitslebenszyklus vereinbaren. | e6a52543-165f-4465-a59f-1928482a96c5 |
| BES.4.5.2 | Mandantentrennung | Beschaffungsmanagement für Outsourcing KANN eine festgelegte Mandantentrennung vereinbaren. | ffafe5ae-04e1-4aef-ae3f-2a3eeb193743 |
| BES.4.6 | Security by Default | Beschaffungsmanagement für Einkäufe SOLLTE Security by Default vereinbaren. | eaea6c10-713f-41d4-95f1-128784ef15d5 |
| BES.4.6.1 | Authentifizierung des Kunden | Beschaffungsmanagement für Dienstleistungen SOLLTE eine Authentifizierung vor dem Zugriff auf schützenswerte Informationen oder Dienste vereinbaren. | 812c1589-0233-4e24-a69b-d9a4b02e3c1e |
| BES.4.6.2 | Verschlüsselung | Beschaffungsmanagement für Outsourcing SOLLTE die Verschlüsselung schützenswerter Informationen durch den Anbieter vereinbaren. | adac1038-a7a7-4346-8c7e-22e322cf8f2b |
| BES.4.6.3 | Manipulationsschutz | Beschaffungsmanagement für IT-Produkte KANN Schutzmechanismen gegen Manipulationen auf dem Lieferweg vereinbaren. | 4e08941c-a1c7-4718-934f-c1e8c3e17864 |
| BES.4.7 | ISMS beim Dienstleister | Beschaffungsmanagement für Outsourcing SOLLTE ein Managementsystem für Informationssicherheit (ISMS) vereinbaren. | b70e7569-2d18-482b-8f7f-720cd0b1fcb7 |
| BES.4.8 | Konformitätsnachweise | Beschaffungsmanagement für Einkäufe SOLLTE Nachweise des Lieferanten zur Erfüllung der Sicherheitskriterien vereinbaren. | 3e56f7c0-63b1-4017-8e30-3a78c1f06693 |
| BES.4.8.1 | Zertifizierung | Beschaffungsmanagement für Einkäufe KANN ein Zertifikat oder Testat nach {{ insert: param, bes.4.8.1-prm1 }} vereinbaren. | 6cecab39-d08d-49a1-922e-b3f9ea7d5af4 |
| BES.4.8.2 | Cloud-Konformität | Beschaffungsmanagement für Cloud-Dienste SOLLTE einen Konformitätsnachweis durch Dritte vereinbaren. | ccb6ba42-3bb5-4ef8-b089-70a6e383f96c |
| BES.4.8.3 | IT-Grundschutz-Analyse der Infrastruktur | Beschaffungsmanagement für Outsourcing KANN eine IT-Grundschutz-Analyse der potenziell zu nutzenden Infrastruktur des Dienstleisters vereinbaren. | 989d9e29-9064-4366-a887-bc17c1440e35 |
| BES.4.8.4 | Offenlegung der Risikoanalyse | Beschaffungsmanagement für Outsourcing KANN eine Offenlegung der Risikoanalyse aus dem ISMS des Dienstleisters, soweit eine Risikoanalyse nach IT-Grun | ff58fdb4-bc6e-42fc-9e28-eb89a32bc656 |
| BES.4.9 | Sicherheitsüberprüfung | Beschaffungsmanagement für Einkäufe KANN Sicherheitsüberprüfungen für Personen, die vom Lieferanten mit der Vertragsdurchführung beauftragt werden, ve | ec083939-6e37-46be-978e-7b0c894ab768 |
| BES.5.1 | Kompetenzen | Beschaffungsmanagement für Dienstleistungen SOLLTE Kompetenzen in Informationssicherheit, die von den Mitarbeitern des Lieferanten verlangt werden, ve | b06b3614-ed43-4d03-a3af-700d7416f550 |
| BES.5.2 | Service Level Agreement | Beschaffungsmanagement für Outsourcing SOLLTE die Einhaltung einer bestimmten Dienstgüte anhand von {{ insert: param, bes.5.2-prm1 }} vereinbaren. | 31fea405-1180-4c99-b080-a90a2ee6f574 |
| BES.5.3 | Compliance-Verpflichtungen | Beschaffungsmanagement für Einkäufe SOLLTE die Übereinstimmung mit Compliance-Verpflichtungen vereinbaren. | 9c0e2a1c-59f9-4390-9d1c-6ec3417892a8 |
| BES.5.4 | Informationssicherheitskontrollmechanismen | Beschaffungsmanagement für Einkäufe SOLLTE Informationssicherheitskontrollmechanismen vereinbaren. | d2df7724-3a8a-4125-bd43-fa78cfe61d7b |
| BES.5.5 | Nutzungsregelungen | Beschaffungsmanagement für Dienstleistungen SOLLTE Regelungen zur Nutzung der Daten und damit verbundenen Assets vereinbaren. | cc1f6483-3c4d-4258-8f4c-f1d4dbff69c8 |
| BES.5.5.1 | Datenlokationen | Beschaffungsmanagement für Dienstleistungen KANN die Verarbeitung von Daten ausschließlich an von der Institution erlaubten Datenlokationen vereinbare | 5fc9434d-4d26-4383-ba5a-d921563f01ce |
| BES.5.5.2 | Autorisierung der Zugriffsberechtigung | Beschaffungsmanagement für Dienstleistungen SOLLTE Regelungen zur Autorisierung der Zugriffsberechtigung für Personal des Lieferanten anhand von {{ in | adb32e38-f59a-42fa-b1a0-67abd118c585 |
| BES.5.6 | Vergabe von Unteraufträgen | Beschaffungsmanagement für Einkäufe SOLLTE Regelungen für die Vergabe von Unteraufträgen vereinbaren. | 893be21d-b437-462d-9d29-193e2b6f62cc |
| BES.5.6.1 | Weitergabe der Beschaffungskriterien | Beschaffungsmanagement für Einkäufe SOLLTE die Weitergabe der Beschaffungskriterien an Unterauftragnehmer vereinbaren. | 58f15c9a-d587-4971-8239-d99a01478dca |
| BES.5.6.2 | Autorisierung von Unterauftragnehmern | Beschaffungsmanagement für Einkäufe KANN die Autorisierung von Unterauftragnehmern durch den Auftraggeber vereinbaren. | 4b719eae-3c29-4579-ad77-653ab02ee880 |
| BES.5.6.3 | Nachverfolgbarkeit der Lieferkette | Beschaffungsmanagement für IT-Produkte KANN die Nachverfolgbarkeit der gesamten Lieferkette bis zum Hersteller für {{ insert: param, bes.5.6.3-prm1 }} | 95512f8d-eca6-4928-a56f-1a58e5fcf3f0 |
| BES.5.7 | Schulung | Beschaffungsmanagement für Einkäufe KANN eine Schulung zur Nutzung gelieferter Sicherheitsmechanismen vereinbaren. | c95ea1ad-f766-43e2-a07d-1eb50cc58907 |
| BES.5.8 | Rechte für geistges Eigentum | Beschaffungsmanagement für Dienstleistungen SOLLTE für geistiges Eigentum, das während der Vertragslaufzeit entwickelt wird,  die Eigentumsrechte vere | fbf79e86-d03e-44bb-9fec-87ad6ade595c |
| BES.5.9 | Umgang mit Änderungen | Beschaffungsmanagement für Dienstleistungen SOLLTE Regelungen für den Umgang mit Änderungen vereinbaren. | 114cc12e-3b48-4632-ae06-d50a461dcd3a |
| BES.5.9.1 | Autorisierung von Änderungen | Beschaffungsmanagement für Dienstleistungen KANN die Autorisierung von Änderungen durch den Auftraggeber vereinbaren. | a47e5549-802f-4d91-a69e-a537a813ba19 |
| BES.5.10 | Behandlung von Vorfällen | Beschaffungsmanagement für Einkäufe SOLLTE Regelungen für die Behandlung von Vorfällen vereinbaren. | 61055c24-1924-4b3f-804c-d96e2a683821 |
| BES.5.10.1 | Meldewege | Beschaffungsmanagement für Einkäufe SOLLTE die Erreichbarkeit des Lieferanten über bestimmte Meldewege vereinbaren. | f2e723f5-6a1a-4358-bce2-458523049346 |
| BES.5.10.2 | Melden von Vorfällen | Beschaffungsmanagement für Einkäufe SOLLTE eine Verpflichtung zur unverzüglichen Information des Auftraggebers über ihn betreffende Vorfälle vereinbar | d359fe31-8bf1-47ae-bbcc-e572b1998d52 |
| BES.5.10.3 | Schwachstellenbehebung | Beschaffungsmanagement für Einkäufe SOLLTE eine Verpflichtung für Lieferanten, die den Auftraggeber betreffende Schwachstelle zeitnah zu beheben, vere | d7946adc-4cf2-4fc9-aad7-9d43c6855384 |
| BES.5.10.3.1 | Schwachstellenmeldeprozess | Beschaffungsmanagement für IT-Produkte KANN einen Schwachstellenmeldeprozess nach {{ insert: param, bes.5.10.3.1-prm1 }} vereinbaren. | ebc08e41-e728-4447-93fa-233fbad7f2fa |
| BES.5.10.4 | Konfliktlösungsprozesse | Beschaffungsmanagement für Einkäufe KANN Prozesse zur Lösung von Konflikten zwischen den Vertragsparteien vereinbaren. | 3535784d-dd78-4fd2-be25-4a2e183087b2 |
| BES.5.10.5 | Konsequenzen bei Verstößen | Beschaffungsmanagement für Einkäufe KANN Abhilfemaßnahmen für den Fall von Verstößen durch den Lieferanten vereinbaren. | 119a13e9-ea12-41a3-a974-2d1cba295fb8 |
| BES.5.11 | Recht auf Audit | Beschaffungsmanagement für Outsourcing SOLLTE ein Recht des Auftraggebers zur Überprüfung der Sicherheitsprozesse und -maßnahmen, die im Zusammenhang  | 4725e406-7802-4a0a-98a5-2195ba2d26d1 |
| BES.5.12 | Informationspflichten | Beschaffungsmanagement für Dienstleistungen SOLLTE eine Pflicht des Lieferanten, den Auftraggeber regelmäßig über die Wirksamkeit der Sicherheitsmaßna | 24f08281-8abf-4a70-8502-72b86f1ca02a |
| BES.5.13 | Bereitstellung von Datensicherungen | Beschaffungsmanagement für Dienstleistungen SOLLTE eine Verpflichtung des Lieferanten, Sicherungskopien regelmäßig bereitzustellen, vereinbaren. | 25e60ed2-9a85-4d03-be14-050253846f38 |
| BES.5.13.1 | Datenbereitstellung | Beschaffungsmanagement für Outsourcing KANN die Bereitstellung der beim Dienstleister verarbeiteten Daten in einem standardisierten Format vereinbaren | 8efd929d-ccc8-422f-b5ae-915fbfc41ddc |
| BES.5.14 | Löschregeln | Beschaffungsmanagement für Outsourcing SOLLTE die Löschung von Daten während der Vertragslaufzeit im Einklang mit den Compliance-Verpflichtungen der I | b75b1a85-9a93-4f76-a9c4-846a0409490e |
| BES.6.1 | Entziehung der Zugangsberechtigungen | Beschaffungsmanagement für Dienstleistungen SOLLTE die Entziehung der für den Vertrag relevanten Zugangsberechtigungen für den Fall einer Kündigung ve | 0e6eb46f-3941-4f64-9fd6-709517a01ad1 |
| BES.6.2 | Löschung von Daten | Beschaffungsmanagement für Dienstleistungen SOLLTE die Löschung aller beim Dienstleister vorhandenen Daten für den Fall einer Kündigung vereinbaren. | 90d55cb8-c0ff-4805-8b45-77aac247c786 |
| BES.6.2.1 | Löschverfahren | Beschaffungsmanagement für Dienstleistungen KANN ein Verfahren zur nicht wiederherstellbaren Löschung für den Fall einer Kündigung vereinbaren. | d0ba4d21-940d-4b06-b446-aeccfdb2b53a |
| BES.6.3 | Übertragbarkeit von Daten | Beschaffungsmanagement für Dienstleistungen SOLLTE die Übertragbarkeit von Daten, Konfigurationen und der Funktionalität für den Fall einer Kündigung  | 4e0fd86f-d5b5-41a8-a25d-0a61630fc37c |
| BES.6.4 | Übertragung von Supportdienstleistungen | Beschaffungsmanagement für Dienstleistungen KANN die Übergabe der Supportdienstleistungen für den Fall einer Kündigung vereinbaren. | 4a487564-f53e-420d-bcc3-e7e35edcf162 |
| BES.6.5 | Behandlung aufzubewahrender Aufzeichnungen | Beschaffungsmanagement für Dienstleistungen SOLLTE Kontrollmechanismen zur Behandlung aufzubewahrender Aufzeichnungen für den Fall einer Kündigung ver | a397ee7e-3766-4454-9805-c2b31ffcb80e |
| BES.6.6 | Rückgewähr von Assets | Beschaffungsmanagement für Dienstleistungen SOLLTE die Rückgewähr von Assets für den Fall einer Kündigung vereinbaren. | 005f0ce7-9372-49b6-b78b-c09a5e2f56f0 |
| BES.7.1 | Eingangskontrolle | Beschaffungsmanagement für Einkäufe SOLLTE erbrachte oder gelieferte Leistungen anhand von {{ insert: param, bes.7.1-prm1 }} vor der ersten Verwendung | abea6f59-f58b-47c3-b908-7ae68410fde3 |
| BES.7.1.1 | Test der Kompatibilität | Beschaffungsmanagement für Outsourcing SOLLTE die Kompatibilität des Dienstes mit dem Informationsverbund im Hinblick auf die Schnittstellen, die Netz | a2157baa-d3d7-4527-a9e9-7325a2b7b9ff |
| BES.7.1.2 | Netzcheck | Beschaffungsmanagement für Outsourcing SOLLTE die Umsetzung der geforderten Beschaffungskriterien für die Netzanbindung vor der Netzanbindung testen. | 2e2346ed-c3fd-4c96-89f7-7ed920eb8d1a |
| BES.7.2 | Prozesse vor Netzanbindung | Beschaffungsmanagement für Outsourcing SOLLTE vor Anbindung des Datennetzes der Nutzenden an das Datennetz der Anbietenden alle sicherheitsrelevanten  | 1421e376-1f13-4381-a30f-597ec113d205 |
| BES.7.3 | Anhörung Prozessbeteiligter | Beschaffungsmanagement für Outsourcing SOLLTE alle am ausgelagerten Prozess beteiligten Mitarbeiter oder Rollen anhören. | 805426be-1d47-46f0-88ab-0014e484fb9a |
| BES.7.4 | Vollständigkeit der Unterlagen | Beschaffungsmanagement für Einkäufe SOLLTE Informationen, die für eine bestimmungsgemäße Verwendung im Informationsverbund erforderlich sind, dokument | 1e4fa113-4c3b-4853-9b12-86f02abd1706 |
| BES.7.4.1 | Beschreibung der Sicherheitsarchitektur | Beschaffungsmanagement für IT-Produkte SOLLTE eine Beschreibung der Sicherheitsarchitektur dokumentieren. | fca365f8-601e-4e9f-8b8a-1cc54c2936fb |
| BES.7.4.2 | Beschreibung von Sicherheitsmechanismen | Beschaffungsmanagement für IT-Produkte SOLLTE eine Beschreibung der gelieferten Sicherheitsmechanismen dokumentieren. | 223cfe79-7b19-4c57-9535-b36c486f810f |
| BES.7.4.3 | Empfohlene Konfiguration | Beschaffungsmanagement für IT-Produkte SOLLTE eine vom Hersteller oder Lieferanten für den sicheren Betrieb empfohlene Konfiguration dokumentieren. | 17260753-9f50-4480-bfbc-226a362b0ab6 |
| BES.7.4.4 | Dokumentation der Komponenten | Beschaffungsmanagement für Einkäufe SOLLTE eine Beschreibung der verwendeten Hardware- und Softwarekomponenten dokumentieren. | 06967239-6b5a-4329-bf28-e910cebefd45 |
| BES.7.4.4.1 | Software Bill of Materials (SBOM) | Beschaffungsmanagement für IT-Produkte KANN für jede gelieferte Software die entsprechende Software Bill of Materials (SBOM) nach {{ insert: param, be | f89b0154-ccb8-401f-b352-9135e685a4e7 |
| BES.7.4.5 | Netzverbindungen ab Werk | Beschaffungsmanagement für IT-Produkte SOLLTE eine Liste der Internetserver, mit denen das IT-Produkt von sich aus Verbindung aufnimmt, mit Zweck der  | f901b96c-6a92-46aa-834d-0b398d46482e |
| BES.7.4.6 | Shared Responsibility | Beschaffungsmanagement für Dienstleistungen SOLLTE die Verteilung der Zuständigkeiten und deren Abgrenzung dokumentieren. | e7afc3eb-feac-4cad-8ad4-a46a867f45d8 |
| BES.7.4.7 | Organisatorische Schnittstellen | Beschaffungsmanagement für Dienstleistungen SOLLTE die organisatorischen Schnittstellen des Dienstleisters dokumentieren. | c8752d5c-3fbf-4853-95f8-d5d87df73b7e |
| BES.7.4.8 | Technische Schnittstellen | Beschaffungsmanagement für Dienstleistungen SOLLTE die vom Dienstleister bereitgestellten technischen Schnittstellen und deren Sicherheitsfunktionalit | e0b880c1-c7a8-491a-a8c4-df081ed9a8d4 |
| BES.7.4.9 | Auslagerungsregister | Beschaffungsmanagement für Outsourcing SOLLTE Informationen über den Dienstleister, die Kritikalität des Prozesses, abgeschlossene Verträge und Verein | ca2e05d8-da09-45f2-b9e7-48e3ef4b032c |
| BES.7.4.10 | Serviceprofil | Beschaffungsmanagement für Cloud-Dienste SOLLTE für jeden geplanten oder genutzten Cloud-Dienst ein Serviceprofil mit dem Namen des Services und des A | 406b5a6e-fb23-4a70-8d6d-2a5965513eb4 |
| BES.7.4.11 | Mandantentrennung | Beschaffungsmanagement für Outsourcing KANN die beim Dienstleister implementierten Maßnahmen zur Mandantentrennung nach Vertragsschluss dokumentieren. | d59ad53c-00d4-4bfd-8af9-bf09722731c5 |
| BES.7.4.12 | Software Bill of Materials (SBOM) - Cloud | Beschaffungsmanagement für Cloud-Dienste KANN für jede gelieferte Software-as-a-Service (SaaS) die entsprechende Software Bill of Materials (SBOM) nac | 7a3321a5-9f54-4ada-955d-647aeb0e51b5 |
| BES.8.1 | Bereithaltung alternativer Lieferanten | Beschaffungsmanagement für Einkäufe KANN die Bereithaltung alternativer Lieferanten verankern. | 7a7af54d-83c0-4a32-900f-e4ff9ac02450 |
| BES.8.2 | Verfahren zur Übertragung von Geschäftsprozessen | Beschaffungsmanagement für Outsourcing KANN Verfahren zur Übertragung von Geschäftsprozessen für den Fall einer geplanten oder ungeplanten Beendigung  | e69b2846-6b36-4b3e-8fbc-e1ccd17f4f48 |
| BES.8.3 | Ressourcensouveränität | Beschaffungsmanagement für Outsourcing KANN ausreichende interne Ressourcen für den Fall einer geplanten oder ungeplanten Beendigung des Vertrages zuw | c928db22-3ace-445e-b501-7ebb8fbd9c2d |
| BES.8.4 | Individuelle Implementierung kritischer Komponenten | Beschaffungsmanagement für IT-Produkte KANN eine eigens für die Institution entwickelte Implementierung kritischer Komponenten vereinbaren. | c3ef1d10-5c10-4411-9a02-bb352211bc88 |
| BES.8.5 | Treuhand | Beschaffungsmanagement für Dienstleistungen KANN ESCROW- bzw. Treuhandverträge vereinbaren. | a5f72086-9f22-4376-9b24-25ca429542d6 |
| DEV.2.2 | Dokumentation der (Software-)Architektur | Entwicklung für Anwendungen SOLLTE die Architektur dokumentieren. | 79eb639b-25ed-4ce3-9d8f-c57b573c1ee3 |
| DEV.2.3 | Ausführbarkeit mit minimalen Rechten | Entwicklung für Anwendungen SOLLTE die fehlerfreie Ausführung mit den geringst möglichen Berechtigungen verankern. | 88b87ec7-be5f-4740-a226-6b23994f86b4 |
| DEV.2.5 | Einschränkung des Zugriffs auf Zugangsdaten | Entwicklung für Anwendungen SOLLTE den lesenden und schreibenden Zugriff auf Zugangsdaten einschränken. | 3a2e18f2-8f77-4f7d-9fc9-cfadbf576c04 |
| DEV.2.6 | Widerstandsfähigkeit gegen gängige Angriffsmuster | Entwicklung für Anwendungen SOLLTE Schutzfunktionen gegen gängige Angriffsmuster installieren. | 65ec8cf9-f2aa-4eb5-85a6-914c3da3e148 |
| DEV.2.6.1 | Eingabevalidierung | Entwicklung für Anwendungen SOLLTE Eingabedaten auf eingeschleuste Befehle testen. | 467ae9d3-922b-44eb-9527-d617416e5330 |
| DEV.2.6.2 | Ausgabekodierung | Entwicklung für Anwendungen SOLLTE eine Ausgabekodierung ausführen. | dee85b12-b7f9-445e-802a-bbe13d67538e |
| DEV.3.1 | Replay-Angriffe | Entwicklung für Anwendungen SOLLTE Replay-Angriffe blockieren. | 2eeb41fa-2354-4ea3-a641-c7e5a33a3087 |
| DEV.3.2 | Routinen zur Fehlerbehandlung | Entwicklung für Anwendungen SOLLTE spezifische und allgemeine Routinen zur Fehlerbehandlung ausführen. | e06f7f69-4c90-4e39-b6be-a9428548e824 |
| DEV.3.3 | Deaktivierung der Ausgabe schützenswerter Daten durch Fehlermeldungen | Entwicklung für Anwendungen SOLLTE die Ausgabe schützenswerter Daten durch Fehlermeldungen deaktivieren. | 2b3f6962-b23f-4698-984e-f5b942ab2fdd |
| DEV.3.4 | Passwort-Hashing | Entwicklung für Anwendungen SOLLTE das Hashing von Passwörtern, die zur Authentifizierung an der Anwendung verwendet werden vor der Verarbeitung oder  | 6b7d5613-a32c-4a47-8a4f-766053da0e74 |
| DEV.4.1 | Nutzerinformation bei kritischen Ereignissen | Entwicklung für Anwendungen SOLLTE bei sicherheitskritischen Ereignissen die betroffenen Nutzenden informieren. | 15c87c6f-7b62-4dcf-88a5-f38bb5a00ce5 |
| DEV.4.2 | Bibliotheksquellen | Entwicklung für Anwendungen SOLLTE die Einbindung externer Softwarebibliotheken und -Schnittstellen aus unzuverlässigen oder unbekannten Quellen unter | 54b5a504-5b17-4fea-8514-079d99eb0102 |
| DEV.4.3 | SBOM | Entwicklung für Anwendungen SOLLTE die Bestandteile mit Hilfe einer Software Bill of Materials (SBOM) vor dem Release dokumentieren. | 5b695087-3a35-441a-b8c9-9937a681a996 |
| DEV.4.4 | Integrität externer Softwarebibliotheken | Entwicklung für Anwendungen SOLLTE die Integrität externer Softwarebibliotheken vor dem Release testen. | 62b75210-9470-456f-a191-9bbe48da5313 |
| DEV.4.5 | Updates externer Softwarebibliotheken | Entwicklung für Anwendungen SOLLTE externe Softwarebibliotheken auf Sicherheitsupdates vor dem Release testen. | 3d451248-af76-44a4-87b9-8a86cdff4c28 |
| DEV.4.6 | Compileroptionen | Entwicklung für Anwendungen SOLLTE Compileroptionen für Sicherheitsfunktionen vor dem Release aktivieren. | 615f77e2-9734-4778-ba5a-95a6b80a92d9 |
| DEV.4.7 | Deterministischer Binärcode | Entwicklung für Anwendungen KANN eine reproduzierbare Vorgehensweise zur Erstellung eines bestimmten Binärcodes aus dem Quellcode dokumentieren. | 973bc793-3acb-4d77-9b7e-9599090c3779 |
| DEV.4.8 | Default-Zugangsdaten | Entwicklung für Anwendungen SOLLTE Default-Zugangsdaten vor dem Release dokumentieren. | 00fa92b3-76a1-40ac-b7ad-d4c0a4e0ae64 |
| DEV.4.9 | Voreinstellungen nach dem Prinzip "Security by Default" | Entwicklung für Anwendungen SOLLTE Voreinstellungen nach dem Prinzip "Security by Default" aktivieren. | fa1f8609-00d9-4d70-84cb-b3616efea279 |
| DEV.4.10 | Protokollierung von Codeänderungen | Entwicklung für Anwendungen SOLLTE Änderungen am Quellcode einschließlich Zeitpunkt, Inhalt der Änderung, ändernder Person und der Begründung der Ände | e2458854-ad5a-433f-896c-e3eef23b6952 |
| DEV.4.11 | Test bei Änderungen am Quellcode | Entwicklung für Anwendungen SOLLTE Änderungen am Quellcode im Einklang mit den Verfahren und Regelungen für Änderungen und Tests testen. | 080fdbcd-0a91-4374-9d1a-c7a1eb078e97 |
| DEV.5.1 | Verankerung des Zeitraums für Updates | Entwicklung für Anwendungen SOLLTE einen Zeitraum der Bereitstellung von Sicherheitsupdates verankern. | 649b5b3b-fd58-4bec-84bb-71c93b264f94 |
| DEV.5.2 | Information über Zeitraum für Updates | Entwicklung für Anwendungen SOLLTE Auftraggeber über den festgelegten Zeitraum für Sicherheitsupdates informieren. | ca255009-1c23-47a7-b0f6-a79693b47b95 |
| DEV.5.3 | Integritätsprüfung | Entwicklung für Anwendungen SOLLTE Nutzende über Möglichkeiten zur Verifikation der Integrität von Installations-, Update- und Patchdateien informiere | 878e31fd-614f-4034-8d96-2604e4ed6b92 |
| DEV.7.2 | Zertifikatsmonitoring | Entwicklung für Anwendungen SOLLTE die Ausstellung neuer Zertifikate für die von der Anwendung verwendeten Domains überwachen. | 61b03a52-d68e-4bda-b715-91cac2e70e87 |
| KONF.2.1 | Grundkonfiguration für Systeme | Konfiguration für IT-Systeme SOLLTE eine Grundkonfiguration dokumentieren. | 8bd05aba-b395-43cf-a38e-f4e8656df7c4 |
| KONF.2.1.1 | Versionierung | Konfiguration für IT-Systeme SOLLTE eine Versionierung vorheriger Konfigurationen verankern. | 3b25d629-b441-4365-96fb-d06e2e35b89d |
| KONF.2.2 | Kryptographische Verfahren und Protokolle | Konfiguration für IT-Systeme SOLLTE kryptographische Verfahren und Protokolle im Einklang mit den zugehörigen Anforderungen zum Identitäts- und Berech | e4570c64-4790-4a5c-95e4-4c168d447566 |
| KONF.2.3 | Änderung von Default-Zugangsdaten | Konfiguration für IT-Systeme SOLLTE die Änderung von Default-Zugangsdaten ausführen. | 14a61781-67a3-41c7-9f73-89d5809ea2b0 |
| KONF.2.4 | Deaktivierung nicht benötigter Systemfunktionen | Konfiguration für IT-Systeme SOLLTE nicht benötigte Systemfunktionen deaktivieren. | 24c072af-d71b-4d57-8b8f-119194e5cb8a |
| KONF.2.4.1 | Nicht benötigte Zertifikate | Konfiguration für IT-Systeme SOLLTE nicht benötigte Zertifikate deaktivieren. | 4a22520b-123c-422a-a871-0bc5b20b9ec3 |
| KONF.2.4.2 | Externe Cloud-Anbindungen | Konfiguration für IT-Systeme SOLLTE nicht benötigte Cloud-Anbindungen deaktivieren. | 35875b35-0c23-473e-b1d6-1741c315dc88 |
| KONF.2.5 | Überprüfung der Konfiguration | Konfiguration für IT-Systeme SOLLTE die Übereinstimmung der tatsächlichen Konfiguration mit dem Referenzzustand {{ insert: param, konf.2.5-prm1 }} übe | a37d5c17-d296-4810-ac13-4a15e7b40e97 |
| KONF.2.5.1 | Automatische Konfigurationsverwaltung | Konfiguration für IT-Systeme KANN die Überprüfung der Konfiguration durch {{ insert: param, konf.2.5.1-prm1 }} aktivieren. | fceb6b0b-2cf9-4644-9f48-c6b307b2d0ad |
| KONF.2.5.1.1 | Automatische Konfigurationsverwaltung | Konfiguration für Endgeräte SOLLTE die Verwaltung durch ein Mobile Device Management (MDM) verankern. | c209d678-2ee3-48f9-8fce-016b4f49481c |
| KONF.2.6 | Souveräne Werkzeuge | Konfiguration für IT-Systeme KANN Souveräne Werkzeuge installieren. | 9b18fd2e-8300-49d5-b244-88df6674c5c6 |
| KONF.2.7 | Alternative Administrationszugänge | Konfiguration für IT-Systeme KANN alternative Administrationszugänge installieren. | 076ffb7b-6f9e-4f71-8752-cfaa290ee306 |
| KONF.2.8 | Abgesicherter und authentisierter Bootprozess | Konfiguration für IT-Systeme KANN einen abgesicherten und authentisierten Bootprozess aktivieren. | 8d460d82-f7db-42c5-b213-625df4381ff3 |
| KONF.3.1 | Kryptographischer Hardwarespeicher | Konfiguration für IT-Systeme SOLLTE einen kryptographischen Hardwarespeicher aktivieren. | 5c63c101-f2d6-479c-963c-0280bd2fb8a7 |
| KONF.3.2 | Speicherverschlüsselung | Konfiguration für IT-Systeme SOLLTE integrierte Festspeichermedien verschlüsseln. | e760f62d-1c68-4665-b07b-5b2846550d59 |
| KONF.3.3 | SIM-PIN | Konfiguration für IT-Systeme SOLLTE bei Mobilfunkanschluss eine SIM-PIN aktivieren. | f2184ae3-ca55-4b77-9727-46deb4b9d0ff |
| KONF.3.4 | Physischer Diebstahlschutz | Konfiguration für Endgeräte KANN einen physischen Diebstahlschutz installieren. | 0984599f-2227-4f74-befe-5a1e11b656b0 |
| KONF.3.5 | Standortbestimmung | Konfiguration für IT-Systeme KANN eine Funktion zur Bestimmung des Standortes aus der Ferne {{ insert: param, konf.3.5-prm1 }} aktivieren. | 4a18939a-0972-4ac7-9584-18fffde38db6 |
| KONF.3.6 | Fernlöschung oder -sperre | Konfiguration für Endgeräte KANN eine Funktion zur Fernlöschung oder -sperre aktivieren. | 4757578a-1000-49e7-96fa-d91affa2c768 |
| KONF.3.6.1 | Automatische Fernlöschung oder -sperre | Konfiguration für Endgeräte KANN eine automatische Fernlöschung oder -sperre bei Inaktivität nach {{ insert: param, konf.3.6.1-prm1 }} aktivieren. | ffc45c05-597f-4be9-9358-124b4a008e50 |
| KONF.3.7 | Einschränkung angeschlossener Peripherie | Konfiguration für IT-Systeme SOLLTE angeschlossene Peripherie einschränken. | e699dfd7-ecc7-4ca6-bce8-3cd1ba44804d |
| KONF.3.8 | Einschränkung von Wechselmedien | Konfiguration für IT-Systeme SOLLTE das automatische Einbinden von Wechselmedien einschränken. | 54314ee4-e904-4ae2-b348-7460f6ebb338 |
| KONF.4.1 | Anbindung an Verzeichnisdienst | Konfiguration für IT-Systeme SOLLTE die Anbindung an einen Verzeichnisdienst aktivieren. | 99b370b9-b48c-4f68-b88c-d44ef31f83e0 |
| KONF.4.1.1 | Weiterleitung von Anmeldeinformationen | Konfiguration für IT-Systeme SOLLTE die Weiterleitung mehrfach verwendbarer Anmeldeinformationen deaktivieren. | 6089e247-2518-4c90-b991-df8cbb24585f |
| KONF.4.2 | DNS-Anbindung | Konfiguration für IT-Systeme SOLLTE die vom System verwendeten DNS-Server autorisieren. | 490400dc-4769-4127-9869-720a3ce1585c |
| KONF.4.2.1 | DNS-Verschlüsselung | Konfiguration für IT-Systeme SOLLTE DNS-Verschlüsselung aktivieren. | ccb6bfb1-1b49-4d03-9705-2d05bca018b5 |
| KONF.4.3 | Authentifizierung von Fernwartungsfunktionen | Konfiguration für IT-Systeme SOLLTE Fernwartungsfunktionen im Einklang mit den zugehörigen Anforderungen zum Identitäts- und Berechtigungsmanagement a | 6fa4659a-8472-4d26-9f3b-a3edfa412a8c |
| KONF.4.4 | Einschränkung von Fernwartungsfunktionen | Konfiguration für IT-Systeme SOLLTE Fernwartungsfunktionen im Einklang mit den zugehörigen Anforderungen zum Identitäts- und Berechtigungsmanagement e | 2e782e35-d708-49c3-b022-76616ae204be |
| KONF.4.5 | Zeitquellen | Konfiguration für IT-Systeme SOLLTE Zeitquellen autorisieren. | 92eee157-2b9b-4a80-8f17-4b124590d72f |
| KONF.5.1 | Authentifizierung am System | Konfiguration für IT-Systeme SOLLTE den Zugriff auf das System im Einklang mit den zugehörigen Anforderungen zum Identitäts- und Berechtigungsmanageme | cc0d5002-8ef3-434c-b19f-15f0f226a6cb |
| KONF.5.1.1 | Authentifizierung an der Firmware | Konfiguration für IT-Systeme SOLLTE den Zugriff auf die Firmware im Einklang mit den zugehörigen Anforderungen zum Identitäts- und Berechtigungsmanage | e9bd0b40-47ed-4e4d-a747-ad71884f076f |
| KONF.5.1.2 | Pre-Boot-Authentifizierung | Konfiguration für Endgeräte KANN den Zugriff vor dem Start des Betriebssystems authentifizieren. | 89f6db4b-b55b-4218-aad6-6f5c33a49ee6 |
| KONF.5.2 | Keine Mehrfachanmeldung | Konfiguration für IT-Systeme SOLLTE die gleichzeitige Anmeldung mehrerer Zugangskonten deaktivieren. | 71f7d8c3-4e50-45b8-a01a-5ee7b957d31b |
| KONF.6.1 | Minimal erforderliche Berechtigungen für Anwendungen | Konfiguration für IT-Systeme SOLLTE erforderliche Berechtigungen für Anwendungen einschränken. | cc6a9a9d-cb65-4e22-aad5-d93f73e522b8 |
| KONF.6.1.1 | Datenkapselung | Konfiguration für IT-Systeme KANN Datenkapselung aktivieren. | 6bb18861-0616-4cde-afed-7929b71ba16c |
| KONF.6.1.2 | Isolierung von Anwendungen | Konfiguration für IT-Systeme KANN Isolierung von Anwendungen aktivieren. | d380c6d8-1ab0-4e4b-bcca-2e620b40d934 |
| KONF.6.1.3 | Isolierte Arbeitsumgebungen | Konfiguration für Endgeräte KANN eine isolierte Arbeitsumgebungen aktivieren. | cfe748d3-22ff-4f2c-8bb0-d22338c67f45 |
| KONF.6.2 | Gemeinsam genutzte Verzeichnisse | Konfiguration für Endgeräte SOLLTE die Zugriffsrechte gemeinsam verwendeter Verzeichnisse einschränken. | ec10cb70-9101-4293-ab4c-92d57f84af77 |
| KONF.6.3 | Kiosk-Modus | Konfiguration für Endgeräte KANN das automatische Zurücksetzen auf einen definierten Zustand nach der Nutzung aktivieren. | 1b90a130-be97-42bf-8d30-8458a1d743ee |
| KONF.6.4 | Privilegierte Systemfunktionen | Konfiguration für IT-Systeme SOLLTE privilegierte Funktionen einschränken. | f129ae20-1423-4df0-a735-db8365592cd1 |
| KONF.6.4.1 | Rollenbasierte Privilegierung | Konfiguration für IT-Systeme KANN rollenbasiertes Berechtigungsmanagement aktivieren. | b20ab43c-96f3-4bc4-8a4c-1dca837bb41f |
| KONF.6.5 | Dynamische Zugriffskontrolle im System | Konfiguration für IT-Systeme KANN dynamische Zugriffskontrolle im System aktivieren. | ced10fd0-a74e-4376-8dac-f3381c6a9482 |
| KONF.6.6 | Getrennte Datenhaltung | Konfiguration für Anwendungen SOLLTE Zugriffe eines Zugangskontos auf Daten anderer Zugangskonten einschränken. | 55e2c264-c09d-4967-83ab-f4430f898099 |
| KONF.6.6.1 | Mandantenfähigkeit | Konfiguration für Anwendungen SOLLTE wenn die Anwendung mehrere Mandaten bedient, für jeden Mandanten eine eigene Berechtigungskonfiguration aktiviere | 2f0d27ba-6f8f-4f1e-9f5b-29cd79d7b08d |
| KONF.6.7 | Privilegierte Funktionen der Anwendung | Konfiguration für Anwendungen SOLLTE privilegierte Funktionen einschränken. | 91968d63-7ef1-4625-a3a5-039c340577b1 |
| KONF.6.8 | Berechtigungen des Webserver-Prozesses | Konfiguration für Webserver SOLLTE die Berechtigungen des Webserver-Prozesses einschränken. | 342916fa-e073-4db3-906c-af2563081e6e |
| KONF.6.9 | Zugriff auf Code | Konfiguration für Webserver SOLLTE den Zugriff auf Quelldateien einschränken. | c6624f60-f990-4900-84ef-747d5a6e81c6 |
| KONF.6.10 | Auflistung von Verzeichnisinhalten | Konfiguration für Webserver SOLLTE die Auflistung von Verzeichnisinhalten einschränken. | ce8d6ad1-d414-48a3-b273-50fa01fd2ee6 |
| KONF.6.11 | Einschränkung von Uploads | Konfiguration für Webserver SOLLTE Uploads einschränken. | 80201ed2-a627-4240-86c1-0d91415f96b5 |
| KONF.6.12 | Konferenzmoderation | Konfiguration für VK-Anwendungen SOLLTE Konferenzmoderation aktivieren. | 862961f1-924d-4557-9f81-e31730162561 |
| KONF.6.13 | Dynamische Zugriffskontrolle in der Anwendung | Konfiguration für Anwendungen KANN dynamische Zugriffskontrolle in der Anwendung aktivieren. | 55dfbf64-f1f3-4765-a0d3-78f0a1f00654 |
| KONF.6.14 | Browser Sandboxing | Konfiguration für Webbrowser SOLLTE Browser Sandboxing aktivieren. | 9b157336-4f35-43f5-90e2-704c00d452e5 |
| KONF.6.15 | Virtualisierte Browser-Umgebung | Konfiguration für Webbrowser KANN Virtualisierte Browser-Umgebung aktivieren. | 2717f887-571c-4830-a5de-a87c44bbca23 |
| KONF.6.16 | Datenaustausch in der Virtualisierung | Konfiguration für Virtualisierungslösungen KANN den Datenaustausch zwischen virtualisierten Client einschränken. | 55db7b45-c04c-42c6-b803-eacd27aee6c7 |
| KONF.7.1 | Echtzeitscanner | Konfiguration für IT-Systeme SOLLTE eine automatische Prüfung auf Schadcode bei Installation oder Öffnung von Dateien aktivieren. | 7356791e-0f8c-4f3a-82f9-37f55a2d66b2 |
| KONF.7.2 | Regelmäßige Scans | Konfiguration für IT-Systeme SOLLTE einen regelmäßigen Scan von Dateien auf dem System nach potenziellem Schadcode aktivieren. | 3fefd9d3-8925-4c08-b2b3-c92775b0279a |
| KONF.7.3 | Host-basierte Angriffserkennung | Konfiguration für IT-Systeme SOLLTE Host-basierte Angriffserkennung aktivieren. | c6ea1218-1fc7-472f-96e5-df42b2acafa9 |
| KONF.7.4 | Angriffserkennung anhand von Netzverkehr | Konfiguration für IT-Systeme KANN Angriffserkennung anhand von Netzverkehr aktivieren. | e6dd6f93-4901-41bd-86ed-ba88ff5c5bf3 |
| KONF.7.5 | Alarmierung | Konfiguration für IT-Systeme SOLLTE eine Benachrichtigung bei potenziellem Schadcode aktivieren. | a0afaca3-947c-4b5b-8bc0-c29f623075e0 |
| KONF.7.6 | Automatische Updates | Konfiguration für IT-Systeme SOLLTE Automatische Updates der Mechanismen zur Schadcodeerkennung aktivieren. | 9ec7a448-9f0e-45bb-b71d-537fe2ef7f0c |
| KONF.7.7 | Regelmäßiger Funktionstest | Konfiguration für IT-Systeme KANN die Funktionsfähigkeit des Schadcodeschutzes {{ insert: param, konf.7.7-prm1 }} überprüfen. | 3cc8cb7f-eeb1-4d12-a87b-3081587e4b93 |
| KONF.7.8 | Dual-Engine-Strategie | Konfiguration für IT-Systeme KANN für die Erkennung von Schadcode unterschiedliche Scan-Engines aktivieren. | a86b7cf5-33c8-40b5-81cd-db942cc27b74 |
| KONF.7.9 | Einschränkung der Installation | Konfiguration für IT-Systeme SOLLTE die Installation von Anwendungen einschränken. | 6bb8fed8-6745-4b58-81cb-ddff66da28d9 |
| KONF.7.10 | Einschränkung der Ausführung | Konfiguration für IT-Systeme SOLLTE die Ausführung nicht autorisierter Anwendungen einschränken. | 02df7412-74de-45a2-abfd-aa8cf94ff93d |
| KONF.7.11 | Einschränkung von Softwarebibliotheken | Konfiguration für IT-Systeme KANN die Ausführung nicht autorisierter Softwarebibliotheken einschränken. | 8de44b0e-0241-4519-9dc3-e941800b4168 |
| KONF.7.12 | Einschränkung von Skripten | Konfiguration für IT-Systeme KANN die Ausführung nicht autorisierter Skripte einschränken. | f835dc6a-5af1-424d-994a-219141d268d7 |
| KONF.7.13 | Einschränkung von Systemaufrufen | Konfiguration für IT-Systeme KANN Systemaufrufe pro Anwendung einschränken. | 0d1bb274-a8e2-4fdb-a94e-25dd0565fab1 |
| KONF.7.14 | Code-Signierung im Betriebssystemkern | Konfiguration für IT-Systeme SOLLTE Code-Signierung im Betriebssystemkern aktivieren. | 276b2d5d-5317-4cc6-b106-c65c764da6f6 |
| KONF.7.15 | Lokale Firewall | Konfiguration für IT-Systeme SOLLTE ein- und ausgehende Netzverbindungen einschränken. | 73cfb678-122c-4bca-a8b0-70673e70d285 |
| KONF.7.16 | Anti-Exploit | Konfiguration für IT-Systeme SOLLTE Systemfunktionen zum Schutz des Systems vor der Ausnutzung bekannter Sicherheitslücken aktivieren. | 6056a588-6f3c-402e-a0ac-f1f169030659 |
| KONF.7.16.1 | Anti-Exploit für den Arbeitsspeicher | Konfiguration für IT-Systeme SOLLTE den Schutz des Arbeitsspeichers vor der Ausnutzung bekannter Sicherheitslücken aktivieren. | 1ce9e25d-e51a-453a-8383-ecdbac044b7a |
| KONF.8.1 | Automatische Überprüfung | Konfiguration für IT-Systeme SOLLTE das Vorliegen von Sicherheitsupdates überwachen. | b26ab0d5-9daf-41e8-9b93-b8cfc58a2c4c |
| KONF.8.1.1 | Automatische Sicherheitsupdates | Konfiguration für IT-Systeme SOLLTE Sicherheitsupdates automatisch installieren. | 9a9b1174-5e40-49a5-8c4b-599c394a8de7 |
| KONF.8.2 | Automatische Updates der Anwendung | Konfiguration für Anwendungen SOLLTE die automatische Installation von Sicherheitsupdates aktivieren. | 5a8998f1-d49f-45aa-8b08-7eafd9b17415 |
| KONF.9.1 | Speicherplatzbegrenzung | Konfiguration für IT-Systeme SOLLTE den Speicherplatz für die Nutzerumgebung einschränken. | d837fc6f-c113-445d-b8e5-021317d2ca90 |
| KONF.9.2 | Begrenzung der Rechenleistung | Konfiguration für Hostsysteme KANN die zur Verfügung stehende Rechenleistung anhand von {{ insert: param, konf.9.2-prm1 }} einschränken. | 3b0eb166-07b9-4b51-a1f5-75513b28015c |
| KONF.9.3 | Alternative Komponenten für kritische Funktionen | Konfiguration für IT-Systeme KANN alternative Komponenten für {{ insert: param, konf.9.3-prm1 }} installieren. | bd64ca41-01df-48ba-85ea-3241017cf750 |
| KONF.10.1 | Grundkonfiguration für Anwendungen | Konfiguration für Anwendungen SOLLTE eine Grundkonfiguration dokumentieren. | 23571325-0e60-4d28-96e1-ed57f794f790 |
| KONF.10.1.1 | Versionierung | Konfiguration für Anwendungen SOLLTE eine Versionierung vorheriger Konfigurationen verankern. | cb46badf-b942-4007-ab50-e941711b3c58 |
| KONF.10.2 | Kryptographische Verfahren und Protokolle in Anwendungen | Konfiguration für Anwendungen SOLLTE kryptographische Verfahren und Protokolle im Einklang mit den zugehörigen Anforderungen zum Identitäts- und Berec | 94aac721-fbe3-44d0-a0ce-55ebded001ab |
| KONF.10.3 | Änderung von Default-Zugangsdaten | Konfiguration für Anwendungen SOLLTE die Änderung von Default-Zugangsdaten ausführen. | f154f8a8-8abb-4c9c-a3d8-f2d20d6fd339 |
| KONF.10.4 | Deaktivierung nicht benötigter Anwendungsfunktionen | Konfiguration für Anwendungen SOLLTE nicht benötigte Anwendungsfunktionen deaktivieren. | 990f4798-6926-41be-b09d-ee0162c530a0 |
| KONF.10.5 | Überprüfung der Konfiguration | Konfiguration für Anwendungen SOLLTE die Übereinstimmung der tatsächlichen Konfiguration mit dem Referenzzustand {{ insert: param, konf.10.5-prm1 }} ü | 7f01dfb0-75b6-4248-a852-16ebca5f1c45 |
| KONF.10.5.1 | Automatisierte Überprüfung der Konfiguration | Konfiguration für Anwendungen KANN die Überprüfung der Konfiguration durch {{ insert: param, konf.10.5.1-prm1 }} aktivieren. | 9e53c0f8-53e0-439b-a4ce-ee321f55ac52 |
| KONF.11.1 | Authentifizierung vor dem Zugriff | Konfiguration für Anwendungen SOLLTE Zugriffe auf schützenswerte Daten im Einklang mit den zugehörigen Anforderungen zum Identitäts- und Berechtigungs | 6bcd486c-909c-424c-9f78-35ed96588a5c |
| KONF.11.1.1 | Authentifizierung von geplanten Konversationen | Konfiguration für TK-Anwendungen SOLLTE den Zugriff auf geplante Konversationen im Einklang mit den zugehörigen Anforderungen zum Identitäts- und Bere | 07493cf7-5071-4749-b58a-586016679f1e |
| KONF.11.1.2 | Authentifizierung von Netzverbindungen - clientseitig | Konfiguration für Anwendungen SOLLTE die Gegenstelle vor dem Datenaustausch im Einklang mit den zugehörigen Anforderungen zum Identitäts- und Berechti | 7bf1392f-5c43-43da-bb36-498b8a678e28 |
| KONF.11.2 | Warteraum | Konfiguration für VK-Anwendungen SOLLTE einen virtuellen Warteraum aktivieren. | 5f29ed91-b7f8-401f-8986-1ea63cf09080 |
| KONF.11.3 | Alternative Authentifizierung | Konfiguration für Anwendungen KANN ein ebenso vertrauenswürdiges, alternatives Verfahren zur Authentifizierung aktivieren. | 7d8e0d79-751c-4afe-bbe5-124004f01577 |
| KONF.11.4 | Veröffentlichung von Domain-Infomationen | Konfiguration für DNS-Server SOLLTE die Veröffentlichung von Domain-Infomationen anhand von {{ insert: param, konf.11.4-prm1 }} einschränken. | 24d7bd4d-9ae9-4871-b6da-4c5186351b46 |
| KONF.11.5 | Erraten von Zugriffslinks | Konfiguration für Webanwendungen SOLLTE das Durchprobieren von Zugriffslinks durch {{ insert: param, konf.11.5-prm1 }} blockieren. | 951aea5d-e4c2-47c8-9a21-b1d00e3d499f |
| KONF.11.6 | Einschränkung unauthentifizierter Anschlüsse | Konfiguration für TK-Anwendungen SOLLTE von unauthentifizierten Anschlüssen erreichbare Gegenstellen einschränken. | 09f3cad1-7245-42f4-a62c-e48ce193ce8a |
| KONF.11.7 | Übersicht angemeldeter Verbindungen | Konfiguration für Anwendungen KANN eine Übersicht angemeldeter Verbindungen aktivieren. | eca3e9a0-b7b5-4e74-9c3e-1108c268246e |
| KONF.11.8 | Einschränkung von Schnittstellen | Konfiguration für Anwendungen SOLLTE aktivierte Schnittstellen einschließlich denen zu anderen Anwendungen, Cloud-Funktionen oder Erweiterungen einsch | e9c7f783-cc8f-499c-b556-8748f9420459 |
| KONF.11.8.1 | Einschränkung von Zonentransfers | Konfiguration für DNS-Server SOLLTE Zonentransfers einschränken. | cf0655b0-3c6a-48a5-8f29-4445c26c3659 |
| KONF.11.8.2 | Einschränkung von TK-Verbindungen | Konfiguration für TK-Anwendungen SOLLTE unerwünschte TK-Verbindungen einschränken. | 0467042c-2497-4f56-9514-404a36a90fd0 |
| KONF.11.8.2.1 | Einschränkung der TK-Gegenstellen | Konfiguration für TK-Anwendungen SOLLTE Verbindungen mit externen Gegenstellen einschränken. | 756c0796-be3d-492d-a64e-3314f6d83805 |
| KONF.11.9 | Verschlüsselung schützenswerter Daten (at-rest) | Konfiguration für Anwendungen KANN schützenswerte Daten bei der Speicherung (at-rest) verschlüsseln. | d3e4416f-e997-4aec-a45b-eade4316d896 |
| KONF.12.1 | Eingabevalidierung | Konfiguration für Anwendungen SOLLTE die Validierung von Eingabedaten durch {{ insert: param, konf.12.1-prm1 }} aktivieren. | 4cf4ca7f-0b09-4777-83dc-5569c8e08f63 |
| KONF.12.1.1 | Zertifikatsprüfung | Konfiguration für Webbrowser SOLLTE die automatische Validierung des Zertifikates einschließlich der vollständigen Zertifikatskette aktivieren. | 0e183da9-8671-492b-ba81-f95ff6d90a26 |
| KONF.12.1.2 | Content Security Policy (CSP) | Konfiguration für Webbrowser SOLLTE aufgerufene Inhalte anhand der von der Webseite bereitgestellten Content Security Policy einschränken. | 65287ea4-9379-4088-adb0-774fb2b9ccbb |
| KONF.12.1.3 | Same-Origin-Policy | Konfiguration für Webbrowser SOLLTE aufgerufene Inhalte anhand der von der Webseite bereitgestellten Same-Origin-Policy einschränken. | faaaee02-ac74-49a0-af01-4e5659ea1053 |
| KONF.12.1.4 | Subresource Integrity-Prüfung | Konfiguration für Webbrowser SOLLTE aufgerufene Inhalte anhand der von der Webseite bereitgestellten Subresource Integrity-Prüfung einschränken. | 0e525ce3-95e3-4095-83f7-942eb6b09c50 |
| KONF.12.1.5 | HTTP Strict Transport Security (HSTS) | Konfiguration für Webbrowser SOLLTE aufgerufene Inhalte anhand der von der Webseite bereitgestellten  HTTP Strict Transport Security (HSTS) Richtlinie | 275e3b2d-5008-48ba-8d4f-72830bc8c730 |
| KONF.12.1.6 | JavaScript | Konfiguration für Webbrowser KANN JavaScript einschränken. | f66bbf9d-76ba-423f-b2e5-25cc775c16c6 |
| KONF.12.1.7 | Filtern schädlicher Webinhalte | Konfiguration für Webanwendungen SOLLTE eine Filterung schädlicher Webinhalte aktivieren. | 568f6977-4f5c-44a4-92c7-1e6e09cc3631 |
| KONF.12.1.8 | Duplikate im Verzeichnisbaum | Konfiguration für Verzeichnisdienste SOLLTE Duplikate im Verzeichnisbaum blockieren. | c9194ad7-5382-4810-a5b9-d4013a28f5a5 |
| KONF.12.1.9 | Journaling | Konfiguration für Dateiserver SOLLTE Journaling aktivieren. | 87ccf38b-ac1d-4e14-a599-b536321b0f75 |
| KONF.12.1.10 | HTTP-Response-Header | Konfiguration für Webanwendungen SOLLTE HTTP-Response-Header aktivieren. | 34bf7846-28cb-41db-bd7b-2e81bee980b3 |
| KONF.12.1.11 | Aktive Inhalte | Konfiguration für Office-Anwendungen SOLLTE Aktive Inhalte deaktivieren. | fe822942-31a1-4961-832f-3523f7622754 |
| KONF.12.2 | Verschlüsselungsstatus der aktuellen Verbindung | Konfiguration für Webbrowser SOLLTE eine Anzeige der Verschlüsselung der aktuellen Verbindung aktivieren. | 8e35ba9c-0926-4cef-bd95-ec79933a6ee2 |
| KONF.12.3 | Cookies | Konfiguration für Webbrowser SOLLTE Cookies einschränken. | 77690b80-cd45-47dd-9540-b8de5d67cbbe |
| KONF.12.4 | Speicherung von Zugangsdaten | Konfiguration für Webbrowser SOLLTE eine geschützte Speicherung von Zugangsdaten aktivieren. | 93d5129d-c905-439f-b7cf-2ddcd92fac5a |
| KONF.12.5 | Auto-Vervollständigung von Daten | Konfiguration für Webbrowser SOLLTE die Auto-Vervollständigung von Daten einschränken. | 884ebdea-7054-48bf-932a-bb4f704baa8e |
| KONF.12.6 | Browser-Historie | Konfiguration für Webbrowser KANN die dauerhafte Browser-Historie deaktivieren. | 1eb77ea1-1c97-4027-9098-a874951b0f47 |
| KONF.12.7 | Erweiterte Attribute | Konfiguration für Dateiserver SOLLTE Erweiterte Attribute aktivieren. | 7ec374a6-4efc-45a4-b596-4e8fc1402daf |
| KONF.12.8 | Teilnahme per Default ohne Bild und Ton | Konfiguration für VK-Anwendungen SOLLTE Bild und Ton per Default deaktivieren. | bbea53dc-e082-4ac7-80f7-a25e0bf04a76 |
| KONF.12.9 | Information über Aufzeichnung | Konfiguration für VK-Anwendungen SOLLTE eine Anzeige laufender Aufzeichnungen aktivieren. | 46dd3e73-e1d5-4dee-9312-d52e9bb5c631 |
| KONF.12.10 | Cookie-Attribute | Konfiguration für Webanwendungen SOLLTE Cookie-Attribute aktivieren. | 4ac2fe69-5f2d-47d8-acf7-2be1485f9f37 |
| KONF.12.11 | Anonyme oder Pseudonyme Kommunikation | Konfiguration für TK-Anwendungen KANN Anonyme oder Pseudonyme Kommunikation aktivieren. | a06eca6b-f142-4808-b04d-c19adf178db4 |
| KONF.12.12 | Verbindungsprotokoll | Konfiguration für TK-Anwendungen SOLLTE ein für Nutzende verfügbares Verbindungsprotokoll protokollieren. | 31191a30-d1fd-4adf-a407-35e4fc782e79 |
| KONF.12.13 | Sendebericht | Konfiguration für Faxe SOLLTE einen Sendebericht protokollieren. | 0ef855ab-834e-405e-99f4-a1bca3f09d15 |
| KONF.12.14 | DNS-Falschinformationen | Konfiguration für DNS-Server SOLLTE DNS-Antworten, die falsche Domain-Informationen liefern, deaktivieren. | d3856d40-5869-4b06-812b-4cc966f96d80 |
| KONF.13.1 | Filtern schädlicher Nachrichten | Konfiguration für Interpersonelle Kommunikation SOLLTE eine Filterung schädlicher Nachrichteninhalte aktivieren. | 0571ae85-f5f8-485c-b3d7-44f8ddfa2d58 |
| KONF.13.1.1 | SPAM-Filter | Konfiguration für Interpersonelle Kommunikation SOLLTE die Zustellung unerwünschter Nachrichten blockieren. | ee57e250-bed1-484e-9ff7-8b7750562877 |
| KONF.13.1.2 | Interpretation aktiver Inhalte | Konfiguration für Interpersonelle Kommunikation SOLLTE die automatische Interpretation aktiver Inhalte deaktivieren. | ecc5b98d-eb77-4902-a01a-a5348ecba8f0 |
| KONF.13.2 | Authentizität von Nachrichten | Konfiguration für Interpersonelle Kommunikation SOLLTE eine automatische Verifikation der Authentizität von Nachrichten aktivieren. | 04eaf9de-736e-4dfc-898e-04dc85fa36f0 |
| KONF.13.2.1 | Verifikation der Sendeberechtigung | Konfiguration für E-Mail SOLLTE eine automatische Verifikation der Sendeberechtigung aktivieren. | c163be1f-8236-439c-a1d1-34fa7472c06a |
| KONF.13.2.2 | Verifikation der Serversignatur | Konfiguration für E-Mail SOLLTE die Serversignatur eingehender E-Mails automatisch authentifizieren. | 2e782128-57ea-4573-a44e-5538d0dd1240 |
| KONF.13.3 | Kryptographische Signatur des Mailservers | Konfiguration für E-Mail SOLLTE die Kryptographische Signatur des Mailservers aktivieren. | 0588d640-bda0-46d7-978e-6c742f098327 |
| KONF.13.4 | Kryptographische Signatur durch Nutzende | Konfiguration für E-Mail KANN die kryptographische Signatur durch Nutzende aktivieren. | 8cda47f9-692a-485d-bc73-a4c3b691c501 |
| KONF.13.5 | Publikation der Sendeberechtigung | Konfiguration für E-Mail SOLLTE die Publikation der eigenen Sendeberechtigung im DNS aktivieren. | 4eedf96c-42cf-4d3e-902f-f3efce1f533a |
| KONF.13.5.1 | Strenge Senderpolicy | Konfiguration für E-Mail SOLLTE eine strenge Senderpolicy aktivieren. | b44ec8f5-20f7-43ad-94a6-545a12cc7a67 |
| KONF.13.6 | Publikation der Serversignatur | Konfiguration für E-Mail SOLLTE die Publikation der Serversignatur im DNS aktivieren. | faf3fea5-b891-4d47-a2f7-74756b02a668 |
| KONF.13.7 | TLS-Reports | Konfiguration für E-Mail KANN TLS-Reports {{ insert: param, konf.13.7-prm1 }} überprüfen. | becbeefc-417d-42e4-b2a0-7a296c23fa9c |
| KONF.13.8 | DMARC-Reports | Konfiguration für E-Mail KANN DMARC-Reports {{ insert: param, konf.13.8-prm1 }} überprüfen. | 96dd928d-e5ac-47ec-a2a2-320ae0359e73 |
| KONF.13.9 | Publikation der DMARC-Richtlinie | Konfiguration für E-Mail SOLLTE die Publikation der DMARC-Richtlinie aktivieren. | b4f12703-f0d8-400d-a979-933d7e29a833 |
| KONF.13.10 | Authentifizierung der Server-Zertifikate über DNS | Konfiguration für E-Mail SOLLTE die Authentifizierung der Server-Zertifikate über das DNS aktivieren. | ee341e2a-290d-4d5f-bf24-c95a265395f6 |
| KONF.13.11 | MTA-STS | Konfiguration für E-Mail SOLLTE MTA-STS aktivieren. | 19e81bd5-20d6-41af-b172-5a3859738a62 |
| KONF.14.1 | Verschlüsselung beim Transport | Konfiguration für Anwendungen SOLLTE Kommunikation beim Transport über Netze nach {{ insert: param, konf.14.1-prm1 }} verschlüsseln. | 99806244-514d-43e2-be34-4ac7ab0517ad |
| KONF.14.1.1 | Obligatorische Verschlüsselung | Konfiguration für Anwendungen SOLLTE unverschlüsselte und anfällige Verbindungen über Netze deaktivieren. | b73c400e-b4f8-494c-ac02-619258f77a2d |
| KONF.14.1.2 | Ende-zu-Ende-Verschlüsselung | Konfiguration für Anwendungen KANN die Kommunikation Ende-zu-Ende über Netze verschlüsseln. | 3e17d0bd-cdec-4d89-b6a6-b2e018009e8f |
| KONF.14.2 | Source Port Randomisierung | Konfiguration für DNS-Server SOLLTE Source Port Randomisierung aktivieren. | 8cf919ad-46cd-4173-9def-7b84abd6f278 |
| KONF.14.3 | Iterative Beantwortung | Konfiguration für DNS-Server SOLLTE die iterative Beantwortung von DNS-Anfragen aus dem Internet aktivieren. | 57cb3f3e-bb54-444c-a337-8f098ae085a2 |
| KONF.14.4 | Caching | Konfiguration für Anwendungen von Endgeräten KANN eine Zwischenspeicherung häufig verwendeter Daten aktivieren. | f6f85541-a8ed-46ec-a1f7-ea0281519866 |
| KONF.14.5 | Zeitüberschreitung von Netzverbindungen | Konfiguration für Anwendungen SOLLTE Netzverbindungen bei Zeitüberschreitung blockieren. | 76f6f959-2505-43b4-9e22-3501e32bc0be |
| KONF.15.1 | Begrenzung des Speicherplatzes | Konfiguration für Anwendungen von Hostsystemen KANN in der Anwendung zur Verfügung stehenden Speicherplatz pro {{ insert: param, konf.15.1-prm1 }} anh | 15596e08-6978-4e61-bf6c-63e24575788f |
| KONF.15.2 | Begrenzung der Rechenleistung | Konfiguration für Anwendungen von Hostsystemen KANN die Rechenleistung einschränken. | 62f53764-d215-4e55-9ad1-7790922620af |
| KONF.15.3 | Denial of Service | Konfiguration für Anwendungen von Hostsystemen KANN Schutzmaßnahmen gegen Denial of Service aktivieren. | 51947077-3600-48fc-83b0-5d5ff343d706 |
| KONF.15.4 | Überbuchung von virtualisierten Ressourcen | Konfiguration für Virtualisierungslösungen KANN die Überbuchung von virtualisierten Ressourcen deaktivieren. | 6cf041a5-163d-4faa-b817-42b35ad681c2 |
| DLS.2.1 | Mehr-Faktor-Authentifizierung | Dienstleistersteuerung für Dienstleistungen SOLLTE Mehr-Faktor-Authentifizierung bei Login in Online-Dienste aktivieren. | 8bbca369-db4c-421d-b930-f4257acc1b83 |
| DLS.2.2 | Transportverschlüsselung | Dienstleistersteuerung für Daten SOLLTE den Transport bei der Übertragung zum Anbieter nach {{ insert: param, dls.2.2-prm1 }} verschlüsseln. | c9cd4b7e-8f76-4884-afb7-dcfd3d228624 |
| DLS.2.3 | Vollverschlüsselung | Dienstleistersteuerung für Daten KANN diese, wenn der Anbieter deren Inhalt zur Vertragserbringung nicht kennen muss, für diesen nicht entschlüsselbar | 30a1e505-c2a4-44d9-8c8e-6584142d5d64 |
| DLS.3.1 | Einhaltung der Sicherheitsvorgaben | Dienstleistersteuerung für Dienstleistungen SOLLTE die Einhaltung der Sicherheitsvorgaben durch den Dienstleister {{ insert: param, dls.3.1-prm1 }} üb | 5b17bd9b-ff38-46eb-a1ef-7b38429f128b |
| DLS.3.1.1 | Audit oder Zertifikat | Dienstleistersteuerung für Outsourcing SOLLTE die Einhaltung der Sicherheitsvorgaben anhand eines {{ insert: param, dls.3.1.1-prm1 }} {{ insert: param | 12c2c250-86b8-46a0-bccd-d0b2f59b6bae |
| DLS.3.2 | Checkup | Dienstleistersteuerung für Outsourcing KANN die risikoorientierte Entscheidung über Outsourcing auf Grundlage der Geschäftsprozessprofile auf Änderung | ca07f3db-7a2f-4156-b1de-4fa648393557 |
| DLS.3.3 | Strategie-Check | Dienstleistersteuerung für Outsourcing KANN die Strategie auf Vollständigkeit und Korrektheit in Bezug auf die betrachteten Geschäftsprozesse bei Ände | cc89b4a1-02a9-48b6-aac9-2b6c2e0d7062 |
| DLS.3.4 | Anhörung | Dienstleistersteuerung für Outsourcing SOLLTE den Dienstleister zu Sicherheitsmaßnahmen für betroffene Zielobjekte anhören. | a36c3091-9132-49dc-9186-d335cb153360 |
| DLS.3.6 | Portabilität | Dienstleistersteuerung für Outsourcing KANN die Portabilität des ausgelagerten Prozesses {{ insert: param, dls.3.6-prm1 }} überprüfen. | 2563b59c-b3da-4bdd-99cd-3eedb94c0abb |
| DLS.4.1 | Dekomissionierung | Dienstleistersteuerung für Dienstleistungen SOLLTE eine Vorgehensweise zur Dekommissionierung vor Vertragsende verankern. | a78062a0-7fff-43a7-906a-6db806cf6822 |
| DLS.4.1.1 | Unabhängigkeit | Dienstleistersteuerung für Outsourcing SOLLTE die Unabhängigkeit der Verarbeitung schützenswerter Informationen vor der Außerbetriebnahme testen. | d37125e2-68cd-4e75-9da9-d4af0b4dd051 |
| DLS.4.1.2 | Berechtigungen deaktivieren | Dienstleistersteuerung für Dienstleistungen SOLLTE für den Vertrag benötigte Berechtigungen bei Vertragsende unverzüglich deaktivieren. | 3449b68e-a78f-4090-9092-6e1a65dd7c2a |
| GEB.1.3 | Autorisierung von Standorten | Gebäudemanagement für Standorte SOLLTE Standorte für die Stationierung von Assets autorisieren. | b25c2cfd-431c-4996-9041-47ae0e516432 |
| GEB.1.3.1 | Abnahme von Standorten | Gebäudemanagement für Standorte SOLLTE Standorte vor Autorisierung anhand von {{ insert: param, geb.1.3.1-prm1 }} testen. | 127de8f4-d265-4b66-83a1-a9d2c5113a17 |
| GEB.1.4 | Exponierte Bereiche | Gebäudemanagement für Standorte SOLLTE schützenswerte Assets oder zugehörige Infrastrukturen nur außerhalb exponierter oder besonders gefährdeter Bere | d5806bcc-a072-4a2e-8fd1-2ff0d30e96d6 |
| GEB.1.5 | Strukturpläne | Gebäudemanagement für Standorte SOLLTE Strukturpläne dokumentieren. | e51b3488-c9ce-4709-b2d1-c995eee3336a |
| GEB.2.1 | Installation von Perimetern | Gebäudemanagement für Standorte SOLLTE Sicherheitsperimeter installieren. | b801be80-6655-485d-bba9-3f1ca8953755 |
| GEB.2.2 | Dokumentation öffentlicher Bereiche | Gebäudemanagement für Gebäude SOLLTE Bereiche, die ohne Authentifizierung zugänglich sind, mit Begründung dokumentieren. | 1147b820-ea85-4137-aad4-d7a5462baaaa |
| GEB.2.3 | Erkundung aus dem öffentlichen Raum | Gebäudemanagement für Standorte SOLLTE Hör- und Sehschutz gegen den öffentlichen Raum testen. | 11a3fb3c-b21e-4d11-b9d1-11ad23cea2b1 |
| GEB.2.4 | Elektromagnetische Abschirmung | Gebäudemanagement für Standorte KANN die Elektromagnetische Abschirmung testen. | 9835ce0d-94a4-4acc-96cf-489f20750808 |
| GEB.3.1 | Überwachung von Zutrittspunkten | Gebäudemanagement für Standorte SOLLTE Zutrittspunkte auf unbefugte Zutritte überwachen. | 0fcd1c71-d16d-4531-94f0-6023bf19b3e9 |
| GEB.3.1.1 | Videoüberwachung | Gebäudemanagement für Standorte KANN Zutritte per Video überwachen. | 842a359b-f8fe-4c81-82e3-50d949dc4bbd |
| GEB.3.1.2 | Überprüfung mitgeführter Gegenstände | Gebäudemanagement für Standorte KANN das Mitführen von Gegenständen überwachen. | 012da5ef-7ee9-4bf2-bb39-eebd2ae7b17b |
| GEB.3.2 | Anmelde- und Empfangsbereiche | Gebäudemanagement für Standorte SOLLTE Anmelde- und Empfangsbereiche installieren. | 46bec5e4-88b9-45d1-ae2a-56b534ad94ad |
| GEB.3.3 | Authentifizierung vor Zutritt | Gebäudemanagement für Standorte SOLLTE Zutritte im Einklang mit den Festlegungen des Identitäts- und Berechtigungsmanagements authentifizieren. | 5ac8362d-3e6b-4922-8e12-66a80d8d883b |
| GEB.3.3.1 | Zugangskontrollanlage | Gebäudemanagement für Standorte KANN Zutritte automatisch im Einklang mit den Festlegungen des Identitäts- und Berechtigungsmanagements authentifizier | 5bc938de-7123-4793-8ba4-3183c2264acf |
| GEB.3.3.2 | Dokumentation von Zutritten | Gebäudemanagement für Standorte KANN Zutritte und Austritte mit Identität und Zeitpunkt dokumentieren. | a0b89dd6-4aec-41bd-b4bf-01e704072ed5 |
| GEB.3.3.3 | Besucheranmeldung | Gebäudemanagement für Standorte SOLLTE Besuche autorisieren. | ce537201-8949-41a6-855b-c7671d226853 |
| GEB.3.4 | Berechtigungsmarkierung | Gebäudemanagement für Nutzende von Standorten KANN zum Tragen von gut sichtbaren Berechtigungsmarkierungen innerhalb des Sicherheitsperimeters anweise | 63985f87-b50e-4c73-9962-f026b5e6d840 |
| GEB.3.5 | Einbruchhemmung | Gebäudemanagement für Standorte KANN einbruchhemmende Bauteile nach {{ insert: param, geb.3.5-prm1 }} installieren. | 02f648cd-8aec-4bfb-b751-dab8974d874c |
| GEB.3.6 | Einbruchmeldeanlagen | Gebäudemanagement für Standorte KANN Einbrüche nach {{ insert: param, geb.3.6-prm1 }} überwachen. | 01193c74-a4fc-4669-816c-651fcdca362e |
| GEB.3.7 | Kontrolle der Zutrittskontrolle | Gebäudemanagement für Standorte SOLLTE die angewendeten Zutrittskontrollmaßnahmen {{ insert: param, geb.3.7-prm1 }} überprüfen. | 407e3436-9719-4c45-a009-183c7818d376 |
| GEB.4.1 | Klimatisierung | Gebäudemanagement für Standorte SOLLTE eine ausreichende Klimatisierung von Räumlichkeiten anhand von {{ insert: param, geb.4.1-prm1 }} installieren. | dfdda615-4afc-4889-b7a0-95c91240add7 |
| GEB.4.1.1 | Luftstrom-Analyse | Gebäudemanagement für Serverräume KANN den Klimatisierungsbedarf anhand einer Luftstrom-Analyse {{ insert: param, geb.4.1.1-prm1 }} überprüfen. | 0abf44e0-ee1c-46fc-a106-fa58b1f5f245 |
| GEB.4.1.2 | Klimamessung | Gebäudemanagement für Serverräume SOLLTE Lufttemperatur und Luftfeuchtigkeit anhand von {{ insert: param, geb.4.1.2-prm1 }} überwachen. | 338031dd-f3c6-4245-b411-7c46852edfcb |
| GEB.4.1.3 | Redundante Klimatisierung | Gebäudemanagement für Standorte KANN redundante Klimasysteme installieren. | ab66de05-230a-46cf-9beb-29368a3768e2 |
| GEB.5.1 | Einrichtung | Gebäudemanagement für Standorte KANN geschlossene Sicherheitsbereiche installieren. | b545c003-c5ea-4d18-bcf5-d5651f9eba7c |
| GEB.5.2 | Gesonderte Autorisierung | Gebäudemanagement für Standorte KANN die Zutrittsberechtigung zu diesem Sicherheitsbereich durch {{ insert: param, geb.5.2-prm1 }} autorisieren. | 94d3b9c2-9040-4bb6-9153-54d5c488a085 |
| GEB.5.3 | Schleusen | Gebäudemanagement für Standorte KANN Schleusen an Zugangspunkten installieren. | b524ac99-b28f-486c-8269-3e589f21cc2d |
| GEB.5.4 | Vereinzelungsanlage | Gebäudemanagement für Standorte KANN Vereinzelungsanlagen an Zugangspunkten installieren. | b1e5f020-7243-4c70-b21a-85f55b68353c |
| GEB.6.1 | Clean Desk | Gebäudemanagement für Räume SOLLTE zum Aufräumen von vertraulichen Dokumenten und Datenträgern vor dem Verlassen des Arbeitsplatzes anweisen. | b5fcf9c6-b6e5-4018-bb9b-64344a2e0a4e |
| GEB.6.2 | Screen Lock | Gebäudemanagement für Räume SOLLTE zum Sperren von IT-System vor dem Verlassen des Arbeitsplatzes anweisen. | 56f4e238-cbce-4353-b4a8-bc3ee1c665c5 |
| GEB.6.3 | Lieferzugang | Gebäudemanagement für Standorte SOLLTE einen Zugang für die Abwicklung von Lieferungen ohne unbefugten Zugang zum restlichen Standort installieren. | bf559e67-d53f-4ef3-928b-5d9774e7b87c |
| GEB.6.4 | Schutz gegen Manipulation | Gebäudemanagement für IT-Systeme KANN Manipulationsschutzvorkehrungen installieren. | 59810143-17bf-49b6-91d0-1266cb7eb9da |
| GEB.6.5 | Mikrosegmentierung | Gebäudemanagement für IT-Systeme KANN eine physische Mikrosegmentierung installieren. | ae6ec98f-fe6f-4334-904c-9f17235c45e5 |
| GEB.7.1 | Zugang zu Ausgabesystemen | Gebäudemanagement für IT-Systeme SOLLTE den Zugang zu nicht-öffentlichen Ausgabesystemen einschränken. | 9c8e26af-7fd2-4a30-ac89-232a0bc418a1 |
| GEB.7.2 | Geschützte Aufstellung | Gebäudemanagement für IT-Systeme SOLLTE diese geschützt vor dem Zugriff von Unbefugten platzieren. | 4bd461c1-265d-4823-8b2c-4c435af0943a |
| GEB.7.2.1 | Hostsysteme | Gebäudemanagement für Hostsysteme SOLLTE diese ausschließlich in Serverräumen platzieren. | 25dfb04d-3274-446e-9bb0-f2fb1a2e511a |
| GEB.7.3 | Netzkomponenten | Gebäudemanagement für Netze SOLLTE für die Funktionsfähigkeit des Netzes erforderliche Systeme ausschließlich in Räumen für technische Infrastruktur p | 525d2727-f932-4f27-bffc-7a8104194bc8 |
| GEB.7.4 | Normgerechte Rechenzentren | Gebäudemanagement für Serverräume KANN diese ausschließlich in normgerechten Rechenzentren platzieren. | 280b1dd1-f839-473f-8e71-3cd871fc55b1 |
| GEB.8.1 | Schlüsselbeauftragte | Gebäudemanagement für Standorte SOLLTE die Verwaltung von Schlüsseln {{ insert: param, geb.8.1-prm1 }} zuweisen. | 989b0846-7561-4d14-99d0-ce46a749cde0 |
| GEB.8.2 | Verwahrung von Schlüsseln | Gebäudemanagement für Standorte SOLLTE zur Verwahrung von Schlüsseln anweisen. | b4af7248-ff08-4cb7-99b5-cd5f589ec1df |
| GEB.8.3 | Schlüsselaudit | Gebäudemanagement für Standorte SOLLTE die vorhandenen Schlüssel {{ insert: param, geb.8.3-prm1 }} überprüfen. | 97d89e25-dbe3-4da7-bcfb-07537a05d6bf |
| GEB.9.1 | Gesonderte Aufbewahrung | Gebäudemanagement für Standorte SOLLTE geschäftskritische Speichermedien in verschließbaren Schutzeinrichtungen platzieren. | fa8a00b9-9190-44f2-875a-68024ff491bd |
| GEB.9.1.1 | Archiv | Gebäudemanagement für Standorte KANN geschäftskritische Speichermedien in Datenträgerarchiven platzieren. | 59be69ee-346c-4a89-b93d-558cfd50f57f |
| GEB.9.2 | Staub und Schmutz | Gebäudemanagement für Datenträgerarchiv KANN Maßnahmen zum Schutz der Datenträger vor Staub und Schmutz verankern. | 219884d2-ef52-4103-bd5f-b5d76bab03d7 |
| GEB.9.3 | Schutz der Datenträger vor Brandschäden | Gebäudemanagement für Standorte KANN feuerfeste Behältnisse nach {{ insert: param, geb.9.3-prm1 }} installieren. | 7fa6a340-5f12-41a3-b9df-a44dfcc6e0be |
| GEB.9.4 | Überwachung schonender Klimatisierung | Gebäudemanagement für Datenträgerarchiv KANN für die Datenträger schonende Temperatur und Luftfeuchtigkeit anhand von {{ insert: param, geb.9.4-prm1 } | b76d96fa-3c33-470e-a624-1fe1aff44cc9 |
| GEB.10.1 | Normgerechte Stromversorgung | Gebäudemanagement für Standorte SOLLTE eine norm- und bedarfsgerechte Stromversorgung und -verkabelung installieren. | 30ed7bd0-4d41-4bc3-880d-cc0e66fd592e |
| GEB.10.1.1 | Vorausschauende Lastanalyse | Gebäudemanagement für Standorte KANN die bedarfsgerechte Stromversorgung {{ insert: param, geb.10.1.1-prm1 }} vorausschauend überprüfen. | a73bc9c8-bd58-4816-9e18-d41e94c20341 |
| GEB.10.1.2 | Dedizierte Elektrounterverteilung | Gebäudemanagement für Standorte KANN eine ausschließlich für diesen Standort bestimmte Elektrounterverteilung die direkt von der Niederspannungshauptv | 59df8c81-694d-4612-a439-63deaee5c4d9 |
| GEB.10.1.3 | Redundante Stromversorgung | Gebäudemanagement für Standorte KANN eine redundante Stromversorgung für {{ insert: param, geb.10.1.3-prm1 }} installieren. | eeaa8977-05e5-4eaa-a5b7-ea490eb543cd |
| GEB.10.1.4 | Langanhaltende Sekundärversorgung | Gebäudemanagement für Standorte KANN eine redundante Stromversorgung für {{ insert: param, geb.10.1.4-prm1 }} installieren. | 9de758ff-88f1-4350-b937-354a5e4e5fc5 |
| GEB.10.2 | Lasttest | Gebäudemanagement für Standorte KANN die Belastbarkeit der Stromversorgung {{ insert: param, geb.10.2-prm1 }} überprüfen. | 56b79b13-09ed-4d7a-adea-bc8cb2cf97dd |
| GEB.10.3 | Notaus | Gebäudemanagement für Standorte KANN eine Notausschaltung für die Versorgungseinrichtungen installieren. | 1520f194-770f-4da5-9ac8-1094105e2d80 |
| GEB.10.4 | Überspannungsschutz | Gebäudemanagement für Standorte KANN Überspannungsschutzeinrichtungen installieren. | dc956422-730a-46c3-987b-3f2cb5ea22f3 |
| GEB.10.5 | Strukturierte Datenverkabelung | Gebäudemanagement für Standorte SOLLTE eine norm- und bedarfsgerechte Datenverkabelung installieren. | 3324eb2a-6548-46c1-9d15-96192fdae5a9 |
| GEB.10.5.1 | Physisch geschützte Verlegung | Gebäudemanagement für Standorte SOLLTE eine geschützte Kabelverlegung installieren. | 71c569f6-99e4-4fd4-8648-84b9c8a0539e |
| GEB.10.6 | Zugang zu Räumen für technische Infrastruktur | Gebäudemanagement für Räume für technische Infrastruktur SOLLTE den Zugang zu Räumen für technische Infrastruktur auf {{ insert: param, geb.10.6-prm1  | 7260f1aa-7b3b-42aa-a4f2-c85bd8047a4b |
| GEB.10.7 | Zweckentfremdung | Gebäudemanagement für Räume für technische Infrastruktur SOLLTE die Verwendung der Räume zu anderen Zwecken untersagen. | efa82caa-8318-4679-a865-48cc380ac9d2 |
| GEB.11.1 | Brandschutz | Gebäudemanagement für Standorte SOLLTE Brandschutz nach den entsprechenden Normen verankern. | 56c85ba9-d534-4b2a-b895-06b24de6ab92 |
| GEB.11.1.1 | Baulicher Brandschutz | Gebäudemanagement für Räume SOLLTE bauliche Brandschutzeinrichtungen nach den entsprechenden Normen installieren. | d2545c9e-2476-4841-a9a6-dafa9b471f1b |
| GEB.11.1.2 | Brandabschnitte | Gebäudemanagement für Räume SOLLTE Brandabschnitte nach den entsprechenden Normen installieren. | 9bba280a-5874-46eb-bbc5-4696d3ee5ed6 |
| GEB.11.1.3 | Rauchdichtheit | Gebäudemanagement für Räume KANN alle raumbildende Teile rauchdicht installieren. | 1cccb05d-47e6-431e-8668-c70be6ec17c6 |
| GEB.11.1.4 | Brandwiderstandsklassen | Gebäudemanagement für Räume KANN feuerfeste Materialen für alle raumbildenden Teile , sodass sie Feuern für {{ insert: param, geb.11.1.4-prm1 }} stand | 4411c989-a51f-4aa9-8d79-e0b3fd492fb9 |
| GEB.11.1.5 | Vermeidung von Brandlasten | Gebäudemanagement für Standorte SOLLTE das ungesicherte Hinterlassen von Brandlasten untersagen. | 3c49b485-9113-4009-a2dc-598c9d9a3f5f |
| GEB.11.1.6 | Brandmeldeanlagen | Gebäudemanagement für Standorte SOLLTE das Entstehen von Bränden überwachen. | 92dfd98d-40ed-4854-a3d8-00a84fe77cec |
| GEB.11.1.7 | Brandunterdrückung | Gebäudemanagement für Serverräume KANN Brandunterdrückungssysteme installieren. | 7520aa89-9296-4ae3-a60d-5c781dd06732 |
| GEB.11.1.8 | Brandschutzprüfung | Gebäudemanagement für Standorte SOLLTE die Wirksamkeit der Brandschutzmaßnahmen {{ insert: param, geb.11.1.8-prm1 }} überprüfen. | 3b904a6b-c440-4360-ab4a-37b76fc639a7 |
| GEB.11.2 | Wasserschutz | Gebäudemanagement für Standorte SOLLTE zwischen Assets und Witterungs- sowie Wassergefahrenstellen mindestens eine physische Schutzmaßnahme vor Wasser | 6f00e3ab-1053-42c0-8c40-0a9d79b0656d |
| GEB.11.2.1 | Doppelter baulicher Wasserschutz | Gebäudemanagement für Standorte KANN zwischen Wassergefahrenstellen und Assets mindestens zwei bauliche Schutzmaßnahmen vor Wasser nach den entspreche | 6b169c24-0f22-4ef3-bfe5-3a95e49e4131 |
| GEB.11.2.2 | Leckagesensor | Gebäudemanagement für Standorte KANN Wassereinbrüche überwachen. | a7d0e63e-e589-4587-bf0b-043e36515dac |
| GEB.11.3 | Blitzschutzeinrichtungen | Gebäudemanagement für Standorte SOLLTE Blitzschutzeinrichtungen nach {{ insert: param, geb.11.3-prm1 }} installieren. | 3a8c199a-408d-4ac6-9355-b850d4f5188a |
| GEB.11.3.1 | Niederohmigkeit | Gebäudemanagement für Standorte KANN Blitzschutzeinrichtungen {{ insert: param, geb.11.3.1-prm1 }}  auf Niederohmigkeit überprüfen. | a70149a9-75af-4784-8011-e1433c72dcfc |
| GEB.11.4 | Ableitfähiger Fußbodenbelag | Gebäudemanagement für Räume für technische Infrastruktur KANN im Nahfeld von Systemen einen ableitfähigen Fußbodenbelag installieren. | face1ab3-e01f-41eb-8870-f2020a5640bc |
| BER.3.5 | Privilegierte Zugangskonten | Berechtigung für Administrierende SOLLTE separate Zugangskonten für administrative Tätigkeiten (Administrationskonten) verankern. | 4791c533-f811-48cf-9957-6e1d438028f5 |
| BER.3.6 | Single-Sign-On | Berechtigung für Anwendungen SOLLTE die Anmeldung über einen zentralen Identitätsprovider aktivieren. | 494391e7-774c-4cc4-b9ed-dc8ab652e83b |
| BER.3.8 | Anmeldeversuchsgrenze am System | Berechtigung für IT-Systeme SOLLTE weitere Anmeldeversuche nach Erreichen von {{ insert: param, ber.3.8-prm1 }} fehlgeschlagenen Versuchen vorübergehe | c37f30d1-8fd7-4497-b3f1-07d8f54b717c |
| BER.3.9 | Anmeldeversuchsgrenze an der Anwendung | Berechtigung für Anwendungen SOLLTE weitere Anmeldeversuche nach Erreichen von einem maximalen Schwellwert an fehlgeschlagenen Versuchen vorübergehend | 265ee5bc-059a-4bde-b480-9bc1611171bf |
| BER.3.10 | Systemsperre bei Inaktivität | Berechtigung für IT-Systeme SOLLTE eine Sperre bei Inaktivität nach {{ insert: param, ber.3.10-prm1 }} aktivieren. | de11e8f3-d1fa-4b11-a6b0-e0d327b42849 |
| BER.3.11 | Sperre der Anwendung bei Inaktivität | Berechtigung für Anwendungen SOLLTE eine Sperre bei Inaktivität nach {{ insert: param, ber.3.11-prm1 }} aktivieren. | 5c8bb88d-6692-4904-908a-ed3f7a81b34e |
| BER.3.17 | Zwischenspeicherung von Zugangsdaten | Berechtigung für IT-Systeme SOLLTE die Zwischenspeicherung der Zugangsdaten von Nutzern deaktivieren. | 13d83a70-bce9-4027-8d4b-d16ee051cfd5 |
| BER.3.18 | Dienstekonten | Berechtigung für Hostsysteme SOLLTE eine automatische Verwaltung der Zugangsdaten von Dienste-Konten aktivieren. | 403fac1f-a78a-4548-858e-a06168253dea |
| BER.3.20 | Notfallzugang Verzeichnisdienst | Berechtigung für Verzeichnisdienste SOLLTE ein Notfallzugangskonto installieren. | 7cd7ca02-458d-4348-ae2f-0b096d4078e3 |
| BER.4.5 | Systemfunktionen ohne Authentifizierung | Berechtigung für IT-Systeme SOLLTE Funktionen, auf die ohne vorherige Authentifizierung zugegriffen werden kann, dokumentieren. | bf5b5f6a-f525-45fc-b5a5-62379b3e6b2f |
| BER.4.6 | Anwendungsfunktionen ohne Authentifizierung | Berechtigung für Anwendungen SOLLTE Funktionen, auf die ohne vorherige Authentifizierung zugegriffen werden kann, dokumentieren. | 383f3a5e-d627-46aa-960f-4e8c5c9c9592 |
| BER.4.7 | IT-System-Zugangskonto | Berechtigung für IT-Systeme KANN diese genau einem Zugangskonto zuweisen. | 7057a1f6-0804-49ac-9d7f-289ecc71fa33 |
| BER.5.3 | Mehr-Faktor-Authentisierung am Perimeter | Berechtigung für Anwendungen von Externe Netzanschlüssen SOLLTE Mehr-Faktor-Authentisierung aktivieren. | 2b9ddd3e-5233-46f5-abca-1793b89e2809 |
| BER.5.5 | Blockieren von Passwort Recycling | Berechtigung für Nutzende SOLLTE die Wiederverwendung von Passwörtern blockieren. | d7c76736-0c1d-4693-92d5-894a8b740204 |
| BER.6.2 | Passwortmanager | Berechtigung für Nutzende SOLLTE einen Passwortmanager installieren. | c1cfa733-340c-497d-a3b6-8480d78e1278 |
| BER.6.4 | Hinweise bei Anmeldefehlern | Berechtigung für Anwendungen SOLLTE Hinweise darauf, ob ein Zugangskonto existiert bei erfolglosen Anmeldeversuchen deaktivieren. | dd5fcc0c-d602-4d15-839c-5adb4fef150e |
| DET.3.1.2 | Datenverarbeitungen | Detektion für Daten KANN die Verarbeitung von Daten protokollieren. | ca3be46d-c9ce-45b0-8da9-e4f83f123e6d |
| DET.3.1.3 | Authentifizierungen | Detektion für IT-Systeme SOLLTE Authentifizierungen bei Erfolg und Fehlschlag protokollieren. | c25354d3-ed8f-4bac-ad0c-f0641d1b7f84 |
| DET.3.1.4 | Privilegierte Ereignisse | Detektion für Anwendungen SOLLTE privilegierte Ereignisse einschließlich der Aktivierung, Deaktivierung oder Blockierung privilegierter Funktionen pro | e7d500ff-393c-4c14-baed-c87b676efe5c |
| DET.3.1.5 | Ausgeführte Kommandozeilenbefehle | Detektion für IT-Systeme SOLLTE ausgeführte Kommandozeilenbefehle protokollieren. | cd3be1eb-6b18-4e69-98c5-a584e7daa9f2 |
| DET.3.1.6 | Anbindung von Peripheriegeräten | Detektion für IT-Systeme SOLLTE das Anschließen von Peripheriegeräten protokollieren. | b0d1ef63-3c21-4d01-a5ad-82c23f113994 |
| DET.3.1.7 | Systemfehler | Detektion für IT-Systeme SOLLTE Fehlermeldungen des Systems protokollieren. | f04839ae-7df6-4518-a726-994a329e910a |
| DET.3.1.8 | Störungen der Netzerreichbarkeit | Detektion für IT-Systeme KANN Störungen der Netzerreichbarkeit protokollieren. | 39faab52-c5ca-4971-8f00-6eb34319cb55 |
| DET.3.1.9 | Systemspezifische Ereignisse | Detektion für IT-Systeme KANN {{ insert: param, det.3.1.9-prm1 }} protokollieren. | 42287f3d-c1ce-4109-bda1-87d1fd892993 |
| DET.3.1.10 | Fehler der Anwendung | Detektion für Anwendungen SOLLTE Fehlermeldungen der Anwendung protokollieren. | 8a99b098-7642-4fec-996c-cbe94e7f88e6 |
| DET.3.1.11 | Nutzungsstatistik | Detektion für Anwendungen KANN eine Nutzungsstatistik protokollieren. | bcc48221-ad2b-4989-a754-23a167a08176 |
| DET.3.1.12 | Anwendungsspezifische Ereignisse | Detektion für Anwendungen KANN {{ insert: param, det.3.1.12-prm1 }} protokollieren. | 80fa36d5-71d4-4a2e-9795-54cedffa44ae |
| DET.3.1.13 | Integration von Cloud-Diensten | Detektion für Cloud-Dienste KANN Ereignisse in der Cloud im Audit Log der Institution protokollieren. | 681494bd-8d1d-4b34-84f6-abab2f4ea751 |
| DET.3.5 | Unbestreitbarkeit | Detektion für Daten KANN Nachweise für den Zusammenhang {{ insert: param, det.3.5-prm1 }} mit {{ insert: param, det.3.5-prm2 }} dokumentieren. | 1d98ecfc-cf7a-4cf5-a108-169802a7b364 |
| DET.4.2 | Automatische Angriffserkennung | Detektion für IT-Systeme SOLLTE diese auf Anzeichen für Angriffe durch {{ insert: param, det.4.2-prm1 }} überwachen. | d1691e68-55a6-4b71-8d55-08a10eaeb4a5 |
| DET.4.5 | Anomale Nutzung der Anwendung | Detektion für Anwendungen KANN die Nutzung der Anwendung auf Anomalien überwachen. | e0194ca3-39a2-4c07-9e7e-c4aad16597c6 |
| DET.4.5.1 | Verhaltensanalyse von Zugangskonten | Detektion für Verzeichnisdienste KANN das Verhalten von Zugangskonten überwachen. | cd3e1fde-3095-4518-b906-ca18824839b8 |
| DET.4.6 | Auslaufen von Domains | Detektion für Webserver KANN das Auslaufen von Domains überwachen. | 631793e6-cc3f-49cf-a6aa-f7672688f007 |
| DET.4.7 | Ausstellung neuer HTTPS-Zertifikate | Detektion für Webserver KANN die rechtzeitige Ausstellung neuer HTTPS-Zertifikate für Server, die im Internet erreichbar sind, überwachen. | 25f3ecb6-15f9-483f-a195-a976e36e89b8 |
| DET.4.8 | Manipulations-Checkup | Detektion für IT-Systeme KANN das System auf Manipulationsversuche {{ insert: param, det.4.8-prm1 }} überprüfen. | 77b66ddb-2066-47f6-b6f7-b5b447287b59 |
| DET.4.9 | Host-basierte Köder | Detektion für IT-Systeme KANN Host-basierte Köder installieren. | dcdb44ac-280a-424b-bd4f-9264137d6895 |
| DET.4.10 | Anomalien in Netzen und am Perimeter | Detektion für Netze SOLLTE den Netzwerkverkehr auf Anomalien überwachen. | e6cf2c48-c49f-4c10-9cca-252d903b0979 |
| DET.4.10.1 | Authentifizierungsversuche an externen Schnittstellen | Detektion für Externe Netzanschlüsse KANN Authentifizierungsversuche auf unauthorisierte Verbindungen {{ insert: param, det.4.10.1-prm1 }} überprüfen. | 1fc84b56-0931-439d-9b5a-4642926e0d04 |
| DET.4.10.2 | Netzwerk-Honeypots | Detektion für Netze KANN Netzwerk-Honeypots installieren. | 7715c6ec-8cf9-446c-807a-783d61ebd539 |
| DET.4.10.3 | Netzverkehrsfluss | Detektion für Netze KANN auf kritische Netzverkehrsflüsse anhand von {{ insert: param, det.4.10.3-prm1 }} überwachen. | 80109af2-9ed7-4aca-807e-aae712dc8e18 |
| DET.4.11 | Monitoring der Netzverfügbarkeit | Detektion für Netze SOLLTE die Verfügbarkeit des Netzes anhand von {{ insert: param, det.4.11-prm1 }} überwachen. | 3757d23d-e17e-4bae-857e-c045505d579a |
| DET.4.11.1 | Auslastung des Netzes | Detektion für Netze KANN die Auslastung des Netzes anhand von {{ insert: param, det.4.11.1-prm1 }} überwachen. | c17dd877-0922-4ca8-a38b-1d2f9ae04f0d |
| DET.4.12 | Verfügbarkeit des Hostsystems | Detektion für Hostsysteme SOLLTE die Netzerreichbarkeit anhand von {{ insert: param, det.4.12-prm1 }} überwachen. | b186a9e9-cce6-4bb5-8e70-ac17499c71d8 |
| DET.4.13 | Verfügbarkeit der Anwendung | Detektion für Anwendungen SOLLTE die Netzerreichbarkeit anhand von {{ insert: param, det.4.13-prm1 }} überwachen. | 170aaef0-d7a1-49be-a219-7ef13c8be738 |
| DET.4.14 | Ressourcenauslastung von Hostsystemen | Detektion für Hostsysteme SOLLTE die Ressourcenauslastung anhand von {{ insert: param, det.4.14-prm1 }} überwachen. | 7cfa26e7-7fe5-4a6a-999b-489c9785821e |
| DET.4.15 | Ressourcenauslastung der Server-Dienste | Detektion für Anwendungen KANN die Ressourcenauslastung der für die Anwendung verwendeten Server-Dienste anhand von {{ insert: param, det.4.15-prm1 }} | f094dca7-3bfb-477b-8a50-da1587033e4d |
| DET.4.16 | Anwendungsbasiertes Kapazitätsmanagement | Detektion für Anwendungen KANN die Ressourcenauslastung systemübergreifend anhand von {{ insert: param, det.4.16-prm1 }} überwachen. | 93561982-927d-461c-a0eb-c9aec0b1159d |
| DET.4.17 | Öffentliche Blocklisten | Detektion für E-Mail KANN öffentliche Blocklisten auf Einträge für eigene E-Mail-Server {{ insert: param, det.4.17-prm1 }} überprüfen. | e180774d-4880-4ef4-bc08-5c06e034dbc9 |
| DET.4.18 | Unautorisierte Sendeanlagen | Detektion für Räume KANN diesen nach unautorisierten Sendeanlagen durch {{ insert: param, det.4.18-prm1 }} überwachen. | d85d0d64-bc5c-4a11-91d8-7c567abd5b21 |
| DET.5.10.3 | Schrittweiser Rollout | Detektion für IT-Systeme KANN die Installation von Patches stufenweise ausführen. | 87ed8671-91f1-4892-b765-4400b25bc665 |
| DET.5.10.4 | Automatisierte Überwachung von Systemupdates | Detektion für IT-Systeme SOLLTE den Patchstatus durch {{ insert: param, det.5.10.4-prm1 }} überwachen. | d652bc78-8f87-42ef-a52a-7bdd9a43212f |
| DET.5.10.5 | Automatisierte Überwachung von Anwendungsupdates | Detektion für Anwendungen KANN den Patchstatus durch {{ insert: param, det.5.10.5-prm1 }} überwachen. | 1aec3d83-b204-4999-88f5-abf1e140a925 |