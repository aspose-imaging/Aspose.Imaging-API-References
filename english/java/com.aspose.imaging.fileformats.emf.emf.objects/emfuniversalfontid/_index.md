---
title: EmfUniversalFontId
second_title: Aspose.Imaging for Java API Reference
description: The UniversalFontId object defines a mechanism for identifying fonts in EMF metafiles.
type: docs
weight: 37
url: /java/com.aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfUniversalFontId extends EmfObject
```

The UniversalFontId object defines a mechanism for identifying fonts in EMF metafiles.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfUniversalFontId()](#EmfUniversalFontId--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getChecksum()](#getChecksum--) | Gets or sets a 32-bit unsigned integer that is the checksum of the font. |
| [setChecksum(int value)](#setChecksum-int-) | Gets or sets a 32-bit unsigned integer that is the checksum of the font. |
| [getIndex()](#getIndex--) | Gets or sets a 32-bit unsigned integer that is an index associated with the font object. |
| [setIndex(int value)](#setIndex-int-) | Gets or sets a 32-bit unsigned integer that is an index associated with the font object. |
### EmfUniversalFontId() {#EmfUniversalFontId--}
```
public EmfUniversalFontId()
```


### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Gets or sets a 32-bit unsigned integer that is the checksum of the font. The checksum value has the following meanings. 0x00000000 The object is a device font. 0x00000001 The object is a Type 1 font that has been installed on the client machine and is enumerated by the PostScript printer driver as a device font. 0x00000002 The object is not a font but is a Type 1 rasterizer. 3 \\u2264 value The object is a bitmap, vector, or TrueType font, or a Type 1 rasterized font that was created by a Type 1 rasterizer.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Gets or sets a 32-bit unsigned integer that is the checksum of the font. The checksum value has the following meanings. 0x00000000 The object is a device font. 0x00000001 The object is a Type 1 font that has been installed on the client machine and is enumerated by the PostScript printer driver as a device font. 0x00000002 The object is not a font but is a Type 1 rasterizer. 3 \\u2264 value The object is a bitmap, vector, or TrueType font, or a Type 1 rasterized font that was created by a Type 1 rasterizer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getIndex() {#getIndex--}
```
public int getIndex()
```


Gets or sets a 32-bit unsigned integer that is an index associated with the font object. The meaning of this field is determined by the type of font.

**Returns:**
int
### setIndex(int value) {#setIndex-int-}
```
public void setIndex(int value)
```


Gets or sets a 32-bit unsigned integer that is an index associated with the font object. The meaning of this field is determined by the type of font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

