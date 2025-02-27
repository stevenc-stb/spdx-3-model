SPDX-License-Identifier: Community-Spec-1.0

# TransportProcess

## Summary

The action of product transport.

## Description

Transporting refers to the act of moving people, goods, information, or substances from one location to another.

## Metadata

- name: TransportProcess
- SubclassOf: ModifyProcess
- Instantiability: Concrete

## Properties

- plannedTransportRoutes
  - type: xsd:string
  - minCount: 0
- forPickupLocation
  - type: /Core/Location
  - minCount: 0
  - maxCount: 1 
- forDropoffLocation
  - type: /Core/Location
  - minCount: 0
  - maxCount: 1 

