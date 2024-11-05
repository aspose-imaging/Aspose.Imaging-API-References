---
title: BmpImage.ToBitmap
second_title: Aspose.Imaging for .NET API Reference
description: BmpImage method. Easily convert your raster image to a bitmap with this simple method. Perfect for developers needing to seamlessly transition between different image formats
type: docs
weight: 150
url: /net/aspose.imaging.fileformats.bmp/bmpimage/tobitmap/
---
## BmpImage.ToBitmap method

Easily convert your raster image to a bitmap with this simple method. Perfect for developers needing to seamlessly transition between different image formats.

```csharp
public override Bitmap ToBitmap()
```

### Return Value

The bitmap

## Examples

The following example converts a BMP image to a GDI bitmap.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
    System.Drawing.Bitmap bitmap = bmpImage.ToBitmap();

    // Process the GDI bitmap.
}
```

### See Also

* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)


