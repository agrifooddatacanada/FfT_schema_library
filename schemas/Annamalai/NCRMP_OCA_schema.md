---
layout: default  
title: NCRMP Fresh Fruits and Vegetables 2020-2121  
parent: Manick Annamalai - PI
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: NCRMP Fresh Fruits and Vegetables 2020-2121  
**Description**: Data taken from the National Chemical Residue Monitoring Program files relating to pesticide residue on fresh fruits and vegetables in the 2020-2021 cohort.  
**Classification**: RDF401  
**Author**: Rebecca Fong  
**Author Email**: fongr@uoguelph.ca  

[Download Schema](NCRMP_OCA_bundle.zip)  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| # of Positives | Num_Pos | The number of pesticides that left residue on the product |
| # of Samples | Num_Samples | The number of samples taken from the product for each pesticide test |
| # of Violations | Num_Vio | The number of pesticide residue violations (the residue amount is over the prescribed limit/MRL) for each individual pesticide |
| Analyte | Analyte | The specific pesticide being examined for residue. One testing program can test for various pesticides, this will break it down into the individual values |
| Chemical Class | Chem_Class | The substance being tested for, in this case pesticides |
| MRL (ppm) | MRL | The maximum residue limit. Determined by the government of Canada, changes for each pesticide and product combination |
| Max (ppm) | Max | The highest amount of pesticide residue found on the product in part per million |
| Mean (ppm) | Mean | The mean amount of pesticide residue found on the product in part per million |
| Min (ppm) | Min | The lowest amount of pesticide residue found on the product in part per million |
| Product | Product | The specific fresh fruit/vegetable/other that was tested for residue |
| Testing Program | Test_Program | The type of testing program being used on the product |
| Total # of Samples tested | Total_Samples | The overall number of samples tested for a product |
| Total Vio of Product | Total_Vio | The total number of violations a singular product received, ignoring which specific pesticide caused the violation |
| Year of MRL | Year_MRL | The year the MRL was established/updated |
| vio/products | Vio_Pro | The number of violations per product, calculated by dividing the total number of violations by the total number of samples tested for each product |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | NCRMP Fresh Fruits and Vegetables 2020-2121 | Data taken from the National Chemical Residue Monitoring Program files relating to pesticide residue on fresh fruits and vegetables in the 2020-2021 cohort. |

## Selection lists

### English

#### Analyte entry codes

| Entry code | Label |
| --- | --- |
| 2,4-D | 2,4-D |
| 2,4-dimethylaniline | 2,4-dimethylaniline |
| Acephate | Acephate |
| Acetamiprid | Acetamiprid |
| AminomethylPhosphonic Acid | AminomethylPhosphonic Acid |
| Atrazine+Desethyl Atrazine | Atrazine+Desethyl Atrazine |
| Azoxystrobin | Azoxystrobin |
| Bifenazate | Bifenazate |
| Bifenthrin | Bifenthrin |
| Biphenyl | Biphenyl |
| Boscalid | Boscalid |
| Buprofezin | Buprofezin |
| CARBENDAZIM/THIOPHANATE METHYL | CARBENDAZIM/THIOPHANATE METHYL |
| Captan | Captan |
| Captan metabolite (THPI) | Captan metabolite (THPI) |
| Carbaryl | Carbaryl |
| Chlorantraniliprole | Chlorantraniliprole |
| Chlordane | Chlordane |
| Chlorfenapyr | Chlorfenapyr |
| Chlorothalonil | Chlorothalonil |
| Chlorpropham | Chlorpropham |
| Chlorpyrifos | Chlorpyrifos |
| Chlorpyrifos-methyl | Chlorpyrifos-methyl |
| Chlorthal-dimethyl (Dacthal) | Chlorthal-dimethyl (Dacthal) |
| Clomazone | Clomazone |
| Clopyralid | Clopyralid |
| Clothianidin | Clothianidin |
| Cyantraniliprole | Cyantraniliprole |
| Cyazofamid | Cyazofamid |
| Cyhalothrin-lambda | Cyhalothrin-lambda |
| Cypermethrin | Cypermethrin |
| Cyprodinil | Cyprodinil |
| Cyromazine | Cyromazine |
| DDT plus metabolites | DDT plus metabolites |
| Daminozide | Daminozide |
| Deltamethrin | Deltamethrin |
| Dicofol | Dicofol |
| Dieldrin | Dieldrin |
| Difenoconazole | Difenoconazole |
| Dimethoate | Dimethoate |
| Dimethoate+Metabolite Omethoate | Dimethoate+Metabolite Omethoate |
| Dimethomorph | Dimethomorph |
| Diphenamid | Diphenamid |
| Diphenylamine | Diphenylamine |
| Diquat | Diquat |
| Dithiocarbamate | Dithiocarbamate |
| Endosulfan Total | Endosulfan Total |
| Epoxiconazole | Epoxiconazole |
| Ethiofencarb | Ethiofencarb |
| Ethylene Thiourea | Ethylene Thiourea |
| Etoxazole | Etoxazole |
| FLUPYRADIFURONE | FLUPYRADIFURONE |
| Famoxadone | Famoxadone |
| Fenamidone | Fenamidone |
| Fenazaquin | Fenazaquin |
| Fenbuconazole | Fenbuconazole |
| Fenhexamid | Fenhexamid |
| Fenpropathrin | Fenpropathrin |
| Fenpropimorph | Fenpropimorph |
| Fenpyroximate | Fenpyroximate |
| Flonicamid | Flonicamid |
| Fludioxonil | Fludioxonil |
| Fluoxastrobin | Fluoxastrobin |
| Flutriafol | Flutriafol |
| Folpet | Folpet |
| Fuberidazole | Fuberidazole |
| Glyphosate | Glyphosate |
| Glyphosate Screen | Glyphosate Screen |
| Heptachlor expoxide | Heptachlor expoxide |
| Hexythiazox | Hexythiazox |
| Imazalil | Imazalil |
| Imidacloprid | Imidacloprid |
| Iprodione | Iprodione |
| Kresoxim-methyl | Kresoxim-methyl |
| Linuron | Linuron |
| Malathion | Malathion |
| Mandipropamid | Mandipropamid |
| Mepanipyrim | Mepanipyrim |
| Metalaxyl | Metalaxyl |
| Metconazole | Metconazole |
| Methamidophos | Methamidophos |
| Methoxyfenozide | Methoxyfenozide |
| Metolachlor | Metolachlor |
| Metribuzin | Metribuzin |
| Myclobutanil | Myclobutanil |
| Novaluron | Novaluron |
| Omethoate | Omethoate |
| Ortho-phenylphenol | Ortho-phenylphenol |
| Oxadixyl | Oxadixyl |
| Oxamyl Oxime+Oxamyl | Oxamyl Oxime+Oxamyl |
| Oxyfluorfen | Oxyfluorfen |
| Pendimethalin | Pendimethalin |
| Permethrin (Total) | Permethrin (Total) |
| Pesticide Screen | Pesticide Screen |
| Phenoxy Herbicides Screen | Phenoxy Herbicides Screen |
| Phosmet | Phosmet |
| Piperonyl butoxide | Piperonyl butoxide |
| Prochloraz | Prochloraz |
| Prometryne | Prometryne |
| Pronamide | Pronamide |
| Propamocarb | Propamocarb |
| Propiconazole | Propiconazole |
| Pymetrozine | Pymetrozine |
| Pyraclostrobin | Pyraclostrobin |
| Pyridaben | Pyridaben |
| Pyrimethanil | Pyrimethanil |
| Pyriproxyfen | Pyriproxyfen |
| Quat Screen | Quat Screen |
| Quinoxyfen | Quinoxyfen |
| Spinetoram | Spinetoram |
| Spinosad (total) | Spinosad (total) |
| Spirodiclofen | Spirodiclofen |
| Spiromesifen | Spiromesifen |
| Spirotetramat | Spirotetramat |
| Tebuconazole | Tebuconazole |
| Tebufenozide | Tebufenozide |
| Tepraloxydim | Tepraloxydim |
| Tetraconazole | Tetraconazole |
| Thiabendazole | Thiabendazole |
| Thiacloprid | Thiacloprid |
| Thiamethoxam | Thiamethoxam |
| Triazophos | Triazophos |
| Trifloxystrobin | Trifloxystrobin |
| Trifluralin | Trifluralin |
| Zinophos | Zinophos |
| fluopyram | fluopyram |
| p,p'-DDE | p,p'-DDE |

#### Product entry codes

| Entry code | Label |
| --- | --- |
| Apple | Apple |
| Bean | Bean |
| Beet | Beet |
| Blackberry | Blackberry |
| Blueberry | Blueberry |
| Broccoli | Broccoli |
| Brussels Sprout | Brussels Sprout |
| Cabbage | Cabbage |
| Cabbage - Chinese | Cabbage - Chinese |
| Carrot | Carrot |
| Cauliflower | Cauliflower |
| Celery | Celery |
| Cherry | Cherry |
| Corn | Corn |
| Cranberry | Cranberry |
| Cucumber | Cucumber |
| Eggplant | Eggplant |
| Garlic - Fresh | Garlic - Fresh |
| Grape | Grape |
| Herb - Chive - Fresh | Herb - Chive - Fresh |
| Herb - Cilantro - Fresh | Herb - Cilantro - Fresh |
| Herb - Dill - Fresh | Herb - Dill - Fresh |
| Herb - Mint - Fresh | Herb - Mint - Fresh |
| Herb - Parsley - Fresh | Herb - Parsley - Fresh |
| Herb - Thyme - Fresh | Herb - Thyme - Fresh |
| Kale | Kale |
| Leek | Leek |
| Lettuce - Head | Lettuce - Head |
| Lettuce - Leaf | Lettuce - Leaf |
| Melon | Melon |
| Melon - Cantaloupe | Melon - Cantaloupe |
| Mushroom | Mushroom |
| Nectarine | Nectarine |
| Onion | Onion |
| Onion - Green | Onion - Green |
| Parsnip | Parsnip |
| Pea | Pea |
| Peach | Peach |
| Pear | Pear |
| Pepper | Pepper |
| Plum | Plum |
| Potato | Potato |
| Radicchio | Radicchio |
| Radish | Radish |
| Raspberry | Raspberry |
| Rutabaga | Rutabaga |
| Spinach | Spinach |
| Sprout - Bean | Sprout - Bean |
| Squash | Squash |
| Strawberry | Strawberry |
| Tomato | Tomato |
| Turnip | Turnip |
| Zucchini | Zucchini |

#### Testing Program entry codes

| Entry code | Label |
| --- | --- |
| ALAR | ALAR |
| AMITRAZ | AMITRAZ |
| DIQUAT/PARAQUAT | DIQUAT/PARAQUAT |
| EBDC(CS2) | EBDC(CS2) |
| EBDC(ETU) | EBDC(ETU) |
| GLYPHOSATE | GLYPHOSATE |
| PESTICIDES-F | PESTICIDES-F |
| PESTICIDES-GCLC | PESTICIDES-GCLC |
| PESTICIDES-LC | PESTICIDES-LC |
| PHENOXY HERBICIDES | PHENOXY HERBICIDES |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Required entry |
| --- | --- | --- | --- | --- | --- |
| # of Positives | false |  | Numeric | utf-8 | false |
| # of Samples | false |  | Numeric | utf-8 | false |
| # of Violations | false |  | Numeric | utf-8 | false |
| Analyte | false |  | Text | utf-8 | true |
| Chemical Class | false |  | Text | utf-8 | false |
| MRL (ppm) | false | ppm | Numeric | utf-8 | false |
| Max (ppm) | false | ppm | Numeric | utf-8 | false |
| Mean (ppm) | false | ppm | Numeric | utf-8 | false |
| Min (ppm) | false | ppm | Numeric | utf-8 | false |
| Product | false |  | Text | utf-8 | true |
| Testing Program | false |  | Text | utf-8 | true |
| Total # of Samples tested | false |  | Numeric | utf-8 | false |
| Total Vio of Product | false |  | Numeric | utf-8 | false |
| Year of MRL | false |  | Numeric | utf-8 | false |
| vio/products | false |  | Numeric | utf-8 | false |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| # of Positives | Num_Pos | The number of pesticides that left residue on the product | Not a list |
| # of Samples | Num_Samples | The number of samples taken from the product for each pesticide test | Not a list |
| # of Violations | Num_Vio | The number of pesticide residue violations (the residue amount is over the prescribed limit/MRL) for each individual pesticide | Not a list |
| Analyte | Analyte | The specific pesticide being examined for residue. One testing program can test for various pesticides, this will break it down into the individual values | 2,4-D, 2,4-dimethylaniline, Acephate, Acetamiprid, AminomethylPhosphonic Acid, Atrazine+Desethyl Atrazine, Azoxystrobin, Bifenazate, Bifenthrin, Biphenyl, Boscalid, Buprofezin, CARBENDAZIM/THIOPHANATE METHYL, Captan, Captan metabolite (THPI), Carbaryl, Chlorantraniliprole, Chlordane, Chlorfenapyr, Chlorothalonil, Chlorpropham, Chlorpyrifos, Chlorpyrifos-methyl, Chlorthal-dimethyl (Dacthal), Clomazone, Clopyralid, Clothianidin, Cyantraniliprole, Cyazofamid, Cyhalothrin-lambda, Cypermethrin, Cyprodinil, Cyromazine, DDT plus metabolites, Daminozide, Deltamethrin, Dicofol, Dieldrin, Difenoconazole, Dimethoate, Dimethoate+Metabolite Omethoate, Dimethomorph, Diphenamid, Diphenylamine, Diquat, Dithiocarbamate, Endosulfan Total, Epoxiconazole, Ethiofencarb, Ethylene Thiourea, Etoxazole, FLUPYRADIFURONE, Famoxadone, Fenamidone, Fenazaquin, Fenbuconazole, Fenhexamid, Fenpropathrin, Fenpropimorph, Fenpyroximate, Flonicamid, Fludioxonil, Fluoxastrobin, Flutriafol, Folpet, Fuberidazole, Glyphosate, Glyphosate Screen, Heptachlor expoxide, Hexythiazox, Imazalil, Imidacloprid, Iprodione, Kresoxim-methyl, Linuron, Malathion, Mandipropamid, Mepanipyrim, Metalaxyl, Metconazole, Methamidophos, Methoxyfenozide, Metolachlor, Metribuzin, Myclobutanil, Novaluron, Omethoate, Ortho-phenylphenol, Oxadixyl, Oxamyl Oxime+Oxamyl, Oxyfluorfen, Pendimethalin, Permethrin (Total), Pesticide Screen, Phenoxy Herbicides Screen, Phosmet, Piperonyl butoxide, Prochloraz, Prometryne, Pronamide, Propamocarb, Propiconazole, Pymetrozine, Pyraclostrobin, Pyridaben, Pyrimethanil, Pyriproxyfen, Quat Screen, Quinoxyfen, Spinetoram, Spinosad (total), Spirodiclofen, Spiromesifen, Spirotetramat, Tebuconazole, Tebufenozide, Tepraloxydim, Tetraconazole, Thiabendazole, Thiacloprid, Thiamethoxam, Triazophos, Trifloxystrobin, Trifluralin, Zinophos, fluopyram, p,p'-DDE |
| Chemical Class | Chem_Class | The substance being tested for, in this case pesticides | Not a list |
| MRL (ppm) | MRL | The maximum residue limit. Determined by the government of Canada, changes for each pesticide and product combination | Not a list |
| Max (ppm) | Max | The highest amount of pesticide residue found on the product in part per million | Not a list |
| Mean (ppm) | Mean | The mean amount of pesticide residue found on the product in part per million | Not a list |
| Min (ppm) | Min | The lowest amount of pesticide residue found on the product in part per million | Not a list |
| Product | Product | The specific fresh fruit/vegetable/other that was tested for residue | Apple, Bean, Beet, Blackberry, Blueberry, Broccoli, Brussels Sprout, Cabbage, Cabbage - Chinese, Carrot, Cauliflower, Celery, Cherry, Corn, Cranberry, Cucumber, Eggplant, Garlic - Fresh, Grape, Herb - Chive - Fresh, Herb - Cilantro - Fresh, Herb - Dill - Fresh, Herb - Mint - Fresh, Herb - Parsley - Fresh, Herb - Thyme - Fresh, Kale, Leek, Lettuce - Head, Lettuce - Leaf, Melon, Melon - Cantaloupe, Mushroom, Nectarine, Onion, Onion - Green, Parsnip, Pea, Peach, Pear, Pepper, Plum, Potato, Radicchio, Radish, Raspberry, Rutabaga, Spinach, Sprout - Bean, Squash, Strawberry, Tomato, Turnip, Zucchini |
| Testing Program | Test_Program | The type of testing program being used on the product | ALAR, AMITRAZ, DIQUAT/PARAQUAT, EBDC(CS2), EBDC(ETU), GLYPHOSATE, PESTICIDES-F, PESTICIDES-GCLC, PESTICIDES-LC, PHENOXY HERBICIDES |
| Total # of Samples tested | Total_Samples | The overall number of samples tested for a product | Not a list |
| Total Vio of Product | Total_Vio | The total number of violations a singular product received, ignoring which specific pesticide caused the violation | Not a list |
| Year of MRL | Year_MRL | The year the MRL was established/updated | Not a list |
| vio/products | Vio_Pro | The number of violations per product, calculated by dividing the total number of violations by the total number of samples tested for each product | Not a list |

## Schema SAIDs

**Capture base**: EXcTABzZLzdt6nvvAgvXHUtprQrmdx_h-AcENtwOas3s

| Layer | SAID |
| --- | --- |
| character_encoding | E4SPFppen4nh_krorszG86FHFJPT19JJ9qi_xp9mKo8E |
| conformance | EjYvNx1K6radvwfUs-ealxqiJ_bhPQR7seNjFY9zSIKo |
| entry (en) | EyMlskXQUpc43GhKZ0ZQsCCVZviwfoT2nyYzdoAdYey4 |
| entry_code | EDWhTwcsaUErgj0ndQTX7YptiDj8GIvrnabgA04RmwdI |
| information (en) | EQUr6nTzZ1rR3qFDgjCjh9kH2yJwueXSivNlQj2vBWnw |
| label (en) | EK9YcxhW6bQB-UZwGJdwTwlVEx3ktQR-ofvlkncplqL4 |
| meta (en) | Eg9agqqVqD9DoU1ReEQIKSD6l_zfJvtEQ_vkEWa6sJnE |
| unit | ExPnZXqy1EE9mVL7dRlUdlZ_rJ8K3c4QGwR1tQame8pc |

**Date created**: 2024-12-11 08:33:31

