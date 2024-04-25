---
title: GifImage
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ein GIF-Bild.
type: docs
weight: 6700
url: /de/aspose.imaging.fileformats.gif/gifimage/
---
## GifImage class

Ein GIF-Bild.

```csharp
public sealed class GifImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [GifImage](gifimage#constructor)(GifFrameBlock) | Initialisiert eine neue Instanz von[`GifImage`](../gifimage) Klasse. |
| [GifImage](gifimage#constructor_1)(GifFrameBlock, IColorPalette) | Initialisiert eine neue Instanz von[`GifImage`](../gifimage) Klasse. |
| [GifImage](gifimage#constructor_2)(GifFrameBlock, IColorPalette, bool, byte, byte, byte, bool) | Initialisiert eine neue Instanz von[`GifImage`](../gifimage) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ActiveFrame](../../aspose.imaging.fileformats.gif/gifimage/activeframe) { get; set; } | Ruft den aktiven Frame ab oder setzt ihn. |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Palette automatisch angepasst wird. |
| override [BackgroundColor](../../aspose.imaging.fileformats.gif/gifimage/backgroundcolor) { get; set; } | Ruft die Hintergrundfarbe ab oder legt sie fest. |
| [BackgroundColorIndex](../../aspose.imaging.fileformats.gif/gifimage/backgroundcolorindex) { get; set; } | Ruft den Index der Hintergrundfarbe ab oder legt ihn fest. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | Ruft die Anzahl der Bildbits pro Pixel ab. |
| [Blocks](../../aspose.imaging.fileformats.gif/gifimage/blocks) { get; } | Ruft die GIF-Blöcke ab. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Ruft die Bildgrenzen ab. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [Container](../../aspose.imaging/image/container) { get; } | Ruft die ab[`Image`](../../aspose.imaging/image) Container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Ruft den Datenstrom des Objekts ab. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| override [FileFormat](../../aspose.imaging.fileformats.gif/gifimage/fileformat) { get; } | Ruft einen Wert von Dateiformat ab |
| override [HasAlpha](../../aspose.imaging/rastercachedmultipageimage/hasalpha) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz alpha hat. |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.gif/gifimage/hasbackgroundcolor) { get; } | Ruft einen Wert ab, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| [HasTrailer](../../aspose.imaging.fileformats.gif/gifimage/hastrailer) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob GIF einen Trailer hat. |
| override [HasTransparentColor](../../aspose.imaging.fileformats.gif/gifimage/hastransparentcolor) { get; set; } | Ruft einen Wert ab, der angibt, ob der aktive Rahmen eine transparente Farbe hat. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | Ruft die Bildhöhe ab. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Ermittelt oder setzt die horizontale Auflösung davon in Pixel pro Zoll[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [ImageOpacity](../../aspose.imaging.fileformats.gif/gifimage/imageopacity) { get; } | Ermittelt die Deckkraft dieses Bildes (aktiver Rahmen). |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Holt oder setzt den Interrupt-Monitor. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | Ruft einen Wert ab, der angibt, ob Bilddaten derzeit zwischengespeichert werden. |
| [IsInterlaced](../../aspose.imaging.fileformats.gif/gifimage/isinterlaced) { get; } | Ruft einen Wert ab, der angibt, ob diese Bildinstanz interlaced ist. |
| [IsPaletteSorted](../../aspose.imaging.fileformats.gif/gifimage/ispalettesorted) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Palette sortiert ist. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Ruft einen Wert ab, der angibt, ob das Laden von Rohdaten verfügbar ist. |
| [LoopsCount](../../aspose.imaging.fileformats.gif/gifimage/loopscount) { get; set; } | Ruft die Schleifenanzahl ab (wenn das gif-Bild Informationen über Schleifen enthält) |
| override [PageCount](../../aspose.imaging.fileformats.gif/gifimage/pagecount) { get; } | Ruft die Seitenanzahl ab. |
| override [PageExportingAction](../../aspose.imaging.fileformats.gif/gifimage/pageexportingaction) { get; set; } | Ruft die Aktion zum Exportieren der Seite ab oder legt sie fest. Bitte beachten Sie, dass das Festlegen dieser Methode automatisch Seitenressourcen freigibt, nachdem sie ausgeführt wurde. Sie wird unmittelbar vor dem Speichern jeder Seite ausgeführt. |
| override [Pages](../../aspose.imaging.fileformats.gif/gifimage/pages) { get; } | Ruft die Seiten ab. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| [PaletteColorResolutionBits](../../aspose.imaging.fileformats.gif/gifimage/palettecolorresolutionbits) { get; set; } | Ruft die Farbauflösungsbits der Palette ab oder setzt sie. |
| [PixelAspectRatio](../../aspose.imaging.fileformats.gif/gifimage/pixelaspectratio) { get; set; } | Ruft das Pixel-Seitenverhältnis ab oder legt es fest. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Bildkomponenten vormultipliziert werden müssen. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Ruft den benutzerdefinierten Farbkonverter ab oder legt ihn fest |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | Ruft das Rohdatenformat ab. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Ruft die aktuellen Rohdateneinstellungen ab. Beachten Sie, dass bei Verwendung dieser Einstellungen die Daten ohne Konvertierung geladen werden. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Ruft den Fallback-Index ab oder legt ihn fest, der verwendet werden soll, wenn der Palettenindex außerhalb der Grenzen liegt |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Holt oder setzt den indizierten Farbkonverter |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Ruft die rohe Zeilengröße in Bytes ab. |
| [Size](../../aspose.imaging/image/size) { get; } | Ruft die Bildgröße ab. |
| override [TransparentColor](../../aspose.imaging.fileformats.gif/gifimage/transparentcolor) { get; } | Ruft die transparente Farbe des aktiven Rahmens ab. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die XMP-Metadaten aktualisiert werden sollen. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Ruft einen Wert ab, der angibt, ob die Bildpalette verwendet wird. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob das Laden von Rohdaten verwendet werden soll, wenn das Laden von Rohdaten verfügbar ist. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | Ermittelt oder setzt die vertikale Auflösung davon in Pixel pro Zoll[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width) { get; } | Ruft die Bildbreite ab. |
| override [XmpData](../../aspose.imaging.fileformats.gif/gifimage/xmpdata) { get; set; } | Ruft die XMP-Metadaten ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddBlock](../../aspose.imaging.fileformats.gif/gifimage/addblock)(IGifBlock) | Fügt einen neuen GIF-Block hinzu. |
| [AddPage](../../aspose.imaging.fileformats.gif/gifimage/addpage)(RasterImage) | Fügt dem Bild eine Seite hinzu. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.gif/gifimage/adjustbrightness)(int) | Anpassen von a*brightness* für Bild. |
| override [AdjustContrast](../../aspose.imaging.fileformats.gif/gifimage/adjustcontrast)(float) | Passt den Kontrast an. |
| override [AdjustGamma](../../aspose.imaging.fileformats.gif/gifimage/adjustgamma#adjustgamma)(float) | Gamma-Korrektur eines Bildes. |
| override [AdjustGamma](../../aspose.imaging.fileformats.gif/gifimage/adjustgamma#adjustgamma_1)(float, float, float) | Gamma-Korrektur eines Bildes. |
| override [BinarizeBradley](../../aspose.imaging.fileformats.gif/gifimage/binarizebradley#binarizebradley)(double) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung des integralen Bildschwellenwerts |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double, int) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung des integralen Bildschwellenwerts |
| override [BinarizeFixed](../../aspose.imaging.fileformats.gif/gifimage/binarizefixed)(byte) | Binarisierung eines Bildes mit vordefiniertem Schwellwert |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.gif/gifimage/binarizeotsu)() | Binarisierung eines Bildes mit Otsu-Thresholding |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata)() | Speichert die Daten privat. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Legt fest, ob das Bild in dem angegebenen Dateiformat gespeichert werden kann, das durch die übergebenen Speicheroptionen repräsentiert wird. |
| [ClearBlocks](../../aspose.imaging.fileformats.gif/gifimage/clearblocks)() | Löscht alle GIF-Blöcke. |
| override [Crop](../../aspose.imaging.fileformats.gif/gifimage/crop#crop)(Rectangle) | Bild zuschneiden. |
| override [Crop](../../aspose.imaging/rastercachedmultipageimage/crop)(int, int, int, int) | Bild mit Verschiebungen zuschneiden. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Führt Dithering auf dem aktuellen Bild durch. |
| override [Dither](../../aspose.imaging.fileformats.gif/gifimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | Führt Dithering auf dem aktuellen Bild durch. |
| override [Filter](../../aspose.imaging.fileformats.gif/gifimage/filter)(Rectangle, FilterOptionsBase) | Filtert das angegebene Rechteck. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Ruft ein 32-Bit-ARGB-Pixelbild ab. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Ruft das standardmäßige 32-Bit-ARGB-Pixel-Array ab. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Ruft die Standardoptionen ab. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Ruft das Standard-Pixel-Array mit partiellem Pixel-Loader ab. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Ruft das Standard-Rohdatenarray ab. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Ruft das Standard-Rohdaten-Array mit partiellem Pixel-Loader ab. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Ruft das Datum und die Uhrzeit ab, zu der das Ressourcenbild zuletzt geändert wurde. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.gif/gifimage/getoriginaloptions)() | Ruft die Optionen basierend auf den ursprünglichen Dateieinstellungen ab. Dies kann hilfreich sein, um die Bittiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz-weißes PNG-Bild mit 1 Bit pro Pixel laden und dann Speichern Sie es mit the [`Save`](../../aspose.imaging/datastreamsupporter/save) -Methode wird das ausgegebene PNG-Bild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und das PNG-Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um entsprechende Speicheroptionen zu erhalten, und übergeben Sie sie an die[`Save`](../../aspose.imaging/image/save) Methode als zweiten Parameter. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Ruft ein Bildpixel ab. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Ruft den Schräglaufwinkel ab. Diese Methode ist auf gescannte Textdokumente anwendbar, um den Schräglaufwinkel beim Scannen zu bestimmen. |
| override [Grayscale](../../aspose.imaging.fileformats.gif/gifimage/grayscale)() | Transformation eines Bildes in seine Graustufendarstellung |
| [InsertBlock](../../aspose.imaging.fileformats.gif/gifimage/insertblock)(int, IGifBlock) | Fügt einen neuen GIF-Block hinzu. |
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
| [OrderBlocks](../../aspose.imaging.fileformats.gif/gifimage/orderblocks)() | Ordnet die GIF-Blöcke gemäß der GIF-Spezifikation an. Etwas[`GifGraphicsControlBlock`](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) kann für ein korrektes GIF-Layout entfernt werden. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Liest die gesamte Scanzeile mit dem angegebenen Scanzeilenindex. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Liest die gesamte Scanzeile mit dem angegebenen Scanzeilenindex. |
| [RemoveBlock](../../aspose.imaging.fileformats.gif/gifimage/removeblock)(IGifBlock) | Entfernt den GIF-Block. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Ersetzt eine Farbe durch eine andere mit zulässigem Unterschied und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | Ersetzt eine Farbe durch eine andere mit zulässigem Unterschied und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Ersetzt alle nicht transparenten Farben durch neue Farben und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. Hinweis: Wenn Sie es auf Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | Ersetzt alle nicht transparenten Farben durch neue Farben und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. Hinweis: Wenn Sie es auf Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Ändert die Bildgröße. Der StandardNearestNeighbourResample wird verwendet. |
| override [Resize](../../aspose.imaging.fileformats.gif/gifimage/resize#resize_1)(int, int, ImageResizeSettings) | Ändert die Bildgröße. |
| override [Resize](../../aspose.imaging.fileformats.gif/gifimage/resize#resize_2)(int, int, ResizeType) | Ändert die Bildgröße. |
| [ResizeFullFrame](../../aspose.imaging.fileformats.gif/gifimage/resizefullframe)(int, int, ResizeType) | Ändert die Größe des Bildes unter Verwendung von Vollbildern für jede GIF-Seite. Erforderlich, um mögliche Artefakte zu vermeiden. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Ändert die Höhe proportional. Der StandardNearestNeighbourResample wird verwendet. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Ändert die Höhe proportional. |
| override [ResizeHeightProportionally](../../aspose.imaging/rastercachedmultipageimage/resizeheightproportionally)(int, ResizeType) | Ändert die Breite proportional. |
| [ResizeProportional](../../aspose.imaging.fileformats.gif/gifimage/resizeproportional)(int, int, ResizeType) | Führt eine proportionale Größenänderung des Bildes durch. Die proportionale Größenänderung ändert die Größe jedes Frames gemäß dem Verhältnis von*newWidth*/Breite und*newHeight* /Höhe. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Ändert die Breite proportional. Der StandardNearestNeighbourResample wird verwendet. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Ändert die Breite proportional. |
| override [ResizeWidthProportionally](../../aspose.imaging/rastercachedmultipageimage/resizewidthproportionally)(int, ResizeType) | Ändert die Breite proportional. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Bild um die Mitte drehen. |
| override [Rotate](../../aspose.imaging.fileformats.gif/gifimage/rotate#rotate_1)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate Bild um die Mitte. |
| override [RotateFlip](../../aspose.imaging.fileformats.gif/gifimage/rotateflip)(RotateFlipType) | Rotiert, kippt oder dreht und kippt nur den aktiven Rahmen. |
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
| [SetFrameTime](../../aspose.imaging.fileformats.gif/gifimage/setframetime)(ushort) | Legt die Dauer aller Frames in Millisekunden fest. Durch Ändern dieses Werts wird die Verzögerung für alle Frames zurückgesetzt. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | Legt die Bildpalette fest. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | Setzt ein Bildpixel für die angegebene Position. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | Legt die Auflösung dafür fest[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Konvertiert Rasterbild in Bitmap. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Schreibt die gesamte Scanzeile in den angegebenen Scanzeilenindex. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Schreibt die gesamte Scanzeile in den angegebenen Scanzeilenindex. |

### Beispiele

Export eines Teils der Animation aus dem GIF-Bild basierend auf dem Zeitintervall.

```csharp
[C#]

using (var image = Image.Load("Animation.gif"))
{
    var options = new GifOptions
    {
        FullFrame = true,
        MultiPageOptions = new MultiPageOptions
        {
            Mode = MultiPageMode.TimeInterval,
            TimeInterval = new TimeInterval(0, 400)
        }
    };

    image.Save("PartOfAnimation.gif", options);
}
```

Dieses Beispiel zeigt, wie ein GIF-Bild erstellt und in einer Datei gespeichert wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Erstellen Sie einen GIF-Frame-Block von 100 x 100 Pixel.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // Den gesamten Block rot füllen.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

Erstellen Sie ein mehrseitiges GIF-Bild mit einseitigen Rasterbildern.

```csharp
[C#]

static void Main(string[] args)
{
    // Frames laden
    var frames = LoadFrames("Animation frames").ToArray();

    // GIF-Bild mit dem ersten Frame erstellen
    using (var image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Rahmen zum GIF-Bild mit der AddPage-Methode hinzufügen
        for (var index = 1; index < frames.Length; index++)
        {
            image.AddPage(frames[index]);
        }

        // GIF-Bild speichern
        image.Save("Multipage.gif");
    }
}

private static IEnumerable<RasterImage> LoadFrames(string directory)
{
    foreach (var filePath in Directory.GetFiles(directory))
    {
        yield return (RasterImage)Image.Load(filePath);
    }
}
```

### Siehe auch

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* namensraum [Aspose.Imaging.FileFormats.Gif](../../aspose.imaging.fileformats.gif)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
