---
title: EmfPlusCompressedImage.CompressedImageData
second_title: Aspose.Imaging for .NET API Reference
description: EmfPlusCompressedImage property. Gets or sets an array of bytes which specify the compressed image. The type of compression MUST be determined from the data itself
type: docs
weight: 20
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompressedimage/compressedimagedata/
---
## EmfPlusCompressedImage.CompressedImageData property

Gets or sets an array of bytes, which specify the compressed image. The type of compression MUST be determined from the data itself.

```csharp
public byte[] CompressedImageData { get; set; }
```

## Remarks

Bitmaps are specified by EmfPlusBitmap objects (section 2.2.2.2). An EmfPlusCompressedImage object MUST be present in the BitmapData field of an EmfPlusBitmap object if BitmapDataTypeCompressed is specified in its Type field. This object is generic and is used for different types of compressed data, including:  Exchangeable Image File Format(EXIF), as specified in [EXIF];  Graphics Interchange Format(GIF), as specified in [GIF];  Joint Photographic Experts Group(JPEG), as specified in [JFIF];  Portable Network Graphics(PNG), as specified in [RFC2083] and[W3C - PNG]; and  Tag Image File Format(TIFF), as specified in [RFC3302] and[TIFF].

### See Also

* class [EmfPlusCompressedImage](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../emfpluscompressedimage/)
* assembly [Aspose.Imaging](../../../)


