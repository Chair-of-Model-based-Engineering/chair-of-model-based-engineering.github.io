---
title: "Entwurf und Implementierung eines experimentellen SAT-Solving-Frameworks zur automatisierten Analyse komplexer Softwaresysteme"
year: 2021
---

# Entwurf und Implementierung eines experimentellen SAT-Solving-Frameworks zur automatisierten Analyse komplexer Softwaresysteme

**Masterarbeit** (abgeschlossen 2021)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

**Beschreibung**

Moderne Software ist zunehmend variantenreich und wird zumeist in Form konfigurierbarer Softwaresysteme implementiert. Eine Möglichkeit ist, ein Softwaresystem als Software-Produktlinie auf Basis von Feature-Modellen zu entwickeln. Dadurch lässt sich das Softwaresystem in separate und wiederverwendbare Features aufteilen, statt einzelne Exemplare mit konkreten Feature-Kombinationen zu entwickeln. Die Variantenvielfalt stellt eine Herausforderung für die Qualitätssicherung dar, da es in der Praxis kaum möglich ist, alle Varianten eines solchen Softwaresystems einzeln zu testen. Eine Alternative ist, stattdessen Sampling-Algorithmen zu verwenden, die möglichst kleine, aber dennoch repräsentative Stichproben von Varianten, sogenannte Samples, zu generieren. Die Implementierungen von Sampling-Algorithmen basieren zumeist auf SAT-Solvern, da sich dieses Vorgehen in der Praxis bewährt hat. Das Generieren solcher Samples kann dennoch sehr lange dauern. Der Grund dafür ist, dass die Laufzeit solcher Sampling-Algorithmen maßgeblich von der Laufzeit der verwendeten SAT-Solving-Algorithmen abhängt und das SAT-Problem selbst NP-vollständig ist. Bisher wurden in der Literatur die verwendeten SAT-Solver stets als Blackbox betrachtet. Durch die spezielle Struktur von Feature- Modellen ist anzunehmen, dass auch die SAT-Probleme eine bestimmte Struktur haben. Somit ist vorstellbar, dass sich bestimmte SAT-Solving-Strategien besser eignen als Andere. Unser Ziel ist es, eine parametrisierbare Whitebox für Sampling und SAT-Solving zu schaffen, um in die Implementierung der Algorithmen einzugreifen und bestimmte Strategien hinsichtlich der Performanz zu untersuchen. Konkret untersuchen wir die Auswirkungen verschiedener Strategien zur Anwendung von Pure Literal Elimination (PLE) und Unit Propagation (UP) sowie Priorisierungsstrategien für Variablen auf die Laufzeiten von DPLL-basierten SAT-Solvern. Zudem führen wir den Dependency Graph als neue Datenstruktur ein und entwickeln damit die inkrementelle k-Bounded Kopplungsmetrik, um durch die Variablenpriorisierung für die Pick-Methode, Einfluss auf die Effektivität von UP zu nehmen. Diese Metrik bewertet Klauseln nach ihrem potentiellen Einfluss auf die Vereinfachung der SAT-Formel bei UP. In unseren Ergebnissen erzielt die Kopplungsmetrik mit k = 2 im Durchschnitt die besten Ergebnisse. Dagegen konnten wir bei den Strategien zur Anwendung der Heuristiken, in unseren Experimenten nur einen geringfügigen Einfluss auf die Laufzeit feststellen. Das entwickelte Framework stellt eine gute Basis für die Entwicklung und Analyse weiterer Algorithmen dar. Mithilfe des Frameworks bietet es sich in Form zukünftiger Arbeiten an, weitere Strategien für SAT-Solving-Algorithmen zu untersuchen. Insbesondere die Integration von Domänenwissen über die Struktur von Feature-Modellen in die Pick-Strategie stellt weitere Verbesserungsansätze in Aussicht. Auf Grundlage dieser Arbeit wurde das entwickelte Framework außerdem erfolgreich für eine Lehrveranstaltung eingesetzt.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
