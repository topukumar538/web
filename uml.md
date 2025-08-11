
---
title: "UML Diagrams — Visual Notes"
author: "Topu"
date: "2025-08-12"
---

# 🎓 Introduction

This PDF compiles annotated visuals from the course “UML Diagrams Full Course (Unified Modeling Language)” to make every concept concrete, with diagram anatomy and examples across structural and behavioral views.

> Each figure caption highlights what to look for in the diagram—notation, structure, and use case.

---

# 📦 Class Diagrams

![Class anatomy: name, attributes, operations, visibility](images/00-09-39.png)
**Figure 1** — Class box anatomy with public (+), private (−), protected (#), package (~); includes parameter directions (in/out/inout).

![Association](images/00-13-13.png)
**Figure 2** — Association with role labels and multiplicity (1..*, 0..1).

![Inheritance](images/00-14-15.png)
**Figure 3** — Hollow triangle toward parent; abstract classes italicized.

![Realization](images/00-15-00.png)
**Figure 4** — Dashed line for class–interface relationship.

![Dependency](images/00-16-02.png)
**Figure 5** — Dashed arrow showing method-level usage.

![Aggregation and Composition](images/00-16-44.png)
**Figure 6** — Hollow diamond (aggregation) vs. filled diamond (composition).

---

# 🔧 Component Diagrams

![Component anatomy](images/00-17-43.png)
**Figure 7** — Component symbol with required (socket) and provided (lollipop) interfaces.

![Interface names](images/00-20-01.png)
**Figure 8** — Named interface symbols via ports.

![Ports and relationships](images/00-21-14.png)
**Figure 9** — How ports expose interfaces; relationships among components.

![Source code view](images/00-23-02.png)
**Figure 10** — Files/packages as components with tags (version, author).

![Executable view](images/00-24-00.png)
**Figure 11** — Executables, libraries, dependencies modeled as components.

---

# 🖥️ Deployment Diagrams

![Node notation](images/00-25-27.png)
**Figure 12** — 3D node boxes with connections.

![Topology view](images/00-26-34.png)
**Figure 13** — Runtime node arrangements and links.

![Embedded modeling](images/00-27-07.png)
**Figure 14** — Device/process stereotypes, processor–device mappings.

![Client-server modeling](images/00-28-02.png)
**Figure 15** — Topology for processors, card readers, displays.

![Distributed modeling](images/00-29-50.png)
**Figure 16** — Logical node groups, networks as packages.

---

# 🎯 Object Diagrams

![Object example](images/00-31-49.png)
**Figure 17** — Snapshot with objectName:ClassName, concrete attribute values.

![Department instance](images/00-33-38.png)
**Figure 18** — Recursive relationships among department objects.

![Robot system state](images/00-36-21.png)
**Figure 19** — Runtime links showing identified elements and internal world view.

---

# 📦 Package Diagrams

![Package notation](images/00-37-41.png)
**Figure 20** — Package box with tab, dependency arrows.

![Visibility](images/00-41-07.png)
**Figure 21** — Public (+), protected (#), package (~), private (−) visibility.

![Dependency stereotypes](images/00-42-12.png)
**Figure 22** — «use», «access», «import», «trace», «merge» relationships.

![Order tracking example](images/00-43-31.png)
**Figure 23** — TrackOrder, OrderDetails, Shipping, UI relationships.

---

# 🧩 Composite Structure Diagrams

![Structured classifier](images/00-45-07.png)
**Figure 24** — Internal parts, ports, and connectors of a class.

![Part naming](images/00-46-01.png)
**Figure 25** — `partName:Type [multiplicity]` notation.

![Store manager view](images/00-47-07.png)
**Figure 26** — Composition showing Customer variants, Items.

![Internal link visibility](images/00-48-28.png)
**Figure 27** — Relationship clarity among nested parts.

![External references](images/00-49-08.png)
**Figure 28** — Dashed rectangles for external linked objects.

![Connector patterns](images/00-50-01.png)
**Figure 29** — Communication paths and ports.

![Computer composite](images/00-51-18.png)
**Figure 30** — PSU, HDD, CPU, RAM illustrated as parts.

---

# 🧬 Profile Diagrams

![Profile basics](images/00-51-32.png)
**Figure 31** — Stereotypes, tags, constraints for domain adaptation.

![Stereotype vocab](images/00-52-21.png)
**Figure 32** — Domain-specific icons and annotations.

![Tagged values](images/00-53-11.png)
**Figure 33** — {key=value} metadata examples.

![Constraints](images/00-54-01.png)
**Figure 34** — [conditions] on attributes, actions.

![Metamodel extension](images/00-55-14.png)
**Figure 35** — Lightweight customization mechanics.

---

# 📈 Behavior Diagrams

![Use case basics](images/00-57-09.png)
**Figure 36** — Actors, goals, system boundaries.

![Activity flow](images/01-04-29.png)
**Figure 37** — Decisions, forks, loops, concurrency.

![State machine](images/01-10-08.png)
**Figure 38** — Lifecycle with events, transitions.

![Sequence diagram](images/01-17-17.png)
**Figure 39** — Lifelines, messages, activation bars.

![Communication diagram](images/01-26-12.png)
**Figure 40** — Collaborations via link emphasis.

![Interaction overview](images/01-33-57.png)
**Figure 41** — Navigation across interactions.

![Timing diagram](images/01-37-11.png)
**Figure 42** — Time vs. state/value tracking.

---

# 📚 Appendix

All diagrams derived from “UML Diagrams Full Course (Unified Modeling Language)” available [here](https://www.youtube.com/watch?v=WnMQ8HlmeXc). Captions reflect key ideas discussed at the timestamps.

