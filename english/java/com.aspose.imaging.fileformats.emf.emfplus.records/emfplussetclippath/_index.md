---
title: EmfPlusSetClipPath
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusSetClipPath record combines the current clipping region with a graphics path.
type: docs
weight: 55
url: /java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipPath extends EmfPlusClippingRecordType
```

The EmfPlusSetClipPath record combines the current clipping region with a graphics path. The new current clipping region is set to the result of the CombineMode operation.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusSetClipPath(EmfPlusRecord source)](#EmfPlusSetClipPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusSetClipPath` class. |
## Methods

| Method | Description |
| --- | --- |
| [getCm()](#getCm--) | Gets or sets the CM (4 bits): Specifies the logical operation for combining two regions. |
| [setCm(byte value)](#setCm-byte-) | Gets or sets the CM (4 bits): Specifies the logical operation for combining two regions. |
| [getObjectId()](#getObjectId--) | Gets or sets the index of an EmfPlusPath object (section 2.2.1.6) in the EMF+ Object Table. |
| [setObjectId(byte value)](#setObjectId-byte-) | Gets or sets the index of an EmfPlusPath object (section 2.2.1.6) in the EMF+ Object Table. |
### EmfPlusSetClipPath(EmfPlusRecord source) {#EmfPlusSetClipPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipPath(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusSetClipPath` class.

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

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Gets or sets the index of an EmfPlusPath object (section 2.2.1.6) in the EMF+ Object Table. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Gets or sets the index of an EmfPlusPath object (section 2.2.1.6) in the EMF+ Object Table. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

