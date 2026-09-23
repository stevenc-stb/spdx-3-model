SPDX-License-Identifier: Community-Spec-1.0

# SimpileCryptographyAlgorithm

## Summary

The class that represents the cryptography algorithm. 

## Description

SimpileCryptographyAlgorithm is an class that defines a cryptographic algorithm used in SPDX documents.

 `providesAlgorithm` reationship  "(From) Element providesAlgorithm (To) CryptographyAlgorithm" during a LifecycleScopeType. 
 `usedAlgorithm` reationship "(From) Element usedAlgorithm (To) CryptographyAlgorithm during a LifecycleScopeType". 
 `supportsAlgorithm` reationship "(From) Element supportsAlgorithm (To) CryptographyAlgorithm during LifecycleScopeType. 

## Metadata

- name: SimpileCryptographyAlgorithm
- SubclassOf: /Core/CryptographyAlgorithm
- Instantiability: Abstract

## Properties

- specifiedkeySize
  - type: /Core/PositiveIntegerRange
  - minCount: 0
- cryptoClass
  - type: cryptoClassType
  - minCount: 1
  - maxCount: 1
- cryptoSubClass
  - type: cryptoSubClassType
  - minCount: 0
  - maxCount: 1
- pqcClass
  - type: pqcClassType
  - minCount: 0
  - maxCount: 1
- reference
  - type: xsd:anyURI
  - minCount: 1
- parameter
  - type: /Core/DictionaryEntry
  

