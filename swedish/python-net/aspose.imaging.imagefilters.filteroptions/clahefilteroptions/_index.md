---
title: "ClaheFilterOptions-klass"
type: docs
weight: 50
url: /sv/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/
---

**Summary:** Provides options for configuring the Contrast-Limited Adaptive Histogram Equalization (CLAHE) filter.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.ClaheFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit)](#ClaheFilterOptions_is_grayscale_tiles_number_horizontal_tiles_number_vertical_clip_limit_1) | Initierar en ny instans av klassen [ClaheFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/)<br/>            med de angivna parametrarna. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| clip_limit | float | r | Hämtar tröskelvärdet för kontrastbegränsning.<br/>            Högre värden ger mer kontrast; lägre värden begränsar förbättringen för att förhindra brusförstärkning. |
| is_grayscale | bool | r | Hämtar ett värde som indikerar om filtret körs i gråskaleläge. |
| tiles_number_horizontal | int | r | Hämtar antalet plattor i horisontell riktning.<br/>            Bestämmer hur många regioner bilden delas in i horisontellt för lokal kontrastutjämning. |
| tiles_number_vertical | int | r | Hämtar antalet plattor i vertikal riktning.<br/>            Bestämmer hur många regioner bilden delas in i vertikalt för lokal kontrastutjämning. |


### Constructor: ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit) {#ClaheFilterOptions_is_grayscale_tiles_number_horizontal_tiles_number_vertical_clip_limit_1}


```
 ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit) 
```

Initierar en ny instans av klassen [ClaheFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/)<br/>            med de angivna parametrarna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| is_grayscale | bool | Anger om filtret ska köras i gråskaleläge. |
| tiles_number_horizontal | int | Antal plattor horisontellt. Standard är 8. |
| tiles_number_vertical | int | Antal plattor vertikalt. Standard är 8. |
| clip_limit | float | Tröskelvärde för kontrastbegränsning. Standard är 4.0. |

