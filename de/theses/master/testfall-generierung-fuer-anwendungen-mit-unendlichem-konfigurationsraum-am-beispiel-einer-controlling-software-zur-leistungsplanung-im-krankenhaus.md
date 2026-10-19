---
title: "Testfall-Generierung für Anwendungen mit unendlichem Konfigurationsraum am Beispiel einer Controlling-Software zur Leistungsplanung im Krankenhaus"
year: 2021
---

# Testfall-Generierung für Anwendungen mit unendlichem Konfigurationsraum am Beispiel einer Controlling-Software zur Leistungsplanung im Krankenhaus

**Masterarbeit** (abgeschlossen 2021)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [Jun.-Prof. Dr. Thomas Ludwig](https://www.wineme.uni-siegen.de/team/ludwig/)

**Beschreibung**

Combinatorial Interaction Testing (CIT) ist ein bewährtes Verfahren, um für Anwendungen mit großem Konfigurationsraum eine verhältnismäßig kleine Menge an Testfällen zu selektieren, die kritische Kombinationen von Eingabeparametern hinreichend abdecken. Moderne Anwendungen werden zunehmend umfangreich gestaltet und bieten weit über 10000 Konfigurationsparameter mit bisweilen unbeschränkten Wertebereichen. Bestehende CIT-Verfahren skalieren nicht auf Konfigurationsräume mit einer derart hohen Anzahl an Parametern. Um bestehende CIT-Verfahren auf Konfigurationsräume mit weit über 10000 Konfigurationsparametern anwenden zu können, wird in dieser Arbeit ein neuartiger Ansatz vorgestellt, der die Konfigurationsparameter anhand statistischer Daten klassifiziert und eine geeignete Teilmenge an Konfigurationsparametern selektiert, die mit bestehenden CIT-Verfahren verarbeitet werden kann. Die meisten CIT-Verfahren sind auf endliche Konfigurationsräume beschränkt und lassen sich nicht direkt auf Konfigurationsparameter mit unbeschränkten Wertebereichen anwenden. Um bestehende CIT-Verfahren auf unbeschränkte Konfigurationsräume anwenden zu können, ist es notwendig, mit Hilfe von Heuristiken eine endliche Teilmenge an Werten aus den unbeschränkten Wertebereichen zu selektieren. Bei einem reinen Blackbox-Ansatz besteht allerdings die Gefahr, dass ineffektive Test-Suites entstehen, die kritische Wertekombinationen nicht beinhalten. Unter der Hinzunahme von zusätzlichem Domänenwissen aus den Spezifikationen des Testobjekts lassen sich Wertebereiche in endliche Mengen an Äquivalenzklassen einteilen. Unter der Annahme, dass Fehler häufig an den Grenzen der Äquivalenzklassen auftreten, können die Grenzwerte jeder Äquivalenzklasse als kritische Repräsentanten selektiert werden. Durch die Selektion einer endlichen Menge an Repräsentanten lassen sich bestehende CIT-Verfahren zur Testfallgenerierung nutzen. Die Evaluation des Verfahrens erfolgt anhand der medizinischen Controlling-Software PLATO. Für die Evaluation des Verfahrens wird der Einfluss verschiedener Parametrierungen auf die Laufzeit des Verfahrens untersucht. Die Ergebnisse zeigen, dass die Menge an Features des Ausgangsmodells einen logarithmischen Einfluss auf die Gesamtlaufzeit des Verfahrens hat. Es zeigt sich außerdem, dass der prozentuale Anteil kombinierter Partitionen die Laufzeit der Funktion für die Bestimmung fehlender notwendiger Features exponentiell positiv beeinflusst. Die Anzahl maximal selektierter Features hat einen schwach quadratischen Einfluss auf die Gesamtlaufzeit des Verfahrens. Für die generierte Test-Suite lässt sich anhand des Testobjekts PLATO keine fundierte Bewertung durchführen. Für PLATO können keine belastbaren Daten für die Analyse der generierter Test-Suite anhand des Verhältnis aufgedeckter Fehler und unentdeckten Fehlern erhoben werden. In zukünftigen Arbeiten bietet es sich an, anhand eines geeigneteren Testobjekts die Qualität der generierten Test-Suite zu evaluieren.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
