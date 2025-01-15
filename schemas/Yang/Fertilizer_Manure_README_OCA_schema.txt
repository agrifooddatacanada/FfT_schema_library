
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

capture_base SAID/digest: EcOFf9XREQAcvJrb9ng5Qf8sX8JlXJ7sSIHqkBbNP394,
character_encoding SAID/digest: EL7wOtCwavvKqSsT3IMH7w79srJo6VMqihgX4yK2WA0Q,
information (en) SAID/digest: EgT5Lt4TZ4Ql1uQRa5eTj76_M3I9m75oMyYWUvMcMj-s,
label (en) SAID/digest: EQAd1RDMMq0JFleMG6pJv09ymj8RI92zNO4w6E2QfR7Y,
meta (en) SAID/digest: "EDITD8PxUeiNwSr4B0hd9OTnzvaAxxwWcCkzHUdIu4U0"
**********************************************************************
END_OCA_MANIFEST

BEGIN_OCA_BUNDLE
**********************************************************************
Layer name: meta/1.0
SAID/digest: EDITD8PxUeiNwSr4B0hd9OTnzvaAxxwWcCkzHUdIu4U0
language: en
name: Cope Management - Fertilizer and Manure
description: This is a dataset documenting crop managent - fertilizer and manure
**********************************************************************
Layer name: character_encoding/1.0
SAID/digest: EL7wOtCwavvKqSsT3IMH7w79srJo6VMqihgX4yK2WA0Q
default_character_encoding: utf-8
**********************************************************************
Layer name: information/1.0
SAID/digest: EgT5Lt4TZ4Ql1uQRa5eTj76_M3I9m75oMyYWUvMcMj-s
language: en

Schema attribute: information/1.0 
   Crop_Name: Code for Crop
   FertbanfFR: Fall Banding Fertilizer Fraction on Surface
   Fertbanfda: Fall Banding Fertilizer Application Date
   Fertbanfmo: Fall Banding Fertilizer Application Month
   Fertbanfn (kg/ha): Fall Banding Fertilizer N Application
   Fertbanfp (kgP/ha): Fall Banding Fertilizer P Application
   FertbansFR: Spring Banding Fertilizer Fraction on Surface
   Fertbansda: Spring Banding Application Fertilizer Date
   Fertbansmo: Spring Banding Fertilizer Application Month
   Fertbansn (kg/ha): Spring Banding Fertilizer N Application
   Fertbansp (kgP/ha): Spring Banding Fertilizer P Application
   FertbroFR: Broadcasting Fertilizer Fraction on Surface
   Fertbroda: Broadcasting Fertilizer Application Date
   Fertbromo: Broadcasting Fertilizer Application Month
   Fertbron: Broadcasting Fertilizer N Application
   Fertbrop: Broadcasting Fertilizer P Application
   Fertsedda: Seeding Fertilizer Application Date
   Fertsedmo: Seeding Fertilizer Application Month
   FertwsedFR: Seeding Fertilizer Fraction on Surface
   Fertwsedn (kg/ha): Seeding Fertilizer N Application
   Fertwsedp (kgP/ha): Seeding Fertilizer P Application
   Field_ID: ID for a Field in a Farm
   Land_id: ID for Land
   ManFR: Manure 1 Fraction on Surface
   ManFR2: Manure 2 Fraction on Surface
   ManSWATcode: Manure 1 SWAT Code
   ManSWATcode2: Manure 2 SWAT Code
   Mancode: Manure 1 Code
   Mancode2: Manure 2 Code
   Manda: Manure 1 Application Date
   Manda2: Manure 2 Application Date
   Manmo: Manure 1 Application Month
   Manmo2: Manure 2 Application Month
   Manrat (kg/ha): Manure 1 Application Rate
   Manrat (kg/ha)2: Manure 2 Application Rate
   Note: Notes for Additional Information
   ONFRAM_ID: ID for ONFARM Program
   Prdc_ID: ID for Producer or Farmer
   Year: Year

**********************************************************************
Layer name: label/1.0
SAID/digest: EQAd1RDMMq0JFleMG6pJv09ymj8RI92zNO4w6E2QfR7Y
language: en

Schema attribute: label/1.0 
   Crop_Name: Crop Name
   FertbanfFR: Fall Banding Fertilizer Fraction
   Fertbanfda: Fall Banding Fertilizer Date
   Fertbanfmo: Fall Banding Fertilizer Month
   Fertbanfn (kg/ha): Fall Banding Fertilizer N
   Fertbanfp (kgP/ha): Fall Banding Fertilizer P
   FertbansFR: Spring Banding Fertilizer Fraction
   Fertbansda: Spring Banding Fertilizer Date
   Fertbansmo: Spring Banding Fertilizer Month
   Fertbansn (kg/ha): Spring Banding Fertilizer N
   Fertbansp (kgP/ha): Spring Banding Fertilizer P
   FertbroFR: Broadcasting Fertilizer Fraction
   Fertbroda: Broadcasting Fertilizer Date
   Fertbromo: Broadcasting Fertilizer Month
   Fertbron: Broadcasting Fertilizer N
   Fertbrop: Broadcasting Fertilizer P
   Fertsedda: Seeding Fertilizer Date
   Fertsedmo: Seeding Fertilizer Month
   FertwsedFR: Seeding Fertilizer Fraction
   Fertwsedn (kg/ha): Seeding Fertilizer N
   Fertwsedp (kgP/ha): Seeding Fertilizer P
   Field_ID: Field ID
   Land_id: Land ID
   ManFR: Manure 1 Fraction
   ManFR2: Manure 2 Fraction
   ManSWATcode: Manure 1 SWAT Code
   ManSWATcode2: Manure 2 SWAT Code
   Mancode: Manure 1 Code
   Mancode2: Manure 2 Code
   Manda: Manure 1 Date
   Manda2: Manure 2 Date
   Manmo: Manure 1 Month
   Manmo2: Manure 2 Month
   Manrat (kg/ha): Manure 1 Rate
   Manrat (kg/ha)2: Manure 2 Rate
   Note: Notes
   ONFRAM_ID: ONFARM ID
   Prdc_ID: Producer ID
   Year: Year

**********************************************************************
Layer name: capture_base/1.0
SAID/digest: EcOFf9XREQAcvJrb9ng5Qf8sX8JlXJ7sSIHqkBbNP394
flagged_attributes: [Land_id,Prdc_ID,Field_ID,ONFRAM_ID]

Schema attribute: data type 
   Crop_Name: Text
   FertbanfFR: Numeric
   Fertbanfda: DateTime
   Fertbanfmo: DateTime
   Fertbanfn (kg/ha): Numeric
   Fertbanfp (kgP/ha): Numeric
   FertbansFR: Numeric
   Fertbansda: DateTime
   Fertbansmo: DateTime
   Fertbansn (kg/ha): Numeric
   Fertbansp (kgP/ha): Numeric
   FertbroFR: Numeric
   Fertbroda: DateTime
   Fertbromo: DateTime
   Fertbron: Numeric
   Fertbrop: Numeric
   Fertsedda: DateTime
   Fertsedmo: DateTime
   FertwsedFR: Numeric
   Fertwsedn (kg/ha): Numeric
   Fertwsedp (kgP/ha): Numeric
   Field_ID: Numeric
   Land_id: Numeric
   ManFR: Numeric
   ManFR2: Numeric
   ManSWATcode: Numeric
   ManSWATcode2: Numeric
   Mancode: Numeric
   Mancode2: Numeric
   Manda: DateTime
   Manda2: DateTime
   Manmo: DateTime
   Manmo2: DateTime
   Manrat (kg/ha): Numeric
   Manrat (kg/ha)2: Numeric
   Note: Text
   ONFRAM_ID: Numeric
   Prdc_ID: Numeric
   Year: DateTime

**********************************************************************
END_OCA_BUNDLE