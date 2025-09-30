SPDX-License-Identifier: Community-Spec-1.0

# CryptographyAlgorithm

## Summary

The class represents an instance of the CryptographyAlgorithm used. 

## Description

Class that describes a instance of CryptographyAlgorithm.
The choice of which specific algorithms to use is made by setting parameters when creating instances of this class.

## Metadata

- name: CryptographyAlgorithm
- SubclassOf: /Core/Element
- Instantiability: Concrete

## Properties

- cryptographyName
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- parameter
  - type: /Core/DictionaryEntry

