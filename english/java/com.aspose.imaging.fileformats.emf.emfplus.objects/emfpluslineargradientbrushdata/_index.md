---
title: EmfPlusLinearGradientBrushData
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusLinearGradientBrushData object specifies a linear gradient for a graphics brush.
type: docs
weight: 53
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusLinearGradientBrushData extends EmfPlusBaseBrushData
```

The EmfPlusLinearGradientBrushData object specifies a linear gradient for a graphics brush.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusLinearGradientBrushData()](#EmfPlusLinearGradientBrushData--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | Gets or sets the brush data flags. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | Gets or sets the brush data flags. |
| [getEndArgb32Color()](#getEndArgb32Color--) | Gets or sets the end color. |
| [setEndArgb32Color(int value)](#setEndArgb32Color-int-) | Gets or sets the end color. |
| [getOptionalData()](#getOptionalData--) | Gets or sets the optional data. |
| [setOptionalData(EmfPlusLinearGradientBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData-) | Gets or sets the optional data. |
| [getRectF()](#getRectF--) | Gets or sets the rect f. |
| [setRectF(RectangleF value)](#setRectF-com.aspose.imaging.RectangleF-) | Gets or sets the rect f. |
| [getStartArgb32Color()](#getStartArgb32Color--) | Gets or sets the start color. |
| [setStartArgb32Color(int value)](#setStartArgb32Color-int-) | Gets or sets the start color. |
| [getWrapMode()](#getWrapMode--) | Gets or sets the wrap mode. |
| [setWrapMode(int value)](#setWrapMode-int-) | Gets or sets the wrap mode. |
### EmfPlusLinearGradientBrushData() {#EmfPlusLinearGradientBrushData--}
```
public EmfPlusLinearGradientBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


Gets or sets the brush data flags.

Value: BrushDataFlags (4 bytes): A 32-bit unsigned integer that specifies the data in the OptionalData field. This value MUST be composed of `EmfPlusBrushDataFlags` (section 2.1.2.1).

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


Gets or sets the brush data flags.

Value: BrushDataFlags (4 bytes): A 32-bit unsigned integer that specifies the data in the OptionalData field. This value MUST be composed of `EmfPlusBrushDataFlags` (section 2.1.2.1).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEndArgb32Color() {#getEndArgb32Color--}
```
public int getEndArgb32Color()
```


Gets or sets the end color.

Value: An EmfPlusARGB object that specifies the color at the ending boundary point of the linear gradient brush.

**Returns:**
int
### setEndArgb32Color(int value) {#setEndArgb32Color-int-}
```
public void setEndArgb32Color(int value)
```


Gets or sets the end color.

Value: An EmfPlusARGB object that specifies the color at the ending boundary point of the linear gradient brush.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusLinearGradientBrushOptionalData getOptionalData()
```


Gets or sets the optional data.

Value: An optional `EmfPlusLinearGradientBrushOptionalData` object (section 2.2.2.25) that specifies additional data for the linear gradient brush. The specific contents of this field are determined by the value of the BrushDataFlags field.

**Returns:**
[EmfPlusLinearGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata)
### setOptionalData(EmfPlusLinearGradientBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData-}
```
public void setOptionalData(EmfPlusLinearGradientBrushOptionalData value)
```


Gets or sets the optional data.

Value: An optional `EmfPlusLinearGradientBrushOptionalData` object (section 2.2.2.25) that specifies additional data for the linear gradient brush. The specific contents of this field are determined by the value of the BrushDataFlags field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusLinearGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata) |  |

### getRectF() {#getRectF--}
```
public RectangleF getRectF()
```


Gets or sets the rect f.

Value: An EmfPlusRectF object (section 2.2.2.39) that specifies the starting and ending points of the gradient line. The upper-left corner of the rectangle is the starting point. The lower-right corner is the ending point.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectF(RectangleF value) {#setRectF-com.aspose.imaging.RectangleF-}
```
public void setRectF(RectangleF value)
```


Gets or sets the rect f.

Value: An EmfPlusRectF object (section 2.2.2.39) that specifies the starting and ending points of the gradient line. The upper-left corner of the rectangle is the starting point. The lower-right corner is the ending point.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStartArgb32Color() {#getStartArgb32Color--}
```
public int getStartArgb32Color()
```


Gets or sets the start color.

Value: An EmfPlusARGB object (section 2.2.2.1) that specifies the color at the starting boundary point of the linear gradient brush.

**Returns:**
int
### setStartArgb32Color(int value) {#setStartArgb32Color-int-}
```
public void setStartArgb32Color(int value)
```


Gets or sets the start color.

Value: An EmfPlusARGB object (section 2.2.2.1) that specifies the color at the starting boundary point of the linear gradient brush.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Gets or sets the wrap mode.

Value: A 32-bit signed integer from the WrapMode enumeration (section 2.1.1.34) that specifies whether to paint the area outside the boundary of the brush. When painting outside the boundary, the wrap mode specifies how the color gradient is repeated.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Gets or sets the wrap mode.

Value: A 32-bit signed integer from the WrapMode enumeration (section 2.1.1.34) that specifies whether to paint the area outside the boundary of the brush. When painting outside the boundary, the wrap mode specifies how the color gradient is repeated.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

