SPDX-License-Identifier: Community-Spec-1.0

# PlanAction

## Summary

A PlanAction involves the execution of a plan in relation to a PlanProcess.

## Description

A PlanAction involves the execution of a plan in relation to a PlanProcess.

The description of the PlanAction is a mandatory property.
For Each `PlanAction` there is at least one `/Core/Relationship` class or subclass with the relationshipType of 'Generated’ on the to and an `planProcess` class or subclass on the from. 

## Metadata

- name: PlanAction
- SubclassOf: UseAction
- Instantiability: Concrete

## External properties restrictions

- /Core/Element/description
  - minCount: 1
