SPDX-License-Identifier: Community-Spec-1.0

# CreationAction

## Summary

Products are created using the Creation Action.

## Description

To create a product you use the Creation Action.

Relationship: 
For Each `CreationAction` there is at least one `/Core/Relationship` class or subclass with the relationshipType of 'hasOutput’ on the from and an `/Core/Element` class or subclass on the to. 

## Metadata

- name: CreationAction
- SubclassOf: /Core/Action
- Instantiability: Abstract

## Properties

- actionStartTime
  - type: /Core/DateTime
  - minCount: 1
  - maxCount: 1

