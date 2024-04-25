---
title: JpegLsPresetCodingParameters
second_title: Aspose.Imaging for Java API Reference
description: Defines the JPEG-LS preset coding parameters as defined in ISO/IEC 14495-1 C.2.4.1.1.
type: docs
weight: 16
url: /com.aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters/
---
**Inheritance:**
java.lang.Object
```
public class JpegLsPresetCodingParameters
```

Defines the JPEG-LS preset coding parameters as defined in ISO/IEC 14495-1, C.2.4.1.1. JPEG-LS defines a default set of parameters, but custom parameters can be used. When used these parameters are written into the encoded bit stream as they are needed for the decoding process.
## Constructors

| Constructor | Description |
| --- | --- |
| [JpegLsPresetCodingParameters()](#JpegLsPresetCodingParameters--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getMaximumSampleValue()](#getMaximumSampleValue--) | Gets or sets the maximum possible value for any image sample in a scan. |
| [setMaximumSampleValue(int value)](#setMaximumSampleValue-int-) | Gets or sets the maximum possible value for any image sample in a scan. |
| [getThreshold1()](#getThreshold1--) | Gets or sets the first quantization threshold value for the local gradients. |
| [setThreshold1(int value)](#setThreshold1-int-) | Gets or sets the first quantization threshold value for the local gradients. |
| [getThreshold2()](#getThreshold2--) | Gets or sets the second quantization threshold value for the local gradients. |
| [setThreshold2(int value)](#setThreshold2-int-) | Gets or sets the second quantization threshold value for the local gradients. |
| [getThreshold3()](#getThreshold3--) | Gets or sets the third quantization threshold value for the local gradients. |
| [setThreshold3(int value)](#setThreshold3-int-) | Gets or sets the third quantization threshold value for the local gradients. |
| [getResetValue()](#getResetValue--) | Gets or sets the value at which the counters A, B, and N are halved. |
| [setResetValue(int value)](#setResetValue-int-) | Gets or sets the value at which the counters A, B, and N are halved. |
### JpegLsPresetCodingParameters() {#JpegLsPresetCodingParameters--}
```
public JpegLsPresetCodingParameters()
```


### getMaximumSampleValue() {#getMaximumSampleValue--}
```
public int getMaximumSampleValue()
```


Gets or sets the maximum possible value for any image sample in a scan. This must be greater than or equal to the actual maximum value for the components in a scan.

**Returns:**
int
### setMaximumSampleValue(int value) {#setMaximumSampleValue-int-}
```
public void setMaximumSampleValue(int value)
```


Gets or sets the maximum possible value for any image sample in a scan. This must be greater than or equal to the actual maximum value for the components in a scan.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getThreshold1() {#getThreshold1--}
```
public int getThreshold1()
```


Gets or sets the first quantization threshold value for the local gradients.

**Returns:**
int
### setThreshold1(int value) {#setThreshold1-int-}
```
public void setThreshold1(int value)
```


Gets or sets the first quantization threshold value for the local gradients.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getThreshold2() {#getThreshold2--}
```
public int getThreshold2()
```


Gets or sets the second quantization threshold value for the local gradients.

**Returns:**
int
### setThreshold2(int value) {#setThreshold2-int-}
```
public void setThreshold2(int value)
```


Gets or sets the second quantization threshold value for the local gradients.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getThreshold3() {#getThreshold3--}
```
public int getThreshold3()
```


Gets or sets the third quantization threshold value for the local gradients.

**Returns:**
int
### setThreshold3(int value) {#setThreshold3-int-}
```
public void setThreshold3(int value)
```


Gets or sets the third quantization threshold value for the local gradients.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getResetValue() {#getResetValue--}
```
public int getResetValue()
```


Gets or sets the value at which the counters A, B, and N are halved.

**Returns:**
int
### setResetValue(int value) {#setResetValue-int-}
```
public void setResetValue(int value)
```


Gets or sets the value at which the counters A, B, and N are halved.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

