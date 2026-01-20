SPDX-License-Identifier: Community-Spec-1.0

# Key

## Summary

Represents a cryptographic key.

## Description

This element describes a specific cryptographic key, identifying its type and associated parameters required for its usage in verification or encryption operations.

## Metadata

- name: Key
- SubclassOf: /Software/File
- Instantiability: Concrete

## Properties

- keyTypeSpecification
  - type: CryptographyAlgorithm
  - minCount: 1
  - maxCount: 1
- keyType
  - type: KeyTypeEnum
  - minCount: 1
  - maxCount: 1
- parameter
  - type: /Core/DictionaryEntry
  - minCount: 0
