---
title: "Extraktion von Feature-Abhängigkeiten aus Blackbox-Klassifikatoren für Konfigurationsräume"
year: 2025
---

# Extraktion von Feature-Abhängigkeiten aus Blackbox-Klassifikatoren für Konfigurationsräume

**Bachelorarbeit** (abgeschlossen 2025)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [M. Sc. Mathis Weiß](/de/team/mathis-weiss/)

**Beschreibung**

Feature-Modelle sind essenziell, um die Struktur und Eigenschaften einer Software-Produktlinie zu analysieren. Eine Herausforderung in diesem Kontext ist die Erklärbarkeit von Konfigurationseinschränkungen. Die Erklärbarkeit von Konfigurationseinschränkungen stellt die Begründung dar, warum eine Konfiguration gültig oder ungültig ist. Für diese Erklärbarkeit verwendet man ein Feature-Modell in FODA-Notation. Ein solches Feature-Modell ist aber in der Realität oft nicht vorhanden und muss rekonstruiert werden. Das Feature-Modell-Lernen stellt eine Möglichkeit dar, ein Feature-Modell aus einer vorhandenen Menge an Konfigurationen automatisiert als Blackbox-Klassifikator zu rekonstruieren. Ein Blackbox-Klassifikator erlaubt keine direkte Einsicht in Abhängigkeiten zwischen Features, wodurch die Erklärbarkeit von Feature-Abhängigkeiten nicht möglich ist.

Beim automatisierten maschinellen Lernen gibt es zahlreiche Einstellungen, die den Trainingsprozess beeinflussen. Um den Prozess für den Nutzer zu vereinfachen, werden diese Einstellungen in Presets zusammengefasst. Diese Presets bieten vorgefertigte Einstellungen, die eine einfache Konfiguration des Trainingsprozesses ermöglichen. Im Rahmen dieser Arbeit untersuchen wir die Auswirkungen unterschiedlicher Presets auf die Erklärbarkeit des Blackbox-Klassifikators. Insbesondere untersuchen wir ein Preset für maximale Leistung und ein Preset für möglichst interpretierbare Ergebnisse. Es zeigt sich, dass das Preset für interpretierbare Ergebnisse durch den Verzicht auf komplexe Ensemble-Methoden die Erklärbarkeit der Vorhersagen erhöht. Die Modellgenauigkeit ist bei der Verwendung des Presets für interpretierbare Ergebnisse deutlich schlechter als bei dem Preset für maximale Leistung. Die Genauigkeit ist wichtiger als die als die Erklärbarkeit eines Modells.

Wir stellen daher einen neuen Ansatz vor, der durch die gezielte Klassifikation von Feature-Paaren versucht, Abhängigkeiten zwischen zwei Features aus einem beliebigen Blackbox-Klassifikator abzuleiten. Hierzu werden valide Konfigurationen erzeugt, in Feature-Paare unterteilt und gezielt abgeändert. Die Analyse der Veränderungen in der Gültigkeit der Konfigurationen ermöglicht die Identifikation logischer Abhängigkeiten zwischen den Features.

Die Ergebnisse zeigen, dass boolsche Abhängigkeiten zuverlässig erkannt werden können. Komplexere Abhängigkeiten erfordern jedoch einen exponentiell steigenden Aufwand, was die Skalierbarkeit des Ansatzes begrenzt. Der Ansatz zur Extraktion von Feature-Abhängigkeiten zeigt Potenzial für die Analyse von Blackbox-Klassifikatoren und bildet eine vielversprechende Grundlage für zukünftige Forschungsarbeiten in diesem Bereich.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
