SPDX-License-Identifier: Community-Spec-1.0

# SystemsEngineering

## Summary

The Systems Engineering Profile is designed to provide a standardized way of documenting and
sharing information about artefacts created, verified and maintained during a system's lifecycle.

## Description

The Systems Engineering profile's namespace defines a set of concepts and data elements related to artefacts and their dependencies or links to each other that are part of engineering related documentation.
These artifacts include the inputs and outputs of the systems engineering phases regarding planning, requirements analysis, system/software architecture, implemenation, and the verification tasks. 


## Metadata

- id: https://spdx.org/rdf/3.1/terms/SystemsEngineering
- name: SystemsEngineering

## Profile conformance
- for every `/SystemsEngineering/RequirementVerification` there shall exist at least one `/Core/Relationship` of type `verifiedBy` having that element as its to property and a `/Core/Requirement` as its from property.
