---
title: Relationships resources
description: Describes resources related to relationships.
ms.assetid: F6157FE3-7C9D-4A8F-AC11-6F4007594C3D
ms.date: 12/15/2017
ms.service: partner-dashboard
ms.subservice:  partnercenter-sdk
ms.localizationpriority: medium
---

# Relationships resources


**Applies To**

- Partner Center

Describes resources related to relationships.

## <span id="PartnerRelationship"/><span id="partnerrelationship"/><span id="PARTNERRELATIONSHIP"/>PartnerRelationship


Represents a relationship between two partners.

| Property         | Type                                                           | Description                                                                                                                                    |
|------------------|----------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|
| id               | string                                                         | The partner identifier. The partner identifier specifies the tenant id of the partner who is in the recipient (from) side of the relationship. |
| location         | string                                                         | The location of the partner.                                                                                                                   |
| mpnId            | string                                                         | The Microsoft Partner Network (MPN) identifier of the partner.                                                                                 |
| name             | string                                                         | The name of the partner.                                                                                                                       |
| relationshipType | string                                                         | The type of relationship.                                                                                                                      |
| state            | string                                                         | The state of the relationship (e.g. "active").                                                                                                 |
| attributes       | [ResourceAttributes](utility-resources.md#resourceattributes) | The metadata attributes.                                                                                                                       |



## <span id="RelationshipRequest"/><span id="relationshiprequest"/><span id="RELATIONSHIPREQUEST"/>RelationshipRequest


Provides the URL by which a customer can establish a relationship with a
partner.

| Property   | Type                                                           | Description                   |
|------------|----------------------------------------------------------------|-------------------------------|
| url        | string                                                         | The relationship request URL. |
| attributes | [ResourceAttributes](utility-resources.md#resourceattributes) | The metadata attributes.      |


