SPDX-License-Identifier: Community-Spec-1.0

# Key

## Certificate

Represents a Certificate.

## Description

This element describes a specific Certificate.

fingerprint is a cryptographic hash of this Certificate used for identification and verification.
fingerprint is set uing the verifiedUsing. 

## Metadata

- name: Certificate
- SubclassOf: CryptographyArtifact
- Instantiability: Concrete

## Properties

- usage
  - type: xsd:string
  - minCount: 0
- /Hardware/serialNumber
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- /Core/Subject
  - type: /Core/Element
  - minCount: 1
- issuerAgent
  - type: /Core/Agent
  - minCount: 1
- notValidBefore
  - type: /Core/DateTime
  - minCount: 1
  - maxCount: 1
- notValidAfter
  - type: /Core/DateTime
  - minCount: 1
  - maxCount: 1
- certificateFormat
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- certificateExtension
  - type: certificateExtension
  - minCount: 0


