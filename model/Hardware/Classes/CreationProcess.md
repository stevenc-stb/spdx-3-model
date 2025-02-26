SPDX-License-Identifier: Community-Spec-1.0

# CreationProcess

## Summary

The Creation Process refers to the abstract process class used to produce products.

## Description

The creation process refers to the systematic steps involved in bringing something new into existence. This can apply to products, ideas, businesses, art, software, and even life itself. 
Relationship: 
For Each `CreationProcess` there is at least one `/Core/Relationship` class or subclass with the relationshipType of 'hasOutput’ on the from and an `/Core/Element` class or subclass on the to. 

## Metadata

- name: CreationProcess
- SubclassOf: /Core/DefinedProcess
- Instantiability: Abstract

## Properties

- description
  - type: xsd:string
  - minCount: 1
  - maxCount: 1

