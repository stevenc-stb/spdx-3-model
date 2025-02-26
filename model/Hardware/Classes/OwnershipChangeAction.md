SPDX-License-Identifier: Community-Spec-1.0

# OwnershipChangeAction

## Summary

Ownership changes are recorded in this action.

## Description

Changes of ownership are recorded in this action based on the ownership change process.

## Metadata

- name: OwnershipChangeAction
- SubclassOf: /Core/Action
- Instantiability: Concrete

## Properties

- actionStartTime
  - type: /Core/DateTime
  - minCount: 1
  - maxCount: 1
- actionEndTime
  - type: /Core/DateTime
  - minCount: 1
  - maxCount: 1
- buyer
  - type: /Core/Agent
  - minCount: 1
  - maxCount: 1
- seller
  - type: /Core/Agent
  - minCount: 0
  - maxCount: 1
- ownershipChangedOnProduct
 - type: /Core/Element
 - minCount: 1

