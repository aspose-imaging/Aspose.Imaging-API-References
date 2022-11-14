---
title: EmfPlusFillRegion
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusFillRegion record specifies filling the interior of a graphics region
type: docs
weight: 38
url: /java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillRegion extends EmfPlusDrawingRecordType
```

The EmfPlusFillRegion record specifies filling the interior of a graphics region
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusFillRegion(EmfPlusRecord source)](#EmfPlusFillRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusFillRegion` class. |
## Methods

| Method | Description |
| --- | --- |
| [getObjectId()](#getObjectId--) | Gets or sets the object identifier. |
| [setObjectId(byte value)](#setObjectId-byte-) | Gets or sets the object identifier. |
| [isColor()](#isColor--) | Gets or sets a value indicating whether this instance is color. |
| [setColor(boolean value)](#setColor-boolean-) | Gets or sets a value indicating whether this instance is color. |
| [getBrushId()](#getBrushId--) | Gets or sets the brush identifier A 32-bit unsigned integer that defines the brush, the content of which is determined by the S bit in the Flags field. |
| [setBrushId(int value)](#setBrushId-int-) | Gets or sets the brush identifier A 32-bit unsigned integer that defines the brush, the content of which is determined by the S bit in the Flags field. |
### EmfPlusFillRegion(EmfPlusRecord source) {#EmfPlusFillRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillRegion(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusFillRegion` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Gets or sets the object identifier. The index of the EmfPlusRegion object (section 2.2.1.8) to fill, in the EMF+ Object Table. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Gets or sets the object identifier. The index of the EmfPlusRegion object (section 2.2.1.8) to fill, in the EMF+ Object Table. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

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

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Gets or sets the brush identifier A 32-bit unsigned integer that defines the brush, the content of which is determined by the S bit in the Flags field.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Gets or sets the brush identifier A 32-bit unsigned integer that defines the brush, the content of which is determined by the S bit in the Flags field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

