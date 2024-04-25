---
title: BmpOptions
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die Erstellungsoptionen für BMP-Dateiformate.
type: docs
weight: 9910
url: /de/aspose.imaging.imageoptions/bmpoptions/
---
## BmpOptions class

Die Erstellungsoptionen für BMP-Dateiformate.

```csharp
public class BmpOptions : ImageOptionsBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [BmpOptions](bmpoptions#constructor)() | Initialisiert eine neue Instanz von[`BmpOptions`](../bmpoptions) Klasse. |
| [BmpOptions](bmpoptions#constructor_1)(BmpOptions) | Initialisiert eine neue Instanz von[`BmpOptions`](../bmpoptions) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BitsPerPixel](../../aspose.imaging.imageoptions/bmpoptions/bitsperpixel) { get; set; } | Ruft die Anzahl der Bildbits pro Pixel ab oder legt sie fest. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [Compression](../../aspose.imaging.imageoptions/bmpoptions/compression) { get; set; } | Ruft die Komprimierung ab oder legt sie fest. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Vollbild]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Die mehrseitigen Optionen |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Ruft den Fortschrittsereignishandler ab oder legt ihn fest. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Ruft die Quelle zum Erstellen des Bildes ab oder legt sie fest. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ruft die Optionen für die Vektorrasterung ab oder legt sie fest. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata) { get; set; } | Ruft den XMP-Metadatencontainer ab oder legt ihn fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Klont diese Instanz. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |

### Beispiele

Dieses Beispiel erstellt eine neue Image-Datei an einem Speicherort auf dem Datenträger, wie von der Source-Eigenschaft der BmpOptions-Instanz angegeben. Mehrere Eigenschaften für die BmpOptions-Instanz werden festgelegt, bevor das eigentliche Bild erstellt wird. Insbesondere die Source-Eigenschaft, die sich in diesem Fall auf den tatsächlichen Speicherort der Festplatte bezieht.

```csharp
[C#]

//Eine Instanz von BmpOptions erstellen und ihre verschiedenen Eigenschaften festlegen
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Eine Instanz von FileCreateSource erstellen und als Quelle für die Instanz von BmpOptions zuweisen
//Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei Temporär ist oder nicht
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp", false);

//Erstellen Sie eine Instanz von Image und initialisieren Sie sie mit einer Instanz von BmpOptions, indem Sie die Create-Methode aufrufen
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    // Bildverarbeitung durchführen

    // Alle Änderungen speichern
    image.Save();
}
```

Dieses Beispiel demonstriert die Verwendung verschiedener Klassen aus dem SaveOptions-Namespace für Exportzwecke. Ein Bild vom Typ Gif wird in eine Instanz von Image geladen und dann in mehrere Formate exportiert.

```csharp
[C#]

string dir = "c:\\temp\\";

//Ein vorhandenes Bild (vom Typ Gif) in eine Instanz der Image-Klasse laden
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    //Export in das BMP-Dateiformat unter Verwendung der Standardoptionen
    image.Save(dir + "output.bmp", new Aspose.Imaging.ImageOptions.BmpOptions());

    // Mit den Standardoptionen in das JPEG-Dateiformat exportieren
    image.Save(dir + "output.jpg", new Aspose.Imaging.ImageOptions.JpegOptions());

    // Mit den Standardoptionen in das PNG-Dateiformat exportieren
    image.Save(dir + "output.png", new Aspose.Imaging.ImageOptions.PngOptions());

    // Mit den Standardoptionen in das TIFF-Dateiformat exportieren
    image.Save(dir + "output.tif", new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

Das folgende Beispiel zeigt, wie Sie ein mehrseitiges Vektorbild auf allgemeine Weise in das BMP-Format konvertieren, ohne auf einen bestimmten Bildtyp zu verweisen.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.bmp");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Nur die ersten beiden Seiten exportieren. Tatsächlich wird nur eine Seite gerastert, da BMP kein mehrseitiges Format ist.
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
