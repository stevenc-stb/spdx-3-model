SPDX-License-Identifier: Community-Spec-1.0

# DesignAssurance  

## Summary

DesignAssurance Profile provides a framework for validating that requirements are met in systems and services. 

## Description

The DesignAssurance Profile serves as a structure for confirming that platforms and solutions comply with necessary security and operational standards, emphasizing areas such as risk oversight, organizational governance, systematic testing, and regulatory compliance.

## Metadata

- id: https://spdx.org/rdf/3.1/terms/DesignAssurance
- name: DesignAssurance

## Profile conformance
For an element collection to be conformant with this profile,
the following has to hold:

1. for every `/DesignAssurance/RequirementVerification` there shall exist atleast one
   `/Core/Relationship` of type `isVerifiedBy` having that element as
   its `from` property and a `/Core/Requirement` as its `to`
   property.
