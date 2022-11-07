---
title: Font
second_title: Aspose.Imaging for Java API Reference
description: Represents XMP Font.
type: docs
weight: 10
url: /java/com.aspose.imaging.xmp.types.complex.font/font/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase), [com.aspose.imaging.xmp.types.complex.ComplexTypeBase](../../com.aspose.imaging.xmp.types.complex/complextypebase)
```
public final class Font extends ComplexTypeBase
```

Represents XMP Font.
## Constructors

| Constructor | Description |
| --- | --- |
| [Font()](#Font--) | Initializes a new instance of the `Font` class. |
| [Font(String fontFamily)](#Font-java.lang.String-) | Initializes a new instance of the `Font` class. |
## Methods

| Method | Description |
| --- | --- |
| [getChildFontFiles()](#getChildFontFiles--) | Gets or sets the array of file names for the fonts that make up a composite font. |
| [setChildFontFiles(String[] value)](#setChildFontFiles-java.lang.String---) | Gets or sets the array of file names for the fonts that make up a composite font. |
| [isComposite()](#isComposite--) | Gets or sets a value indicating whether this font is composite. |
| [setComposite(boolean value)](#setComposite-boolean-) | Gets or sets a value indicating whether this font is composite. |
| [getFontFace()](#getFontFace--) | Gets or sets the font face. |
| [setFontFace(String value)](#setFontFace-java.lang.String-) | Gets or sets the font face. |
| [getFontFamily()](#getFontFamily--) | Gets or sets the font family. |
| [setFontFamily(String value)](#setFontFamily-java.lang.String-) | Gets or sets the font family. |
| [getFontFileName()](#getFontFileName--) | Gets or sets the font file name without full path. |
| [setFontFileName(String value)](#setFontFileName-java.lang.String-) | Gets or sets the font file name without full path. |
| [getFontName()](#getFontName--) | Gets or sets the PostScript font name. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Gets or sets the PostScript font name. |
| [getFontType()](#getFontType--) | Gets or sets the font type. |
| [setFontType(String value)](#setFontType-java.lang.String-) | Gets or sets the font type. |
| [getVersion()](#getVersion--) | Gets or sets the font version. |
| [setVersion(String value)](#setVersion-java.lang.String-) | Gets or sets the font version. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Gets the string contained value in XMP format. |
### Font() {#Font--}
```
public Font()
```


Initializes a new instance of the `Font` class.

### Font(String fontFamily) {#Font-java.lang.String-}
```
public Font(String fontFamily)
```


Initializes a new instance of the `Font` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontFamily | java.lang.String | Font family. |

### getChildFontFiles() {#getChildFontFiles--}
```
public String[] getChildFontFiles()
```


Gets or sets the array of file names for the fonts that make up a composite font.

Value: The array of file names for the fonts that make up a composite font.

**Returns:**
java.lang.String[]
### setChildFontFiles(String[] value) {#setChildFontFiles-java.lang.String---}
```
public void setChildFontFiles(String[] value)
```


Gets or sets the array of file names for the fonts that make up a composite font.

Value: The array of file names for the fonts that make up a composite font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### isComposite() {#isComposite--}
```
public boolean isComposite()
```


Gets or sets a value indicating whether this font is composite.

Value: `true` if this font is composite; otherwise, `false`.

**Returns:**
boolean
### setComposite(boolean value) {#setComposite-boolean-}
```
public void setComposite(boolean value)
```


Gets or sets a value indicating whether this font is composite.

Value: `true` if this font is composite; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFontFace() {#getFontFace--}
```
public String getFontFace()
```


Gets or sets the font face.

Value: The font face.

**Returns:**
java.lang.String
### setFontFace(String value) {#setFontFace-java.lang.String-}
```
public void setFontFace(String value)
```


Gets or sets the font face.

Value: The font face.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFontFamily() {#getFontFamily--}
```
public String getFontFamily()
```


Gets or sets the font family.

Value: The font family.

**Returns:**
java.lang.String
### setFontFamily(String value) {#setFontFamily-java.lang.String-}
```
public void setFontFamily(String value)
```


Gets or sets the font family.

Value: The font family.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFontFileName() {#getFontFileName--}
```
public String getFontFileName()
```


Gets or sets the font file name without full path.

Value: The font file name without full path.

**Returns:**
java.lang.String
### setFontFileName(String value) {#setFontFileName-java.lang.String-}
```
public void setFontFileName(String value)
```


Gets or sets the font file name without full path.

Value: The font file name without full path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFontName() {#getFontName--}
```
public String getFontName()
```


Gets or sets the PostScript font name.

Value: The name of PostScript font name.

**Returns:**
java.lang.String
### setFontName(String value) {#setFontName-java.lang.String-}
```
public void setFontName(String value)
```


Gets or sets the PostScript font name.

Value: The name of PostScript font name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFontType() {#getFontType--}
```
public String getFontType()
```


Gets or sets the font type.

TrueType, Type 1, Open Type, and so on. Value: The font type.

**Returns:**
java.lang.String
### setFontType(String value) {#setFontType-java.lang.String-}
```
public void setFontType(String value)
```


Gets or sets the font type.

TrueType, Type 1, Open Type, and so on. Value: The font type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public String getVersion()
```


Gets or sets the font version.

/version for Type1 fonts nameId 5 for Apple True Type and OpenType /CIDFontVersion for CID fonts The empty string for bitmap fonts Value: The font version.

**Returns:**
java.lang.String
### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


Gets or sets the font version.

/version for Type1 fonts nameId 5 for Apple True Type and OpenType /CIDFontVersion for CID fonts The empty string for bitmap fonts Value: The font version.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Gets the string contained value in XMP format.

**Returns:**
java.lang.String - Returns the string contained value in XMP format.
