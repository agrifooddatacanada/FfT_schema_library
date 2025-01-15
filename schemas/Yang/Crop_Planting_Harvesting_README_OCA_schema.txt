
BEGIN_REFERENCE_MATERIAL
******************************************************************
OCA_READ_ME/1.0
This is a human-readable schema, based on the OCA schema standard.

Reference for Overlays Capture Architecture (OCA):
https://doi.org/10.5281/zenodo.7707467

Reference for OCA_READ_ME/1.0:
https://github.com/agrifooddatacanada/OCA_README

A schema describes details about a dataset.
In OCA, a schema consists of a capture_base which documents the attributes and their most basic features.
A schema may also contain overlays which add details to the capture_base.
For each overlay and capture_base, a hash of their original contents has been calculated and is reported here as the SAID value.

This README format documents the capture_base and overlays that were associated together in a single OCA Bundle.
OCA_MANIFEST lists all components of the OCA Bundle.
For the OCA_BUNDLE, each section between rows of ****'s contains the details of one "layer type/version" of the OCA Bundle.
******************************************************************
END_REFERENCE_MATERIAL

BEGIN_OCA_MANIFEST
**********************************************************************
Bundle SAID/digest: unavailable

capture_base SAID/digest: Equl7djtUR9VJs-iDRTpfJei2IlHaahNbNG12M5Rs9u8,
character_encoding SAID/digest: EreMhlmUFycvSJ4oyjaKRV_EMR6Q9S7ON2muAxbalWnM,
conformance SAID/digest: EXBw-xHqYAzbkBZ5Kpxit5NKXL0HyFNnfT_b8_2peO1g,
information (en) SAID/digest: EMw0ESlfq66Y6475VZqWgpOgPYP6Lwzhm-GezaupYsy4,
label (en) SAID/digest: Ebq7SZjqGbM_AZO_wXS-VnmOYBSHfvNKHn28wxTEhP7A,
meta (en) SAID/digest: "EqabzGjtNM2h5l-rIuCOY7fbxctR8zzVnr9DS5WFBeqs"
**********************************************************************
END_OCA_MANIFEST

BEGIN_OCA_BUNDLE
**********************************************************************
Layer name: capture_base/1.0
SAID/digest: Equl7djtUR9VJs-iDRTpfJei2IlHaahNbNG12M5Rs9u8
classification: RDF405
flagged_attributes: [Land_id,Prdc_ID,Field_ID,ONFARM_ID]

Schema attribute: data type 
   Crop_Code: Numeric
   Crop_Group: Text
   Crop_Name: Text
   Field_ID: Numeric
   Harvest_Date: DateTime
   Harvest_month: DateTime
   Land_id: Numeric
   Note: Text
   ONFARM_ID: Numeric
   Prdc_ID: Numeric
   Residue_cover: Numeric
   SWAT_Code: Text
   Seed_Date: DateTime
   Seed_Month: DateTime
   Strawmgt_Code: Numeric
   Strawmgt_Type: Text
   Year: DateTime

**********************************************************************
Layer name: meta/1.0
SAID/digest: EqabzGjtNM2h5l-rIuCOY7fbxctR8zzVnr9DS5WFBeqs
language: en
name: Crop Managemnt - Planting and Harvesting
description: This is a dataset documenting crop managent - planting and harvestin
**********************************************************************
Layer name: character_encoding/1.0
SAID/digest: EreMhlmUFycvSJ4oyjaKRV_EMR6Q9S7ON2muAxbalWnM
default_character_encoding: utf-8
**********************************************************************
Layer name: conformance/1.0
SAID/digest: EXBw-xHqYAzbkBZ5Kpxit5NKXL0HyFNnfT_b8_2peO1g

Schema attribute: conformance/1.0 
   Crop_Code: O
   Crop_Group: O
   Crop_Name: M
   Field_ID: M
   Harvest_Date: M
   Harvest_month: M
   Land_id: O
   Note: O
   ONFARM_ID: O
   Prdc_ID: O
   Residue_cover: O
   SWAT_Code: O
   Seed_Date: M
   Seed_Month: M
   Strawmgt_Code: O
   Strawmgt_Type: O
   Year: M

**********************************************************************
Layer name: information/1.0
SAID/digest: EMw0ESlfq66Y6475VZqWgpOgPYP6Lwzhm-GezaupYsy4
language: en

Schema attribute: information/1.0 
   Crop_Code: Code for Crop
   Crop_Group: Crop Group
   Crop_Name: Crop Name
   Field_ID: ID for a Field in a Farm
   Harvest_Date: Harvesing Date for Crop
   Harvest_month: Harvetsing Month for Crop
   Land_id: ID for Land
   Note: Notes for Additional Information
   ONFARM_ID: ID for ONFARM Program
   Prdc_ID: ID for Producer or Farmer
   Residue_cover: Straw Management Percentages
   SWAT_Code: Crop Code for SWAT Model (CORN - corn SOYB - Soybean WWHT- Winter Wheat)
   Seed_Date: Seeding Date for Crop
   Seed_Month: Seeding Month for Crop
   Strawmgt_Code: Code for Straw Management
   Strawmgt_Type: Straw Management Type
   Year: Yes

**********************************************************************
Layer name: label/1.0
SAID/digest: Ebq7SZjqGbM_AZO_wXS-VnmOYBSHfvNKHn28wxTEhP7A
language: en

Schema attribute: label/1.0 
   Crop_Code: Crop Code
   Crop_Group: Crop Group
   Crop_Name: Crop Name
   Field_ID: Field ID
   Harvest_Date: Harvest Date
   Harvest_month: Harvest Month
   Land_id: Land ID
   Note: Notes
   ONFARM_ID: ONFARM Program ID
   Prdc_ID: Producer ID
   Residue_cover: Residue Cover
   SWAT_Code: SWAT Code
   Seed_Date: Seeding Date
   Seed_Month: Seeding Month
   Strawmgt_Code: Straw Management Code
   Strawmgt_Type: Straw Management Type
   Year: Year

**********************************************************************
END_OCA_BUNDLE