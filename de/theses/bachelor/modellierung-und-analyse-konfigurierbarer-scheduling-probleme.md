---
title: "Modellierung und Analyse konfigurierbarer Scheduling-Probleme"
year: 2024
---

# Modellierung und Analyse konfigurierbarer Scheduling-Probleme

**Bachelorarbeit** (abgeschlossen 2024)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [M. Sc. Mathis Weiß](/de/team/mathis-weiss/)

**Beschreibung**

Scheduling, das Konstruieren eines optimalen Ablaufplans für eine Menge voneinander\\
abhängigen Aufgaben, ist ein NP-hartes Problem, welches auch in der Realität\\
in vielen Bereichen der Planung von Relevanz ist. Der Großteil der Lösungsverfahren\\
für Scheduling-Probleme löst allerdings nur eine einzelne Instanz des Problems\\
mit festen Werten, zum Beispiel für die Ausführungszeit einer Task. In der Praxis\\
verfügen wir in einer Planungsphase jedoch nicht über dieses präzise Wissen, sodass\\
wir die genaue Ausführungszeit nicht bestimmen können und eine Problemfamilie\\
erhalten, die mehrere Instanzen beinhaltet. Aufgrund der vielen möglichen\\
Wertekombinationen ist es ineffizient eine Problemfamilie zu lösen, indem wir alle\\
möglichen Instanzen einzeln lösen. Untersucht wird die Effizienz einer Lösungssuche\\
mittels einer Problemfamilie gegenüber der Suche über jede Instanz dieser\\
Familie. In dieser Arbeit soll ein Lösungsansatz vorgestellt werden, der es ermöglicht\\
Familien von Scheduling-Problemen kompakt in einer einzigen Baumstruktur\\
durch Feature-Modelle grafisch darzustellen. Anschließend werden diese Problemfamilien\\
automatisch in eine Darstellung transformiert, die die Verwendung eines\\
CP-SAT-Solvers zu deren Lösung ermöglicht. CP-SAT ist ein SAT-Solver, welchem\\
wir als Eingabe ein Problem durch Constraint Programming definieren können und\\
mit dem sowohl die Erfüllbarkeit als auch die Ermittlung eines optimalen Schedules\\
automatisiert werden kann. Hierfür wird eine Menge an Variablen erstellt und die\\
Werte, welche diese annehmen können, durch Constraints und Bedingungen eingeschränkt.\\
Wir glauben, dass dieser Ansatz vielversprechend ist, da sich Scheduling-\\
Probleme gut als Constraint Satisfiability Probleme modellieren lassen und CP-SAT\\
ein schneller SAT-Solver ist, welcher bereits mehrere SAT Competitions gewonnen\\
hat. Die Evaluationsergebnisse unterstützen diese Vermutung und deuten darauf\\
hin, dass selbst bei größeren Problemen noch eine Lösung in annehmbarer Zeit gefunden\\
wird.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
