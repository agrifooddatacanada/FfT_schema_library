---
layout: default  
title: Climate Change Driven Agricultural Frontiers and Non-Frontiers  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Climate Change Driven Agricultural Frontiers and Non-Frontiers  
**Description**:   
**Author**: Krishna KC  
**Author Email**: krishnak@uoguelph.ca  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| % Cropland | Percent cropland threshold | This threshold indicates the minimum amount of cropland in a cell to be considered "cropland". It was used for a cropland layer that was not binary. Ex. 5% cropland indicates that at least 5% of each cell contains cropland. |
| % Suitability | Percent suitability threshold | This threshold indicates the minimum value of a cell to be considered "suitable". It was used for FAO suitability data that were not binary. Ex. 5% suitability indicates that at least 5% of each cell contains suitable land for a crop. |
| Al | Alfalfa | Abbreviation for Alfalfa |
| Bn | Banana | Abbreviation for Banana |
| Br | Barley | Abbreviation for Barley |
| CE_%Crop% | Current exclusion layer | Exclusion layer used in the frontier model - where 0 represents suitable area for a specific crop, and 1 represents unsuitable area for a specific crop for the current time period (2011-2040) |
| CI_%Crop% | Current inclusion layer | Inclusion layer used in the frontier model - where 0 represents unsuitable area for a specific crop, and 1 represents suitable area for a specific crop for the current time period (2011-2040) |
| CU | Current | Time period of 2011-2040 |
| CU_%crop%_AgFr | Current single-crop agricultural frontiers | Area that is considered suitable for a certain crop in the current time period (2011-2040) and is not currently under agriculture |
| CU_%crop%_NonFr | Current single-crop agricultural non-frontiers | Area that is currently harvested for a certain crop, but will no longer be suitable in the current time period (2011-2040) |
| CU_Bin_AgFr | Current binary agricultural frontiers | Binary layer of all current frontiers |
| CU_Pure_NonFr | Pure current non-frontiers | Cumulative area of current non-frontiers that does not overlap with any current frontiers |
| Cf | Coffee | Abbreviation for Coffee |
| Co | Cocoa | Abbreviation for Cocoa |
| Cumul_CU_AgFr | Current cumulative agricultural frontiers | Mosaic layer of all current single-crop frontiers. Value indicates the number of crops which have a current frontier in each cell |
| Cumul_EM_AgFr | Emerging cumulative agricultural frontiers | Mosaic layer of all emerging single-crop frontiers. Value indicates the number of crops which have an emerging frontier in each cell |
| EM | Emerging | Time period of 2071-2100 |
| EM_%crop%_AgFr | Emerging single-crop agricultural frontiers | Area that is considered suitable for a certain crop in the emerging time period (2071-2100), is not currently under agriculture, and is not suitable in the current time period (2011-2040) |
| EM_%crop%_NonFr | Emerging single-crop agricultural non-frontiers | Area that is currently harvested for a certain crop, but will no longer be suitable in the emerging time period (2071-2100) |
| EM_Bin_AgFr | Emerging binary agricultural frontiers | Binary layer of all emerging frontiers |
| EM_Pure_NonFr | Pure emerging non-frontiers | Cumulative area of emerging non-frontiers that does not overlap with any emerging frontiers |
| FE_%Crop% | Future exclusion layer | Exclusion layer used in the frontier model - where 0 represents suitable area for a specific crop, and 1 represents unsuitable area for a specific crop for the emerging time period (2071-2100) |
| FI_%Crop% | Future inclusion layer | Inclusion layer used in the frontier model - where 0 represents unsuitable area for a specific crop, and 1 represents suitable area for a specific crop for the emerging time period (2071-2100) |
| Fm | Foxtail Millet | Abbreviation for Foxtail Millet |
| Fx | :Flax | Abbreviation for Flax |
| Mt | Millet | Abbreviation for Millet |
| Mz | Maize | Abbreviation for Maize |
| PuCU_Binary | Pure current frontiers (binary) | Cumulative area of current frontiers that does not overlap with any emerging frontiers |
| PuCU_agg | Pure current aggregate frontiers | Cumulative area of current frontiers that does not overlap with emerging frontiers - where the value indicates the number of crops which have an emerging frontier in each cell |
| PuEM_Binary | Pure emerging frontiers (binary) | Cumulative area of emerging frontiers that does not overlap with any current frontiers |
| PuEM_agg | Pure emerging aggregate frontiers | Cumulative area of emerging frontiers that does not overlap with any current frontiers - where the value indicates the number of crops which have an emerging frontier in each cell |
| PuEMxHotspots | Intersection of biodiversity hotspots and pure emerging frontiers | Area of biodiversity hotspots that falls within pure emerging frontiers |
| PuEMxSOC_tonha | Intersection of soil organic carbon and pure emerging frontiers | Amount of soil organic carbon that lies within 30m depth of pure emerging frontiers |
| PuEMxWDPA | Intersection of protected areas and pure emerging frontiers | Area of protected areas that falls within pure emerging frontiers |
| Rs | Rapeseed | Abbreviation for Rapeseed |
| SP | Sweet Potato | Abbreviation for Sweet Potato |
| So | Soy | Abbreviation for Soy |
| WP | White Potato | Abbreviation for White Potato |
| Wh | Wheat | Abbreviation for Wheat |
| Ym | Yam | Abbreviation for Yam |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Climate Change Driven Agricultural Frontiers and Non-Frontiers |  |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| % Cropland | false |  | Text | utf-8 |
| % Suitability | false |  | Text | utf-8 |
| Al | false |  | Text | utf-8 |
| Bn | false |  | Text | utf-8 |
| Br | false |  | Text | utf-8 |
| CE_%Crop% | false |  | Binary | utf-8 |
| CI_%Crop% | false |  | Binary | utf-8 |
| CU | false |  | Text | utf-8 |
| CU_%crop%_AgFr | false |  | Binary | utf-8 |
| CU_%crop%_NonFr | false |  | Binary | utf-8 |
| CU_Bin_AgFr | false |  | Binary | utf-8 |
| CU_Pure_NonFr | false |  | Numeric | utf-8 |
| Cf | false |  | Text | utf-8 |
| Co | false |  | Text | utf-8 |
| Cumul_CU_AgFr | false |  | Numeric | utf-8 |
| Cumul_EM_AgFr | false |  | Numeric | utf-8 |
| EM | false |  | Text | utf-8 |
| EM_%crop%_AgFr | false |  | Binary | utf-8 |
| EM_%crop%_NonFr | false |  | Binary | utf-8 |
| EM_Bin_AgFr | false |  | Binary | utf-8 |
| EM_Pure_NonFr | false |  | Numeric | utf-8 |
| FE_%Crop% | false |  | Binary | utf-8 |
| FI_%Crop% | false |  | Binary | utf-8 |
| Fm | false |  | Text | utf-8 |
| Fx | false |  | Text | utf-8 |
| Mt | false |  | Text | utf-8 |
| Mz | false |  | Text | utf-8 |
| PuCU_Binary | false |  | Binary | utf-8 |
| PuCU_agg | false |  | Numeric | utf-8 |
| PuEM_Binary | false |  | Binary | utf-8 |
| PuEM_agg | false |  | Numeric | utf-8 |
| PuEMxHotspots | false |  | Binary | utf-8 |
| PuEMxSOC_tonha | false | Ton per hectare | Numeric | utf-8 |
| PuEMxWDPA | false |  | Binary | utf-8 |
| Rs | false |  | Text | utf-8 |
| SP | false |  | Text | utf-8 |
| So | false |  | Text | utf-8 |
| WP | false |  | Text | utf-8 |
| Wh | false |  | Text | utf-8 |
| Ym | false |  | Text | utf-8 |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| % Cropland | Percent cropland threshold | This threshold indicates the minimum amount of cropland in a cell to be considered "cropland". It was used for a cropland layer that was not binary. Ex. 5% cropland indicates that at least 5% of each cell contains cropland. | Not a list |
| % Suitability | Percent suitability threshold | This threshold indicates the minimum value of a cell to be considered "suitable". It was used for FAO suitability data that were not binary. Ex. 5% suitability indicates that at least 5% of each cell contains suitable land for a crop. | Not a list |
| Al | Alfalfa | Abbreviation for Alfalfa | Not a list |
| Bn | Banana | Abbreviation for Banana | Not a list |
| Br | Barley | Abbreviation for Barley | Not a list |
| CE_%Crop% | Current exclusion layer | Exclusion layer used in the frontier model - where 0 represents suitable area for a specific crop, and 1 represents unsuitable area for a specific crop for the current time period (2011-2040) | Not a list |
| CI_%Crop% | Current inclusion layer | Inclusion layer used in the frontier model - where 0 represents unsuitable area for a specific crop, and 1 represents suitable area for a specific crop for the current time period (2011-2040) | Not a list |
| CU | Current | Time period of 2011-2040 | Not a list |
| CU_%crop%_AgFr | Current single-crop agricultural frontiers | Area that is considered suitable for a certain crop in the current time period (2011-2040) and is not currently under agriculture | Not a list |
| CU_%crop%_NonFr | Current single-crop agricultural non-frontiers | Area that is currently harvested for a certain crop, but will no longer be suitable in the current time period (2011-2040) | Not a list |
| CU_Bin_AgFr | Current binary agricultural frontiers | Binary layer of all current frontiers | Not a list |
| CU_Pure_NonFr | Pure current non-frontiers | Cumulative area of current non-frontiers that does not overlap with any current frontiers | Not a list |
| Cf | Coffee | Abbreviation for Coffee | Not a list |
| Co | Cocoa | Abbreviation for Cocoa | Not a list |
| Cumul_CU_AgFr | Current cumulative agricultural frontiers | Mosaic layer of all current single-crop frontiers. Value indicates the number of crops which have a current frontier in each cell | Not a list |
| Cumul_EM_AgFr | Emerging cumulative agricultural frontiers | Mosaic layer of all emerging single-crop frontiers. Value indicates the number of crops which have an emerging frontier in each cell | Not a list |
| EM | Emerging | Time period of 2071-2100 | Not a list |
| EM_%crop%_AgFr | Emerging single-crop agricultural frontiers | Area that is considered suitable for a certain crop in the emerging time period (2071-2100), is not currently under agriculture, and is not suitable in the current time period (2011-2040) | Not a list |
| EM_%crop%_NonFr | Emerging single-crop agricultural non-frontiers | Area that is currently harvested for a certain crop, but will no longer be suitable in the emerging time period (2071-2100) | Not a list |
| EM_Bin_AgFr | Emerging binary agricultural frontiers | Binary layer of all emerging frontiers | Not a list |
| EM_Pure_NonFr | Pure emerging non-frontiers | Cumulative area of emerging non-frontiers that does not overlap with any emerging frontiers | Not a list |
| FE_%Crop% | Future exclusion layer | Exclusion layer used in the frontier model - where 0 represents suitable area for a specific crop, and 1 represents unsuitable area for a specific crop for the emerging time period (2071-2100) | Not a list |
| FI_%Crop% | Future inclusion layer | Inclusion layer used in the frontier model - where 0 represents unsuitable area for a specific crop, and 1 represents suitable area for a specific crop for the emerging time period (2071-2100) | Not a list |
| Fm | Foxtail Millet | Abbreviation for Foxtail Millet | Not a list |
| Fx | :Flax | Abbreviation for Flax | Not a list |
| Mt | Millet | Abbreviation for Millet | Not a list |
| Mz | Maize | Abbreviation for Maize | Not a list |
| PuCU_Binary | Pure current frontiers (binary) | Cumulative area of current frontiers that does not overlap with any emerging frontiers | Not a list |
| PuCU_agg | Pure current aggregate frontiers | Cumulative area of current frontiers that does not overlap with emerging frontiers - where the value indicates the number of crops which have an emerging frontier in each cell | Not a list |
| PuEM_Binary | Pure emerging frontiers (binary) | Cumulative area of emerging frontiers that does not overlap with any current frontiers | Not a list |
| PuEM_agg | Pure emerging aggregate frontiers | Cumulative area of emerging frontiers that does not overlap with any current frontiers - where the value indicates the number of crops which have an emerging frontier in each cell | Not a list |
| PuEMxHotspots | Intersection of biodiversity hotspots and pure emerging frontiers | Area of biodiversity hotspots that falls within pure emerging frontiers | Not a list |
| PuEMxSOC_tonha | Intersection of soil organic carbon and pure emerging frontiers | Amount of soil organic carbon that lies within 30m depth of pure emerging frontiers | Not a list |
| PuEMxWDPA | Intersection of protected areas and pure emerging frontiers | Area of protected areas that falls within pure emerging frontiers | Not a list |
| Rs | Rapeseed | Abbreviation for Rapeseed | Not a list |
| SP | Sweet Potato | Abbreviation for Sweet Potato | Not a list |
| So | Soy | Abbreviation for Soy | Not a list |
| WP | White Potato | Abbreviation for White Potato | Not a list |
| Wh | Wheat | Abbreviation for Wheat | Not a list |
| Ym | Yam | Abbreviation for Yam | Not a list |

## Schema SAIDs

**Capture base**: Ekkq6u76WG7ZtD7AKRapn8nBENATUuuM8JYb6ecAA_Dg

| Layer | SAID |
| --- | --- |
| character_encoding | ECMcrPTovZwDRlLDT44eOkLKOVi1CPxWtFK9tV4HiHyw |
| information (en) | EVTEuboTHOvhqaI_6KifOjbB29vBlzuvStC7f6iNCXMc |
| label (en) | EtdXnbqzFoCrcZ_X8W4hiJNdvMvqusV3fd76Hhu-2jXg |
| meta (en) | E9d0V20V3p0P8yqFNEx6dY6yZ8BwXVa6PJHclAPZ5Zdg |
| unit | EZM5opIMTC73Rasvctq3u3QuEv4SFzypAYvS6Yya2-tY |

**Date created**: 2025-02-10 16:01:50

