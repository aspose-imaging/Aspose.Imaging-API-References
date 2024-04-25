---
title: EmfPlusPenOptionalData
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusPenOptionalData object specifies optional data for a graphics pen
type: docs
weight: 65
url: /com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPenOptionalData extends EmfPlusStructureObjectType
```

The EmfPlusPenOptionalData object specifies optional data for a graphics pen
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusPenOptionalData()](#EmfPlusPenOptionalData--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a world space to device space transform for the pen. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a world space to device space transform for the pen. |
| [getStartCap()](#getStartCap--) | Gets or sets an optional 32-bit signed integer that specifies the shape for the start of a line in the CustomStartCapData field. |
| [setStartCap(int value)](#setStartCap-int-) | Gets or sets an optional 32-bit signed integer that specifies the shape for the start of a line in the CustomStartCapData field. |
| [getEndCap()](#getEndCap--) | Gets or sets optional 32-bit signed integer that specifies the shape for the end of a line in the CustomEndCapData field. |
| [setEndCap(int value)](#setEndCap-int-) | Gets or sets optional 32-bit signed integer that specifies the shape for the end of a line in the CustomEndCapData field. |
| [getJoin()](#getJoin--) | Gets or sets an optional 32-bit signed integer that specifies how to join two lines that are drawn by the same pen and whose ends meet. |
| [setJoin(int value)](#setJoin-int-) | Gets or sets an optional 32-bit signed integer that specifies how to join two lines that are drawn by the same pen and whose ends meet. |
| [getMiterLimit()](#getMiterLimit--) | Gets or sets optional 32-bit floating-point value that specifies the miter limit, which is the maximum allowed ratio of miter length to line width. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Gets or sets optional 32-bit floating-point value that specifies the miter limit, which is the maximum allowed ratio of miter length to line width. |
| [getLineStyle()](#getLineStyle--) | Gets or sets optional 32-bit signed integer that specifies the style used for lines drawn with this pen object. |
| [setLineStyle(int value)](#setLineStyle-int-) | Gets or sets optional 32-bit signed integer that specifies the style used for lines drawn with this pen object. |
| [getDashedLineCapType()](#getDashedLineCapType--) | Gets or sets optional 32-bit signed integer that specifies the shape for both ends of each dash in a dashed line. |
| [setDashedLineCapType(int value)](#setDashedLineCapType-int-) | Gets or sets optional 32-bit signed integer that specifies the shape for both ends of each dash in a dashed line. |
| [getDashOffset()](#getDashOffset--) | Gets or sets optional 32-bit floating-point value that specifies the distance from the start of a line to the start of the first space in a dashed line pattern. |
| [setDashOffset(float value)](#setDashOffset-float-) | Gets or sets optional 32-bit floating-point value that specifies the distance from the start of a line to the start of the first space in a dashed line pattern. |
| [getDashedLineData()](#getDashedLineData--) | Gets or sets optional EmfPlusDashedLineData object (section 2.2.2.16) that specifies the lengths of dashes and spaces in a custom dashed line. |
| [setDashedLineData(EmfPlusDashedLineData value)](#setDashedLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusDashedLineData-) | Gets or sets optional EmfPlusDashedLineData object (section 2.2.2.16) that specifies the lengths of dashes and spaces in a custom dashed line. |
| [getPenAlignment()](#getPenAlignment--) | Gets or sets optional 32-bit signed integer that specifies the distribution of the pen width with respect to the coordinates of the line being drawn. |
| [setPenAlignment(int value)](#setPenAlignment-int-) | Gets or sets optional 32-bit signed integer that specifies the distribution of the pen width with respect to the coordinates of the line being drawn. |
| [getCompoundLineData()](#getCompoundLineData--) | Gets or sets optional EmfPlusCompoundLineData object (section 2.2.2.9) that specifies an array of floating-point values that define the compound line of a pen, which is made up of parallel lines and spaces. |
| [setCompoundLineData(EmfPlusCompoundLineData value)](#setCompoundLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCompoundLineData-) | Gets or sets optional EmfPlusCompoundLineData object (section 2.2.2.9) that specifies an array of floating-point values that define the compound line of a pen, which is made up of parallel lines and spaces. |
| [getCustomStartCapData()](#getCustomStartCapData--) | Gets or sets optional EmfPlusCustomStartCapData object (section 2.2.2.15) that defines the custom start-cap shape, which is the shape to use at the start of a line drawn with this pen. |
| [setCustomStartCapData(EmfPlusCustomStartCapData value)](#setCustomStartCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomStartCapData-) | Gets or sets optional EmfPlusCustomStartCapData object (section 2.2.2.15) that defines the custom start-cap shape, which is the shape to use at the start of a line drawn with this pen. |
| [getCustomEndCapData()](#getCustomEndCapData--) | Gets or sets optional EmfPlusCustomEndCapData object (section 2.2.2.11) that defines the custom end-cap shape, which is the shape to use at the end of a line drawn with this pen. |
| [setCustomEndCapData(EmfPlusCustomEndCapData value)](#setCustomEndCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomEndCapData-) | Gets or sets optional EmfPlusCustomEndCapData object (section 2.2.2.11) that defines the custom end-cap shape, which is the shape to use at the end of a line drawn with this pen. |
### EmfPlusPenOptionalData() {#EmfPlusPenOptionalData--}
```
public EmfPlusPenOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a world space to device space transform for the pen. This field MUST be present if the PenDataTransform flag is set in the PenDataFlags field of the EmfPlusPenData object.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Gets or sets an optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies a world space to device space transform for the pen. This field MUST be present if the PenDataTransform flag is set in the PenDataFlags field of the EmfPlusPenData object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Gets or sets an optional 32-bit signed integer that specifies the shape for the start of a line in the CustomStartCapData field. This field MUST be present if the PenDataStartCap flag is set in the PenDataFlags field of the EmfPlusPenData object, and the value MUST be defined in the LineCapType enumeration (section 2.1.1.18).

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Gets or sets an optional 32-bit signed integer that specifies the shape for the start of a line in the CustomStartCapData field. This field MUST be present if the PenDataStartCap flag is set in the PenDataFlags field of the EmfPlusPenData object, and the value MUST be defined in the LineCapType enumeration (section 2.1.1.18).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Gets or sets optional 32-bit signed integer that specifies the shape for the end of a line in the CustomEndCapData field. This field MUST be present if the PenDataEndCap flag is set in the PenDataFlags field of the EmfPlusPenData object, and the value MUST be defined in the LineCapType enumeration

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Gets or sets optional 32-bit signed integer that specifies the shape for the end of a line in the CustomEndCapData field. This field MUST be present if the PenDataEndCap flag is set in the PenDataFlags field of the EmfPlusPenData object, and the value MUST be defined in the LineCapType enumeration

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getJoin() {#getJoin--}
```
public int getJoin()
```


Gets or sets an optional 32-bit signed integer that specifies how to join two lines that are drawn by the same pen and whose ends meet. This field MUST be present if the PenDataJoin flag is set in the PenDataFlags field of the EmfPlusPenData object, and the value MUST be defined in the LineJoinType enumeration (section 2.1.1.19).

**Returns:**
int
### setJoin(int value) {#setJoin-int-}
```
public void setJoin(int value)
```


Gets or sets an optional 32-bit signed integer that specifies how to join two lines that are drawn by the same pen and whose ends meet. This field MUST be present if the PenDataJoin flag is set in the PenDataFlags field of the EmfPlusPenData object, and the value MUST be defined in the LineJoinType enumeration (section 2.1.1.19).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Gets or sets optional 32-bit floating-point value that specifies the miter limit, which is the maximum allowed ratio of miter length to line width. The miter length is the distance from the intersection of the line walls on the inside the join to the intersection of the line walls outside the join. The miter length can be large when the angle between two lines is small. This field MUST be present if the PenDataMiterLimit flag is set in the PenDataFlags field of the EmfPlusPenData object.

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Gets or sets optional 32-bit floating-point value that specifies the miter limit, which is the maximum allowed ratio of miter length to line width. The miter length is the distance from the intersection of the line walls on the inside the join to the intersection of the line walls outside the join. The miter length can be large when the angle between two lines is small. This field MUST be present if the PenDataMiterLimit flag is set in the PenDataFlags field of the EmfPlusPenData object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLineStyle() {#getLineStyle--}
```
public int getLineStyle()
```


Gets or sets optional 32-bit signed integer that specifies the style used for lines drawn with this pen object. This field MUST be present if the PenDataLineStyle flag is set in the PenDataFlags field of the EmfPlusPenData object, and the value MUST be defined in the LineStyle enumeration (section 2.1.1.20).

**Returns:**
int
### setLineStyle(int value) {#setLineStyle-int-}
```
public void setLineStyle(int value)
```


Gets or sets optional 32-bit signed integer that specifies the style used for lines drawn with this pen object. This field MUST be present if the PenDataLineStyle flag is set in the PenDataFlags field of the EmfPlusPenData object, and the value MUST be defined in the LineStyle enumeration (section 2.1.1.20).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDashedLineCapType() {#getDashedLineCapType--}
```
public int getDashedLineCapType()
```


Gets or sets optional 32-bit signed integer that specifies the shape for both ends of each dash in a dashed line. This field MUST be present if the PenDataDashedLineCap flag is set in the PenDataFlags field of the EmfPlusPenData object, and the value MUST be defined in the DashedLineCapType enumeration (section 2.1.1.10).

**Returns:**
int
### setDashedLineCapType(int value) {#setDashedLineCapType-int-}
```
public void setDashedLineCapType(int value)
```


Gets or sets optional 32-bit signed integer that specifies the shape for both ends of each dash in a dashed line. This field MUST be present if the PenDataDashedLineCap flag is set in the PenDataFlags field of the EmfPlusPenData object, and the value MUST be defined in the DashedLineCapType enumeration (section 2.1.1.10).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Gets or sets optional 32-bit floating-point value that specifies the distance from the start of a line to the start of the first space in a dashed line pattern. This field MUST be present if the PenDataDashedLineOffset flag is set in the PenDataFlags field of the EmfPlusPenData object.

**Returns:**
float
### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Gets or sets optional 32-bit floating-point value that specifies the distance from the start of a line to the start of the first space in a dashed line pattern. This field MUST be present if the PenDataDashedLineOffset flag is set in the PenDataFlags field of the EmfPlusPenData object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDashedLineData() {#getDashedLineData--}
```
public EmfPlusDashedLineData getDashedLineData()
```


Gets or sets optional EmfPlusDashedLineData object (section 2.2.2.16) that specifies the lengths of dashes and spaces in a custom dashed line. This field MUST be present if the PenDataDashedLine flag is set in the PenDataFlags field of the EmfPlusPenData object.

**Returns:**
[EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata)
### setDashedLineData(EmfPlusDashedLineData value) {#setDashedLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusDashedLineData-}
```
public void setDashedLineData(EmfPlusDashedLineData value)
```


Gets or sets optional EmfPlusDashedLineData object (section 2.2.2.16) that specifies the lengths of dashes and spaces in a custom dashed line. This field MUST be present if the PenDataDashedLine flag is set in the PenDataFlags field of the EmfPlusPenData object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata) |  |

### getPenAlignment() {#getPenAlignment--}
```
public int getPenAlignment()
```


Gets or sets optional 32-bit signed integer that specifies the distribution of the pen width with respect to the coordinates of the line being drawn. This field MUST be present if the PenDataNonCenter flag is set in the PenDataFlags field of the EmfPlusPenData object, and the value MUST be defined in the PenAlignment enumeration (section 2.1.1.24).

**Returns:**
int
### setPenAlignment(int value) {#setPenAlignment-int-}
```
public void setPenAlignment(int value)
```


Gets or sets optional 32-bit signed integer that specifies the distribution of the pen width with respect to the coordinates of the line being drawn. This field MUST be present if the PenDataNonCenter flag is set in the PenDataFlags field of the EmfPlusPenData object, and the value MUST be defined in the PenAlignment enumeration (section 2.1.1.24).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCompoundLineData() {#getCompoundLineData--}
```
public EmfPlusCompoundLineData getCompoundLineData()
```


Gets or sets optional EmfPlusCompoundLineData object (section 2.2.2.9) that specifies an array of floating-point values that define the compound line of a pen, which is made up of parallel lines and spaces. This field MUST be present if the PenDataCompoundLine flag is set in the PenDataFlags field of the EmfPlusPenData object

**Returns:**
[EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata)
### setCompoundLineData(EmfPlusCompoundLineData value) {#setCompoundLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCompoundLineData-}
```
public void setCompoundLineData(EmfPlusCompoundLineData value)
```


Gets or sets optional EmfPlusCompoundLineData object (section 2.2.2.9) that specifies an array of floating-point values that define the compound line of a pen, which is made up of parallel lines and spaces. This field MUST be present if the PenDataCompoundLine flag is set in the PenDataFlags field of the EmfPlusPenData object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata) |  |

### getCustomStartCapData() {#getCustomStartCapData--}
```
public EmfPlusCustomStartCapData getCustomStartCapData()
```


Gets or sets optional EmfPlusCustomStartCapData object (section 2.2.2.15) that defines the custom start-cap shape, which is the shape to use at the start of a line drawn with this pen. It can be any of various shapes, such as a square, circle, or diamond. This field MUST be present if the PenDataCustomStartCap flag is set in the PenDataFlags field of the EmfPlusPenData object

**Returns:**
[EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata)
### setCustomStartCapData(EmfPlusCustomStartCapData value) {#setCustomStartCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomStartCapData-}
```
public void setCustomStartCapData(EmfPlusCustomStartCapData value)
```


Gets or sets optional EmfPlusCustomStartCapData object (section 2.2.2.15) that defines the custom start-cap shape, which is the shape to use at the start of a line drawn with this pen. It can be any of various shapes, such as a square, circle, or diamond. This field MUST be present if the PenDataCustomStartCap flag is set in the PenDataFlags field of the EmfPlusPenData object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata) |  |

### getCustomEndCapData() {#getCustomEndCapData--}
```
public EmfPlusCustomEndCapData getCustomEndCapData()
```


Gets or sets optional EmfPlusCustomEndCapData object (section 2.2.2.11) that defines the custom end-cap shape, which is the shape to use at the end of a line drawn with this pen. It can be any of various shapes, such as a square, circle, or diamond. This field MUST be present if the PenDataCustomEndCap flag is set in the PenDataFlags field of the EmfPlusPenData object

**Returns:**
[EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata)
### setCustomEndCapData(EmfPlusCustomEndCapData value) {#setCustomEndCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomEndCapData-}
```
public void setCustomEndCapData(EmfPlusCustomEndCapData value)
```


Gets or sets optional EmfPlusCustomEndCapData object (section 2.2.2.11) that defines the custom end-cap shape, which is the shape to use at the end of a line drawn with this pen. It can be any of various shapes, such as a square, circle, or diamond. This field MUST be present if the PenDataCustomEndCap flag is set in the PenDataFlags field of the EmfPlusPenData object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata) |  |

