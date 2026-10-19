---
title: "Kodierungsstrategien von boole’schen Konfigurationsräumen für Ansätze zum Feature-Modell-Lernen"
year: 2024
---

# Kodierungsstrategien von boole’schen Konfigurationsräumen für Ansätze zum Feature-Modell-Lernen

**Bachelorarbeit** (abgeschlossen 2024)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [M. Sc. Mathis Weiß](/de/team/mathis-weiss/)

**Beschreibung**

In der SPL-Entwicklung werden Feature-Modelle eingesetzt, um eine Vielzahl von ähnlichen, aber unterschiedlichen Produktvarianten in einem konfigurierbaren Softwaresystem zu modellieren. Feature-Modelle werden in der Praxis jedoch meistens nicht manuell von Grund auf neu erstellt, sondern durch Ansätze wie das Feature-Modell-Lernen (FML) rekonstruiert. FML verwendet maschinelle Lernalgorithmen, um aus einer bereits implementierten Menge von Produktkonfigurationen automatisch ein Feature-Modell zu lernen.

Ein kritisches Problem, das jedoch bei maschinellen Lernalgorithmen auftritt, ist der sogenannte Curse-of-Dimensionality. Mit jedem hinzugefügten Feature (Dimension) wächst die Größe des Konfigurationsraums exponentiell, was zur Folge hat, dass die vorhandenen Datenpunkte im Vergleich zur Gesamtgröße des Raums zunehmend spärlicher verteilt sind. Diese spärlichere Verteilung der Daten führt dazu, dass es für maschinelle Lernalgorithmen schwieriger wird, signifikante Muster aus dem Datensatz zu erkennen und effektive Klassifikationsmodelle zu erstellen. Um diese Herausforderung zu adressieren, untersuchen wir in dieser Arbeit den Einsatz von Dimensionality-Reduction (DR). Im Rahmen der DR-Technik wenden wir automatisierte Kodierungsstrategien an, die den ursprünglich hochdimensionalen Datensatz in eine niedriger dimensionierte Repräsentation transformieren. Insbesondere konzentrieren wir uns auf zwei spezifische Methoden: Linear-Principal-Component-Analysis (Linear PCA) und Logistic-Principal-Component-Analysis (LogisticPCA). Bei der Linear PCA erreichen wir die Reduktion, indem wir die Daten auf die Hauptachsen (Principal-Components) projizieren, die den größten Teil der Informationen des Datensatzes erfassen. Die Logistic PCA passt das Prinzip der Linear PCA an, um auch mit der booleschen Natur der Konfigurationsräume umzugehen.

Durch experimentelle Evaluierung auf drei verschiedenen Fallstudien vergleichen wir die Effektivität (Präzision und Recall) und Effizienz (Rechenaufwand) von FML sowohl mit als auch ohne den Einsatz von Linear und Logistic PCA. Wir zeigen, dass die Präzision für FML ohne Dimensionality-Reduction nur leicht effektiver ist. Der Recall weist allerdings deutlich höhere Werte im Fall von FML mit Einsatz von DR auf. Der Rechenaufwand von FML verbessert sich durch die Anwendung von PCA in seinen verschiedenen Varianten im Durchschnitt um bis zu 9 % im Vergleich zu FML ohne den Einsatz von PCA. Die Ergebnisse verdeutlichen den Trade-off zwischen Effektivität und Effizienz beim Einsatz von Dimensionality-Reduction im Kontext des FMLs.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
