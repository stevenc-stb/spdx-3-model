SPDX-License-Identifier: Community-Spec-1.0

# AssemblyAction

## Summary

The assembly action is composed of the various actions that produce a product. 

## Description

A product is produced by assembly actions. These actions vary by need and purpose. 
Assembled products may be designed to be disassembled into components. 


## Metadata

- name: AssemblyAction
- SubclassOf: CreationAction
- Instantiability: Concrete

## Properties

- actionStartTime
  - type: /Core/DateTime
  - minCount: 1
  - maxCount: 1

