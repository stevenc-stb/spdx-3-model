SPDX-License-Identifier: Community-Spec-1.0

# Role

## Summary

A Role defines a specific position or function that an entity plays in the context of a build, system, distribution, or lifecycle.

## Description

A Role defines a specific position or function that an entity plays in the context of a build, system, distribution, Supply Chain, or lifecycle. 

## Metadata

- name: Role
- SubclassOf: Element
- Instantiability: Concrete

## Properties

- refDefinition
  - type: DefinedType
  - minCount: 0
- roleQualification
  - type: Requirement
  - minCount: 1
- authority
  - type: xsd:string
  - minCount: 0
- responsibility
  - type: xsd:string
  - minCount: 0
  
## External properties restrictions

- name
  - minCount: 1
