---
title: "Continuous Exploration of Infinitely Configurable Cyber-Physical Systems for Sample-based Testing (Co-InCyTe)"
nav_title: "Co-InCyTe"
---

# Continuous Exploration of Infinitely Configurable Cyber-Physical Systems for Sample-based Testing (Co-InCyTe)

[M. Sc. Mathis Weiß](/de/team/mathis-weiss/)

## **DFG Funded Research Project:** **Continuous Exploration of Infinitely Configurable Cyber-Physical Systems for Sample-based Testing**

![Überblick über das Projekt: links das cyber-physische System mit einem Szenario zum kollaborativen Fahren und einer konfigurierbaren Fahrzeuggruppe aus Leader und Relays, rechts die konfigurierbare Software mit Konfigurationsmodell (Problemraum) und Verhaltensmodell (Lösungsraum)](/assets/img/Co-InCyTe_image-1024x326.png)

Today’s software comprises up to thousands of configuration options to adjust to diverse requirements, contexts, and platforms. For instance, in the automotive domain, almost every car and the respective on-board software leaves the factory individually tailored. Therefore, it is impossible to assure the quality for each individual configuration for systems with such variability. One analysis strategy that bypasses the infeasible configuration-by-configuration approach is sample-based testing. The selection of a representative subset (sample) is usually guided by a sampling criterion, where pairwise combinatorial coverage of configuration options is the most established one. Pairwise combinatorial coverage presumably yields the best efficiency/effectiveness trade-off.

**Nevertheless, sample-based testing has the following open problems seriously obstructing applicability and acceptance:**

- **No Explicit Configuration Model.** Most sampling approaches require a configuration model rigorously specifying the valid configuration space. However, it is widely considered to be practically impossible to completely specify and explore the whole configuration space of modern configurable software, especially in case of infinite configuration spaces.
- **CPS with Non-Boolean and Non-Functional Configuration Options.** For modern software that is part of cyber physical systems (CPS) the notion of software configuration as a vector of Boolean options is insufficient. Rather, the configuration space is shaped by a mixture of Boolean features and parameters over numerical value domains, with complex inter-dependencies.
- **Continuous Exploration of Configuration Spaces.** Modern software that is embedded into CPS is not effectively testable as isolated entities. Most sampling approaches do not support continuous exploration of configuration spaces for incremental refinement of sample selections based on insights gained from previously tested configurations.
- **Black-Box Assumption.** Most recent sampling techniques are back-box approaches where sample selection is guided by the configuration model only. The critical influence of behavioral variability within the solution space is usually out of scope.

**We address these open problems during the research project Co-InCyTe guided by the following research questions**:

1. We need to provide *continuous model-extraction techniques* of configurable CPS with infinite configuration space and behavioral solution-space model.
2. We need to design *continuous sampling techniques* for configurable CPS with infinite configuration spaces and behavioral solution-space models.
3. We need to develop *machine-learning techniques* for continuously improving effectiveness of model extraction and sampling of configurable CPS with infinite configuration spaces and behavioral solution-space models.

The figure at the top illustrates a hypothetical scenario for configurable CPS. The goal of this collaborative-driving scenario is to form a Dissemination Group, consisting of an arbitrary number of cars driving nearby on a road. The group members are supposed to perform autonomous driving in a convoy in order to increase traffic safety and to reduce fuel consumption. A configuration model for the cars’ software system is depicted on the right of the figure. This extended feature model goes beyond purely Boolean features by containing feature attributes and feature cardinalities. The safety-critical nature of this scenario imposes high demands on quality assurance. Developers have to decide which combinations of group sizes, communication channels, speed/distance values etc. from the -literally infinite- number of possible configurations are tested in order to reach a reasonable trade-off between testing effort and fault-detection probability. Additionally, supplementary solution-space knowledge is indispensable for selecting effective samples. For instance, the figure (on the right) depicts (an extract of) a specification of the real-time behavior of the communication protocol between group members based on a configurable parametric timed automaton. This representation superimposes the model variants of all configurations, facilitating family-based analysis techniques to identify particularly critical configurations (e.g., with worst-case execution time or highest fault probability).

The research project Co-InCyTe is funded by the German Research Foundation (DFG). The project is a collaboration between the Chair of Test, Validation and Analysis (TVA) at the Karlsruhe Institute of Technology and the Chair of Model-based Engineering (MBE) at the University of Siegen.
