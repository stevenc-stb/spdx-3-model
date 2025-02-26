SPDX-License-Identifier: Community-Spec-1.0

# StateAction

## Summary

This is the state of an affected element. 

## Description

The state of a specific element is defined in this class.The state of an object refers to the set of attributes, properties, or data that define the object's condition at a specific moment in time.
Relationship: 
For Each `ResolutionAction` there is at least one `/Core/Relationship` class or subclass with the relationshipType of 'resolution’ on the from and an `OutOfSpecAction` class or subclass on the to. 

## Metadata

- name: StateAction
- SubclassOf: UseAction
- Instantiability: Concrete

## Properties

- description
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- objectState
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
