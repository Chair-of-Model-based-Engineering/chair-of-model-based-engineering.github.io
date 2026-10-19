---
title: "Inkrementelles Paarweises Sampling basierend auf grundlegenden SAT Solving Verfahren"
year: 2023
---

# Inkrementelles Paarweises Sampling basierend auf grundlegenden SAT Solving Verfahren

**Bachelorarbeit** (abgeschlossen 2023)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: M. Sc. Tobias Schüler

**Beschreibung**

Da die Anzahl möglicher Software-Varianten einer Software-Produktlinie exponentiell mit der Anzahl der enthaltenen Features steigt, ist eine vollständige Produkt-basierte Analyse aller Software-Varianten praktisch unmöglich. Für die Analyse realistischer Anwendungen verfolgt die Sample-basierte Produktlinienanalyse deshalb den Ansatz, eine möglichst kleine, aber dennoch repräsentative Stichprobe des validen Konfigurationsraums einer Software-Produktlinie zu analysieren. Die Mehrzahl aller Fehler werden von einem einzigen Feature oder einer Interaktion zweier Features hervorgerufen. Daher ist ein mögliches Auswahlkriterium für die Erstellung von Stichproben, alle validen Kombinationen von Wertezuweisungen aller Feature-Paare von mindestens einer Konfiguration des Samples abzudecken. Die Berechnung eines minimalen Pairwise Samples ist allerdings ein NP-hartes Problem. Der bestimmende Faktor für den Aufwand eines Sampling-Algorithmus ist das NP-vollständige Erfüllbarkeitsproblem von aussagenlogischen Formeln, für das ein SAT-Solver, wie der grundlegende DPLL-Solver, benötigt wird. Die in der Literatur vorgeschlagenen Heuristiken zur effektiven Annäherung möglichst kleiner Samples versuchen deshalb, die Anzahl unnötiger SAT-Solver-Aufrufe während der Sample-Generierung zu reduzieren.

Für das bestehende SAT-Solving-Framework des Lehrstuhls für Modellbasierte Entwicklung der Universität Siegen wurde bereits ein Basis-Sampling-Algorithmus implementiert, welcher jedoch potentiell einige unnötige SAT-Solver-Aufrufe ausführt, um einen möglichst kleinen Pairwise-Sample zu erstellen. Um einige dieser unnötigen SAT-Solver-Aufrufe zu vermeiden, haben wir die Grundideen des ICPL-Algorithmus modularisiert und parameterisierbar in das bestehende SAT-Solving-Framework integriert. Die Implementierungen der einzlenen Grundideen des ICPL-Algorithmus haben wir gezielt auf die Auswirkungen der einzelnen Maßnahmen während der Sample-Generierung, hinsichtlich der Laufzeiten sowie der Sample-Größen, untersucht. Durch die richtige Wahl des Zeitpunkts für die „Invalide Value Schema Detektion“ konnten wir den mittleren Aufwand am meisten reduzieren. Hingegen konnte durch das „Hinzufügen von invertierten Feature-Belegungen“ am wenigsten Aufwand eingespart werden.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
