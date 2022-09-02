---
title: EpsImage
second_title: Aspose.Imaging für .NET-API-Referenz
description: Basisklasse für EPS-Format
type: docs
weight: 6560
url: /de/net/aspose.imaging.fileformats.eps/epsimage/
---
## EpsImage class

Basisklasse für EPS-Format

```csharp
public abstract class EpsImage : VectorImage
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Palette automatisch angepasst wird. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Ruft einen Wert für die Hintergrundfarbe ab oder legt ihn fest. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.eps/epsimage/bitsperpixel) { get; } | Ruft die Anzahl der Bildbits pro Pixel ab. |
| [BoundingBoxBottomLeft](../../aspose.imaging.fileformats.eps/epsimage/boundingboxbottomleft) { get; } | Ruft die Position des Begrenzungsrahmens unten links ab |
| [BoundingBoxString](../../aspose.imaging.fileformats.eps/epsimage/boundingboxstring) { get; } | Ruft den BoundingBox-String-Wert ab |
| [BoundingBoxTopRight](../../aspose.imaging.fileformats.eps/epsimage/boundingboxtopright) { get; } | Ruft die Position des Begrenzungsrahmens oben rechts ab |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Ruft die Bildgrenzen ab. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [Container](../../aspose.imaging/image/container) { get; } | Ruft die ab[`Image`](../../aspose.imaging/image) Container. |
| [CreationDate](../../aspose.imaging.fileformats.eps/epsimage/creationdate) { get; } | Ruft das CreationDate-Feld ab |
| [CreationDateString](../../aspose.imaging.fileformats.eps/epsimage/creationdatestring) { get; } | Ruft den CreationDate-Feldstringwert ab |
| [Creator](../../aspose.imaging.fileformats.eps/epsimage/creator) { get; } | Ruft das Creator-Feld ab |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Ruft den Datenstrom des Objekts ab. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| abstract [EpsType](../../aspose.imaging.fileformats.eps/epsimage/epstype) { get; } | Ruft den Wert des EPS-Subtyps ab |
| override [FileFormat](../../aspose.imaging.fileformats.eps/epsimage/fileformat) { get; } | Ruft einen Wert von Dateiformat ab |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| abstract [HasRasterPreview](../../aspose.imaging.fileformats.eps/epsimage/hasrasterpreview) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz eine formatspezifische Rastervorschau hat |
| override [Height](../../aspose.imaging.fileformats.eps/epsimage/height) { get; } | Ruft die Bildhöhe ab. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Ruft die Objekthöhe in Zoll ab. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Holt oder setzt den Interrupt-Monitor. |
| override [IsCached](../../aspose.imaging.fileformats.eps/epsimage/iscached) { get; } | Ruft einen Wert ab, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist. |
| [PageNumber](../../aspose.imaging.fileformats.eps/epsimage/pagenumber) { get; } | Ruft die Seitennummer ab |
| [PagesCount](../../aspose.imaging.fileformats.eps/epsimage/pagescount) { get; } | Ruft die Seitenanzahl ab |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| [PhotoshopThumbnail](../../aspose.imaging.fileformats.eps/epsimage/photoshopthumbnail) { get; } | Ruft eine Miniaturansicht der Photoshop-Vorschau ab (falls in den ursprünglichen EPS-Daten vorhanden) |
| [PostScriptVersion](../../aspose.imaging.fileformats.eps/epsimage/postscriptversion) { get; } | Ruft die PostScript-Version ab field |
| [Size](../../aspose.imaging/image/size) { get; } | Ruft die Bildgröße ab. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Ruft die Objektgröße in Zoll ab. |
| [Title](../../aspose.imaging.fileformats.eps/epsimage/title) { get; } | Ruft das Titelfeld ab |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Ruft einen Wert ab, der angibt, ob die Bildpalette verwendet wird. |
| override [Width](../../aspose.imaging.fileformats.eps/epsimage/width) { get; } | Ruft die Bildbreite ab. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Ruft die Objektbreite in Zoll ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.eps/epsimage/cachedata)() | Cache kann nicht verwendet werden. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Legt fest, ob das Bild in dem angegebenen Dateiformat gespeichert werden kann, das durch die übergebenen Speicheroptionen repräsentiert wird. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.eps/epsimage/getdefaultoptions)(object[]) | Ruft die Standardoptionen ab. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages)() | Ruft die eingebetteten Bilder ab. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Ruft die Optionen basierend auf den ursprünglichen Dateieinstellungen ab. Dies kann hilfreich sein, um die Bittiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz-weißes PNG-Bild mit 1 Bit pro Pixel laden und dann Speichern Sie es mit the [`Save`](../../aspose.imaging/datastreamsupporter/save) -Methode wird das ausgegebene PNG-Bild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und das PNG-Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um entsprechende Speicheroptionen zu erhalten, und übergeben Sie sie an die[`Save`](../../aspose.imaging/image/save) Methode als zweiten Parameter. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Ändert die Bildgröße. Der StandardNearestNeighbourResample wird verwendet. |
| override [Resize](../../aspose.imaging.fileformats.eps/epsimage/resize#resize_1)(int, int, ImageResizeSettings) | Ändert die Bildgröße. |
| override [Resize](../../aspose.imaging.fileformats.eps/epsimage/resize#resize_2)(int, int, ResizeType) | Ändert die Bildgröße. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Ändert die Höhe proportional. Der StandardNearestNeighbourResample wird verwendet. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Ändert die Höhe proportional. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Ändert die Höhe proportional. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Ändert die Breite proportional. Der StandardNearestNeighbourResample wird verwendet. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Ändert die Breite proportional. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Ändert die Breite proportional. |
| override [RotateFlip](../../aspose.imaging.fileformats.eps/epsimage/rotateflip)(RotateFlipType) | Dreht, kippt oder dreht und kippt das Bild. |
| [Save](../../aspose.imaging/image/save)() | Speichert die Bilddaten im zugrunde liegenden Stream. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Speichert die Daten des Objekts im angegebenen Stream. |
| override [Save](../../aspose.imaging/image/save)(string) | Speichert das Bild am angegebenen Dateispeicherort. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Speichert die Bilddaten gemäß den Speicheroptionen im angegebenen Stream im angegebenen Dateiformat. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Speichert die Daten des Objekts am angegebenen Dateispeicherort. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Speichert die Bilddaten gemäß den Speicheroptionen im angegebenen Stream im angegebenen Dateiformat. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| override [SetPalette](../../aspose.imaging.fileformats.eps/epsimage/setpalette)(IColorPalette, bool) | Legt die Bildpalette fest. |

### Beispiele

Ändern Sie die Größe des EPS-Bildes und exportieren Sie es in das PNG-Format.

```csharp
[C#]

// EPS-Bild laden
using (var image = Image.Load("AstrixObelix.eps"))
{
    // Größe des Bildes mit der kubischen Interpolationsmethode von Mitchell ändern
    image.Resize(400, 400, ResizeType.Mitchell);

    // Bild ins PNG-Format exportieren
    image.Save("ExportResult.png", new PngOptions());
}
```

Konvertieren Sie EPS-Bilder mithilfe von PostScript-Rendering in PDF.

```csharp
[C#]

using (var image = (EpsImage)Image.Load("Sample.eps"))
{
    var options = new PdfOptions
    {
        PdfCoreOptions = new PdfCoreOptions
        {
            PdfCompliance = PdfComplianceVersion.PdfA1b // Erforderliche PDF-Compliance festlegen
        }
    };
  
    image.Save("Sample.pdf", options);
}
```

Konvertieren Sie EPS-Bilder mit PostScript-Rendering in PNG.

```csharp
[C#]

using (var image = (EpsImage)Image.Load("Sample.eps"))
{
    var options = new PngOptions
    {
        VectorRasterizationOptions = new EpsRasterizationOptions
        {
            PageWidth = 500, // Bild breite
            PageHeight = 500 // Bildhöhe
            PreviewToExport = EpsPreviewFormat.PostScriptRendering; // Rasterbild mit PostScript rendern
        }
    };

    image.Save("Sample.png", options);
}
```

Ändern Sie die Größe des EPS-Bildes mit erweiterten Einstellungen.

```csharp
[C#]

// EPS-Bild laden
using (var image = Image.Load("AstrixObelix.eps"))
{
    // Größe des Bildes mit erweiterten Größenanpassungseinstellungen ändern
    image.Resize(400, 400, new ImageResizeSettings
    {
        // Setze den Interpolationsmodus
        Mode = ResizeType.LanczosResample,

        // Legen Sie den Typ des Filters fest
        FilterType = ImageFilterType.SmallRectangular,

        // Legt die Farbvergleichsmethode fest
        ColorCompareMethod = ColorCompareMethod.Euclidian,

        // Legen Sie die Farbquantisierungsmethode fest
        ColorQuantizationMethod = ColorQuantizationMethod.Popularity
    });

    // Bild ins PNG-Format exportieren
    image.Save("ExportResult.png", new PngOptions());
}
```

### Siehe auch

* class [VectorImage](../../aspose.imaging/vectorimage)
* namensraum [Aspose.Imaging.FileFormats.Eps](../../aspose.imaging.fileformats.eps)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
