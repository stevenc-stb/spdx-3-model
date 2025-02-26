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

- description
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- storageLocation 
  - type: /Core/Location
  - minCount: 1
  - maxCount: 1 
