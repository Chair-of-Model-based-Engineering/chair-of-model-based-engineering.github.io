---
title: "Auswertung der Effizienz und Effektivität von Modellprüfungsstrategien für Gewichtete Automaten"
year: 2025
---

# Auswertung der Effizienz und Effektivität von Modellprüfungsstrategien für Gewichtete Automaten

**Masterarbeit** (abgeschlossen 2025)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [M. Sc. Robert Müller](/de/team/robert-mueller/)

**Beschreibung**

Feature-Modelle ermöglichen uns Familien von Softwaresystemen zu modellieren. Die Variation von Softwaresystemen aus derselben Familie wird erreicht durch Einund Ausschließen von verschiedenen Features aus einem Feature-Modell. Um mehrere Instanzen des gleichen Features zu ermöglichen, werden kardinalitätsbasierte Feature-Modelle verwendet. Die Ergänzung von Multiplizität für Features führt zu einer höheren Komplexität der Feature-Modelle, was vorherige Lösungsraum- Abbildungen unpraktikabel macht.

Ein neuer Ansatz wird verwendet, um Multimengen von Features auf gewichtete Automaten abzubilden. Das CFM-WA-Mapping Tool analysiert gewichtete Automaten basierend auf den vier Eigenschaften non-emptiness, universality, lower boundedness und upper boundedness. Bisher wurde das CFM-WA-Mapping Tool nur mit einer kleinen Menge von gewichteten Automaten geprüft, welche manuell erstellt wurden. Um das CFM-WA-Mapping Tool ausführlicher zu überprüfen, wird eine höhere Anzahl und Vielfalt an gewichteten Automaten benötigt.

Da es derzeit keine standardisierte Bibliothek an gewichteten Automaten existiert, um eine Evaluierung durchzuführen, präsentieren wir zwei Ansätze, um gewichtete Automaten automatisch zu generieren. Die Zufallsgenerierung erstellt gewichtete Automaten basierend auf mehreren strukturellen Parametern, um den gewünschten gewichteten Automaten zu generieren. Mutation verfolgt einen regelbasierten Ansatz, welcher vorhandene Automaten anhand von Mutationsregeln verändert. Beide Ansätze zur Generierung von gewichteten Automaten wurden in dieser Arbeit verwendet, um eine umfangreiche Evaluierung für das CFM-WA-Mapping Tool durchzuführen. Dazu haben wir das CFM-WA-Mapping Tool erweitert, sodass Testkonfigurationen automatisch generiert werden und deren Ground Truths ermittelt werden.

Unsere Evaluationsergebnisse zeigen, dass es möglicherweise nicht praktikabel ist, die Ground Truth automatisch zu ermitteln basierend auf der fortlaufenden Anzahl an gleichen Ergebnissen und einer hohen Anzahl an Pfaden. Testkonfigurationen, für welche die Ergebnisse in einem Muster abhängig von der Anzahl der Pfade evaluiert werden, könnten ein mögliches Problem in der Evaluierung aufzeigen. Der einflussreichste strukturelle Parameter, um die Ground Truth zu entdecken und die Korrektheit der Testkonfigurationen zu erhöhen ist die Anzahl der zusätzlichen Transitionen. Für die Laufzeit der Testkonfigurationen ist die Anzahl der Aktionen am einflussreichsten. Mutationen, welche die Anzahl der Komponenten des gewichteten Automaten reduzieren und somit diese weniger komplex machen, evaluieren eher korrekt. Generell erhöhen Mutationen die durchschnittliche Laufzeit der Testkonfigurationen im Vergleich zu den Testkonfigurationen der ursprünglichen gewichteten Automaten.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
