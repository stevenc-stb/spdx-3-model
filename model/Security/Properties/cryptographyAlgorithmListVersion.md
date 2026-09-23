SPDX-License-Identifier: Community-Spec-1.0

# cryptographyAlgorithmListVersion

## Summary

The version of the SPDX cryptography algorithm List used in the cryptography algorithm expression.

## Description

Recognizing that cryptography algorithm are added to the
[SPDX cryptography algorithm List](https://github.com/spdx/cryptographic-algorithm-list/) with each
subsequent version, the intent is to provide consumers with the version of the
SPDX cryptography algorithm list and expression used.

This anticipates that in the future, cryptography algorithm expression can used a
version of the SPDX License List that is older than the then current one.

The specified version of the SPDX cryptography algorithm List shall include all listed cryptography algorithm in the expression.

## Metadata

- name: cryptographyAlgorithmListVersion
- Nature: DataProperty
- Range: xsd:string
