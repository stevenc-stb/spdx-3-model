SPDX-License-Identifier: Community-Spec-1.0

# ListedCryptographyAlgorithm

## Summary

The class that represents the cryptography algorithm that is found in the cryptographic algorithm list.

## Description

ListedCryptographyAlgorithm is an class that defines a cryptographic algorithm used in SPDX documents.

`providesAlgorithm` reationship  "(From) Element providesAlgorithm (To) CryptographyAlgorithm" during a LifecycleScopeType.
`usedAlgorithm` reationship "(From) Element usedAlgorithm (To) CryptographyAlgorithm during a LifecycleScopeType".
`supportsAlgorithm` reationship "(From) Element supportsAlgorithm (To) CryptographyAlgorithm during LifecycleScopeType.

## Metadata

- name: ListedCryptographyAlgorithm
- SubclassOf: SimpileCryptographyAlgorithm
- Instantiability: Concrete

## Properties

- algorithmExpressionListVersion
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
