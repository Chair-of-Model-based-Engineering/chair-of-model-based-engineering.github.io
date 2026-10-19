---
title: "Sample-based Testing of Configurable Software using Reinforcement Learning"
year: 2026
---

# Sample-based Testing of Configurable Software using Reinforcement Learning

**Masterarbeit** (abgeschlossen 2026)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [M. Sc. Mathis Weiß](/de/team/mathis-weiss/)

**Beschreibung**

Software-Produktlinien ermöglichen die Anpassung von Produkten an unterschiedliche Kundenbedürfnisse, indem sie die Flexibilität bieten, Features in den Produktlinien auszuwählen oder wegzulassen. Diese Flexibilität bei der Anpassung führt zu einer großen Anzahl möglicher Konfigurationen und erschwert das Testen von Produktlinien, da zur Qualitätssicherung theoretisch alle Kombinationen getestet werden müssten. Um dieses Problem zu lösen, wird das samplebasierte Testen eingesetzt, um eine Teilmenge von Konfigurationen auszuwählen, die gemeinsam ein vorgegebenes Samplenkriterium für das Testen erfüllen. Dabei legt das Samplekriterium fest, welche Kombinationen von Features im Sample abgedeckt werden müssen. Diese Kombinationen von Features werden als Value-Schema bezeichnet, und bestehende Ansätze stützen sich in der Regel auf Greedy-Algorithmen, um diese Value-Schemata abzudecken, da Greedy-Algorithmen schnell sind. Obwohl Greedy-Algorithmen jedes beliebige Samplekriterium erfüllen können, ist die resultierende Stichprobe nicht minimal und kann je nach der genauen Reihenfolge der Werteschemata in ihrer Größe schwanken. Daher bleibt die effiziente Ermittlung der kleinsten Stichprobe, die bei stichprobenbasierten Tests ein gegebenes Samplekriterium erfüllt, ein offenes Forschungsproblem. In dieser Arbeit untersuchen wir den Einsatz von Reinforcement Learning als einen alternativen Ansatz zu Greedy-Algorithmen, um dieses Problem anzugehen. Der vorgeschlagene Ansatz modelliert den Sampling-Prozess als Entscheidungsproblem, um Konfigurationen unabhängig von der Reihenfolge der gegebenen Value-Schemata auszuwählen. Anschließend bewerten wir unseren Ansatz im Vergleich zum einfachen Greedy-Algorithmus als Baseline und zum State-of-the-Art-Algorithmus ICLP an großen Echtwelt-Produktlinien. Die Bewertungsergebnisse zeigen, dass es keinen statistisch signifikanten Unterschied zwischen unserem Ansatz und ICLP gibt. Darüber hinaus beobachten wir in unserer Evaluation Faktoren, die sowohl die Sample-Größe als auch die Laufzeit während des Samplings beeinflussen. Diese Erkenntnisse liefern Einblicke in die Dynamik von Sampling. Im Allgemeinen hebt diese Forschung sowohl das Potenzial als auch die Grenzen des Einsatzes von Reinforcement Learning zur Verbesserung der Effizienz der Sample-Größe hervor und weist auf die zugrunde liegende Dynamik von Sampling hin.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
