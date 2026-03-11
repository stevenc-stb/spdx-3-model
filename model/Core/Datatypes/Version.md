SPDX-License-Identifier: Community-Spec-1.0

# Version

## Summary

A string following the SemVer 2.0.0 specification with the exceptions of the patch version being optional and extensions are not supported.

## Description

A semantic version is a string that is following the specification of
[Semantic Versioning 2.0.0](https://semver.org/).
The SPDX SemVer type differs from Semantic Versioning 2.0.0 in that the patch version is optional and extensions are not supported.
If no patch version is present, the latest released patch version can be assumed.
Note that this Datatype was named "SemVer" prior to the SPDX Specification release 3.1.

## Metadata

- name: Version
- SubclassOf: xsd:string

## Format

- pattern: ^(0|[1-9][0-9]*)\.(0|[1-9][0-9]*)(\.(0|[1-9][0-9]*))?$
