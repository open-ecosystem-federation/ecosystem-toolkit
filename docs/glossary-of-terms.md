# Glossary of Terms

**Version: 0.1.0-beta**

## 1 Introduction

The terms defined herein provide a Common Language for working with the Open Ecosystem Federation Toolkit. Definitions are provided for concepts found within both the technical and governance elements of the Toolkit.

This material is typically more useful for those developing implementations of Ecosystem Toolkit against the Technical Specification or Rules of Engagement or those involved in designing Collaboration Agreements to govern Ecosystems instantiated with the OEF Ecosystem Toolkit.

Service User Manual related material can be found at [TBC].

## 2 Glossary of Terms

### Action Term
The subset of terms within the [Core Ontology](glossary-of-terms#core-ontology) that are associated with an [Administration Protocol](glossary-of-terms#administration-protocol). Whenever the [Owner](glossary-of-terms#owner) writes a [Core Ontology Event](glossary-of-terms#core-ontology-event) containing an Action Term, the [Habitat](glossary-of-terms#habitat) must implement the Administration Protocol that is associated with that term - i.e. the Habitat does exactly what its Owner has asked it to do, in line with the Administration Protocol set out in the Core Ontology.

### Administration
One of the [Responsibilities](glossary-of-terms#responsibilities) that must be deployed to comply with the [Technical Specification](glossary-of-terms#technical-specification), containing the instruction set used to provision and configure the [Habitat](glossary-of-terms#habitat).

### Administration Protocol
The execution of code by a [Habitat](glossary-of-terms#habitat) to deliver core functionality and further configure the Habitat. Administration Protocols are initiated by the writing of their corresponding [Action Term](glossary-of-terms#action-term) by the entity interacting with the Habitat.

### Affordance
The possible actions that entities can take, indicating what [entitlements](glossary-of-terms#entitlement) they have at that point in time and consequently how they may interact with a [Habitat](glossary-of-terms#habitat). Typically revealed to the entity interacting with the habitat through a process of discovery.

### Agent
The role played by a [habitat](glossary-of-terms#habitat) acting on behalf its [Owner](glossary-of-terms#owner) in all its interactions.

### Assertion
The statement of a fact or a belief by an entity. The [Event](glossary-of-terms#event) aims to structure information as assertions, in which the provenance of the assertion is as important as its content. This provides a consistent basis for trust within the fundamental structure of information itself. Most events moving in Ecosystems are assertions.

### Core Ontology
The concepts that are used by the [Technical Specification](glossary-of-terms#technical-specification) to describe the domain of interest comprised of provisioning, instantiating, configuring and operating an [Ecosystem](glossary-of-terms#ecosystem). The concepts are given meaning in that domain by the description of the properties that they hold and the relationships between them.

### Core Ontology Event
An [Event](glossary-of-terms#event) that includes a term from the Core Ontology in its body. A Core Ontology Event therefore describes a facet of the [Administration](glossary-of-terms#administration) and/or configuration of a [Habitat](glossary-of-terms#habitat).

### Domain of interest
A particular field of thought or activity in which one or more entities has an interest.

### Directory
The discovery, identity proofing and certification of entities that have deployed a [Habitat](glossary-of-terms#habitat). The current [Technical Specification](glossary-of-terms#technical-specification) does not include Directory as a required Responsibility, but it represents a potential future extension of scope.

### Ecosystem
A community of entities that collaborate to share information over a common [domain of interest](glossary-of-terms#domain-of-interest) via the deployment of two or more [Habitats](glossary-of-terms#habitat).

### Ecosystem Ontology
The concepts that are used by a given [Ecosystem](glossary-of-terms#ecosystem) to describe the domain of interest that is common to those [Ecosystem Participants](glossary-of-terms#ecosystem-participant).

### Ecosystem Participant
Entities that use the [Ecosystem Toolkit](glossary-of-terms#ecosystem-toolkit) to collaborate. Two or more Participants collaborating together are collectively referred to as an [Ecosystem](glossary-of-terms#ecosystem).

### Ecosystem Toolkit
The collective term for the [Technical Specification](glossary-of-terms#technical-specification) and [Rules of Engagement](glossary-of-terms#rules-of-engagement) which aim to make it easier for entities to collaborate as an [Ecosystem](glossary-of-terms#-ecosystem) through the deployment of repeatable patterns.

### Entitlement
The fact of having a right to something, or having been granted permission to do something.

### Event
A piece of information consistently structured as a machine-readable assertion, including key aspects of of the assertion's provenance as well as its content. Not every Event is an assertion.

### Event Producer
The [Legal Entity](glossary-of-terms#legal-entity) that is responsible for the system acting as a [Feed](glossary-of-terms#feed), and which generates [assertions](glossary-of-terms#assertion) or [signals](glossary-of-terms#signal).

The Event Producer is often the sole [Rights Owner](glossary-of-terms#rights-owner) over the resulting [Assertion](glossary-of-terms#assertion), although this is not always the case. An Event Producer may be operating a [Feed](glossary-of-terms#feed) that has been used to capture an [assertion](glossary-of-terms#assertion) on behalf of another [Rights Owner](glossary-of-terms#rights-owner) (e.g. a customer of the Event Producer).

The [Technical Specification](glossary-of-terms#technical-specification) requires that the Event Producer (or Event Provider if there is no Producer) is identified for every [assertion](glossary-of-terms#assertion).

### Expert System
Machinery (a system comprising architecture and infrastructure) which exists on the IT Estate of an [Ecosystem Participant](glossary-of-terms#ecosystem-participant). This machinery is involved in the deployment of expertise undertaken by the Participant during the course of their day to day business.

### Feed
A system that acts as an external source used to input information into a [Habitat](glossary-of-terms#habitat).

### Governance Framework
Governance frameworks structure and delineate roles within an [Ecosystem](glossary-of-terms#ecosystem), setting rules, procedures, and other informational guidelines, as well as specifying the basis for enforcement. Governance frameworks are shaped by the goals, mandates, incentives, structures and processes of the [Ecosystem Participants](glossary-of-terms#ecosystem-participant) that are seeking to collaborate over a common [domain of interest](glossary-of-terms#domain-of-interest).

### Habitat
A deployment of all the [Responsibilities](glossary-of-terms#responsibilities) required under the [Technical Specification](glossary-of-terms#technical-specification).

### Legal Entity
An individual, company, or organization that has legal rights and obligations.

### Ontology
The definition of the concepts and their relationships that are used to describe a given domain of interest.

### Owner
The owning entity or 'Owner' that deploys and provisions a [habitat](glossary-of-terms#habitat). The Habitat acts on behalf its Owner in all its interactions.

### Participant
See [Ecosystem Participant](glossary-of-terms#ecosystem-participant).

### Protocol
The execution of code by a system (or collection of systems) to deliver given functionality.

### Reasoning Engine
The execution of logic-based reasoning to infer conclusions from a given set of information. The current [Technical Specification](glossary-of-terms#technical-specification) does not include a Reasoning Engine as a required [Responsibility](glossary-of-terms#responsibilities), but it represents a potential future extension of scope.

### Refinery
One of the [Responsibilities](glossary-of-terms#responsibilities) that must be deployed to comply with the [Technical Specification](glossary-of-terms#technical-specification), relating to the transformation of information into a machine-readable representation of an [assertion](glossary-of-terms#assertion).

### Registry
One of the [Responsibilities](glossary-of-terms#responsibilities) that must be deployed to comply with the [Technical Specification](glossary-of-terms#technical-specification), providing a registry of all the 'things' that have been declared as nodes, including the [Ecosystem Participants](glossary-of-terms#ecosystem-participant) that form part of an [Ecosystem](glossary-of-terms#ecosystem) and their associated [entitlements](glossary-of-terms#entitlement).

### Responsibilities
Functional areas of concern that collectively deliver the minimum required to deploy an [Habitat](glossary-of-terms#habitat) support an [Ecosystem](glossary-of-terms#ecosystem).

### Rights Owner
The [Legal Entity](glossary-of-terms#legal-entity) or Entities that exercise rights over the content of an [Assertion](glossary-of-terms#assertion).

The [Technical Specification](glossary-of-terms#technical-specification) requires that any Rights Owner (other than the Event Provider) is identified as part of the structure of an [Assertion](glossary-of-terms#event).

### Rules of Engagement
The document specifying the default [governance framework](glossary-of-terms#governance-framework) that must be deployed in order to collaborate as part of an [Ecosystem](glossary-of-terms#ecosystem).

### Signal
A more precise form of[Assertion](glossary-of-terms#assertion) providing attribute values for concerns such as 'confidence' or 'priority'.

### State machine
A device that stores the status of something at a given time and can operate on input to change the status and/or cause an action or output to take place for any given change.

### Technical Specification
The document specifying the technical considerations that must be deployed in order to implement a [Habitat](glossary-of-terms#habitat).

### Triple
The atomic data structure in the Resource Description Framework (RDF) data model. A triple is a set of three entities that codifies a statement about semantic data in the form of subject–predicate–object expressions (e.g. "Bob is 35", or "Bob knows John").

### Tuple
A data structure consisting of multiple entities. A [Triple](glossary-of-terms#triple) is a Tuple comprising of three entities.
