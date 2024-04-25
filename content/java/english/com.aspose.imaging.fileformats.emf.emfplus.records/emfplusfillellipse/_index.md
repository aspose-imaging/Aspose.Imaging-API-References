---
title: EmfPlusFillEllipse
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusFillEllipse record specifies filling the interior of an ellipse
type: docs
weight: 33
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillEllipse extends EmfPlusDrawingRecordType
```

The EmfPlusFillEllipse record specifies filling the interior of an ellipse
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusFillEllipse(EmfPlusRecord source)](#EmfPlusFillEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusFillEllipse` class. |
## Methods

| Method | Description |
| --- | --- |
| [isColor()](#isColor--) | Gets or sets a value indicating whether this instance is color. |
| [setColor(boolean value)](#setColor-boolean-) | Gets or sets a value indicating whether this instance is color. |
| [isCompressed()](#isCompressed--) | Gets or sets a value indicating whether this instance is compressed. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Gets or sets a value indicating whether this instance is compressed. |
| [getBrushId()](#getBrushId--) | Gets or sets the brush identifier A 32-bit unsigned integer that specifies the brush, the content of which is determined by the S bit in the Flags field. |
| [setBrushId(int value)](#setBrushId-int-) | Gets or sets the brush identifier A 32-bit unsigned integer that specifies the brush, the content of which is determined by the S bit in the Flags field. |
| [getRectData()](#getRectData--) | Gets or sets the rect data Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the ellipse |
| [setRectData(RectangleF value)](#setRectData-com.aspose.imaging.RectangleF-) | Gets or sets the rect data Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the ellipse |
### EmfPlusFillEllipse(EmfPlusRecord source) {#EmfPlusFillEllipse-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillEllipse(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusFillEllipse` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Gets or sets a value indicating whether this instance is color. If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table.

Value: `true` if this instance is color; otherwise, `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Gets or sets a value indicating whether this instance is color. If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table.

Value: `true` if this instance is color; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isCompressed() {#isCompressed--}
```
public boolean isCompressed()
```


Gets or sets a value indicating whether this instance is compressed. If set, RectData contains an EmfPlusRect object (section 2.2.2.38). If clear, RectData contains an EmfPlusRectF object (section 2.2.2.39).

Value: `true` if this instance is compressed; otherwise, `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Gets or sets a value indicating whether this instance is compressed. If set, RectData contains an EmfPlusRect object (section 2.2.2.38). If clear, RectData contains an EmfPlusRectF object (section 2.2.2.39).

Value: `true` if this instance is compressed; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Gets or sets the brush identifier A 32-bit unsigned integer that specifies the brush, the content of which is determined by the S bit in the Flags field. This definition is used to fill the interior of the ellipse

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Gets or sets the brush identifier A 32-bit unsigned integer that specifies the brush, the content of which is determined by the S bit in the Flags field. This definition is used to fill the interior of the ellipse

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRectData() {#getRectData--}
```
public RectangleF getRectData()
```


Gets or sets the rect data Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the ellipse

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectData(RectangleF value) {#setRectData-com.aspose.imaging.RectangleF-}
```
public void setRectData(RectangleF value)
```


Gets or sets the rect data Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the ellipse

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

