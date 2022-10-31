---
title: EmfText
second_title: Aspose.Imaging for Java API Reference
description: The EmrText object contains values for text output.
type: docs
weight: 35
url: /java/com.aspose.imaging.fileformats.emf.emf.objects/emftext/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfText extends EmfObject
```

The EmrText object contains values for text output.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfText()](#EmfText--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getReference()](#getReference--) | Gets or sets a WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the coordinates of the reference point used to position the string. |
| [setReference(Point value)](#setReference-com.aspose.imaging.Point-) | Gets or sets a WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the coordinates of the reference point used to position the string. |
| [getChars()](#getChars--) | Gets or sets a 32-bit unsigned integer that specifies the number of characters in the string |
| [setChars(int value)](#setChars-int-) | Gets or sets a 32-bit unsigned integer that specifies the number of characters in the string |
| [getOptions()](#getOptions--) | Gets or sets a 32-bit unsigned integer that specifies how to use the rectangle specified in the Rectangle field. |
| [setOptions(int value)](#setOptions-int-) | Gets or sets a 32-bit unsigned integer that specifies how to use the rectangle specified in the Rectangle field. |
| [getRectangle()](#getRectangle--) | Gets or sets an optional WMF RectL object ([MS-WMF] section 2.2.2.19) that defines a clipping and/or opaquing rectangle in logical units. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.imaging.Rectangle-) | Gets or sets an optional WMF RectL object ([MS-WMF] section 2.2.2.19) that defines a clipping and/or opaquing rectangle in logical units. |
| [getStringBuffer()](#getStringBuffer--) | Gets or sets the character string buffer UndefinedSpace1 (variable): An optional number of unused bytes. |
| [setStringBuffer(String value)](#setStringBuffer-java.lang.String-) | Gets or sets the character string buffer UndefinedSpace1 (variable): An optional number of unused bytes. |
| [getGlyphIndexBuffer()](#getGlyphIndexBuffer--) | Gets the optional glyph index buffer. |
| [setGlyphIndexBuffer(int[] value)](#setGlyphIndexBuffer-int---) | Sets the optional glyph index buffer. |
| [getDxBuffer()](#getDxBuffer--) | Gets or sets the optional character spacing buffer UndefinedSpace2 (variable): An optional number of unused bytes. |
| [setDxBuffer(int[] value)](#setDxBuffer-int---) | Gets or sets the optional character spacing buffer UndefinedSpace2 (variable): An optional number of unused bytes. |
### EmfText() {#EmfText--}
```
public EmfText()
```


### getReference() {#getReference--}
```
public Point getReference()
```


Gets or sets a WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the coordinates of the reference point used to position the string. The reference point is defined by the last EMR\_SETTEXTALIGN record (section 2.3.11.25). If no such record has been set, the default alignment is TA\_LEFT,TA\_TOP.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setReference(Point value) {#setReference-com.aspose.imaging.Point-}
```
public void setReference(Point value)
```


Gets or sets a WMF PointL object ([MS-WMF] section 2.2.2.15) that specifies the coordinates of the reference point used to position the string. The reference point is defined by the last EMR\_SETTEXTALIGN record (section 2.3.11.25). If no such record has been set, the default alignment is TA\_LEFT,TA\_TOP.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getChars() {#getChars--}
```
public int getChars()
```


Gets or sets a 32-bit unsigned integer that specifies the number of characters in the string

**Returns:**
int
### setChars(int value) {#setChars-int-}
```
public void setChars(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the number of characters in the string

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getOptions() {#getOptions--}
```
public int getOptions()
```


Gets or sets a 32-bit unsigned integer that specifies how to use the rectangle specified in the Rectangle field. This field can be a combination of more than one ExtTextOutOptions enumeration (section 2.1.11) values

**Returns:**
int
### setOptions(int value) {#setOptions-int-}
```
public void setOptions(int value)
```


Gets or sets a 32-bit unsigned integer that specifies how to use the rectangle specified in the Rectangle field. This field can be a combination of more than one ExtTextOutOptions enumeration (section 2.1.11) values

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Gets or sets an optional WMF RectL object ([MS-WMF] section 2.2.2.19) that defines a clipping and/or opaquing rectangle in logical units. This rectangle is applied to the text output performed by the containing record.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setRectangle(Rectangle value) {#setRectangle-com.aspose.imaging.Rectangle-}
```
public void setRectangle(Rectangle value)
```


Gets or sets an optional WMF RectL object ([MS-WMF] section 2.2.2.19) that defines a clipping and/or opaquing rectangle in logical units. This rectangle is applied to the text output performed by the containing record.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getStringBuffer() {#getStringBuffer--}
```
public String getStringBuffer()
```


Gets or sets the character string buffer UndefinedSpace1 (variable): An optional number of unused bytes. The OutputString field is not required to follow immediately the preceding portion of this structure. OutputString (variable): An array of characters that specify the string to output. The location of this field is specified by the value of offString in bytes from the start of this record. The number of characters is specified by the value of Chars.

**Returns:**
java.lang.String
### setStringBuffer(String value) {#setStringBuffer-java.lang.String-}
```
public void setStringBuffer(String value)
```


Gets or sets the character string buffer UndefinedSpace1 (variable): An optional number of unused bytes. The OutputString field is not required to follow immediately the preceding portion of this structure. OutputString (variable): An array of characters that specify the string to output. The location of this field is specified by the value of offString in bytes from the start of this record. The number of characters is specified by the value of Chars.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getGlyphIndexBuffer() {#getGlyphIndexBuffer--}
```
public int[] getGlyphIndexBuffer()
```


Gets the optional glyph index buffer. If options has ETO\_GLYPH\_INDEX flag then the codes for characters in an output text string are actually indexes of the character glyphs in a TrueType font (2.1.11 ExtTextOutOptions enumeration). Glyph indexes are font-specific, so to display the correct characters on playback, the font that is used MUST be identical to the font used to generate the indexes.

**Returns:**
int[] - the optional glyph index buffer.
### setGlyphIndexBuffer(int[] value) {#setGlyphIndexBuffer-int---}
```
public void setGlyphIndexBuffer(int[] value)
```


Sets the optional glyph index buffer. If options has ETO\_GLYPH\_INDEX flag then the codes for characters in an output text string are actually indexes of the character glyphs in a TrueType font (2.1.11 ExtTextOutOptions enumeration). Glyph indexes are font-specific, so to display the correct characters on playback, the font that is used MUST be identical to the font used to generate the indexes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | the optional glyph index buffer. |

### getDxBuffer() {#getDxBuffer--}
```
public int[] getDxBuffer()
```


Gets or sets the optional character spacing buffer UndefinedSpace2 (variable): An optional number of unused bytes. The OutputDx field is not required to follow immediately the preceding portion of this structure. OutputDx (variable): An array of 32-bit unsigned integers that specify the output spacing between the origins of adjacent character cells in logical units. The location of this field is specified by the value of offDx in bytes from the start of this record. If spacing is defined, this field contains the same number of values as characters in the output string. If the Options field of the EmrText object contains the ETO\_PDY flag, then this buffer contains twice as many values as there are characters in the output string, one horizontal and one vertical offset for each, in that order. If ETO\_RTLREADING is specified, characters are laid right to left instead of left to right. No other options affect the interpretation of this field.

**Returns:**
int[]
### setDxBuffer(int[] value) {#setDxBuffer-int---}
```
public void setDxBuffer(int[] value)
```


Gets or sets the optional character spacing buffer UndefinedSpace2 (variable): An optional number of unused bytes. The OutputDx field is not required to follow immediately the preceding portion of this structure. OutputDx (variable): An array of 32-bit unsigned integers that specify the output spacing between the origins of adjacent character cells in logical units. The location of this field is specified by the value of offDx in bytes from the start of this record. If spacing is defined, this field contains the same number of values as characters in the output string. If the Options field of the EmrText object contains the ETO\_PDY flag, then this buffer contains twice as many values as there are characters in the output string, one horizontal and one vertical offset for each, in that order. If ETO\_RTLREADING is specified, characters are laid right to left instead of left to right. No other options affect the interpretation of this field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

