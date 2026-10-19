---
title: "Regelbasiertes Mischen von Programmvarianten"
year: 2020
---

# Regelbasiertes Mischen von Programmvarianten

**Masterarbeit** (abgeschlossen 2020)

Student: [Robert Müller](/de/team/robert-mueller/)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: M. Sc. Dennis Reuling

**Beschreibung**

Das N-Wege-Mischen von Modellen ist eine vielversprechende Methodik der Software-Produktlinienentwicklung, um die Gemeinsamkeiten von N verschiedenen Modellvarianten in einem Modell zu vereinigen und Code-Wiederverwendung zwischen Varianten zu ermöglichen.

Zum präzisen Mischen von C-Programmen hat sich die Repräsentation als semantisch äquivalente Kontrollfluss-Automaten (CFA) als nützlich herausgestellt. Das SiMPOSE-Mischverfahren nutzt diese Programm-Repräsentation und erreicht für eine in der Praxis häufig zur Programmanalyse verwendete Sammlung von Programmen einen guten Trade-off zwischen Effizienz (Laufzeit) und Effektivität (Grad an Code-Wiederverwendung). Die Implementierung erfolgt als monolithischer Algorithmus, also durch nicht-unterteilbare Schritte, welche speziell für CFAs implementiert sind. Dies hat zur Folge, dass der Trade-off nur in geringem Ausmaß gesteuert werden kann und nachträgliche Änderungen erschwert werden.

Ein alternativer Ansatz wurde für die UML-Klassendiagramm-Domäne vorgeschlagen. Statt wie SiMPOSE, als monolithischer Algorithmus, wird dieses Verfahren regelbasiert durch die Verwendung von einfachen, lokalen Regeln realisiert, wodurch die inkrementelle Ausführung des Verfahrens ermöglicht wird und der Trade-off gezielt gesteuert werden kann. Zudem können, im Vergleich zum monolithischen Verfahren, Regeln leicht hinzugefügt, entfernt oder einzeln angepasst werden. Allerdings ist dieser Ansatz auf Grund der komplexeren, pfadbasierten Struktur nicht direkt auf CFAs übertragbar.

Zielsetzungen dieser Arbeit sind Konzeption und Implementierung des regelbasierten Ansatzes zum Mischen für CFA-Repräsentationen von C-Programmen, sowie die Auswertung der Effizienz und Effektivität im Vergleich zum SiMPOSE-Verfahren. Während für Klassendiagramme die Betrachtung lokaler Kontexte ausreicht, so ist die Übertragung des regelbasierten Ansatzes auf CFAs wegen der komplexeren, pfadbasierten Struktur herausfordernd. Zur Lösung wird in dieser Arbeit das inkrementell anwendbare SiFACTOR-Verfahren entwickelt.

Die experimentelle Auswertung des SiFACTOR-Verfahrens mit einer Auswahl von realistischen C-Programmen ergibt, dass eine Vielzahl schwieriger Programmstrukturen trotz der beschränkten Kontextinformationen der lokalen Regeln bereits vollständig unterstützt wird. Für die unterstützten Programme wird eine Verbesserung der Code-Wiederverwendung sowie der Effizienz der familienbasierten Testfall-Generierung um rund 30% erreicht, verglichen mit der Auswertung der einzelnen Varianten. Erwartungsgemäß liegt die Ausführungszeit des SiFACTOR-Verfahrens auf Grund von erhöhtem Overhead durch die inkrementelle Regelausführung über der Ausführungszeit des SiMPOSE-Verfahrens, bewegt sich aber in einer vergleichbaren Größenordnung. Das zukünftige Potential des inkrementellen Refactorings, insbesondere für größere Eingabeprogramme, wird gezeigt, indem die Ausführungszeit schrittweise eingeschränkt und die bis zu einem bestimmten Zeitpunkt erreichte Code-Wiederverwendung ausgewertet wird.

---

Die PDFs der Abschlussarbeit und Präsentation werden auf Anfrage zur Verfügung gestellt.

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
