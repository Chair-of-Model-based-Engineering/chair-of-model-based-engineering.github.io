---
title: "Strukturierte Code-Generierung aus Kontrollflussautomaten"
year: 2021
---

# Strukturierte Code-Generierung aus Kontrollflussautomaten

**Bachelorarbeit** (abgeschlossen 2021)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [M. Sc. Robert Müller](/de/team/robert-mueller/)

**Beschreibung**

Das N-Wege-Mischen von Modellen bietet, bei der Entwicklung von Software-Produktlinien, eine Möglichkeit, um N verschiedene Modellvarianten zu einem einzigen Modell zusammenzufassen. Durch das Verfahren wird eine Wiederverwendung von Code zwischen Modellvarianten ermöglicht. Für die Anwendung von modellbasierten Verfahren auf C-Programmen, kann C-Code in einen semantisch äquivalente Kontrollflussautomaten übersetzt werden. Kontrollflussautomaten beschreiben den Ablauf der einzelnen Befehle eines Programmes und eignen sich gut für verschiedene Analyseverfahren. Um die analysierten Programme im Anschluss wieder nutzbar zu machen, ist eine Generierung von Programmcode aus dem Kontrollflussautomaten erforderlich. Die Code-Generierung erfolgt dabei über einen naiven Code-Generator, welcher ausschließlich Code generiert, der aus If-Verzweigungen und Sprungbefehlen besteht. Für die maschinelle Weiterverarbeitung in statische Analysetools ist dieses Verfahren ausreichend. Für die Verwendung des N-Wege-Mischens im Rahmen von Software-Produktion stellt sich dieses Verfahren als ungenügend heraus, da der generierte Code von Menschen, auf Grund der Unstrukturiertheit, nur bedingt nutzbar ist.

Die Ziele dieser Arbeit sind die Konzeption und Implementierung eines strukturierten Code-Generators, der aus Kontrollflussautomaten strukturierten C-Code generieren kann. Die Generierung von strukturiertem Programmcode stellt eine Schwierigkeit dar, da durch die Konvertierung in Kontrollflussautomaten viele Informationen über Kontrollstrukturen verloren gehen. Es bedarf eines Verfahrens, welches die Struktur des ursprünglichen Programmcodes anhand des Kontrollflussautomaten wiederherstellen kann. Um dies zu erreichen, wird die Eigenschaft des hierarchischen Aufbaus von strukturiertem Code genutzt. Das Verfahren traversiert den Kontrollflussautomaten und speichert dabei erkannte Kontrollstrukturen in einem hierarchisch aufgebauten Strukturmodell, aus welchen anschließend Programmcode generiert werden kann. Zusätzlich wird das Verfahren mit einer Sammlung an minimalen Beispielprogrammen ausgewertet, um zu zeigen, dass die Implementierung strukturierteren Code generiert als der naive Code-Generator.

Die experimentelle Auswertung mit insgesamt 38 minimalen Beispielprogramme zeigt, dass insgesamt 92,1% der Programme korrekt generiert werden können. Davon sind 60% der Programme solche, für die Sprungbefehle gespart werden können, wodurch eine Verbesserung hinsichtlich der Strukturiertheit gezeigt werden kann. Bei den restlichen 3 von insgesamt 38 Programmen gelingt die Generierung noch nicht, da der Generator einige komplexe Kombinationen von unstrukturierten Elementen nicht erkennen kann.

---

Die PDFs der Abschlussarbeit und Präsentation werden auf Anfrage zur Verfügung gestellt.

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
