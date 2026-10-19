---
title: "Performance-Vergleich von BDD-basierten und SAT-basierten Analysestrategien für Konfigurationsmodelle"
year: 2021
---

# Performance-Vergleich von BDD-basierten und SAT-basierten Analysestrategien für Konfigurationsmodelle

**Bachelorarbeit** (abgeschlossen 2021)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: M. Sc. Tobias Schüler

**Beschreibung**

Bei Produkten mit vielen möglichen Produktkonfigurationen kann ein Featuremodell erstellt werden. Ein Featuremodell stellt die Abhängigkeiten der einzelnen Konfigurationsmöglichkeiten dar. Von einem Featuremodell kann eine SAT-Formel abgeleitet werden, mit der zum Beispiel die Erfüllbarkeit des Featuremodells ermittelt werden kann. Zusätzlich kann für eine SAT-Formel eine Variablenreihenfolge festgelegt werden, die festlegt, in welcher Reihenfolge die Variablen aus der SATFormel verarbeitet werden sollen. Die Variablenreihenfolge hat einen Einfluss auf die Performance der weiteren Verarbeitung der SAT-Formel. Um die Erfüllbarkeit einer SAT-Formel zu ermitteln, kann der DPLL Algorithmus ausgeführt oder der BDD erzeugt werden. In dieser Bachelorarbeit wird erarbeitet, ob bei einer längeren Laufzeit des DPLL-Algorithmus, in der die Erfüllbarkeit einer SAT-Formel ermittelt oder widerlegt wird, automatisch auch der BDD für die gleiche SAT-Formel und die gleiche Variablenreihenfolge mehr Knoten hat. Dazu wird ein Testaufbau entwickelt, mit dem Testdaten ausgeführt und Messwerte ermittelt werden. Bei erfüllbaren SAT-Formeln mit einer höheren Komplexitätsstufe hat der DPLL-Algorithmus im Durchschnitt eine längere Laufzeit und der BDD hat im Durchschnitt mehr Knoten. Allerdings wird bei erfüllbaren SAT-Formeln das Verhältnis von den Knoten im BDD zu der Laufzeit des DPLL-Algorithmus von dem Verhältnis der Anzahl der Variablen zu der Anzahl der Klauseln in den SAT-Formeln beeinflusst. Bei nicht erfüllbaren SAT-Formeln hat der BDD außer dem Knoten 0 generell keine Knoten. Daher kann bei nicht erfüllbaren SAT-Formeln der BDD nicht größer werden.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
