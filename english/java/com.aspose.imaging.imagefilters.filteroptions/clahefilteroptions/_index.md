---
title: ClaheFilterOptions
second_title: Aspose.Imaging for Java API Reference
description: Provides options for configuring the Contrast-Limited Adaptive Histogram Equalization CLAHE filter.
type: docs
weight: 14
url: /java/com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class ClaheFilterOptions extends FilterOptionsBase
```

Provides options for configuring the Contrast-Limited Adaptive Histogram Equalization (CLAHE) filter.
## Constructors

| Constructor | Description |
| --- | --- |
| [ClaheFilterOptions()](#ClaheFilterOptions--) |  |
| [ClaheFilterOptions(boolean isGrayscale)](#ClaheFilterOptions-boolean-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal)](#ClaheFilterOptions-boolean-int-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical)](#ClaheFilterOptions-boolean-int-int-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit)](#ClaheFilterOptions-boolean-int-int-double-) | Initializes a new instance of the [ClaheFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions) class with the specified parameters. |
## Methods

| Method | Description |
| --- | --- |
| [isGrayscale()](#isGrayscale--) | Gets a value indicating whether the filter operates in grayscale mode. |
| [getTilesNumberHorizontal()](#getTilesNumberHorizontal--) | Gets the number of tiles in the horizontal direction. |
| [getTilesNumberVertical()](#getTilesNumberVertical--) | Gets the number of tiles in the vertical direction. |
| [getClipLimit()](#getClipLimit--) | Gets the contrast limiting threshold. |
### ClaheFilterOptions() {#ClaheFilterOptions--}
```
public ClaheFilterOptions()
```


### ClaheFilterOptions(boolean isGrayscale) {#ClaheFilterOptions-boolean-}
```
public ClaheFilterOptions(boolean isGrayscale)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isGrayscale | boolean |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal) {#ClaheFilterOptions-boolean-int-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isGrayscale | boolean |  |
| tilesNumberHorizontal | int |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical) {#ClaheFilterOptions-boolean-int-int-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isGrayscale | boolean |  |
| tilesNumberHorizontal | int |  |
| tilesNumberVertical | int |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit) {#ClaheFilterOptions-boolean-int-int-double-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit)
```


Initializes a new instance of the [ClaheFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions) class with the specified parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isGrayscale | boolean | Indicates whether the filter should operate in grayscale mode. |
| tilesNumberHorizontal | int | Number of tiles horizontally. Default is 8. |
| tilesNumberVertical | int | Number of tiles vertically. Default is 8. |
| clipLimit | double | Contrast limiting threshold. Default is 4.0. |

### isGrayscale() {#isGrayscale--}
```
public final boolean isGrayscale()
```


Gets a value indicating whether the filter operates in grayscale mode.

**Returns:**
boolean - a value indicating whether the filter operates in grayscale mode.
### getTilesNumberHorizontal() {#getTilesNumberHorizontal--}
```
public final int getTilesNumberHorizontal()
```


Gets the number of tiles in the horizontal direction. Determines how many regions the image is divided into horizontally for local contrast equalization.

**Returns:**
int - the number of tiles in the horizontal direction.
### getTilesNumberVertical() {#getTilesNumberVertical--}
```
public final int getTilesNumberVertical()
```


Gets the number of tiles in the vertical direction. Determines how many regions the image is divided into vertically for local contrast equalization.

**Returns:**
int - the number of tiles in the vertical direction.
### getClipLimit() {#getClipLimit--}
```
public final double getClipLimit()
```


Gets the contrast limiting threshold. Higher values allow more contrast; lower values limit the enhancement to prevent noise amplification.

**Returns:**
double - the contrast limiting threshold.
