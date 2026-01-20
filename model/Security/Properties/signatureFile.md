SPDX-License-Identifier: Community-Spec-1.0

# signatureFile

## Summary

A reference to a file that contains the cryptographic signature data.

## Description

The signatureFile property provides a reference to an file that contains the signature data. In many signing formats (such as detached signatures), the signature is intentionally stored separately from the signed content to maintain clean separation between the data and its verification information.

## Metadata

- name: signatureFile
- Nature: ObjectProperty
- Range: /Software/SoftwareArtifact
