---
title: AdaptiveWhiteStretchFilterOptions
second_title: Aspose.Imaging for Java API Reference
description: Provides options for configuring the Adaptive White Stretch filter.
type: docs
weight: 10
url: /java/com.aspose.imaging.imagefilters.filteroptions/adaptivewhitestretchfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class AdaptiveWhiteStretchFilterOptions extends FilterOptionsBase
```

Provides options for configuring the Adaptive White Stretch filter. Allows customization of histogram stretch parameters to enhance the white level and improve the readability of faint-text or low-contrast document images.
## Constructors

| Constructor | Description |
| --- | --- |
| [AdaptiveWhiteStretchFilterOptions()](#AdaptiveWhiteStretchFilterOptions--) | Initializes a new instance of the AdaptiveWhiteStretchFilter class. |
| [AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale)](#AdaptiveWhiteStretchFilterOptions-boolean-int-int-int-float-) | Initializes a new instance of the AdaptiveWhiteStretchFilter class. |
## Methods

| Method | Description |
| --- | --- |
| [isGrayscale()](#isGrayscale--) | Gets a value indicating whether the filter operates in grayscale mode. |
| [getLowPercentile()](#getLowPercentile--) | Gets the lower percentile for black point calculation. |
| [getHighPercentile()](#getHighPercentile--) | Gets the upper percentile for white point calculation. |
| [getTargetWhite()](#getTargetWhite--) | Gets the target white value the stretch aims to achieve. |
| [getMaxScale()](#getMaxScale--) | Gets the maximum allowed brightness scale. |
### AdaptiveWhiteStretchFilterOptions() {#AdaptiveWhiteStretchFilterOptions--}
```
public AdaptiveWhiteStretchFilterOptions()
```


Initializes a new instance of the AdaptiveWhiteStretchFilter class.

### AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale) {#AdaptiveWhiteStretchFilterOptions-boolean-int-int-int-float-}
```
public AdaptiveWhiteStretchFilterOptions(boolean isGrayscale, int lowPercentile, int highPercentile, int targetWhite, float maxScale)
```


Initializes a new instance of the AdaptiveWhiteStretchFilter class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isGrayscale | boolean | Indicates whether the filter should operate in grayscale mode. |
| lowPercentile | int | Lower percentile for black point (e.g. 10). |
| highPercentile | int | Upper percentile for white point (e.g. 90). |
| targetWhite | int | Target white value (e.g. 240). |
| maxScale | float | Maximum allowed brightness scale (e.g. 1.7).

--------------------

The algorithm stretches the histogram so that the white percentile approaches `targetWhite`, but without exceeding `maxScale` to avoid over-brightening. |

### isGrayscale() {#isGrayscale--}
```
public final boolean isGrayscale()
```


Gets a value indicating whether the filter operates in grayscale mode.

**Returns:**
boolean - a value indicating whether the filter operates in grayscale mode.
### getLowPercentile() {#getLowPercentile--}
```
public final int getLowPercentile()
```


Gets the lower percentile for black point calculation. Pixel values below this percentile are considered as black during stretching.

**Returns:**
int - the lower percentile for black point calculation.
### getHighPercentile() {#getHighPercentile--}
```
public final int getHighPercentile()
```


Gets the upper percentile for white point calculation. Pixel values above this percentile are considered as white during stretching.

**Returns:**
int - the upper percentile for white point calculation.
### getTargetWhite() {#getTargetWhite--}
```
public final int getTargetWhite()
```


Gets the target white value the stretch aims to achieve.

**Returns:**
int - the target white value the stretch aims to achieve.
### getMaxScale() {#getMaxScale--}
```
public final float getMaxScale()
```


Gets the maximum allowed brightness scale. The actual stretching will not exceed this factor, to avoid over-brightening.

**Returns:**
float - the maximum allowed brightness scale.
