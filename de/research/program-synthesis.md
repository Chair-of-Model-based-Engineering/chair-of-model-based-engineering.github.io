---
title: "Kontinuierliche Programmsynthese"
nav_title: "Programmsynthese"
---

# Kontinuierliche Programmsynthese

[M. Sc. Robert Müller](/de/team/robert-mueller/)

Various techniques and tools for program synthesis have recently gained wide attention both among researchers as well as developers. This trend is, amongst others, driven by the dramatic breakthroughs in artificial intelligence and data-driven machine learning during the past decade. Prominent examples include amazing tools for auto-completion and auto-correction such as FlashFill/FlashMeta, Program Sketching and GitHub Copilot.

The unifying goal of all these approaches is to (semi-)automatically find implementation code satisfying user-oriented, and therefore inherently incomplete, descriptions of the intended functionality of the program under development. However, although the previously mentioned examples all share this common goal, they often vastly differ with respect to the intent and acquired inputs as well as the internally applied search technique.

We focus our considerations on the branch of program synthesis known as *programming-by-example (PBE)*. In PBE, the user writes input-output examples to describe the desired behavior of a program (unit) under development and a PBE synthesizer searches for implementation code satisfying the given examples. In this regard, PBE is well-aligned with modern agile development principles of test-driven development (TDD), by interpreting input-output examples as unit test cases pro-actively driving the implementation of a program unit. However, this promising synergy of PBE and TDD is still far away from being ready-to-use. In particular, the main challenges of PBE approaches can be summarized as follows:

- **Ambiguity.** The specification is naturally limited to *finite sets of input-output examples*, where every additional example may help to further refine the solution. On the other hand, too many examples of the same kind may lead to over-fitting solutions. For instance, feeding the synthesizer with too many simple cases would tend to solutions with over-simplified control-flows.
- **Infinite search space**. Enumerating all candidate solutions is literally impossible such that any effective synthesizer requires some form of additional input as a guidance through the *infinite program space* (e.g., partial implementations or program fragments). Besides correctly implementing the given examples, it is not obvious which further optimization goals to be requested from a synthesizer in order to rule out useless solutions. For instance, simply implementing a look-up table returning each input-output example one-by-one always constitutes the literally most precise, yet also maximally over-fitted solution.

These challenges become even more eminent in the light of recently proclaimed *continuous* development principles.

First, programs together with their accompanying test cases constantly evolve over time and so does the search space for synthesis. On the other hand, developers usually refine their programs in small—and locally restricted—increments in a mostly monotone manner thus leaving unaffected parts unchanged.

Second, in a continuous setting, we may observe two different kinds of ambiguity. As before, *incomplete* specifications may have *multiple* solutions, differing in the input/output behavior for *unknown* examples. Here, a continuous synthesizer should try to estimate which solution fits best to future examples. In addition, *inconsistent* specifications may emerge over time having *no* solution due to examples with *contradicting* input/output behavior. Most existing incremental synthesis approaches resolve such conflicts by *prioritizing* the most recent consistent sets of examples (thus potentially overwriting previously synthesized code). In a continuous setting, however, the intention of contradicting examples may also to describe behavioral *variations* instead of behavioral *changes* (i.e., both behaviors should be preserved).
