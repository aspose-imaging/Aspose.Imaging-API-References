---
title: TiffFrame
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der TIFF-Frame.
type: docs
weight: 7870
url: /de/aspose.imaging.fileformats.tiff/tiffframe/
---
## TiffFrame class

Der TIFF-Frame.

```csharp
public sealed class TiffFrame : RasterCachedImage
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [TiffFrame](tiffframe#constructor_1)(RasterImage) | Initialisiert eine neue Instanz von[`TiffFrame`](../tiffframe) Klasse. |
| [TiffFrame](tiffframe#constructor_3)(Stream) | Initialisiert eine neue Instanz von[`TiffFrame`](../tiffframe) Klasse. |
| [TiffFrame](tiffframe#constructor_5)(string) | Initialisiert eine neue Instanz von[`TiffFrame`](../tiffframe) Klasse. |
| [TiffFrame](tiffframe#constructor_2)(RasterImage, TiffOptions) | Initialisiert eine neue Instanz von[`TiffFrame`](../tiffframe) Klasse. |
| [TiffFrame](tiffframe#constructor_4)(Stream, TiffOptions) | Initialisiert eine neue Instanz von[`TiffFrame`](../tiffframe) Klasse. |
| [TiffFrame](tiffframe#constructor_6)(string, TiffOptions) | Initialisiert eine neue Instanz von[`TiffFrame`](../tiffframe) Klasse. |
| [TiffFrame](tiffframe#constructor)(TiffOptions, int, int) | Initialisiert eine neue Instanz von[`TiffFrame`](../tiffframe) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Palette automatisch angepasst wird. |
| override [BackgroundColor](../../aspose.imaging.fileformats.tiff/tiffframe/backgroundcolor) { get; set; } | Ruft einen Wert für die Hintergrundfarbe ab oder legt ihn fest. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.tiff/tiffframe/bitsperpixel) { get; } | Ruft die Anzahl der Bildbits pro Pixel ab. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Ruft die Bildgrenzen ab. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [Container](../../aspose.imaging/image/container) { get; } | Ruft die ab[`Image`](../../aspose.imaging/image) Container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Ruft den Datenstrom des Objekts ab. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [ExifData](../../aspose.imaging.fileformats.tiff/tiffframe/exifdata) { get; set; } | Ruft EXIF-Daten vom Frame ab oder legt sie fest. |
| virtual [FileFormat](../../aspose.imaging/image/fileformat) { get; } | Ruft einen Wert von Dateiformat ab |
| [FrameOptions](../../aspose.imaging.fileformats.tiff/tiffframe/frameoptions) { get; } | Ruft die Rahmenerstellungsoptionen ab. |
| override [HasAlpha](../../aspose.imaging.fileformats.tiff/tiffframe/hasalpha) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz alpha hat. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| override [HasTransparentColor](../../aspose.imaging.fileformats.tiff/tiffframe/hastransparentcolor) { get; set; } | Ruft einen Wert ab, der angibt, ob das Bild eine transparente Farbe hat. |
| override [Height](../../aspose.imaging.fileformats.tiff/tiffframe/height) { get; } | Ruft die Bildhöhe ab. |
| override [HorizontalResolution](../../aspose.imaging.fileformats.tiff/tiffframe/horizontalresolution) { get; set; } | Ermittelt oder setzt die horizontale Auflösung davon in Pixel pro Zoll[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity) { get; } | Ruft die Deckkraft dieses Bildes ab. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Holt oder setzt den Interrupt-Monitor. |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached) { get; } | Ruft einen Wert ab, der angibt, ob Bilddaten derzeit zwischengespeichert werden. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Ruft einen Wert ab, der angibt, ob das Laden von Rohdaten verfügbar ist. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| [PathResources](../../aspose.imaging.fileformats.tiff/tiffframe/pathresources) { get; set; } | Ruft die Pfadressourcen ab oder legt sie fest. |
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
| override [VerticalResolution](../../aspose.imaging.fileformats.tiff/tiffframe/verticalresolution) { get; set; } | Ermittelt oder setzt die vertikale Auflösung davon in Pixel pro Zoll[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging.fileformats.tiff/tiffframe/width) { get; } | Ruft die Bildbreite ab. |
| override [XmpData](../../aspose.imaging.fileformats.tiff/tiffframe/xmpdata) { get; set; } | Ruft XMP-Daten vom Frame ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [CopyFrame](../../aspose.imaging.fileformats.tiff/tiffframe/copyframe)(TiffFrame) | Kopiert den gesamten Frame (Duplikate). |
| static [CreateFrameFrom](../../aspose.imaging.fileformats.tiff/tiffframe/createframefrom)(TiffFrame, TiffOptions) | Erstellt den Rahmen aus angegeben*tiffFrame* unter Verwendung der angegebenen*options* . Die Pixeldaten bleiben erhalten, werden aber in das gewünschte Format konvertiert. |
| override [AdjustBrightness](../../aspose.imaging/rastercachedimage/adjustbrightness)(int) | Anpassen einer Helligkeit für das Bild. |
| override [AdjustContrast](../../aspose.imaging/rastercachedimage/adjustcontrast)(float) | Bildkontrast |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float) | Gamma-Korrektur eines Bildes. |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float, float, float) | Gamma-Korrektur eines Bildes. |
| [AlignResolutions](../../aspose.imaging.fileformats.tiff/tiffframe/alignresolutions)() | Hilfsmethode, um horizontale und vertikale Auflösungen gleich zu machen. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung des integralen Bildschwellenwerts |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double, int) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung des integralen Bildschwellenwerts |
| override [BinarizeFixed](../../aspose.imaging/rastercachedimage/binarizefixed)(byte) | Binarisierung eines Bildes mit vordefiniertem Schwellwert |
| override [BinarizeOtsu](../../aspose.imaging/rastercachedimage/binarizeotsu)() | Binarisierung eines Bildes mit Otsu-Thresholding |
| override [CacheData](../../aspose.imaging/rastercachedimage/cachedata)() | Zwischenspeichert die Daten und stellt sicher, dass kein zusätzliches Laden von Daten aus der zugrunde liegenden Datei durchgeführt wird[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Legt fest, ob das Bild in dem angegebenen Dateiformat gespeichert werden kann, das durch die übergebenen Speicheroptionen repräsentiert wird. |
| override [Crop](../../aspose.imaging.fileformats.tiff/tiffframe/crop#crop)(Rectangle) | Bild zuschneiden. |
| virtual [Crop](../../aspose.imaging/rasterimage/crop)(int, int, int, int) | Bild mit Verschiebungen zuschneiden. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Führt Dithering auf dem aktuellen Bild durch. |
| override [Dither](../../aspose.imaging/rastercachedimage/dither)(DitheringMethod, int, IColorPalette) | Führt Dithering auf dem aktuellen Bild durch. |
| virtual [Filter](../../aspose.imaging/rasterimage/filter)(Rectangle, FilterOptionsBase) | Filtert das angegebene Rechteck. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Ruft ein 32-Bit-ARGB-Pixelbild ab. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Ruft das standardmäßige 32-Bit-ARGB-Pixel-Array ab. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Ruft die Standardoptionen ab. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Ruft das Standard-Pixel-Array mit partiellem Pixel-Loader ab. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Ruft das Standard-Rohdatenarray ab. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Ruft das Standard-Rohdaten-Array mit partiellem Pixel-Loader ab. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Ruft das Datum und die Uhrzeit ab, zu der das Ressourcenbild zuletzt geändert wurde. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.tiff/tiffframe/getoriginaloptions)() | Ruft die Optionen basierend auf den ursprünglichen Dateieinstellungen ab. Dies kann hilfreich sein, um die Bittiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz-weißes PNG-Bild mit 1 Bit pro Pixel laden und dann Speichern Sie es mit the [`Save`](../../aspose.imaging/datastreamsupporter/save) -Methode wird das ausgegebene PNG-Bild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und das PNG-Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um entsprechende Speicheroptionen zu erhalten, und übergeben Sie sie an die[`Save`](../../aspose.imaging/image/save) Methode als zweiten Parameter. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Ruft ein Bildpixel ab. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Ruft den Schräglaufwinkel ab. Diese Methode ist auf gescannte Textdokumente anwendbar, um den Schräglaufwinkel beim Scannen zu bestimmen. |
| override [Grayscale](../../aspose.imaging/rastercachedimage/grayscale)() | Transformation eines Bildes in seine Graustufendarstellung |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | Lädt 32-Bit-ARGB-Pixel. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | Lädt 64-Bit-ARGB-Pixel. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | Lädt Pixel im CMYK-Format. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Lädt 32-Bit-ARGB-Pixel teilweise nach Paketen. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Lädt Pixel teilweise nach Paketen. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | Lädt Pixel. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Lädt Rohdaten. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Lädt Rohdaten. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | Normalisiert den Winkel. Diese Methode ist auf gescannte Textdokumente anwendbar, um den schiefen Scan zu beseitigen. Diese Methode verwendet[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) und[`Rotate`](../../aspose.imaging/rasterimage/rotate) Methoden. |
| virtual [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)(bool, Color) | Normalisiert den Winkel. Diese Methode ist auf gescannte Textdokumente anwendbar, um den schiefen Scan zu beseitigen. Diese Methode verwendet[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) und[`Rotate`](../../aspose.imaging/rasterimage/rotate) Methoden. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Liest die gesamte Scanzeile mit dem angegebenen Scanzeilenindex. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Liest die gesamte Scanzeile mit dem angegebenen Scanzeilenindex. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Ersetzt eine Farbe durch eine andere mit zulässigem Unterschied und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. |
| virtual [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(int, byte, int) | Ersetzt eine Farbe durch eine andere mit zulässigem Unterschied und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Ersetzt alle nicht transparenten Farben durch neue Farben und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. Hinweis: Wenn Sie es auf Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| virtual [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(int) | Ersetzt alle nicht transparenten Farben durch neue Farben und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. Hinweis: Wenn Sie es auf Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Ändert die Bildgröße. Der StandardNearestNeighbourResample wird verwendet. |
| override [Resize](../../aspose.imaging/rastercachedimage/resize)(int, int, ImageResizeSettings) | Ändert die Bildgröße. |
| override [Resize](../../aspose.imaging.fileformats.tiff/tiffframe/resize#resize_2)(int, int, ResizeType) | Ändert die Bildgröße. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Ändert die Höhe proportional. Der StandardNearestNeighbourResample wird verwendet. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Ändert die Höhe proportional. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Ändert die Höhe proportional. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Ändert die Breite proportional. Der StandardNearestNeighbourResample wird verwendet. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Ändert die Breite proportional. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Ändert die Breite proportional. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Bild um die Mitte drehen. |
| override [Rotate](../../aspose.imaging.fileformats.tiff/tiffframe/rotate#rotate_1)(float, bool, Color) | Bild um die Mitte drehen. |
| override [RotateFlip](../../aspose.imaging/rastercachedimage/rotateflip)(RotateFlipType) | Dreht, kippt oder dreht und kippt das Bild. |
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

Dieses Beispiel zeigt, wie Sie ein TIFF-Bild von Grund auf neu erstellen und in einer Datei speichern.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    
// Setze 8 Bits für jede Farbkomponente.
createOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// Lege die Big-Endian-Byte-Reihenfolge fest (Motorola)
createOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Legen Sie die LZW-Komprimierung fest.
createOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Legen Sie das RGB-Farbmodell fest.
createOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// Alle Farbkomponenten werden in einer einzigen Ebene gespeichert.
createOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Erstellen Sie einen TIFF-Frame von 100 x 100 px.
// Beachten Sie, dass Sie einen Rahmen nicht explizit löschen müssen, wenn er in TiffImage enthalten ist.
// Wenn der Container entsorgt wird, werden alle Frames automatisch entsorgt.
Aspose.Imaging.FileFormats.Tiff.TiffFrame firstFrame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions, 100, 100);
    
// Füllen Sie den gesamten Rahmen mit dem blau-gelben Farbverlauf.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(firstFrame.Width, firstFrame.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(firstFrame);
graphics.FillRectangle(gradientBrush, firstFrame.Bounds);

// Erstellen Sie ein TIFF-Bild.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(firstFrame))
{
    tiffImage.Save(dir + "output.tif");
}
```

### Siehe auch

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage)
* namensraum [Aspose.Imaging.FileFormats.Tiff](../../aspose.imaging.fileformats.tiff)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
