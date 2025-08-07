SPDX-License-Identifier: Community-Spec-1.0

# RequirementContext

## Summary

Context of the requirement relating it to a project and its structure.

## Description

The requirement context describes the the hierarchical level of the requirement within a project. It does not give any idea where this requirement ends up in the final full system. It defines the project as a context for the requirement, e.g. Zephyr, Xen, Linux, any Application, any Library etc.

## Metadata

- name: RequirementContext
- SubclassOf: none

## Properties

- requirementNamespace
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- requirementHierarchyLevel
  - type: PositiveIntegerRange
  - minCount: 0
  - maxCount: 1
- contextOrigin
  - type: Specification
  - minCount: 0
  - maxCount: 1
