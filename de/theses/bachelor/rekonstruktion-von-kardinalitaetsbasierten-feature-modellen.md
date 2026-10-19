---
title: "Rekonstruktion von kardinalitätsbasierten Feature-Modellen"
year: 2025
---

# Rekonstruktion von kardinalitätsbasierten Feature-Modellen

**Bachelorarbeit** (abgeschlossen 2025)

Erstbetreuer: [Prof. Dr. Malte Lochau](/de/team/malte-lochau/)

Zweitbetreuer: [M. Sc. Mathis Weiß](/de/team/mathis-weiss/)

**Beschreibung**

Moderne Software-Systeme müssen auf die Bedürfnisse vieler diverser Nutzer individuell anpassbar sein. In konfigurierbaren Software-Systemen können wir die Anpassbarkeit durch das Auswählen oder Abwählen einer Vielzahl von Features\\
ermöglichen. In kardinalitätsbasierten Feature-Modellen (KFM) können wir im Rahmen von Kardinalitätseinschränkungen die Features eines Software-Systems sogar mehrfach instanziieren. Die Kardinalitätseinschränkungen erlauben dabei die Ableitung von potentiell unendlich vielen Multimengenkonfigurationen aus einem KFM. Wir sind zur Modellierung des Konfigurationsraumes von solchen Software-Systemen interessiert, KFMs aus einer endlichen Teilmenge von Multimengenkonfigurationen automatisiert zu rekonstruieren.

In dieser Bachelorarbeit haben wir einen automatisierten Rekonstruktionsansatz von Kardinalitätseinschränkungen entwickelt. Dafür bilden wir im ersten Schritt eine endliche Teilmenge an bekannten Multimengenkonfigurationen auf Boole’sche Konfigurationen ab, um mit der Formal Concept Analysis (FCA) eine Eltern-Kind-Hierarchie zu rekonstruieren.Wir rekonstruieren anschließend anhand der rekonstruierten Eltern-Kind-Hierarchie mit der endlichen Teilmenge an bekannten Multimengenkonfigurationen explizit 4 Kardinalitätseinschränkungen in Form von Feature-Instanzkardinalitäten von Features, Gruppen-Instanzkardinalitäten sowie Gruppen-Typkardinalitäten von Eltern-Features und Cross-Tree-Constraints-Kardinalitäten. Im Rahmen dieser Bachelorarbeit haben wir festgestellt, dass in tiefen Eltern-Kind-Hierarchien die Multiplizitäten von Kind-Features von den Multiplizitäten der Eltern-Features abhängig sind und für eine präzise Rekonstruktion der Kardinalitätseinschränkungen berücksichtigt werden müssen.

Die Ergebnisse unserer experimentellen Evaluation zeigen, dass die Rekonstruktion einer Eltern-Kind-Hierarchie mit FCA ungenau ist. Unsere experimentelle Evaluation hat zudem gezeigt, dass wir in unserem Rekonstruktionsansatz für KFM die Gruppen-Typkardinalitäten und Feature-Instanzkardinalitäten genauer als die Gruppen-Instanzkardinalitäten und Cross-Tree-Constraints-Kardinalitäten rekonstruieren.Wir haben hoheWerte bezüglich der Präzision und des Recalls bei KFMs mit kleinen Kardinalitätsintervallen erkannt. Die Laufzeit in Form der Wall-Clock-Time korreliert linear mit der Anzahl der Features von KFM und der Anzahl an genutzten bekannten Multimengenkonfigurationen. Unser Rekonstruktionsansatz bietet Verbesserungsbedarf an der Rekonstruktion einer Eltern-Kind-Hierarchie, stellt aber eine vielversprechende Grundlage zur Rekonstruktion der Kardinalitätseinschränkungen von KFM dar.

---

[⇐ Zurück zur Übersicht der Abschlussarbeiten](/de/theses/)
