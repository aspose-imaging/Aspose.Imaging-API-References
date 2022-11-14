---
title: EmfPlusSetClipRegion
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusSetClipRegion record combines the current clipping region with another graphics region.
type: docs
weight: 57
url: /java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipRegion extends EmfPlusClippingRecordType
```

The EmfPlusSetClipRegion record combines the current clipping region with another graphics region. The new current clipping region is set to the result of performing the CombineMode operation on the previous current clipping region and the specified EmfPlusRegion object.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusSetClipRegion(EmfPlusRecord source)](#EmfPlusSetClipRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusSetClipRegion` class. |
## Methods

| Method | Description |
| --- | --- |
| [getCm()](#getCm--) | Gets or sets the CM (4 bits): Specifies the logical operation for combining two regions. |
| [setCm(byte value)](#setCm-byte-) | Gets or sets the CM (4 bits): Specifies the logical operation for combining two regions. |
| [getObjectId()](#getObjectId--) | Gets or sets the index of an EmfPlusRegion object (section 2.2.1.8) in the EMF+ Object Table.The value MUST be zero to 63, inclusive. |
| [setObjectId(byte value)](#setObjectId-byte-) | Gets or sets the index of an EmfPlusRegion object (section 2.2.1.8) in the EMF+ Object Table.The value MUST be zero to 63, inclusive. |
### EmfPlusSetClipRegion(EmfPlusRecord source) {#EmfPlusSetClipRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipRegion(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusSetClipRegion` class.

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


Gets or sets the index of an EmfPlusRegion object (section 2.2.1.8) in the EMF+ Object Table.The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Gets or sets the index of an EmfPlusRegion object (section 2.2.1.8) in the EMF+ Object Table.The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

