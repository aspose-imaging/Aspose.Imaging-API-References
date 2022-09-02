---
title: ImageMasking
second_title: Aspose.Imaging für .NET-API-Referenz
description: Bietet Bildmaskierungsvorgänge
type: docs
weight: 10430
url: /de/net/aspose.imaging.masking/imagemasking/
---
## ImageMasking class

Bietet Bildmaskierungsvorgänge

```csharp
public class ImageMasking
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ImageMasking](imagemasking)(RasterImage) | Initialisiert eine neue Instanz von[`ImageMasking`](../imagemasking) Klasse. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CreateSession](../../aspose.imaging.masking/imagemasking/createsession)(MaskingOptions) | Erstellt die Maskierungssitzung, die Retraining-Zerlegungsvorgänge ausführen kann. |
| [Decompose](../../aspose.imaging.masking/imagemasking/decompose)(MaskingOptions) | Führt den Zerlegungsvorgang mit angegebenen Maskierungsoptionen durch |
| [DecomposeAsync](../../aspose.imaging.masking/imagemasking/decomposeasync)(MaskingOptions) | Erstellt die asynchrone Dekompositionstask unter Verwendung angegebener Maskierungsoptionen. |
| [LoadSession](../../aspose.imaging.masking/imagemasking/loadsession#loadsession)(Stream) | Laden Sie die Sitzung aus dem angegebenen Stream. |
| [LoadSession](../../aspose.imaging.masking/imagemasking/loadsession#loadsession_1)(string) | Laden Sie die Sitzung aus der angegebenen Datei. |
| static [ApplyMask](../../aspose.imaging.masking/imagemasking/applymask)(RasterImage, RasterImage, MaskingOptions) | Wendet die Maske auf das angegebene Quellbild an. |

### Beispiele

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

* namensraum [Aspose.Imaging.Masking](../../aspose.imaging.masking)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
