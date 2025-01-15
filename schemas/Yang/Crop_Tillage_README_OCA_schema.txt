
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

capture_base SAID/digest: EluX6ZqwX6WHUHRP6SXpWg9cxJ6RfzGOq986-QWigA14,
character_encoding SAID/digest: E9-B15RjMmKKD0fT0I_lnuG6dIVZRGFHsWeHI6OFMIlo,
information (en) SAID/digest: EIWtLtyrlLihIxjiug4myBSUbdl9Z6zC8e9LKaam2p4c,
label (en) SAID/digest: EhGuKB92ciFyT7KV-RkJoIJUsc1wvFkGJL0-ZFT7QYtk,
meta (en) SAID/digest: "EgXWTbpNKXv70jcNwyuSaRYgzYvvCMw7g8z1TvoYa_uQ"
**********************************************************************
END_OCA_MANIFEST

BEGIN_OCA_BUNDLE
**********************************************************************
Layer name: meta/1.0
SAID/digest: EgXWTbpNKXv70jcNwyuSaRYgzYvvCMw7g8z1TvoYa_uQ
language: en
name: Crop Management - Tillage
description: This is a dataset documenting crop managent - Tillage
**********************************************************************
Layer name: character_encoding/1.0
SAID/digest: E9-B15RjMmKKD0fT0I_lnuG6dIVZRGFHsWeHI6OFMIlo
default_character_encoding: utf-8
**********************************************************************
Layer name: information/1.0
SAID/digest: EIWtLtyrlLihIxjiug4myBSUbdl9Z6zC8e9LKaam2p4c
language: en

Schema attribute: information/1.0 
   Crop_Name: Crop Name
   Field_ID: ID for a Field in a Farm
   Ftilimp1: Fall Tillage 1
   Ftilimp1_Date: Fall Tillage 1 Date
   Ftilimp1_Month: Fall Tillage 1 Month
   Ftilimp1_SWAT: Fall Tillage 1 SWAT Code
   Ftilimp1_Type: Fall Tillage 1 Type
   Ftilimp2: Fall Tillage 2
   Ftilimp2_Date: Fall Tillage 2 Date
   Ftilimp2_Month: Fall Tillage 2 Month
   Ftilimp2_SWAT: Fall Tillage 2 SWAT Code
   Ftilimp2_Type: Fall Tillage 2 Type
   Land_id: ID for Land
   Note: Notes for Additional Information
   ONFARM_ID: ID for ONFARM Program
   Prdc_ID: ID for Producer or Farmer
   Stilimp1: Spring Tillage 1
   Stilimp1_Date: Spring Tillage 1 Date
   Stilimp1_Month: Spring Tillage 1 Month
   Stilimp1_SWAT: Spring Tillage 1 SWAT Code
   Stilimp1_Type: Spring Tillage 1 Type
   Stilimp2: Spring Tillage 2
   Stilimp2_Date: Spring Tillage 2 Date
   Stilimp2_Month: Spring Tillage 2 Month
   Stilimp2_SWAT: Spring Tillage 2 SWAT Code
   Stilimp2_Type: Spring Tillage 2 Type
   Year: Year

**********************************************************************
Layer name: label/1.0
SAID/digest: EhGuKB92ciFyT7KV-RkJoIJUsc1wvFkGJL0-ZFT7QYtk
language: en

Schema attribute: label/1.0 
   Crop_Name: Crop Name
   Field_ID: Field ID
   Ftilimp1: Fall Tillage 1
   Ftilimp1_Date: Fall Tillage 1 Date
   Ftilimp1_Month: Fall Tillage 1 Month
   Ftilimp1_SWAT: Fall Tillage 1 SWAT Code
   Ftilimp1_Type: Fall Tillage 1 Type
   Ftilimp2: Fall Tillage 2
   Ftilimp2_Date: Fall Tillage 2 Date
   Ftilimp2_Month: Fall Tillage 2 Month
   Ftilimp2_SWAT: Fall Tillage 2 SWAT Code
   Ftilimp2_Type: Fall Tillage 2 Type
   Land_id: Land ID
   Note: Notes
   ONFARM_ID: ONFARM ID
   Prdc_ID: Producer ID
   Stilimp1: Spring Tillage 1
   Stilimp1_Date: Spring Tillage 1 Date
   Stilimp1_Month: Spring Tillage 1 Month
   Stilimp1_SWAT: Spring Tillage 1 SWAT Code
   Stilimp1_Type: Spring Tillage 1 Type
   Stilimp2: Spring Tillage 2
   Stilimp2_Date: Spring Tillage 2 Date
   Stilimp2_Month: Spring Tillage 2 Month
   Stilimp2_SWAT: Spring Tillage 2 SWAT Code
   Stilimp2_Type: Spring Tillage 2 Type
   Year: Year

**********************************************************************
Layer name: capture_base/1.0
SAID/digest: EluX6ZqwX6WHUHRP6SXpWg9cxJ6RfzGOq986-QWigA14
flagged_attributes: [Prdc_ID,Field_ID,ONFARM_ID]

Schema attribute: data type 
   Crop_Name: Text
   Field_ID: Numeric
   Ftilimp1: Text
   Ftilimp1_Date: DateTime
   Ftilimp1_Month: DateTime
   Ftilimp1_SWAT: Numeric
   Ftilimp1_Type: Text
   Ftilimp2: Text
   Ftilimp2_Date: DateTime
   Ftilimp2_Month: DateTime
   Ftilimp2_SWAT: Numeric
   Ftilimp2_Type: Text
   Land_id: Numeric
   Note: Text
   ONFARM_ID: Numeric
   Prdc_ID: Numeric
   Stilimp1: Text
   Stilimp1_Date: DateTime
   Stilimp1_Month: DateTime
   Stilimp1_SWAT: Numeric
   Stilimp1_Type: Text
   Stilimp2: Text
   Stilimp2_Date: DateTime
   Stilimp2_Month: DateTime
   Stilimp2_SWAT: Numeric
   Stilimp2_Type: Text
   Year: DateTime

**********************************************************************
END_OCA_BUNDLE