---
title: "Anfrage-spezifische Synthese großer Testdatensätze für relationale Datenbanken"
year: 2023
---

# Anfrage-spezifische Synthese großer Testdatensätze für relationale Datenbanken

**Masterarbeit** (abgeschlossen 2023)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: M. Sc. Tobias Schüler

**Beschreibung**

In der modernen Softwareentwicklung ist es häufig nötig, Testdatensätze für Datenbanken bereitzustellen, um eine testgetriebene Entwicklung für Softwaresysteme mit integrierten Datenbanksystemen zu ermöglichen. Die testgetriebene Entwicklung fordert zudem eine große Anzahl möglichst realistischer Daten, um eine hohe Effektivität der Softwaretests sicherzustellen. Durch Anfrage-spezifische Synthese von Datensätzen lassen sich für ein Anwendungsszenario zugeschnittene Datensätze erzeugen, indem der Datenbankinhalt durch Anfragen mit sogenannten cardinality constraints beschrieben wird. Eine Anfrage samt cardinality constraints enthält dabei Informationen über die Anzahl an Datensätzen, welche einzelne Teilausdrücke erfüllen sollen, sowie die Anzahl der Tupel in der Ergebnismenge. Durch die Abhängigkeiten von cardinality constraints innerhalb einzelner Anfrage lässt sich die Generierung eines validen Datensatzes auf die Erfüllbarkeit eines Optimierungsproblems zurückführen, welches als NP-hart bekannt ist.

Das von Binnig et al. vorgestellte QAGen-Verfahren beschreibt einen Ansatz, bei dem zu erzeugende Einträge durch Variablen repräsentiert werden. Bevor der Generierungsprozess beginnt, werden cardinality constraints als SQL-Abragen formuliert. Während des Generierungsprozesses werden diese constraints in Gleichungen für die einzelnen Variablen übersetzt. Diese Gleichungen werden dann durch einen SMT-Solver gelöst, welcher eine Wertebelegung für die symbolischen Variablen erstellt. Für große Datensätze ergibt sich allerdings das Problem, dass die resultierenden Problemgrößen nicht mehr durch gängige SMT-Solver handhabbar sind und somit keinerlei Testdatensätze erzeugt werden können.

In dieser Arbeit stellen wir das GenT-Verfahren vor, welches auf dem QAGen-Verfahren basiert, aber die Menge der Testdatensätze iterativ erzeugt und nach jeder Iteration prüft, ob die Teilergebnismenge die cardinality constraints erfüllt. Dabei wird der Syntax-Baum der Anfrage durchlaufen und für jeden Knoten zunächst für jeden Nachfolgeknoten ein gültiger Datensatz generiert. Das Generieren eines Datensatzes erfolgt durch sukzessives Übersetzen der cardinality constraints in Gleichungen, welche durch einen SMT-Solver gelöst werden können. Das Ergebnis des SMT-Solvers ist eine Wertebelegung für Einträge des Datensatzes. Durch diesen Ansatz ist es möglich, auch für große Datensätze zumindest Teile der cardinality constraints zu erfüllen.

Für Eingabeprobleme, für die das QAGen-Verfahren ein Ergebnis liefert, ist die Performanz des QAGen-Verfahrens deutlich besser als die des GenT-Verfahrens. Für Eingabeprobleme, für die das QAGen-Verfahren kein Ergebnis liefert, liefert das GenTVerfahren zumindest Teilergebnisse, welche graduell die cardinality constraints erfüllen. Dies ist in Szenarien von Vorteil, in denen die cardinality constraints als Richtmaß für den Umfang der Testdaten verstanden werden können.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
