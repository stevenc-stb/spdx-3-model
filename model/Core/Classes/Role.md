SPDX-License-Identifier: Community-Spec-1.0

# Role

## Summary

A Role defines a specific position or function that an entity plays in the context of a build, system, distribution, supply chain, or lifecycle.

## Description

A Role defines a specific position or function that an entity plays in the context of a build, system, distribution, supply chain, or lifecycle.

## Metadata

- name: Role
- SubclassOf: Element
- Instantiability: Concrete

## Properties

- referenceSpecification
  - type: DefinedType
  - minCount: 0
- roleQualification
  - type: Requirement
  - minCount: 1
- authorization
  - type: xsd:string
  - minCount: 0
- responsibility
  - type: Requirement
  - minCount: 0

## External properties restrictions

- /Core/Element/name
  - minCount: 1
