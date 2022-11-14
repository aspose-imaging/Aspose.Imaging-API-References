---
title: DeconvolutionFilterOptions
second_title: Aspose.Imaging for Java API Reference
description: Deconvolution Filter Options abstract class
type: docs
weight: 13
url: /java/com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public abstract class DeconvolutionFilterOptions extends FilterOptionsBase
```

Deconvolution Filter Options, abstract class
## Methods

| Method | Description |
| --- | --- |
| [getSnr()](#getSnr--) | Gets or sets the SNR(signal-to-noise ratio) recommended range 0.002 - 0.009, default value = 0.007 |
| [setSnr(double value)](#setSnr-double-) | Gets or sets the SNR(signal-to-noise ratio) recommended range 0.002 - 0.009, default value = 0.007 |
| [getBrightness()](#getBrightness--) | Gets or sets the brightness. |
| [setBrightness(double value)](#setBrightness-double-) | Gets or sets the brightness. |
| [getGrayscale()](#getGrayscale--) | Gets or sets a value indicating whether this `DeconvolutionFilterOptions` is grayscale. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Gets or sets a value indicating whether this `DeconvolutionFilterOptions` is grayscale. |
| [isPartialLoaded()](#isPartialLoaded--) | Gets a value indicating whether this instance is partial loaded. |
### getSnr() {#getSnr--}
```
public double getSnr()
```


Gets or sets the SNR(signal-to-noise ratio) recommended range 0.002 - 0.009, default value = 0.007

Value: The SNR.

**Returns:**
double
### setSnr(double value) {#setSnr-double-}
```
public void setSnr(double value)
```


Gets or sets the SNR(signal-to-noise ratio) recommended range 0.002 - 0.009, default value = 0.007

Value: The SNR.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getBrightness() {#getBrightness--}
```
public double getBrightness()
```


Gets or sets the brightness. recommended range 1 - 1.5 default value = 1.15

Value: The brightness.

**Returns:**
double
### setBrightness(double value) {#setBrightness-double-}
```
public void setBrightness(double value)
```


Gets or sets the brightness. recommended range 1 - 1.5 default value = 1.15

Value: The brightness.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getGrayscale() {#getGrayscale--}
```
public boolean getGrayscale()
```


Gets or sets a value indicating whether this `DeconvolutionFilterOptions` is grayscale. Return grayscale mode or RGB mode.

Value: `true` if grayscale; otherwise, `false`.

**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public void setGrayscale(boolean value)
```


Gets or sets a value indicating whether this `DeconvolutionFilterOptions` is grayscale. Return grayscale mode or RGB mode.

Value: `true` if grayscale; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isPartialLoaded() {#isPartialLoaded--}
```
public boolean isPartialLoaded()
```


Gets a value indicating whether this instance is partial loaded.

Value: `true` if this instance is partial loaded; otherwise, `false`.

**Returns:**
boolean
