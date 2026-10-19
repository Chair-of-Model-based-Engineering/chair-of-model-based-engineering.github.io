---
title: "Evaluation induktiver Strategien zur Test-getriebenen Programmsynthese"
year: 2022
---

# Evaluation induktiver Strategien zur Test-getriebenen Programmsynthese

**Bachelorarbeit** (abgeschlossen 2022)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [M. Sc. Robert Müller](/de/team/robert-mueller/)

**Beschreibung**

Die induktive Programmsynthese ist ein benutzerfreundlicher Ansatz, um Programme aus Eingabe-/Ausgabebeispielen zu generieren. Dabei dienen die Beispiele, die vom Benutzer angegeben werden, als Spezifikation für den Synthesizer.

FrAngel realisiert den Ansatz der induktiven Programmsynthese in Java und ergänzt die Synthese mit Erweiterungen. Die zwei Hauptideen von FrAngel sind die Gewinnung von Code-Fragmenten von Programmen, die einen Teil der Spezifikation erfüllen und den angelic conditions, die als Platzhalter für Kontrollstrukturen dienen. Mit diesen Erweiterungen sollen möglichst früh vielversprechende Programme gefunden werden, die dem Zielprogramm ähneln.

Zielsetzung dieser Arbeit ist die Ausführung und Evaluierung von FrAngel. Für die Ausführung von FrAngel werden Eingabe-/Ausgabebeispiele generiert. Die Eingabe-/Ausgabebeispiele werden für vorgefertigten Programme generierten, indem die Eingabe sowie die daraus resultierende Ausgabe des Programmes abgespeichert werden. FrAngel wird dann anhand dieser Eingabe-/Ausgabebeispiele ausgeführt und unter den Aspekten der Konsistenz, Korrektheit und Suchdauer geprüft. Unter der Konsistenz wird geprüft, ob FrAngel immer zum selben Ergebnis kommt. Die Korrektheit und Suchdauer werden unter Betrachtung der Anzahl der genutzten Beispiele in der Synthese geprüft.

Die experimentelle Auswertung von FrAngel mit vorgefertigten Programmen zeigt, dass die Programmsynthese von FrAngel nicht konsistent zum selben Abschluss kommt. Die höchste Konsistenz erreicht FrAngel ab einer Anzahl von neun Beispielen. Bezogen auf die Korrektheit und Suchdauer der Synthese, sind ab neun Beispiele ebenfalls die besten Ergebnisse zustandegekommen. Eine Erhöhung der Beispielanzahl über neun Beispielen hat keine deutlich messbaren Vorteile ergeben. Mit einer Anzahl von neun Beispielen kann FrAngel mit einer Wahrscheinlichkeit von 90% ein korrektes Programm generieren, dadurch ist FrAngel nicht zuverlässig.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
