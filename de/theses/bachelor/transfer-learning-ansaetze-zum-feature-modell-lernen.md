---
title: "Transfer-Learning-Ansätze zum Feature-Modell-Lernen"
year: 2024
---

# Transfer-Learning-Ansätze zum Feature-Modell-Lernen

**Bachelorarbeit** (abgeschlossen 2024)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [M. Sc. Mathis Weiß](/de/team/mathis-weiss/)

**Beschreibung**

In der Software-Produktlinien-Entwicklung spielen Feature-Modelle eine zentrale Rolle. Sie bilden die Struktur zahlreicher ähnlicher, jedoch unterschiedlicher Produktvarianten innerhalb eines konfigurierbaren Softwaresystems ab und ermöglichen Analysen des Konfigurationsraums. In der Praxis existiert jedoch oft kein vollständiges Feature-Modell, da Produktvarianten häufig manuell und ohne eine systematische\\
Modellierung entwickelt werden. Daher ist eine Rekonstruktion des Feature-Modells notwendig. Ein Ansatz, der diese Feature-Modell-Rekonstruktion automatisiert, ist das Feature-Modell-Lernen (FML).

\\
Eine wesentliche Herausforderung bei Feature-Modell-Lernen ist, dass die modernsten maschinellen Lernalgorithmen oft große Datenmengen und dementsprechend hohen Rechenaufwand benötigen, um ihr volles Potenzial hinsichtlich Präzision und Recall zu erreichen. Transfer-Learning (TL) hat sich in Domänen wie der Bild- und Textverarbeitung als sehr erfolgreich erwiesen, um diese Probleme zu adressieren und die Effektivität und Effizienz von maschinellen Lernmodellen zu steigern. Da Feature-Modelle häufig ähnliche hierarchische Strukturen mit Eltern-Kind-Beziehungen aufweisen, bietet sich hier eine geeignete Grundlage für denWissenstransfer zwischen verschiedenen Lernaufgaben. Transfer-Learning erlaubt es, ein bereits trainiertes maschinelles Lernmodell für einen Konfigurationsraum erneut\\
zu verwenden und dieses an einen anderen Konfigurationsraum anzupassen.

In unserer experimentellen Evaluation nutzen wir Transfer-Learning mit dem Tool TransTab und das Feature-Modell-Lernen mit dem AutoML-Tool AutoGluon. Wir analysieren die Präzision, den Recall und die Rechenzeit des Transfer-Learning-Ansatzes und vergleichen die Ergebnisse mit Feature-Modell-Lernen mit AutoGluon. Unsere Evaluierungsergebnisse zeigen, dass die Struktur und Komplexität der Konfigurationsräume einen direkten Einfluss auf die Effektivität und Effizienz des Transfer-Learning-Ansatzes haben. Zudem zeigen wir, dass AutoGluon bei größeren Datensätzen sowohl effektiver als auch effizienter ist. Bei kleineren Datensätzen ist der Transfer-Learning-Ansatz effizienter, während AutoGluon eine höhere Effektivität\\
aufweist.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
