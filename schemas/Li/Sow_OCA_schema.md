---
layout: default  
title: Sow Lifetime Litter Information
parent: Julang Li, PI
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Sow Lifetime Litter Information  
**Description**: This schema is used for describing lifetime reproductive performance of sows.  
**Classification**: RDF402  
**Author**: Lauren Fletcher  
**Author Email**: lfletc03@uoguelph.ca  

[Download Schema](Sow_OCA_bundle.zip) 


## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| Average_NPD | Average non-productive days | Average number of days the sow was not pregnant, farrowing, or nursing across her parities. |
| Average_Services_Per_Parity | Average Services per Parity | Average number of rounds of artificial insemination the sow received per litter. |
| Average_litter_weight_kg | Average litter weight in kilograms | Average weight of a sow's litters across her lifetime |
| Average_piglet_weight_kg | Average piglet weight in kilograms | Average weight of a piglet in a sow's litter across her lifetime |
| DOB | Date of Birth | The date that the sow was born. |
| FI | Farrowing Index | How many litters a pig has in a year. |
| Farrowing_Interval | Farrowing Interval | Average number of days between a farrowing and her next one. |
| Genetics | Genetics | Genetics of the pig. |
| Gestation_Length | Gestation Length | The length of the pigs pregnancy before she farrows. |
| ID | Animal Identification Number | The identification number of the pig on the farm it was sampled from. |
| Lactation_Length | Lactation length | How long after farrowing the sow was nursing her piglets before weaning. |
| Liveborn | Liveborn | Average number of alive piglets per litter. |
| Mummified | Mummified | Average number of mummified piglets per litter. |
| NPD | Non-productive days | How many days the sow was not pregnant, farrowing, or nursing during her most recent litter. |
| Notes | Notes | Extra information regarding a sow's reproductive performance that may be useful or important for her use in the study. |
| Parity | Parity | Number of litters that the sow has had in her lifetime. |
| Piglet_Loss_Percentage | Piglet losses percentage | Average percentage of stillborn or mummified piglets relative to total born. |
| Piglet_losses_at_farrowing | Piglet losses at farrowing | Average number of stillborn and mummified piglets per litter. |
| Piglets_Weaned | Piglets weaned | Average piglets weaned per litter across a sow's lifetime. |
| Sample_collection_date | Sample Collection Date | The date that the sow was sampled for urine, saliva and serum. |
| Status | Status in the herd | Status of the sow in the herd at the time of data collection. |
| Stillborn | Stillborn | Average number of stillborn piglets per litter. |
| Total_Born | Total born | Average number of piglets born per litter (alive, stillborn or mummified). |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Sow Lifetime Litter Information | This schema is used for describing lifetime reproductive performance of sows. |

## Selection lists

### English

#### Genetics entry codes

| Entry code | Label |
| --- | --- |
| Y | Yorkshire |
| Y/L | Yorkshire Landrace Cross |
| Y/L/D | Yorkshire Landrace Duroc Cross |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry | Format rule |
| --- | --- | --- | --- | --- | --- | --- |
| Average_NPD | false |  | Numeric | utf-8 | true |  |
| Average_Services_Per_Parity | false |  | Numeric | utf-8 | false |  |
| Average_litter_weight_kg | false |  | Numeric | utf-8 | true |  |
| Average_piglet_weight_kg | false |  | Numeric | utf-8 | true |  |
| DOB | false |  | DateTime | utf-8 | true |  |
| FI | false |  | Numeric | utf-8 | false |  |
| Farrowing_Interval | false |  | Numeric | utf-8 | false |  |
| Genetics | false |  | Text | utf-8 | true |  |
| Gestation_Length | false |  | Numeric | utf-8 | false |  |
| ID | false |  | Numeric | utf-8 | true | ^\-?\[0\-9\]\+$ |
| Lactation_Length | false |  | Numeric | utf-8 | true |  |
| Liveborn | false |  | Numeric | utf-8 | true |  |
| Mummified | false |  | Numeric | utf-8 | true |  |
| NPD | false |  | Numeric | utf-8 | false |  |
| Notes | false |  | Text | utf-8 | false | ^\.\{0,800\}$ |
| Parity | false |  | Numeric | utf-8 | true |  |
| Piglet_Loss_Percentage | false |  | Numeric | utf-8 | false |  |
| Piglet_losses_at_farrowing | false |  | Numeric | utf-8 | true |  |
| Piglets_Weaned | false |  | Numeric | utf-8 | true |  |
| Sample_collection_date | false |  | DateTime | utf-8 | false |  |
| Status | false |  | Text | utf-8 | true | ^\.\{0,50\}$ |
| Stillborn | false |  | Numeric | utf-8 | true |  |
| Total_Born | false |  | Numeric | utf-8 | true |  |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| Average_NPD | Average non-productive days | Average number of days the sow was not pregnant, farrowing, or nursing across her parities. | Not a list |
| Average_Services_Per_Parity | Average Services per Parity | Average number of rounds of artificial insemination the sow received per litter. | Not a list |
| Average_litter_weight_kg | Average litter weight in kilograms | Average weight of a sow's litters across her lifetime | Not a list |
| Average_piglet_weight_kg | Average piglet weight in kilograms | Average weight of a piglet in a sow's litter across her lifetime | Not a list |
| DOB | Date of Birth | The date that the sow was born. | Not a list |
| FI | Farrowing Index | How many litters a pig has in a year. | Not a list |
| Farrowing_Interval | Farrowing Interval | Average number of days between a farrowing and her next one. | Not a list |
| Genetics | Genetics | Genetics of the pig. | Yorkshire, Yorkshire Landrace Cross, Yorkshire Landrace Duroc Cross |
| Gestation_Length | Gestation Length | The length of the pigs pregnancy before she farrows. | Not a list |
| ID | Animal Identification Number | The identification number of the pig on the farm it was sampled from. | Not a list |
| Lactation_Length | Lactation length | How long after farrowing the sow was nursing her piglets before weaning. | Not a list |
| Liveborn | Liveborn | Average number of alive piglets per litter. | Not a list |
| Mummified | Mummified | Average number of mummified piglets per litter. | Not a list |
| NPD | Non-productive days | How many days the sow was not pregnant, farrowing, or nursing during her most recent litter. | Not a list |
| Notes | Notes | Extra information regarding a sow's reproductive performance that may be useful or important for her use in the study. | Not a list |
| Parity | Parity | Number of litters that the sow has had in her lifetime. | Not a list |
| Piglet_Loss_Percentage | Piglet losses percentage | Average percentage of stillborn or mummified piglets relative to total born. | Not a list |
| Piglet_losses_at_farrowing | Piglet losses at farrowing | Average number of stillborn and mummified piglets per litter. | Not a list |
| Piglets_Weaned | Piglets weaned | Average piglets weaned per litter across a sow's lifetime. | Not a list |
| Sample_collection_date | Sample Collection Date | The date that the sow was sampled for urine, saliva and serum. | Not a list |
| Status | Status in the herd | Status of the sow in the herd at the time of data collection. | Not a list |
| Stillborn | Stillborn | Average number of stillborn piglets per litter. | Not a list |
| Total_Born | Total born | Average number of piglets born per litter (alive, stillborn or mummified). | Not a list |

## Schema SAIDs

**Capture base**: E5UsEHFRvxIYuw1YGgFLOUA7dOSk4vWdMzU17OIUHrrU

| Layer | SAID |
| --- | --- |
| character_encoding | Ex2oX1Woj7tc21nH-LTM8_HAeT0zy6Z8ovIpTbiGJLf4 |
| conformance | EkEDKZRCCecX2qKCdjy4JrtcztktP5abxrXCrMsWkr6Q |
| entry (en) | E4TZUH_ANLmQTM9vfPbeoWMA1aTdsm6f8dJwYOcM_63Q |
| entry_code | E7r8ManQ2Q37KyhI1RGUV1wUvU3sIX0896Fpajcus_PI |
| format | EakKdShCahAmK6g3Vb9v2gzsESg6q15Uoowcbl0_m0xo |
| information (en) | E6q3Ba86hWtWnna7gqObmPp4H5nV2GSTe_TjiD_lrt44 |
| label (en) | EYLJ5rCXv0ycWVprhC2I6BVSg390MghQxo4GK55ahdng |
| meta (en) | EEH8Bt1pCuzJ8gW7boF8vR5dQnpn9m7KM2ZD1U7ZAXgM |

**Date created**: 2025-01-20 14:43:38

