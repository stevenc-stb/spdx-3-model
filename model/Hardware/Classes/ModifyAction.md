SPDX-License-Identifier: Community-Spec-1.0

# ModifyAction

## Summary

The action of product modification.

## Description

This is the specific action of product modification.

Relationship: 
For Each `ModifyAction` there is at least one `/Core/Relationship` class or subclass with the relationshipType of 'hasOutput’ on the from and an `/Core/Element` class or subclass on the to. 
For Each `ModifyAction` there is at least one `/Core/Relationship` class or subclass with the relationshipType of 'performedBy’ on the from and an `/Core/Element` class or subclass on the to. 

## Metadata

- name: ModifyAction
- SubclassOf: /Core/Action
- Instantiability: Abstract

## External properties restrictions

- actionStartTime
  - minCount: 1
  - maxCount: 1

