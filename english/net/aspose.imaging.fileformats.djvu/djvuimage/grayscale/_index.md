---
title: DjvuImage.Grayscale
second_title: Aspose.Imaging for .NET API Reference
description: DjvuImage method. Grayscale transformation converts an image to a blackandwhite representation where each pixels intensity is represented by a single value ranging from black to white. This process removes color information resulting in a monochromatic image. Grayscale images are commonly used in applications where color is unnecessary or where simplicity is preferred such as document scanning printing and certain types of image analysis
type: docs
weight: 250
url: /net/aspose.imaging.fileformats.djvu/djvuimage/grayscale/
---
## DjvuImage.Grayscale method

Grayscale transformation converts an image to a black-and-white representation, where each pixel's intensity is represented by a single value ranging from black to white. This process removes color information, resulting in a monochromatic image. Grayscale images are commonly used in applications where color is unnecessary or where simplicity is preferred, such as document scanning, printing, and certain types of image analysis.

```csharp
public override void Grayscale()
```

## Examples

The following example transforms a colored DJVU image to its grayscale representation. Grayscale images are composed exclusively of shades of gray and carry only intensity information.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    djvuImage.Grayscale();
    djvuImage.Save(dir + "sample.Grayscale.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


