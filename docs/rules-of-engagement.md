# Rules of Engagement

**Version: 0.1.0-beta**

## Table of Contents

* [1 Introduction](rules-of-engagement#1-introduction)
* [2 Rules of Engagement](rules-of-engagement#2-rules-of-engagement)
  * [2.1 Principles](rules-of-engagement#21-principles)
  * [2.2 Default Configuration of Permissions / Entitlements](rules-of-engagement#22-default-configuration-of-permissions--entitlements)
  * [2.3 Default Governance Framework](rules-of-engagement#23-default-governance-framework)
* [3 Ecosystem Governance](rules-of-engagement#3-ecosystem-governance)
  * [3.1 Legal Instrumentation](rules-of-engagement#31-legal-instrumentation)
  * [3.2 Components](rules-of-engagement#32-components)
    * [3.2.1 Legal Basis](rules-of-engagement#321-legal-basis)
    * [3.2.2 Liability Framework](rules-of-engagement#322-liability-framework)
    * [3.2.3 Assurance Framework](rules-of-engagement#323-assurance-framework)
    * [3.2.4 Issue Resolution](rules-of-engagement#324-issue-resolution)
    * [3.2.5 Terms of Service](rules-of-engagement#325-terms-of-service)
    * [3.2.6 Scope of Service](rules-of-engagement#326-scope-of-service)
    * [3.2.7 Ecosystem Intent](rules-of-engagement#327-ecosystem-intent)
    * [3.2.8 Membership Administration](rules-of-engagement#328-membership-administration)
    * [3.2.9 Value Exchange Framework](rules-of-engagement#329-value-exchange-framework)
    * [3.2.10 Settlement Framework](rules-of-engagement#3210-settlement-framework)
* [Appendix](rules-of-engagement#Appendix)
  * [Bilateral Contract](rules-of-engagement#bilateral-contract)
  * [Scheme](rules-of-engagement#scheme)

## 1 Introduction

The Rules of Engagement (RoE) are designed to allow separate entities to agree and execute a repeatable, scalable and extensible model for collaboration to enable the sharing of information and expertise.

The RoE are one part of a Toolkit comprising of two parts:

* A Technical Specification (TODO: link provided soon) that is based on open standards and provides functionality to enable the _execution_ of scalable and extensible collaboration
* This **Rules of Engagement** document which is a default governance framework that facilitates the _agreement_ required for scalable, extensible and repeatable collaboration

This document both defines the RoE and sets out how Ecosystem Participants can use the Technical Specification to reference governance frameworks that go beyond the RoE. In this way, each Ecosystem can combine the Technical Specification with their own governance framework.

## 2 Rules of Engagement

### 2.1 Principles

Both the Technical Specification and RoE **must** be considered a minimum set of requirements. Entities that comply with this minimum set of requirements are referred to as Ecosystem Participants.

Pairs and/or groups of Ecosystem Participants **may** collaborate to share information in a given domain of interest by using the functionality defined in the Technical Specification and by adhering to the RoE.

Pairs and/or groups of Ecosystem Participants **may** also collaborate on a _mutually agreed_ basis by opting to use a governance framework that goes _beyond_ the RoE. Such pairings or groupings are referred to as Ecosystems.

Any Ecosystem Participant **may** initiate an Ecosystem. Potential Ecosystem Participants **must** be invited to join a given Ecosystem and may collaborate within the ecosystem once they additionally make a decision to opt in. These commitments are recorded as Events using implementations of the Technical Specification.

By definition, a given Ecosystem excludes all Participants which either choose not to opt in or are not invited to join. The rationale for exclusion can be opaque: they may be unable to meet the incremental requirements set out in the Ecosystem's governance framework, be unaware of its existence, be unwilling to join it or are simply not invited.

Whenever Ecosystem Participants share information, they **must** record the governance framework under which the transaction is occurring (although it is important to note that this record might not be something that is replayed with every transaction - for example, an Ecosystem Participant may specify that it is universally acting under a given governance framework for a given period of time):
* When information is being shared under the RoE, a set of [minimum requirements](rules-of-engagement#minimum-requirements) is assumed to apply.
* When information is being shared under a governance framework that goes beyond the RoE, Ecosystem Participants must reference artefacts which collectively comprise that Ecosystem Governance.

Whenever Participants form an Ecosystem that references a governance framework that goes beyond the RoE, they **must** take responsibility for monitoring and enforcing compliance with that governance framework (e.g. through systems for issue identification, escalation, resolution, remediation, etc.).

It is **best practice** for 'open' Ecosystems (e.g. market places, extended supply chains) to make the reference to such artefacts public to all other Ecosystem Participants.

'Open' Ecosystems **must** configure such artefacts in terms of standardised models, [component parts](rules-of-engagement#32-components) and easily accessible, repeatable patterns.  These component parts must separate concerns and break granularity down to the level necessary to provision for 'policy as code'.  Simply put, everything which can be separated out and configured/considered independently **must** be separated out and defined either as data or code in an implementation of the Technical Specification.

These **best practices** are designed to lower barriers to entry into a given Ecosystem. However, the Ecosystem Toolkit does not preclude or prejudice against 'closed' Ecosystems (e.g. collaborations based on statutory or regulatory requirements). There is no requirement to make the reference governance artefacts public to other Participants beyond those already party to the Ecosystem, or to use any particular form of governance.

### 2.2 Default Configuration of Permissions / Entitlements

The default configuration of the Technical Specification is to permit / entitle Ecosystem Participants to _write_ Events, but not to _read_ events. It is assumed that this default configuration complies with the vast majority of laws and regulations (i.e. everyone is entitled to write down what they think, if those thoughts remain inaccessible to everyone) and would be considered to constitute security best practice.

Ecosystem Participants are responsible for ensuring that permissions / entitlements that extend beyond the default configuration continue to comply with all the national and international laws and regulations that are relevant to them.

In its fundamental structure, every Event includes a reference to the rights owner(s) on whose behalf the Event has been written. A rights owner is referred to as an Event Producer. In most cases, the Ecosystem Participant will be the sole Event Producer. In others, the Ecosystem Participant may be writing Events on behalf of another rights owner. In this situation, the Ecosystem Participant will be playing the role of Event Provider.

When acting in the role of Event Producer, Ecosystem Participants can _write_ their own Events, including Events that actively _grant permission_ to themselves - or any other Ecosystem Participant - to _read_ any other Event. In the same role, Ecosystem Participants can also _remove permission_ to read any given Event from any given Ecosystem Participant (including themselves) at any given time. Such permissions are also referred to as entitlements.

When writing Events on behalf of other rights owners (i.e. acting as an Event Provider), Ecosystem Participants cannot grant or remove permissions / entitlements over these Events. Ecosystem Participants are therefore responsible for:
* identifying rights owners
* providing rights owners with a service that allows them to configure permissions / entitlements over their Events
* authenticating rights owners

The legal and regulatory context in which each Ecosystem Participant operates will be specific to them and their domain of interest. Every Ecosystem Participant is responsible for the configuration of permissions / entitlements that comply with their specific legal and regulatory context.

The Technical Specification only provides a toolkit which enables permissions / entitlements for each individual Event to be configured in an easily _extensible_ way, and to be executed in a highly _scalable_ and _machine-readable_ environment.

### 2.3 Default Governance Framework

Whenever Ecosystem Participants share information under the Ecosystem RoE, a default governance framework **must** always apply:

* The default legal basis on which Ecosystem Participants share information is "consent" - i.e. the Ecosystem Participant is acting _on behalf of_ the entities that act as Rights Owner(s) over the information being shared to configure permissions / entitlements according to their _active instruction_ (as recorded by a further set of Events)

* The default liability limit under which other Ecosystem Participants access the Events being shared is zero - i.e. Ecosystem Participants rely on the information that they access at their own risk.

* The default assurance level of the events contributed by Ecosystem Participants is zero - i.e. the default expectation is that other Ecosystem Participants may choose the level of trustability they read into the information exchange, and may consider the information they are consuming on a spectrum of utility.  Although the Technical Specification assures the _provenance_ of Events, the RoE does not by default assure the _quality_ of the information contained in Events.

* The default legal instrument under which Ecosystem Participants share information is the general body of national and international law and regulation that is relevant to each Ecosystem Participant. The RoE do not assume the existence of any other construct (such as a contract, memorandum of understanding, letter of intent, etc.) between the parties that might act as a further point of reference in the eyes of the legal or regulatory authorities.

* The default enforcement mechanisms are the general enforcement mechanisms provided by national and international legal and regulatory authorities (such as the courts, ombudsman, arbitration panels, channels for complaints, etc.). The RoE does not assume the existence of any incremental and mutually agreed systems for issue identification, escalation, resolution, remediation, etc.

* The default motivation for sharing information is altruism (i.e. acting for the greater good). The RoE does not assume any requirement for reciprocal value to be exchanged in return for the act of sharing information. As a result, the default value placed on the information being shared is zero, and therefore the RoE does not assume the need for any value settlement framework (beyond that of psychic reward).

Collectively and exhaustively, these components comprise the default governance framework that constitutes the RoE. This is the default artefact that is referenced by the Technical Specification.

## 3 Ecosystem Governance

By design, the RoE aim to set out a minimal basis under which information is exchanged. It is therefore desirable for Ecosystems to collaborate on the basis of governance frameworks that are tailored to their specific context. These frameworks are referred to as Ecosystem Governance.

When information is being shared under a governance framework that goes _beyond_ the RoE, Ecosystem Participants **must** reference legal instrumentation which collectively comprise that Ecosystem Governance and establishes the legal basis under which the transaction is occurring (see [Sections 3.1](rules-of-engagement#31-legal-instrumentation) and [Section 3.2.1](rules-of-engagement#321-legal-basis) below).

The RoE enforces a default legal basis of consent, but does not seek to define the governance frameworks that are appropriate for any given Ecosystem. Rather, its goal is help to associate the governance framework under which information is shared with the information itself, as a way of supporting the collaboration between the Ecosystem Participants that comprise the Ecosystem.

It is best practice for Ecosystems to use governance frameworks that are composed of artefacts which - over time - may become standardised points of reference for other Ecosystems. This facilitates the _agreement_ required for repeatable, scalable and extensible collaboration, making it easier for Ecosystem Participants both to join existing Ecosystems and to initiate their own.

In this section, we consider two aspects of a given governance framework: firstly, we point to the spectrum of different legal instruments that might be used to define a governance framework; secondly, we highlight some of the different dimensions of governance that may be covered by such instrumentation and which collectively compose the governance framework itself.

We recognise that neither constitutes a comprehensive or definitive set, and can only act as an initial hypothesis for the "composability" of Ecosystem Governance. The intention is for the Open Ecosystem Federation (OEF) to test this hypothesis in a Beta Project, by using the Technical Specification to reference a legally enforceable governance framework that uses a collaboration agreement based on the default setting contained in the Rules of Engagement and extending across the components set out below.

### 3.1 Legal Instrumentation

There are a number of legal bases on which governance frameworks can be constructed. Taking the EU's General Data Protection Regulation (GDPR) as an example, there are six lawful bases for processing personal data: consent, contract, legal obligation, vital interests, public task and legitimate interests.

It is expected that the majority of Ecosystems that rely on a legal basis that goes beyond the default of consent set out in the RoE will do so under contract. The precise nature of the contract used to articulate a given Ecosystem Governance model may vary. For example, it is easy to identify at least three such variants:

* [Bilateral contract](rules-of-engagement#bilateral-contract)
* Multilateral [collaboration agreement](rules-of-engagement#collaboration-agreement)
* Bilateral contracts with a legal entity tasked with operating a [scheme](rules-of-engagement#scheme)

Given the expected use of a contract in the form of a collaboration agreement to suppport the Beta phase, we use this section to focus on this particular variant of legal instrumentation. The [Appendix](rules-of-engagement#appendix) elaborates further on contracts organised bilaterally or as a scheme.

A collaboration agreement is a contract that covers multiple data services and uses, using template annexes to reflect any incremental dimension of governance that is specific to a particular data service and/or use.

The collaboration agreement governs the information exchange between _several_ Ecosystem Participants acting as Event Providers and _several_ Ecosystem Participants acting as Event Consumers, all of whom choose to submit to the terms which it contains.

A collaboration agreement therefore provides a common artefact which can be referenced by all the Ecosystem Participants - in other words, unlike a master service agreement, it is a multilateral agreement. The collaboration agreement may include the constitution of administrative roles and mechanisms to support the evolution of the agreement itself over time ([see Section 3.2.7](rules-of-engagement#327-membership-administration)).

**_Figure 1: Collaboration Agreement_**

![Collaboration Agreement](https://raw.githubusercontent.com/open-ecosystem-federation/ecosystem-toolkit/develop/assets/img/collaboration-agreement.png)
_[Source: Pinsent Masons]_

As the name suggests, collaboration agreements are likely to be best suited to ecosystems where the participants are actively looking to collaborate with one another to streamline the mechanisms through which agreement can be reached to share information.

It is best practice to reference an open and standard artefact as the legal basis for collaboration. For example:
* Where an Ecosystem Participant is making information available to all other Ecosystem Participants (e.g. as 'open data'), they may reference the terms of an open and standard licence.
* Where Ecosystem Participants share information multilaterally, they may invite others to participate under the terms of an open and standard collaboration agreement.

It is still possible for Event Providers to compete to provide data services to Event Consumers under the terms of a collaboration agreement. However, they have agreed to do so under a common governance framework.  

### 3.2 Components

This section elaborates a non-exhaustive list of the different dimensions that Ecosystems might use to compose the governance framework under which they have mutually agreed to collaborate. These dimensions might be captured in a form of legal instrumentation (such as the examples in the section above), which in turn can then be referenced as the basis for information sharing via implementations of the Technical Specification.

#### 3.2.1 Legal Basis

Ecosystems **may** share information on a legal basis that is different from the legal basis of "consent" that is the default under the RoE.

Taking the EU's General Data Protection Regulation (GDPR) as an example, there are six lawful bases for processing personal data: consent, contract, legal obligation, vital interests, public task and legitimate interests.  

When personal data is involved, the GDPR imposes a high duty of care upon data controllers in selecting their data processing service providers. This duty of care may be reflected in specific clauses within the legal instrumentation used to set out Ecosystem Governance.

#### 3.2.2 Liability Framework

Ecosystems **may** choose to accept a level of liability linked to the quality of the information being shared that is greater than the level of zero that is the default under the RoE.

Ecosystem Governance that includes a liability framework (linked to data quality standards and assurance levels) gives those Ecosystem Participants a basis for recourse if they rely on the information being shared.

#### 3.2.3 Assurance Framework

Ecosystems **may** choose to specify a level of assurance over the quality of information on specific events that is greater than the level of zero that is the default under the RoE.

The Technical Specification enforces a level of assurance as to the _lineage_ or _provenance_ of information. However, it does not impose or generate any level of assurance about the _quality_ of the information being shared - it may range from well formed but nonsensical to highly refined insight.  Assurance framework specifics will depend on the context of the types of information exchange present in an ecosystem and the domains and subdomains over which the participants are intersecting.

#### 3.2.4 Issue Resolution

Issue resolution mechanisms are closely linked to liability and assurance frameworks. These **may** involve mutually agreed procedures to identify, remediate and resolve issues, as well as sanctions for ecosystem members that fail to observe them (e.g. expulsion from the ecosystem).

#### 3.2.5 Terms of Service

Ecosystem Participants **may** use an implementation of the Technical Specification to reference terms of service that cannot (yet) be expressed within the ontology. These might include service levels, feedback loops, revocation rights, etc.

For example, Ecosystems **may** choose to specify a service model that is designed to encourage members to behave as good ecosystem "citizens" and to minimise the need for escalation of issues by alerting Event Providers to issues with their data service on the basis that the Event Provider will use the feedback to address the issues - and improve data services - in a timely manner.

#### 3.2.6 Scope of Service

The default scope of service within the Technical Specification is the provision of access to write information in the form of Events. The Technical Specification defines the service via its core administration responsibilities and ontology.

Ecosystem Participants **may** expand the administrative responsibilities and ontology to express key features of this service (such as time-to-live, access expiry, etc.) and to express an expansion of the scope of service (such as mirroring, notifications, etc.).

#### 3.2.7 Ecosystem Intent

Ecosystem Participants **may** use an implementation of the Technical Specification to reference a mechanism that defines the intent of a given Ecosystem, beyond the immediate transaction involved in sharing information.

For example, intent may be used to capture what is expected of the members of the Ecosystem, what good reciprocation looks like, how common interests are protected, etc.

#### 3.2.8 Membership Administration

An Ecosystem **may** use an implementation of the Technical Specification to reference artefacts used to administer its membership. Such artefacts might include (but are not limited to):  

* The _people_ or _entities_ responsible for administration. For example, an Ecosystem operating under a collaboration agreement may appoint a 'Steward' to be responsible for maintaining the agreement and administering the process of members signing up to it
* The _policies_ used to determine membership. For example, an Ecosystem comprises of members of a given club: to become a member of the club, parties must be recommended by at least one other member.
* The _mechanisms_ or _tools_ used to assign or revoke the attributes or characteristics required to participate in an Ecosystem. For example, the process for administering membership is handled using Github and Github accounts.  

#### 3.2.9 Value Exchange Framework

The default motivation for sharing information is altruism. The default value placed on the information being shared is therefore zero.

Ecosystem Participants **may** use an implementation of the Technical Specification to reference a value on the information being shared that is greater than the default value of zero that is the basis for the RoE.

Access to the information within that Ecosystem will then be contingent on settlement to that value. Best practice is to reference open and standard values (such as currency-based prices) to minimise barriers to entry.

#### 3.2.10 Settlement Framework

The default reward for those sharing information or expertise within ecosystems is "psychic reward" therefore unless configured otherwise via a Collaboration Agreement there is no value settlement framework in place.

Ecosystem Participants **may** use an implementation of the Technical Specification to reference a value settlement framework that is different to the default settlement framework that is the basis for the RoE.

Best practice is to reference open and standard settlement frameworks (such as currency-based payment schemes) to minimise barriers to entry.

## Appendix

### Bilateral Contract

The second example of legal instrumentation is that of a bilateral contract between an Ecosystem Participant acting in the role of Event Provider and another Ecosystem Participant acting in the role of Event Consumer. The contract specifies the terms under which the Event Provider makes a given data service available to the Event Consumer for a given purpose or use.

The Ecosystem Participants use their respective implementations of the Technical Specification to reference the relevant contract as the primary artefact which describes the governance framework under which the information (in the form of Events) is being shared, as illustrated in Figure 1.

**_Figure 2: Bilateral Contracts between Event Providers and Event Consumers_**

![Bilateral Contract](https://raw.githubusercontent.com/open-ecosystem-federation/ecosystem-toolkit/develop/assets/img/bilateral-contract.png)
_[Source: Pinsent Masons]_

Contractual arrangements like this may be best suited to competitive ecosystems (e.g. markets) where different Event Providers compete to offer a range of data services. In such an environment, there may be competitive advantage in using a single contract that covers multiple data services and uses (e.g. a master service agreement).

### Scheme

The third example of legal instrumentation is that of a scheme. Each Ecosystem Participant that opts to join an Ecosystem governed by a scheme signs a bilateral contract with the legal entity that is tasked with operating that scheme.

Schemes are often used to mutualise the costs and risks inherent in sharing information. The existence of the legal entity dedicated to operating the scheme provides a vehicle for shared operations (such as dispute resolution and scheme administration) and shared risk management (such as access to balance sheet strength).

**_Figure 3: Scheme_**

![Scheme](https://raw.githubusercontent.com/open-ecosystem-federation/ecosystem-toolkit/develop/assets/img/scheme.png)
_[Source: Pinsent Masons]_

Schemes provide the governance framework for many ecosystems already operating today, and the key properties of a scheme are desirable in many contexts. However, schemes can also have properties that make them undesirable in other contexts:

* Schemes can result in high barriers to entry into the ecosystem, leading to anti-competitive behaviour
* Schemes are usually very specialised in terms of the data services and uses in scope
* Schemes risk becoming 'gold-plated' and/or 'outdated' as the legal entity that operates is required to play an intermediary role but is constrained in its ability to innovate the way it executes that role

Although schemes provide an entirely valid governance framework for any Ecosystem, schemes that hold these properties work _against_ the primary objectives of the RoE (i.e. to agree and execute a _scalable_ and _extensible_ model for collaboration through the sharing of information).
