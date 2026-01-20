SPDX-License-Identifier: Community-Spec-1.0

# SignatureAnnotation

## Summary

SignatureAnnotation represents a cryptographic signature associated with a Element providing verification information about the authenticity and integrity of signed content.

## Description

SignatureAnnotation captures metadata about a cryptographic signature applied to software, documents, or other elements. This annotation enables verification that the signed content has not been modified since signing and confirms the identity of the signer. The signatureValue contains the actual cryptographic signature data, typically encoded as base64, while signatureAlgorithm identifies the specific cryptographic method used (such as RSA, ECDSA, DSA, or Ed25519). The signedByKey and signedByAgent properties indicate the cryptographic key and organizational entity that created the signature, respectively. The verifiedByKey property references the key used to validate the signature during verification. Optionally, signatureFile points to a separate file containing the signature data, and signatureFormat specifies the signature container format (such as PGP, CMS/PKCS#7, JSON Web Signature, or detached signature format). The signatureTimestamp records when the signature was created, which is important for establishing the timeline of signed content and determining signature validity in relation to certificate expiration or revocation.

## Metadata

- name: SignatureAnnotation
- SubclassOf: /Core/Annotation
- Instantiability: Concrete

## Properties

- signatureFile
  - type: /Software/SoftwareArtifact
  - minCount: 0
  - maxCount: 1
- signatureValue
  - type: xsd:string
  - minCount: 1
  - maxCount: 1
- signatureAlgorithm
  - type: CryptographyAlgorithm
  - minCount: 1
  - maxCount: 1
- verifiedByKey
  - type: Key
  - minCount: 0
  - maxCount: 1
- signedByKey
  - type: Key
  - minCount: 0
  - maxCount: 1
- signedByAgent
  - type: /Core/Agent
  - minCount: 0
  - maxCount: 1
- signatureTimestamp
  - type: /Core/DateTime
  - minCount: 0
  - maxCount: 1
- signatureFormat
  - type: xsd:string
  - minCount: 0
  - maxCount: 1
   
  
  
