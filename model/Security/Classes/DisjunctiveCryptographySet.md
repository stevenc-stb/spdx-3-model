SPDX-License-Identifier: Community-Spec-1.0

# DisjunctiveCryptographySet

## Summary

Representing a set of CryptographyAlgorithm where only one(or more) of the elements apply.

## Description

A ConjunctiveCryptographySet of two or more CryptographyAlgorithm represents a logical grouping of multiple CryptographyAlgorithm instances in a selection list.
It is represented in the SPDX Cryptography Algorithm List Expression Syntax by the `OR` operator.

## Metadata

- name: DisjunctiveCryptographySet
- SubclassOf: CryptographyAlgorithm
- Instantiability: Concrete

## Properties

- member
  - type: CryptographyAlgorithm
  - minCount: 2
