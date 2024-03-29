---
title: ObjectsPoints
second_title: Aspose.Imaging för .NET API-referens
description: Hämtar eller ställer in punkterna som hör till separerade objekt valfritt NumberOfObjects koordinater som tillhör NumberOfObjects objekt i initialbilden. Denna parameter används för att öka segmenteringsmetodens precision.
type: docs
weight: 40
url: /sv/net/aspose.imaging.masking.options/automaskingargs/objectspoints/
---
## AutoMaskingArgs.ObjectsPoints property

Hämtar eller ställer in punkterna som hör till separerade objekt (valfritt) NumberOfObjects koordinater som tillhör NumberOfObjects objekt i initialbilden. Denna parameter används för att öka segmenteringsmetodens precision.

```csharp
public Point[][] ObjectsPoints { get; set; }
```

### Fastighetsvärde

Objekten pekar.

### Exempel

Det här exemplet visar hur man anger förslag på bildmaskeringsalgoritmer för att förbättra precisionen i segmenteringsmetoden (klustring). Bildmaskering är en bildbehandlingsteknik som används för att dela upp bakgrunden från förgrundsbildobjekten.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

    // Förslag #1.
    // Analysera bilden visuellt och ställ in intresseområdet. Resultatet av segmenteringen kommer endast att omfatta objekt som kommer att vara helt placerade inom detta område.
    args.ObjectsRectangles = new Rectangle[]
    {
        new Rectangle(86, 6, 270, 364),
    };

    // Förslag #2.
    // Analysera bilden visuellt och ställ in punkterna som hör till separerade objekt.
    args.ObjectsPoints = new Point[][]
    {
        new Point[] { new Point(103, 326) },
        new Point[] { new Point(280, 43) },
        new Point[] { new Point(319, 86) },
    };

    // Varje kluster (segment) kommer att lagras i en separat PNG-fil.
    Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
    exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
        
    // Använd GraphCut-klustring.
    maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
    maskingOptions.Decompose = false;
    maskingOptions.Args = args;

    // Bakgrundsfärgen kommer att vara orange.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // Skapa en instans av klassen ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Dela upp källbilden i flera kluster (segment).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Skaffa bilder från maskeringsresultat och spara dem i PNG.
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

### Se även

* struct [Point](../../../aspose.imaging/point)
* class [AutoMaskingArgs](../../automaskingargs)
* namnutrymme [Aspose.Imaging.Masking.Options](../../automaskingargs)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
