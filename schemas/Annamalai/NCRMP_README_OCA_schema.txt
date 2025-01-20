
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

capture_base SAID/digest: EXcTABzZLzdt6nvvAgvXHUtprQrmdx_h-AcENtwOas3s,
character_encoding SAID/digest: E4SPFppen4nh_krorszG86FHFJPT19JJ9qi_xp9mKo8E,
conformance SAID/digest: EjYvNx1K6radvwfUs-ealxqiJ_bhPQR7seNjFY9zSIKo,
entry (en) SAID/digest: EyMlskXQUpc43GhKZ0ZQsCCVZviwfoT2nyYzdoAdYey4,
entry_code SAID/digest: EDWhTwcsaUErgj0ndQTX7YptiDj8GIvrnabgA04RmwdI,
information (en) SAID/digest: EQUr6nTzZ1rR3qFDgjCjh9kH2yJwueXSivNlQj2vBWnw,
label (en) SAID/digest: EK9YcxhW6bQB-UZwGJdwTwlVEx3ktQR-ofvlkncplqL4,
meta (en) SAID/digest: Eg9agqqVqD9DoU1ReEQIKSD6l_zfJvtEQ_vkEWa6sJnE,
unit SAID/digest: "ExPnZXqy1EE9mVL7dRlUdlZ_rJ8K3c4QGwR1tQame8pc"
**********************************************************************
END_OCA_MANIFEST

BEGIN_OCA_BUNDLE
**********************************************************************
Layer name: capture_base/1.0
SAID/digest: EXcTABzZLzdt6nvvAgvXHUtprQrmdx_h-AcENtwOas3s
classification: RDF401

Schema attribute: data type 
   # of Positives: Numeric
   # of Samples: Numeric
   # of Violations: Numeric
   Analyte: Text
   Chemical Class: Text
   MRL (ppm): Numeric
   Max (ppm): Numeric
   Mean (ppm): Numeric
   Min (ppm): Numeric
   Product: Text
   Testing Program: Text
   Total # of Samples tested: Numeric
   Total Vio of Product: Numeric
   Year of MRL: Numeric
   vio/products: Numeric

**********************************************************************
Layer name: meta/1.0
SAID/digest: Eg9agqqVqD9DoU1ReEQIKSD6l_zfJvtEQ_vkEWa6sJnE
language: en
name: NCRMP Fresh Fruits and Vegetables 2020-2121
description: Data taken from the National Chemical Residue Monitoring Program files relating to pesticide residue on fresh fruits and vegetables in the 2020-2021 cohort.
**********************************************************************
Layer name: character_encoding/1.0
SAID/digest: E4SPFppen4nh_krorszG86FHFJPT19JJ9qi_xp9mKo8E
default_character_encoding: utf-8

Schema attribute: character_encoding/1.0 
   # of Positives: utf-8
   # of Samples: utf-8
   # of Violations: utf-8
   Analyte: utf-8
   Chemical Class: utf-8
   MRL (ppm): utf-8
   Max (ppm): utf-8
   Mean (ppm): utf-8
   Min (ppm): utf-8
   Product: utf-8
   Testing Program: utf-8
   Total # of Samples tested: utf-8
   Total Vio of Product: utf-8
   Year of MRL: utf-8
   vio/products: utf-8

**********************************************************************
Layer name: conformance/1.0
SAID/digest: EjYvNx1K6radvwfUs-ealxqiJ_bhPQR7seNjFY9zSIKo

Schema attribute: conformance/1.0 
   # of Positives: O
   # of Samples: O
   # of Violations: O
   Analyte: M
   Chemical Class: O
   MRL (ppm): O
   Max (ppm): O
   Mean (ppm): O
   Min (ppm): O
   Product: M
   Testing Program: M
   Total # of Samples tested: O
   Total Vio of Product: O
   Year of MRL: O
   vio/products: O

**********************************************************************
Layer name: entry/1.0
SAID/digest: EyMlskXQUpc43GhKZ0ZQsCCVZviwfoT2nyYzdoAdYey4
language: en

Schema attribute: entry/1.0 
   Analyte: 
      24-D: 24-D
      24-dimethylaniline: 24-dimethylaniline
      Acephate: Acephate
      Acetamiprid: Acetamiprid
      AminomethylPhosphonic Acid: AminomethylPhosphonic Acid
      Atrazine+Desethyl Atrazine: Atrazine+Desethyl Atrazine
      Azoxystrobin: Azoxystrobin
      Bifenazate: Bifenazate
      Bifenthrin: Bifenthrin
      Biphenyl: Biphenyl
      Boscalid: Boscalid
      Buprofezin: Buprofezin
      CARBENDAZIM/THIOPHANATE METHYL: CARBENDAZIM/THIOPHANATE METHYL
      Captan: Captan
      Captan metabolite (THPI): Captan metabolite (THPI)
      Carbaryl: Carbaryl
      Chlorantraniliprole: Chlorantraniliprole
      Chlordane: Chlordane
      Chlorfenapyr: Chlorfenapyr
      Chlorothalonil: Chlorothalonil
      Chlorpropham: Chlorpropham
      Chlorpyrifos: Chlorpyrifos
      Chlorpyrifos-methyl: Chlorpyrifos-methyl
      Chlorthal-dimethyl (Dacthal): Chlorthal-dimethyl (Dacthal)
      Clomazone: Clomazone
      Clopyralid: Clopyralid
      Clothianidin: Clothianidin
      Cyantraniliprole: Cyantraniliprole
      Cyazofamid: Cyazofamid
      Cyhalothrin-lambda: Cyhalothrin-lambda
      Cypermethrin: Cypermethrin
      Cyprodinil: Cyprodinil
      Cyromazine: Cyromazine
      DDT plus metabolites: DDT plus metabolites
      Daminozide: Daminozide
      Deltamethrin: Deltamethrin
      Dicofol: Dicofol
      Dieldrin: Dieldrin
      Difenoconazole: Difenoconazole
      Dimethoate: Dimethoate
      Dimethoate+Metabolite Omethoate: Dimethoate+Metabolite Omethoate
      Dimethomorph: Dimethomorph
      Diphenamid: Diphenamid
      Diphenylamine: Diphenylamine
      Diquat: Diquat
      Dithiocarbamate: Dithiocarbamate
      Endosulfan Total: Endosulfan Total
      Epoxiconazole: Epoxiconazole
      Ethiofencarb: Ethiofencarb
      Ethylene Thiourea: Ethylene Thiourea
      Etoxazole: Etoxazole
      FLUPYRADIFURONE: FLUPYRADIFURONE
      Famoxadone: Famoxadone
      Fenamidone: Fenamidone
      Fenazaquin: Fenazaquin
      Fenbuconazole: Fenbuconazole
      Fenhexamid: Fenhexamid
      Fenpropathrin: Fenpropathrin
      Fenpropimorph: Fenpropimorph
      Fenpyroximate: Fenpyroximate
      Flonicamid: Flonicamid
      Fludioxonil: Fludioxonil
      Fluoxastrobin: Fluoxastrobin
      Flutriafol: Flutriafol
      Folpet: Folpet
      Fuberidazole: Fuberidazole
      Glyphosate: Glyphosate
      Glyphosate Screen: Glyphosate Screen
      Heptachlor expoxide: Heptachlor expoxide
      Hexythiazox: Hexythiazox
      Imazalil: Imazalil
      Imidacloprid: Imidacloprid
      Iprodione: Iprodione
      Kresoxim-methyl: Kresoxim-methyl
      Linuron: Linuron
      Malathion: Malathion
      Mandipropamid: Mandipropamid
      Mepanipyrim: Mepanipyrim
      Metalaxyl: Metalaxyl
      Metconazole: Metconazole
      Methamidophos: Methamidophos
      Methoxyfenozide: Methoxyfenozide
      Metolachlor: Metolachlor
      Metribuzin: Metribuzin
      Myclobutanil: Myclobutanil
      Novaluron: Novaluron
      Omethoate: Omethoate
      Ortho-phenylphenol: Ortho-phenylphenol
      Oxadixyl: Oxadixyl
      Oxamyl Oxime+Oxamyl: Oxamyl Oxime+Oxamyl
      Oxyfluorfen: Oxyfluorfen
      Pendimethalin: Pendimethalin
      Permethrin (Total): Permethrin (Total)
      Pesticide Screen: Pesticide Screen
      Phenoxy Herbicides Screen: Phenoxy Herbicides Screen
      Phosmet: Phosmet
      Piperonyl butoxide: Piperonyl butoxide
      Prochloraz: Prochloraz
      Prometryne: Prometryne
      Pronamide: Pronamide
      Propamocarb: Propamocarb
      Propiconazole: Propiconazole
      Pymetrozine: Pymetrozine
      Pyraclostrobin: Pyraclostrobin
      Pyridaben: Pyridaben
      Pyrimethanil: Pyrimethanil
      Pyriproxyfen: Pyriproxyfen
      Quat Screen: Quat Screen
      Quinoxyfen: Quinoxyfen
      Spinetoram: Spinetoram
      Spinosad (total): Spinosad (total)
      Spirodiclofen: Spirodiclofen
      Spiromesifen: Spiromesifen
      Spirotetramat: Spirotetramat
      Tebuconazole: Tebuconazole
      Tebufenozide: Tebufenozide
      Tepraloxydim: Tepraloxydim
      Tetraconazole: Tetraconazole
      Thiabendazole: Thiabendazole
      Thiacloprid: Thiacloprid
      Thiamethoxam: Thiamethoxam
      Triazophos: Triazophos
      Trifloxystrobin: Trifloxystrobin
      Trifluralin: Trifluralin
      Zinophos: Zinophos
      fluopyram: fluopyram
      pp'-DDE: pp'-DDE
   
   Product: 
      Apple: Apple
      Bean: Bean
      Beet: Beet
      Blackberry: Blackberry
      Blueberry: Blueberry
      Broccoli: Broccoli
      Brussels Sprout: Brussels Sprout
      Cabbage: Cabbage
      Cabbage - Chinese: Cabbage - Chinese
      Carrot: Carrot
      Cauliflower: Cauliflower
      Celery: Celery
      Cherry: Cherry
      Corn: Corn
      Cranberry: Cranberry
      Cucumber: Cucumber
      Eggplant: Eggplant
      Garlic - Fresh: Garlic - Fresh
      Grape: Grape
      Herb - Chive - Fresh: Herb - Chive - Fresh
      Herb - Cilantro - Fresh: Herb - Cilantro - Fresh
      Herb - Dill - Fresh: Herb - Dill - Fresh
      Herb - Mint - Fresh: Herb - Mint - Fresh
      Herb - Parsley - Fresh: Herb - Parsley - Fresh
      Herb - Thyme - Fresh: Herb - Thyme - Fresh
      Kale: Kale
      Leek: Leek
      Lettuce - Head: Lettuce - Head
      Lettuce - Leaf: Lettuce - Leaf
      Melon: Melon
      Melon - Cantaloupe: Melon - Cantaloupe
      Mushroom: Mushroom
      Nectarine: Nectarine
      Onion: Onion
      Onion - Green: Onion - Green
      Parsnip: Parsnip
      Pea: Pea
      Peach: Peach
      Pear: Pear
      Pepper: Pepper
      Plum: Plum
      Potato: Potato
      Radicchio: Radicchio
      Radish: Radish
      Raspberry: Raspberry
      Rutabaga: Rutabaga
      Spinach: Spinach
      Sprout - Bean: Sprout - Bean
      Squash: Squash
      Strawberry: Strawberry
      Tomato: Tomato
      Turnip: Turnip
      Zucchini: Zucchini
   
   Testing Program: 
      ALAR: ALAR
      AMITRAZ: AMITRAZ
      DIQUAT/PARAQUAT: DIQUAT/PARAQUAT
      EBDC(CS2): EBDC(CS2)
      EBDC(ETU): EBDC(ETU)
      GLYPHOSATE: GLYPHOSATE
      PESTICIDES-F: PESTICIDES-F
      PESTICIDES-GCLC: PESTICIDES-GCLC
      PESTICIDES-LC: PESTICIDES-LC
      PHENOXY HERBICIDES: PHENOXY HERBICIDES
   

**********************************************************************
Layer name: entry_code/1.0
SAID/digest: EDWhTwcsaUErgj0ndQTX7YptiDj8GIvrnabgA04RmwdI

Schema attribute: entry_code/1.0 
   Analyte: [Daminozide,2,4-dimethylaniline,Dithiocarbamate,EthyleneThiourea,GlyphosateScreen,Glyphosate,PesticideScreen,Acetamiprid,Bifenazate,Biphenyl,Boscalid,Captan,Captanmetabolite(THPI),Carbaryl,CARBENDAZIM/THIOPHANATEMETHYL,Chlorantraniliprole,Chlorpropham,Cyantraniliprole,Cyhalothrin-lambda,Cypermethrin,Cyprodinil,DDTplusmetabolites,Deltamethrin,Dicofol,Difenoconazole,Dimethoate+MetaboliteOmethoate,Diphenylamine,Flonicamid,Fludioxonil,fluopyram,FLUPYRADIFURONE,Flutriafol,Folpet,Imidacloprid,Methoxyfenozide,Myclobutanil,Novaluron,Ortho-phenylphenol,Oxadixyl,Permethrin(Total),Phosmet,Piperonylbutoxide,Prochloraz,Pyraclostrobin,Pyridaben,Pyrimethanil,Quinoxyfen,Spinetoram,Spinosad(total),Spirodiclofen,Spirotetramat,Tebuconazole,Thiabendazole,Thiacloprid,Trifloxystrobin,PhenoxyHerbicidesScreen,Chlorthal-dimethyl(Dacthal),Azoxystrobin,Dieldrin,Clopyralid,Fenhexamid,Malathion,Bifenthrin,Chlorothalonil,Fenpropathrin,Clothianidin,Dimethoate,Mandipropamid,Propamocarb,Thiamethoxam,Metalaxyl,Dimethomorph,Buprofezin,Chlorpyrifos,Diphenamid,Fenamidone,Fenpropimorph,Iprodione,Linuron,Metolachlor,Pendimethalin,Trifluralin,EndosulfanTotal,Ethiofencarb,OxamylOxime+Oxamyl,Triazophos,Fenbuconazole,Metconazole,Epoxiconazole,Tepraloxydim,Zinophos,Chlorfenapyr,Cyromazine,Fenazaquin,Fenpyroximate,Propiconazole,Pymetrozine,Spiromesifen,Tebufenozide,Kresoxim-methyl,Mepanipyrim,QuatScreen,Acephate,Methamidophos,Fuberidazole,Omethoate,Oxyfluorfen,Prometryne,AminomethylPhosphonicAcid,Atrazine+DesethylAtrazine,Hexythiazox,Diquat,Chlorpyrifos-methyl,Etoxazole,Pronamide,2,4-D,Metribuzin,Chlordane,Clomazone,Heptachlorexpoxide,p,p'-DDE,Fluoxastrobin,Tetraconazole,Cyazofamid,Famoxadone,Imazalil,Pyriproxyfen]
   Product: [Apple,Bean,Beet,Blackberry,Blueberry,Broccoli,BrusselsSprout,Cabbage,Cabbage-Chinese,Carrot,Cauliflower,Celery,Cherry,Corn,Cranberry,Cucumber,Eggplant,Garlic-Fresh,Grape,Herb-Chive-Fresh,Herb-Cilantro-Fresh,Herb-Dill-Fresh,Herb-Mint-Fresh,Herb-Parsley-Fresh,Herb-Thyme-Fresh,Kale,Leek,Lettuce-Head,Lettuce-Leaf,Melon,Melon-Cantaloupe,Mushroom,Nectarine,Onion,Onion-Green,Parsnip,Pea,Peach,Pear,Pepper,Plum,Potato,Radicchio,Radish,Raspberry,Rutabaga,Spinach,Sprout-Bean,Squash,Strawberry,Tomato,Turnip,Zucchini]
   Testing Program: [ALAR,AMITRAZ,EBDC(CS2),EBDC(ETU),GLYPHOSATE,PESTICIDES-GCLC,PHENOXYHERBICIDES,PESTICIDES-F,PESTICIDES-LC,DIQUAT/PARAQUAT]

**********************************************************************
Layer name: information/1.0
SAID/digest: EQUr6nTzZ1rR3qFDgjCjh9kH2yJwueXSivNlQj2vBWnw
language: en

Schema attribute: information/1.0 
   # of Positives: The number of pesticides that left residue on the product
   # of Samples: The number of samples taken from the product for each pesticide test
   # of Violations: The number of pesticide residue violations (the residue amount is over the prescribed limit/MRL) for each individual pesticide
   Analyte: The specific pesticide being examined for residue. One testing program can test for various pesticides this will break it down into the individual values
   Chemical Class: The substance being tested for in this case pesticides
   MRL (ppm): The maximum residue limit. Determined by the government of Canada changes for each pesticide and product combination
   Max (ppm): The highest amount of pesticide residue found on the product in part per million
   Mean (ppm): The mean amount of pesticide residue found on the product in part per million
   Min (ppm): The lowest amount of pesticide residue found on the product in part per million
   Product: The specific fresh fruit/vegetable/other that was tested for residue
   Testing Program: The type of testing program being used on the product
   Total # of Samples tested: The overall number of samples tested for a product
   Total Vio of Product: The total number of violations a singular product received ignoring which specific pesticide caused the violation
   Year of MRL: The year the MRL was established/updated
   vio/products: The number of violations per product calculated by dividing the total number of violations by the total number of samples tested for each product

**********************************************************************
Layer name: label/1.0
SAID/digest: EK9YcxhW6bQB-UZwGJdwTwlVEx3ktQR-ofvlkncplqL4
language: en

Schema attribute: label/1.0 
   # of Positives: Num_Pos
   # of Samples: Num_Samples
   # of Violations: Num_Vio
   Analyte: Analyte
   Chemical Class: Chem_Class
   MRL (ppm): MRL
   Max (ppm): Max
   Mean (ppm): Mean
   Min (ppm): Min
   Product: Product
   Testing Program: Test_Program
   Total # of Samples tested: Total_Samples
   Total Vio of Product: Total_Vio
   Year of MRL: Year_MRL
   vio/products: Vio_Pro

**********************************************************************
Layer name: unit/1.0
SAID/digest: ExPnZXqy1EE9mVL7dRlUdlZ_rJ8K3c4QGwR1tQame8pc

Schema attribute: unit/1.0 
   MRL (ppm): ppm
   Max (ppm): ppm
   Mean (ppm): ppm
   Min (ppm): ppm

**********************************************************************
END_OCA_BUNDLE
