---
title: "Testansätze für relationale Datenbanksysteme"
year: 2023
---

# Testansätze für relationale Datenbanksysteme

**Masterarbeit** (abgeschlossen 2023)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: M. Sc. Tobias Schüler

**Beschreibung**

Wenn wir uns mit dem Thema des Datenbank-Testings beschäftigen wollen, werden wir auch über Testdaten sprechen. Deshalb haben wir uns in dieser Arbeit mit den folgenden Forschungsfragen beschäftigt: Was ist unter dem Begriff Datenbank- Testing zu verstehen und kann für die Lehre eine Schnittstelle zur Verfügung gestellt werden, mit der Studenten Testdaten für beliebige PostgreSQL-basierte Datenbanken generieren können? In den generierten Daten können Verteilungen für Arten von Daten wie Geschlecht, Alter und Passwörter eingestellt werden.

Aus drei Blickwinkeln heraus hat sich herausgestellt, dass Datenbank-Testing nicht mit Software-Testing zu verwechseln wäre, sondern Datenbank-Testing kann als ein Schritt des Softwaretestprozesses betrachtet werden.Wir konnten die wichtigen Aspekte und Prinzipien herausfinden, die bei einem Datenbank-Testing zu beachten sind. Aus einem der Blickwinkel wird es über einen Plan für Datenbank- Testing berichtet, der von der Definition der Ziele bis hin zu den Testergebnissen und deren Protokollierung zusammenfasst.

Für diese Arbeit ist das entwickelte Konzept ein Grundgerüst (Schnittstelle), das in der Lage ist, realistische Testdaten für eine beliebige PostgreSQL-basierte Datenbank zu generieren und die direkt in der Datenbank laden zu können. Nach der Untersuchung von mehreren Softwareprodukten fiel die Entscheidung für die JavaFaker-Bibliothek, die realistische Daten zur Verfügung stellt und sich in einem Spring-Framework Projekt integrieren lässt. Durch Hibernate Reverse Engineering konnten wir Datenbanktabellen der verwendeten auf PostgreSQL basierten Datenbank als XML-Dateien erzeugen. Diese XML-Dateien spiegeln das Datenbankschema der verwendeten Datenbank wider. Der Benutzer musste dann nach dem Start des Programms folgende Informationen eingeben: Den Pfad zum Speicherort für die erzeugten XML-Dateien, den Benutzernamen und das Passwort des Servers, auf dem die Datenbank gespeichert ist, die Anzahl der zu generierenden Entitäten und, falls vom Benutzer gewünscht, die Parameter für die Einstellung der verschiedenen Verteilungen.

Nach durchgeführten Tests des implementierten Konzepts sowie anhand der generierten Testdaten hat sich Folgendes herausgestellt: Die Einstellung einer Verteilung in den Testdaten hat einen geringen Einfluss auf die Zeit der Generierung. Deswegen könnte eine andere Methode für die Speicherung der Daten in der Datenbank angewendet werden, um die benötigte Zeit für die Generierung von Testdaten möglichst beschleunigen zu können. Die Generierung von Testdaten für eine Datenbanktabelle mit Primärschlüssel des Datentyps text (in Java String) sollte mit speziellen Anforderungen erfolgen. Die Verwendung von Indizes und materialisierten Ansichten kann zwar bei der Abfrage von Testdaten verwendet werden, aber der Ausführungsplan des Query-Optimierer muss immer berücksichtigt werden, um ihn kontrollieren und gegebenenfalls optimieren zu können.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
