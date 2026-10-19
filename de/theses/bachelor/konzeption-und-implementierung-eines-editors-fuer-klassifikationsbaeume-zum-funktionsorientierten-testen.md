---
title: "Konzeption und Implementierung eines Editors für Klassifikationsbäume zum Funktionsorientierten Testen"
year: 2024
---

# Konzeption und Implementierung eines Editors für Klassifikationsbäume zum Funktionsorientierten Testen

**Bachelorarbeit** (abgeschlossen 2024)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [M. Sc. Robert Müller](/de/team/robert-mueller/)

**Beschreibung**

Bei dem funktionalen Testen liegt der Fokus darauf, Fehlerfälle aufzudecken, ohne Wissen über Implementierungsdetails zu verfügen. Eine häufig angewendete Methode dafür ist die Klassifikationsbaum-Methode. Bei dieser Methode werden die relevanten Aspekte des zu testenden Systems bestimmt und in Äquivalenzklassen eingeteilt. Durch die Aufteilung kann das System als Klassifikationsbaum dargestellt werden. Die Wurzel des Baumes repräsentiert die zu testende Funktion. Die inneren Knoten stellen die Parameter dar und die Blätter des Baumes repräsentieren die Äquivalenzklassen. Anschließend können mithilfe des Klassifikationsbaums Testfälle generiert werden. Der Umfang der generierten Testsuite ist abhängig von der Anzahl und Gruppierung der Äquivalenzklassen.

Aktuell sind Lösungen zur Erstellung von Klassifikationsbäumen und Testfällen, die von diesen Bäumen abhängen, nur im kommerziellen Bereich und als proprietäre Software erhältlich. Deshalb ist das Ziel dieser Bachelorarbeit die Konzeption und Implementierung einer Webanwendung, mit der Klassifikationsbäume textbasiert erstellt und bearbeitet werden können. Testfälle sollen automatisiert und manuell erstellt werden können und als Tabelle mit Bezug zu den Äquivalenzklassen des Klassifikationsbaums dargestellt werden. Der Klassifikationsbaum und die Testfälle sollen als Text-, PDF- und SVG-Datei exportiert werden können. Außerdem sollen Textdateien importiert werden können, aus denen wiederum der Klassifikationsbaum erstellt wird.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
