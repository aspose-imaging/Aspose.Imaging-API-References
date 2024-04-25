---
title: ApngImage
second_title: Aspose.Imaging für .NET-API-Referenz
description: Das animierte PNG-Bild.
type: docs
weight: 1320
url: /de/aspose.imaging.fileformats.apng/apngimage/
---
## ApngImage class

Das animierte PNG-Bild.

```csharp
public sealed class ApngImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ApngImage](apngimage)(ApngOptions, int, int) | Initialisiert eine neue Instanz von[`ApngImage`](../apngimage) Klasse. |

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
| [DefaultFrameTime](../../aspose.imaging.fileformats.apng/apngimage/defaultframetime) { get; set; } | Ruft die Standard-Frame-Dauer ab oder legt sie fest. Wird beim Erstellen neuer Frames verwendet. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| override [FileFormat](../../aspose.imaging.fileformats.apng/apngimage/fileformat) { get; } | Ruft einen Wert von Dateiformat ab |
| override [HasAlpha](../../aspose.imaging/rastercachedmultipageimage/hasalpha) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz alpha hat. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor) { get; } | Ruft einen Wert ab, der angibt, ob das Bild eine transparente Farbe hat. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | Ruft die Bildhöhe ab. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Ermittelt oder setzt die horizontale Auflösung davon in Pixel pro Zoll[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity) { get; } | Ruft die Deckkraft dieses Bildes ab. |
| [Interlaced](../../aspose.imaging.fileformats.apng/apngimage/interlaced) { get; } | Ruft einen Wert ab, der angibt, ob dies[`PngImage`](../../aspose.imaging.fileformats.png/pngimage) ist interlaced. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Holt oder setzt den Interrupt-Monitor. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | Ruft einen Wert ab, der angibt, ob Bilddaten derzeit zwischengespeichert werden. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Ruft einen Wert ab, der angibt, ob das Laden von Rohdaten verfügbar ist. |
| [NumPlays](../../aspose.imaging.fileformats.apng/apngimage/numplays) { get; set; } | Ruft ab oder legt fest, wie oft die Animation wiederholt werden soll. 0 bedeutet Endlosschleife. |
| override [PageCount](../../aspose.imaging.fileformats.apng/apngimage/pagecount) { get; } | Ruft die Seitenanzahl ab. |
| override [PageExportingAction](../../aspose.imaging.fileformats.apng/apngimage/pageexportingaction) { get; set; } | Ruft die Aktion zum Exportieren der Seite ab oder legt sie fest. Bitte beachten Sie, dass das Festlegen dieser Methode automatisch Seitenressourcen freigibt, nachdem sie ausgeführt wurde. Sie wird unmittelbar vor dem Speichern jeder Seite ausgeführt. |
| override [Pages](../../aspose.imaging.fileformats.apng/apngimage/pages) { get; } | Ruft die Seiten ab. |
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
| override [XmpData](../../aspose.imaging.fileformats.apng/apngimage/xmpdata) { get; set; } | Ruft die XMP-Metadaten ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe#addframe)() | Fügt einen neuen Rahmen am Ende der eigenen Rahmensammlung hinzu. Ein neuer Rahmen wird entsprechend der Größe des aktuellen Bildes erstellt. |
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe#addframe_1)(RasterImage) | Fügt einen neuen Rahmen am Ende der eigenen Rahmensammlung hinzu. Der Inhalt des neuen Rahmens wird aus dem angegebenen Bild gefüllt. |
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe#addframe_2)(RasterImage, uint) | Fügt einen neuen Rahmen am Ende der eigenen Rahmensammlung hinzu. Der Inhalt des neuen Rahmens wird aus dem angegebenen Bild gefüllt. |
| [AddPage](../../aspose.imaging.fileformats.apng/apngimage/addpage)(RasterImage) | Fügt dem Bild eine Seite hinzu. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.apng/apngimage/adjustbrightness)(int) | Anpassen von a*brightness* für Bild. |
| override [AdjustContrast](../../aspose.imaging.fileformats.apng/apngimage/adjustcontrast)(float) | [`Image`](../../aspose.imaging/image) kontrastierend |
| override [AdjustGamma](../../aspose.imaging.fileformats.apng/apngimage/adjustgamma#adjustgamma)(float) | Gamma-Korrektur eines Bildes. |
| override [AdjustGamma](../../aspose.imaging.fileformats.apng/apngimage/adjustgamma#adjustgamma_1)(float, float, float) | Gamma-Korrektur eines Bildes. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung des integralen Bildschwellenwerts |
| override [BinarizeBradley](../../aspose.imaging.fileformats.apng/apngimage/binarizebradley#binarizebradley_1)(double, int) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung des integralen Bildschwellenwerts |
| override [BinarizeFixed](../../aspose.imaging.fileformats.apng/apngimage/binarizefixed)(byte) | Binarisierung eines Bildes mit vordefiniertem Schwellwert |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.apng/apngimage/binarizeotsu)() | Binarisierung eines Bildes mit Otsu-Thresholding |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata)() | Speichert die Daten privat. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Legt fest, ob das Bild in dem angegebenen Dateiformat gespeichert werden kann, das durch die übergebenen Speicheroptionen repräsentiert wird. |
| override [Crop](../../aspose.imaging.fileformats.apng/apngimage/crop#crop)(Rectangle) | Bild zuschneiden. |
| override [Crop](../../aspose.imaging.fileformats.apng/apngimage/crop#crop_1)(int, int, int, int) | Bild mit Verschiebungen zuschneiden. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Führt Dithering auf dem aktuellen Bild durch. |
| override [Dither](../../aspose.imaging.fileformats.apng/apngimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | Führt Dithering auf dem aktuellen Bild durch. |
| override [Filter](../../aspose.imaging.fileformats.apng/apngimage/filter)(Rectangle, FilterOptionsBase) | Filtert das angegebene Rechteck. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Ruft ein 32-Bit-ARGB-Pixelbild ab. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Ruft das standardmäßige 32-Bit-ARGB-Pixel-Array ab. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.apng/apngimage/getdefaultoptions)(object[]) | Ruft die Standardoptionen ab. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Ruft das Standard-Pixel-Array mit partiellem Pixel-Loader ab. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Ruft das Standard-Rohdatenarray ab. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Ruft das Standard-Rohdaten-Array mit partiellem Pixel-Loader ab. |
| override [GetModifyDate](../../aspose.imaging.fileformats.apng/apngimage/getmodifydate)(bool) | Ruft das Datum und die Uhrzeit ab, zu der das Ressourcenbild zuletzt geändert wurde. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.apng/apngimage/getoriginaloptions)() | Ruft die Optionen basierend auf den ursprünglichen Dateieinstellungen ab. Dies kann hilfreich sein, um die Bittiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz-weißes PNG-Bild mit 1 Bit pro Pixel laden und dann Speichern Sie es mit the [`Save`](../../aspose.imaging/datastreamsupporter/save) -Methode wird das ausgegebene PNG-Bild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und das PNG-Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um entsprechende Speicheroptionen zu erhalten, und übergeben Sie sie an die[`Save`](../../aspose.imaging/image/save) Methode als zweiten Parameter. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Ruft ein Bildpixel ab. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Ruft den Schräglaufwinkel ab. Diese Methode ist auf gescannte Textdokumente anwendbar, um den Schräglaufwinkel beim Scannen zu bestimmen. |
| override [Grayscale](../../aspose.imaging.fileformats.apng/apngimage/grayscale)() | Transformation eines Bildes in seine Graustufendarstellung |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe#insertframe)(int) | Fügt einen neuen Rahmen in die eigene Rahmensammlung am angegebenen Index ein. Ein neuer Rahmen wird entsprechend der Größe des aktuellen Bildes erstellt. |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe#insertframe_1)(int, RasterImage) | Fügt einen neuen Rahmen in die eigene Rahmensammlung am angegebenen Index ein. Der Inhalt des neuen Rahmens wird aus dem angegebenen Bild gefüllt. |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe#insertframe_2)(int, RasterImage, uint) | Fügt einen neuen Rahmen in die eigene Rahmensammlung am angegebenen Index ein. Der Inhalt des neuen Rahmens wird aus dem angegebenen Bild gefüllt. |
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
| [PopFrameAt](../../aspose.imaging.fileformats.apng/apngimage/popframeat)(int) | Entfernt den Frame und gibt ihn am angegebenen Index der eigenen Frame-Sammlung zurück. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Liest die gesamte Scanzeile mit dem angegebenen Scanzeilenindex. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Liest die gesamte Scanzeile mit dem angegebenen Scanzeilenindex. |
| [RemoveAllFrames](../../aspose.imaging.fileformats.apng/apngimage/removeallframes)() | Entfernt alle Frames aus der eigenen Frame-Sammlung. |
| [RemoveFrameAt](../../aspose.imaging.fileformats.apng/apngimage/removeframeat)(int) | Entfernt den Frame am angegebenen Index aus der eigenen Frame-Sammlung. Der zu löschende Frame wird verworfen. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Ersetzt eine Farbe durch eine andere mit zulässigem Unterschied und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | Ersetzt eine Farbe durch eine andere mit zulässigem Unterschied und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Ersetzt alle nicht transparenten Farben durch neue Farben und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. Hinweis: Wenn Sie es auf Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | Ersetzt alle nicht transparenten Farben durch neue Farben und behält den ursprünglichen Alpha-Wert bei, um glatte Kanten zu erhalten. Hinweis: Wenn Sie es auf Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| [ResetDefaultImage](../../aspose.imaging.fileformats.apng/apngimage/resetdefaultimage)() | Löscht ein zuvor gesetztes Standardbild. Danach ist das Standardbild das erste Bild in der eigenen Rahmensammlung (es kann mit dieser Methode nicht gelöscht werden). |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Ändert die Bildgröße. Der StandardNearestNeighbourResample wird verwendet. |
| override [Resize](../../aspose.imaging.fileformats.apng/apngimage/resize#resize_1)(int, int, ImageResizeSettings) | Ändert die Bildgröße. |
| override [Resize](../../aspose.imaging.fileformats.apng/apngimage/resize#resize_2)(int, int, ResizeType) | Ändert die Bildgröße. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Ändert die Höhe proportional. Der StandardNearestNeighbourResample wird verwendet. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Ändert die Höhe proportional. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.apng/apngimage/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Ändert die Breite proportional. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Ändert die Breite proportional. Der StandardNearestNeighbourResample wird verwendet. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Ändert die Breite proportional. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.apng/apngimage/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Ändert die Breite proportional. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Bild um die Mitte drehen. |
| override [Rotate](../../aspose.imaging.fileformats.apng/apngimage/rotate#rotate_1)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate Bild um die Mitte. |
| override [RotateFlip](../../aspose.imaging.fileformats.apng/apngimage/rotateflip)(RotateFlipType) | Rotiert, kippt oder dreht und kippt nur den aktiven Rahmen. |
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
| [SetDefaultImage](../../aspose.imaging.fileformats.apng/apngimage/setdefaultimage)(RasterImage) | Legt das angegebene Rasterbild als Standardbild der aktuellen Animation fest. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | Legt die Bildpalette fest. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | Setzt ein Bildpixel für die angegebene Position. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | Legt die Auflösung dafür fest[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Konvertiert Rasterbild in Bitmap. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Schreibt die gesamte Scanzeile in den angegebenen Scanzeilenindex. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Schreibt die gesamte Scanzeile in den angegebenen Scanzeilenindex. |

### Beispiele

Das folgende Beispiel zeigt, wie das Dateiformat apng APNG aus einem anderen nicht animierten mehrseitigen Format exportiert wird.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("img4.tif")) {
    // Festlegen der Standard-Frame-Dauer
    image.Save("img4.tif.500ms.png", new ApngOptions() { DefaultFrameTime = 500 }); // 500 ms
    image.Save("img4.tif.250ms.png", new ApngOptions() { DefaultFrameTime = 250 }); // 250 ms
}
```

Das folgende Beispiel zeigt, wie Sie in das APNG-Dateiformat exportieren.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("Animation1.webp")) {
    // Export in APNG-Animation mit unbegrenzten Animationszyklen als Standard
    image.Save("Animation1.webp.png", new ApngOptions());
    // Animationszyklen einrichten
    image.Save("Animation2.webp.png", new ApngOptions() { NumPlays = 5 }); // 5 Zyklen
}
```

Das folgende Beispiel zeigt, wie Sie ein APNG-Bild aus einem anderen einseitigen Rasterbild erstellen.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;
using Aspose.Imaging.FileFormats.Apng;

const int AnimationDuration = 1000; // 1 Sek
const int FrameDuration = 70; // 70 ms
using (RasterImage sourceImage = (RasterImage)Image.Load("not_animated.png"))
{
    ApngOptions createOptions = new ApngOptions
    {
        Source = new FileCreateSource("raster_animation.png", false),
        DefaultFrameTime = (uint)FrameDuration,
        ColorType = PngColorType.TruecolorWithAlpha,
    };

    using (ApngImage apngImage = (ApngImage)Image.Create(
        createOptions,
        sourceImage.Width,
        sourceImage.Height))
    {
        // Es ist möglich, dort die Standard-Frame-Zeit des Bildes einzustellen: apngImage.DefaultFrameTime = (uint)FrameDuration;

        int numOfFrames = AnimationDuration / FrameDuration;
        int numOfFrames2 = numOfFrames / 2;

        // Bereinigen, da das Bild standardmäßig einen Frame enthält
        apngImage.RemoveAllFrames();

        // ersten Frame hinzufügen
        apngImage.AddFrame(sourceImage);

        // Zwischenframes hinzufügen
        for (int frameIndex = 1; frameIndex < numOfFrames - 1; ++frameIndex)
        {
            apngImage.AddFrame(sourceImage);
            ApngFrame lastFrame = (ApngFrame)apngImage.Pages[apngImage.PageCount - 1];
            float gamma = frameIndex >= numOfFrames2 ? numOfFrames - frameIndex - 1 : frameIndex;
            lastFrame.AdjustGamma(gamma);
        }

        // letzten Frame hinzufügen
        apngImage.AddFrame(sourceImage);

        apngImage.Save();
    }
}
```

### Siehe auch

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* namensraum [Aspose.Imaging.FileFormats.Apng](../../aspose.imaging.fileformats.apng)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
