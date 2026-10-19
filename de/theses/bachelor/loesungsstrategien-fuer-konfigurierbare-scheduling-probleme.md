---
title: "Lösungsstrategien für konfigurierbare Scheduling-Probleme"
year: 2026
---

# Lösungsstrategien für konfigurierbare Scheduling-Probleme

**Bachelorarbeit** (abgeschlossen 2026)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [M. Sc. Mathis Weiß](/de/team/mathis-weiss/)

**Beschreibung**

Ein Machine Scheduling Problem (MSP) beschreibt die Zuweisung der Aufgaben (Tasks) zu den Maschinen, deren Bearbeitungsdauer, deren Abhängigkeiten und die Reihenfolge, sodass alle Tasks innerhalb einer bestimmten Zeit erledigt werden. Ein Schedule ist eine konkrete Lösung zu dem jeweiligen Problem, indem es die Tasks zu den Maschinen verteilt. Damit ein Schedule für das jeweilige Problem erstellt werden kann, muss man die konkrete Bearbeitungsdauer der Tasks wissen. In der Realität lässt sich diese Bearbeitungsdauer nicht genau bestimmen. Dadurch entstehen Unsicherheiten in den MSPs, beispielsweise der Bearbeitungsdauern der Tasks. Breit et al. modellieren mithilfe ihres Ansatzes des ConfigurableSchedulingTool (CST) diese MSPs mit Variabilität in der Bearbeitungsdauer als konfigurierbare MSPs, welche Feature-Modelle als Basis verwenden. Die Feature-Modelle beschreiben dabei eine Menge von Scheduling-Problemen, die sämtliche Informationen über die möglichen Kombinationen des MSP enthalten. Mithilfe eines CP-Solvers werden die konfigurierbaren MSPs gelöst.

In dieser Arbeit entwickeln wir einen strukturbasierten Ansatz zur Analyse und Generalisierung von Schedules der konfigurierbaren MSPs. Dafür führen wir ein Konzept der Schedule-Strukturen ein, welche die maschinenspezifische Taskreihenfolge eines Schedules von den konkreten Start- und Endzeiten abstrahieren. Auf dieser Grundlage definieren wir die Begriffe der strukturellen Äquivalenz und der strukturellen Verfeinerung, um die Schedules unterschiedlicher Konfigurationen systematisch vergleichen zu können. Aufbauend darauf generalisieren wir die Schedule-Strukturen zu einer generalisierten, konfigurationsübergreifenden Planungsstruktur, welche gemeinsame Relationen der Tasks erfasst, damit wir mit den Unsicherheiten in den Bearbeitungsdauern umgehen können.

Wir evaluieren unseren Ansatz anhand mehrerer Subjektsysteme und untersuchen dabei insbesondere die benötigte Laufzeit des Prozesses zur Erzeugung der Schedule-Strukturen. Die Ergebnisse zeigen, dass die totale Laufzeit stark von der Anzahl der betrachteten Konfigurationen abhängt, welche wieder durch die Variabilität in der strukturellen Komplexität entsteht. Gleichzeitig erreicht unser Ansatz der Schedule-Strukturen eine vollständige Abdeckung des validen Konfigurationsraums für die betrachteten Subjektsysteme. Unser strukturbasierter Ansatz zeigt damit, dass sich die konfigurierbaren Scheduling-Probleme mit Unsicherheiten in der Bearbeitungsdauer strukturell analysieren und über weitere betrachteten Konfigurationen hinweg verallgemeinern lassen.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
