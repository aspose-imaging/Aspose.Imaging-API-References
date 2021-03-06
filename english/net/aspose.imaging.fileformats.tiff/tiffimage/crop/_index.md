---
title: Crop
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 240
url: /net/aspose.imaging.fileformats.tiff/tiffimage/crop/
---
## TiffImage.Crop method (1 of 2)

Cropping the image.

```csharp
public override void Crop(Rectangle rectangle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | The rectangle. |

### Examples

The following example crops a TIFF image. The cropping area is be specified via Aspose.Imaging.Rectangle.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Crop the image. The cropping area is the rectangular central area of the image.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(tiffImage.Width / 4, tiffImage.Height / 4, tiffImage.Width / 2, tiffImage.Height / 2);
    tiffImage.Crop(area);

    // Save the cropped image to PNG
    tiffImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* struct [Rectangle](../../../aspose.imaging/rectangle)
* class [TiffImage](../../tiffimage)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* assembly [Aspose.Imaging](../../../)

---

## TiffImage.Crop method (2 of 2)

Crop image with shifts.

```csharp
public override void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Parameter | Type | Description |
| --- | --- | --- |
| leftShift | Int32 | The left shift. |
| rightShift | Int32 | The right shift. |
| topShift | Int32 | The top shift. |
| bottomShift | Int32 | The bottom shift. |

### Examples

The following example crops a TIFF image. The cropping area is specified via Left, Top, Right, Bottom margins.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Crop again. Set a margin of 10% of the image size.
    int horizontalMargin = tiffImage.Width / 10;
    int verticalMargin = tiffImage.Height / 10;
    tiffImage.Crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Save the cropped image to PNG.
    tiffImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [TiffImage](../../tiffimage)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
