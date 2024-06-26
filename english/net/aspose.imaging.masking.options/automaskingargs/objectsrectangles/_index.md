---
title: AutoMaskingArgs.ObjectsRectangles
second_title: Aspose.Imaging for .NET API Reference
description: AutoMaskingArgs property. Gets or sets the objects rectangles that belong to separated objects optional. This parameter is used to increase segmentation method precision
type: docs
weight: 50
url: /net/aspose.imaging.masking.options/automaskingargs/objectsrectangles/
---
## AutoMaskingArgs.ObjectsRectangles property

Gets or sets the objects rectangles that belong to separated objects (optional). This parameter is used to increase segmentation method precision.

```csharp
public Rectangle[] ObjectsRectangles { get; set; }
```

### Property Value

The objects rectangles.

## Examples

This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method. Image masking is an image processing technique that is used to split the background from the foreground image objects.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

    // Suggestion #1.
    // Analyze the image visually and set the area of interest. The result of segmentation will include only objects that will be completely located within this area.
    args.ObjectsRectangles = new Rectangle[]
    {
        new Rectangle(86, 6, 270, 364),
    };

    // Suggestion #2.
    // Analyze the image visually and set the points that belong to separated objects.
    args.ObjectsPoints = new Point[][]
    {
        new Point[] { new Point(103, 326) },
        new Point[] { new Point(280, 43) },
        new Point[] { new Point(319, 86) },
    };

    // Each cluster (segment) will be stored to a separate PNG file.
    Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
    exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
        
    // Use GraphCut clustering.
    maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
    maskingOptions.Decompose = false;
    maskingOptions.Args = args;

    // The backgroung color will be orange.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // Create an instance of the ImageMasking class.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Divide the source image into several clusters (segments).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Obtain images from masking result and save them to PNG.
        for (int i = 0; i < maskingResult.Length; i++)
        {
            string outputFileName = string.Format("Gorilla.Segment{0}.png", maskingResult[i].ObjectNumber);
            using (Aspose.Imaging.Image resultImage = maskingResult[i].GetImage())
            {
                resultImage.Save(dir + outputFileName);
            }
        }
    }
}
```

### See Also

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [AutoMaskingArgs](../)
* namespace [Aspose.Imaging.Masking.Options](../../automaskingargs/)
* assembly [Aspose.Imaging](../../../)


