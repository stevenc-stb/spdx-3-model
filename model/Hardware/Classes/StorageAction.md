SPDX-License-Identifier: Community-Spec-1.0

# StorageAction

## Summary

Records the storage of a hardware product.

## Description

A StoreAction expresses the actual storage of hardware in a specific location.

## Metadata

- name: StorageAction
- SubclassOf: ModifyAction
- Instantiability: Concrete

## Properties

- storageLocation
  - type: /Core/Location
  - minCount: 1

## External properties restrictions

- /Core/Element/description
  - minCount: 1
