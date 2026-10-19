---
title: "Entwicklung einer integrierten Web-Applikation zur automatisierten Testdatensynthese für SQL-Datenbanken"
year: 2024
---

# Entwicklung einer integrierten Web-Applikation zur automatisierten Testdatensynthese für SQL-Datenbanken

**Masterarbeit** (abgeschlossen 2024)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: Dr. Schüll

**Beschreibung**

Datenbanktests bewerten die Genauigkeit, Zuverlässigkeit und Leistung eines Datenbanksystems, um Fehler zu verhindern, Entwicklungskosten zu senken und die Leistung zu verbessern. Verschiedene Arten von Testtechniken können manuell oder automatisch durchgeführt werden. Die Vorteile der Verwendung einer geeigneten Testtechnik während der Entwicklungsphase, um ein gut funktionierendes Datenbanksystem ohne Fehler zu erhalten, sind von entscheidender Bedeutung.

Um sicherzustellen, dass die in der Datenbank gespeicherten und abgerufenen Daten konsistent, präzise und zuverlässig sind, ist es besser, das Datenbanksystem vor der Inbetriebnahme zu testen.

Manuelle Methodenansätze zur Generierung von Testdaten sind zeitaufwändig, erfordern viel manuellen Aufwand, sind fehleranfällig und liefern oft keine repräsentativen Datensätze, die verschiedene Szenarien abdecken. Infolgedessen wird die Effizienz des Softwareentwicklungsprozesses beeinträchtigt, was zu verzögerter Veröffentlichung, erhöhten Kosten und Fehlern in der Produktion führt.

In dieser Masterarbeit geht es darum, ein Konzept zur automatisierten Generierung von Testdatensynthese. Selbst bei einem vorgegebenen Datenbankschema und Constraints sollte das Konzept automatisch passende Testdaten erzeugen, ohne dass der Nutzer den Generierungsprozess manuell steuern muss. Dieses Konzept wird als Webanwendung implementiert, um Testdaten für SQL-Datenbanken basierend auf Eingaben wie Datenbankschema und Constraints zu erstellen.DieseWebanwendung kann zur effektiven Unterstützung von Datenbanktests beitragen, indem sie die Leistung des Datenbanksystems bewertet und dabei hilft, Entwicklungskosten und -zeit zu reduzieren.

Darüber hinaus wird ein experimenteller Test derWebanwendung durchgeführt, um festzustellen, welchen Einfluss die Verteilung des Indizes (Primär- und Fremdschlüssel) sowie die Anzahl der Tabellen und Constraints auf den Generierungsaufwand der Testdaten haben. Es wird auch interessant sein zu bestimmen, in welchem Zeitraum dieWebanwendung eine bestimmte Anzahl von Entitäten (1000, 2000 usw. pro Tabelle) für eine bestimmte Anzahl von Tabellen (5, 25 oder 50 Tabellen) generieren kann.

Eine solche Webanwendung unterstützt den Softwareentwickler bei der Erstellung der Testdatenspezifikation, indem sie erkennt, ob Probleme mit der Datenintegrität, im falschen Format gespeicherte Daten oder falsch definierte Beziehungen zwischen Entitäten vorliegen.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
