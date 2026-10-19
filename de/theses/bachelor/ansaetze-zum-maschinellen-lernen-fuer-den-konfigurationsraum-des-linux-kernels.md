---
title: "Ansätze zum maschinellen Lernen für den Konfigurationsraum des Linux Kernels"
year: 2024
---

# Ansätze zum maschinellen Lernen für den Konfigurationsraum des Linux Kernels

**Bachelorarbeit** (abgeschlossen 2024)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [M. Sc. Mathis Weiß](/de/team/mathis-weiss/)

**Beschreibung**

Der Linux Kernel ist mit einer Menge von ca. 15000 Features eines der größten konfigurierbaren Softwaresystemen der Welt. Ein Feature-Modell bietet eine strukturelle Darstellung der Variabilität von konfigurierbaren Softwaresystemen. Für den Linux Kernel existiert ein Feature Modell aber nicht. Aufgrund der Größe des Linux Kernels wird ein automatischer Vorgang benötigt. Zudem besteht aus der Linux Kernel aus Features mit unterschiedlichen Werttypen, wie z.B. tristate, int, String, und hex. Feature-Modell-Lernen ist eine Methode, mit der wir ein Feature-Modell mithilfe von maschinellen Algorithmen erlernen können. Feature-Modell-Lernen wurde jedoch nicht an ein konfigurierbares Softwaresystem mit einer solchen Größe wie des Linux Kernels ausprobiert.

Eine große Herausforderung bei Feature-Modell-Lernen ist das Erstellen eines Datensatzes, welches aus validen und invaliden Konfigurationen besteht. Zum einen wird ein automatischer Vorgang benötigt, mit der wir eine große Menge an Konfigurationen erstellen. Zum anderen brauchen wir ein Ansatz, mit der wir klassifizieren können, ob eine erstellte Konfiguration valide oder invalide ist.

In dieser Arbeit werden wir ein Datensatz aus einer Menge an Konfigurationen vom Linux Kernel erstellen und Feature-Modell-Lernen am Linux Kernel testen. Dabei wurden Verfahren getestet, mit der wir eine große Anzahl an Konfigurationen für den Linux Kernel erstellen. Die Erstellung der Feature-Modelle erfolgt über AutoML-Tools, welche sich geeignete Algorithmen zum Erlernen der Modelle aussucht.

In der experimentellen Evaluation schauen wir uns an, wie viele Konfigurationen wir unterschiedlichen Ansätzen innerhalb einer gewissen Zeitspanne erstellen können. Wir messen die Trainingszeit, die für zum Erstellen eines Modells mithilfe von Feature-Modell-Lernen brauchen. Wir beurteilen die Effektivität der Modelle anhand von Precision und Recall. Wir haben herausgefunden, dass die Generierung von validen Konfigurationen zeitaufwändig ist und dass Feature-Modell- Lernen Schwierigkeiten hat, ein Feature-Modell bei einem großen Softwaresystem zu erstellen.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
