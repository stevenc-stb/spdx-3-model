SPDX-License-Identifier: Community-Spec-1.0

# CryptographicArtifact

## Summary

An abstract base for concrete Cryptographic data objects (e.g., keys, certificates, signatures) used in security operations.

## Description

A Cryptographic artifact is any concrete piece of data that embodies or supports a cryptographic function, such as protecting confidentiality, integrity, or authenticity. In practice, it is a specific, handleable item (file, value, or record).

## Metadata

- name: CryptographicArtifact
- SubclassOf: /Core/Artifact
- Instantiability: Abstract

## Properties

- sourceElement
  - type: /Core/Element
  - minCount: 0
- serializedArtifact
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- serializedArtifactFormat
  - type: SerializedFormatEnum
  - minCount: 0
  - maxCount: 1
