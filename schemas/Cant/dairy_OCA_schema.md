---
layout: default  
title: dairy cow energy balance  
---

# Schema information
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

**Name**: dairy cow energy balance  
**Description**: Automatically collected daily dairy cow data to estimate energy balance  
**Classification**: RDF402  
**Author**: John Cant  
**Author Email**: jcant@uoguelph.ca  

## Schema quick view

| Attribute | Label | Description |
| --- | --- | --- |
| BCS | BCS | body condition score on a 5-point scale |
| BW_raw | BW_raw | raw bodyweight recorded by scale |
| BW_smooth | BW_smooth | bodyweight smoothed by algorithm of choice |
| CH4_g/d | CH4_g/d | total exhaled CH4 output for the day |
| CO2_g/d | CO2_g/d | total respiratory CO2 output for the day |
| CowID | CowID | unique cow identifying number |
| DEI_Mcal/d | DEI_Mcal/d | digestible energy intake for the day |
| DIM | DIM | number of days-in-milk of the cow at the time of measurement |
| DMI_total | DMI_total | total dry matter intake for the day |
| EBal_Mcal/d | EBal_Mcal/d | energy balance of the cow for the day |
| HP_GreenFeed | HP_GreenFeed | heat production for the day according to GreenFeed measurements |
| MEI_Mcal/d | MEI_Mcal/d | metabolizable energy intake for the day |
| NEI_Mcal/d | NEI_Mcal/d | net energy intake for the day |
| NE_milk | NE_milk | milk energy output for the day |
| O2_g/d | O2_g/d | total respiratory O2 consumption for the day |
| PMRintake_asfed | PMRintake_asfed | intake of partial mixed ration for the 24-hour day, as fed |
| PMRintake_dry | PMRintake_dry | intake of partial mixed ration for the 24-hour day, dry matter |
| RE_Mcal/d | RE_Mcal/d | energy recovered in milk and body for the day |
| chgBW_raw | chgBW_raw | raw bodyweight change since previous day |
| chgBW_smooth | chgBW_smooth | smoothed bodyweight change since previous day |
| date | date | year month and day of measurement |
| milkfat_pct | milkfat_pct | fat content of the milk |
| milkfat_yld_g/d | milkfat_yld_g/d | milk fat yield for the day |
| milklac_pct | milklac_pct | lactose content of the milk |
| milklac_yld_g/d | milklac_yld_g/d | milk lactose yield for the day |
| milkprt_pct | milkprt_pct | protein content of the milk |
| milkprt_yld_g/d | milkprt_yld_g/d | milk protein yield for the day |
| milkyld | milkyld | milk yield for the 24-hour day |
| parity | parity | lactation number of the cow |
| pelletdrops_num | pelletdrops_num | number of drops of pellet from GreenFeed system for the day |
| pelletintake_asfed | pelletintake_asfed | intake of pellet from GreenFeed system for the day, as fed |
| pelletintake_dry | pelletintake_dry | intake of pellet from GreenFeed system for the day, dry |

## International schema information

| Language | Name | Description |
| --- | --- | --- |
| English | dairy cow energy balance | Automatically collected daily dairy cow data to estimate energy balance |

## Language-independent schema details

| Attribute | Sensitive | Unit | Type | Character encoding | Format rule |
| --- | --- | --- | --- | --- | --- |
| BCS | false | 1 - 5 | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| BW_raw | false | kg | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| BW_smooth | false | kg | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| CH4_g/d | false | g/d | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| CO2_g/d | false | g/d | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| CowID | true |  | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| DEI_Mcal/d | false | Mcal/d | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| DIM | false |  | Numeric | utf-8 | ^\-?\[0\-9\]\+$ |
| DMI_total | false | kg/d | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| EBal_Mcal/d | false | Mcal/d | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| HP_GreenFeed | false | Mcal/d | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| MEI_Mcal/d | false | Mcal/d | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| NEI_Mcal/d | false | Mcal/d | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| NE_milk | false | Mcal/d | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| O2_g/d | false | g/d | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| PMRintake_asfed | false | kg/d | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| PMRintake_dry | false | kg/d | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| RE_Mcal/d | false | Mcal/d | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| chgBW_raw | false | kg/d | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| chgBW_smooth | false | kg/d | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| date | false |  | DateTime | utf-8 | ^\(\\d\{4\}\)\-\(0\[1\-9\]\|1\[0\-2\]\)\-\(0\[1\-9\]\|\[12\]\\d\|3\[01\]\)$ |
| milkfat_pct | false | % | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| milkfat_yld_g/d | false | g/d | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| milklac_pct | false | % | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| milklac_yld_g/d | false | g/d | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| milkprt_pct | false | % | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| milkprt_yld_g/d | false | g/d | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| milkyld | false | kg/d | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| parity | false |  | Numeric | utf-8 | ^\-?\[0\-9\]\+$ |
| pelletdrops_num | false |  | Numeric | utf-8 | ^\-?\[0\-9\]\+$ |
| pelletintake_asfed | false | kg/d | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |
| pelletintake_dry | false | kg/d | Numeric | utf-8 | ^\[\-\+\]?\\d\*\\\.?\\d\+$ |

## Language-specific schema details

### English

| Attribute | Label | Description | List |
| --- | --- | --- | --- |
| BCS | BCS | body condition score on a 5-point scale | Not a list |
| BW_raw | BW_raw | raw bodyweight recorded by scale | Not a list |
| BW_smooth | BW_smooth | bodyweight smoothed by algorithm of choice | Not a list |
| CH4_g/d | CH4_g/d | total exhaled CH4 output for the day | Not a list |
| CO2_g/d | CO2_g/d | total respiratory CO2 output for the day | Not a list |
| CowID | CowID | unique cow identifying number | Not a list |
| DEI_Mcal/d | DEI_Mcal/d | digestible energy intake for the day | Not a list |
| DIM | DIM | number of days-in-milk of the cow at the time of measurement | Not a list |
| DMI_total | DMI_total | total dry matter intake for the day | Not a list |
| EBal_Mcal/d | EBal_Mcal/d | energy balance of the cow for the day | Not a list |
| HP_GreenFeed | HP_GreenFeed | heat production for the day according to GreenFeed measurements | Not a list |
| MEI_Mcal/d | MEI_Mcal/d | metabolizable energy intake for the day | Not a list |
| NEI_Mcal/d | NEI_Mcal/d | net energy intake for the day | Not a list |
| NE_milk | NE_milk | milk energy output for the day | Not a list |
| O2_g/d | O2_g/d | total respiratory O2 consumption for the day | Not a list |
| PMRintake_asfed | PMRintake_asfed | intake of partial mixed ration for the 24-hour day, as fed | Not a list |
| PMRintake_dry | PMRintake_dry | intake of partial mixed ration for the 24-hour day, dry matter | Not a list |
| RE_Mcal/d | RE_Mcal/d | energy recovered in milk and body for the day | Not a list |
| chgBW_raw | chgBW_raw | raw bodyweight change since previous day | Not a list |
| chgBW_smooth | chgBW_smooth | smoothed bodyweight change since previous day | Not a list |
| date | date | year month and day of measurement | Not a list |
| milkfat_pct | milkfat_pct | fat content of the milk | Not a list |
| milkfat_yld_g/d | milkfat_yld_g/d | milk fat yield for the day | Not a list |
| milklac_pct | milklac_pct | lactose content of the milk | Not a list |
| milklac_yld_g/d | milklac_yld_g/d | milk lactose yield for the day | Not a list |
| milkprt_pct | milkprt_pct | protein content of the milk | Not a list |
| milkprt_yld_g/d | milkprt_yld_g/d | milk protein yield for the day | Not a list |
| milkyld | milkyld | milk yield for the 24-hour day | Not a list |
| parity | parity | lactation number of the cow | Not a list |
| pelletdrops_num | pelletdrops_num | number of drops of pellet from GreenFeed system for the day | Not a list |
| pelletintake_asfed | pelletintake_asfed | intake of pellet from GreenFeed system for the day, as fed | Not a list |
| pelletintake_dry | pelletintake_dry | intake of pellet from GreenFeed system for the day, dry | Not a list |

## Schema SAIDs

**Capture base**: EFBHkqwnrqooS6WjzihH1E7J9uoitRxCDmz0d3GsiPs4

| Layer | SAID |
| --- | --- |
| character_encoding | Eh9LLP26xMpiBPo_xmUo-Ry-f8pHnGm27vFQBrAtFRwI |
| format | EiD5O_5asr8jbP0j4M8gMRlVE6ou9H4kfVdA9bXiKqow |
| information (en) | EZdjoW08mZa9exqSCc3-jiHbCWf9gWgCAuYy55-0jM-Y |
| label (en) | EdX0V-UmaiSTMo2Z_VgWKdbm2okio1DtxbzeSVfTZc2s |
| meta (en) | E-yUp_vbgbN9RgiUwD6xIilcsprCv--4w5yfyfalJ27Q |
| unit | EDya1qbNcqVh2dB4j8dGilYqnd5Ez7jALdXg3qIE7tC0 |

**Date created**: 2025-02-11 10:50:24

