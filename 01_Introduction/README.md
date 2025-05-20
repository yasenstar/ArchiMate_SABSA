# 01 Introduction

## 01.0 Opening Question

One first questions from [alidayani](https://github.com/alidayani) in Discussion Board, responding the modeling challenge, are

- why ArchiMate® for security architect, why not other models? and
- why set apart SABSA® architect with normal one?

In [Chapter 3](../03_Introduction_of_ArchiMate/README.md), we'll look at overall landscape of ArchiMate®, but here we may try to put some historical evolvement of OpenGroup so setting the scene:

1. TOGAF was developed from OpenGroup from Enterprise Architecture and for Enterprise Architects
2. The definition of "Enterprise Architecture" and in the lifecyle of the phases A to F, with Change Mangement in the center.
3. To answer the needs of modeling EA complying TOGAF, ArchiMate was introduced, and was commonly grouped in horizontal and vertical matrix in the industry
4. From top to bottom of horizontal - not meaning the prioritization, just placement - Business Architecture, Application Architecture, Technology Architecture - as core
5. Vertical crossing above layers called Solution Architecture, which is not explicitly visible in ArchiMate
6. ArchiMate is not one "dead" standard, it's keep evolving, and adding more context like Strategy, Motivation, Implementation & Migration
7. Expanding certain layers are also possible, like adding more notation in Technology Layer to model manufacturing enterprise with Physical Architecture meaning
8. ArchiMate community has long opened discussion thread about how ArchiMate to cope with data modeling, since there's no clear Inforemation Architecture layer there

Now, come to our Security Architecture, we should respect first that there're lots of architect roles in the world, sitting not only in IT side but also business side, ArchiMate is now only cover part of those context, but as one modeling language, it is really capable to extend in necessity.

So, you don't see Security Architecture layer in ArchiMate, doesn't means ArchiMate (or TOGAF, or OpenGroup) forgot Security Architects role, that's exactly similar like Information Architecture, means we may not yet find one common-accepted and easy adopted way to adding some more notations. However, keep in mind, the scope of "Enterprise Architecture" is "the Enterprise", so definitely, Security Architecture is in the scope of overall EA.

Then we can recap the purpose of this document, which are from the guide:

- "This document discusses how security architecture concepts can be expressed using The Open Group ArchiMate® modeling language."
- "This document describes a model-based approach for creating SABSA® artifacts using ArchiMate notation and tooling."
- "The integration of security into Enterprise Architecture methodologies, through the alignment of SABSA® concepts with the Zachman Framework™, the TOGAF® Standard, and other popular frameworks, has been established for several years." -- positive side
- "In practice, however, the lack of native support for security concepts in Enterprise Architecture modeling notations (and therefore tools and processes) has placed security architects at a disadvantage to their architectural peers." -- negative side

Why not other models? Not limited, you're freely to choose any other models or modeling language to perform your work, as long as you and your colleague, your stakeholders and your partners have those as common language.

## 01.1 Background

If you look for "Information Security Framework" via any search engine, you may get following, but not limited, list of the IT security standards and frameworks:

- ISO 27001 series
- NIST SP 800-53
- NIST SP 800-171
- NIST CSF
- NIST SP 1800 series
- COBIT (from ISACA)
- CIS Controls
- HITRUST Common Security Framework
- GDPR
- COSO
- FISMA
- NERC CIP

Searching "Top Security Frameworks used by CISOs in 2025", got below 5 ones:

- NIST Cybersecurity Framework (CSF 2.0)
- ISO/IEC 27001
- CIS Controls (Version 8)
- Zero Trust Architecture
- Factor Analysis of Information Risk (FAIR)

Interesting is I found SABSA is not popular as I expected, from another point of view, that's also meaning there're quite a lot of work need to communicate SABSA to the broader audience, even to the CISOs group as well.

---

Any comments are welcome, feel free to raise pull-request or post in Discussion Board