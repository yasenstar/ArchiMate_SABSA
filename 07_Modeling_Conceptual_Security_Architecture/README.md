# 07 Modeling the Conceptual Security Architecture

- [07 Modeling the Conceptual Security Architecture](#07-modeling-the-conceptual-security-architecture)
  - [7.0 Overview](#70-overview)
    - [Table 28: SABSA Conceptual Security Architecture](#table-28-sabsa-conceptual-security-architecture)
    - [Figure 37: Developing the SABSA Conceptual Security Architecture](#figure-37-developing-the-sabsa-conceptual-security-architecture)
  - [7.1 Attribute Profiling](#71-attribute-profiling)
  - [7.2 Risk Management \& Strategy](#72-risk-management--strategy)
    - [7.2.1 Risk Management](#721-risk-management)

## 7.0 Overview

### Table 28: SABSA Conceptual Security Architecture

![SABSA Concepture Security Architecture](./Table28/SABSA-Conceptual-Security-Architecture.png)

Snapshot Protege RDF File: [sabsa_matrices_2018_ch07.rdf](./sabsa_matrices_2018_ch07.rdf)

### Figure 37: Developing the SABSA Conceptual Security Architecture



## 7.1 Attribute Profiling

Key points for presenting SABSA Attributes in ArchiMate language:

- SABSA Attributes are at the apex of the `motivation` pyramid - more abstract than Control Objectives
- SABSA Attributes are global atomic singletons: existing at most once in the model and never appearing, even as copies, more than once in any ArchiMate diagram
- In models, SABSA Attribute profiles are constructed using `influence relationships` to form tree structures that broadly follow the layered architecture
- Each SABSA Attribute may influence/be influenced by zero or more other Attributes, but the tree structure must hold: these `influence relationships` should not be directed downwards from higher to lower layers, so circular paths should not occur in the structure
- SABSA Attributes should be associated to the elements to which they apply, and must be influenced by another `Motivation element`: typically, another Attribute and ultimately by a `Goal` or `Requirement`

## 7.2 Risk Management & Strategy

### 7.2.1 Risk Management



---

[<button type="button">«Chapter 06</button>](../06_Modeling_Contextual_Security_Architecture/README.md) [<button type="button">Chapter 08»</button>](../08_Modeling_Logical_Security_Architecture/README.md) [<button type="button">HOME</button>](../README.md)

---

Any comments, feel free to post to the [Discussion Board](https://github.com/yasenstar/ArchiMate_SABSA/discussions).