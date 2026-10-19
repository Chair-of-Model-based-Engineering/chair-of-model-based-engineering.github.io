---
title: "Performance-Vergleich von Optimierungsstrategien für SQL Anfragen"
year: 2022
---

# Performance-Vergleich von Optimierungsstrategien für SQL Anfragen

**Bachelorarbeit** (abgeschlossen 2022)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: M. Sc. Tobias Schüler

**Beschreibung**

Wenn wir eine Abfrage in PostgreSQL eingeben, vertrauen wir darauf, dass PostgreSQL unsere Abfrage richtig verarbeitet und danach eine Ausgabe liefert. Wenn es aber dazu ankommt, ob unsere Abfrage optimal im Bezug auf die Ausführungszeit ist, können wir es nicht wissen, weil wir die ganze Verarbeitung PostgreSQL überlassen. In dem wir das tun, entwickeln wir nicht das Gespür für optimierte Abfragen und stellen uns irgendwann die Frage, ob PostgreSQL tatsächlich unsere Abfrage optimiert, oder ob eine externe Optimierung unserer Abfrage von PostgreSQL erkannt werden würde?

In dieser Arbeit haben wir uns mit diesen Fragen beschäftigt, indem wir erst mal analysiert haben, wie PostgreSQL eine Abfrage verarbeitet. Dabei kam heraus, dass PostgreSQL aus einer Abfrage Pläne erstellt und dass die Optimierung einer Abfrage mit der Wahl eines schnellen ausführbaren Plans verbunden ist. Damit war schon klar, dass eine externe Optimierung nur wenig Einfluss auf die Verarbeitung unserer Abfrage hat, denn diese mehr die Syntax der Abfrage in PostgreSQL beeinflussen und weniger die Suche nach einem schnellen ausführbaren Plan.

Die Wahl eines Plans war damit verbunden, wie wir PostgreSQL konfigurieren oder welche Indizes, materialisierten Sichten wir angelegt hatten. Denn durch diese Möglichkeiten konnten wir PostgreSQL helfen einen Plan. Deshalb trägt es nicht zu einer guten Optimierung unserer Abfrage bei, wenn wir PostgreSQL die ganze Verarbeitung überlassen. Mit diesen Erkenntnissen haben wir uns der Optimierung unserer Abfrage mit diesen Möglichkeiten gewidmet. Das Ziel dabei war nun herauszufinden, welchen Einfluss diese Möglichkeiten auf die Suche eines schnellen ausführbaren Plan haben, indem wir analysieren, wann diese Möglichkeiten am besten zu Einsatz kommen und welche Vor- und Nachteile diese haben. Die Untersuchung führten wir dann mit dem Kommando Explain Analyse. Aus dieser Untersuchung kam dann insgesamt heraus, dass diese Möglichkeiten sich komplementieren und mit einem sinnvollen Einsatz durch den Benutzer zur Suche oder zur Erstellung eines schnellen ausführbaren Plans auf ihre Weisen beitragen.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
