SPDX-License-Identifier: Community-Spec-1.0

# DestroyAction

## Summary

The record of destruction is entered in this action. 

## Description

The action of destroying an element is recorded as part of the DestroyAction. To destroy refers to the act of completely eliminating, or rendering something unusable or irretrievable. 

## Metadata

- name: DestroyAction
- SubclassOf: /Core/Action
- Instantiability: Abstract

## Properties

- actionStartTime
  - type: /Core/DateTime
  - minCount: 1
  - maxCount: 1
- actionEndTime
  - type: /Core/DateTime
  - minCount: 1
  - maxCount: 1
- description
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- destructionPerformedBy
  - type: /Core/Agent
  - minCount: 1

