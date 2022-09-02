---
title: GetImage
second_title: Aspose.Imaging för .NET API-referens
description: Ger resultatbild.
type: docs
weight: 20
url: /sv/net/aspose.imaging.masking.result/imaskinglayer/getimage/
---
## IMaskingLayer.GetImage method

Ger resultatbild.

```csharp
public RasterImage GetImage()
```

### Returvärde

Resultatbild.

### Exempel

Det här exemplet visar hur man bryter ner en rasterbild till flera bilder med hjälp av bildmaskering och K-means segmenteringsalgoritmen. Bildmaskering är en bildbehandlingsteknik som används för att dela upp bakgrunden från förgrundsbildobjekten.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Blue hills.png"))
{
    Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

    // Ställ in antalet kluster (separerade objekt). Standardvärdet är 2, förgrundsobjektet och bakgrunden.
    args.NumberOfObjects = 3;

    // Ställ in det maximala antalet iterationer.
    args.MaxIterationNumber = 50;

    // Ställ in precisionen för segmenteringsmetoden (valfritt)
    args.Precision = 1;
        
    // Varje kluster (segment) kommer att lagras i en separat PNG-fil.
    Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
    exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();

    // Använd K-betyder klustring.
    // K-means klustring gör det möjligt att dela upp bilden i flera oberoende kluster (segment).
    maskingOptions.Method = Masking.Options.SegmentationMethod.KMeans;
    maskingOptions.Decompose = true;
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
            string outputFileName = string.Format("Blue hills.Segment{0}.png", maskingResult[i].ObjectNumber);
            using (Aspose.Imaging.Image resultImage = maskingResult[i].GetImage())
            {
                resultImage.Save(dir + outputFileName);
            }
        }
    }
}
```

Det här exemplet visar hur man delar upp en rasterbild till flera bilder med hjälp av bildmaskering och en manuell mask. Bildmaskering är en bildbehandlingsteknik som används för att dela upp bakgrunden från förgrundsbildobjekten.

```csharp
[C#]

string dir = "c:\\temp\\";

// Definiera en manuell mask.
Aspose.Imaging.GraphicsPath manualMask = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();
figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 40, 40)));
figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new RectangleF(10, 20, 50, 30)));
manualMask.AddFigure(figure);

// Varje kluster (segment) kommer att lagras i en separat PNG-fil.
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

// Ställ in den manuella masken.
Aspose.Imaging.Masking.Options.ManualMaskingArgs args = new Aspose.Imaging.Masking.Options.ManualMaskingArgs();
args.Mask = manualMask;

using (RasterImage image = (RasterImage)Image.Load(dir + "Blue hills.png"))
{
    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();

    // Använd manuell klustringsalgoritm.
    maskingOptions.Method = Masking.Options.SegmentationMethod.Manual;

    // Alla former som utgör en mask kommer att kombineras till en. 
    maskingOptions.Decompose = false;
    maskingOptions.Args = args;

    // Bakgrundsfärgen kommer att vara orange.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // Området av källbilden som maskeringen kommer att tillämpas på.
    maskingOptions.MaskingArea = new Rectangle(50, 50, 120, 120);

    // Skapa en instans av klassen ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Dela upp källbilden i flera kluster (segment).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Skaffa bilder från maskeringsresultat och spara dem i PNG.
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

* class [RasterImage](../../../aspose.imaging/rasterimage)
* interface [IMaskingLayer](../../imaskinglayer)
* namnutrymme [Aspose.Imaging.Masking.Result](../../imaskinglayer)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
