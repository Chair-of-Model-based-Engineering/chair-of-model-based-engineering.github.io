---
title: "Integration und Evaluation von Werkzeugen zur Programmanalyse für den Einsatz in der Lehre"
year: 2022
---

# Integration und Evaluation von Werkzeugen zur Programmanalyse für den Einsatz in der Lehre

**Bachelorarbeit** (abgeschlossen 2022)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [M. Sc. Robert Müller](/de/team/robert-mueller/)

**Beschreibung**

Das Einsetzen von Werkzeugen in vorlesungsbegleitenden Übungen erzeugt Praxisnähe, die das Lernen unterstützen kann. Dazu werden in dieser Abschlussarbeit Werkzeuge zur Programmanalyse anhand dreier Kriterien untersucht.

Das erste Kriterium ist die Lauffähigkeit auf den Betriebssystemen Windows, Linux und Mac. Das zweite Kriterium ist die kostenlose und freie Verfügbarkeit. Das dritte Kriterium ist die Ähnlichkeit der Notation der Werkzeuge zur Notation in der Vorlesung. Außerdem wird die Eignung zur Verwendung in der Übung evaluiert.

Diffutils ist eine Sammlung vonWerkzeugen zum Finden und Auflösen von Differenzen in einander ähnlichen Dateien. Mit dem Befehl diff können Unterschiede zwischen zwei Dateien angezeigt werden. Anhand dieser Unterschiede kann eine Patch-Datei erzeugt werden. Mit dem Befehl patch kann eine erzeugte Patch-Datei auf eine andere Datei angewendet werden. Mit dem Befehl diff3 können Unterschiede zwischen drei Dateien angezeigt werden. Außerdem können zwei Dateien, die eine gemeinsame Ursprungsdatei haben, zusammengeführt werden.

JUnit5 ist ein Java-Plugin für die Entwicklung von White-Box-Tests. Mit der Annotation @Test kann im Quelltext ein nachfolgender Testfall eingeleitet werden. Diese Tests sollen die korrekte Funktionalität des Quelltextes testen.

JaCoCo ist eine Java-Bibliothek für die Berechnung von Code-Abdeckung. Das Plugin EclEmma nutzt diese Bibliothek, um Code-Abdeckung in einer Benutzeroberfläche anzuzeigen. Wenn dieses Analysewerkzeug in Kombination mit JUnit-Tests verwendet wird, kann die Erfüllung vieler Abdeckungskriterien untersucht werden.

Alle Werkzeuge erfüllen die Kriterien der Lauffähigkeit und der Verfügbarkeit. Die Notation von Diffutils weicht ein wenig von der Notation in der Vorlesung ab. Die Notation von JUnit5 ist gleich der Notation in der Vorlesung. Die Ausgabe von JaCoCo hingegen weist Abweichungen zur Vorlesung auf. Für die Nutzung in den Übungen sind die Werkzeuge geeignet, allerdings sollte JaCoCo hauptsächlich zu Demonstrationszwecken genutzt werden.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
