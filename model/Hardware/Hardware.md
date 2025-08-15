SPDX-License-Identifier: Community-Spec-1.0

# Hardware

## Summary

The Hardware Profile provides metadata that describes hardware and its supply chain.

## Description

The Hardware namespace defines metadata related to physical and virtual hardware including its supply chain and properties. 

## Metadata

- id: https://spdx.org/rdf/3.1.0/terms/Hardware
- name: Hardware

## Profile conformance

For an element collection to be conformant with this profile,
the following has to hold:

1. for every `/Hardware/InstantiationVirtualHardwareProcess` there MUST exist exactly one
   `/Core/Relationship` of type `instantiates` having that element as its
   `from` property and a `/Hardware/VirualHardware` as its `to`.

2. for every `/Hardware/PhysicalHardware`, if the properties `dimensions` and
   `centerOfMass` are defined then both `dimensions` and `centerOfMass`
   must have the same `coordinateOrientationType` for x, y, and z.
