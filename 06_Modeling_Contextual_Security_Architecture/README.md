# 06 Modeling the Contextual Security Architecture

The SABSA Matrix illustration:

![SABSA Matrix](./img/SABSA-Matrix.png)

_Sourse: https://www.slideshare.net/MVeeraragaloo/sabsa-implementationpart-viver10_

another Matrix view with Lifecycle context:

![SABSA Matrix and Lifecyle](./img/SABSA-Matrix-Lifecycle.png)

_Source: https://www.alctraining.com.sg/course/sabsa-foundation/_

## 6.1 Business Assets

### 6.1.1 Capability and Value Stream

- `Value Stream` is a behavioral element within ArchiMate's Strategy Layer
- A key principle of a `Value Stream` is that its value is always defined from the perspective of the Stakeholder, the consumer of the product, service, or deliverable, and not on its intrinsic value; i.e., the cost of production
- The value of `Value Stream` can be modeled in the ArchiMate language using the `Value` element.

### 6.1.2 Business Object

- `Business Object` represent Information Assets.

### 6.1.3 Business Service, Interface, and Service Level Agreements

- Business Layer services need a distinct property set when they are offered through human interfaces.
- SLA is using `Contract` element, a bespoke `Requirement`/`Constraint` may also be used where a simple property is insufficient.
- `Business Service`s may be offered via multiple interfaces (`Business Interface`)

## 6.2 Business Risk

Risk, threats, vulnerabilities, and opportunities can be modeled at the Business and Strategy level using the orthodox ArchiMate approach discussed in [Chapter 4.3](../04_Align_SABSA_and_ArchiMate_Framework/README.md#43-risk--security-modeling-in-the-archimet-specification)

## 6.3 Business Process/Function/Interaction

## 6.4 Business Roles and Actors

## 6.5 Business Geography

## 6.6 Business Time Dependencies

---

[<button type="button">«Chapter 05</button>](../05_Motivation_Aspect/README.md) [<button type="button">Chapter 07»</button>](../07_Modeling_Conceptual_Security_Architecture/README.md) [<button type="button">HOME</button>](../README.md)

---

Any comments, feel free to post to the [Discussion Board](https://github.com/yasenstar/ArchiMate_SABSA/discussions).