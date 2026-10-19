---
title: "Modellierungsansätze und Teststrategien für unabhängige Features in konfigurierbarer Software"
year: 2026
---

# Modellierungsansätze und Teststrategien für unabhängige Features in konfigurierbarer Software

**Bachelorarbeit** (abgeschlossen 2026)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [M. Sc. Mathis Weiß](/de/team/mathis-weiss/)

**Beschreibung**

Konfigurierbare Software erlaubt es, mit einem Softwaresystem unterschiedlichen Anforderungen von Nutzern zu entsprechen. Dazu können für unterschiedliche Nutzer durch die An- und Abwahl von Features des Softwaresystems unterschiedliche Konfigurationen erstellt werden. So muss nicht für jeden Nutzer ein separates Softwaresystem entwickelt werden. Die Features können durch ein Feature-Modell als Baumgraph modelliert werden, in dem Constraints Beziehungen zwischen Features, wie gegenseitiger Ausschluss, abbilden. Mit jedem neuen Feature, das einer konfigurierbaren Software hinzugefügt wird, verdoppelt sich die Anzahl der Featurekombinationen. Dieses Wachstum der Anzahl der Kombinationen ist eine Herausforderung bei der Qualitätskontrolle, da nicht jede valide Konfiguration einzeln getestet werden kann. Sampling-Algorithmen ermöglichen die Qualitätskontrolle auf einer generierten repräsentativen Stichprobe, die nur einen Teil der validen Konfigurationen enthält. Herkömmliche Sampling-Algorithmen berücksichtigen bei der Samplegenerierung, ob Konfigurationen valide sind, indem sie überprüfen, ob die Constraints des Feature-Modells eingehalten werden. Sie betrachten aber nicht, ob zwischen den Features tatsächliche Interaktionen bestehen. Eine tatsächliche Interaktion zwischen Features kann ein Daten- oder Kontrollfluss zwischen den Implementierungen der Features sein. Wir nehmen an, dass Kombinationen aus Features ohne Interaktionen keinen Erkenntnisgewinn bringen und daher deren Betrachtung beim Sampling ineffizient ist. Deshalb schlagen wir vor, Kombinationen aus Features, die keine tatsächlichen Interaktionen miteinander haben, während des Samplings zu ignorieren. Wir führen daher in dieser Arbeit unabhängige Features modelliert als eine neue Relation zwischen Features ein, die keine tatsächlichen Interaktionen haben. Unser Ziel ist es, durch das Auswählen von unabhängigen Features und das Ignorieren dieser während des Samplings die Sampling-Zeit und Sample-Größe zu reduzieren. Um Domänenexperten bei der Auswahl unabhängiger Features zu unterstützen, stellen wir eine Metrik vor, die potentielle Kandidaten identifizieren soll. Außerdem implementieren wir ein Sampling mit unabhängigen Features in einem einfachen Sampling-Algorithmus. In unserer Evaluation testen wir den Einfluss des Ignorierens von unabhängigen Features in unserer Implementierung auf die Sampling-Zeit des Algorithmus und die Sample-Größe. Unsere Evaluation zeigt, dass zunehmend große Mengen unabhängiger Features zu zunehmend großen Reduzierungen der Sampling-Zeit und Sample-Größe verglichen mit Sampling ohne unabhängige Features führen. Die Reduzierung der Sampling-Zeit ist dabei größer als die Reduzierung der Sample-Größe. Somit eignet sich unser Ansatz für konfigurierbare Software, bei der unabhängige Features identifizierbar sind, um die Effizienz des Samplings durch eine reduzierte Sampling-Zeit und Sample-Größe zu verbessern.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
