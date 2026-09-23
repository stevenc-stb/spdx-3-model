SPDX-License-Identifier: Community-Spec-1.0

# CustomCryptographyAlgorithm

## Summary

The class that represents the cryptography algorithm that is `NOT` found in the cryptographic algorithm list.

## Description

CustomCryptographyAlgorithm that represents the cryptography algorithm that is `NOT` found in the cryptographic algorithm list. 

`providesAlgorithm` reationship  "(From) Element providesAlgorithm (To) CryptographyAlgorithm" during a LifecycleScopeType.
`usedAlgorithm` reationship "(From) Element usedAlgorithm (To) CryptographyAlgorithm during a LifecycleScopeType".
`supportsAlgorithm` reationship "(From) Element supportsAlgorithm (To) CryptographyAlgorithm during LifecycleScopeType.

## Metadata

- name: CustomCryptographyAlgorithm
- SubclassOf: SimpileCryptographyAlgorithm
- Instantiability: Concrete

## External properties restrictions

- /Security/CryptographyAlgorithm/cryptographicAlgorithmID
  - minCount: 0
