SPDX-License-Identifier: Community-Spec-1.0

# DefinedStateProcess

## Summary

This process is used to determine the state of an affected Element.

## Description

This process is used to determine the state of an affected Element. 
The DefinedStateProcess used to define a list of vaild state(s) of an affected Element.
A DefinedStateProcess may describes the steps or conditions required to move an entity from one state to another. 

## Metadata

- name: DefinedStateProcess
- SubclassOf: UseProcess
- Instantiability: Concrete

## Properties

- vaildState
  - type: State
  - minCount: 1

