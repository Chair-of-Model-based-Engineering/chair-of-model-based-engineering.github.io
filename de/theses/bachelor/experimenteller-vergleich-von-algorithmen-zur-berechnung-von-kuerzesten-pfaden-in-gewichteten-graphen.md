---
title: "Experimenteller Vergleich von Algorithmen zur Berechnung von kürzesten Pfaden in gewichteten Graphen"
year: 2026
---

# Experimenteller Vergleich von Algorithmen zur Berechnung von kürzesten Pfaden in gewichteten Graphen

**Bachelorarbeit** (abgeschlossen 2026)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [M. Sc. Robert Müller](/de/team/robert-mueller/)

**Beschreibung**

Graphen sind heutzutage in vielen Bereichen integriert, was ihre Bedeutung unterstreicht. Eines der populärsten und wichtigsten Themen der Graphentheorie ist das Problem des kürzesten Pfades. Es ist ein grundlegendes Problem der Graphentheorie und spielt in vielen Lebensbereichen eine Rolle. Es gibt viele Algorithmen zur Berechnung vom kürzesten Pfad, aber sie liefern nicht immer die gleiche Leistung und Ergebnisse. Einige sind unter bestimmten Bedingungen besser als andere, manche schneller oder langsamer, und manche können bestimmte Graphentypen gar nicht verarbeiten.

Graphen können sich in ihrer Größe, d. h. in der Anzahl ihrer Knoten, unterscheiden. Sie können sich auch in ihrer Dichte, d. h. dem Verhältnis von Knoten zu Kanten, unterscheiden. Sie können auch Kanten mit negativen und/oder positiven Gewichten sowie Zyklen enthalten.

Wir wollen das Verhalten der vier Algorithmen: Dijkstra-Algorithmus, Bellman- Ford-Algorithmus, A\*-Algorithmus und Johnson-Algorithmus, bei diesen verschiedenen Graphentypen untersuchen. Wir werden die Vor- und Nachteile jedes Algorithmus diskutieren und analysieren, wann diese Algorithmen gute bzw. schlechte Ergebnisse liefern. Anschließend entwickeln und implementieren wir ein Framework zur Berechnung des kürzesten Pfades mit diesen vier Algorithmen sowie der benötigten Laufzeit.Wir führen diese Experimente mit zufällig generierten Graphen durch.

Die Ergebnisse zeigen, dass der Dijkstra-Algorithmus und der A\*-Algorithmus Graphen mit Kanten negativer Gewichte nicht gut verarbeiten und in diesem Fall eine sehr schlechte Leistung erbringen. Gleichzeitig weisen diese Algorithmen die kürzeste Laufzeit der vier Algorithmen auf. Ein wichtiger Aspekt des A\*-Algorithmus ist seine starke Abhängigkeit von den Heuristikwerten, die sowohl die Laufzeit als auch die Genauigkeit beeinflussen. Die Ergebnisse zeigen, dass die Größe des Graphen die Laufzeit des Bellman-Ford-Algorithmus signifikant beeinflusst. Aus den Ergebnissen lässt sich schließen, dass der Bellman-Ford-Algorithmus und der Johnson-Algorithmus die höchste Genauigkeit unter den vier Algorithmen aufweisen.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
