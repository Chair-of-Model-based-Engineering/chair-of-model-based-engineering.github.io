---
title: "Shortest-Path Search in Multi-Weighted Automata"
year: 2026
---

# Shortest-Path Search in Multi-Weighted Automata

**Masterarbeit** (abgeschlossen 2026)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [M. Sc. Robert Müller](/de/team/robert-mueller/)

**Beschreibung**

Gewichtete Automaten werden häufig verwendet, um Systeme zu modellieren, in denen möglichen Pfaden oder Verhaltensweisen quantitative Kosten wie Zeit, Distanz oder Ressourcenverbrauch zugeordnet werden. In vielen praktischen Anwendungen müssen mehrere solcher Kosten gleichzeitig berücksichtigt werden, und zulässige Lösungen müssen zusätzlich gegebene Bedingungen erfüllen. Dies führt zu Kürzeste-Wege-Problemen in mehrfach gewichteten Automaten, bei denen Pfade anhand mehrerer Gewichtsdimensionen statt durch einzelne skalare Kosten bewertet werden.

In dieser Arbeit untersuchen wir, wie der A\*-Prune Algorithmus im Kontext mehrfach gewichteter Automaten angewendet werden kann. Der A\*-Prune Algorithmus wurde ursprünglich entwickelt, um die K kürzesten Pfade in mehrfach gewichteten gerichteten Graphen unter mehreren Bedingungen zu finden. Die Übertragung des Algorithmus auf mehrfach gewichtete Automaten ist nicht trivial, da diese initiale und finale Gewichte verwenden und Pfadgewichte durch die Operationen eines Halbrings definieren. Wir analysieren daher, welche Annahmen des ursprünglichen Algorithmus im Automatenkontext erforderlich sind. Das Hauptergebnis ist, dass A\*-Prune nicht allein unter Verwendung der Halbringoperationen auf beliebige Halbringe angewendet werden kann. Zusätzlich benötigt der Algorithmus eine geeignete totale Ordnung der Gewichte zur Priorisierung von Pfaden, monotone Pfaderweiterung, zulässige Heuristiken für untere Schranken und Prüfungen der Bedingungen, die mit der Suchordnung kompatibel sind. Auf Grundlage dieser Analyse entwickeln wir einen Prototyp des angepassten Algorithmus und integrieren ihn in das JAutomata-Framework, das die notwendige Funktionalität für mehrfach gewichtete Automaten und Halbringe bereitstellt.

Wir werten diesen Prototyp auf zufällig generierten mehrfach gewichteten Automaten unter Verwendung eines min-tropischen Integer-Halbrings aus.Wir untersuchen den Einfluss der Bedingungen und Heuristiken auf den betrachteten Suchraum und die Laufzeit. Die Ergebnisse zeigen, dass die Implementierung auf allen getesteten Instanzen die validen Top-K Pfade korrekt berechnet. Sie zeigen außerdem, dass Pruning die Anzahl der betrachteten Kandidatenpfade erheblich reduziert und dass eine gut informierte Dijkstra-basierte Heuristik die Performance gegenüber einer uninformierten Nullheuristik verbessert. Gleichzeitig zeigen die Experimente schwierige Automateninstanzen mit hohen Laufzeiten. Dies verdeutlicht, dass der angepasste Algorithmus das praktische Suchverhalten verbessert, aber weiterhin exponentielleWorst- Case-Laufzeiten aufweist.

Da unsere Auswertung in einem engen Rahmen stattfindet, in dem nur ein Halbring verwendet wird und einige Parameter wie die Gewichtsdimensionen und möglichen Gewichtswerte festgelegt sind, müssen weitere Experimente durchgeführt werden, um zu zeigen, dass unsere Ergebnisse auf beliebige mehrfach gewichtete Automaten verallgemeinert werden können. Insbesondere wird empfohlen, für die Auswertung reale Modelle anstatt zufällig generierter Automaten zu verwenden.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
