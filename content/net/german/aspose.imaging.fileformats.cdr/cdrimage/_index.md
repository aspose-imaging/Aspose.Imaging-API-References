---
title: CdrImage
second_title: Aspose.Imaging für .NET-API-Referenz
description: Das Cdr-Image.
type: docs
weight: 1420
url: /de/aspose.imaging.fileformats.cdr/cdrimage/
---
## CdrImage class

Das Cdr-Image.

```csharp
public class CdrImage : VectorMultipageImage, ICdrImage
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [CdrImage](cdrimage)(Stream, LoadOptions) | Initialisiert eine neue Instanz von[`CdrImage`](../cdrimage) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Palette automatisch angepasst wird. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Ruft einen Wert für die Hintergrundfarbe ab oder legt ihn fest. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.cdr/cdrimage/bitsperpixel) { get; } | Ruft die Anzahl der Bildbits pro Pixel ab. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Ruft die Bildgrenzen ab. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [CdrDocument](../../aspose.imaging.fileformats.cdr/cdrimage/cdrdocument) { get; } | Ruft das CDR-Dokument ab oder legt es fest. |
| [Container](../../aspose.imaging/image/container) { get; } | Ruft die ab[`Image`](../../aspose.imaging/image) Container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Ruft den Datenstrom des Objekts ab. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| override [FileFormat](../../aspose.imaging.fileformats.cdr/cdrimage/fileformat) { get; } | Ruft einen Wert von Dateiformat ab |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| override [Height](../../aspose.imaging.fileformats.cdr/cdrimage/height) { get; } | Ruft die Bildhöhe ab. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Ruft die Objekthöhe in Zoll ab. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Holt oder setzt den Interrupt-Monitor. |
| override [IsCached](../../aspose.imaging.fileformats.cdr/cdrimage/iscached) { get; } | Ruft einen Wert ab, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist. |
| override [PageCount](../../aspose.imaging.fileformats.cdr/cdrimage/pagecount) { get; } | Ruft die Seitenanzahl ab oder legt sie fest. |
| override [PageExportingAction](../../aspose.imaging.fileformats.cdr/cdrimage/pageexportingaction) { get; set; } | Ruft die Aktion zum Exportieren der Seite ab oder legt sie fest. Bitte beachten Sie, dass das Festlegen dieser Methode automatisch Seitenressourcen freigibt, nachdem sie ausgeführt wurde. Sie wird unmittelbar vor dem Speichern jeder Seite ausgeführt. |
| override [Pages](../../aspose.imaging.fileformats.cdr/cdrimage/pages) { get; } | Ruft die Seiten ab. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| [Size](../../aspose.imaging/image/size) { get; } | Ruft die Bildgröße ab. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Ruft die Objektgröße in Zoll ab. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Ruft einen Wert ab, der angibt, ob die Bildpalette verwendet wird. |
| override [Width](../../aspose.imaging.fileformats.cdr/cdrimage/width) { get; } | Ruft die Bildbreite ab. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Ruft die Objektbreite in Zoll ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.cdr/cdrimage/cachedata)() | Cachet die Daten und stellt sicher, dass kein zusätzliches Laden von Daten aus dem zugrunde liegenden durchgeführt wird[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Legt fest, ob das Bild in dem angegebenen Dateiformat gespeichert werden kann, das durch die übergebenen Speicheroptionen repräsentiert wird. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.cdr/cdrimage/getdefaultoptions)(object[]) | Ruft die Standardoptionen ab. |
| override [GetEmbeddedImages](../../aspose.imaging/vectormultipageimage/getembeddedimages)() | Ruft die eingebetteten Bilder ab. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Ruft die Optionen basierend auf den ursprünglichen Dateieinstellungen ab. Dies kann hilfreich sein, um die Bittiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz-weißes PNG-Bild mit 1 Bit pro Pixel laden und dann Speichern Sie es mit the [`Save`](../../aspose.imaging/datastreamsupporter/save) -Methode wird das ausgegebene PNG-Bild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und das PNG-Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um entsprechende Speicheroptionen zu erhalten, und übergeben Sie sie an die[`Save`](../../aspose.imaging/image/save) Methode als zweiten Parameter. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Ändert die Bildgröße. Der StandardNearestNeighbourResample wird verwendet. |
| override [Resize](../../aspose.imaging.fileformats.cdr/cdrimage/resize#resize_1)(int, int, ImageResizeSettings) | Ändert die Bildgröße. |
| override [Resize](../../aspose.imaging.fileformats.cdr/cdrimage/resize#resize_2)(int, int, ResizeType) | Ändert die Bildgröße. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Ändert die Höhe proportional. Der StandardNearestNeighbourResample wird verwendet. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Ändert die Höhe proportional. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Ändert die Höhe proportional. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Ändert die Breite proportional. Der StandardNearestNeighbourResample wird verwendet. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Ändert die Breite proportional. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Ändert die Breite proportional. |
| override [RotateFlip](../../aspose.imaging.fileformats.cdr/cdrimage/rotateflip)(RotateFlipType) | Dreht, kippt oder dreht und kippt das Bild. |
| [Save](../../aspose.imaging/image/save)() | Speichert die Bilddaten im zugrunde liegenden Stream. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Speichert die Daten des Objekts im angegebenen Stream. |
| override [Save](../../aspose.imaging/image/save)(string) | Speichert das Bild am angegebenen Dateispeicherort. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Speichert die Bilddaten gemäß den Speicheroptionen im angegebenen Stream im angegebenen Dateiformat. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Speichert die Daten des Objekts am angegebenen Dateispeicherort. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Speichert die Bilddaten gemäß den Speicheroptionen im angegebenen Stream im angegebenen Dateiformat. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| override [SetPalette](../../aspose.imaging.fileformats.cdr/cdrimage/setpalette)(IColorPalette, bool) | Legt die Bildpalette fest. |

### Beispiele

Das folgende Beispiel zeigt, wie alle Seiten eines CDR-Image zwischengespeichert werden.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein Bild aus einer CDR-Datei.
using (Aspose.Imaging.FileFormats.Cdr.CdrImage image = (Aspose.Imaging.FileFormats.Cdr.CdrImage)Aspose.Imaging.Image.Load(dir + "sample.cdr"))
{
    // Dieser Aufruf speichert nur die Standardseite.
    image.CacheData();

    // Alle Seiten zwischenspeichern, damit kein zusätzliches Laden von Daten aus dem zugrunde liegenden Datenstrom durchgeführt wird.
    foreach (Aspose.Imaging.FileFormats.Cdr.CdrImagePage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### Siehe auch

* class [Image](../../aspose.imaging/image)
* interface [ICdrImage](../icdrimage)
* class [VectorMultipageImage](../../aspose.imaging/vectormultipageimage)
* namensraum [Aspose.Imaging.FileFormats.Cdr](../../aspose.imaging.fileformats.cdr)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
