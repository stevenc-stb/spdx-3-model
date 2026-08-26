SPDX-License-Identifier: Community-Spec-1.0

# UnitOfMeasure

## Summary

UnitOfMeasure specify information structures through industry standards for
A Unit of Measure defines a standard used to quantify
a dimension or property.

## Description

The QUDT, or "Quantity, Unit, Dimension and Type" schema defines the base classes properties, and restrictions used for modeling physical quantities, units of measure, and their dimensions in various measurement systems.

## Metadata

- name: UnitOfMeasure
- Instantiability: Concrete

## Properties

- quantity
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- unitQUDT
  - type: xsd:anyURI
  - minCount: 1
  - maxCount: 1
