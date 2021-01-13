# Glossary of Terms

**Version: 0.1.0-beta**

# 1 Introduction

The terms defined herein provide a Common Language for working with the Open Ecosystem Federation Toolkit. Definitions are provided for concepts found within both the technical and governance elements of the Toolkit.

This material is typically more useful for those developing implementations of Ecosystem Toolkit against the Technical Specification or Rules of Engagement or those involved in designing Collaboration Agreements to govern Ecosystems instantiated with the OEF Ecosystem Toolkit.

Service User Manual related material can be found at [TBC].

# 2 Glossary of Terms

## Action Term
The subset of terms within the [Core Ontology](glossary-of-terms#core-ontology) that are associated with an [Administration Protocol](glossary-of-terms#administration-protocol). Whenever the [Owner](glossary-of-terms#owner) writes a [Core Ontology Event](glossary-of-terms#core-ontology-event) containing an Action Term, the [Habitat](glossary-of-terms#habitat) must implement the Administration Protocol that is associated with that term - i.e. the Habitat does exactly what its Owner has asked it to do, in line with the Administration Protocol set out in the Core Ontology.

## Administration
One of the [Responsibilities](glossary-of-terms#responsibilities) that must be deployed to comply with the [Technical Specification](glossary-of-terms#technical-specification), containing the instruction set used to provision and configure the [Habitat](glossary-of-terms#habitat).

## Administration Protocol
The execution of code by a [Habitat](glossary-of-terms#habitat) to deliver core functionality and further configure the Habitat. Administration Protocols are initiated by the writing of their corresponding [Action Term](glossary-of-terms#action-term) by the entity interacting with the Habitat.

## Core Ontology
The concepts that are used by the [Technical Specification](glossary-of-terms#technical-specification) to describe the domain of interest comprised of provisioning, instantiating, configuring and operating an [Ecosystem](glossary-of-terms#ecosystem). The concepts are given meaning in that domain by the description of the properties that they hold and the relationships between them.

## Core Ontology Event
An [Event](glossary-of-terms#event) that includes a term from the Core Ontology in its body. A Core Ontology Event therefore describes a facet of the [Administration](glossary-of-terms#administration) and/or configuration of a [Habitat](glossary-of-terms#habitat).

## Domain of interest
A particular field of thought or activity in which one or more entities has an interest.

## Ecosystem
A community of entities that collaborate to share information over a common [domain of interest](glossary-of-terms#domain-of-interest) via the deployment of two or more [Habitats](glossary-of-terms#habitat).

## Event
A piece of information consistently structured as a machine-readable assertion, including key aspects of of the assertion's provenance as well as its content.

## Habitat
A deployment of all the [Responsibilities](glossary-of-terms#responsibilities) required under the [Technical Specification](glossary-of-terms#technical-specification).

## Responsibilities
Functional areas of concern that collectively deliver the minimum required to deploy an [Habitat](glossary-of-terms#habitat) support an [Ecosystem](glossary-of-terms#ecosystem).

## Technical Specification
The document specifying the technical considerations that must be deployed in order to implement a [Habitat](glossary-of-terms#habitat).
