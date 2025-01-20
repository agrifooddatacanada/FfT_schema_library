
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

capture_base SAID/digest: EMbIKdu0PEqQ4gOgtuC1lDmAsJ_jx51K2r0SJji4OzS0,
character_encoding SAID/digest: EGF7nNIbamvcA0WVxO6d__CKrGFLxbI_zGNOI7zXMD9I,
information (en) SAID/digest: EY5nG4BhSof9xdmur4VKg01osz1IyHUDPgrcX9yNgjEQ,
label (en) SAID/digest: ERvjn4qSKv0sz98-j9zGtk3YU4PnKSzHVw9WbEbec7P8,
meta (en) SAID/digest: EY_dJZG0gOf1KMZuLOWHpycIR0Vu62aytTIJvpD3HJp0,
unit SAID/digest: "Ety3-dAfiCytUeknKgmJarYAlj60dhBFMBlPRVft4bdA"
**********************************************************************
END_OCA_MANIFEST

BEGIN_OCA_BUNDLE
**********************************************************************
Layer name: capture_base/1.0
SAID/digest: EMbIKdu0PEqQ4gOgtuC1lDmAsJ_jx51K2r0SJji4OzS0
classification: RDF401
flagged_attributes: [Farm_ID]

Schema attribute: data type 
   Box_Name: Text
   Collection_Date: DateTime
   Collection_Time: DateTime
   Dry_and_Wet_Taken: Binary
   Farm_ID: Text
   Final_Mass: Numeric
   Initial_Mass: Numeric
   Laboratory_Notes: Text
   Location_In_Box: Text
   Location_In_Freezer: Text
   Moisture_Content: Text
   Paddlock_ID: Text
   Paddlock_Notes: Text
   Paddy_Intact: Binary
   Processing_Date_In_Oven: DateTime
   Processing_Date_Out_Oven: DateTime
   Sample_ID: Text
   Sample_Type: Text
   Tall_Grass_Surrounding_Paddy: Binary
   Temperature: Numeric
   Time_In: Text
   Time_Out: DateTime

**********************************************************************
Layer name: meta/1.0
SAID/digest: EY_dJZG0gOf1KMZuLOWHpycIR0Vu62aytTIJvpD3HJp0
language: en
name: RegenerativeAg_Dataset
description: Summer Faecal Data from Guelph Farms
**********************************************************************
Layer name: character_encoding/1.0
SAID/digest: EGF7nNIbamvcA0WVxO6d__CKrGFLxbI_zGNOI7zXMD9I
default_character_encoding: utf-8
**********************************************************************
Layer name: information/1.0
SAID/digest: EY5nG4BhSof9xdmur4VKg01osz1IyHUDPgrcX9yNgjEQ
language: en
**********************************************************************
Layer name: label/1.0
SAID/digest: ERvjn4qSKv0sz98-j9zGtk3YU4PnKSzHVw9WbEbec7P8
language: en
**********************************************************************
Layer name: unit/1.0
SAID/digest: Ety3-dAfiCytUeknKgmJarYAlj60dhBFMBlPRVft4bdA

Schema attribute: unit/1.0 
   Final_Mass: grams (g)
   Initial_Mass: grams (g)
   Moisture_Content: percentage (%)
   Temperature: temperature (°C)

**********************************************************************
END_OCA_BUNDLE