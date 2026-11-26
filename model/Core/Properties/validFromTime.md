SPDX-License-Identifier: Community-Spec-1.0

# validFromTime

## Summary

Specifies the date and time from which the associated element is considered valid or suitable for use.

## Description

The `validFromTime` property specifies the exact date and time from which the associated element becomes valid or suitable for its intended use.

- **For certificates**: This marks the beginning of the certificate's validity window (the `notValidBefore` equivalent in X.509). Before this timestamp, the certificate MUST NOT be relied upon, even if it was issued by a trusted authority.
- **For artifacts**: This marks the date from which the artifact can be used without requiring reassessment.

## Metadata

- name: validFromTime
- Nature: DataProperty
- Range: DateTime
