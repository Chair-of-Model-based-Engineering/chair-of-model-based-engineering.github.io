---
title: "Entwicklung eines automatisierten Testwerkzeugs für Enterprise Applications"
year: 2021
---

# Entwicklung eines automatisierten Testwerkzeugs für Enterprise Applications

**Masterarbeit** (abgeschlossen 2021)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

**Beschreibung**

Topologische Graphen ermöglichen Mehrkomponenten-Anwendungen darzustellen. Jeder Knote in der Graph repräsentiert eine Anwendungskomponente. Das Verhalten einer Komponente wird durch ein Management-Protokoll bestimmt. Es legt anhand Transitionen fest, welche Operationen in einem Zustand ausgeführt werden können. Der Vergleich von Managementprotokollen kann durch einer Konformitätsprüfung erfolgen. Dadurch wird festgestellt, ob eine Komponente durch eine andere zu ersetzen ist. Eine Theorie dafür wurde bereits definiert, aber es fehlt noch eine Implementierung, um die Theorie praktisch verwendet werden zu können.

Dabei gibt es zwei wesentliche Probleme zu lösen: Während einer Konformitätsprüfung können unendlich viele Traces vorkommen und diese können zu Dauerschleifen führen. Um eine endliche Anzahl von Traces zu erreichen, sollte die Erstellung der Traces abgebrochen werden, wenn ein Zustand bereits besucht worden ist. Außerdem sollten nicht nur deterministische sondern auch nichtdeterministische Komponente miteinander verglichen werden können. Eine mögliche Lösung ist dafür, dass Nichtdeterminismus durch verschiedene Varianten von Mpioco unterschiedlich behandelt wird.

Daraus erfolgt, dass Schleifen nicht weiter geprüft werden müssen und die Konformitätsprüfung einfacher ausgeführt werden kann. In dieser Arbeit wird eine Implementierung für die vorgegebene Theorie beschrieben, Konformitätsprüfungen anhand mehreren Beispielen ausgeführt und die Implementierung evaluiert.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
