# I4.0-Anlagen-Dashboards
Projektauftrag
Projekttitel: 
Entwicklung eines I4.0-Anlagen-Dashboards für ETS Didactic

Projektteam: 
Steven -- Webdesign
Tobias -- Webdesign
Dennis -- Webdesign
Alexander -- Webdesign

Projektziele: 
Das Hauptziel dieses Projekts ist die Konzeption und Entwicklung eines Software-Produkts, das es ermöglicht, Sensordaten im Industrie 4.0-Labor (I4.0_LAB) zu visualisieren, zu analysieren und zu überwachen. Die Software wird den Nutzern die Möglichkeit bieten, auf das System zuzugreifen, verschiedene Abschnitte oder Stationen auszuwählen, auf Server-Daten im JSON-Format zuzugreifen, Sensordaten für unterschiedliche Zeiträume (Stunde, Tag, Woche, Monat) anzuzeigen und verschiedene Sensor- und Aktor-Zustände zu überwachen. Zusätzlich wird das System Daten im JSON-Format exportieren können, um die Integration mit Tools wie NodeRED und die weitere Visualisierung zu erleichtern. Obwohl das Produkt sich an bestehenden Systemen wie Grafana orientieren kann, wird die Implementierung vollständig eigenständig erfolgen.

Projektumfeld: 
Das Projekt wird im Industrie 4.0-Labor (I4.0_LAB) von ETS Didactic durchgeführt, wo Anlagendaten, MES-Aufträge und Sensordaten gesammelt und auf Thingspeak oder einem eigenen MQTT-Server gespeichert werden. Diese Daten liegen im JSON-Format oder ähnlichen Datenstrukturen vor und werden für weitere Verarbeitungsschritte genutzt. Zur Datenverwaltung wird eine relationale Datenbank eingesetzt. Die Entwicklung des Frontends erfolgt unter Verwendung des React-Frameworks.

Funktionalitäten: 
Das Software-Produkt wird folgende Funktionalitäten umfassen:
1.	Anmeldung am System: Benutzer können sich authentifizieren, um Zugriff auf Sensordaten zu erhalten.
2.	Auswahl von Abschnitten/Stationen: Benutzer können spezifische Abschnitte oder Stationen auswählen, um Sensordaten und Zustände anzuzeigen.
3.	Zugriff auf Server-Daten im JSON-Format: Das System ermöglicht den Zugriff auf Server-Daten, die im JSON-Format bereitgestellt werden.
4.	Visualisierung von Sensordaten: Das System erlaubt die Visualisierung von Sensordaten für verschiedene Zeiträume, einschließlich Stunden, Tage, Wochen und Monate. Hierbei kann auf bewährte Ansätze wie Grafana aufgebaut werden.
5.	Signalisierung von Sensor-/Aktor-Zuständen: Das System stellt verschiedene Methoden zur Verfügung, um Sensor- und Aktor-Zustände anzuzeigen, einschließlich Signal-Lampen im physischen Raum, Benachrichtigungen in der begleitenden App und visuellen Elementen auf der Webseite.
6.	Datenexport im JSON-Format: Benutzer haben die Möglichkeit, Daten im JSON-Format zu exportieren, um weitere Visualisierungen und Analysen mit Tools wie NodeRED zu ermöglichen.

Meilensteine und Zeitplan: 
Meilenstein 1: Projektinitialisierung und Planung
•	Definition der Projektziele und -anforderungen
•	Erstellung eines detaillierten Projektplans
•	Festlegung des Projektteams und der Verantwortlichkeiten
•	Bereitstellung von Ressourcen und Budget
Meilenstein 2: Systemkonzeption und Design
•	Erstellung eines Systemkonzepts, das die Anmeldung am System, die Auswahl von Abschnitten/Stationen und den Zugriff auf Server-Daten umfasst
•	Design der Benutzeroberfläche für die Visualisierung von Sensordaten
•	Festlegung der Anforderungen an die Signalisierung von Sensor-/Aktor-Zuständen
•	Definition der Datenexportfunktion im JSON-Format
Meilenstein 3: Entwicklung und Implementierung
•	Implementierung der Anmeldung am System
•	Realisierung der Auswahl von Abschnitten/Stationen
•	Entwicklung des Zugriffs auf Server-Daten per JSON
•	Umsetzung der Visualisierung von Sensordaten für verschiedene Zeitabschnitte
•	Implementierung der Signalisierung von Sensor-/Aktor-Zuständen
•	Integration der Datenexportfunktion im JSON-Format
Meilenstein 4: Tests und Qualitätskontrolle
•	Durchführung von umfassenden Systemtests, um sicherzustellen, dass die Funktionalitäten ordnungsgemäß funktionieren
•	Überprüfung der Benutzerfreundlichkeit und der Benutzererfahrung
•	Validierung der Datenintegrität und Sicherheitsmaßnahmen
•	Behebung von Fehlern und Problemen
Meilenstein 5: Schulung der Benutzer
•	Erstellung von Schulungsmaterialien für die Endbenutzer
•	Schulung der Endbenutzer im Umgang mit dem System
•	Bereitstellung von Hilfsmitteln und Unterstützung für die Einführung
Meilenstein 6: Projektabschluss und Übergabe
•	Dokumentation des gesamten Projekts, einschließlich der Systemdokumentation
•	Übergabe des Systems an die Betreiber und Endbenutzer
•	Abschlussbericht und Evaluierung des Projekts

Qualitätskriterien und -standards:
Für die Umsetzung des Projekts gelten die folgenden Qualitätskriterien und Standards:
•	Sicherstellung der Benutzerfreundlichkeit und einfache Navigation im System. 
•	Regelmäßige Überprüfung und Dokumentation des Entwicklungsprozesses. 

Datenstruktur: 
Die vorliegenden Daten sind im JSON-Format oder ähnlichen Datenstrukturen organisiert und werden im System für Verarbeitung und Anzeige genutzt.

Technologie-Stack:
•	Frontend-Entwicklung mit React.
•	Verwendung einer relationalen Datenbank zur Speicherung von Sensordaten und Anlagendaten.
•	Implementierung von Visualisierungs- und Überwachungsfunktionen, einschließlich Signalisierung und Datenexport.
Dieses Projekt hat das Potenzial, die Effizienz und den Mehrwert im Industrie 4.0-Labor erheblich zu steigern, indem es Echtzeitdaten visualisiert und überwacht sowie die Analyse und Berichterstellung vereinfacht.

