SPDX-License-Identifier: Community-Spec-1.0

# Key

## Summary

Specifies a Cryptography Key and its associated information.

## Description

A cryptography key represents a data object used in encryption, decryption, or authentication processes. It often includes parameters such as the key type, length, algorithm, validity period, and storage location. This entity helps ensure secure communication and data protection by defining standardized handling of key material.

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
  - minCount: 0
  - maxCount: 1
- otherParameter
  - type: /Core/DictionaryEntry
