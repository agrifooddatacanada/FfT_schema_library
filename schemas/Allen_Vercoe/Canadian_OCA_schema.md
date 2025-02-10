---
layout: default  
title: Canadian Bee Gut Project Data Schema  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: Canadian Bee Gut Project Data Schema  
**Description**: The Canadian Bee Gut Project (CBGP) dataset captures comprehensive microbiome and metadata associated with honey bee colonies across Canada. The schema includes essential identifiers such as sample ID, hive ID, beekeeper ID, and province, along with hive attributes like bee breed, colony management type (commercial/organic), and sampling date. Additionally, the dataset features relative abundances of key bacterial taxa identified through sequencing, including members of the Lactobacillaceae, Bifidobacteriaceae, and Bartonellaceae families, among others. This shcema will be extended to include addtional taxonomic infromation as more sequencing data is generated from the samples over time. This structured data facilitates microbial ecology research, enabling insights into regional variations, host-microbiota interactions, and potential links to colony health and resilience.  
**Classification**: RDF401  
**Author**: Brendan Daisley  
**Author Email**: bdaisley@uoguelph.ca  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| SV_10;Bacteria;Actinomycetota;Actinomycetes;Bifidobacteriales;Bifidobacteriaceae;Bifidobacterium;Bifidobacterium_polysaccharolyticum | Bifidobacterium polysaccharolyticum Relative Abundance | The relative abundance of Bifidobacterium polysaccharolyticum in the sample. |
| SV_11;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Bombilactobacillus;Bombilactobacillus_mellis | Bombilactobacillus mellis Relative Abundance (var1) | The relative abundance of Bombilactobacillus mellis, a lactic acid bacterium found in bees. Variant type 1. |
| SV_12;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Bombilactobacillus;Bombilactobacillus_mellis | Bombilactobacillus mellis Relative Abundance (var2) | The relative abundance of Bombilactobacillus mellis, a lactic acid bacterium found in bees. Variant type 2. |
| SV_13;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Lactobacillus;Lactobacillus_kimbladii | Lactobacillus kimbladii Relative Abundance | The relative abundance of Lactobacillus kimbladii, a beneficial gut-associated bacterium. |
| SV_14;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Lactobacillus;Lactobacillus_melliventris | Lactobacillus melliventris Relative Abundance (var2) | The relative abundance of Lactobacillus melliventris in the sample. Variant type 2. |
| SV_15;Bacteria;Pseudomonadota;Alphaproteobacteria;Rhodospirillales;Acetobacteraceae;bsv105;bsv105_bsv105 | Acetobacteraceae bsv105 Relative Abundance | The relative abundance of an unclassified Acetobacteraceae bacterium (bsv105) in the sample. The identifer bsv105 represents a predicted novel species. |
| SV_16;Bacteria;Pseudomonadota;Alphaproteobacteria;Hyphomicrobiales;Bartonellaceae;Bartonella;Bartonella_apis | Bartonella apis Relative Abundance (var2) | The relative abundance of Bartonella apis, a core gut bacterium in honeybees. Variant type 2. |
| SV_1;Bacteria;Pseudomonadota;Alphaproteobacteria;Hyphomicrobiales;Bartonellaceae;Bartonella;Bartonella_apis | Bartonella apis Relative Abundance (var1) | The relative abundance of Bartonella apis, a core gut bacterium in honeybees. Variant type 1. |
| SV_2;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Lactobacillus;Lactobacillus_apis | Lactobacillus apis Relative Abundance (var1) | The relative abundance of Lactobacillus apis in the sample. Variant type 1. |
| SV_3;Bacteria;Actinomycetota;Actinomycetes;Bifidobacteriales;Bifidobacteriaceae;Bifidobacterium;Bifidobacterium_apousia | Bifidobacterium apousia Relative Abundance | The relative abundance of Bifidobacterium apousia in the sample. |
| SV_4;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Apilactobacillus;Apilactobacillus_kunkeei | Apilactobacillus kunkeei Relative Abundance | The relative abundance of Apilactobacillus kunkeei in the sample. |
| SV_5;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Lactobacillus;Lactobacillus_melliventris | Lactobacillus melliventris Relative Abundance (var1) | The relative abundance of Lactobacillus melliventris in the sample. Variant type 1. |
| SV_6;Bacteria;Actinomycetota;Actinomycetes;Bifidobacteriales;Bifidobacteriaceae;Bifidobacterium;Bifidobacterium_coryneforme | Bifidobacterium coryneforme Relative Abundance | The relative abundance of Bifidobacterium coryneforme in the sample. |
| SV_7;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Lactobacillus;Lactobacillus_apis | Lactobacillus apis Relative Abundance (var2) | The relative abundance of Lactobacillus apis in the sample. Variant type 2. |
| SV_8;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Lactobacillus;Lactobacillus_helsingborgensis | Lactobacillus helsingborgensis Relative Abundance | The relative abundance of Lactobacillus helsingborgensis in the sample. |
| SV_9;Bacteria;Pseudomonadota;Betaproteobacteria;Neisseriales;Neisseriaceae;Snodgrassella;Snodgrassella_alvi | Snodgrassella alvi Relative Abundance | The relative abundance of Snodgrassella alvi, a core gut symbiont of honeybees. |
| beekeeper_id | Beekeeper Identifier | A unique identifier for the beekeeper managing the hive. |
| breed | Bee Breed | The breed or genetic lineage of the honeybee colony. |
| build | Hive Management Type | Classification of the hive as commercial or organic. |
| date | Sample Collection Date | The date on which the sample was collected from the hive. |
| hive_id | Hive Identifier | A unique identifier for the hive from which the sample was collected. |
| province | Province/Region | The Canadian province where the sample was collected. |
| sample_id | Unique Sample Identifier | A unique alphanumeric identifier assigned to each sample. The S[0-9]+ part of the name is relevent to the sequencing run from which the data was derived. |
| sample_id2 | Secondary Sample Identifier | An alternative identifier used for internal tracking. This is the main Canadian Bee Gut Project identifier used for internal and external sample referencing. |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | Canadian Bee Gut Project Data Schema | The Canadian Bee Gut Project (CBGP) dataset captures comprehensive microbiome and metadata associated with honey bee colonies across Canada. The schema includes essential identifiers such as sample ID, hive ID, beekeeper ID, and province, along with hive attributes like bee breed, colony management type (commercial/organic), and sampling date. Additionally, the dataset features relative abundances of key bacterial taxa identified through sequencing, including members of the Lactobacillaceae, Bifidobacteriaceae, and Bartonellaceae families, among others. This shcema will be extended to include addtional taxonomic infromation as more sequencing data is generated from the samples over time. This structured data facilitates microbial ecology research, enabling insights into regional variations, host-microbiota interactions, and potential links to colony health and resilience. |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding |
| --- | --- | --- | --- | --- |
| SV_10;Bacteria;Actinomycetota;Actinomycetes;Bifidobacteriales;Bifidobacteriaceae;Bifidobacterium;Bifidobacterium_polysaccharolyticum | false |  | Numeric | utf-8 |
| SV_11;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Bombilactobacillus;Bombilactobacillus_mellis | false |  | Numeric | utf-8 |
| SV_12;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Bombilactobacillus;Bombilactobacillus_mellis | false |  | Numeric | utf-8 |
| SV_13;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Lactobacillus;Lactobacillus_kimbladii | false |  | Numeric | utf-8 |
| SV_14;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Lactobacillus;Lactobacillus_melliventris | false |  | Numeric | utf-8 |
| SV_15;Bacteria;Pseudomonadota;Alphaproteobacteria;Rhodospirillales;Acetobacteraceae;bsv105;bsv105_bsv105 | false |  | Numeric | utf-8 |
| SV_16;Bacteria;Pseudomonadota;Alphaproteobacteria;Hyphomicrobiales;Bartonellaceae;Bartonella;Bartonella_apis | false |  | Numeric | utf-8 |
| SV_1;Bacteria;Pseudomonadota;Alphaproteobacteria;Hyphomicrobiales;Bartonellaceae;Bartonella;Bartonella_apis | false |  | Numeric | utf-8 |
| SV_2;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Lactobacillus;Lactobacillus_apis | false |  | Numeric | utf-8 |
| SV_3;Bacteria;Actinomycetota;Actinomycetes;Bifidobacteriales;Bifidobacteriaceae;Bifidobacterium;Bifidobacterium_apousia | false |  | Numeric | utf-8 |
| SV_4;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Apilactobacillus;Apilactobacillus_kunkeei | false |  | Numeric | utf-8 |
| SV_5;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Lactobacillus;Lactobacillus_melliventris | false |  | Numeric | utf-8 |
| SV_6;Bacteria;Actinomycetota;Actinomycetes;Bifidobacteriales;Bifidobacteriaceae;Bifidobacterium;Bifidobacterium_coryneforme | false |  | Numeric | utf-8 |
| SV_7;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Lactobacillus;Lactobacillus_apis | false |  | Numeric | utf-8 |
| SV_8;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Lactobacillus;Lactobacillus_helsingborgensis | false |  | Numeric | utf-8 |
| SV_9;Bacteria;Pseudomonadota;Betaproteobacteria;Neisseriales;Neisseriaceae;Snodgrassella;Snodgrassella_alvi | false |  | Numeric | utf-8 |
| beekeeper_id | true |  | Text | utf-8 |
| breed | false |  | Text | utf-8 |
| build | false |  | Text | utf-8 |
| date | false |  | DateTime | utf-8 |
| hive_id | false |  | Text | utf-8 |
| province | false |  | Text | utf-8 |
| sample_id | false |  | Text | utf-8 |
| sample_id2 | false |  | Text | utf-8 |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| SV_10;Bacteria;Actinomycetota;Actinomycetes;Bifidobacteriales;Bifidobacteriaceae;Bifidobacterium;Bifidobacterium_polysaccharolyticum | Bifidobacterium polysaccharolyticum Relative Abundance | The relative abundance of Bifidobacterium polysaccharolyticum in the sample. | Not a list |
| SV_11;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Bombilactobacillus;Bombilactobacillus_mellis | Bombilactobacillus mellis Relative Abundance (var1) | The relative abundance of Bombilactobacillus mellis, a lactic acid bacterium found in bees. Variant type 1. | Not a list |
| SV_12;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Bombilactobacillus;Bombilactobacillus_mellis | Bombilactobacillus mellis Relative Abundance (var2) | The relative abundance of Bombilactobacillus mellis, a lactic acid bacterium found in bees. Variant type 2. | Not a list |
| SV_13;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Lactobacillus;Lactobacillus_kimbladii | Lactobacillus kimbladii Relative Abundance | The relative abundance of Lactobacillus kimbladii, a beneficial gut-associated bacterium. | Not a list |
| SV_14;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Lactobacillus;Lactobacillus_melliventris | Lactobacillus melliventris Relative Abundance (var2) | The relative abundance of Lactobacillus melliventris in the sample. Variant type 2. | Not a list |
| SV_15;Bacteria;Pseudomonadota;Alphaproteobacteria;Rhodospirillales;Acetobacteraceae;bsv105;bsv105_bsv105 | Acetobacteraceae bsv105 Relative Abundance | The relative abundance of an unclassified Acetobacteraceae bacterium (bsv105) in the sample. The identifer bsv105 represents a predicted novel species. | Not a list |
| SV_16;Bacteria;Pseudomonadota;Alphaproteobacteria;Hyphomicrobiales;Bartonellaceae;Bartonella;Bartonella_apis | Bartonella apis Relative Abundance (var2) | The relative abundance of Bartonella apis, a core gut bacterium in honeybees. Variant type 2. | Not a list |
| SV_1;Bacteria;Pseudomonadota;Alphaproteobacteria;Hyphomicrobiales;Bartonellaceae;Bartonella;Bartonella_apis | Bartonella apis Relative Abundance (var1) | The relative abundance of Bartonella apis, a core gut bacterium in honeybees. Variant type 1. | Not a list |
| SV_2;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Lactobacillus;Lactobacillus_apis | Lactobacillus apis Relative Abundance (var1) | The relative abundance of Lactobacillus apis in the sample. Variant type 1. | Not a list |
| SV_3;Bacteria;Actinomycetota;Actinomycetes;Bifidobacteriales;Bifidobacteriaceae;Bifidobacterium;Bifidobacterium_apousia | Bifidobacterium apousia Relative Abundance | The relative abundance of Bifidobacterium apousia in the sample. | Not a list |
| SV_4;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Apilactobacillus;Apilactobacillus_kunkeei | Apilactobacillus kunkeei Relative Abundance | The relative abundance of Apilactobacillus kunkeei in the sample. | Not a list |
| SV_5;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Lactobacillus;Lactobacillus_melliventris | Lactobacillus melliventris Relative Abundance (var1) | The relative abundance of Lactobacillus melliventris in the sample. Variant type 1. | Not a list |
| SV_6;Bacteria;Actinomycetota;Actinomycetes;Bifidobacteriales;Bifidobacteriaceae;Bifidobacterium;Bifidobacterium_coryneforme | Bifidobacterium coryneforme Relative Abundance | The relative abundance of Bifidobacterium coryneforme in the sample. | Not a list |
| SV_7;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Lactobacillus;Lactobacillus_apis | Lactobacillus apis Relative Abundance (var2) | The relative abundance of Lactobacillus apis in the sample. Variant type 2. | Not a list |
| SV_8;Bacteria;Bacillota;Bacilli;Lactobacillales;Lactobacillaceae;Lactobacillus;Lactobacillus_helsingborgensis | Lactobacillus helsingborgensis Relative Abundance | The relative abundance of Lactobacillus helsingborgensis in the sample. | Not a list |
| SV_9;Bacteria;Pseudomonadota;Betaproteobacteria;Neisseriales;Neisseriaceae;Snodgrassella;Snodgrassella_alvi | Snodgrassella alvi Relative Abundance | The relative abundance of Snodgrassella alvi, a core gut symbiont of honeybees. | Not a list |
| beekeeper_id | Beekeeper Identifier | A unique identifier for the beekeeper managing the hive. | Not a list |
| breed | Bee Breed | The breed or genetic lineage of the honeybee colony. | Not a list |
| build | Hive Management Type | Classification of the hive as commercial or organic. | Not a list |
| date | Sample Collection Date | The date on which the sample was collected from the hive. | Not a list |
| hive_id | Hive Identifier | A unique identifier for the hive from which the sample was collected. | Not a list |
| province | Province/Region | The Canadian province where the sample was collected. | Not a list |
| sample_id | Unique Sample Identifier | A unique alphanumeric identifier assigned to each sample. The S[0-9]+ part of the name is relevent to the sequencing run from which the data was derived. | Not a list |
| sample_id2 | Secondary Sample Identifier | An alternative identifier used for internal tracking. This is the main Canadian Bee Gut Project identifier used for internal and external sample referencing. | Not a list |

## Schema SAIDs

**Capture base**: EsjG9RorD_tcAzcwm5Y-okGOOietLCCLRXSKxiZHF6Us

| Layer | SAID |
| --- | --- |
| character_encoding | Eu8QHe2PxvifmloVeNOgAMaRFSQFE867ZRTeMZk3ZerQ |
| information (en) | Ep9sIb-JrxXnVhsbZ2rX2OWtQHG6P4PED_tmNFEg_lRw |
| label (en) | E06CF2ABpenuVOMFmOXS-Mj2b9zMnu6lLPtQWU3YYP6A |
| meta (en) | EXX29QKpmfNWGaF4pOlVMqi5_EhMtpYRlXN9ssR03Mf8 |

**Date created**: 2025-02-10 16:20:44

