---
title: "A Calculus of Relational Database-Manipulation Processes"
nav_title: "Database-Manipulation Processes"
---

# A Calculus of Relational Database-Manipulation Processes

M. Sc. Tobias Schüler

Database manipulation systems (DMS) are transition systems whose states are relational database instances. Actions describe the transitions from one state to the next by modifying the database instances. In recent DMS models, there is no explicit notion of processes that constrain the order of actions, such that any action can be applied to an instance whenever it is activated.

In my PhD project I would like to introduce an additional layer of control in database manipulation systems. This control layer is based on process algebra. It is planned that the process algebra will be based on Milner’s CSS (Calculus of communicating systems). Based on the operational semantics of the calculus, equivalence notions for DMS processes and other aspects such as reachability properties, concurrency and parallel independence are to be examined. An implementation is also planned.
