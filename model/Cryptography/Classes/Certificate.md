SPDX-License-Identifier: Community-Spec-1.0

# Certificate

## Summary

Represents a certificate, (typically X.509 v3 ITU-T) that binds a public key to an identity.

## Description

This element describes a specific Certificate.
An certificate is a standardized document (often using the X.509 v3 ITU-T format) that binds a public key to an identity (user, service, device, or organization) using a signature from a trusted Certificate Authority (CA).
A fingerprint of a certificate can be stored in the verifiedUsing property.

In X.509 v3 ITU-T `notValidAfter` maps to the `validUntilTime`.
In X.509 v3 ITU-T `notValidBefore` maps to the `validFromTime`.
Every `Certificate` instance must have an associated `SignatureAnnotation` (to carry the signatureValue and signatureAlgorithm).

## Metadata

- name: Certificate
- SubclassOf: CryptographicArtifact
- Instantiability: Concrete

## Properties

- certificateExtension
  - type: CertificateExtension
  - minCount: 0
- certificateFormat
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- issuerAgent
  - type: /Core/Agent
  - minCount: 1
- serialNumber
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- subjectPublicKey
  - type: Key
  - minCount: 1
  - maxCount: 1
- version
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- /Core/subject
  - type: /Core/Element
  - minCount: 1
- /Core/validFromTime
  - type: /Core/DateTime
  - minCount: 1
  - maxCount: 1

## External properties restrictions

- /Core/Artifact/validUntilTime
  - minCount: 1
