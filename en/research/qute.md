---
title: "Optimized Quantum Software Testing using Functional Property Specifications and Quantum State Verification Techniques (QuTe)"
nav_title: "QuTe"
---

# Optimized Quantum Software Testing using Functional Property Specifications and Quantum State Verification Techniques (QuTe)

![Project poster for QuTe by Otfried Gühne and Malte Lochau with the key question of how quantum programs can be tested efficiently and effectively; it shows examples, the state of the art, research challenges, project goals, work packages and references](/assets/img/Poster_SPP2514_QuTe-724x1024.png)

Programming a quantum computer is difficult and error-prone, which makes it very hard for developers of new quantum algorithms to write functionally correct code. In classical software development, software testing is a widely established and easy-to-use technique for systematically inspecting program code to detect and localize potential bugs. As software testing relies on actual program executions, it is not only able to find bugs in the software, but may also exploit erroneous effects of the hardware which is particularly crucial for inherently noisy quantum computers. But, adopting classical testing techniques to quantum programs is challenging due to the inaccessibility of quantum variables in intermediate states of test executions and the probabilistic nature of quantum measurements.

The goal of this project is a new methodology for functional white-box testing of quantum programs that tackles these challenges. As a first step, we define a quantum-specific test specification language to formalize functional correctness properties to be tested.  The design of the language should allow developers to express properties to obtain effective tests and, at the same time, to ensure practical testability of these specified properties in a quantum environment. We combine techniques for generating test cases from probabilistic test models with quantum state verification techniques to operationalize the execution and evaluation of the generated test cases in a simulated quantum computing environment. We use estimated cost measures for different state verification strategies to optimize the trade-off between efficiency (testing effort) and effectiveness (probability of detecting property violations) and thereby characterizing the confidence level of the test results.

To study practical applicability of the methodology, we consider two application scenarios. First, we test canonical quantum algorithms with classical inputs and outputs such as Shor’s algorithm.  We use existing program repositories with documented bugs to investigate the efficiency/effectiveness trade-off obtained by different testing strategies. Second, we consider newly developed algorithms for quantum graph state preparation for which more elaborated testing concepts like hyper properties and corresponding state verification techniques are required.

To investigate the impact of noise in quantum hardware on the confidence level of test results, we also consider simulations with noise and, ultimately, also potential test executions on real quantum hardware. Here, we are interested in the question, whether it is possible to characterize test cases which are able to distinguish between errors caused by software bugs and errors at the hardware level.

Part of the [Priority Program 2514](https://www.spp2514.kit.edu/index.php) .
