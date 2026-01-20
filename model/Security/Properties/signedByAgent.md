SPDX-License-Identifier: Community-Spec-1.0

# signedByAgent 

## Summary

The organizational entity responsible for creating the signature.

## Description

The signedByAgent property references a /Core/Agent element (which may be an organization, department, or other entity) that is responsible for creating the signature. This provides organizational context and accountability for the signing operation, establishing who or what organization the signer represents.

This property complements signedByKey by linking the cryptographic key to a real-world identity. While signedByKey identifies the specific technical credential used, signedByAgent identifies the organizational entity that owns or controls that credential.

## Metadata

- name: signedByAgent 
- Nature: ObjectProperty
- Range: /Core/Agent
