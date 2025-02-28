SPDX-License-Identifier: Community-Spec-1.0

# UseProcess

## Summary

Use Process defines actions used by elements.

## Description

The UseProcess is an abstract class used to define processes that interact with key elements. Plan, state, and inspection processes plus managing boundaries are critical processes used by elements.
For Each `CreationProcess` or subclass except the`planProcess` there is at least one `/Core/Relationship` class or subclass with the relationshipType of 'effected’ on the from and an `/Core/Element` class or subclass on the to. 

## Metadata

- name: UseProcess
- SubclassOf: /Core/DefinedProcess
- Instantiability: Abstract

## External properties restrictions

- description
  - minCount: 1
  - maxCount: 1
