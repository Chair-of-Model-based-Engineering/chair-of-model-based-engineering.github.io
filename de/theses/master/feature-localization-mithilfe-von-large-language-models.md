---
title: "Feature Localization mithilfe von Large Language Models"
year: 2025
---

# Feature Localization mithilfe von Large Language Models

**Masterarbeit** (abgeschlossen 2025)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [M. Sc. Mathis Weiß](/de/team/mathis-weiss/)

Student: [M. Sc. Evelyn Rühl](/de/team/evelyn-ruehl/)

**Beschreibung**

Automatic Program Repair (APR) zielt darauf ab, Softwarefehler automatisch zu identifizieren und zu beheben, indem fehlgeschlagene Testfälle analysiert und Patches generiert werden.\\
Ein zentraler Schritt in diesem Prozess ist die Lokalisierung der, für die Fehler verantwortlichen Codestellen (engl. Fault Localization).\\
In konfigurierbaren Softwaresystemen können Fehler jedoch auch auf fehlerhafte Konfigurationen statt auf Codefehler zurückzuführen sein.\\
Traditionelle APR-Methoden, die von einer festen Konfiguration ausgehen, stoßen bei dieser Variabilität an ihre Grenzen.

Feature Localization versucht, Konfigurationsoptionen oder Features den entsprechenden Codestellen zuzuordnen und bildet so die Grundlage für das Verständnis konfigurationsbedingten Verhaltens.\\
Die Integration dieses Wissens in APR könnte effektivere Reparaturstrategien für konfigurierbare Systeme ermöglichen.

Jüngste Fortschritte bei der Entwicklung von Large Language Models (LLMs) zeigen großes Potenzial für Aufgaben der Programmbearbeitung.\\
Bestehende LLM-basierte APR-Ansätze ignorieren jedoch weitgehend Variabilität und konfigurationsbezogene Fehler.\\
Der Einsatz von LLMs für Feature- und Fault Localization eröffnet einen vielversprechenden Ansatz, um APR an die besonderen Herausforderungen konfigurierbarer Softwaresysteme anzupassen.

In dieser Arbeit wird untersucht, wie LLMs zur Feature Localization in konfigurierbaren Softwaresystemen eingesetzt werden können.\\
Hierzu werden LLMs mit Prompts eingesetzt, die Codeausschnitte, Konfigurationsdateien und Testergebnisse enthalten, um die mit beobachteten Fehlern in Verbindung stehenden Features und Codestellen zu identifizieren.\\
Die Evaluation bewertet die Korrektheit der identifizierten Features und Codestellen, die Einhaltung des geforderten Ausgabeformats sowie die Antwortzeit.\\
Es werden vier Modelle verglichen: zwei Versionen von qwen2.5-coder, codellama und gpt-oss.\\
Dabei kommt eine Few-Shot-Prompting-Strategie zum Einsatz, die ein Beispiel für einen variabilitätsbezogenen Fehler und dessen Behebung enthält.

Durch die Erweiterung von LLM-basierter APR auf konfigurierbare Softwaresysteme soll diese Arbeit Fehler adressieren, die aus einer fehlerhaften Feature-Auswahl und nicht aus Logikfehlern im Programm resultieren.\\
Die Ergebnisse, insbesondere aus Experimenten mit sechs Software Product Line (SPL) Systemen, zeigen das Potenzial von LLMs zur Verbesserung der Feature Localization in hochvariablen Softwaresystemen.\\
Während die Modelle vielversprechend bei der Identifikation relevanter Features im Zusammenhang mit beobachteten Fehlern waren, was den Debugging-Prozess unterstützen kann, hatten sie Schwierigkeiten, spezifische Codestellen genau zu lokalisieren.\\
Dies unterstreicht den Bedarf an weiterer Forschung in diesem Bereich.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
