SPDX-License-Identifier: Community-Spec-1.0

# OwnershipChangeProcess

## Summary

The tasks used to change ownership are defined in this process.

## Description

Ownership changes vary by region and ownership definition. The process for changing ownership is defined based on requirements in this process.

## Metadata

- name: OwnershipChangeProcess
- SubclassOf: /Core/DefinedProcess
- Instantiability: Concrete

## Properties

- plannedBuyer
  - type: /Core/Agent
  - minCount: 0
  - maxCount: 1
- plannedSeller
  - type: /Core/Agent
  - minCount: 0
  - maxCount: 1
- plannedProductofOwnershipChange
  - type: /Core/Element
  - minCount: 0
