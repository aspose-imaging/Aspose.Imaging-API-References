---
title: EmfPlusCustomLineCapData
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusCustomLineCapData object specifies default data for a custom line cap.
type: docs
weight: 36
url: /com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomBaseLineCap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustombaselinecap)
```
public final class EmfPlusCustomLineCapData extends EmfPlusCustomBaseLineCap
```

The EmfPlusCustomLineCapData object specifies default data for a custom line cap.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusCustomLineCapData()](#EmfPlusCustomLineCapData--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getCustomLineCapDataFlags()](#getCustomLineCapDataFlags--) | Gets or sets 32-bit unsigned integer that specifies the data in the OptionalData field |
| [setCustomLineCapDataFlags(int value)](#setCustomLineCapDataFlags-int-) | Gets or sets 32-bit unsigned integer that specifies the data in the OptionalData field |
| [getBaseCap()](#getBaseCap--) | Gets or sets 32-bit unsigned integer that specifies the value from the LineCap enumeration (section 2.1.1.18) on which the custom line cap is based. |
| [setBaseCap(int value)](#setBaseCap-int-) | Gets or sets 32-bit unsigned integer that specifies the value from the LineCap enumeration (section 2.1.1.18) on which the custom line cap is based. |
| [getBaseInset()](#getBaseInset--) | Gets or sets 32-bit floating-point value that specifies the distance between the beginning of the line cap and the end of the line. |
| [setBaseInset(float value)](#setBaseInset-float-) | Gets or sets 32-bit floating-point value that specifies the distance between the beginning of the line cap and the end of the line. |
| [getStrokeStartCap()](#getStrokeStartCap--) | Gets or sets 32-bit unsigned integer that specifies the value in the LineCap enumeration that indicates the line cap used at the start of the line to be drawn |
| [setStrokeStartCap(int value)](#setStrokeStartCap-int-) | Gets or sets 32-bit unsigned integer that specifies the value in the LineCap enumeration that indicates the line cap used at the start of the line to be drawn |
| [getStrokeEndCap()](#getStrokeEndCap--) | Gets or sets 32-bit unsigned integer that specifies the value in the LineCap enumeration that indicates what line cap is to be used at the end of the line to be drawn. |
| [setStrokeEndCap(int value)](#setStrokeEndCap-int-) | Gets or sets 32-bit unsigned integer that specifies the value in the LineCap enumeration that indicates what line cap is to be used at the end of the line to be drawn. |
| [getStrokeJoin()](#getStrokeJoin--) | Gets or sets 32-bit unsigned integer that specifies the value in the LineJoin enumeration (section 2.1.1.19), which specifies how to join two lines that are drawn by the same pen and whose ends meet. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Gets or sets 32-bit unsigned integer that specifies the value in the LineJoin enumeration (section 2.1.1.19), which specifies how to join two lines that are drawn by the same pen and whose ends meet. |
| [getStrokeMiterLimit()](#getStrokeMiterLimit--) | Gets or sets 32-bit floating-point value that contains the limit of the thickness of the join on a mitered corner by setting the maximum allowed ratio of miter length to line width. |
| [setStrokeMiterLimit(float value)](#setStrokeMiterLimit-float-) | Gets or sets 32-bit floating-point value that contains the limit of the thickness of the join on a mitered corner by setting the maximum allowed ratio of miter length to line width. |
| [getWidthScale()](#getWidthScale--) | Gets or sets 32-bit floating-point value that specifies the amount by which to scale the custom line cap with respect to the width of the EmfPlusPen object (section 2.2.1.7) that is used to draw the lines. |
| [setWidthScale(float value)](#setWidthScale-float-) | Gets or sets 32-bit floating-point value that specifies the amount by which to scale the custom line cap with respect to the width of the EmfPlusPen object (section 2.2.1.7) that is used to draw the lines. |
| [getFillHotSpot()](#getFillHotSpot--) | Gets or sets EmfPlusPointF object that is not currently used. |
| [setFillHotSpot(PointF value)](#setFillHotSpot-com.aspose.imaging.PointF-) | Gets or sets EmfPlusPointF object that is not currently used. |
| [getStrokeHotSpot()](#getStrokeHotSpot--) | Gets or sets EmfPlusPointF object that is not currently used. |
| [setStrokeHotSpot(PointF value)](#setStrokeHotSpot-com.aspose.imaging.PointF-) | Gets or sets EmfPlusPointF object that is not currently used. |
| [getOptionalData()](#getOptionalData--) | Gets or sets optional EmfPlusCustomLineCapOptionalData object (section 2.2.2.14) that specifies additional data for the custom graphics line cap. |
| [setOptionalData(EmfPlusCustomLineCapOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData-) | Gets or sets optional EmfPlusCustomLineCapOptionalData object (section 2.2.2.14) that specifies additional data for the custom graphics line cap. |
### EmfPlusCustomLineCapData() {#EmfPlusCustomLineCapData--}
```
public EmfPlusCustomLineCapData()
```


### getCustomLineCapDataFlags() {#getCustomLineCapDataFlags--}
```
public int getCustomLineCapDataFlags()
```


Gets or sets 32-bit unsigned integer that specifies the data in the OptionalData field

**Returns:**
int
### setCustomLineCapDataFlags(int value) {#setCustomLineCapDataFlags-int-}
```
public void setCustomLineCapDataFlags(int value)
```


Gets or sets 32-bit unsigned integer that specifies the data in the OptionalData field

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


Gets or sets 32-bit unsigned integer that specifies the value from the LineCap enumeration (section 2.1.1.18) on which the custom line cap is based.

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


Gets or sets 32-bit unsigned integer that specifies the value from the LineCap enumeration (section 2.1.1.18) on which the custom line cap is based.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


Gets or sets 32-bit floating-point value that specifies the distance between the beginning of the line cap and the end of the line.

**Returns:**
float
### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


Gets or sets 32-bit floating-point value that specifies the distance between the beginning of the line cap and the end of the line.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getStrokeStartCap() {#getStrokeStartCap--}
```
public int getStrokeStartCap()
```


Gets or sets 32-bit unsigned integer that specifies the value in the LineCap enumeration that indicates the line cap used at the start of the line to be drawn

**Returns:**
int
### setStrokeStartCap(int value) {#setStrokeStartCap-int-}
```
public void setStrokeStartCap(int value)
```


Gets or sets 32-bit unsigned integer that specifies the value in the LineCap enumeration that indicates the line cap used at the start of the line to be drawn

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStrokeEndCap() {#getStrokeEndCap--}
```
public int getStrokeEndCap()
```


Gets or sets 32-bit unsigned integer that specifies the value in the LineCap enumeration that indicates what line cap is to be used at the end of the line to be drawn.

**Returns:**
int
### setStrokeEndCap(int value) {#setStrokeEndCap-int-}
```
public void setStrokeEndCap(int value)
```


Gets or sets 32-bit unsigned integer that specifies the value in the LineCap enumeration that indicates what line cap is to be used at the end of the line to be drawn.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


Gets or sets 32-bit unsigned integer that specifies the value in the LineJoin enumeration (section 2.1.1.19), which specifies how to join two lines that are drawn by the same pen and whose ends meet. At the intersection of the two line ends, a line join makes the connection look more continuous.

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


Gets or sets 32-bit unsigned integer that specifies the value in the LineJoin enumeration (section 2.1.1.19), which specifies how to join two lines that are drawn by the same pen and whose ends meet. At the intersection of the two line ends, a line join makes the connection look more continuous.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStrokeMiterLimit() {#getStrokeMiterLimit--}
```
public float getStrokeMiterLimit()
```


Gets or sets 32-bit floating-point value that contains the limit of the thickness of the join on a mitered corner by setting the maximum allowed ratio of miter length to line width.

**Returns:**
float
### setStrokeMiterLimit(float value) {#setStrokeMiterLimit-float-}
```
public void setStrokeMiterLimit(float value)
```


Gets or sets 32-bit floating-point value that contains the limit of the thickness of the join on a mitered corner by setting the maximum allowed ratio of miter length to line width.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Gets or sets 32-bit floating-point value that specifies the amount by which to scale the custom line cap with respect to the width of the EmfPlusPen object (section 2.2.1.7) that is used to draw the lines.

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Gets or sets 32-bit floating-point value that specifies the amount by which to scale the custom line cap with respect to the width of the EmfPlusPen object (section 2.2.1.7) that is used to draw the lines.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFillHotSpot() {#getFillHotSpot--}
```
public PointF getFillHotSpot()
```


Gets or sets EmfPlusPointF object that is not currently used. It MUST be set to \{0.0, 0.0\}.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setFillHotSpot(PointF value) {#setFillHotSpot-com.aspose.imaging.PointF-}
```
public void setFillHotSpot(PointF value)
```


Gets or sets EmfPlusPointF object that is not currently used. It MUST be set to \{0.0, 0.0\}.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getStrokeHotSpot() {#getStrokeHotSpot--}
```
public PointF getStrokeHotSpot()
```


Gets or sets EmfPlusPointF object that is not currently used. It MUST be set to \{0.0, 0.0\}.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setStrokeHotSpot(PointF value) {#setStrokeHotSpot-com.aspose.imaging.PointF-}
```
public void setStrokeHotSpot(PointF value)
```


Gets or sets EmfPlusPointF object that is not currently used. It MUST be set to \{0.0, 0.0\}.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusCustomLineCapOptionalData getOptionalData()
```


Gets or sets optional EmfPlusCustomLineCapOptionalData object (section 2.2.2.14) that specifies additional data for the custom graphics line cap. T he specific contents of this field are determined by the value of the CustomLineCapDataFlags field.

**Returns:**
[EmfPlusCustomLineCapOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata)
### setOptionalData(EmfPlusCustomLineCapOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData-}
```
public void setOptionalData(EmfPlusCustomLineCapOptionalData value)
```


Gets or sets optional EmfPlusCustomLineCapOptionalData object (section 2.2.2.14) that specifies additional data for the custom graphics line cap. T he specific contents of this field are determined by the value of the CustomLineCapDataFlags field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusCustomLineCapOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata) |  |

