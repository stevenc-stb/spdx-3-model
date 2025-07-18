SPDX-License-Identifier: Community-Spec-1.0

# StorageAction

## Summary

Records the storage of a hardware product.

## Description

A StorageAction expresses the actual storage of hardware in a specific location.

## Metadata

- name: StorageAction
- SubclassOf: ModifyAction
- Instantiability: Concrete

## External properties restrictions

- /Core/Element/description
  - minCount: 1

- /Core/Action/actionLocation
  - minCount: 1
