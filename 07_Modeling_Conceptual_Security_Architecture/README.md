# 07 Modeling the Conceptual Security Architecture

- [07 Modeling the Conceptual Security Architecture](#07-modeling-the-conceptual-security-architecture)
  - [7.0 Overview](#70-overview)
    - [Table 28: SABSA Conceptual Security Architecture](#table-28-sabsa-conceptual-security-architecture)
    - [Figure 37: Developing the SABSA Conceptual Security Architecture](#figure-37-developing-the-sabsa-conceptual-security-architecture)
  - [7.1 Attribute Profiling](#71-attribute-profiling)
    - [Figure 38: Attribute Profiling (i)](#figure-38-attribute-profiling-i)
    - [Figure 39: Attribute Profiling (ii)](#figure-39-attribute-profiling-ii)
    - [Figure 40: Attribute Profiling (iii)](#figure-40-attribute-profiling-iii)
    - [Figure 41: Completed Attribute Profile](#figure-41-completed-attribute-profile)
  - [7.2 Risk Management \& Strategy](#72-risk-management--strategy)
    - [7.2.1 Risk Management](#721-risk-management)

## 7.0 Overview

### Table 28: SABSA Conceptual Security Architecture

![SABSA Concepture Security Architecture](./Table28/SABSA-Conceptual-Security-Architecture.png)

Snapshot Protege RDF File: [sabsa_matrices_2018_ch07.rdf](./sabsa_matrices_2018_ch07.rdf)

You may find the detail descriptions per Artifacts and Avtivity, the ontology / matrix outline enables the visualizing the set of processes and activities necessary to create and maintain an Architecture Descroption of the Conceptual Architecture.

### Figure 37: Developing the SABSA Conceptual Security Architecture

Although the Conceptual layer has no ArchiMate equivalent, many of the asset (What) and motivation (Why) concepts (attribute profiles, metrics, risk, compliance, control objectives, and layering, etc.) have already been discussed as stereotypes of Motivation elements (see [Chapter 5](../05_Motivation_Aspect/README.md))

![Figure37](./Figure37/Figure37_Developing-the-SABSA-Conceptual-Security_Architecture.png)

Snapshot ArchiMate Model: [Figure 37: Developing SABSA Conceptual Security Architecture](./Figure37/ArchiMate_SABSA_Figure37.archimate)

## 7.1 Attribute Profiling

Key points for presenting SABSA Attributes in ArchiMate language:

- SABSA Attributes are at the apex of the `motivation` pyramid - more abstract than Control Objectives
- SABSA Attributes are global atomic singletons: existing at most once in the model and never appearing, even as copies, more than once in any ArchiMate diagram
- In models, SABSA Attribute profiles are constructed using `influence relationships` to form tree structures that broadly follow the layered architecture
- Each SABSA Attribute may influence/be influenced by zero or more other Attributes, but the tree structure must hold: these `influence relationships` should not be directed downwards from higher to lower layers, so circular paths should not occur in the structure
- SABSA Attributes should be associated to the elements to which they apply, and must be influenced by another `Motivation element`: typically, another Attribute and ultimately by a `Goal` or `Requirement`

### Figure 38: Attribute Profiling (i)

Following section describes the creation of such a profile through a worked example from [GDPR Article 5](https://gdpr-info.eu/art-5-gdpr/), which sets out the principles relating to the processing of personal data.

Article 5 clause (a) states:

"Personal data shall be (a) processed __lawfully__, __fairly__ and in a __transparent__ manner in relation to the data subject ("lawfulness, fairness, and transparency")."

Below Figure 38 shows the Attribute Profiling (i):

![Attribute-Profiling-i](./Figure38/Figure38_Attribute-Profiling(i).png)

Snapshot ArchiMate Model: [Figure 38: Attribute Profiling (i)](./Figure38/ArchiMate_SABSA_Figure38.archimate)

### Figure 39: Attribute Profiling (ii)

Article 5 clause (b) states:

"(b) collected for __specified__, __explicit__ and __legitimate__ purposes and not further processed in a manner that is incompatible with those purposes; further processing for archiving purposes in the public interest, scientific or historical research purposes or statistical purposes shall, in accordance with Article 89(1), not be considered to be incompatible with the initial purposes (‘purpose limitation’);"

![Attribute-Profiling-ii](./Figure39/Figure39_Attribute-Profiling(ii).png)

Snapshot ArchiMate Model: [Figure 39: Attribute Profiling (ii)](./Figure39/ArchiMate_SABSA_Figure39.archimate)

### Figure 40: Attribute Profiling (iii)

Article 5 clause (c) & (d) states:

"(c) __adequate__, __relevant__ and __limited__ to what is necessary in relation to the purposes for which they are processed (‘data minimisation’);"

"(d) __accurate__ and, where necessary, __kept up to date__; every reasonable step must be taken to ensure that personal data that are inaccurate, having regard to the purposes for which they are processed, are erased or rectified without delay (‘accuracy’);"

![Attribute-Profiling-iii](./Figure40/Figure40_Attribute-Profiling(iii).png)

Snapshot ArchiMate Model: [Figure 40: Attribute Profiling (iii)](./Figure40/ArchiMate_SABSA_Figure40.archimate)

### Figure 41: Completed Attribute Profile

Article 5 clause (e) & (f) states:

"(e) kept in a form which permits __identification__ of data subjects for no longer than is necessary for the purposes for which the personal data are processed; personal data may be stored for longer periods insofar as the personal data will be processed solely for archiving purposes in the public interest, scientific or historical research purposes or statistical purposes in accordance with Article 89(1) subject to implementation of the appropriate technical and organisational measures required by this Regulation in order to safeguard the rights and freedoms of the data subject (‘storage limitation’);"

"(f) processed in a manner that ensures appropriate security of the personal data, including __protection__ against unauthorised or unlawful processing and against __accidental loss__, __destruction or damage__, using appropriate technical or organisational measures (‘__integrity__ and __confidentiality__’)."

"2. The controller shall be __responsible__ for, and be able to demonstrate compliance with, paragraph 1 (‘accountability’)."

![Attribute-Profiling-Complete](./Figure41/Figure41_Completed-Attribute-Profile.png)

Snapshot ArchiMate Model: [Figure 41: Completed Attribute Profile](./Figure41/ArchiMate_SABSA_Figure41.archimate)

## 7.2 Risk Management & Strategy

### 7.2.1 Risk Management



---

[<button type="button">«Chapter 06</button>](../06_Modeling_Contextual_Security_Architecture/README.md) [<button type="button">Chapter 08»</button>](../08_Modeling_Logical_Security_Architecture/README.md) [<button type="button">HOME</button>](../README.md)

---

Any comments, feel free to post to the [Discussion Board](https://github.com/yasenstar/ArchiMate_SABSA/discussions).