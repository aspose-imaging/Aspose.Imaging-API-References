---
title: Class ManualMaskingArgs
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.Masking.Options.ManualMaskingArgs class. Represents the arguments that are specified for manual masking method
type: docs
weight: 10980
url: /net/aspose.imaging.masking.options/manualmaskingargs/
---
## ManualMaskingArgs class

Represents the arguments that are specified for manual masking method

```csharp
public class ManualMaskingArgs : IMaskingArgs
```

## Constructors

| Name | Description |
| --- | --- |
| [ManualMaskingArgs](manualmaskingargs/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Mask](../../aspose.imaging.masking.options/manualmaskingargs/mask/) { get; set; } | Gets or sets the set of graphic shapes that form mask. |

## Examples

This example shows how to decompose a raster image into multiple images using image masking and a manual mask. Image masking is an image processing technique that is used to split the background from the foreground image objects.

```csharp
[C#]

string dir = "c:\\temp\\";

// Define a manual mask.
Aspose.Imaging.GraphicsPath manualMask = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();
figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 40, 40)));
figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new RectangleF(10, 20, 50, 30)));
manualMask.AddFigure(figure);

// Each cluster (segment) will be stored to a separate PNG file.
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

// Set the manual mask.
Aspose.Imaging.Masking.Options.ManualMaskingArgs args = new Aspose.Imaging.Masking.Options.ManualMaskingArgs();
args.Mask = manualMask;

using (RasterImage image = (RasterImage)Image.Load(dir + "Blue hills.png"))
{
    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();

    // Use manual clustering algorithm.
    maskingOptions.Method = Masking.Options.SegmentationMethod.Manual;

    // All shapes making up a mask will be combined into one. 
    maskingOptions.Decompose = false;
    maskingOptions.Args = args;

    // The backgroung color will be orange.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // The area of the source image that masking will be applied to.
    maskingOptions.MaskingArea = new Rectangle(50, 50, 120, 120);

    // Create an instance of the ImageMasking class.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Divide the source image into several clusters (segments).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Obtain images from masking result and save them to PNG.
        for (int i = 0; i < maskingResult.Length; i++)
        {
            string outputFileName = string.Format("Blue hills.Segment{0}.png", maskingResult[i].ObjectNumber);
            using (Aspose.Imaging.Image resultImage = maskingResult[i].GetImage())
            {
                resultImage.Save(dir + outputFileName);
            }
        }
    }
}
```

### See Also

* interface [IMaskingArgs](../imaskingargs/)
* namespace [Aspose.Imaging.Masking.Options](../../aspose.imaging.masking.options/)
* assembly [Aspose.Imaging](../../)


