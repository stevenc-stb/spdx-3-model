SPDX-License-Identifier: Community-Spec-1.0

# UnitofMeasure

## Summary

QUDT units are used for measure based on product type, region and use.

## Description

The QUDT, or "Quantity, Unit, Dimension and Type" schema defines the base classes properties, and restrictions used for modeling physical quantities, units of measure, and their dimensions in various measurement systems.

## Metadata

- name: UnitofMeasure
- Instantiability: Concrete

## Properties

- quantity
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- unitQUDT
  - type: xsd:string
  - minCount: 1
  - maxCount: 1

