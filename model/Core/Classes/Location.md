SPDX-License-Identifier: Community-Spec-1.0

# Location

## Summary

Location is used to define the location, address or GPS coordinates of an object.

## Description

Location is used to define the location, address or GPS coordinates of an object.

## Metadata

- name: Location
- SubclassOf: Element
- Instantiability: Abstract

## Properties
- country
  - type: CountryCodeAlpha3
  - minCount: 0
  - maxCount: 1
- locationCategory 
  - type: LocationType
  - minCount: 1
  - maxCount: 1
- locationTime
  - type: DateTime
  - minCount: 0
  - maxCount: 1
- geographicPointLocation
  - type: xsd:string
  - minCount: 0
