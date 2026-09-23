SPDX-License-Identifier: Community-Spec-1.0

# CryptographyAlgorithmExpression

## Summary

An SPDX Element containing an SPDX Cryptography Algorithm Expression string.

## Description

A CryptographyAlgorithmExpression enables the representation, in a single string, of a
combination of one or more Cryptography Algorithm.

The syntax for a Cryptography Algorithm Expression string is set forth in the corresponding
Annex (["Cryptography Algorithm Expression"] (TODO).
A CryptographyAlgorithmExpression string is not valid if it does not conform to the grammar.

## Metadata

- name: CryptographyAlgorithmExpression
- SubclassOf: CryptographyAlgorithm
- Instantiability: Concrete

## Properties

- cryptographyAlgorithmExpression
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- cryptographyAlgorithmListVersion
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
