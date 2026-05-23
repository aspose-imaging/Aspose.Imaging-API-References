---
title: "AutoWhiteBalanceFilterOptions klass"
type: docs
weight: 20
url: /sv/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/
---

**Summary:** Provides configuration options for the Auto White Balance filter.<br/>            Allows tuning of contrast stretching parameters and channel scaling<br/>            to improve the appearance of digital images.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.AutoWhiteBalanceFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset)](#AutoWhiteBalanceFilterOptions_low_percentile_target_high_percentile_target_value_max_scale_protected_dark_offset_1) | Initierar en ny instans av klassen [AutoWhiteBalanceFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| low_percentile | int | r | Den låga percentilen för svartpunkt, används för skydd av mörka områden (standard: 3). |
| max_scale | float | r | Hämtar den maximala skalningsfaktorn för varje kanal.<br/>            Begränsar förstärkningen av någon kanal för att undvika överdrivna färgskiftningar. |
| protected_dark_offset | int | r | Offset från låg percentil under vilken mörka pixlar inte sträcks (skydd). |
| target_high_percentile | int | r | Hämtar mål‑högpercentilen för kontrastutsträckning.<br/>            Bestämmer vilken ljusstyrke‑percentil som kommer att mappas till mål‑värdet. |
| target_value | int | r | Hämtar mål‑värdet för den höga percentilen.<br/>            Detta värde kommer att användas som vit referens för kontrastutsträckning. |


### Constructor: AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset) {#AutoWhiteBalanceFilterOptions_low_percentile_target_high_percentile_target_value_max_scale_protected_dark_offset_1}


```
 AutoWhiteBalanceFilterOptions(low_percentile, target_high_percentile, target_value, max_scale, protected_dark_offset) 
```

Initierar en ny instans av klassen [AutoWhiteBalanceFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| low_percentile | int | Den låga percentilen för svartpunkt, används för skydd av mörka områden (standard: 3). |
| target_high_percentile | int | Den målade högpercentilen för kontrastutsträckning (standard 97). |
| target_value | int | Målvärdet för den höga percentilen (standard 255). |
| max_scale | float | Den maximala skalningsfaktorn för varje kanal (standard 1.4f). |
| protected_dark_offset | int | Offset från låg percentil under vilken mörka pixlar inte sträcks (skydd). |

