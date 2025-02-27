SPDX-License-Identifier: Community-Spec-1.0

# StandardAndSpecifications

## Summary

Standards and specifications are identified in this class.

## Description

Standards and specifications are referenced in this class. Requirements, standards, specification and processes are referenced in this class.

A standard is an agreed-upon set of rules established by industry organizations or regulatory bodies. It ensures uniformity, safety, and compatibility across different systems, products, and services.
A specification (spec) is a detailed document that outlines the exact requirements for a product, process, or system. Specifications are often based on standards but provide more specific details for implementation.


## Metadata

- name: StandardAndSpecifications
- SubclassOf: /Core/Artifact
- Instantiability: Concrete

## Properties

- ExternalIdentifier
  - type: /Core/ExternalIdentifier
  - minCount: 1
- externalRef
  - type: /Core/ExternalRef
    minCount: 1
- releaseTime
  - type: /Core/DateTime
  - minCount: 1
  - maxCount: 1
- originatedBy
  - type: /Core/Agent
  - minCount: 1

