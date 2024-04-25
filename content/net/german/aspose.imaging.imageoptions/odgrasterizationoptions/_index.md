---
title: OdgRasterizationOptions
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die Odg-Rasterisierungsoptionen
type: docs
weight: 10080
url: /de/aspose.imaging.imageoptions/odgrasterizationoptions/
---
## OdgRasterizationOptions class

Die Odg-Rasterisierungsoptionen

```csharp
public class OdgRasterizationOptions : OdRasterizationOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [OdgRasterizationOptions](odgrasterizationoptions)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.imageoptions/vectorrasterizationoptions/backgroundcolor) { get; set; } | Ruft eine Hintergrundfarbe ab oder legt sie fest. |
| [BorderX](../../aspose.imaging.imageoptions/vectorrasterizationoptions/borderx) { get; set; } | Holt oder setzt den Rand X. |
| [BorderY](../../aspose.imaging.imageoptions/vectorrasterizationoptions/bordery) { get; set; } | Holt oder setzt den Rand Y. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [CenterDrawing](../../aspose.imaging.imageoptions/vectorrasterizationoptions/centerdrawing) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob das Zeichnen zentriert ist. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [DrawColor](../../aspose.imaging.imageoptions/vectorrasterizationoptions/drawcolor) { get; set; } | Ruft eine Vordergrundfarbe ab oder legt sie fest. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Vollbild]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Die mehrseitigen Optionen |
| [PageHeight](../../aspose.imaging.imageoptions/vectorrasterizationoptions/pageheight) { get; set; } | Ruft die Seitenhöhe ab oder legt sie fest. |
| [PageSize](../../aspose.imaging.imageoptions/vectorrasterizationoptions/pagesize) { get; set; } | Ruft die Seitengröße ab oder legt sie fest. |
| [PageWidth](../../aspose.imaging.imageoptions/vectorrasterizationoptions/pagewidth) { get; set; } | Ruft die Seitenbreite ab oder legt sie fest. |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. |
| [Positioning](../../aspose.imaging.imageoptions/vectorrasterizationoptions/positioning) { get; set; } | Holt oder setzt die Positionierung. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Ruft den Fortschrittsereignishandler ab oder legt ihn fest. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [SmoothingMode](../../aspose.imaging.imageoptions/vectorrasterizationoptions/smoothingmode) { get; set; } | Ruft den Glättungsmodus ab oder legt ihn fest. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Ruft die Quelle zum Erstellen des Bildes ab oder legt sie fest. |
| [TextRenderingHint](../../aspose.imaging.imageoptions/vectorrasterizationoptions/textrenderinghint) { get; set; } | Ruft den Textwiedergabehinweis ab oder legt ihn fest. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ruft die Optionen für die Vektorrasterung ab oder legt sie fest. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata) { get; set; } | Ruft den XMP-Metadatencontainer ab oder legt ihn fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Klont diese Instanz. |
| [CopyTo](../../aspose.imaging.imageoptions/vectorrasterizationoptions/copyto)(VectorRasterizationOptions) | Kopien nach. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |

### Beispiele

Das folgende Beispiel zeigt, wie Sie ein FODG-Bild (Flat XML ODF Template) in das PDF-Format exportieren.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3635";

string inputFileName = System.IO.Path.Combine(dir, "VariousObjectsMultiPage.fodg");
string outputFileName = inputFileName + ".pdf";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFileName))
{
    Aspose.Imaging.ImageOptions.OdgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.OdgRasterizationOptions();
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.White;
    rasterizationOptions.PageSize = image.Size;

    Aspose.Imaging.ImageOptions.PdfOptions saveOptions = new Aspose.Imaging.ImageOptions.PdfOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    image.Save(outputFileName, saveOptions);
}
```

### Siehe auch

* class [OdRasterizationOptions](../odrasterizationoptions)
* namensraum [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
