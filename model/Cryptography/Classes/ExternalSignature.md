SPDX-License-Identifier: Community-Spec-1.0

# ExternalSignature

## Summary

Represents a Signature that is stored externally to an SPDX graph.

## Description

Represents a Signature that is stored externally to an SPDX graph.

## Metadata

- name: ExternalSignature
- SubclassOf: SignatureAnnotation
- Instantiability: Concrete

## External properties restrictions

- /Cryptography/SignatureAnnotation/signatureStorage
  - minCount: 1

