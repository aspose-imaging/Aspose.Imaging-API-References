---
title: EmfScaleWindowExtex
second_title: Aspose.Imaging for Java API Reference
description: The EMR_SCALEWINDOWEXTEX record respecifies the window for a playback device context by using the ratios formed by the specified multiplicands and divisors.
type: docs
weight: 114
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfScaleWindowExtex extends EmfStateRecordType
```

The EMR\_SCALEWINDOWEXTEX record respecifies the window for a playback device context by using the ratios formed by the specified multiplicands and divisors.

The extent cannot be changed if the device context is using a fixed scale mapping mode. Only MM\_ISOTROPIC and MM\_ANISOTROPIC are not fixed scale. The window extents are modified as follows. xNewWE = (xOldWE \* xNum) / xDenom yNewWE = (yOldWE \* yNum) / yDenom
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfScaleWindowExtex(EmfRecord source)](#EmfScaleWindowExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfScaleWindowExtex` class. |
| [EmfScaleWindowExtex()](#EmfScaleWindowExtex--) | Initializes a new instance of the [EmfScaleWindowExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex) class. |
## Methods

| Method | Description |
| --- | --- |
| [getXNum()](#getXNum--) | Gets or sets a 32-bit signed integer that specifies the horizontal multiplicand. |
| [setXNum(int value)](#setXNum-int-) | Gets or sets a 32-bit signed integer that specifies the horizontal multiplicand. |
| [getXDenom()](#getXDenom--) | Gets or sets a 32-bit signed integer that specifies the horizontal divisor. |
| [setXDenom(int value)](#setXDenom-int-) | Gets or sets a 32-bit signed integer that specifies the horizontal divisor. |
| [getYNum()](#getYNum--) | Gets or sets a 32-bit signed integer that specifies the vertical multiplicand. |
| [setYNum(int value)](#setYNum-int-) | Gets or sets a 32-bit signed integer that specifies the vertical multiplicand. |
| [getYDenom()](#getYDenom--) | Gets or sets a 32-bit signed integer that specifies the vertical divisor. |
| [setYDenom(int value)](#setYDenom-int-) | Gets or sets a 32-bit signed integer that specifies the vertical divisor. |
### EmfScaleWindowExtex(EmfRecord source) {#EmfScaleWindowExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfScaleWindowExtex(EmfRecord source)
```


Initializes a new instance of the `EmfScaleWindowExtex` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### EmfScaleWindowExtex() {#EmfScaleWindowExtex--}
```
public EmfScaleWindowExtex()
```


Initializes a new instance of the [EmfScaleWindowExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex) class.

### getXNum() {#getXNum--}
```
public int getXNum()
```


Gets or sets a 32-bit signed integer that specifies the horizontal multiplicand. MUST NOT be zero.

**Returns:**
int
### setXNum(int value) {#setXNum-int-}
```
public void setXNum(int value)
```


Gets or sets a 32-bit signed integer that specifies the horizontal multiplicand. MUST NOT be zero.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getXDenom() {#getXDenom--}
```
public int getXDenom()
```


Gets or sets a 32-bit signed integer that specifies the horizontal divisor. MUST NOT be zero.

**Returns:**
int
### setXDenom(int value) {#setXDenom-int-}
```
public void setXDenom(int value)
```


Gets or sets a 32-bit signed integer that specifies the horizontal divisor. MUST NOT be zero.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getYNum() {#getYNum--}
```
public int getYNum()
```


Gets or sets a 32-bit signed integer that specifies the vertical multiplicand. MUST NOT be zero.

**Returns:**
int
### setYNum(int value) {#setYNum-int-}
```
public void setYNum(int value)
```


Gets or sets a 32-bit signed integer that specifies the vertical multiplicand. MUST NOT be zero.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getYDenom() {#getYDenom--}
```
public int getYDenom()
```


Gets or sets a 32-bit signed integer that specifies the vertical divisor. MUST NOT be zero.

**Returns:**
int
### setYDenom(int value) {#setYDenom-int-}
```
public void setYDenom(int value)
```


Gets or sets a 32-bit signed integer that specifies the vertical divisor. MUST NOT be zero.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

