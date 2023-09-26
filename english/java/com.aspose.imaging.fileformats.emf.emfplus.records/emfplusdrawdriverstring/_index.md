---
title: EmfPlusDrawDriverString
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusDrawDriverString record specifies text output with character positions.
type: docs
weight: 20
url: /java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawDriverString extends EmfPlusDrawingRecordType
```

The EmfPlusDrawDriverString record specifies text output with character positions.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusDrawDriverString(EmfPlusRecord source)](#EmfPlusDrawDriverString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusDrawDriverString` class. |
## Methods

| Method | Description |
| --- | --- |
| [getObjectId()](#getObjectId--) | Gets the object identifier. |
| [setObjectId(byte value)](#setObjectId-byte-) | Sets the object identifier. |
| [getBrushId()](#getBrushId--) | Gets the brush identifier A 32-bit unsigned integer that specifies either the foreground color of the text or a graphics brush, depending on the value of the S flag in the Flags |
| [setBrushId(int value)](#setBrushId-int-) | Sets the brush identifier A 32-bit unsigned integer that specifies either the foreground color of the text or a graphics brush, depending on the value of the S flag in the Flags |
| [getDriverStringOptionsFlags()](#getDriverStringOptionsFlags--) | Gets the driver string options flags A 32-bit unsigned integer that specifies the spacing, orientation, and quality of rendering for the string. |
| [setDriverStringOptionsFlags(int value)](#setDriverStringOptionsFlags-int-) | Sets the driver string options flags A 32-bit unsigned integer that specifies the spacing, orientation, and quality of rendering for the string. |
| [getGlyphCount()](#getGlyphCount--) | Gets the glyph count A 32-bit unsigned integer that specifies number of glyphs in the string |
| [setGlyphCount(int value)](#setGlyphCount-int-) | Sets the glyph count A 32-bit unsigned integer that specifies number of glyphs in the string |
| [getGlyphPos()](#getGlyphPos--) | Gets the glyph positions array An array of EmfPlusPointF objects (section 2.2.2.36) that specify the output position of each character glyph. |
| [setGlyphPos(PointF[] value)](#setGlyphPos-com.aspose.imaging.PointF---) | Sets the glyph positions array An array of EmfPlusPointF objects (section 2.2.2.36) that specify the output position of each character glyph. |
| [getGlyphs()](#getGlyphs--) | Gets the glyphs array An array of 16-bit values that define the text string to draw. |
| [setGlyphs(short[] value)](#setGlyphs-short---) | Sets the glyphs array An array of 16-bit values that define the text string to draw. |
| [isColor()](#isColor--) | Gets or sets a value indicating whether this instance is color. |
| [setColor(boolean value)](#setColor-boolean-) | Sets a value indicating whether this instance is color. |
| [getMatrixPresent()](#getMatrixPresent--) | Gets if the matrix present flag A 32-bit unsigned integer that specifies whether a transform matrix is present in the TransformMatrix field 0 - no matrix present. |
| [setMatrixPresent(int value)](#setMatrixPresent-int-) | Sets if the matrix present flag A 32-bit unsigned integer that specifies whether a transform matrix is present in the TransformMatrix field 0 - no matrix present. |
| [getTransformMatrix()](#getTransformMatrix--) | Gets the transform matrix An optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies the transformation to apply to each value in the text array. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Sets the transform matrix An optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies the transformation to apply to each value in the text array. |
### EmfPlusDrawDriverString(EmfPlusRecord source) {#EmfPlusDrawDriverString-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawDriverString(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusDrawDriverString` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Gets the object identifier. The EMF+ Object Table index of an `` object (section 2.2.1.3) to render the text. The value MUST be zero to 63, inclusive.

**Returns:**
byte - The object identifier.
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Sets the object identifier. The EMF+ Object Table index of an `` object (section 2.2.1.3) to render the text. The value MUST be zero to 63, inclusive.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte | The object identifier. |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Gets the brush identifier A 32-bit unsigned integer that specifies either the foreground color of the text or a graphics brush, depending on the value of the S flag in the Flags

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Sets the brush identifier A 32-bit unsigned integer that specifies either the foreground color of the text or a graphics brush, depending on the value of the S flag in the Flags

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDriverStringOptionsFlags() {#getDriverStringOptionsFlags--}
```
public int getDriverStringOptionsFlags()
```


Gets the driver string options flags A 32-bit unsigned integer that specifies the spacing, orientation, and quality of rendering for the string.

**Returns:**
int
### setDriverStringOptionsFlags(int value) {#setDriverStringOptionsFlags-int-}
```
public void setDriverStringOptionsFlags(int value)
```


Sets the driver string options flags A 32-bit unsigned integer that specifies the spacing, orientation, and quality of rendering for the string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGlyphCount() {#getGlyphCount--}
```
public int getGlyphCount()
```


Gets the glyph count A 32-bit unsigned integer that specifies number of glyphs in the string

**Returns:**
int
### setGlyphCount(int value) {#setGlyphCount-int-}
```
public void setGlyphCount(int value)
```


Sets the glyph count A 32-bit unsigned integer that specifies number of glyphs in the string

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGlyphPos() {#getGlyphPos--}
```
public PointF[] getGlyphPos()
```


Gets the glyph positions array An array of EmfPlusPointF objects (section 2.2.2.36) that specify the output position of each character glyph. There MUST be GlyphCount elements, which have a one-to-one correspondence with the elements in the Glyphs array. Glyph positions are calculated from the position of the first glyph if the DriverStringOptionsRealizedAdvance flag in DriverStringOptions flags is set. In this case, GlyphPos specifies the position of the first glyph only.

**Returns:**
com.aspose.imaging.PointF[]
### setGlyphPos(PointF[] value) {#setGlyphPos-com.aspose.imaging.PointF---}
```
public void setGlyphPos(PointF[] value)
```


Sets the glyph positions array An array of EmfPlusPointF objects (section 2.2.2.36) that specify the output position of each character glyph. There MUST be GlyphCount elements, which have a one-to-one correspondence with the elements in the Glyphs array. Glyph positions are calculated from the position of the first glyph if the DriverStringOptionsRealizedAdvance flag in DriverStringOptions flags is set. In this case, GlyphPos specifies the position of the first glyph only.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### getGlyphs() {#getGlyphs--}
```
public short[] getGlyphs()
```


Gets the glyphs array An array of 16-bit values that define the text string to draw. If the DriverStringOptionsCmapLookup flag in the DriverStringOptionsFlags field is set, each value in this array specifies a Unicode character. Otherwise, each value specifies an index to a character glyph in the EmfPlusFont object specified by the ObjectId value in Flags field.

**Returns:**
short[]
### setGlyphs(short[] value) {#setGlyphs-short---}
```
public void setGlyphs(short[] value)
```


Sets the glyphs array An array of 16-bit values that define the text string to draw. If the DriverStringOptionsCmapLookup flag in the DriverStringOptionsFlags field is set, each value in this array specifies a Unicode character. Otherwise, each value specifies an index to a character glyph in the EmfPlusFont object specified by the ObjectId value in Flags field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short[] |  |

### isColor() {#isColor--}
```
public boolean isColor()
```


Gets or sets a value indicating whether this instance is color. This bit indicates the type of data in the BrushId field. If set, BrushId specifies the color value in an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the EMF+ Object Table index of an EmfPlusBrush object (section 2.2.1.1).

**Returns:**
boolean - `true` if this instance is color; otherwise, `false`.
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Sets a value indicating whether this instance is color. This bit indicates the type of data in the BrushId field. If set, BrushId specifies the color value in an EmfPlusARGB object (section 2.2.2.1). If clear, BrushId contains the EMF+ Object Table index of an EmfPlusBrush object (section 2.2.1.1).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | `true` if this instance is color; otherwise, `false`. |

### getMatrixPresent() {#getMatrixPresent--}
```
public int getMatrixPresent()
```


Gets if the matrix present flag A 32-bit unsigned integer that specifies whether a transform matrix is present in the TransformMatrix field 0 - no matrix present. 1 - transform matrix is in TransformMatrix field

**Returns:**
int
### setMatrixPresent(int value) {#setMatrixPresent-int-}
```
public void setMatrixPresent(int value)
```


Sets if the matrix present flag A 32-bit unsigned integer that specifies whether a transform matrix is present in the TransformMatrix field 0 - no matrix present. 1 - transform matrix is in TransformMatrix field

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Gets the transform matrix An optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies the transformation to apply to each value in the text array. The presence of this data is determined from the MatrixPresent field.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Sets the transform matrix An optional EmfPlusTransformMatrix object (section 2.2.2.47) that specifies the transformation to apply to each value in the text array. The presence of this data is determined from the MatrixPresent field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

