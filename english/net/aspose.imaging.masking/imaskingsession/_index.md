---
title: Interface IMaskingSession
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.Masking.IMaskingSession interface. The masking session
type: docs
weight: 10880
url: /net/aspose.imaging.masking/imaskingsession/
---
## IMaskingSession interface

The masking session

```csharp
public interface IMaskingSession : IDisposable
```

## Methods

| Name | Description |
| --- | --- |
| [Decompose](../../aspose.imaging.masking/imaskingsession/decompose/)() | Performs first rough decompose operation |
| [DecomposeAsync](../../aspose.imaging.masking/imaskingsession/decomposeasync/)() | Creates the asynchronous task which can perform first rough decompose operation |
| [ImproveDecomposition](../../aspose.imaging.masking/imaskingsession/improvedecomposition/)(IMaskingArgs) | Performs retraining decompose operation |
| [ImproveDecompositionAsync](../../aspose.imaging.masking/imaskingsession/improvedecompositionasync/)(IMaskingArgs) | Creates the asynchronous task which can perform retraining decompose operation |
| [Save](../../aspose.imaging.masking/imaskingsession/save/#save)(Stream) | Save the session state to the specified stream. |
| [Save](../../aspose.imaging.masking/imaskingsession/save/#save_1)(string) | Saves the session state to the specified file. |

## Examples

Saving the masking session to a file for long sessions, as well as for the possibility of resuming the session in another environment.

```csharp
[C#]

string dir = "c:\\temp\\";
string sessionBackupFile = dir + "session.bak";

// Masking export options
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// Use GraphCut clustering.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// The backgroung color will be orange.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
maskingOptions.ExportOptions = exportOptions;

// Starting a session for the first time and saving to a file
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // Create an instance of the ImageMasking class.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    using (Aspose.Imaging.Masking.IMaskingSession session = masking.CreateSession(maskingOptions))
    {
        using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = session.Decompose())
        {
            using (Aspose.Imaging.RasterImage segmentImage = maskingResult[1].GetImage())
            {
                segmentImage.Save(dir + "step1.png");
            }
        }

        session.Save(sessionBackupFile);
    }
}

// Resuming a masking session from a file
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // Create an instance of the ImageMasking class.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    using (Aspose.Imaging.Masking.IMaskingSession session = masking.LoadSession(sessionBackupFile))
    {
        Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

        // Analyze the image visually and set the points that belong to separated objects.
        args.ObjectsPoints = new Point[][]
                                     {
                                         new Point[]
                                             {
                                                 new Point(0, 0), new Point(0, 1), new Point(1, 0),
                                                 new Point(1, 1), new Point(2, 0), new Point(2, 1),
                                                 new Point(3, 0), new Point(3, 1)
                                             },
                                     };
        using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = session.ImproveDecomposition(args))
        {
            // Explicit transfer of export options, since it is not serializable
            maskingResult.MaskingOptions.ExportOptions = exportOptions;

            using (Aspose.Imaging.RasterImage segmentImage = maskingResult[1].GetImage())
            {
                segmentImage.Save(dir + "step2.png");
            }
        }
    }
}
```

### See Also

* namespace [Aspose.Imaging.Masking](../../aspose.imaging.masking/)
* assembly [Aspose.Imaging](../../)


