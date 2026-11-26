SPDX-License-Identifier: Community-Spec-1.0

# hashAlgorithm

## Summary

The cryptographic algorithm used to create and verify the hash.

## Description

The `hashAlgorithm` property references a `CryptographicAlgorithm` element that specifies the cryptographic method used to generate and verify the hash value. This algorithm defines the one-way mathematical function applied to the content (e.g., a file, snippet, or certificate) to produce a fixed-length digest.

Common hash algorithms include SHA-256, SHA-384, SHA-512, and MD5. The hash algorithm determines the length and properties of the resulting hash value, such as collision resistance and pre-image resistance.

## Metadata

- name: hashAlgorithm
- Nature: ObjectProperty
- Range: CryptographicAlgorithm
