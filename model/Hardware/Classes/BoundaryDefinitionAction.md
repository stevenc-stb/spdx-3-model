SPDX-License-Identifier: Community-Spec-1.0

# BoundaryDefinitionAction

## Summary

Class that describes an instance of VirtualHardware.

## Description

A VirtualHardware is a distinct article related to simulation or emulation hardware. 
This is used to assist in recording "Digital Twinning".
A FPGA simualtion of hardware is a VirtualHardware. 
Virtual hardware requires instantiation involving specific hardware and software. 

## Metadata

- name: BoundaryDefinitionAction
- SubclassOf: /Core/Action
- Instantiability: Concrete

## Properties

- description
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- boundaryParameters
  - type: /Core/DictionaryEntry
  - minCount: 1
  - maxCount: 1
