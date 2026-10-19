---
title: "Vergleich der Effizienz und Effektivität von Syntheseverfahren und LLM-Tools zur automatisierten Programmerzeugung"
year: 2025
---

# Vergleich der Effizienz und Effektivität von Syntheseverfahren und LLM-Tools zur automatisierten Programmerzeugung

**Bachelorarbeit** (abgeschlossen 2025)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [M. Sc. Robert Müller](/de/team/robert-mueller/)

**Beschreibung**

Die Programmsynthese ist die automatische Erzeugung von Programmcode auf Basis gegebener Spezifikationen. Diese Spezifikationen können dabei auf unterschiedliche Weise erfolgen, insbesondere in Form von Eingabe-/Ausgabebeispielen, die intuitiv und für Nicht-Programmierer leicht nachvollziehbar sind. Obwohl in den letzten Jahren große Fortschritte in der Programmsynthese erzielt wurden, bestehen weiterhin zentrale Herausforderungen. Dazu zählen die Mehrdeutigkeit der gegebenen Spezifikationen, der enorme Suchraum möglicher Programme und die Schwierigkeit, die tatsächliche Nutzerintention aus Beispielen zuverlässig zu erfassen.

In dieser Arbeit steht die induktive Programmsynthese im Fokus, bei der Programme aus Eingabe-/Ausgabebeispielen generiert werden. Ziel dieser Arbeit ist es, zwei Verfahren zur testgetriebenen Synthese mit einem Large Language Model (LLM) zu vergleichen. Zum einen ein Baseline-Verfahren, bei dem das vollständige Programm direkt auf Basis aller Beispiele erzeugt wird. Zum anderen ein dekompositionelles Verfahren, bei dem das Problem in kleinere Teilprobleme aufgeteilt wird, die jeweils separat gelöst und anschließend zu einem Gesamtprogramm zusammengesetzt werden. Das LLM generiert für beide Verfahren Programme anhand den bereitgestellten Eingabe-/Ausgabebeispielen. Wir evaluieren die Effektivität beider Verfahren anhand der Anzahl erfolgreich bestandener Testfälle der generierten Programme. Darüber hinaus untersuchen wir in dieser Arbeit, wie die Anzahl der Eingabe-/Ausgabebeispiele auf die Effektivität der Synthese auswirkt und ob das LLM bei wiederholter Ausführung mit denselben Beispielen zu konsistenten Ergebnissen kommt. Zusätzlich dazu untersuchen wir, wie sich die Angabe eines konkreten Funktionsnamens die Effektivität der Synthese beeinflusst.

Unsere Evaluierungsergebnisse zeigen, dass das dekompositionelle Verfahren insgesamt effektiver als das Baseline-Verfahren ist. Während sich die Effektivität des dekompositionellen Verfahrens mit zunehmender Anzahl an Eingabe-/Ausgabebeispiele kontinuierlich verbessert, zeigt das Baseline-Verfahren nur bei niedrigen Anteilen der Eingabe-/Ausgabebeispiele einen klaren Anstieg in der Effektivität. Außerdem haben wir gezeigt, dass die Syntheseergebnisse bei identischen Prompts bei der Mehrheit der Funktionen inkonsistent sind. Die explizite Angabe des Funktionsnamens kann die Effektivität weiter steigern und zu etwas konsistenteren Ergebnissen führen.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
