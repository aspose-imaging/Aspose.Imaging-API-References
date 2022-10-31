---
title: EmfPlusDrawString
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusDrawString record specifies text output with string formatting
type: docs
weight: 28
url: /java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawstring/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawString extends EmfPlusDrawingRecordType
```

The EmfPlusDrawString record specifies text output with string formatting
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusDrawString(EmfPlusRecord source)](#EmfPlusDrawString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusDrawString` class. |
## Methods

| Method | Description |
| --- | --- |
| [isColor()](#isColor--) | Gets or sets a value indicating whether this instance is color. |
| [setColor(boolean value)](#setColor-boolean-) | Gets or sets a value indicating whether this instance is color. |
| [getObjectId()](#getObjectId--) | Gets or sets the object identifier. |
| [setObjectId(byte value)](#setObjectId-byte-) | Gets or sets the object identifier. |
| [getBrushId()](#getBrushId--) | Gets or sets the brush identifier A 32-bit unsigned integer that specifies the brush, the content of which is determined by the S bit in the Flags field. |
| [setBrushId(int value)](#setBrushId-int-) | Gets or sets the brush identifier A 32-bit unsigned integer that specifies the brush, the content of which is determined by the S bit in the Flags field. |
| [getFormatId()](#getFormatId--) | Gets or sets the format identifier A 32-bit unsigned integer that specifies the index of an optional EmfPlusStringFormat object (section 2.2.1.9) in the EMF+ Object Table. |
| [setFormatId(int value)](#setFormatId-int-) | Gets or sets the format identifier A 32-bit unsigned integer that specifies the index of an optional EmfPlusStringFormat object (section 2.2.1.9) in the EMF+ Object Table. |
| [getLength()](#getLength--) | Gets or sets the length 32-bit unsigned integer that specifies the number of characters in the string. |
| [setLength(int value)](#setLength-int-) | Gets or sets the length 32-bit unsigned integer that specifies the number of characters in the string. |
| [getLayoutRect()](#getLayoutRect--) | Gets or sets the layout rect An EmfPlusRectF object (section 2.2.2.39) that defines the bounding area of the destination that will receive the string |
| [setLayoutRect(RectangleF value)](#setLayoutRect-com.aspose.imaging.RectangleF-) | Gets or sets the layout rect An EmfPlusRectF object (section 2.2.2.39) that defines the bounding area of the destination that will receive the string |
| [getStringData()](#getStringData--) | Gets or sets the string data An array of 16-bit Unicode characters that specifies the string to be drawn |
| [setStringData(String value)](#setStringData-java.lang.String-) | Gets or sets the string data An array of 16-bit Unicode characters that specifies the string to be drawn |
### EmfPlusDrawString(EmfPlusRecord source) {#EmfPlusDrawString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawString(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusDrawString` class.

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

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Gets or sets the object identifier. The index of an EmfPlusFont object (section 2.2.1.3) in the EMF+ Object Table to render the text. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Gets or sets the object identifier. The index of an EmfPlusFont object (section 2.2.1.3) in the EMF+ Object Table to render the text. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Gets or sets the brush identifier A 32-bit unsigned integer that specifies the brush, the content of which is determined by the S bit in the Flags field. This definition is used to paint the foreground text color; that is, just the glyphs themselves.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Gets or sets the brush identifier A 32-bit unsigned integer that specifies the brush, the content of which is determined by the S bit in the Flags field. This definition is used to paint the foreground text color; that is, just the glyphs themselves.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormatId() {#getFormatId--}
```
public int getFormatId()
```


Gets or sets the format identifier A 32-bit unsigned integer that specifies the index of an optional EmfPlusStringFormat object (section 2.2.1.9) in the EMF+ Object Table. This object specifies text layout information and display manipulations to be applied to a string

**Returns:**
int
### setFormatId(int value) {#setFormatId-int-}
```
public void setFormatId(int value)
```


Gets or sets the format identifier A 32-bit unsigned integer that specifies the index of an optional EmfPlusStringFormat object (section 2.2.1.9) in the EMF+ Object Table. This object specifies text layout information and display manipulations to be applied to a string

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLength() {#getLength--}
```
public int getLength()
```


Gets or sets the length 32-bit unsigned integer that specifies the number of characters in the string.

**Returns:**
int
### setLength(int value) {#setLength-int-}
```
public void setLength(int value)
```


Gets or sets the length 32-bit unsigned integer that specifies the number of characters in the string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLayoutRect() {#getLayoutRect--}
```
public RectangleF getLayoutRect()
```


Gets or sets the layout rect An EmfPlusRectF object (section 2.2.2.39) that defines the bounding area of the destination that will receive the string

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setLayoutRect(RectangleF value) {#setLayoutRect-com.aspose.imaging.RectangleF-}
```
public void setLayoutRect(RectangleF value)
```


Gets or sets the layout rect An EmfPlusRectF object (section 2.2.2.39) that defines the bounding area of the destination that will receive the string

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStringData() {#getStringData--}
```
public String getStringData()
```


Gets or sets the string data An array of 16-bit Unicode characters that specifies the string to be drawn

**Returns:**
java.lang.String
### setStringData(String value) {#setStringData-java.lang.String-}
```
public void setStringData(String value)
```


Gets or sets the string data An array of 16-bit Unicode characters that specifies the string to be drawn

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

