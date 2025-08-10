 Modeling SABSA®
in ArchiMate®

# 00. Preface

## Mission of The Open Group: drive the creation of Boundaryless Information Flow

## The Joint Working Group aims to develop a settled consensus of core security elements, relationships, and properties - referred to collectively as the "Security Overlay".

# 01. Introduction

## 01.01 Background

### SABSA Blue Book (Executive Summary)

## 01.02 The ArchiMate® Specification
 (see:03. Introduction of ArchiMate)
### Figure 1； A Simple ArchiMate Diagram

## 01.03 Purpose

# 02. Rationale for the Alignment of SABSA and ArchiMate

## 02.1 Benefits of Modeling

## 02.2 The Case of an ArchiMate Security Perspective

## 02.3 Benefits that Modeling Can Bring to SABSA

## 02.4 Benefits of Modeling to the Practitioner

## 02.5 Vendor Neutrality

# 03. Introduction of ArchiMate

## 03.1 Core Elements

## 03.2 Core Relationships

## 03.3 Extension Layers and Elements

### 3.3.1 Strategy Layer

### 3.3.2 Motivation Elements

### 3.3.3 Implementation and Migration Layer

### 3.3.4 Composite Elements

## 03.4 ArchiMate Language Customization

### 03.4.1 User-Defined Attributes

### 03.4.2 Specializations and "Stereotypes"

#### Figure 2: In-Model versus Out-of-Model Specialization

### 03.4.3 Overloaded Relationships

## 03.5 The ArchiMate Full Framework

# 04. Aligning SABSA and ArchiMate Framework

## 04.1 Introduction to the Security Overlay

## 04.2 An Overview of the Task

## 04.3 Risk & Security Modeling in the ArchiMate Specification
 (see:05.6 Controls: Objectives, Requirements, and Measures05.10 Control Mechanisms06.2 Business Risk)
### Figure 6: The Risk-Modeling Example in the ArchiMate 3.2 Specification

### Figure 7: Risk Modeling Relationships

### Figure 8: Mapping of Risk and Security Elements

### Figure 9: ArchiMate Motivation Metamodel

## 04.4 The Basic Element and Relationships

# 07. Modeling Conceptual Security Architecture

## 7.0 Conceptual Overview

### Table 28: SABSA Conceptual Architecture

### Figure 37: Developing the SABSA Conceptual Security Architecture

## 7.1 Attribute Profiling

### Figure 38: Attribute Profiling (i)

### Figure 39: Attribute Profiling (ii)

### Figure 40: Attribute Profiling (iii)

### Figure 41: Completed Attribute Profile

## 7.2 Risk Management & Strategy
 (see:04.3 Risk & Security Modeling in the ArchiMate Specification05.5 Impact, Threat, Vulnerability, and Risk)
### 7.2.1 Risk Management

#### Figure 42: Business Risk Analysis Process

### 7.2.2 Policy Architecture

#### Figure 43: Compliance Metamodel

#### Figure 44: An Example Compliance Model

### 7.2.3 Multi-Regulatory Compliance

#### Figure 45: Control Consolidation

#### Figure 46: Possible Duplicate Objectives, Coupled Through Attribute Profile

## 7.3 Conceptual Security Services

### Figure 47: Security Services in the Conceptual Layer

## 7.4 Identity and Trust

### 7.4.1 Identity and Access Rights

#### Figure 48: What the Security Overlay Would Like to Express

#### Figure 49: What the ArchiMate Specification Supports

#### Table 29: Elements used in Logical Access Management

### 7.4.2 Roles and Responsibilities

#### Figure 50: Modeling Identity and Role Concepts

### 7.4.3 Trust

#### Figure 51: Common Examples of Signals Crossing Domain Boundaries

#### Figure 52: Simple Trust Relationships using Flow

#### Figure 53: Trust Attributes Associated with Inter-Domain Signals

#### Table 30: Elements and Relationships used in Trust Modeling

## 7.5 Domain Framework Model

### Table 31: Security Domain Mapping

## 7.6 Security Events

### Table 32: Security Events

# 08. Modeling Logical Security Architecture

## 8.0 Logical Overview

### Table 33: SABSA Logical Architecture

### Figure 54; Developing the SABSA Logical Security Architecture

## 08.1 Information Assets

### 8.1.1 Application Components

#### Figure 55: Critical Applications

### 8.1.2 Security Configuration

### 8.1.3 Software Defects and Malware

### 8.1.4 Data Assets

## 08.2 Risk Modeling

### 8.2.1 Risk Modeling

### 8.2.2 The Scenario

#### Figure 56: Open FAIR™ Example Scenario

#### Figure 57: The Open Fair Risk Taxonomy

#### Figure 58: The Open FAIR Risk Taxonomy Modeled in the ArchiMate Language

#### Figure 59: Qualitative Example from the Open FAIR Risk Analysis Example Guide

#### Figure 60: Quantitative Example from the Open FAIR Risk Analysis Example Guide

## 08.3 Application Functionality and Services

### Figure 61: Application Services

## 08.4 Logical Access Management

### Figure 62: Modeling Authentication in the Primary Architecture

### Figure 63: Example of Registration and Provisioning in the Secondary Architecture

### 8.4.1 Account

### 8.4.2 Application Role

### 8.4.3 Application Service

### 8.4.4 Application Process and Function

### 8.4.5 Application Interface

## 08.5 Logical Domains

## 08.6 Timing and Events

### 8.6.1 Application Security Events

# 09. Modeling Physical Security Architecture

## Figure 64: Developing the SABSA Physical Security Architecture

## 09.1 Data and Technology Assets

### 9.1.1 Artifact

#### 9.1.1.1 Executable

#### 9.1.1.2 Data

#### 9.1.1.3 Configuration

##### Figure 66: Configuration Files

### 9.1.2 Device and Node

#### Figure 67: Stereotyping Security Nodes and Devices

## 09.2 Risk Management Practices

### 9.2.1 Defect

#### Figure 68: Risk Management Practices

## 09.3 Process Mechanisms

### Figure 69: Realization of Security Services

### 9.3.1 Technology Functions and Services

### 9.3.2 System Software

## 09.4 Human-Machine Interfaces

### 9.4.1 Technology Interfaces

## 09.5 Physical Environment

## 09.6 Timing and Interrupts

### 9.6.1 Technology Security Events

# 10. Conclusion

# 05. The Motivation Aspect

## Figure 10: Security Enhanced Motivation Metamodel

## 05.1 Value & Loss

### Figure 11: Modeling Assets using Value

### Table 10: Proposed Value Property Overlay

## 05.2 Value Chain

### Figure 12: Composition of Value Chains

### Table 11: Value Chain Properties

## 05.3 SABSA Business Attributes

### Figure 13: SABSA Business Attributes Represented in the ArchiMate Language

### Table 12: SABSA Attribute Properties

### 5.3.1 Structural Placement of Business Attributes

#### Figure 16: Principle in the ArchiMate Motivation Hierarchy

#### Figure 17: Highlighting the Control Hierarchy Mismatch (i)

#### Figure 18: Highlighting the Control Hierarchy Mismatch (ii)

#### Figure 19: Achieving the Desired Hierarchy

### 5.3.2 Traceability of Business Attributes

#### Figure 20: Attribute Traceability Across Layers

## 05.4 Meaning

### Figure 21: Applying Attribute Metrics to Multiple controls

### Figure 22: Use of Meaning to Externalize Context-Sensitive Metrics

## 05.5 Impact, Threat, Vulnerability, and Risk
 (see:06.2 Business Risk)
### Table 13: Risk Element Properties

## 05.6 Controls: Objectives, Requirements, and Measures

### Figure 23: Expressing Composite Requirements

### Figure 24: Example of a Control Pattern

## 05.7 Multi-Tiered Security

### Table 14: Control Element Properties

### Figure 25: Example of Multi-Tiered Security

## 05.8 Regulations and Standards

### Figure 26: The Structure of Standards and Regulations

### Table 15: Standard and Regulation Properties

## 05.9 Articles, Mandates, and Compliance Objectives

### Figure 27: Articles and Compliance Objectives

### Table 16: Compliance Conceptual Element Properties

## 05.10 Control Mechanisms

### Figure 28: Use Cases and Iconography for Control

### Table 17: Control Properties

## 05.11 Trust

### Table 18: Trust Profile

# 06. Modeling Contextual Security Architecture

## 06.0 Overview

### Table 19: SABSA Contextual Architecture

### Figure 29: Developing and Maintaining the Contextual Security Architecture

### Table 20: Contextual Elements

## 06.1 Business Assets

### 6.1.1 Capability and Value Stream

#### Table 21: The Value Stream Element

#### Figure 30: Value Modeling

### 6.1.2 Business Object

#### Table 22: Business Object Security Properties

#### Figure 31: Element Properties and SABSA Attributes

### 6.1.3 Business Service, Interface, and Service Level Agreements

#### Table 23: Business Service Properties

## 06.2 Business Risk

## 06.3 Business Process/Function/Interaction

### Table 24: Business Behavior Properties

## 06.4 Business Roles and Actors

### Table 25: Actor & Role Properties

### 6.4.1 Governance

#### Figure 32: Representing RACI Relationships

#### Figure 33: Avoid RACI Entanglement

#### Figure 34: Recommended RACI Patterns

#### Table 26: RACI Properties

### 6.4.2 Threat Actors

#### Figure 35: Possibilities for Modeling Threat Actors

#### Figure 36: Sensitivity in the Representation of Threats

#### Table 27: Threat Agent Properties

## 06.5 Business Geography
 (see:7.5 Domain Framework Model)
## 06.6 Business Time Dependencies
 (see:7.6 Security Events)