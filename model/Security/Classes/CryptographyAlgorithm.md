SPDX-License-Identifier: Community-Spec-1.0

# CryptographyAlgorithm

## Summary

Specifies a CryptographyAlgorithm and its associated information.

## Description

Specifies a CryptographyAlgorithm and its associated information.

## Metadata

- name: CryptographyAlgorithm
- SubclassOf: /Core/Element
- Instantiability: Concrete

## Properties

- cryptographyName
  - type: CryptographyNameType
  - minCount: 1
  - maxCount: 1
- parameter
  - type: /Core/DictionaryEntry
  - minCount: 0

