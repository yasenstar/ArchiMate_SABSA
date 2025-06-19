# 05 The Motivation Aspect

A quick table shows the ArchiMate notations matching SABSA attributes:

| SABSA | ArchiMate Notation|
| --- | --- |
| Value / Loss / Value Chain | Value |
| Business Attribute / Article / Mandate / Trust | Principle |
| Control Objective / Compliance Objective | Goal |
| Controls* / Exception | Requirement |
| Context of Requirements | Meaning |
| Risk / Impact / Threat / Vulnerability | Assessment |
| Constraint | Constraint |
| Standard / Regulation | Representation |

\* Control is unique in the Security Overlay in that it can extend any base type.

### Figure 10: Security Enhanced Motivation Metamodel

- Image: [Figure10_Security-Enhanced-Motivation-Metamodel.png](./Figure10/Figure10_Security-Enhanced-Motivation-Metamodel.png)
- Archi Model: [ArchiMate_SABSA_Figure10.archimate](./Figure10/ArchiMate_SABSA_Figure10.archimate)

## 5.1 Value & Loss

The "What" column of the SABSA Architecture Matrix acknowledges the business value of assets.

**Business Value** may be expressed in several forms (financial, legal, brand, social, economic, health & safety) in combination or with others.

This evolution brings it closer to the ArchiMate Specification, which has no element to represent an abstract Asset but instead offers the ability to associate a **Value** element with any model element.

### Figure 11: Modeling Assets using Value

Models containing many Values will have following consideration for reflecting the associated Element name through adopting of a naming conversion:

| Figure 11 | Diagram | Source |
| --- | --- | --- |
| a) Simple model, shows the simple association of a Value with a generic eelment, thereby making it as an asset. | ![11-a](./Figure11/Figure11_a.png) | [11-a](./Figure11/Figure11_a.puml) |
| b1) Modeling Value to Stakeholder, this model needs CAUTION when a Value is appreciated by several Stakeholder or associated with multiple assets. | ![11-b1](./Figure11/Figure11_b1.png) | [11-b1](./Figure11/Figure11_b1.puml) |
| b2) Modeling Value to Stakeholder, this in-line (teritiary) relationship is better pattern and is recommended | ![11-b2](./Figure11/Figure11_b2.png) | [11-b2](./Figure11/Figure11_b2.puml) |
| c) Avoice this kind of Amibiguity/Unintended Coupling | ![11-c](./Figure11/Figure11_c.png) | [11-c](./Figure11/Figure11_c.puml) |

For 11-b2, here is the updated code for diagramming, after checking with PlantUML team:

```bash
@startuml
title Figure 11 - b)-2 Modeling Value to Stakeholder (Recommended)

class Stakeholder <<motivation>>
class AssetValue <<motivation>>
class Asset <<element>>

hide <<motivation>> circle
hide <<element>> circle

hide <<motivation>> members
hide <<element>> members

Stakeholder - Asset
AssetValue .. (Stakeholder, Asset)

@enduml
```

Fullying using Class Diagram notations with the link to the link:

![11_b2_1](./Figure11/Figure11_b2_1.png)

### Table 10: Proposed Value Property Overlay

Visualized Schema for Element Value / «Loss» is modeled in JSON format: [Value_Loss.json](./Table10/Value_Loss.json)

## 5.2 Value Chain

### Figure 12: Composition of Value Chain

The Security Overlay also specializes Value into «Value Chain», providing a specific profile for the Strategy elements, Capability and Value Stream.

Detail is to be discussed in [Chapter 6.1](../06_Modeling_Contextual_Security_Architecture/README.md#61-business-assets)

- The key measures of meta-processes are rooted in cost-accounting: production cost, sales prices, and margin.
- The organization seeks to identify which activities generate value and which are inefficient or uneconomic.
- The security perspective is concerned with enhancing and protecting the value of the value generators while containing the costs of the inefficient process.
- The ValueChain stereotype models the breakdown of costs and is, therefore, principally a financial measure.
- The Security Overlay can be used to map the composition of a Value Chain to any behavioral element in the Enterprise Architecture model.

### Value Chain Properties

- The attributes proposed for the Value Chain profile enable the margin to be calculated as the sum of its constituent sub-chains.
- The ArchiMate Specification allows the Value elements to be decomposed into compositions and aggregations of the same type.
- Composition seems the safer option here because, unlike aggregation, it should prevent cost accounting figures from being counted multiple times.

## 5.3 SABSA Business Attributes

### Figure 13: SABSA Business Attributes Represented in the ArchiMate Language

| SABSA | ArchiMate |
| --- | --- |
| **Business Attributes** represent the essential qualities of the Stakeholders' ideal system, to be promoted, protected, and enhanced in the Target Architecture if the enterprise is to deliver its strategy. | **Principle** elements are defined as "an intended property of a system ... a general property that applies to any system in a certain context ... motivated by some goal or driver" |



## 5.4 Meaning

## 5.5 Impact, Threat, Vulnerability, and Risk

## 5.6 Controls: Objectives, Requirements, and Measures

## 5.7 Multi-Teired Security

## 5.8 Regulations and Standards

## 5.9 Articles, Mandates, and Compliance Objectives

## 5.10 Control Mechanisms

## 5.11 Trust

---

[<button type="button">«Chapter 04</button>](../04_Align_SABSA_and_ArchiMate_Framework/README.md) [<button type="button">Chapter 06»</button>](../06_Modeling_Contextual_Security_Architecture/README.md) [<button type="button">HOME</button>](../README.md)

---

Any comments, feel free to post to the [Discussion Board](https://github.com/yasenstar/ArchiMate_SABSA/discussions).