---
title: "Benchmarks zur Performance Evaluation von SAT-Solvern"
year: 2025
---

# Benchmarks zur Performance Evaluation von SAT-Solvern

**Bachelorarbeit** (abgeschlossen 2025)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [M. Sc. Mathis Weiß](/de/team/mathis-weiss/)

**Beschreibung**

Das Erfüllbarkeitsproblem der Aussagenlogik, auch SAT-Problem (SAT, von englisch Satisfiability „Erfüllbarkeit“) genannt, behandelt die Frage, ob eine Belegung der Variablen einer aussagenlogische Formel mit den Wahrheitswerten wahr oder falsch existiert, mit der die Formel erfüllbar ist. Zum Beantworten dieser Frage werden SAT-Solver verwendet. Ein Anwendungsfall von SAT-Solvern sind Software– Produktlinien. Der Konfigurationsraum einer Software-Produktlinie kann als aussagenlogische Formel repräsentiert werden und dann von einem SAT-Solver auf Erfüllbarkeit getestet werden. Aufgrund der enormen Größe und Komplexität moderner Software-Produktlinien und der damit einhergehenden Größe der zugehörigen aussagenlogischen Formeln, sind schnelle und effiziente SAT-Solver erforderlich. Um die Leistung von SAT-Solvern zu messen, wird eine Benchmark benötigt.

Im Rahmen des Softwaretechnik-Praktikums der Universität Siegen entwickeln die Studierenden selbst einen SAT-Solver. Dabei implementieren sie die grundlegenden Algorithmen wie den DPLL-Algorithmus und verbessern ihren SAT-Solver dabei schrittweise. Das für das Softwaretechnik-Praktikum bereitgestellte SAT-Solver- Framework stellt den Studierenden eine Benchmark Sammlung zur Verfügung, mit der die Leistung und die Verbesserungen der entwickelten SAT-Solver gemessen werden können. Im Laufe der Zeit haben sich allerdings Probleme mit der Auswahl der SAT-Probleme bemerkbar gemacht. Zum einen hat sich herausgestellt, dass ein Teil der Probleme, der als nicht erfüllbar gekennzeichnet ist, fälschlicherweise erfüllbar ist. Zum anderen ist die Unterteilung der Probleme in die Komplexitätsklassen ungenau.

Wir stellen eine neue Benchmark Sammlung zusammen und überarbeiten die Einteilung der Probleme in die Komplexitätsklassen, damit die jeweiligen Klassen auf die unterschiedlichen SAT-Solver zugeschnitten sind. Außerdem entwickeln wir eine Implementierung, um mit dieser Benchmark Sammlung SAT-Solver evaluieren zu können. Diese Implementierung haben wir genutzt, um die Leistung der in der Vergangenheit im Softwaretechnik Praktikum entwickelten SAT-Solver untereinander zu vergleichen und haben uns angeschaut, wie sie gegen moderne SAT-Solver abschneiden.Wir konnten dabei feststellen, dass manche SAT-Solver aus dem Praktikum bei recht simplen SAT-Problemen nicht schlecht abschneiden. Bei komplexeren SAT-Problemen mit vielen Variablen können sie allerdings mit den modernen SAT-Sovlern nicht mithalten. Die neue Benchmark Sammlung eignet sich gut, um die SAT-Solver aus dem Praktikum zu evaluieren.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
