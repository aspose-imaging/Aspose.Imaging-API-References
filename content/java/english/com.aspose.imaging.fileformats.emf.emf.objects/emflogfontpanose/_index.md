---
title: EmfLogFontPanose
second_title: Aspose.Imaging for Java API Reference
description: The LogFontPanose object specifies the PANOSE characteristics of a logical font.
type: docs
weight: 25
url: /com.aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont)
```
public final class EmfLogFontPanose extends EmfLogFont
```

The LogFontPanose object specifies the PANOSE characteristics of a logical font.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfLogFontPanose(EmfLogFont emfLogFont)](#EmfLogFontPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-) | Initializes a new instance of the `EmfLogFontPanose` class. |
## Methods

| Method | Description |
| --- | --- |
| [getFullName()](#getFullName--) | Gets or sets a string of 64 Unicode characters that defines the font's full name. |
| [setFullName(String value)](#setFullName-java.lang.String-) | Gets or sets a string of 64 Unicode characters that defines the font's full name. |
| [getStyle()](#getStyle--) | Gets or sets a string of 32 Unicode characters that defines the font's style. |
| [setStyle(String value)](#setStyle-java.lang.String-) | Gets or sets a string of 32 Unicode characters that defines the font's style. |
| [getVersion()](#getVersion--) | Gets or sets This field MUST be ignored. |
| [setVersion(int value)](#setVersion-int-) | Gets or sets This field MUST be ignored. |
| [getStyleSize()](#getStyleSize--) | Gets or sets a 32-bit unsigned integer that specifies the point size at which font hinting is performed. |
| [setStyleSize(int value)](#setStyleSize-int-) | Gets or sets a 32-bit unsigned integer that specifies the point size at which font hinting is performed. |
| [getMatch()](#getMatch--) | Gets or sets This field MUST be ignored. |
| [setMatch(int value)](#setMatch-int-) | Gets or sets This field MUST be ignored. |
| [getVendorId()](#getVendorId--) | Gets or sets This field MUST be ignored. |
| [setVendorId(int value)](#setVendorId-int-) | Gets or sets This field MUST be ignored. |
| [getCulture()](#getCulture--) | Gets or sets a 32-bit unsigned integer that MUST be set to zero and MUST be ignored. |
| [setCulture(int value)](#setCulture-int-) | Gets or sets a 32-bit unsigned integer that MUST be set to zero and MUST be ignored. |
| [getPanose()](#getPanose--) | Gets or sets a Panose object (section 2.2.21) that specifies the PANOSE characteristics of the logical font. |
| [setPanose(EmfPanose value)](#setPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfPanose-) | Gets or sets a Panose object (section 2.2.21) that specifies the PANOSE characteristics of the logical font. |
| [getPadding()](#getPadding--) | Gets or sets a field that exists only to ensure 32-bit alignment of this structure. |
| [setPadding(short value)](#setPadding-short-) | Gets or sets a field that exists only to ensure 32-bit alignment of this structure. |
### EmfLogFontPanose(EmfLogFont emfLogFont) {#EmfLogFontPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-}
```
public EmfLogFontPanose(EmfLogFont emfLogFont)
```


Initializes a new instance of the `EmfLogFontPanose` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| emfLogFont | [EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont) | The base log font. |

### getFullName() {#getFullName--}
```
public String getFullName()
```


Gets or sets a string of 64 Unicode characters that defines the font's full name. If the length of this string is less than 64 characters, a terminating NULL MUST be present, after which the remainder of this field MUST be ignored.

**Returns:**
java.lang.String
### setFullName(String value) {#setFullName-java.lang.String-}
```
public void setFullName(String value)
```


Gets or sets a string of 64 Unicode characters that defines the font's full name. If the length of this string is less than 64 characters, a terminating NULL MUST be present, after which the remainder of this field MUST be ignored.

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

### getVersion() {#getVersion--}
```
public int getVersion()
```


Gets or sets This field MUST be ignored.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Gets or sets This field MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStyleSize() {#getStyleSize--}
```
public int getStyleSize()
```


Gets or sets a 32-bit unsigned integer that specifies the point size at which font hinting is performed. If set to zero, font hinting is performed at the point size corresponding to the Height field in the LogFont object in the LogFont field

**Returns:**
int
### setStyleSize(int value) {#setStyleSize-int-}
```
public void setStyleSize(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the point size at which font hinting is performed. If set to zero, font hinting is performed at the point size corresponding to the Height field in the LogFont object in the LogFont field

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMatch() {#getMatch--}
```
public int getMatch()
```


Gets or sets This field MUST be ignored.

**Returns:**
int
### setMatch(int value) {#setMatch-int-}
```
public void setMatch(int value)
```


Gets or sets This field MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVendorId() {#getVendorId--}
```
public int getVendorId()
```


Gets or sets This field MUST be ignored.

**Returns:**
int
### setVendorId(int value) {#setVendorId-int-}
```
public void setVendorId(int value)
```


Gets or sets This field MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCulture() {#getCulture--}
```
public int getCulture()
```


Gets or sets a 32-bit unsigned integer that MUST be set to zero and MUST be ignored.

**Returns:**
int
### setCulture(int value) {#setCulture-int-}
```
public void setCulture(int value)
```


Gets or sets a 32-bit unsigned integer that MUST be set to zero and MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPanose() {#getPanose--}
```
public EmfPanose getPanose()
```


Gets or sets a Panose object (section 2.2.21) that specifies the PANOSE characteristics of the logical font. If all fields of this object are zero, it MUST be ignored.

**Returns:**
[EmfPanose](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpanose)
### setPanose(EmfPanose value) {#setPanose-com.aspose.imaging.fileformats.emf.emf.objects.EmfPanose-}
```
public void setPanose(EmfPanose value)
```


Gets or sets a Panose object (section 2.2.21) that specifies the PANOSE characteristics of the logical font. If all fields of this object are zero, it MUST be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPanose](../../com.aspose.imaging.fileformats.emf.emf.objects/emfpanose) |  |

### getPadding() {#getPadding--}
```
public short getPadding()
```


Gets or sets a field that exists only to ensure 32-bit alignment of this structure. It MUST be ignored

**Returns:**
short
### setPadding(short value) {#setPadding-short-}
```
public void setPadding(short value)
```


Gets or sets a field that exists only to ensure 32-bit alignment of this structure. It MUST be ignored

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

