---
title: ClaheFilterOptions Class
type: docs
weight: 50
url: /python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/
---

**Summary:** Provides options for configuring the Contrast-Limited Adaptive Histogram Equalization (CLAHE) filter.

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.ClaheFilterOptions

**Inheritance:** FilterOptionsBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit)](#ClaheFilterOptions_is_grayscale_tiles_number_horizontal_tiles_number_vertical_clip_limit_1) | Initializes a new instance of the [ClaheFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/) class<br/>            with the specified parameters. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| clip_limit | float | r | Gets the contrast limiting threshold.<br/>            Higher values allow more contrast; lower values limit the enhancement to prevent noise amplification. |
| is_grayscale | bool | r | Gets a value indicating whether the filter operates in grayscale mode. |
| tiles_number_horizontal | int | r | Gets the number of tiles in the horizontal direction.<br/>            Determines how many regions the image is divided into horizontally for local contrast equalization. |
| tiles_number_vertical | int | r | Gets the number of tiles in the vertical direction.<br/>            Determines how many regions the image is divided into vertically for local contrast equalization. |


### Constructor: ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit) {#ClaheFilterOptions_is_grayscale_tiles_number_horizontal_tiles_number_vertical_clip_limit_1}


```
 ClaheFilterOptions(is_grayscale, tiles_number_horizontal, tiles_number_vertical, clip_limit) 
```

Initializes a new instance of the [ClaheFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/clahefilteroptions/) class<br/>            with the specified parameters.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| is_grayscale | bool | Indicates whether the filter should operate in grayscale mode. |
| tiles_number_horizontal | int | Number of tiles horizontally. Default is 8. |
| tiles_number_vertical | int | Number of tiles vertically. Default is 8. |
| clip_limit | float | Contrast limiting threshold. Default is 4.0. |

