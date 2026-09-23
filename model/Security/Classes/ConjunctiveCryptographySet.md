SPDX-License-Identifier: Community-Spec-1.0

# ConjunctiveCryptographySet

## Summary

Representing a set of CryptographyAlgorithm where all elements apply.

## Description

A ConjunctiveCryptographySet of two or more CryptographyAlgorithm represents a logical grouping of multiple CryptographyAlgorithm instances.
It is represented in the SPDX Cryptography Algorithm List Expression Syntax by the `AND` operator.

## Metadata

- name: ConjunctiveCryptographySet
- SubclassOf: CryptographyAlgorithm
- Instantiability: Concrete

## Properties

- member
  - type: CryptographyAlgorithm
  - minCount: 2
