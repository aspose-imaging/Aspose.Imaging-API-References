---
title: EmfPlusFont
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusFont object specifies properties that determine the appearance of text including typeface size and style.
type: docs
weight: 42
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfont/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusFont extends EmfPlusGraphicsObjectType
```

The EmfPlusFont object specifies properties that determine the appearance of text, including typeface, size, and style.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusFont()](#EmfPlusFont--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Gets or sets a string of Length Unicode characters that contains the name of the font family |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | Gets or sets a string of Length Unicode characters that contains the name of the font family |
| [getFontStyleFlags()](#getFontStyleFlags--) | Gets or sets a 32-bit signed integer that specifies attributes of the character glyphs that affect the appearance of the font, such as bold and italic. |
| [setFontStyleFlags(int value)](#setFontStyleFlags-int-) | Gets or sets a 32-bit signed integer that specifies attributes of the character glyphs that affect the appearance of the font, such as bold and italic. |
| [getSizeUnit()](#getSizeUnit--) | Gets or sets a 32-bit unsigned integer that specifies the units used for the EmSize field. |
| [setSizeUnit(int value)](#setSizeUnit-int-) | Gets or sets a 32-bit unsigned integer that specifies the units used for the EmSize field. |
| [getEmSize()](#getEmSize--) | Gets or sets a 32-bit floating-point value that specifies the em size of the font in units specified by the SizeUnit field. |
| [setEmSize(float value)](#setEmSize-float-) | Gets or sets a 32-bit floating-point value that specifies the em size of the font in units specified by the SizeUnit field. |
### EmfPlusFont() {#EmfPlusFont--}
```
public EmfPlusFont()
```


### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Gets or sets a string of Length Unicode characters that contains the name of the font family

**Returns:**
java.lang.String
### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public void setFamilyName(String value)
```


Gets or sets a string of Length Unicode characters that contains the name of the font family

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFontStyleFlags() {#getFontStyleFlags--}
```
public int getFontStyleFlags()
```


Gets or sets a 32-bit signed integer that specifies attributes of the character glyphs that affect the appearance of the font, such as bold and italic. This value MUST be composed of FontStyle flags (section 2.1.2.4).

**Returns:**
int
### setFontStyleFlags(int value) {#setFontStyleFlags-int-}
```
public void setFontStyleFlags(int value)
```


Gets or sets a 32-bit signed integer that specifies attributes of the character glyphs that affect the appearance of the font, such as bold and italic. This value MUST be composed of FontStyle flags (section 2.1.2.4).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSizeUnit() {#getSizeUnit--}
```
public int getSizeUnit()
```


Gets or sets a 32-bit unsigned integer that specifies the units used for the EmSize field. These are typically the units that were employed when designing the font. The value MUST be in the UnitType enumeration (section 2.1.1.33).

**Returns:**
int
### setSizeUnit(int value) {#setSizeUnit-int-}
```
public void setSizeUnit(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the units used for the EmSize field. These are typically the units that were employed when designing the font. The value MUST be in the UnitType enumeration (section 2.1.1.33).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEmSize() {#getEmSize--}
```
public float getEmSize()
```


Gets or sets a 32-bit floating-point value that specifies the em size of the font in units specified by the SizeUnit field.

**Returns:**
float
### setEmSize(float value) {#setEmSize-float-}
```
public void setEmSize(float value)
```


Gets or sets a 32-bit floating-point value that specifies the em size of the font in units specified by the SizeUnit field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

