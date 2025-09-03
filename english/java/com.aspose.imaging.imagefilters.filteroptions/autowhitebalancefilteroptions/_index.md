---
title: AutoWhiteBalanceFilterOptions
second_title: Aspose.Imaging for Java API Reference
description: Provides configuration options for the Auto White Balance filter.
type: docs
weight: 11
url: /java/com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class AutoWhiteBalanceFilterOptions extends FilterOptionsBase
```

Provides configuration options for the Auto White Balance filter. Allows tuning of contrast stretching parameters and channel scaling to improve the appearance of digital images.
## Constructors

| Constructor | Description |
| --- | --- |
| [AutoWhiteBalanceFilterOptions()](#AutoWhiteBalanceFilterOptions--) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile)](#AutoWhiteBalanceFilterOptions-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile)](#AutoWhiteBalanceFilterOptions-int-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue)](#AutoWhiteBalanceFilterOptions-int-int-int-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale)](#AutoWhiteBalanceFilterOptions-int-int-int-float-) |  |
| [AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset)](#AutoWhiteBalanceFilterOptions-int-int-int-float-int-) | Initializes a new instance of the [AutoWhiteBalanceFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getTargetHighPercentile()](#getTargetHighPercentile--) | Gets the target high percentile for contrast stretching. |
| [getTargetValue()](#getTargetValue--) | Gets the target value for the high percentile. |
| [getMaxScale()](#getMaxScale--) | Gets the maximum scaling factor for each channel. |
| [getLowPercentile()](#getLowPercentile--) | The low percentile for black point, used for dark protection (default: 3). |
| [getProtectedDarkOffset()](#getProtectedDarkOffset--) | Offset from low percentile below which dark pixels are not stretched (protection). |
### AutoWhiteBalanceFilterOptions() {#AutoWhiteBalanceFilterOptions--}
```
public AutoWhiteBalanceFilterOptions()
```


### AutoWhiteBalanceFilterOptions(int lowPercentile) {#AutoWhiteBalanceFilterOptions-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lowPercentile | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile) {#AutoWhiteBalanceFilterOptions-int-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue) {#AutoWhiteBalanceFilterOptions-int-int-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |
| targetValue | int |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale) {#AutoWhiteBalanceFilterOptions-int-int-int-float-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lowPercentile | int |  |
| targetHighPercentile | int |  |
| targetValue | int |  |
| maxScale | float |  |

### AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset) {#AutoWhiteBalanceFilterOptions-int-int-int-float-int-}
```
public AutoWhiteBalanceFilterOptions(int lowPercentile, int targetHighPercentile, int targetValue, float maxScale, int protectedDarkOffset)
```


Initializes a new instance of the [AutoWhiteBalanceFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/autowhitebalancefilteroptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lowPercentile | int | The low percentile for black point, used for dark protection (default: 3). |
| targetHighPercentile | int | The target high percentile for contrast stretching (default 97). |
| targetValue | int | The target value for the high percentile (default 255). |
| maxScale | float | The maximum scaling factor for each channel (default 1.4f). |
| protectedDarkOffset | int | Offset from low percentile below which dark pixels are not stretched (protection). |

### getTargetHighPercentile() {#getTargetHighPercentile--}
```
public final int getTargetHighPercentile()
```


Gets the target high percentile for contrast stretching. Determines which brightness percentile will be mapped to the target value.

**Returns:**
int - the target high percentile for contrast stretching.
### getTargetValue() {#getTargetValue--}
```
public final int getTargetValue()
```


Gets the target value for the high percentile. This value will be used as the white reference for contrast stretching.

**Returns:**
int - the target value for the high percentile.
### getMaxScale() {#getMaxScale--}
```
public final float getMaxScale()
```


Gets the maximum scaling factor for each channel. Restricts the amplification of any channel to avoid excessive color shifts.

**Returns:**
float - the maximum scaling factor for each channel.
### getLowPercentile() {#getLowPercentile--}
```
public final int getLowPercentile()
```


The low percentile for black point, used for dark protection (default: 3).

**Returns:**
int
### getProtectedDarkOffset() {#getProtectedDarkOffset--}
```
public final int getProtectedDarkOffset()
```


Offset from low percentile below which dark pixels are not stretched (protection).

**Returns:**
int
