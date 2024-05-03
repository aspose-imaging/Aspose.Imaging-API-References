---
title: EmfPlusBitmap.Stride
second_title: Aspose.Imaging for .NET API Reference
description: EmfPlusBitmap property. Gets or sets stride of the image Stride 4 bytes A 32bit signed integer that specifies the byte offset between the beginning of one scanline and the next. This value is the number of bytes per pixel which is specified in the PixelFormat field multiplied by the width in pixels which is specified in the Width field. The value of this field MUST be a multiple of four. If the image is compressed according to the Type field this value is undefined and MUST be ignored
type: docs
weight: 50
url: /net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/stride/
---
## EmfPlusBitmap.Stride property

Gets or sets stride of the image Stride (4 bytes): A 32-bit signed integer that specifies the byte offset between the beginning of one scan-line and the next. This value is the number of bytes per pixel, which is specified in the PixelFormat field, multiplied by the width in pixels, which is specified in the Width field. The value of this field MUST be a multiple of four. If the image is compressed, according to the Type field, this value is undefined and MUST be ignored.

```csharp
public int Stride { get; set; }
```

### Property Value

The stride.

### See Also

* class [EmfPlusBitmap](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../emfplusbitmap/)
* assembly [Aspose.Imaging](../../../)


