SPDX-License-Identifier: Community-Spec-1.0

# Cryptography

## Summary

The class represents an instance of the cryptographic systems used. 

## Description

Class that describes a  instance of Cryptography system.
The choice of which specific algorithms to use is made by setting parameters when creating instances of this class.

## Metadata

- name: Cryptography
- SubclassOf: element
- Instantiability: Concrete

## Properties

- cryptographyName
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- parameter
  - type: /Core/DictionaryEntry

