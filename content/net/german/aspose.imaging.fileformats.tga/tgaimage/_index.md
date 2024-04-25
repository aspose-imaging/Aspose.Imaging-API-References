---
title: TgaImage
second_title: Aspose.Imaging für .NET-API-Referenz
description: Das TGA-Bild.
type: docs
weight: 7580
url: /de/aspose.imaging.fileformats.tga/tgaimage/
---
## TgaImage class

Das TGA-Bild.

```csharp
public class TgaImage : RasterCachedImage
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [TgaImage](tgaimage#constructor)(RasterImage) | Initialisiert eine neue Instanz von[`TgaImage`](../tgaimage) Klasse. |
| [TgaImage](tgaimage#constructor_1)(Stream) | Initialisiert eine neue Instanz von[`TgaImage`](../tgaimage) Klasse. |
| [TgaImage](tgaimage#constructor_2)(string) | Initialisiert eine neue Instanz von[`TgaImage`](../tgaimage) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AuthorComments](../../aspose.imaging.fileformats.tga/tgaimage/authorcomments) { get; set; } | Ruft Autorenkommentare ab oder legt sie fest. Dies ist ein ASCII-Feld, das aus 324 Bytes besteht, die in vier Zeilen mit 80 Zeichen organisiert sind, denen jeweils ein Nullabschlusszeichen folgt. |
| [AuthorName](../../aspose.imaging.fileformats.tga/tgaimage/authorname) { get; set; } | Ruft den Autorennamen ab oder legt ihn fest. Dieses Feld enthält insgesamt 40 ASCII-Zeichen für den Namen. Wenn das Feld verwendet wird, sollte es den Namen der Person enthalten, die das Bild erstellt hat (Autor). |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Palette automatisch angepasst wird. |
| override [BackgroundColor](../../aspose.imaging.fileformats.tga/tgaimage/backgroundcolor) { get; set; } | Ruft die Hintergrundfarbe ab oder legt sie fest. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.tga/tgaimage/bitsperpixel) { get; } | Ruft Bits pro Pixel ab. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Ruft die Bildgrenzen ab. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [BytesPerPixel](../../aspose.imaging.fileformats.tga/tgaimage/bytesperpixel) { get; } | Ruft Bytes pro Pixel ab. |
| [Container](../../aspose.imaging/image/container) { get; } | Ruft die ab[`Image`](../../aspose.imaging/image) Container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Ruft den Datenstrom des Objekts ab. |
| [DateTimeStamp](../../aspose.imaging.fileformats.tga/tgaimage/datetimestamp) { get; set; } | Ruft Datums-/Zeitstempel ab oder legt diesen fest. Dieses Feld definiert den Wert für das Datum und die Uhrzeit, zu der das Bild gespeichert wurde. Obwohl Betriebssysteme Dateien normalerweise mit Zeit- und Datumsstempeln versehen, wird diese Funktion bereitgestellt, da das Betriebssystem den Zeit- und Datumsstempel ändern kann, wenn die Datei kopiert wird. Durch die Verwendung dieses Bereichs wird Ihnen ein unveränderter Bereich für die Aufnahme von Datum und Uhrzeit garantiert. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| override [FileFormat](../../aspose.imaging.fileformats.tga/tgaimage/fileformat) { get; } | Ruft das Dateiformat ab. |
| [GammaValueDenominator](../../aspose.imaging.fileformats.tga/tgaimage/gammavaluedenominator) { get; } | Ruft den Teil des Gamma-Wert-Nenners ab. Ein unkorrigiertes Bild (ein Bild ohne Gamma) sollte als Ergebnis den Wert 1,0 haben. |
| [GammaValueNumerator](../../aspose.imaging.fileformats.tga/tgaimage/gammavaluenumerator) { get; } | Ruft den Teil des Gammawertzählers ab. Ein unkorrigiertes Bild (ein Bild ohne Gamma) sollte als Ergebnis den Wert 1,0 haben. |
| override [HasAlpha](../../aspose.imaging.fileformats.tga/tgaimage/hasalpha) { get; } | Ruft einen Wert ab, der angibt, ob dies[`TgaImage`](../tgaimage) hat einen Alphakanal. |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.tga/tgaimage/hasbackgroundcolor) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| [HasColorMap](../../aspose.imaging.fileformats.tga/tgaimage/hascolormap) { get; } | Ruft einen Wert ab, der angibt, ob dieses Bild eine Farbkarte hat. |
| override [HasTransparentColor](../../aspose.imaging.fileformats.tga/tgaimage/hastransparentcolor) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob das Bild transparente Farbe hat. |
| override [Height](../../aspose.imaging.fileformats.tga/tgaimage/height) { get; } | Ruft diese Bildhöhe ab. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Ermittelt oder setzt die horizontale Auflösung davon in Pixel pro Zoll[`RasterImage`](../../aspose.imaging/rasterimage) . |
| [ImageId](../../aspose.imaging.fileformats.tga/tgaimage/imageid) { get; set; } | Ruft die Bild-ID ab oder legt sie fest. |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity) { get; } | Ruft die Deckkraft dieses Bildes ab. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Holt oder setzt den Interrupt-Monitor. |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached) { get; } | Ruft einen Wert ab, der angibt, ob Bilddaten derzeit zwischengespeichert werden. |
| [IsGrayScale](../../aspose.imaging.fileformats.tga/tgaimage/isgrayscale) { get; } | Ruft einen Wert ab, der angibt, ob dies[`TgaImage`](../tgaimage) ist Graustufen. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Ruft einen Wert ab, der angibt, ob das Laden von Rohdaten verfügbar ist. |
| [JobNameOrId](../../aspose.imaging.fileformats.tga/tgaimage/jobnameorid) { get; set; } | Ruft Jobname/ID ab oder legt sie fest. |
| [JobTime](../../aspose.imaging.fileformats.tga/tgaimage/jobtime) { get; set; } | Ruft die Auftragszeit ab oder legt sie fest. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| [PixelAspectRatioDenominator](../../aspose.imaging.fileformats.tga/tgaimage/pixelaspectratiodenominator) { get; } | Ruft Pixel-Seitenverhältnis-Nennerteil ab. |
| [PixelAspectRatioNumerator](../../aspose.imaging.fileformats.tga/tgaimage/pixelaspectrationumerator) { get; } | Ruft Pixel-Seitenverhältnis-Zählerteil ab. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Bildkomponenten vormultipliziert werden müssen. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Ruft den benutzerdefinierten Farbkonverter ab oder legt ihn fest |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | Ruft das Rohdatenformat ab. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Ruft die aktuellen Rohdateneinstellungen ab. Beachten Sie, dass bei Verwendung dieser Einstellungen die Daten ohne Konvertierung geladen werden. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Ruft den Fallback-Index ab oder legt ihn fest, der verwendet werden soll, wenn der Palettenindex außerhalb der Grenzen liegt |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Holt oder setzt den indizierten Farbkonverter |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Ruft die rohe Zeilengröße in Bytes ab. |
| [Size](../../aspose.imaging/image/size) { get; } | Ruft die Bildgröße ab. |
| [SoftwareId](../../aspose.imaging.fileformats.tga/tgaimage/softwareid) { get; set; } | Liest oder setzt Software-ID. Insgesamt 40 ASCII-Zeichen für die Software-ID. |
| [SoftwareVersion](../../aspose.imaging.fileformats.tga/tgaimage/softwareversion) { get; set; } | Ruft die Softwareversion ab oder legt sie fest. Die zulässige Länge der Versionszeichenfolge beträgt 3-4 Zeichen. |
| [SoftwareVersionLetter](../../aspose.imaging.fileformats.tga/tgaimage/softwareversionletter) { get; set; } | Abrufen oder Festlegen des Buchstabenteils der Softwareversion. |
| [SoftwareVersionNumber](../../aspose.imaging.fileformats.tga/tgaimage/softwareversionnumber) { get; set; } | Ruft die Software-Versionsnummer ab oder legt sie fest part. |
| override [TransparentColor](../../aspose.imaging.fileformats.tga/tgaimage/transparentcolor) { get; set; } | Ruft Schlüsselfarbe ab oder legt sie fest. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die XMP-Metadaten aktualisiert werden sollen. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Ruft einen Wert ab, der angibt, ob die Bildpalette verwendet wird. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob das Laden von Rohdaten verwendet werden soll, wenn das Laden von Rohdaten verfügbar ist. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | Ermittelt oder setzt die vertikale Auflösung davon in Pixel pro Zoll[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging.fileformats.tga/tgaimage/width) { get; } | Ruft diese Bildbreite ab. |
| virtual [XmpData](../../aspose.imaging/rasterimage/xmpdata) { get; set; } | Ruft die XMP-Metadaten ab oder legt sie fest. |
| [XOrigin](../../aspose.imaging.fileformats.tga/tgaimage/xorigin) { get; set; } | Ermittelt oder setzt die absolute horizontale Koordinate für die untere linke Ecke des Bildes , wie es auf einem Anzeigegerät positioniert ist, dessen Ursprung unten links auf dem -Bildschirm liegt (z. B. die TARGA-Serie). |
| [YOrigin](../../aspose.imaging.fileformats.tga/tgaimage/yorigin) { get; set; } | Ermittelt oder setzt die absolute vertikale Koordinate für die untere linke Ecke des Bildes , wie es auf einem Anzeigegerät positioniert ist, dessen Ursprung unten links auf dem -Bildschirm liegt (z. B. die TARGA-Serie). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [AdjustBrightness](../../aspose.imaging/rastercachedimage/adjustbrightness)(int) | Anpassen einer Helligkeit für das Bild. |
| override [AdjustContrast](../../aspose.imaging/rastercachedimage/adjustcontrast)(float) | Bildkontrast |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float) | Gamma-Korrektur eines Bildes. |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float, float, float) | Gamma-Korrektur eines Bildes. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung des integralen Bildschwellenwerts |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double, int) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung des integralen Bildschwellenwerts |
| override [BinarizeFixed](../../aspose.imaging/rastercachedimage/binarizefixed)(byte) | Binarisierung eines Bildes mit vordefiniertem Schwellwert |
| override [BinarizeOtsu](../../aspose.imaging/rastercachedimage/binarizeotsu)() | Binarisierung eines Bildes mit Otsu-Thresholding |
| override [CacheData](../../aspose.imaging/rastercachedimage/cachedata)() | Zwischenspeichert die Daten und stellt sicher, dass kein zusätzliches Laden von Daten aus der zugrunde liegenden Datei durchgeführt wird[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Legt fest, ob das Bild in dem angegebenen Dateiformat gespeichert werden kann, das durch die übergebenen Speicheroptionen repräsentiert wird. |
| [Clone](../../aspose.imaging.fileformats.tga/tgaimage/clone#clone)() | Erstellt ein neues Objekt, das eine Kopie der aktuellen Instanz ist. |
| [Clone](../../aspose.imaging.fileformats.tga/tgaimage/clone#clone_1)(TgaImage) | Andere klonen[`TgaImage`](../tgaimage) Objekteigenschaften. |
| override [Crop](../../aspose.imaging.fileformats.tga/tgaimage/crop#crop)(Rectangle) | Bild zuschneiden. |
| override [Crop](../../aspose.imaging.fileformats.tga/tgaimage/crop#crop_1)(int, int, int, int) | Bild mit Verschiebungen zuschneiden. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Führt Dithering auf dem aktuellen Bild durch. |
| override [Dither](../../aspose.imaging/rastercachedimage/dither)(DitheringMethod, int, IColorPalette) | Führt Dithering auf dem aktuellen Bild durch. |
| override [Equals](../../aspose.imaging.fileformats.tga/tgaimage/equals#equals_1)(object) | Gleichheitsvergleich. |
| [Equals](../../aspose.imaging.fileformats.tga/tgaimage/equals#equals)(TgaImage) | Gleichheitsvergleich. |
| virtual [Filter](../../aspose.imaging/rasterimage/filter)(Rectangle, FilterOptionsBase) | Filtert das angegebene Rechteck. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Ruft ein 32-Bit-ARGB-Pixelbild ab. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Ruft das standardmäßige 32-Bit-ARGB-Pixel-Array ab. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Ruft die Standardoptionen ab. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Ruft das Standard-Pixel-Array mit partiellem Pixel-Loader ab. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Ruft das Standard-Rohdatenarray ab. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Ruft das Standard-Rohdaten-Array mit partiellem Pixel-Loader ab. |
| override [GetHashCode](../../aspose.imaging.fileformats.tga/tgaimage/gethashcode)() | Holen Sie sich den Hash-Code dieser Instanz. Als Schlüssel nicht geeignet[`TgaImage`](../tgaimage) ist nicht unveränderlich. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Ruft das Datum und die Uhrzeit ab, zu der das Ressourcenbild zuletzt geändert wurde. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Ruft die Optionen basierend auf den ursprünglichen Dateieinstellungen ab. Dies kann hilfreich sein, um die Bittiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz-weißes PNG-Bild mit 1 Bit pro Pixel laden und dann Speichern Sie es mit the [`Save`](../../aspose.imaging/datastreamsupporter/save) -Methode wird das ausgegebene PNG-Bild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und das PNG-Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um entsprechende Speicheroptionen zu erhalten, und übergeben Sie sie an die[`Save`](../../aspose.imaging/image/save) Methode als zweiten Parameter. |
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
| override [Resize](../../aspose.imaging.fileformats.tga/tgaimage/resize#resize_1)(int, int, ImageResizeSettings) | Ändert die Bildgröße. |
| override [Resize](../../aspose.imaging.fileformats.tga/tgaimage/resize#resize_2)(int, int, ResizeType) | Ändert die Bildgröße. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Ändert die Höhe proportional. Der StandardNearestNeighbourResample wird verwendet. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Ändert die Höhe proportional. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Ändert die Höhe proportional. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Ändert die Breite proportional. Der StandardNearestNeighbourResample wird verwendet. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Ändert die Breite proportional. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Ändert die Breite proportional. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Bild um die Mitte drehen. |
| override [Rotate](../../aspose.imaging.fileformats.tga/tgaimage/rotate#rotate_1)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate Bild um die Mitte. |
| override [RotateFlip](../../aspose.imaging.fileformats.tga/tgaimage/rotateflip)(RotateFlipType) | Der Dreh-Flip. |
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
| [operator ==](../../aspose.imaging.fileformats.tga/tgaimage/op_equality) | Gleichheitsvergleich. |
| [operator !=](../../aspose.imaging.fileformats.tga/tgaimage/op_inequality) | Nichtgleichheitsvergleich. |

### Beispiele

Speichern des JPG-Bildes als TGA-Bild.

```csharp
[C#]

using (RasterImage image = (JpegImage)Image.Load("test.jpg"))
{
    image.Save("test.tga"", new TgaOptions());
}
```

Laden des PNG-Bildes, Konvertierung in das TgaImage und Speichern als TGA-Bild.

```csharp
[C#]

using (RasterImage image = (RasterImage)Image.Load("test.png"))
{
    using (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.Save("test.tga");
    }
}
```

Aktualisieren öffentlicher Eigenschaften des geladenen TGA-Bildes.

```csharp
[C#]

using (TgaImage image = (TgaImage)Image.Load("test.tga"))
{
    image.DateTimeStamp = testTime;
    image.AuthorName = "John Smith";
    image.AuthorComments = "Comment";
    image.ImageId = "ImageId";
    image.JobNameOrId = "Important Job";
    image.JobTime = TimeSpan.FromDays(10);
    image.TransparentColor = Color.FromArgb(123);
    image.SoftwareId = "SoftwareId";
    image.SoftwareVersion = "abc1";
    image.SoftwareVersionLetter = 'a';
    image.SoftwareVersionNumber = 2;
    image.XOrigin = 1000;
    image.YOrigin = 1000;

    image.Save("test.tga")
}
```

Abrufen von Werten der öffentlichen Eigenschaften des geladenen TGA-Bildes.

```csharp
[C#]

using (TgaImage image = (TgaImage)Image.Load("test.tga"))
{
    dateTimeStamp = image.DateTimeStamp;
    authorName = image.AuthorName;
    authorComments = image.AuthorComments;
    imageId = image.ImageId;
    jobNameOrId = image.JobNameOrId;
    jobTime = image.JobTime;
    keyColor = image.TransparentColor;
    softwareId = image.SoftwareId;
    softwareVersion = image.SoftwareVersion;
    softwareVersionLetter = image.SoftwareVersionLetter;
    softwareVersionNumber = image.SoftwareVersionNumber;
    xOrigin = image.XOrigin;
    yOrigin = image.YOrigin;
    gammaValueDenominator = image.GammaValueDenominator;
    gammaValueNumerator = image.GammaValueNumerator;
    hasAlphaChannel = image.HasAlpha;
    hasColorMap = image.HasColorMap;
    height = image.Height;
    isGrayScale = image.IsGrayScale;
    pixelAspectRatioDenominator = image.PixelAspectRatioDenominator;
    pixelAspectRatioNumerator = image.PixelAspectRatioNumerator;
    size = image.Size;
    width = image.Width;
}
```

### Siehe auch

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage)
* namensraum [Aspose.Imaging.FileFormats.Tga](../../aspose.imaging.fileformats.tga)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
