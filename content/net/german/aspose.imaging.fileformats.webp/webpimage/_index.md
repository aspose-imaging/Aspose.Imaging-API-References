---
title: WebPImage
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ein Webp-Bild.
type: docs
weight: 8080
url: /de/aspose.imaging.fileformats.webp/webpimage/
---
## WebPImage class

Ein Webp-Bild.

```csharp
public sealed class WebPImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [WebPImage](webpimage#constructor)(RasterImage) | Initialisiert eine neue Instanz von[`WebPImage`](../webpimage) Klasse von rasterImage. |
| [WebPImage](webpimage#constructor_4)(Stream) | Initialisiert eine neue Instanz von[`WebPImage`](../webpimage) class aus stream. |
| [WebPImage](webpimage#constructor_6)(string) | Initialisiert eine neue Instanz von[`WebPImage`](../webpimage) Klasse aus Datei. |
| [WebPImage](webpimage#constructor_1)(RasterImage, LoadOptions) | Initialisiert eine neue Instanz von[`WebPImage`](../webpimage) Klasse von rasterImage. |
| [WebPImage](webpimage#constructor_5)(Stream, LoadOptions) | Initialisiert eine neue Instanz von[`WebPImage`](../webpimage) Klasse aus stream. |
| [WebPImage](webpimage#constructor_7)(string, LoadOptions) | Initialisiert eine neue Instanz von[`WebPImage`](../webpimage) Klasse aus Datei. |
| [WebPImage](webpimage#constructor_2)(int, int, WebPOptions) | Initialisiert eine neue Instanz von[`WebPImage`](../webpimage) Klasse mit leerem Bild. |
| [WebPImage](webpimage#constructor_3)(int, int, WebPOptions, LoadOptions) | Initialisiert eine neue Instanz von[`WebPImage`](../webpimage) Klasse mit leerem Bild. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Palette automatisch angepasst wird. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor) { get; set; } | Ruft einen Wert für die Hintergrundfarbe ab oder legt ihn fest. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | Ruft die Anzahl der Bildbits pro Pixel ab. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Ruft die Bildgrenzen ab. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [Container](../../aspose.imaging/image/container) { get; } | Ruft die ab[`Image`](../../aspose.imaging/image) Container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Ruft den Datenstrom des Objekts ab. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| override [FileFormat](../../aspose.imaging.fileformats.webp/webpimage/fileformat) { get; } | Ruft einen Wert von Dateiformat ab |
| override [HasAlpha](../../aspose.imaging.fileformats.webp/webpimage/hasalpha) { get; } | Ruft den Has-Alphakanal ab. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor) { get; } | Ruft einen Wert ab, der angibt, ob das Bild eine transparente Farbe hat. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | Ruft die Bildhöhe ab. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Ermittelt oder setzt die horizontale Auflösung davon in Pixel pro Zoll[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity) { get; } | Ruft die Deckkraft dieses Bildes ab. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Holt oder setzt den Interrupt-Monitor. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | Ruft einen Wert ab, der angibt, ob Bilddaten derzeit zwischengespeichert werden. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Ruft einen Wert ab, der angibt, ob das Laden von Rohdaten verfügbar ist. |
| [Options](../../aspose.imaging.fileformats.webp/webpimage/options) { get; } | Ruft die Optionen ab oder legt sie fest. |
| override [PageCount](../../aspose.imaging.fileformats.webp/webpimage/pagecount) { get; } | Ruft die Seitenanzahl ab. |
| override [PageExportingAction](../../aspose.imaging.fileformats.webp/webpimage/pageexportingaction) { get; set; } | Ruft die Aktion zum Exportieren der Seite ab oder legt sie fest. Bitte beachten Sie, dass das Festlegen dieser Methode automatisch Seitenressourcen freigibt, nachdem sie ausgeführt wurde. Sie wird unmittelbar vor dem Speichern jeder Seite ausgeführt. |
| override [Pages](../../aspose.imaging.fileformats.webp/webpimage/pages) { get; } | Holt die Blöcke. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Bildkomponenten vormultipliziert werden müssen. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Ruft den benutzerdefinierten Farbkonverter ab oder legt ihn fest |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | Ruft das Rohdatenformat ab. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Ruft die aktuellen Rohdateneinstellungen ab. Beachten Sie, dass bei Verwendung dieser Einstellungen die Daten ohne Konvertierung geladen werden. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Ruft den Fallback-Index ab oder legt ihn fest, der verwendet werden soll, wenn der Palettenindex außerhalb der Grenzen liegt |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Holt oder setzt den indizierten Farbkonverter |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Ruft die rohe Zeilengröße in Bytes ab. |
| [Size](../../aspose.imaging/image/size) { get; } | Ruft die Bildgröße ab. |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor) { get; set; } | Ruft die transparente Farbe des Bildes ab. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die XMP-Metadaten aktualisiert werden sollen. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Ruft einen Wert ab, der angibt, ob die Bildpalette verwendet wird. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob das Laden von Rohdaten verwendet werden soll, wenn das Laden von Rohdaten verfügbar ist. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | Ermittelt oder setzt die vertikale Auflösung davon in Pixel pro Zoll[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width) { get; } | Ruft die Bildbreite ab. |
| override [XmpData](../../aspose.imaging/rastercachedmultipageimage/xmpdata) { get; set; } | Ruft XMP-Daten vom Frame ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddBlock](../../aspose.imaging.fileformats.webp/webpimage/addblock)(IFrame) | Fügt einen neuen Webp-Block hinzu. |
| [AddPage](../../aspose.imaging.fileformats.webp/webpimage/addpage)(RasterImage) | Fügt dem Bild eine Seite hinzu. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.webp/webpimage/adjustbrightness)(int) | Anpassen von a*brightness* für Bild. |
| override [AdjustContrast](../../aspose.imaging.fileformats.webp/webpimage/adjustcontrast)(float) | [`Image`](../../aspose.imaging/image) kontrastierend |
| override [AdjustGamma](../../aspose.imaging.fileformats.webp/webpimage/adjustgamma#adjustgamma)(float) | Gamma-Korrektur eines Bildes. |
| override [AdjustGamma](../../aspose.imaging.fileformats.webp/webpimage/adjustgamma#adjustgamma_1)(float, float, float) | Gamma-Korrektur eines Bildes. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung des integralen Bildschwellenwerts |
| override [BinarizeBradley](../../aspose.imaging.fileformats.webp/webpimage/binarizebradley#binarizebradley_1)(double, int) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung des integralen Bildschwellenwerts |
| override [BinarizeFixed](../../aspose.imaging.fileformats.webp/webpimage/binarizefixed)(byte) | Binarisierung eines Bildes mit vordefiniertem Schwellwert |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.webp/webpimage/binarizeotsu)() | Binarisierung eines Bildes mit Otsu-Thresholding |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata)() | Speichert die Daten privat. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Legt fest, ob das Bild in dem angegebenen Dateiformat gespeichert werden kann, das durch die übergebenen Speicheroptionen repräsentiert wird. |
| [ClearBlocks](../../aspose.imaging.fileformats.webp/webpimage/clearblocks)() | Löscht alle Webp-Blöcke. |
| override [Crop](../../aspose.imaging.fileformats.webp/webpimage/crop#crop)(Rectangle) | Bild zuschneiden. |
| override [Crop](../../aspose.imaging.fileformats.webp/webpimage/crop#crop_1)(int, int, int, int) | Bild mit Verschiebungen zuschneiden. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Führt Dithering auf dem aktuellen Bild durch. |
| override [Dither](../../aspose.imaging.fileformats.webp/webpimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | Führt Dithering auf dem aktuellen Bild durch. |
| override [Filter](../../aspose.imaging.fileformats.webp/webpimage/filter)(Rectangle, FilterOptionsBase) | Filtert das angegebene Rechteck. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Ruft ein 32-Bit-ARGB-Pixelbild ab. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Ruft das standardmäßige 32-Bit-ARGB-Pixel-Array ab. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Ruft die Standardoptionen ab. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Ruft das Standard-Pixel-Array mit partiellem Pixel-Loader ab. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Ruft das Standard-Rohdatenarray ab. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Ruft das Standard-Rohdaten-Array mit partiellem Pixel-Loader ab. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Ruft das Datum und die Uhrzeit ab, zu der das Ressourcenbild zuletzt geändert wurde. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Ruft die Optionen basierend auf den ursprünglichen Dateieinstellungen ab. Dies kann hilfreich sein, um die Bittiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz-weißes PNG-Bild mit 1 Bit pro Pixel laden und dann Speichern Sie es mit the [`Save`](../../aspose.imaging/datastreamsupporter/save) -Methode wird das ausgegebene PNG-Bild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und das PNG-Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um entsprechende Speicheroptionen zu erhalten, und übergeben Sie sie an die[`Save`](../../aspose.imaging/image/save) Methode als zweiten Parameter. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Ruft ein Bildpixel ab. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Ruft den Schräglaufwinkel ab. Diese Methode ist auf gescannte Textdokumente anwendbar, um den Schräglaufwinkel beim Scannen zu bestimmen. |
| override [Grayscale](../../aspose.imaging.fileformats.webp/webpimage/grayscale)() | Transformation eines Bildes in seine Graustufendarstellung |
| [InsertBlock](../../aspose.imaging.fileformats.webp/webpimage/insertblock)(int, IFrame) | Fügt einen neuen Webp-Block hinzu. |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | Lädt 32-Bit-ARGB-Pixel. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | Lädt 64-Bit-ARGB-Pixel. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | Lädt Pixel im CMYK-Format. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Lädt 32-Bit-ARGB-Pixel teilweise nach Paketen. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Lädt Pixel teilweise nach Paketen. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | Lädt Pixel. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Lädt Rohdaten. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Lädt Rohdaten. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | Normalisiert den Winkel. Diese Methode ist auf gescannte Textdokumente anwendbar, um den schiefen Scan zu beseitigen. Diese Methode verwendet[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) und[`Rotate`](../../aspose.imaging/rasterimage/rotate) Methoden. |
| override [NormalizeAngle](../../aspose.imaging/rastercachedmultipageimage/normalizeangle)(bool, Color) | Normalisiert den Winkel. Diese Methode ist auf gescannte Textdokumente anwendbar, um den schiefen Scan zu beseitigen. Diese Methode verwendet!:GetSkewAngle und[`Rotate`](../../aspose.imaging/rastercachedmultipageimage/rotate) Methoden. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Liest die gesamte Scanzeile mit dem angegebenen Scanzeilenindex. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Liest die gesamte Scanzeile mit dem angegebenen Scanzeilenindex. |
| [RemoveBlock](../../aspose.imaging.fileformats.webp/webpimage/removeblock)(IFrame) | Entfernt den Webp-Block. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Ersetzt eine Farbe durch eine andere mit zulässigem Unterschied und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | Ersetzt eine Farbe durch eine andere mit zulässigem Unterschied und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Ersetzt alle nicht transparenten Farben durch neue Farben und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. Hinweis: Wenn Sie es auf Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | Ersetzt alle nicht transparenten Farben durch neue Farben und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. Hinweis: Wenn Sie es auf Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Ändert die Bildgröße. Der StandardNearestNeighbourResample wird verwendet. |
| override [Resize](../../aspose.imaging.fileformats.webp/webpimage/resize#resize_1)(int, int, ImageResizeSettings) | Ändert die Bildgröße. |
| override [Resize](../../aspose.imaging.fileformats.webp/webpimage/resize#resize_2)(int, int, ResizeType) | Ändert die Bildgröße. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Ändert die Höhe proportional. Der StandardNearestNeighbourResample wird verwendet. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Ändert die Höhe proportional. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.webp/webpimage/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Ändert die Breite proportional. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Ändert die Breite proportional. Der StandardNearestNeighbourResample wird verwendet. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Ändert die Breite proportional. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.webp/webpimage/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Ändert die Breite proportional. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Bild um die Mitte drehen. |
| override [Rotate](../../aspose.imaging.fileformats.webp/webpimage/rotate#rotate_1)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate Bild um die Mitte. |
| override [RotateFlip](../../aspose.imaging.fileformats.webp/webpimage/rotateflip)(RotateFlipType) | Rotiert, kippt oder dreht und kippt nur den aktiven Rahmen. |
| [Save](../../aspose.imaging/image/save)() | Speichert die Bilddaten im zugrunde liegenden Stream. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Speichert die Daten des Objekts im angegebenen Stream. |
| override [Save](../../aspose.imaging/image/save)(string) | Speichert das Bild am angegebenen Dateispeicherort. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Speichert die Bilddaten gemäß den Speicheroptionen im angegebenen Stream im angegebenen Dateiformat. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Speichert die Daten des Objekts am angegebenen Dateispeicherort. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| override [Save](../../aspose.imaging/rasterimage/save)(Stream, ImageOptionsBase, Rectangle) | Speichert die Bilddaten gemäß den Speicheroptionen im angegebenen Stream im angegebenen Dateiformat. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [SaveArgb32Pixels](../../aspose.imaging/rasterimage/saveargb32pixels)(Rectangle, int[]) | Speichert die 32-Bit-ARGB-Pixel. |
| [SaveCmyk32Pixels](../../aspose.imaging/rasterimage/savecmyk32pixels)(Rectangle, int[]) | Speichert die Pixel. |
| [SavePixels](../../aspose.imaging/rasterimage/savepixels)(Rectangle, Color[]) | Speichert die Pixel. |
| [SaveRawData](../../aspose.imaging/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | Speichert die Rohdaten. |
| [SetArgb32Pixel](../../aspose.imaging/rasterimage/setargb32pixel)(int, int, int) | Legt ein 32-Bit-ARGB-Bildpixel für die angegebene Position fest. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | Legt die Bildpalette fest. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | Setzt ein Bildpixel für die angegebene Position. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | Legt die Auflösung dafür fest[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Konvertiert Rasterbild in Bitmap. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Schreibt die gesamte Scanzeile in den angegebenen Scanzeilenindex. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Schreibt die gesamte Scanzeile in den angegebenen Scanzeilenindex. |

### Beispiele

Dieses Beispiel zeigt, wie ein WebP-Bild aus einer Datei geladen und im PNG-Format gespeichert wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein WebP-Bild aus einer Datei.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(dir + "test.webp"))
{
    // Als PNG speichern
    // Beachten Sie, dass nur der aktive Frame in PNG gespeichert wird, da PNG kein mehrseitiges Format ist.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Siehe auch

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* namensraum [Aspose.Imaging.FileFormats.Webp](../../aspose.imaging.fileformats.webp)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
