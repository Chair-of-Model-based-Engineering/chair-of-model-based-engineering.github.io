---
title: "Priorisierungsstrategien für die SAT-basierte Analyse von Konfigurationsmodellen variantenreicher Software"
year: 2021
---

# Priorisierungsstrategien für die SAT-basierte Analyse von Konfigurationsmodellen variantenreicher Software

**Bachelorarbeit** (abgeschlossen 2021)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: M. Sc. Tobias Schüler

**Beschreibung**

Ein Ansatz zur Konfiguration einer Softwareproduktlinie ist die Nutzung von Feature- Modellen. Diese bieten die Möglichkeit, alle gewünschten Features der Software frei auszuwählen. Gewählte Varianten müssen dabei die durch das Feature- Modell gegebenen Restriktionen erfüllen.Umdies automatisiert überprüfen zu können, kann ein Feature-Modell in ein SAT-Problem überführt werden. Dabei gehen jedoch Informationen zum Feature-Modell verloren. An der Professur „Modellbasierte Entwicklung“ der Universität Siegen wurde für das Lösen von SAT-Problemen im Rahmen einer Masterarbeit ein SAT-Solving-Framework entworfen und implementiert. Ein Punkt, der im Rahmen der Masterarbeit besonders auffiel, war die lange Laufzeit der SAT-Solving-Algorithmen. Die Masterarbeit gab einige Aussichten zur Verbesserung der Laufzeit aus Feature-Modellen abegeliteter SAT-Probleme durch Integration von Domänenwissen über Feature-Modelle.

Im Rahmen dieser Arbeit werden auf Basis von Eigenschaften von Feature-Modellen
Lösungsstrategien formuliert und in das SAT-Solver-Framework implementiert. Diese
werden getestet, ausgewertet und auf Basis der Auswertung in einem iterativen
Prozess neue Strategien entwickelt. Dies wird so lange fortgeführt, bis alle sinnvoll
erscheinenden Strategien ausgewertet wurden. Die Strategie, welche die größte
Laufzeitverbesserung erzielt, wird letztlich mit den bestehenden Strategien im Framework
verglichen. Auf Basis dieses Vergleichs wird ein Fazit gezogen und entschieden,
ob das Einbeziehen von Eigenschaften von Feature-Modellen in die Priorisierungsstrategie
von Variablen Verbesserungen der Laufzeit erzielen kann.

Dabei konnten wir herausfinden, dass das Auflösen der cross-tree-constraints und
das anschließende hierarchische durchlaufen des Feature-Baumes im Schema einer
breadth-first search die besten Ergebnisse erzielt. Auch im Vergleich mit einer Basis-
Strategie und den zwei besten im Framework vorhandenen Strategien kann die gefundene
Strategie eine deutliche Verbesserung der Laufzeit erzielen. Das zeigt, dass
das Einbeziehen von Eigenschaften von Feature-Modellen einen eindeutig positiven
Effekt auf die Laufzeit der abgeleiteten SAT-Probleme haben kann.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
