---
title: "Statistisches Model-Checking zur effizienten Analyse echtzeitkritischer Rekonfigurationen"
year: 2021
---

# Statistisches Model-Checking zur effizienten Analyse echtzeitkritischer Rekonfigurationen

**Bachelorarbeit** (abgeschlossen 2021)

Student: [Mathis Weiß](/de/team/mathis-weiss/)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [M. Sc. Hendrik Göttmann](https://www.es.tu-darmstadt.de/es/team/hendrik-goettmann) (TU Darmstadt)

**Beschreibung**

Dynamische Software Produktlinien (DSPL) werden für die Implementierung dynamisch rekonfigurierbarer Systeme genutzt. DSPL dienen zur systematischen Modellierung von Systemen, die sich beispielsweise an einen veränderten Kontext, also an eine veränderte Umgebung, in der sich das System befindet, anpassen. Dabei wird die DSPL über Kontext-Featuremodelle(KFM) definiert und eingeschränkt. KFM können für die Modellierung der Konfigurationen, in denen sich das System befinden kann, genutzt werden, als auch zur Modellierung des Kontexts, indem sich das System befindet. Durch das Vereinen des Kontexts und der Features des Systems in einem Modell können Abhängigkeiten zwischen diesen modelliert werden. An Rekonfigurationen im vom KFM dargestellten Zustandsraum kann es zudem Echtzeitanforderungen geben. In früheren Arbeiten stellte Göttmann et al. vor, wie Echtzeitanforderungen an Rekonfigurationen von DSPL mit der Real-Time Reconfiguration Constraint Language (RRCL) formalisiert werden können. Dabei generiert man aus dem KFM und den RRCL-Constraints ein Timed Automata (TA)-Netzwerk, welches mit dem Model-Checker UPPAAL auf Eigenschaften und Inkonsistenzen analysiert werden konnte. Dieser Ansatz kämpft jedoch mit hohen Berechnungszeiten und Skalierbarkeitsproblemen, wenn die Zahl der Zustände im TA-Netzwerk steigt. Zudem wurde nur klassisches Model-Checking verwendet. Somit konnten keine stochastischen Eigenschaften modelliert werden, welche oft zur Modellierung des Kontexts verwendet werden. Wir passen das bestehende Verfahren an, um Analysen mit statistischem Model-Checking (SMC) durchführen zu können. Dazu erweitern wir das bestehende Verfahren um eine Produktautomatenbildung, welche das bestehende TA-Netzwerk in einen Produkt-TA überträgt, der mit dem Tool UPPAALSMC mit statistischem Model-Checking analysiert werden kann. Wir loten aus, ob wir durch das Verwenden von statistischem Model-Checking einen Performancegewinn erzielen können. Zudem untersuchen wir, wie präzise und performant statistisches Model-Checking im Vergleich zum bestehenden Ansatz ist. Dabei kann die Präzision und Performance durch einige Parameter angepasst werden, wir untersuchen, wie wir diese Parameter optimal wählen können. Diese Fragestellungen evaluieren wir mit verschiedenen Fallstudien.

---

Die PDFs der Abschlussarbeit und Präsentation werden auf Anfrage zur Verfügung gestellt.

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
