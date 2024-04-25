---
title: EmfLogFont
second_title: Aspose.Imaging for Java API Reference
description: The LogFont object specifies the basic attributes of a logical font.
type: docs
weight: 22
url: /com.aspose.imaging.fileformats.emf.emf.objects/emflogfont/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public class EmfLogFont extends EmfObject
```

The LogFont object specifies the basic attributes of a logical font.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfLogFont()](#EmfLogFont--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getHeight()](#getHeight--) | Gets or sets a 32-bit signed integer that specifies the height, in logical units, of the font's character cell or character. |
| [setHeight(int value)](#setHeight-int-) | Gets or sets a 32-bit signed integer that specifies the height, in logical units, of the font's character cell or character. |
| [getWidth()](#getWidth--) | Gets or sets a 32-bit signed integer that specifies the average width, in logical units, of characters in the font. |
| [setWidth(int value)](#setWidth-int-) | Gets or sets a 32-bit signed integer that specifies the average width, in logical units, of characters in the font. |
| [getEscapement()](#getEscapement--) | Gets or sets a 32-bit signed integer that specifies the angle, in tenths of degrees, between the escapement vector and the x-axis of the device. |
| [setEscapement(int value)](#setEscapement-int-) | Gets or sets a 32-bit signed integer that specifies the angle, in tenths of degrees, between the escapement vector and the x-axis of the device. |
| [getOrientation()](#getOrientation--) | Gets or sets a 32-bit signed integer that specifies the angle, in tenths of degrees, between each character's baseline and the x-axis of the device. |
| [setOrientation(int value)](#setOrientation-int-) | Gets or sets a 32-bit signed integer that specifies the angle, in tenths of degrees, between each character's baseline and the x-axis of the device. |
| [getWeight()](#getWeight--) | Gets or sets a 32-bit signed integer that specifies the weight of the font in the range zero through 1000. |
| [setWeight(int value)](#setWeight-int-) | Gets or sets a 32-bit signed integer that specifies the weight of the font in the range zero through 1000. |
| [getItalic()](#getItalic--) | Gets or sets an 8-bit unsigned integer that specifies an italic font if set to 0x01; otherwise, it MUST be set to 0x00. |
| [setItalic(byte value)](#setItalic-byte-) | Gets or sets an 8-bit unsigned integer that specifies an italic font if set to 0x01; otherwise, it MUST be set to 0x00. |
| [getUnderline()](#getUnderline--) | Gets or sets an 8-bit unsigned integer that specifies an underlined font if set to 0x01; otherwise, it MUST be set to 0x00. |
| [setUnderline(byte value)](#setUnderline-byte-) | Gets or sets an 8-bit unsigned integer that specifies an underlined font if set to 0x01; otherwise, it MUST be set to 0x00. |
| [getStrikeout()](#getStrikeout--) | Gets or sets an 8-bit unsigned integer that specifies a strikeout font if set to 0x01; otherwise, it MUST be set to 0x00. |
| [setStrikeout(byte value)](#setStrikeout-byte-) | Gets or sets an 8-bit unsigned integer that specifies a strikeout font if set to 0x01; otherwise, it MUST be set to 0x00. |
| [getCharSet()](#getCharSet--) | Gets or sets an 8-bit unsigned integer that specifies the set of character glyphs. |
| [setCharSet(byte value)](#setCharSet-byte-) | Gets or sets an 8-bit unsigned integer that specifies the set of character glyphs. |
| [getOutPrecision()](#getOutPrecision--) | Gets or sets an 8-bit unsigned integer that specifies the output precision. |
| [setOutPrecision(byte value)](#setOutPrecision-byte-) | Gets or sets an 8-bit unsigned integer that specifies the output precision. |
| [getClipPrecision()](#getClipPrecision--) | Gets or sets an 8-bit unsigned integer that specifies the clipping precision. |
| [setClipPrecision(byte value)](#setClipPrecision-byte-) | Gets or sets an 8-bit unsigned integer that specifies the clipping precision. |
| [getQuality()](#getQuality--) | Gets or sets an 8-bit unsigned integer that specifies the output quality. |
| [setQuality(byte value)](#setQuality-byte-) | Gets or sets an 8-bit unsigned integer that specifies the output quality. |
| [getPitchAndFamily()](#getPitchAndFamily--) | Gets or sets a WMF PitchAndFamily object ([MS-WMF] section 2.2.2.14) that specifies the pitch and family of the font. |
| [setPitchAndFamily(WmfPitchAndFamily value)](#setPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-) | Gets or sets a WMF PitchAndFamily object ([MS-WMF] section 2.2.2.14) that specifies the pitch and family of the font. |
| [getFacename()](#getFacename--) | Gets or sets a Facename (64 bytes): A string of no more than 32 Unicode characters that specifies the typeface name of the font. |
| [setFacename(String value)](#setFacename-java.lang.String-) | Gets or sets a Facename (64 bytes): A string of no more than 32 Unicode characters that specifies the typeface name of the font. |
### EmfLogFont() {#EmfLogFont--}
```
public EmfLogFont()
```


### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets or sets a 32-bit signed integer that specifies the height, in logical units, of the font's character cell or character. The character height value, also known as the em size, is the character cell height value minus the internal leading value. The font mapper SHOULD interpret the value specified in the Height field in the following manner.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Gets or sets a 32-bit signed integer that specifies the height, in logical units, of the font's character cell or character. The character height value, also known as the em size, is the character cell height value minus the internal leading value. The font mapper SHOULD interpret the value specified in the Height field in the following manner.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets or sets a 32-bit signed integer that specifies the average width, in logical units, of characters in the font. If the Width field value is zero, an appropriate value SHOULD be calculated from other LogFont values to find a font that has the typographer's intended aspect ratio

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Gets or sets a 32-bit signed integer that specifies the average width, in logical units, of characters in the font. If the Width field value is zero, an appropriate value SHOULD be calculated from other LogFont values to find a font that has the typographer's intended aspect ratio

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEscapement() {#getEscapement--}
```
public int getEscapement()
```


Gets or sets a 32-bit signed integer that specifies the angle, in tenths of degrees, between the escapement vector and the x-axis of the device. The escapement vector is parallel to the baseline of a row of text.

**Returns:**
int
### setEscapement(int value) {#setEscapement-int-}
```
public void setEscapement(int value)
```


Gets or sets a 32-bit signed integer that specifies the angle, in tenths of degrees, between the escapement vector and the x-axis of the device. The escapement vector is parallel to the baseline of a row of text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Gets or sets a 32-bit signed integer that specifies the angle, in tenths of degrees, between each character's baseline and the x-axis of the device.

**Returns:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Gets or sets a 32-bit signed integer that specifies the angle, in tenths of degrees, between each character's baseline and the x-axis of the device.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getWeight() {#getWeight--}
```
public int getWeight()
```


Gets or sets a 32-bit signed integer that specifies the weight of the font in the range zero through 1000. For example, 400 is normal and 700 is bold. If this value is zero, a default weight can be used.

**Returns:**
int
### setWeight(int value) {#setWeight-int-}
```
public void setWeight(int value)
```


Gets or sets a 32-bit signed integer that specifies the weight of the font in the range zero through 1000. For example, 400 is normal and 700 is bold. If this value is zero, a default weight can be used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getItalic() {#getItalic--}
```
public byte getItalic()
```


Gets or sets an 8-bit unsigned integer that specifies an italic font if set to 0x01; otherwise, it MUST be set to 0x00.

**Returns:**
byte
### setItalic(byte value) {#setItalic-byte-}
```
public void setItalic(byte value)
```


Gets or sets an 8-bit unsigned integer that specifies an italic font if set to 0x01; otherwise, it MUST be set to 0x00.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getUnderline() {#getUnderline--}
```
public byte getUnderline()
```


Gets or sets an 8-bit unsigned integer that specifies an underlined font if set to 0x01; otherwise, it MUST be set to 0x00.

**Returns:**
byte
### setUnderline(byte value) {#setUnderline-byte-}
```
public void setUnderline(byte value)
```


Gets or sets an 8-bit unsigned integer that specifies an underlined font if set to 0x01; otherwise, it MUST be set to 0x00.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStrikeout() {#getStrikeout--}
```
public byte getStrikeout()
```


Gets or sets an 8-bit unsigned integer that specifies a strikeout font if set to 0x01; otherwise, it MUST be set to 0x00.

**Returns:**
byte
### setStrikeout(byte value) {#setStrikeout-byte-}
```
public void setStrikeout(byte value)
```


Gets or sets an 8-bit unsigned integer that specifies a strikeout font if set to 0x01; otherwise, it MUST be set to 0x00.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCharSet() {#getCharSet--}
```
public byte getCharSet()
```


Gets or sets an 8-bit unsigned integer that specifies the set of character glyphs. It MUST be a value in the WMF CharacterSet enumeration ([MS-WMF] section 2.1.1.5). If the character set is unknown, metafile processing SHOULD NOT attempt to translate or interpret strings that are rendered with that font.

**Returns:**
byte
### setCharSet(byte value) {#setCharSet-byte-}
```
public void setCharSet(byte value)
```


Gets or sets an 8-bit unsigned integer that specifies the set of character glyphs. It MUST be a value in the WMF CharacterSet enumeration ([MS-WMF] section 2.1.1.5). If the character set is unknown, metafile processing SHOULD NOT attempt to translate or interpret strings that are rendered with that font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getOutPrecision() {#getOutPrecision--}
```
public byte getOutPrecision()
```


Gets or sets an 8-bit unsigned integer that specifies the output precision. The output precision defines how closely the font is required to match the requested height, width, character orientation, escapement, pitch, and font type. It MUST be a value from the WMF OutPrecision enumeration

**Returns:**
byte
### setOutPrecision(byte value) {#setOutPrecision-byte-}
```
public void setOutPrecision(byte value)
```


Gets or sets an 8-bit unsigned integer that specifies the output precision. The output precision defines how closely the font is required to match the requested height, width, character orientation, escapement, pitch, and font type. It MUST be a value from the WMF OutPrecision enumeration

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getClipPrecision() {#getClipPrecision--}
```
public byte getClipPrecision()
```


Gets or sets an 8-bit unsigned integer that specifies the clipping precision. The clipping precision defines how to clip characters that are partially outside the clipping region. It can be one or more of the WMF ClipPrecision Flags

**Returns:**
byte
### setClipPrecision(byte value) {#setClipPrecision-byte-}
```
public void setClipPrecision(byte value)
```


Gets or sets an 8-bit unsigned integer that specifies the clipping precision. The clipping precision defines how to clip characters that are partially outside the clipping region. It can be one or more of the WMF ClipPrecision Flags

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getQuality() {#getQuality--}
```
public byte getQuality()
```


Gets or sets an 8-bit unsigned integer that specifies the output quality. The output quality defines how closely to attempt to match the logical-font attributes to those of an actual physical font. It MUST be one of the values in the WMF FontQuality enumeration ([MS-WMF] section 2.1.1.10).

**Returns:**
byte
### setQuality(byte value) {#setQuality-byte-}
```
public void setQuality(byte value)
```


Gets or sets an 8-bit unsigned integer that specifies the output quality. The output quality defines how closely to attempt to match the logical-font attributes to those of an actual physical font. It MUST be one of the values in the WMF FontQuality enumeration ([MS-WMF] section 2.1.1.10).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getPitchAndFamily() {#getPitchAndFamily--}
```
public WmfPitchAndFamily getPitchAndFamily()
```


Gets or sets a WMF PitchAndFamily object ([MS-WMF] section 2.2.2.14) that specifies the pitch and family of the font. Font families describe the look of a font in a general way. They are intended for specifying a font when the specified typeface is not available.

**Returns:**
[WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily)
### setPitchAndFamily(WmfPitchAndFamily value) {#setPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public void setPitchAndFamily(WmfPitchAndFamily value)
```


Gets or sets a WMF PitchAndFamily object ([MS-WMF] section 2.2.2.14) that specifies the pitch and family of the font. Font families describe the look of a font in a general way. They are intended for specifying a font when the specified typeface is not available.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |

### getFacename() {#getFacename--}
```
public String getFacename()
```


Gets or sets a Facename (64 bytes): A string of no more than 32 Unicode characters that specifies the typeface name of the font. If the length of this string is less than 32 characters, a terminating NULL MUST be present, after which the remainder of this field MUST be ignored.

**Returns:**
java.lang.String
### setFacename(String value) {#setFacename-java.lang.String-}
```
public void setFacename(String value)
```


Gets or sets a Facename (64 bytes): A string of no more than 32 Unicode characters that specifies the typeface name of the font. If the length of this string is less than 32 characters, a terminating NULL MUST be present, after which the remainder of this field MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

