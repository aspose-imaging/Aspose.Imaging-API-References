---
title: Length
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft die Länge ab.
type: docs
weight: 30
url: /de/aspose.imaging.masking.result/maskingresult/length/
---
## MaskingResult.Length property

Ruft die Länge ab.

```csharp
public int Length { get; }
```

### Eigentumswert

Die Länge.

### Beispiele

Dieses Beispiel zeigt, wie ein Rasterbild mithilfe von Bildmaskierung und dem K-Means-Segmentierungsalgorithmus in mehrere Bilder zerlegt wird. Bildmaskierung ist eine Bildverarbeitungstechnik, die verwendet wird, um den Hintergrund von den Vordergrundbildobjekten zu trennen.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Blue hills.png"))
{
    Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

    // Legen Sie die Anzahl der Cluster (getrennte Objekte) fest. Der Standardwert ist 2, das Vordergrundobjekt und der Hintergrund.
    args.NumberOfObjects = 3;

    // Legen Sie die maximale Anzahl von Iterationen fest.
    args.MaxIterationNumber = 50;

    // Legen Sie die Genauigkeit der Segmentierungsmethode fest (optional)
    args.Precision = 1;
        
    // Jeder Cluster (Segment) wird in einer separaten PNG-Datei gespeichert.
    Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
    exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();

    // K-Means-Clustering verwenden.
    // K-Means-Clustering ermöglicht es, das Bild in mehrere unabhängige Cluster (Segmente) aufzuteilen.
    maskingOptions.Method = Masking.Options.SegmentationMethod.KMeans;
    maskingOptions.Decompose = true;
    maskingOptions.Args = args;
        
    // Die Hintergrundfarbe ist orange.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // Erstellen Sie eine Instanz der ImageMasking-Klasse.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Teilen Sie das Quellbild in mehrere Cluster (Segmente).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Bilder aus dem Maskierungsergebnis abrufen und als PNG speichern.
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

Dieses Beispiel zeigt, wie Sie ein Rasterbild mithilfe der Bildmaskierung und einer manuellen Maske in mehrere Bilder zerlegen. Bildmaskierung ist eine Bildverarbeitungstechnik, die verwendet wird, um den Hintergrund von den Vordergrundbildobjekten zu trennen.

```csharp
[C#]

string dir = "c:\\temp\\";

// Definiere eine manuelle Maske.
Aspose.Imaging.GraphicsPath manualMask = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();
figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 40, 40)));
figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new RectangleF(10, 20, 50, 30)));
manualMask.AddFigure(figure);

// Jeder Cluster (Segment) wird in einer separaten PNG-Datei gespeichert.
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

// Setzen Sie die manuelle Maske.
Aspose.Imaging.Masking.Options.ManualMaskingArgs args = new Aspose.Imaging.Masking.Options.ManualMaskingArgs();
args.Mask = manualMask;

using (RasterImage image = (RasterImage)Image.Load(dir + "Blue hills.png"))
{
    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();

    // Manuellen Clustering-Algorithmus verwenden.
    maskingOptions.Method = Masking.Options.SegmentationMethod.Manual;

    // Alle Formen, aus denen eine Maske besteht, werden zu einer kombiniert. 
    maskingOptions.Decompose = false;
    maskingOptions.Args = args;

    // Die Hintergrundfarbe ist orange.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // Der Bereich des Quellbildes, auf den die Maskierung angewendet wird.
    maskingOptions.MaskingArea = new Rectangle(50, 50, 120, 120);

    // Erstellen Sie eine Instanz der ImageMasking-Klasse.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Teilen Sie das Quellbild in mehrere Cluster (Segmente).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Bilder aus dem Maskierungsergebnis abrufen und als PNG speichern.
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

Dieses Beispiel zeigt, wie Vorschläge für den Bildmaskierungsalgorithmus angegeben werden, um die Genauigkeit der Segmentierungsmethode (Clustering) zu verbessern. Bildmaskierung ist eine Bildverarbeitungstechnik, die verwendet wird, um den Hintergrund von den Vordergrundbildobjekten zu trennen.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

    // Vorschlag Nr. 1.
    // Analysieren Sie das Bild visuell und legen Sie den Interessenbereich fest. Das Ergebnis der Segmentierung enthält nur Objekte, die sich vollständig in diesem Bereich befinden.
    args.ObjectsRectangles = new Rectangle[]
    {
        new Rectangle(86, 6, 270, 364),
    };

    // Vorschlag Nr. 2.
    // Analysieren Sie das Bild visuell und setzen Sie die Punkte, die zu getrennten Objekten gehören.
    args.ObjectsPoints = new Point[][]
    {
        new Point[] { new Point(103, 326) },
        new Point[] { new Point(280, 43) },
        new Point[] { new Point(319, 86) },
    };

    // Jeder Cluster (Segment) wird in einer separaten PNG-Datei gespeichert.
    Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
    exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
        
    // GraphCut-Clustering verwenden.
    maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
    maskingOptions.Decompose = false;
    maskingOptions.Args = args;

    // Die Hintergrundfarbe ist orange.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // Erstellen Sie eine Instanz der ImageMasking-Klasse.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Teilen Sie das Quellbild in mehrere Cluster (Segmente).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Bilder aus dem Maskierungsergebnis abrufen und als PNG speichern.
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

### Siehe auch

* class [MaskingResult](../../maskingresult)
* namensraum [Aspose.Imaging.Masking.Result](../../maskingresult)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
