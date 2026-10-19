---
title: "Vergleich der Effizienz und Effektivität von Feature-Modell-Synthese und Feature-Modell-Lernen"
year: 2023
---

# Vergleich der Effizienz und Effektivität von Feature-Modell-Synthese und Feature-Modell-Lernen

**Masterarbeit** (abgeschlossen 2023)

Student: [Mathis Weiß](/de/team/mathis-weiss/)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [M. Sc. Robert Müller](/de/team/robert-mueller/)

**Beschreibung**

Software-Produktlinien (SPL) vereinen sich unterscheidende, aber ähnliche Produktvarianten einer variantenreicher Software zu einer konfigurierbaren Software. In der SPL-Entwicklung wird häufig ein Feature-Modell verwendet, um zu definieren, welche Auswahl von Konfigurationsoptionen (Features) zu einem gültigen Produkt führt. Feature-Modelle bilden daher den zentralen Bestandteil der SPL-Entwicklung, einschließlich entscheidender Entwicklungsschritte wie der automatisierten Generierung von Produkten und der familienbasierten Analyse.

In der Praxis werden Feature-Modelle jedoch nicht vor der Erstellung der Produkte von Grund auf neu erstellt, sondern müssen aus einer Teilmenge von bereits bekannten, ähnlichen, aber sich unterscheidenden Produktvarianten rekonstruiert werden. Die manuelle Rekonstruktion eines kompletten Feature-Modells durch einen Entwickler ist für SPL aus der Praxis mit bis zu Tausenden Features nicht durchführbar. Daher sollte diese Rekonstruktion automatisiert werden. Ausgehend von einer unvollständigen Menge gültiger Konfigurationen soll ein allgemeines Feature-Modell abgeleitet werden, das den gesamten Konfigurationsraum beschreibt. Es genügt nicht, lediglich die Konfigurationen der vorhandenen Varianten zu erfassen. Das rekonstruierte Modell soll eine möglichst präzise Partitionierung des gesamten Konfigurationsraumes in einen gültigen und einen ungültigen Teil auf der Basis der bekannten Konfigurationen approximieren.

Einer der vielversprechendsten Versuche, ein Feature-Modell automatisch aus einer Menge gültiger Konfigurationen zu synthetisieren, ist die „formal concept analysis“ (FCA). Mit der FCA wird die Menge der bekannten Konfigurationen analysiert, um alle binären Abhängigkeiten zwischen den Features zu extrahieren und ein Feature-Diagramm zu erstellen. Dies führt häufig zu unpräzisen Ergebnissen, da FCA nur binäre Abhängigkeiten erfasst.

In dieser Arbeit betrachten wir einen alternativen Ansatz, bei dem wir maschinelle Lernalgorithmen zum Erlernen eines Feature-Modells einsetzen. Der Einsatz von maschinellem Lernen kann einige Schwächen der FCA umgehen. Erstens sind maschinelle Lernalgorithmen in der Lage, sowohl Informationen über gültige als auch über ungültige Konfigurationen zu berücksichtigen, was beim Syntheseansatz nicht der Fall ist. Außerdem sind maschinelle Lernalgorithmen nicht auf binäre Bedingungen beschränkt, was die Rekonstruktion präziserer Feature-Modelle ermöglicht. Ein dritter Vorteil besteht darin, dass wir mithilfe von AutoML-Tools die Pipeline für maschinelles Lernen vollständig automatisieren können. Damit können wir den Feature-Modell-Lernprozess vollständig automatisieren. Ebenso ermöglicht AutoML die automatische Auswahl und das Tuning der am besten geeigneten maschinellen Lernalgorithmen, ohne dass weiteres Expertenwissen erforderlich ist. Ein potenzieller Nachteil des Feature-Modell-Lernens ist, dass das resultierende Modell ein Black-Box-Klassifikator ist und kein Feature-Diagramm, das explizit alle rekonstruierten Feature-Abhängigkeiten enthält, wie es der Syntheseansatz rekonstruiert.

In unserer experimentellen Evaluation wenden wir die auf FCA basierende Feature-Modell-Synthese mit dem Tool BUT4Reuse und Feature-Modell-Lernen mit dem AutoML-Tool AutoGluon an. Wir vergleichen beide Ansätze hinsichtlich ihrer Effizienz (Rechenaufwand) und Effektivität (Präzision und Recall). Für die von uns untersuchten Systeme erweist sich die Feature-Modell-Synthese bezüglich des Rechenaufwands als effizienter und erreicht hohe Recall-Werte. Das Feature-Modell-Lernen verursacht mehr Rechenaufwand, übertrifft aber die Feature-Modell-Synthese hinsichtlich der Präzision der rekonstruierten Modelle.

---

Die PDFs der Abschlussarbeit und Präsentation werden auf Anfrage zur Verfügung gestellt.

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
