---
title: PageSize
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft die Seitengröße ab oder legt sie fest.
type: docs
weight: 80
url: /de/aspose.imaging.imageoptions/vectorrasterizationoptions/pagesize/
---
## VectorRasterizationOptions.PageSize property

Ruft die Seitengröße ab oder legt sie fest.

```csharp
public SizeF PageSize { get; set; }
```

### Beispiele

Dieses Beispiel zeigt, wie ein WMF-Bild aus einer Datei geladen und mit WmfRasterizationOptions in SVG konvertiert wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Die Verwendung von Aspose.Imaging.Image.Load ist eine einheitliche Methode zum Laden aller Arten von Bildern, einschließlich WMF.
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "test.wmf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();
        
    // Text wird in Formen umgewandelt.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.WmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions();

    // Die Hintergrundfarbe der Zeichenfläche.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // Die Seitengröße.
    rasterizationOptions.PageSize = wmfImage.Size;

    // Wenn eingebettetes emf existiert, dann emf rendern; andernfalls wmf rendern.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Wmf.WmfRenderMode.Auto;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    wmfImage.Save(dir + "test.output.svg", saveOptions);
}
```

Dieses Beispiel zeigt, wie ein EMF-Bild aus einer Datei geladen und mit EmfRasterizationOptions in SVG konvertiert wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Die Verwendung von Aspose.Imaging.Image.Load ist eine einheitliche Methode zum Laden aller Arten von Bildern, einschließlich EMF.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();

    // Text wird in Formen umgewandelt.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.EmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions();

    // Die Hintergrundfarbe der Zeichenfläche.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // Die Seitengröße.
    rasterizationOptions.PageSize = emfImage.Size;

    // Wenn eingebettetes emf existiert, dann emf rendern; andernfalls wmf rendern.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Emf.EmfRenderMode.Auto;

    // Legen Sie den horizontalen Rand fest
    rasterizationOptions.BorderX = 50;

    // Legen Sie den vertikalen Rand fest
    rasterizationOptions.BorderY = 50;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    emfImage.Save(dir + "test.output.svg", saveOptions);
}
```

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

* struct [SizeF](../../../aspose.imaging/sizef)
* class [VectorRasterizationOptions](../../vectorrasterizationoptions)
* namensraum [Aspose.Imaging.ImageOptions](../../vectorrasterizationoptions)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
