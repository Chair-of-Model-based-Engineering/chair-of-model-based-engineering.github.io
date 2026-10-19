---
title: "Fallstudien zum Vergleich von relationalen Datenbanksystemen und Graphdatenbanken in Neo4J"
year: 2021
---

# Fallstudien zum Vergleich von relationalen Datenbanksystemen und Graphdatenbanken in Neo4J

**Bachelorarbeit** (abgeschlossen 2021)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

**Beschreibung**

Relationale SQL-Datenbanken können heutige hohe Vernetzung der Daten, schnelle CRUD-Operationen und Datenvielfalt manchmal nicht mehr völlig handhaben. Aus diesem Grund entstand ein Bedürfnis nach einer alternativen Lösung, und zwar NoSQLDatenbanken. Eine Möglichkeit, eine NoSQL-Datenbank zu realisieren, ist Anwendung einer Graphdatenbank. Dadurch lassen sich Daten in Form eines Graphs, nämlich als Knoten und Kanten darstellen. Im Vergleich zu etablierten RDB, sind GDB jung, nicht so stark im “Alltag“ verbreitet und enthalten viele offenen Forschungsfragen. Wir führen 3 Fallstudien aus, um Unterschiede zwischen RDB und GDB zu untersuchen und Vor- und Nachteile von beiden Datenbankmodellen hinsichtlich Performanz und Ausdrucksfähigkeit zu ermitteln. Wir betrachten drei Beispiele aus der realen Welt: ein Sozialnetzwerk, einen Onlineshop und eine Mitarbeiter-Hierarchie. Für jedes der Beispiele organisieren wir die Datenhaltung in zwei Formen: als RDB SQLite und als GDB Neo4J. Vor der Transformation des Klassendiagramms des Sozialnetzwerks in GDB stellen wir fest, dass es keine standardisierten Konzepte der Umwandlung der Klassen und Beziehungen des Klassendiagramms in Graphdatenbankobjekte definiert sind. Wir entwickeln verschiedene möglichen Konzepte und erläutern Vor- und Nachteile des jeden Konzeptes. Wir stellen SQL-Abfragen in RDB SQLite und Cypher-Abfragen in GDB Neo4J gegenüber und schauen, in welchem Fall die Abfragen schneller sind und das DBMS weniger Speicher verbraucht. Wir prüfen, ob Einschränkungen der RDB, besonders in Problemen der Suche über Pfade fester und beliebiger Länge sowie Berechnen der kürzesten Wege, durch Einsatz von GDB überwunden werden. Unsere Experimente zeigen, dass Geschwindigkeit der Cypher-Abfragen oftmals viel höher, als der ähnlichen SQL-Abfragen ist, und von der Art der Abfrage abhängt. Auch Aggregationsoperationen stellen für GDB kein Hemmnis dar. Die Pfad-basierten Probleme können in GDB teilweise gelöst werden, jedoch im Fall der sehr komplexen Pfaden stoßen GDB ebenfalls auf ihre Grenzen. Flexibilität, die durch Nonexistenz des RDB-ähnlichen Schemas in GDB entsteht, kann die Datenkonsistenz gefährden. Zudem verbraucht Neo4J viel mehr RAM und Plattenspeicher als SQLite. Effizienz des jeden DBS hängt von dem konkreten Anwendungsszenario und konkreten Daten ab, so dass die Auswahl eines passenden Modells durch Festlegung der klaren Zielen, Beurteilung der vorhandenen Ressourcen und Evaluation der Vor- und Nachteile des jeden Datenbankmodells getroffen werden kann. Die in der Arbeit entwickelten GDB-Transformationskonzepte können in zukünftigen Arbeiten automatisiert, und der Vergleich zwischen GDB und RDB vor allem bezüglich den Pfad-basierten Problemen weiter erforscht werden.

---

Die PDFs der Abschlussarbeit und Präsentation werden auf Anfrage zur Verfügung gestellt.

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
