---
title: TiffImage.Rotate
second_title: Aspose.Imaging for .NET API Reference
description: TiffImage method. Rotate the image around its center point by a specified angle enabling precise orientation adjustments. Incorporate this functionality into your image processing pipeline to facilitate accurate transformations ensuring optimal alignment and presentation of visual content within your application
type: docs
weight: 370
url: /net/aspose.imaging.fileformats.tiff/tiffimage/rotate/
---
## TiffImage.Rotate method

Rotate the image around its center point by a specified angle, enabling precise orientation adjustments. Incorporate this functionality into your image processing pipeline to facilitate accurate transformations, ensuring optimal alignment and presentation of visual content within your application.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| Parameter | Type | Description |
| --- | --- | --- |
| angle | Single | The rotate angle in degrees. Positive values will rotate clockwise. |
| resizeProportionally | Boolean | if set to `true` you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only internal image contents are rotated. |
| backgroundColor | Color | Color of the background. |

## Examples

The following example shows how to rotate a TIFF image around the center by 45 degrees clockwise.

```csharp
[C#]

string dir = "c:\\temp\\";
Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    
// Create a permanent, not temporary file source.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "rotated.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // The linear gradient from the left-top to the right-bottom corner of the image.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Fill the active frame with the linear gradient brush.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // Rotate the image around the center by 45 degrees clockwise. 
    // The image size changed according to rotated rectangle (corner points).
    tiffImage.Rotate(45f, true, Aspose.Imaging.Color.Black);
    tiffImage.Save();

    // Rotate the image around the center by 45 degrees clockwise.
    // Leave the image dimensions untouched and only the internal image content are rotated.
    tiffImage.Rotate(45f, false, Aspose.Imaging.Color.Gray);
    tiffImage.Save(dir + "rotated.preservesize.tif");
}
```

### See Also

* struct [Color](../../../aspose.imaging/color/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


