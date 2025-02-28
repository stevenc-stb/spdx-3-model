SPDX-License-Identifier: Community-Spec-1.0

# StorageAction

## Summary

This is the action of product storage.

## Description

This is the specific action of product storage

## Metadata

- name: StorageAction
- SubclassOf: ModifyAction
- Instantiability: Concrete

## Properties

- storageLocation
  - type: /Core/Location
  - minCount: 1
  - maxCount: 1 

## External properties restrictions

- /Core/Element/description
  - minCount: 1
  - maxCount: 1
