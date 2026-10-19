---
title: "SAT-basierte Analyse konfigurierbarer Scheduling-Probleme"
year: 2025
---

# SAT-basierte Analyse konfigurierbarer Scheduling-Probleme

**Bachelorarbeit** (abgeschlossen 2025)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [M. Sc. Mathis Weiß](/de/team/mathis-weiss/)

**Beschreibung**

Ein Job-Shop Scheduling-Problem (JSSP) enthält eine Menge von zu bearbeitenden Aufgaben (Tasks), wobei es Abhängigkeiten zwischen den Tasks bezüglich der Bearbeitungsreihenfolge gibt. Damit wir einen Ablaufplan (Schedule) für die Bearbeitung der Tasks ermitteln können, müssen wir alle Informationen zu den Tasks wie deren Bearbeitungsdauern eindeutig kennen. In realen Anwendungsfällen von JSSPs in der Industrie oder in Softwaresystemen können wir diese Informationen häufig nicht vollständig angeben, wodurch Variabilität in Form von Unsicherheit in JSSPs auftritt. Breit et al. modellieren JSSPs mit Variabilität als konfigurierbare JSSPs auf Basis von Feature-Modellen, welche zur Modellierung von Softwareproduktlinien genutzt werden. Ein solches Feature-Modell beschreibt eine Menge von Instanzen des konfigurierbaren JSSPs, welche den möglichen Kombinationen der variablen Informationen des konfigurierbaren JSSPs entsprechen. Die Autoren stellen zusätzlich einen Ansatz zum Lösen eines konfigurierbaren JSSPs als Constraint-Optimization-Problem mithilfe des CP-SAT-Solvers vor.

In dieser Arbeit erweitern wir die Möglichkeiten zur Beschreibung konfigurierbarer Scheduling-Probleme. Wir ermöglichen mithilfe von Task mit unbegrenzten Bearbeitungsdauern im konfigurierbaren JSSP die Beschreibung von Tasks bei minimalem Wissen über ihre Bearbeitungsdauern. Wir erweitern die Modellierung konfigurierbarer JSSPs auf konfigurierbare Machine Scheduling-Probleme (MSP).

Wir analysieren die Lösbarkeit konfigurierbarer Scheduling-Probleme in Situationen, in denen keine optimalen Bearbeitungsdauern gewählt werden können. Wir präsentieren zwei Methoden mit unterschiedlicher Laufzeit und Effektivität zur Normalisierung eines konfigurierbaren Scheduling-Problems, dessen Ziel der Ausschluss unlösbarer Instanzen ist. Wir stellen zwei Ansätze zum Finden passender Schedules für ein konfigurierbares MSP bei teilweise bekannten Informationen über unsichere Bearbeitungsdauern vor: einen statischen Ansatz zur Ermittlung eines möglichst allgemeinen Schedules und einen dynamischen Ansatz auf Basis eines Entscheidungsbaums abhängig von der Bearbeitungsdauer eines Tasks.

Unsere Evaluation zeigt, dass die Laufzeit für das Parsen konfigurierbarer MSPs im Vergleich zu konfigurierbaren JSSPs nicht steigt. Mithilfe der Normalisierungen können wir bei geringer Laufzeit viele unlösbare Instanzen ausschließen. Die Ansätze zum Finden von Schedules für ein konfigurierbares MSP sind nur für einen kleinen Teil der Instanzen nutzbar, wobei sie teilweise minimale Laufzeit-Kosten besitzen.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
