---
title: "Testdatengenerierung zum automatisierten Regressionstesten von Service-Applikationen im Maschinenbau"
year: 2022
---

# Testdatengenerierung zum automatisierten Regressionstesten von Service-Applikationen im Maschinenbau

**Bachelorarbeit** (abgeschlossen 2022)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: M. Sc. Tobias Schüler

**Beschreibung**

Unter dem Gesichtspunkt fortschreitender Digitalisierung im Maschinenbau müssen sich Softwareentwickelnde die Frage nach effektiven Testmöglichkeiten von Service- Applikationen stellen. Service-Applikationen im Maschinenbau besitzen häufig spezielle Anforderungen und Einschränkungen, wie bspw. voneinander abhängige Kombinationen binärer Zustände mit der Notwendigkeit einer sequenziellen Reihenfolge. Das GEORGdashboard dient als konkretes Beispiel einer solchen Service- Applikation und bringt als laufendes Entwicklungsprojekt im Unternehmen Heinrich Georg GmbH Maschinenfabrik anwendungsspezifische Anforderungen und Einschränkungen mit. Für das Testen von Software sind entsprechende Testdaten notwendig. Die manuelle Generierung von Testdaten ist fehleranfällig und aufwendig. Eine Recherche zu verfügbaren datengenerierenden Werkzeugen im Rahmen dieser Arbeit zeigt, dass keines der ermittelten Werkzeuge zur Datengenerierung allen Anforderungen gerecht wird. Wir erkennen hier einen Bedarf an Werkzeugen zur Umsetzung komplexer Anforderungen. Softwaretests, als Teil der Qualitätssicherung, werden unstrukturiert und unsystematisch durchgeführt, weshalb keine systematischen Testansätze eingesetzt werden.

Der Mangel an geeigneten Werkzeugen zur Datengenerierung und fehlende systematische Abläufe zur Abdeckung der anwendungsspezifischen Anforderungen und Einschränkungen erschweren den Prozess der effektiven Qualitätssicherung. Eine wachsende Nachfrage nach Software-Lösungen in der Maschinenbau-Branche erfordert jedoch eine systematische Qualitätssicherung in Form von Softwaretests.

In dieser Arbeit untersuchen wir Testansätze und Werkzeuge, die im industriellen Kontext unter der Betrachtung anwendungsspezifischer Constraints zur Erzeugung von Testdaten anwendbar sind. Die Untersuchung erfolgt anhand des GEORGdashboards. Das GEORGdashboard wird auf Anforderungen und Einschränkungen hin untersucht. Wir suchen nach Werkzeugen, welche die ermittelten Constraints umsetzen und eine Testdatenbasis für erarbeitete Testansätze erzeugen können. Ebenfalls suchen wir nach Testansätzen, die für die Constraints geeignet sind. Dabei versuchen wir systematisch neue Testfälle aus bestehenden Testfällen zu generieren. Wir entwerfen eine Testspezifikation als möglichen Ablauf zur Erzeugung von Testfällen. Die entworfene Testspezifikation wird anhand des GEORGdashboards evaluiert.

Die Evaluation der Testspezifikation zeigt, dass die ausgearbeiteten Testansätze metamorpher Test, Äquivalenzklassenbildung und Grenzwertanalyse geeignete Testansätze sind, um die gestellten Anforderungen und Constraints umzusetzen. Eine Parametrierung der, im metamorphen Test verwendeten metamorphen Relation ermöglicht uns die gezielte Steuerung des Übergangs zwischen positiven, toleranzbasierten und negativen Testfällen und gestattet gleichzeitig die Erstellung neuer Testfälle auf Basis der gewählten Ausgangsdatenbasis.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
