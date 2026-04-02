SPDX-License-Identifier: Community-Spec-1.0

# RoleRelationship

## Summary

RoleRelationship represents a relationship between an entity holding a role and the scope or context in which that role applies. The givenRole property specifies the specific Role assigned.

## Description

RoleRelationship is a concrete subclass of Relationship that captures the connection between an entities (such as a person, organization, tool, or component) and the specific position, function, or responsibility it fulfills. This relationship type is used when documenting roles that are not implicitly defined by the SPDX document structure, allowing explicit modeling of organizational responsibilities, tooling involvement, or component functions across systems or contexts.
RoleRelationship inherits the `from` and `to` properties from Relationship, where:

- `relationshipType` = `hasRole`.
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
