---
title: EmfPlusFillPath
second_title: Aspose.Imaging for Java API Reference
description: Fill path record FLAGS 16-bit unsigned integer that provides information about how the operation is to be performed and about the structure of the record.
type: docs
weight: 34
url: /java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillPath extends EmfPlusDrawingRecordType
```

Fill path record FLAGS: 16-bit unsigned integer that provides information about how the operation is to be performed, and about the structure of the record. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 S X X X X X X X | ObjectId | S (1 bit): This bit indicates the type of data in the BrushId field. If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table. X (1 bit): Reserved and MUST be ignored. ObjectId (1 byte): The index of the EmfPlusPath object (section 2.2.1.6) to fill, in the EMF+ Object Table. The value MUST be zero to 63, inclusive.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusFillPath(EmfPlusRecord source)](#EmfPlusFillPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusFillPath` class. |
## Methods

| Method | Description |
| --- | --- |
| [isColor()](#isColor--) | Gets or sets a value indicating whether this instance is color. |
| [setColor(boolean value)](#setColor-boolean-) | Gets or sets a value indicating whether this instance is color. |
| [getObjectId()](#getObjectId--) | Gets or sets the object identifier. |
| [setObjectId(byte value)](#setObjectId-byte-) | Gets or sets the object identifier. |
| [getBrushId()](#getBrushId--) | Gets or sets the Brush ID A 32-bit unsigned integer that defines the brush, the content of which is determined by the S bit in the Flags field. |
| [setBrushId(int value)](#setBrushId-int-) | Gets or sets the Brush ID A 32-bit unsigned integer that defines the brush, the content of which is determined by the S bit in the Flags field. |
### EmfPlusFillPath(EmfPlusRecord source) {#EmfPlusFillPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillPath(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusFillPath` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Gets or sets a value indicating whether this instance is color. If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table

Value: `true` if this instance is color; otherwise, `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Gets or sets a value indicating whether this instance is color. If set, BrushId specifies a color as an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the index of an EmfPlusBrush object (section 2.2.1.1) in the EMF+ Object Table

Value: `true` if this instance is color; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Gets or sets the object identifier. The index of the EmfPlusPath object (section 2.2.1.6) to fill, in the EMF+ Object Table. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Gets or sets the object identifier. The index of the EmfPlusPath object (section 2.2.1.6) to fill, in the EMF+ Object Table. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Gets or sets the Brush ID A 32-bit unsigned integer that defines the brush, the content of which is determined by the S bit in the Flags field.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Gets or sets the Brush ID A 32-bit unsigned integer that defines the brush, the content of which is determined by the S bit in the Flags field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

