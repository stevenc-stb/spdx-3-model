SPDX-License-Identifier: Community-Spec-1.0

# validUntilTime

## Summary

Specifies the date and time until which the associated element is considered valid or suitable for use.

## Description

The `validUntilTime` property specifies the exact date and time until which the associated element remains valid or suitable for its intended use.

- **For certificates**: This marks the end of the certificate's validity window (the `notValidAfter` equivalent in X.509). After this timestamp, the certificate MUST NOT be relied upon, even if it was issued by a trusted authority.
- **For artifacts**: This marks the date until which the artifact can be used before its usage needs to be reassessed.

## Metadata

- name: validUntilTime
- Nature: DataProperty
- Range: DateTime
