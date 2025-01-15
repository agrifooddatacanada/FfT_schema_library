---
layout: default  
title: Cope Management - Fertilizer and Manure  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Cope Management - Fertilizer and Manure  
**Description**: This is a dataset documenting crop managent - fertilizer and manure  
**Author**: Wanhong Yang  
**Author Email**: wayang@uoguelph.ca  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| Crop_Name | Crop Name | Code for Crop |
| FertbanfFR | Fall Banding Fertilizer Fraction | Fall Banding Fertilizer Fraction on Surface |
| Fertbanfda | Fall Banding Fertilizer Date | Fall Banding Fertilizer Application Date |
| Fertbanfmo | Fall Banding Fertilizer Month | Fall Banding Fertilizer Application Month |
| Fertbanfn (kg/ha) | Fall Banding Fertilizer N | Fall Banding Fertilizer N Application |
| Fertbanfp (kgP/ha) | Fall Banding Fertilizer P | Fall Banding Fertilizer P Application |
| FertbansFR | Spring Banding Fertilizer Fraction | Spring Banding Fertilizer Fraction on Surface |
| Fertbansda | Spring Banding Fertilizer Date | Spring Banding Application Fertilizer Date |
| Fertbansmo | Spring Banding Fertilizer Month | Spring Banding Fertilizer Application Month |
| Fertbansn (kg/ha) | Spring Banding Fertilizer N | Spring Banding Fertilizer N Application |
| Fertbansp (kgP/ha) | Spring Banding Fertilizer P | Spring Banding Fertilizer P Application |
| FertbroFR | Broadcasting Fertilizer Fraction | Broadcasting Fertilizer Fraction on Surface |
| Fertbroda | Broadcasting Fertilizer Date | Broadcasting Fertilizer Application Date |
| Fertbromo | Broadcasting Fertilizer Month | Broadcasting Fertilizer Application Month |
| Fertbron | Broadcasting Fertilizer N | Broadcasting Fertilizer N Application |
| Fertbrop | Broadcasting Fertilizer P | Broadcasting Fertilizer P Application |
| Fertsedda | Seeding Fertilizer Date | Seeding Fertilizer Application Date |
| Fertsedmo | Seeding Fertilizer Month | Seeding Fertilizer Application Month |
| FertwsedFR | Seeding Fertilizer Fraction | Seeding Fertilizer Fraction on Surface |
| Fertwsedn (kg/ha) | Seeding Fertilizer N | Seeding Fertilizer N Application |
| Fertwsedp (kgP/ha) | Seeding Fertilizer P | Seeding Fertilizer P Application |
| Field_ID | Field ID | ID for a Field in a Farm |
| Land_id | Land ID | ID for Land |
| ManFR | Manure 1 Fraction | Manure 1 Fraction on Surface |
| ManFR2 | Manure 2 Fraction | Manure 2 Fraction on Surface |
| ManSWATcode | Manure 1 SWAT Code | Manure 1 SWAT Code |
| ManSWATcode2 | Manure 2 SWAT Code | Manure 2 SWAT Code |
| Mancode | Manure 1 Code | Manure 1 Code |
| Mancode2 | Manure 2 Code | Manure 2 Code |
| Manda | Manure 1 Date | Manure 1 Application Date |
| Manda2 | Manure 2 Date | Manure 2 Application Date |
| Manmo | Manure 1 Month | Manure 1 Application Month |
| Manmo2 | Manure 2 Month | Manure 2 Application Month |
| Manrat (kg/ha) | Manure 1 Rate | Manure 1 Application Rate |
| Manrat (kg/ha)2 | Manure 2 Rate | Manure 2 Application Rate |
| Note | Notes | Notes for Additional Information |
| ONFRAM_ID | ONFARM ID | ID for ONFARM Program |
| Prdc_ID | Producer ID | ID for Producer or Farmer |
| Year | Year | Year |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Cope Management - Fertilizer and Manure | This is a dataset documenting crop managent - fertilizer and manure |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| Crop_Name | false |  | Text | utf-8 |
| FertbanfFR | false |  | Numeric | utf-8 |
| Fertbanfda | false |  | DateTime | utf-8 |
| Fertbanfmo | false |  | DateTime | utf-8 |
| Fertbanfn (kg/ha) | false |  | Numeric | utf-8 |
| Fertbanfp (kgP/ha) | false |  | Numeric | utf-8 |
| FertbansFR | false |  | Numeric | utf-8 |
| Fertbansda | false |  | DateTime | utf-8 |
| Fertbansmo | false |  | DateTime | utf-8 |
| Fertbansn (kg/ha) | false |  | Numeric | utf-8 |
| Fertbansp (kgP/ha) | false |  | Numeric | utf-8 |
| FertbroFR | false |  | Numeric | utf-8 |
| Fertbroda | false |  | DateTime | utf-8 |
| Fertbromo | false |  | DateTime | utf-8 |
| Fertbron | false |  | Numeric | utf-8 |
| Fertbrop | false |  | Numeric | utf-8 |
| Fertsedda | false |  | DateTime | utf-8 |
| Fertsedmo | false |  | DateTime | utf-8 |
| FertwsedFR | false |  | Numeric | utf-8 |
| Fertwsedn (kg/ha) | false |  | Numeric | utf-8 |
| Fertwsedp (kgP/ha) | false |  | Numeric | utf-8 |
| Field_ID | true |  | Numeric | utf-8 |
| Land_id | true |  | Numeric | utf-8 |
| ManFR | false |  | Numeric | utf-8 |
| ManFR2 | false |  | Numeric | utf-8 |
| ManSWATcode | false |  | Numeric | utf-8 |
| ManSWATcode2 | false |  | Numeric | utf-8 |
| Mancode | false |  | Numeric | utf-8 |
| Mancode2 | false |  | Numeric | utf-8 |
| Manda | false |  | DateTime | utf-8 |
| Manda2 | false |  | DateTime | utf-8 |
| Manmo | false |  | DateTime | utf-8 |
| Manmo2 | false |  | DateTime | utf-8 |
| Manrat (kg/ha) | false |  | Numeric | utf-8 |
| Manrat (kg/ha)2 | false |  | Numeric | utf-8 |
| Note | false |  | Text | utf-8 |
| ONFRAM_ID | true |  | Numeric | utf-8 |
| Prdc_ID | true |  | Numeric | utf-8 |
| Year | false |  | DateTime | utf-8 |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| Crop_Name | Crop Name | Code for Crop | Not a list |
| FertbanfFR | Fall Banding Fertilizer Fraction | Fall Banding Fertilizer Fraction on Surface | Not a list |
| Fertbanfda | Fall Banding Fertilizer Date | Fall Banding Fertilizer Application Date | Not a list |
| Fertbanfmo | Fall Banding Fertilizer Month | Fall Banding Fertilizer Application Month | Not a list |
| Fertbanfn (kg/ha) | Fall Banding Fertilizer N | Fall Banding Fertilizer N Application | Not a list |
| Fertbanfp (kgP/ha) | Fall Banding Fertilizer P | Fall Banding Fertilizer P Application | Not a list |
| FertbansFR | Spring Banding Fertilizer Fraction | Spring Banding Fertilizer Fraction on Surface | Not a list |
| Fertbansda | Spring Banding Fertilizer Date | Spring Banding Application Fertilizer Date | Not a list |
| Fertbansmo | Spring Banding Fertilizer Month | Spring Banding Fertilizer Application Month | Not a list |
| Fertbansn (kg/ha) | Spring Banding Fertilizer N | Spring Banding Fertilizer N Application | Not a list |
| Fertbansp (kgP/ha) | Spring Banding Fertilizer P | Spring Banding Fertilizer P Application | Not a list |
| FertbroFR | Broadcasting Fertilizer Fraction | Broadcasting Fertilizer Fraction on Surface | Not a list |
| Fertbroda | Broadcasting Fertilizer Date | Broadcasting Fertilizer Application Date | Not a list |
| Fertbromo | Broadcasting Fertilizer Month | Broadcasting Fertilizer Application Month | Not a list |
| Fertbron | Broadcasting Fertilizer N | Broadcasting Fertilizer N Application | Not a list |
| Fertbrop | Broadcasting Fertilizer P | Broadcasting Fertilizer P Application | Not a list |
| Fertsedda | Seeding Fertilizer Date | Seeding Fertilizer Application Date | Not a list |
| Fertsedmo | Seeding Fertilizer Month | Seeding Fertilizer Application Month | Not a list |
| FertwsedFR | Seeding Fertilizer Fraction | Seeding Fertilizer Fraction on Surface | Not a list |
| Fertwsedn (kg/ha) | Seeding Fertilizer N | Seeding Fertilizer N Application | Not a list |
| Fertwsedp (kgP/ha) | Seeding Fertilizer P | Seeding Fertilizer P Application | Not a list |
| Field_ID | Field ID | ID for a Field in a Farm | Not a list |
| Land_id | Land ID | ID for Land | Not a list |
| ManFR | Manure 1 Fraction | Manure 1 Fraction on Surface | Not a list |
| ManFR2 | Manure 2 Fraction | Manure 2 Fraction on Surface | Not a list |
| ManSWATcode | Manure 1 SWAT Code | Manure 1 SWAT Code | Not a list |
| ManSWATcode2 | Manure 2 SWAT Code | Manure 2 SWAT Code | Not a list |
| Mancode | Manure 1 Code | Manure 1 Code | Not a list |
| Mancode2 | Manure 2 Code | Manure 2 Code | Not a list |
| Manda | Manure 1 Date | Manure 1 Application Date | Not a list |
| Manda2 | Manure 2 Date | Manure 2 Application Date | Not a list |
| Manmo | Manure 1 Month | Manure 1 Application Month | Not a list |
| Manmo2 | Manure 2 Month | Manure 2 Application Month | Not a list |
| Manrat (kg/ha) | Manure 1 Rate | Manure 1 Application Rate | Not a list |
| Manrat (kg/ha)2 | Manure 2 Rate | Manure 2 Application Rate | Not a list |
| Note | Notes | Notes for Additional Information | Not a list |
| ONFRAM_ID | ONFARM ID | ID for ONFARM Program | Not a list |
| Prdc_ID | Producer ID | ID for Producer or Farmer | Not a list |
| Year | Year | Year | Not a list |

## Schema SAIDs

**Capture base**: EcOFf9XREQAcvJrb9ng5Qf8sX8JlXJ7sSIHqkBbNP394

| Layer | SAID |
| --- | --- |
| character_encoding | EL7wOtCwavvKqSsT3IMH7w79srJo6VMqihgX4yK2WA0Q |
| information (en) | EgT5Lt4TZ4Ql1uQRa5eTj76_M3I9m75oMyYWUvMcMj-s |
| label (en) | EQAd1RDMMq0JFleMG6pJv09ymj8RI92zNO4w6E2QfR7Y |
| meta (en) | EDITD8PxUeiNwSr4B0hd9OTnzvaAxxwWcCkzHUdIu4U0 |

**Date created**: 2025-01-15 14:03:40

