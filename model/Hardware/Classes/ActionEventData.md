SPDX-License-Identifier: Community-Spec-1.0

# ActionEventData

## Summary

Action event data refers to the additional information captured when an action event occurs.

## Description

Action event data refers to the additional information captured when an action event occurs. It can include details about the event, what happened, when it happened, and what data was involved.

For Each `ActionEventData` there is only one `/Core/Relationship` class or subclass class with the relationshipType of 'contains’ on the to and an `/Core/Action` class or subclass on the from. 

## Metadata

- name: ActionEventData
- SubclassOf: /Core/Artifact
- Instantiability: Concrete

## Properties

- userData
  - type: xsd:string

