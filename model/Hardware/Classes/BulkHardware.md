SPDX-License-Identifier: Community-Spec-1.0

# BulkHardware

## Summary

Products or commodities produced as a bulk unit are called bulk products. Commodities are often sold in bulk. 

## Description

Products or commodities produced as a bulk unit are called bulk products. Commodities are often sold in bulk based on a batch or bulk ID number associated with the bulk unit. 
Bulk units defined in the QUDT Units standards.

## Metadata

- name: BulkHardware
- SubclassOf: Hardware
- Instantiability: Concrete

## Properties

- bulkQuantity
  - type: /Core/UnitofMeasure
  - minCount: 1
  - maxCount: 1
  
 ## External properties restrictions

- description
  - minCount: 1
  - maxCount: 1
- serialNumber
  - maxCount: 0
