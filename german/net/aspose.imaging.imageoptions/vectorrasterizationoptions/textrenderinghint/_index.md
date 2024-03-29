---
title: TextRenderingHint
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft den Textwiedergabehinweis ab oder legt ihn fest.
type: docs
weight: 120
url: /de/net/aspose.imaging.imageoptions/vectorrasterizationoptions/textrenderinghint/
---
## VectorRasterizationOptions.TextRenderingHint property

Ruft den Textwiedergabehinweis ab oder legt ihn fest.

```csharp
public TextRenderingHint TextRenderingHint { get; set; }
```

### Eigentumswert

Der Textwiedergabehinweis.

### Beispiele

Dieses Beispiel zeigt, wie Sie ein SVG-Bild aus einer Datei laden und es mit verschiedenen Optionen in PNG rastern.

```csharp
[C#]

string dir = "c:\\temp\\";

// Die Verwendung von Aspose.Imaging.Image.Load ist eine einheitliche Methode zum Laden von Bildern.
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = (Aspose.Imaging.FileFormats.Svg.SvgImage)Aspose.Imaging.Image.Load(dir + "test.svg"))
{
    // Um SVG zu rastern, müssen wir Rasterisierungsoptionen angeben.
    Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();

    // Legen Sie die Standardfarbe eines Hintergrunds für ein Bild fest. Der Standardwert ist weiß.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.Gray;

    // Legen Sie die Seitengröße fest
    rasterizationOptions.PageSize = svgImage.Size;

    // Antialiasing wird auf Linien und Kurven sowie die Kanten gefüllter Bereiche angewendet.
    rasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.AntiAlias;

    // Jedes Zeichen wird mit seiner geglätteten Glyphen-Bitmap ohne Hinting gezeichnet.
    rasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.AntiAlias;

    // Bildgröße 10-mal verkleinern, dh die Ausgabegröße beträgt 10 % der Originalgröße.
    rasterizationOptions.ScaleX = 0.1f;
    rasterizationOptions.ScaleY = 0.1f;

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    // Speichern in einer PNG-Datei
    svgImage.Save(dir + "test.output.png", saveOptions);
}
```

### Siehe auch

* enum [TextRenderingHint](../../../aspose.imaging/textrenderinghint)
* class [VectorRasterizationOptions](../../vectorrasterizationoptions)
* namensraum [Aspose.Imaging.ImageOptions](../../vectorrasterizationoptions)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
