---
title: Grayscale
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 280
url: /net/aspose.imaging.fileformats.tiff/tiffimage/grayscale/
---
## TiffImage.Grayscale method

Transformation of an image to its grayscale representation

```csharp
public override void Grayscale()
```

### Examples

The following example transforms a colored TIFF image to its grayscale representation. Grayscale images are composed exclusively of shades of gray and carry only intensity information.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    tiffImage.Grayscale();
    tiffImage.Save(dir + "sample.Grayscale.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [TiffImage](../../tiffimage)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
