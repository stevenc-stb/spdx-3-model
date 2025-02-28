SPDX-License-Identifier: Community-Spec-1.0

# OwnershipChangeAction

## Summary

Ownership changes are recorded in this action.

## Description

Changes of ownership are recorded in this action. Ownership Change refers to the transfer of rights, responsibilities, and control of an asset, property, business, or entity from one party to another. This change can occur in various contexts, including real estate, business acquisitions, intellectual property, and personal assets.

## Metadata

- name: OwnershipChangeAction
- SubclassOf: /Core/Action
- Instantiability: Concrete

## Properties

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

## External properties restrictions

- actionStartTime
  - minCount: 1
  - maxCount: 1
- actionEndTime
  - minCount: 1
  - maxCount: 1
