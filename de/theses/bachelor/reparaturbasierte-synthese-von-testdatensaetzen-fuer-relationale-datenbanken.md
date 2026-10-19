---
title: "Reparaturbasierte Synthese von Testdatensätzen für relationale Datenbanken"
year: 2025
---

# Reparaturbasierte Synthese von Testdatensätzen für relationale Datenbanken

**Bachelorarbeit** (abgeschlossen 2025)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [M. Sc. Sofie Schüler](/de/team/sofie-schueler/)

**Beschreibung**

Es werden immer wieder relationale Datenbanken für Testzwecke benötigt. Bestehende Generierungsverfahren, wie das QAGen-Verfahren und das GenT-Verfahren, welche wir in dieser Arbeit verwenden, stoßen dabei aber immer wieder an ihre Grenzen, wenn sowohl Konsistenz als auch Effizienz gewahrt bleiben sollen. Ein anderer Ansatz wäre, dass man fehlerhafte Dateien korrigiert.

Wir wollen mittels eines Verfahrens eine Datenbank mit konsistenten Daten füllen, dass auf einem reparaturorientierten Ansatz beruht. Das heißt, dass wir gezielt ungültige Tupel einer Datenbank identifizieren und nach einem festgelegten Schema behandeln.

Wir füllen die Datenbank erst einmal mit komplett zufällig gewählten Werten und identifizieren im Anschluss, welche der so generierten Tupel ungültig sind. Im Anschluss löschen wir diese und steuern entweder das QAGen-Verfahren oder aber das GenT-Verfahren an, um wieder die vorgegebenen Kardinalitäten zu erreichen.

Wir konnten feststellen, dass der Ansatz ein Verfahren zu Reparaturzwecke mit einem der üblichen Generierungsverfahren zu kombinieren gute Laufzeiten bietet. Gerade beim Verbund konnte das von uns erstellte Verfahren die Laufzeit erheblich kürzen.

Der Ansatz scheint vielversprechend zu sein und bietet Potential weiter ausgebaut zu werden. Möglicherweise wäre es sinnvoll einen tiefer gehenden Reparaturalgorithmus zu erschaffen, der die ungültigen Daten nicht nur löscht, sondern ungültige Attributwerte innerhalb des Tupels korrigiert.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
