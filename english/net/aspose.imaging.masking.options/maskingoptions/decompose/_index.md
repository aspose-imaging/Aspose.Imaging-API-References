---
title: MaskingOptions.Decompose
second_title: Aspose.Imaging for .NET API Reference
description: MaskingOptions property. Gets or sets a value indicating whether needless to separate each Shape from mask as individual object or as united object from mask separated from background
type: docs
weight: 40
url: /net/aspose.imaging.masking.options/maskingoptions/decompose/
---
## MaskingOptions.Decompose property

Gets or sets a value indicating whether needless to separate each Shape from mask as individual object or as united object from mask separated from background.

```csharp
public bool Decompose { get; set; }
```

### Property Value

`true` if decompose; otherwise, `false`.

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

* class [MaskingOptions](../)
* namespace [Aspose.Imaging.Masking.Options](../../maskingoptions/)
* assembly [Aspose.Imaging](../../../)


