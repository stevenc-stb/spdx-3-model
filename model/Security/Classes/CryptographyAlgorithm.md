SPDX-License-Identifier: Community-Spec-1.0

# CryptographyAlgorithm

## Summary

The base class that represents the cryptography algorithm.

## Description

CryptographyAlgorithm is an abstract class that defines a cryptographic algorithm used in SPDX documents.

`providesAlgorithm` reationship  "(From) Element providesAlgorithm (To) CryptographyAlgorithm" during a LifecycleScopeType.
`usedAlgorithm` reationship "(From) Element usedAlgorithm (To) CryptographyAlgorithm during a LifecycleScopeType".
`supportsAlgorithm` reationship "(From) Element supportsAlgorithm (To) CryptographyAlgorithm during LifecycleScopeType.

## Metadata

- name: CryptographyAlgorithm
- SubclassOf: /Core/Element
- Instantiability: Abstract

## Properties

- cryptographicAlgorithmID
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
