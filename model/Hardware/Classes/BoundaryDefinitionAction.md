SPDX-License-Identifier: Community-Spec-1.0

# BoundaryDefinitionAction

## Summary

The boundary definition is used to define boundaries.

## Description

Boundaries can be physical or abstract. This is the act of defining the boundaries. 

This class must have: 
For Each ‘Boundary Definition Action’ there is one and only one `/Core/Relationship` class or subclass with the relationshipType of 'Creator’ on the to and an `/Core/Agent` class or subclass on the from. 

## Metadata

- name: BoundaryDefinitionAction
- SubclassOf: /Core/Action
- Instantiability: Concrete

## Properties

- description
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- boundaryParameters
  - type: /Core/DictionaryEntry
  - minCount: 1
  - maxCount: 1
