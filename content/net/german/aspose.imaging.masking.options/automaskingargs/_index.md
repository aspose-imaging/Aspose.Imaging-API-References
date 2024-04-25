---
title: AutoMaskingArgs
second_title: Aspose.Imaging für .NET-API-Referenz
description: Stellt die Argumente dar die für automatische Maskierungsmethoden angegeben werden
type: docs
weight: 10450
url: /de/aspose.imaging.masking.options/automaskingargs/
---
## AutoMaskingArgs class

Stellt die Argumente dar, die für automatische Maskierungsmethoden angegeben werden

```csharp
public class AutoMaskingArgs : IMaskingArgs
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [AutoMaskingArgs](automaskingargs)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [MaxIterationNumber](../../aspose.imaging.masking.options/automaskingargs/maxiterationnumber) { get; set; } | Ruft die maximale Anzahl von Iterationen ab oder legt sie fest. |
| [NumberOfObjects](../../aspose.imaging.masking.options/automaskingargs/numberofobjects) { get; set; } | Ruft die Anzahl der Objekte ab oder legt sie fest, um das Anfangsbild zu trennen (optional), der Standardwert ist 2 (Objekt und Hintergrund). |
| [ObjectsPoints](../../aspose.imaging.masking.options/automaskingargs/objectspoints) { get; set; } | Ermittelt oder setzt die Punkte, die zu getrennten Objekten gehören (optional) NumberOfObjects-Koordinaten, die zu NumberOfObjects-Objekten des Anfangsbilds gehören. Dieser Parameter wird verwendet, um die Genauigkeit der Segmentierungsmethode zu erhöhen. |
| [ObjectsRectangles](../../aspose.imaging.masking.options/automaskingargs/objectsrectangles) { get; set; } | Ruft die Objektrechtecke ab oder legt sie fest, die zu getrennten Objekten gehören (optional). Dieser Parameter wird verwendet, um die Genauigkeit der Segmentierungsmethoden zu erhöhen. |
| [OrphanedPoints](../../aspose.imaging.masking.options/automaskingargs/orphanedpoints) { get; set; } | Holt oder setzt die Punkte, die zu keinem Objekt mehr gehören (optional). Dieser Parameter wird nur im Falle einer Neusegmentierung verwendet. |
| [Precision](../../aspose.imaging.masking.options/automaskingargs/precision) { get; set; } | Ruft die Genauigkeit der Segmentierungsmethode ab oder legt sie fest (optional). |

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

Verwenden einer Segmentmaske, um den Segmentierungsprozess zu beschleunigen

```csharp
[C#]

// Exportoptionen maskieren
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// GraphCut-Clustering verwenden.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// Die Hintergrundfarbe wird transparent sein.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Transparent;
maskingOptions.ExportOptions = exportOptions;

string dir = "c:\\temp\\";
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
{
    Aspose.Imaging.Size imageSize = image.Size;

    // Reduzieren der Bildgröße, um den Segmentierungsprozess zu beschleunigen
    image.ResizeHeightProportionally(600, Aspose.Imaging.ResizeType.HighQualityResample);

    // Erstellen Sie eine Instanz der ImageMasking-Klasse.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Teilen Sie das Quellbild in mehrere Cluster (Segmente).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Erhalte die Vordergrundmaske
        using (Aspose.Imaging.RasterImage foregroundMask = maskingResult[1].GetMask()) 
        {
            // Erhöhen Sie die Größe der Maske auf die Größe des Originalbildes
            foregroundMask.Resize(imageSize.Width, imageSize.Height, Aspose.Imaging.ResizeType.NearestNeighbourResample);

            // Anwenden der Maske auf das Originalbild, um ein Vordergrundsegment zu erhalten
            using (Aspose.Imaging.RasterImage originImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
            {
                Aspose.Imaging.Masking.ImageMasking.ApplyMask(originImage, foregroundMask, maskingOptions);
                originImage.Save(dir + "BigImage_foreground.png", exportOptions);
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

Speichern der Maskierungssitzung in einer Datei für lange Sitzungen sowie für die Möglichkeit, die Sitzung in einer anderen Umgebung fortzusetzen.

```csharp
[C#]

string dir = "c:\\temp\\";
string sessionBackupFile = dir + "session.bak";

// Exportoptionen maskieren
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// GraphCut-Clustering verwenden.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// Die Hintergrundfarbe ist orange.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
maskingOptions.ExportOptions = exportOptions;

// Zum ersten Mal eine Sitzung starten und in eine Datei speichern
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // Erstellen Sie eine Instanz der ImageMasking-Klasse.
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

// Fortsetzen einer Maskierungssitzung aus einer Datei
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // Erstellen Sie eine Instanz der ImageMasking-Klasse.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    using (Aspose.Imaging.Masking.IMaskingSession session = masking.LoadSession(sessionBackupFile))
    {
        Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

        // Analysieren Sie das Bild visuell und setzen Sie die Punkte, die zu getrennten Objekten gehören.
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
            // Explizite Übergabe von Exportoptionen, da nicht serialisierbar
            maskingResult.MaskingOptions.ExportOptions = exportOptions;

            using (Aspose.Imaging.RasterImage segmentImage = maskingResult[1].GetImage())
            {
                segmentImage.Save(dir + "step2.png");
            }
        }
    }
}
```

### Siehe auch

* interface [IMaskingArgs](../imaskingargs)
* namensraum [Aspose.Imaging.Masking.Options](../../aspose.imaging.masking.options)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
