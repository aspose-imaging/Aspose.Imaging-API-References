---
title: ManualMaskingArgs
second_title: Aspose.Imaging für .NET-API-Referenz
description: Stellt die Argumente dar die für die manuelle Maskierungsmethode angegeben sind
type: docs
weight: 10500
url: /de/net/aspose.imaging.masking.options/manualmaskingargs/
---
## ManualMaskingArgs class

Stellt die Argumente dar, die für die manuelle Maskierungsmethode angegeben sind

```csharp
public class ManualMaskingArgs : IMaskingArgs
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ManualMaskingArgs](manualmaskingargs)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Mask](../../aspose.imaging.masking.options/manualmaskingargs/mask) { get; set; } | Ruft den Satz grafischer Formen ab, die eine Maske bilden, oder legt ihn fest. |

### Beispiele

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

### Siehe auch

* interface [IMaskingArgs](../imaskingargs)
* namensraum [Aspose.Imaging.Masking.Options](../../aspose.imaging.masking.options)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->