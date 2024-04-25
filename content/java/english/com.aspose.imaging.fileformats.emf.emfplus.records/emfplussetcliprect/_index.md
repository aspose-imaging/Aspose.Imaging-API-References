---
title: EmfPlusSetClipRect
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusSetClipRect record combines the current clipping region with a rectangle.
type: docs
weight: 56
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipRect extends EmfPlusClippingRecordType
```

The EmfPlusSetClipRect record combines the current clipping region with a rectangle.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusSetClipRect(EmfPlusRecord source)](#EmfPlusSetClipRect-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusSetClipRect` class. |
## Methods

| Method | Description |
| --- | --- |
| [getCm()](#getCm--) | Gets or sets the CM (4 bits): Specifies the logical operation for combining two regions. |
| [setCm(byte value)](#setCm-byte-) | Gets or sets the CM (4 bits): Specifies the logical operation for combining two regions. |
| [getClipRect()](#getClipRect--) | Gets or sets an EmfPlusRectF object (section 2.2.2.39) that defines the rectangle to use in the CombineMode operation. |
| [setClipRect(RectangleF value)](#setClipRect-com.aspose.imaging.RectangleF-) | Gets or sets an EmfPlusRectF object (section 2.2.2.39) that defines the rectangle to use in the CombineMode operation. |
### EmfPlusSetClipRect(EmfPlusRecord source) {#EmfPlusSetClipRect-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipRect(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusSetClipRect` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getCm() {#getCm--}
```
public byte getCm()
```


Gets or sets the CM (4 bits): Specifies the logical operation for combining two regions. See the CombineMode enumeration (section 2.1.1.4) for the meanings of the values.

Value: The cm.

**Returns:**
byte
### setCm(byte value) {#setCm-byte-}
```
public void setCm(byte value)
```


Gets or sets the CM (4 bits): Specifies the logical operation for combining two regions. See the CombineMode enumeration (section 2.1.1.4) for the meanings of the values.

Value: The cm.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getClipRect() {#getClipRect--}
```
public RectangleF getClipRect()
```


Gets or sets an EmfPlusRectF object (section 2.2.2.39) that defines the rectangle to use in the CombineMode operation.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setClipRect(RectangleF value) {#setClipRect-com.aspose.imaging.RectangleF-}
```
public void setClipRect(RectangleF value)
```


Gets or sets an EmfPlusRectF object (section 2.2.2.39) that defines the rectangle to use in the CombineMode operation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

