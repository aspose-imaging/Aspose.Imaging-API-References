---
title: EmfPlusDrawPath
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusDrawPath record specifies drawing a graphics path.
type: docs
weight: 25
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawPath extends EmfPlusDrawingRecordType
```

The EmfPlusDrawPath record specifies drawing a graphics path.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusDrawPath(EmfPlusRecord source)](#EmfPlusDrawPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusDrawPath` class. |
## Methods

| Method | Description |
| --- | --- |
| [getObjectId()](#getObjectId--) | Gets or sets the object identifier. |
| [setObjectId(byte value)](#setObjectId-byte-) | Gets or sets the object identifier. |
| [getPenId()](#getPenId--) | Gets or sets the pen identifier A 32-bit unsigned integer that specifies an index in the EMF+ Object Table for an EmfPlusPen object (section 2.2.1.7) to use for drawing the EmfPlusPath. |
| [setPenId(int value)](#setPenId-int-) | Gets or sets the pen identifier A 32-bit unsigned integer that specifies an index in the EMF+ Object Table for an EmfPlusPen object (section 2.2.1.7) to use for drawing the EmfPlusPath. |
### EmfPlusDrawPath(EmfPlusRecord source) {#EmfPlusDrawPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawPath(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusDrawPath` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Gets or sets the object identifier. The index of the EmfPlusPath object (section 2.2.1.6) to draw, in the EMF+ Object Table. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Gets or sets the object identifier. The index of the EmfPlusPath object (section 2.2.1.6) to draw, in the EMF+ Object Table. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getPenId() {#getPenId--}
```
public int getPenId()
```


Gets or sets the pen identifier A 32-bit unsigned integer that specifies an index in the EMF+ Object Table for an EmfPlusPen object (section 2.2.1.7) to use for drawing the EmfPlusPath. The value MUST be zero to 63, inclusive

**Returns:**
int
### setPenId(int value) {#setPenId-int-}
```
public void setPenId(int value)
```


Gets or sets the pen identifier A 32-bit unsigned integer that specifies an index in the EMF+ Object Table for an EmfPlusPen object (section 2.2.1.7) to use for drawing the EmfPlusPath. The value MUST be zero to 63, inclusive

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

