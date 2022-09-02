---
title: PsdOptions
second_title: Aspose.Imaging für .NET-API-Referenz
description: Optionen zum Erstellen des PSD-Dateiformats.
type: docs
weight: 10140
url: /de/net/aspose.imaging.imageoptions/psdoptions/
---
## PsdOptions class

Optionen zum Erstellen des PSD-Dateiformats.

```csharp
public class PsdOptions : ImageOptionsBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PsdOptions](psdoptions#constructor)() | Initialisiert eine neue Instanz von[`PsdOptions`](../psdoptions) Klasse. |
| [PsdOptions](psdoptions#constructor_1)(PsdOptions) | Initialisiert eine neue Instanz von[`PsdOptions`](../psdoptions) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [ChannelBitsCount](../../aspose.imaging.imageoptions/psdoptions/channelbitscount) { get; set; } | Ruft die Anzahl der Bits pro Farbkanal ab oder setzt sie. |
| [ChannelsCount](../../aspose.imaging.imageoptions/psdoptions/channelscount) { get; set; } | Ruft die Anzahl der Farbkanäle ab oder legt sie fest. |
| [ColorMode](../../aspose.imaging.imageoptions/psdoptions/colormode) { get; set; } | Ruft den PSD-Farbmodus ab oder legt ihn fest. |
| [CompressionMethod](../../aspose.imaging.imageoptions/psdoptions/compressionmethod) { get; set; } | Ruft die psd-Komprimierungsmethode ab oder legt sie fest. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Vollbild]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Die mehrseitigen Optionen |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Ruft den Fortschrittsereignishandler ab oder legt ihn fest. |
| [PsdVersion](../../aspose.imaging.imageoptions/psdoptions/psdversion) { get; set; } | Ruft die Version des Dateiformats ab oder legt sie fest. Es kann PSD oder PSB sein. |
| [RefreshImagePreviewData](../../aspose.imaging.imageoptions/psdoptions/refreshimagepreviewdata) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Bildvorschaudaten aktualisieren] - Option, die verwendet wird, um die Kompatibilität mit anderen PSD-Bildbetrachtern zu maximieren. Bitte beachten Sie, dass das Zeichnen von Textebenen im endgültigen Layout für die Compact Framework-Plattform nicht unterstützt wird |
| [RemoveGlobalTextEngineResource](../../aspose.imaging.imageoptions/psdoptions/removeglobaltextengineresource) { get; set; } | Erhält oder setzt einen Wert, der angibt, ob - die globale Text-Engine-Ressource entfernt wird - nur für einige PSD-Dateien mit Textebenen verwendet wird, wenn sie nach der Verarbeitung nicht in Adobe Photoshop geöffnet werden können (hauptsächlich für Textebenen mit fehlenden Schriftarten). Nachdem Sie diese Option verwendet haben, müssen Sie als Nächstes die in Photoshop geöffnete Datei erstellen: Menü „Text“ -&gt; „Fehlende Schriftarten verarbeiten“. Nach diesem Vorgang wird der gesamte Text wieder angezeigt. Bitte beachten Sie, dass dieser Vorgang einige endgültige Layoutänderungen verursachen kann. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Ruft die Quelle zum Erstellen des Bildes ab oder legt sie fest. |
| [VectorizationOptions](../../aspose.imaging.imageoptions/psdoptions/vectorizationoptions) { get; set; } | Ruft die PSD-Vektorisierungsoptionen ab oder legt sie fest. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ruft die Optionen für die Vektorrasterung ab oder legt sie fest. |
| [Version](../../aspose.imaging.imageoptions/psdoptions/version) { get; set; } | Ruft die PSD-Dateiversion ab oder legt sie fest. |
| override [XmpData](../../aspose.imaging.imageoptions/psdoptions/xmpdata) { get; set; } | XMP-Datencontainer abrufen oder festlegen |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Klont diese Instanz. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |

### Beispiele

Dieses Beispiel zeigt die Verwendung von Aspsoe.Imaging für die .Net-API zum Konvertieren von Bildern in das PSD-Format. Um dieses Ziel zu erreichen, lädt dieses Beispiel ein vorhandenes Bild und speichert es dann wieder im PSD-Format.

```csharp
[C#]

string dir = "c:\\temp\\";

//Erzeugt eine Instanz der Bildklasse und initialisiert sie mit einer vorhandenen Datei über den Dateipfad
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //Eine Instanz der PsdOptions-Klasse erstellen
    Aspose.Imaging.ImageOptions.PsdOptions psdOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

    // Legen Sie die CompressionMethod als RLE fest
    //Hinweis: Andere unterstützte CompressionMethod ist CompressionMethod.RAW [Keine Komprimierung]
    psdOptions.CompressionMethod = Aspose.Imaging.FileFormats.Psd.CompressionMethod.RLE;

    // Setzen Sie den ColorMode auf GrayScale
    //Hinweis: Andere unterstützte ColorModes sind ColorModes.Bitmap und ColorModes.RGB
    psdOptions.ColorMode = Aspose.Imaging.FileFormats.Psd.ColorModes.Grayscale;

    //Speichern Sie das Bild mit den angegebenen PsdOptions-Einstellungen am Speicherort der Festplatte
    image.Save(dir + "output.psd", psdOptions);
}
```

Das folgende Beispiel zeigt, wie Sie ein mehrseitiges Vektorbild auf allgemeine Weise in das PSD-Format konvertieren, ohne auf einen bestimmten Bildtyp zu verweisen.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.psd");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Nur die ersten beiden Seiten exportieren. Diese Seiten werden in der Ausgabe-PSD als Ebenen dargestellt.
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
