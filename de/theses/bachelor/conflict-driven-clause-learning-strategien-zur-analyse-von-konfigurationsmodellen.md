---
title: "Conflict-driven Clause-Learning-Strategien zur Analyse von Konfigurationsmodellen"
year: 2022
---

# Conflict-driven Clause-Learning-Strategien zur Analyse von Konfigurationsmodellen

**Bachelorarbeit** (abgeschlossen 2022)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: M. Sc. Tobias Schüler

**Beschreibung**

Feature Modelle bieten ein ubersichtliches Modell zur Modellierung und Konfiguration komplexer Softwaresysteme im Rahmen einer Software Product Line. Sie können als aussagenlogische Formeln dargestellt werden, um einfacher maschinell mit ihnen zu arbeiten. Eine häufige Anwendung ist die Überprüfung, ob es valide Konfigurationen des Feature Modells gibt, beziehungsweise ob eine bestimmte Konfiguration das Feature Modell erfüllt. Ersteres ist äquivalent zu dem Booleschen Erfüllbarkeitsproblem.

Da diese Überprüfung aufgrund ihrer NP-Vollständigkeit schnell zu prohibitiv langen Rechenzeiten fuhrt, setzen sogenannte SAT-Solver eine Vielzahl unterschiedlicher Methoden ein, um ein, in der Regel schnelleres, Ergebnis zu erzielen. Ein solcher SAT-Solver, dessen Fokus auf Feature Modellen und aus ihnen ableitbaren Heuristiken ihn von anderen SAT-Solvern abhebt, wurde an der Professur „Modellbasierte Entwicklung“ der Universität Siegen entwickelt.

Bisher bietet das Framework exklusiv Implementierungen auf Basis des DPLL-Algorithmus an. Wir erforschen, ob das generell performantere CDCL-Verfahren, das eine Erweiterung von DPLL darstellt, ebenfalls eine Verbesserung für aus Feature Modellen generierte Formeln darstellt, wobei wir sowohl im Bezug auf die Laufzeit wie auch den Speicherverbrauch des Algorithmus ein definitiv positives Resultat erzielen konnten. Darüber hinaus diskutieren wir den Sinn einer Erweiterung des Frameworks um einen CDCL basierten Algorithmus, mit einem trotz der guten Ergebnisse negativen Bescheid, da zu viele architektonische Entscheidungen getroffen wurden, die exklusiv auf rekursiv laufende Algorithmen ausgelegt sind. Ebenfalls diskutieren wir die aus ähnlichen Gründen negativ bewertete Möglichkeit, von Studenten im Rahmen eines Praktikums einen CDCL Algorithmus implementieren zu lassen.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
