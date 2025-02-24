SPDX-License-Identifier: Community-Spec-1.0

# Location

## Summary

Location is used to define the location, address or GPS coordinates of an object.

## Description

Mailing, street and description define location. GPS coordinates are used to locate any object anywhere on earth.

## Metadata

- name: Location
- Instantiability: Concrete

## Properties
- locationTime
  - type: DateTime
  - minCount: 1
  - maxCount: 1
- mailingAddress
  - type: xsd:string
  - maxCount: 1
- streetAddress
  - type: xsd:string
  - maxCount: 1
- geographicalPointLocation
  - type: xsd:string
  - maxCount: 1
