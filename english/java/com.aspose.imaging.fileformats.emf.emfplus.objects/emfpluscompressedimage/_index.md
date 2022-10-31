---
title: EmfPlusCompressedImage
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusCompressedImage object specifies an image with compressed data.
type: docs
weight: 31
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompressedimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBitmapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata)
```
public final class EmfPlusCompressedImage extends EmfPlusBaseBitmapData
```

The EmfPlusCompressedImage object specifies an image with compressed data.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusCompressedImage()](#EmfPlusCompressedImage--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getCompressedImageData()](#getCompressedImageData--) | Gets or sets an array of bytes, which specify the compressed image. |
| [setCompressedImageData(byte[] value)](#setCompressedImageData-byte---) | Gets or sets an array of bytes, which specify the compressed image. |
### EmfPlusCompressedImage() {#EmfPlusCompressedImage--}
```
public EmfPlusCompressedImage()
```


### getCompressedImageData() {#getCompressedImageData--}
```
public byte[] getCompressedImageData()
```


Gets or sets an array of bytes, which specify the compressed image. The type of compression MUST be determined from the data itself.

Bitmaps are specified by EmfPlusBitmap objects (section 2.2.2.2). An EmfPlusCompressedImage object MUST be present in the BitmapData field of an EmfPlusBitmap object if BitmapDataTypeCompressed is specified in its Type field. This object is generic and is used for different types of compressed data, including: \\uf0a7 Exchangeable Image File Format(EXIF), as specified in [EXIF]; \\uf0a7 Graphics Interchange Format(GIF), as specified in [GIF]; \\uf0a7 Joint Photographic Experts Group(JPEG), as specified in [JFIF]; \\uf0a7 Portable Network Graphics(PNG), as specified in [RFC2083] and[W3C - PNG]; and \\uf0a7 Tag Image File Format(TIFF), as specified in [RFC3302] and[TIFF].

**Returns:**
byte[]
### setCompressedImageData(byte[] value) {#setCompressedImageData-byte---}
```
public void setCompressedImageData(byte[] value)
```


Gets or sets an array of bytes, which specify the compressed image. The type of compression MUST be determined from the data itself.

Bitmaps are specified by EmfPlusBitmap objects (section 2.2.2.2). An EmfPlusCompressedImage object MUST be present in the BitmapData field of an EmfPlusBitmap object if BitmapDataTypeCompressed is specified in its Type field. This object is generic and is used for different types of compressed data, including: \\uf0a7 Exchangeable Image File Format(EXIF), as specified in [EXIF]; \\uf0a7 Graphics Interchange Format(GIF), as specified in [GIF]; \\uf0a7 Joint Photographic Experts Group(JPEG), as specified in [JFIF]; \\uf0a7 Portable Network Graphics(PNG), as specified in [RFC2083] and[W3C - PNG]; and \\uf0a7 Tag Image File Format(TIFF), as specified in [RFC3302] and[TIFF].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

