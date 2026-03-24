SPDX-License-Identifier: Community-Spec-1.0

# RoleRelationship

## Summary

RoleRelationship represents a relationship between two elements (from, to).
The givenRole property specifies the Role being assigned from another element to another element within a build, system, distribution, or lifecycle context.

## Description

RoleRelationship is a concrete subclass of Relationship that captures the connection between an entities (such as a person, organization, tool, or component) and the specific position, function, or responsibility it fulfills. This relationship type is used when documenting roles that are not implicitly defined by the SPDX document structure, allowing explicit modeling of organizational responsibilities, tooling involvement, or component functions across systems.
RoleRelationship inherits the `from` and `to` properties from Relationship, where:

- `from`: The element to which the role is assigned (the role recipient).
- `to`: The context, system, element or domain within which the role exists.

## Metadata

- name: RoleRelationship
- SubclassOf: Relationship
- Instantiability: Concrete

## Properties

- givenRole
  - type: Role
  - minCount: 1
- assignedByAgent
  - type: Agent
  - minCount: 0
