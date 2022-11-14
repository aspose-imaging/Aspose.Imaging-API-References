---
title: EmfLogFontEx
second_title: Aspose.Imaging for Java API Reference
description: The LogFontEx object specifies the extended attributes of a logical font.
type: docs
weight: 23
url: /java/com.aspose.imaging.fileformats.emf.emf.objects/emflogfontex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont)
```
public class EmfLogFontEx extends EmfLogFont
```

The LogFontEx object specifies the extended attributes of a logical font.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfLogFontEx(EmfLogFont emfLogFont)](#EmfLogFontEx-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-) | Initializes a new instance of the `EmfLogFontEx` class. |
## Methods

| Method | Description |
| --- | --- |
| [getFullName()](#getFullName--) | Gets or sets a string of 64 Unicode characters that contains the font's full name. |
| [setFullName(String value)](#setFullName-java.lang.String-) | Gets or sets a string of 64 Unicode characters that contains the font's full name. |
| [getStyle()](#getStyle--) | Gets or sets a string of 32 Unicode characters that defines the font's style. |
| [setStyle(String value)](#setStyle-java.lang.String-) | Gets or sets a string of 32 Unicode characters that defines the font's style. |
| [getScript()](#getScript--) | Gets or sets a string of 32 Unicode characters that defines the character set of the font. |
| [setScript(String value)](#setScript-java.lang.String-) | Gets or sets a string of 32 Unicode characters that defines the character set of the font. |
### EmfLogFontEx(EmfLogFont emfLogFont) {#EmfLogFontEx-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-}
```
public EmfLogFontEx(EmfLogFont emfLogFont)
```


Initializes a new instance of the `EmfLogFontEx` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| emfLogFont | [EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont) | The EMF log font. |

### getFullName() {#getFullName--}
```
public String getFullName()
```


Gets or sets a string of 64 Unicode characters that contains the font's full name. If the length of this string is less than 64 characters, a terminating NULL MUST be present, after which the remainder of this field MUST be ignored.

**Returns:**
java.lang.String
### setFullName(String value) {#setFullName-java.lang.String-}
```
public void setFullName(String value)
```


Gets or sets a string of 64 Unicode characters that contains the font's full name. If the length of this string is less than 64 characters, a terminating NULL MUST be present, after which the remainder of this field MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getStyle() {#getStyle--}
```
public String getStyle()
```


Gets or sets a string of 32 Unicode characters that defines the font's style. If the length of this string is less than 32 characters, a terminating NULL MUST be present, after which the remainder of this field MUST be ignored.

**Returns:**
java.lang.String
### setStyle(String value) {#setStyle-java.lang.String-}
```
public void setStyle(String value)
```


Gets or sets a string of 32 Unicode characters that defines the font's style. If the length of this string is less than 32 characters, a terminating NULL MUST be present, after which the remainder of this field MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getScript() {#getScript--}
```
public String getScript()
```


Gets or sets a string of 32 Unicode characters that defines the character set of the font. If the length of this string is less than 32 characters, a terminating NULL MUST be present, after which the remainder of this field MUST be ignored.

**Returns:**
java.lang.String
### setScript(String value) {#setScript-java.lang.String-}
```
public void setScript(String value)
```


Gets or sets a string of 32 Unicode characters that defines the character set of the font. If the length of this string is less than 32 characters, a terminating NULL MUST be present, after which the remainder of this field MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

