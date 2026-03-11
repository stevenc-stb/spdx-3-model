SPDX-License-Identifier: Community-Spec-1.0

# SemVer

## Summary

A string following the SemVer 2.0.0 specification with the exception of the patch version being optional.

## Description

A semantic version is a string that is following the specification of
[Semantic Versioning 2.0.0](https://semver.org/).
The SPDX SemVer type differs from Semantic Versioning 2.0.0 in that the patch version is optional whereas the patch version is required in the Semantic Versioning 2.0.0 spec.
If no patch version is present, the latest stable patch version can be assumed.

## Metadata

- name: SemVer
- SubclassOf: xsd:string

## Format

- pattern: ^(0|[1-9][0..9]*)\.(0|[1-9][0..9]*)(\.(0|[1-9][0..9]*))?(?:-((?:0|[1-9][0..9]*|[0..9]*[a-zA-Z-][0-9a-zA-Z-]*)(?:\.(?:0|[1-9][0..9]*|[0..9]*[a-zA-Z-][0-9a-zA-Z-]*))*))?(?:\+([0-9a-zA-Z-]+(?:\.[0-9a-zA-Z-]+)*))?$
