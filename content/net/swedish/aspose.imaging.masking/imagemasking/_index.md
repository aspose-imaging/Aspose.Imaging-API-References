---
title: ImageMasking
second_title: Aspose.Imaging för .NET API-referens
description: Ger bildmaskeringsoperationer
type: docs
weight: 10430
url: /sv/aspose.imaging.masking/imagemasking/
---
## ImageMasking class

Ger bildmaskeringsoperationer

```csharp
public class ImageMasking
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ImageMasking](imagemasking)(RasterImage) | Initierar en ny instans av[`ImageMasking`](../imagemasking) class. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [CreateSession](../../aspose.imaging.masking/imagemasking/createsession)(MaskingOptions) | Skapar maskeringssessionen som kan utföra omträningsoperationer. |
| [Decompose](../../aspose.imaging.masking/imagemasking/decompose)(MaskingOptions) | Utför nedbrytningsoperationen med angivna maskeringsalternativ |
| [DecomposeAsync](../../aspose.imaging.masking/imagemasking/decomposeasync)(MaskingOptions) | Skapar den asynkrona nedbrytningsuppgiften med angivna maskeringsalternativ. |
| [LoadSession](../../aspose.imaging.masking/imagemasking/loadsession#loadsession)(Stream) | Ladda sessionen från den angivna strömmen. |
| [LoadSession](../../aspose.imaging.masking/imagemasking/loadsession#loadsession_1)(string) | Ladda sessionen från den angivna filen. |
| static [ApplyMask](../../aspose.imaging.masking/imagemasking/applymask)(RasterImage, RasterImage, MaskingOptions) | Tillämpar masken på angiven källbild. |

### Exempel

Använda en segmentmask för att påskynda segmenteringsprocessen

```csharp
[C#]

// Maskering av exportalternativ
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// Använd GraphCut-klustring.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// Bakgrundsfärgen kommer att vara transparent.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Transparent;
maskingOptions.ExportOptions = exportOptions;

string dir = "c:\\temp\\";
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
{
    Aspose.Imaging.Size imageSize = image.Size;

    // Minska bildstorleken för att påskynda segmenteringsprocessen
    image.ResizeHeightProportionally(600, Aspose.Imaging.ResizeType.HighQualityResample);

    // Skapa en instans av klassen ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Dela upp källbilden i flera kluster (segment).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Får förgrundsmasken
        using (Aspose.Imaging.RasterImage foregroundMask = maskingResult[1].GetMask()) 
        {
            // Öka storleken på masken till storleken på originalbilden
            foregroundMask.Resize(imageSize.Width, imageSize.Height, Aspose.Imaging.ResizeType.NearestNeighbourResample);

            // Applicera masken på originalbilden för att få ett förgrundssegment
            using (Aspose.Imaging.RasterImage originImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
            {
                Aspose.Imaging.Masking.ImageMasking.ApplyMask(originImage, foregroundMask, maskingOptions);
                originImage.Save(dir + "BigImage_foreground.png", exportOptions);
            }
        }
    }
}
```

Spara maskeringssessionen till en fil för långa sessioner, samt för möjligheten att återuppta sessionen i en annan miljö.

```csharp
[C#]

string dir = "c:\\temp\\";
string sessionBackupFile = dir + "session.bak";

// Maskering av exportalternativ
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// Använd GraphCut-klustring.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// Bakgrundsfärgen kommer att vara orange.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
maskingOptions.ExportOptions = exportOptions;

// Starta en session för första gången och spara till en fil
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // Skapa en instans av klassen ImageMasking.
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

// Återuppta en maskeringssession från en fil
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // Skapa en instans av klassen ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    using (Aspose.Imaging.Masking.IMaskingSession session = masking.LoadSession(sessionBackupFile))
    {
        Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

        // Analysera bilden visuellt och ställ in punkterna som hör till separerade objekt.
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
            // Explicit överföring av exportalternativ, eftersom det inte går att serialisera
            maskingResult.MaskingOptions.ExportOptions = exportOptions;

            using (Aspose.Imaging.RasterImage segmentImage = maskingResult[1].GetImage())
            {
                segmentImage.Save(dir + "step2.png");
            }
        }
    }
}
```

### Se även

* namnutrymme [Aspose.Imaging.Masking](../../aspose.imaging.masking)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
