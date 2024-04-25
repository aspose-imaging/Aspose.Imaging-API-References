---
title: Jpeg2000Options
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die Jpeg2000-Dateiformatoptionen.
type: docs
weight: 10020
url: /de/aspose.imaging.imageoptions/jpeg2000options/
---
## Jpeg2000Options class

Die Jpeg2000-Dateiformatoptionen.

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Jpeg2000Options](jpeg2000options#constructor)() | Initialisiert eine neue Instanz von[`Jpeg2000Options`](../jpeg2000options) Klasse. |
| [Jpeg2000Options](jpeg2000options#constructor_1)(Jpeg2000Options) | Initialisiert eine neue Instanz von[`Jpeg2000Options`](../jpeg2000options) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [Codec](../../aspose.imaging.imageoptions/jpeg2000options/codec) { get; set; } | Holt oder setzt den JPEG2000-Codec |
| [Comments](../../aspose.imaging.imageoptions/jpeg2000options/comments) { get; set; } | Ruft die Jpeg-Kommentarmarkierungen ab oder setzt sie. |
| [CompressionRatios](../../aspose.imaging.imageoptions/jpeg2000options/compressionratios) { get; set; } | Ruft das Komprimierungsverhältnis des Arrays ab oder legt es fest. Unterschiedliche Komprimierungsverhältnisse für aufeinanderfolgende Schichten. Die für jede Qualitätsstufe angegebene Rate ist der gewünschte Komprimierungsfaktor. Verringern der Verhältnisse erforderlich. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Vollbild]. |
| [Irreversible](../../aspose.imaging.imageoptions/jpeg2000options/irreversible) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die irreversible DWT 9-7-Komprimierung (true) oder die verlustfreie DWT 5-3-Komprimierung (Standard) verwendet wird. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Die mehrseitigen Optionen |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Ruft den Fortschrittsereignishandler ab oder legt ihn fest. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Ruft die Quelle zum Erstellen des Bildes ab oder legt sie fest. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ruft die Optionen für die Vektorrasterung ab oder legt sie fest. |
| override [XmpData](../../aspose.imaging.imageoptions/jpeg2000options/xmpdata) { get; set; } | Ruft den XMP-Metadatencontainer ab oder legt ihn fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Klont diese Instanz. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |

### Beispiele

Das folgende Beispiel zeigt, wie Sie ein mehrseitiges Vektorbild auf allgemeine Weise in das JPEG 2000-Format konvertieren, ohne auf einen bestimmten Bildtyp zu verweisen.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.j2k");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Nur die ersten beiden Seiten exportieren. Tatsächlich wird nur eine Seite gerastert, da JPEG 2000 kein mehrseitiges Format ist.
    Aspose.Imaging.IMultipageImage multipageImage = image as Aspose.Imaging.IMultipageImage;
    if (multipageImage != null && (multipageImage.Pages != null && multipageImage.PageCount > 2))
    {
        exportOptions.MultiPageOptions = new Aspose.Imaging.ImageOptions.MultiPageOptions(new Aspose.Imaging.IntRange(0, 2));
    }

    if (image is Aspose.Imaging.VectorImage)
    {
        exportOptions.VectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Aspose.Imaging.Color.White, image.Width, image.Height });
        exportOptions.VectorRasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel;
        exportOptions.VectorRasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.None;
    }

    image.Save(outputFilePath, exportOptions);
}
```

### Siehe auch

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* namensraum [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
