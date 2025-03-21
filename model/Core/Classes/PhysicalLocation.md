SPDX-License-Identifier: Community-Spec-1.0

# PhysicalLocation

## Summary

A physical location is a tangible, geographically identifiable place where objects, people, or assets exist or operate.

## Description

A physical location is a tangible, geographically identifiable place where objects, people, or assets exist or operate. 

## Metadata

- name: PhysicalLocation
- SubclassOf: Location
- Instantiability: Concrete

## Properties
- city
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- postalCode
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- postalName
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- postOfficeBoxNumber
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- regionInCountry
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
- steetAddress
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
