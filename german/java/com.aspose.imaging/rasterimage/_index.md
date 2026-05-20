---
title: "RasterImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt ein Rasterbild dar, das Rastergrafik‑Operationen unterstützt."
type: docs
weight: 91
url: /de/java/com.aspose.imaging/rasterimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image)

**All Implemented Interfaces:**
[com.aspose.imaging.IRasterImageArgb32PixelLoader](../../com.aspose.imaging/irasterimageargb32pixelloader), com.aspose.internal.IPixelsSaver, [com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public abstract class RasterImage extends Image implements IRasterImageArgb32PixelLoader, IPixelsSaver, IHasXmpData
```

Stellt ein Rasterbild dar, das Rastergrafik‑Operationen unterstützt.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Liest oder setzt einen Wert, der angibt, ob die Bildkomponenten vorvermultipliziert werden müssen. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Liest oder setzt einen Wert, der angibt, ob die Bildkomponenten vorvermultipliziert werden müssen. |
| [getUseRawData()](#getUseRawData--) | Liest oder setzt einen Wert, der angibt, ob das Laden von Rohdaten verwendet werden soll, wenn das Laden von Rohdaten verfügbar ist. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Liest oder setzt einen Wert, der angibt, ob das Laden von Rohdaten verwendet werden soll, wenn das Laden von Rohdaten verfügbar ist. |
| [getUpdateXmpData()](#getUpdateXmpData--) | Liest oder setzt einen Wert, der angibt, ob die XMP‑Metadaten aktualisiert werden sollen. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Liest oder setzt einen Wert, der angibt, ob die XMP‑Metadaten aktualisiert werden sollen. |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Liest oder setzt den indizierten Farbkonverter |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-) | Liest oder setzt den indizierten Farbkonverter |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Liest oder setzt den benutzerdefinierten Farbkonverter |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.imaging.IColorConverter-) | Liest oder setzt den benutzerdefinierten Farbkonverter |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Liest oder setzt den Ersatzindex, der verwendet wird, wenn der Palettenindex außerhalb des zulässigen Bereichs liegt |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Liest oder setzt den Ersatzindex, der verwendet wird, wenn der Palettenindex außerhalb des zulässigen Bereichs liegt |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [isUsePalette()](#isUsePalette--) | Liefert einen Wert, der angibt, ob die Bildpalette verwendet wird. |
| [getRawDataFormat()](#getRawDataFormat--) | Liest das Rohdatenformat. |
| [getRawLineSize()](#getRawLineSize--) | Liest die Rohzeilengröße in Bytes. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Liest einen Wert, der angibt, ob das Laden von Rohdaten verfügbar ist. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Liest oder setzt die horizontale Auflösung dieses `RasterImage` in Pixel pro Zoll. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Liest oder setzt die horizontale Auflösung dieses `RasterImage` in Pixel pro Zoll. |
| [getVerticalResolution()](#getVerticalResolution--) | Liest oder setzt die vertikale Auflösung dieses `RasterImage` in Pixel pro Zoll. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Liest oder setzt die vertikale Auflösung dieses `RasterImage` in Pixel pro Zoll. |
| [hasTransparentColor()](#hasTransparentColor--) | Liest einen Wert, der angibt, ob diese [RasterImage](../../com.aspose.imaging/rasterimage) Instanz eine transparente Farbe hat. |
| [hasAlpha()](#hasAlpha--) | Gibt einen Wert zurück, der angibt, ob diese Instanz Alpha hat. |
| [getTransparentColor()](#getTransparentColor--) | Liest die transparente Farbe des Bildes. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Setzt einen Wert, der angibt, ob diese [RasterImage](../../com.aspose.imaging/rasterimage) Instanz eine transparente Farbe hat. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Liest die transparente Farbe des Bildes. |
| [getImageOpacity()](#getImageOpacity--) | Ermittelt die Opazität dieses Bildes. |
| [removeMetadata()](#removeMetadata--) | Entfernt die Metadaten dieser Bildinstanz, indem dieser `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) Wert auf `null` gesetzt wird. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Ermittelt das Datum und die Uhrzeit, zu der das Ressourcenbild zuletzt geändert wurde. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | Führt Dithering auf dem aktuellen Bild aus. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Führt Dithering auf dem aktuellen Bild aus. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-) | Liest das Standard-Pixel-Array mit dem partiellen Pixel-Loader. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialRawDataLoader-com.aspose.imaging.RawDataSettings-) | Liest das Standard‑Rohdaten‑Array mit dem partiellen Pixel‑Loader. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.imaging.Rectangle-) | Liest das Standard‑32‑Bit‑ARGB‑Pixel‑Array. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-) | Liest das Standard‑Rohdaten‑Array. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Liest ein 32‑Bit‑ARGB‑Pixel eines Bildes. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Liest ein Bildpixel. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Setzt ein 32‑Bit‑ARGB‑Pixel des Bildes für die angegebene Position. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.imaging.Color-) | Setzt ein Bildpixel für die angegebene Position. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Liest die gesamte Scan‑Zeile anhand des angegebenen Scan‑Zeilen‑Index. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Liest die gesamte Scan‑Zeile anhand des angegebenen Scan‑Zeilen‑Index. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.imaging.Color---) | Schreibt die gesamte Scan‑Zeile an den angegebenen Scan‑Zeilen‑Index. |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Schreibt die gesamte Scan‑Zeile an den angegebenen Scan‑Zeilen‑Index. |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-) | Lädt 32‑Bit‑ARGB‑Pixel partiell nach Paketen. |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-) | Lädt Pixel partiell nach Paketen. |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.imaging.Rectangle-) | Lädt 32‑Bit‑ARGB‑Pixel. |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.imaging.Rectangle-) | Lädt 64‑Bit‑ARGB‑Pixel. |
| [loadPartialArgb64Pixels(Rectangle rectangle, IPartialArgb64PixelLoader partialPixelLoader)](#loadPartialArgb64Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb64PixelLoader-) | Lädt 64‑Bit‑ARGB‑Pixel partiell nach Paketen. |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.imaging.Rectangle-) | Lädt Pixel. |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.imaging.Rectangle-) | Lädt Pixel im CMYK‑Format. |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.imaging.Rectangle-) | Lädt Pixel im CMYK‑Format. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-) | Lädt Rohbilddaten mit dem partiellen Verarbeitungsmechanismus. |
| [loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-) | Lädt Rohdaten. |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-) | Speichert die Rohdaten. |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.imaging.Rectangle-int---) | Speichert die 32‑Bit‑ARGB‑Pixel. |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.imaging.Rectangle-com.aspose.imaging.Color---) | Speichert die Pixel. |
| [toBitmap()](#toBitmap--) | Konvertiert Rasterbild in das Bitmap. |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.CmykColor---) | Speichert die Pixel. |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.imaging.Rectangle-int---) | Speichert die Pixel. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Setzt die Auflösung für dieses `RasterImage`. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Legt die Bildpalette fest. |
| [autoRotate()](#autoRotate--) | Dreht das Bild automatisch basierend auf Orientierungsdaten, die aus Exif-Metadaten extrahiert wurden. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Skaliert das Bild mit erweiterten Optionen. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Bild um die Mitte drehen. |
| [rotate(float angle)](#rotate-float-) | Bild um die Mitte drehen. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarisierung eines Bildes mit vordefiniertem Schwellenwert |
| [binarizeOtsu()](#binarizeOtsu--) | Binarisierung eines Bildes mit Otsu-Schwellenwertbestimmung |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Binarisierung eines Bildes mittels Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild-Schwellenwertbestimmung |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarisierung eines Bildes mittels Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild-Schwellenwertbestimmung |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-) | Mischt diese Bildinstanz mit dem `overlay`-Bild. |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | Mischt diese Bildinstanz mit dem `overlay`-Bild. |
| [blend(Point origin, RasterImage overlay)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-) | Mischt diese Bildinstanz mit dem `overlay` bei Alpha == 255. |
| [blend(Point origin, RasterImage overlay, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-byte-) | Mischt diese Bildinstanz mit dem `overlay`. |
| [grayscale()](#grayscale--) | Transformation eines Bildes in seine Graustufen-Darstellung |
| [normalizeHistogram()](#normalizeHistogram--) | Normalisiert das Bildhistogramm \\u2014 passt Pixelwerte an, um den gesamten verfügbaren Bereich zu nutzen. |
| [autoBrightnessContrast()](#autoBrightnessContrast--) | Automatische adaptive Helligkeits- und Kontrastnormalisierung für das gesamte Bild. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Anpassung der Helligkeit des Bildes. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Bildkontrastierung |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | Betten Sie ein digitales Signatur basierend auf dem bereitgestellten Passwort in das Bild ein, mittels Steganographie. |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | Berechnet den prozentualen Ähnlichkeitswert zwischen den extrahierten Daten und dem ursprünglichen Passwort. |
| [isDigitalSigned(String password)](#isDigitalSigned-java.lang.String-) | Führt eine schnelle Prüfung durch, um festzustellen, ob das Bild digital signiert ist, unter Verwendung des bereitgestellten Passworts und Schwellenwerts. |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | Führt eine schnelle Prüfung durch, um festzustellen, ob das Bild digital signiert ist, unter Verwendung des bereitgestellten Passworts und Schwellenwerts. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Gammakorrektur eines Bildes. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Gammakorrektur eines Bildes. |
| [getSkewAngle()](#getSkewAngle--) | Ermittelt den Schrägstellungswinkel. |
| [normalizeAngle()](#normalizeAngle--) | Normalisiert den Winkel. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | Normalisiert den Winkel. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Filtert das angegebene Rechteck. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.imaging.Color-byte-com.aspose.imaging.Color-) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.imaging.Color-) | Ersetzt alle nicht-transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Ersetzt alle nicht-transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |

## Example: This example shows how to load pixel information in an array of colors, manipulates the array and set it back to the image.

``` java
String dir = "c:\\temp\\";

// Erstelle eine Instanz von GifOptions und setze deren verschiedene Eigenschaften, einschließlich der Source-Eigenschaft
com.aspose.imaging.imageoptions.GifOptions gifOptions = new com.aspose.imaging.imageoptions.GifOptions();
gifOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "output.gif", false));

// Erstelle eine Instanz von Image
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(gifOptions, 500, 500);
try {
    // Hole die Pixel des Bildes, indem du den Bereich als Bildgrenze angibst
    com.aspose.imaging.Color[] pixels = image.loadPixels(image.getBounds());

    // Durchlaufe das Array und setze die Farbe des alternierenden indizierten Pixels
    for (int index = 0; index < pixels.length; index++) {
        if (index % 2 == 0) {
            // Setze die Farbe des indizierten Pixels auf Gelb
            pixels[index] = com.aspose.imaging.Color.getYellow();
        } else {
            // Setze die Farbe des indizierten Pixels auf Blau
            pixels[index] = com.aspose.imaging.Color.getBlue();
        }
    }

    // Wende die Pixeländerungen auf das Bild an
    image.savePixels(image.getBounds(), pixels);

    // Speichere alle Änderungen.
    image.save();
} finally {
    image.dispose();
}
```

### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Liest oder setzt einen Wert, der angibt, ob die Bildkomponenten vorvermultipliziert werden müssen.

**Returns:**
boolean - `true`, wenn die Bildkomponenten vormultipliziert werden müssen; andernfalls `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob die Bildkomponenten vorvermultipliziert werden müssen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | `true`, wenn die Bildkomponenten vormultipliziert werden müssen; andernfalls `false`. |


**Example: The following example creates a new raster image, saves the specified semi-transparent pixels, then loads those pixels and gets final colors in the premultiplied form.**

``` java
int imageWidth = 3;
int imageHeight = 2;

com.aspose.imaging.Color[] colors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 0, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 255, 255, 0),
                com.aspose.imaging.Color.fromArgb(127, 255, 0, 255),
                com.aspose.imaging.Color.fromArgb(127, 0, 255, 255),
        };

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new com.aspose.imaging.system.io.MemoryStream(), true));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);

com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, imageWidth, imageHeight);
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Pixel für das gesamte Bild speichern.
    rasterImage.savePixels(rasterImage.getBounds(), colors);

    // Die Pixel werden im Originalbild in nicht vormultiplizierter Form gespeichert.
    // Die entsprechende Option muss explizit angegeben werden, um vormultiplizierte Farbkomponenten zu erhalten.
    // Die vormultiplizierten Farbkomponenten werden mit den Formeln berechnet:
    // red = original_red * alpha / 255;
    // green = original_green * alpha / 255;
    // blue = original_blue * alpha / 255;
    rasterImage.setPremultiplyComponents(true);
    com.aspose.imaging.Color[] premultipliedColors = rasterImage.loadPixels(rasterImage.getBounds());

    for (int i = 0; i < colors.length; i++) {
        System.out.println("Original color: " + colors[i].toString());
        System.out.println("Premultiplied color: " + premultipliedColors[i].toString());
    }
} finally {
    image.dispose();
}
```

### getUseRawData() {#getUseRawData--}
```
public boolean getUseRawData()
```


Liest oder setzt einen Wert, der angibt, ob das Laden von Rohdaten verwendet werden soll, wenn das Laden von Rohdaten verfügbar ist.

**Returns:**
boolean - `true`, wenn Rohdaten geladen werden sollen, wenn das Laden von Rohdaten verfügbar ist; andernfalls `false`.
### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob das Laden von Rohdaten verwendet werden soll, wenn das Laden von Rohdaten verfügbar ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | `true`, wenn Rohdaten geladen werden sollen, wenn das Laden von Rohdaten verfügbar ist; andernfalls `false`. |

### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


Liest oder setzt einen Wert, der angibt, ob die XMP‑Metadaten aktualisiert werden sollen.

**Returns:**
boolean - `true`, wenn die XMP-Metadaten aktualisiert werden sollen; andernfalls `false`.
### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob die XMP‑Metadaten aktualisiert werden sollen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | `true`, wenn die XMP-Metadaten aktualisiert werden sollen; andernfalls `false`. |

### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


Liest oder setzt den indizierten Farbkonverter

**Returns:**
[IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) - The indexed color converter
### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


Liest oder setzt den indizierten Farbkonverter

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) | Der indizierte Farbkonverter |

### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


Liest oder setzt den benutzerdefinierten Farbkonverter

**Returns:**
[IColorConverter](../../com.aspose.imaging/icolorconverter) - The custom color converter
### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.imaging.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


Liest oder setzt den benutzerdefinierten Farbkonverter

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.imaging/icolorconverter) | Der benutzerdefinierte Farbkonverter |

### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


Liest oder setzt den Ersatzindex, der verwendet wird, wenn der Palettenindex außerhalb des zulässigen Bereichs liegt

**Returns:**
int - Der Ausweichindex, der verwendet wird, wenn der Palettenindex außerhalb des Bereichs liegt
### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


Liest oder setzt den Ersatzindex, der verwendet wird, wenn der Palettenindex außerhalb des zulässigen Bereichs liegt

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Der Ausweichindex, der verwendet wird, wenn der Palettenindex außerhalb des Bereichs liegt |

### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


Ermittelt die aktuellen Rohdaten-Einstellungen. Hinweis: Beim Verwenden dieser Einstellungen werden die Daten ohne Konvertierung geladen.

**Returns:**
[RawDataSettings](../../com.aspose.imaging/rawdatasettings)
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Liefert einen Wert, der angibt, ob die Bildpalette verwendet wird.

Wert: `true`, wenn die Palette im Bild verwendet wird; andernfalls `false`.

**Returns:**
boolean – ein Wert, der angibt, ob die Bildpalette verwendet wird.
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Liest das Rohdatenformat.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.

**Example: The following example loads raster images and prints information about raw data format and alpha channel.**

``` java

// Die Bilddateien zum Laden.
String[] fileNames = new String[]
        {
                "c:\\temp\\sample.bmp",
                "c:\\temp\\alpha.png",
        };

for (String fileName : fileNames) {
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
    try {
        com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
        System.out.println(
                "ImageFile=" + fileName +
                        " FileFormat=" + rasterImage.getRawDataFormat() +
                        " HasAlpha=" + rasterImage.hasAlpha());
    } finally {
        image.dispose();
    }
}

// Die Ausgabe könnte so aussehen:
// ImageFile=c:\temp\sample.bmp FileFormat=Rgb24Bpp, verwendete Kanäle: 8,8,8 HasAlpha=false
// ImageFile=c:\temp\alpha.png FileFormat=RGBA32Bpp, verwendete Kanäle: 8,8,8,8 HasAlpha=true
```

### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Liest die Rohzeilengröße in Bytes.

**Returns:**
int - Die Rohzeilengröße in Bytes.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


Liest einen Wert, der angibt, ob das Laden von Rohdaten verfügbar ist.

**Returns:**
boolean - `true`, wenn dieses Laden von Rohdaten verfügbar ist; andernfalls `false`.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Liest oder setzt die horizontale Auflösung dieses `RasterImage` in Pixel pro Zoll.

**Returns:**
double - Die horizontale Auflösung.

Hinweis: Standardmäßig hat dieser Wert immer 96, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie können in Erwägung ziehen, die SetResolution-Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.

**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Horizontale und vertikale Auflösung des Bildes abrufen
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Verwenden Sie die SetResolution-Methode, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // Die Ausgabe könnte so aussehen:
    // Die horizontale Auflösung, in Pixel pro Zoll: 300.0
    // Die vertikale Auflösung, in Pixel pro Zoll: 300.0
    // Auflösungswerte auf 96 dpi setzen
    // Die horizontale Auflösung, in Pixel pro Zoll: 96.0
    // Die vertikale Auflösung, in Pixel pro Zoll: 96.0
} finally {
    image.dispose();
}
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Liest oder setzt die horizontale Auflösung dieses `RasterImage` in Pixel pro Zoll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die horizontale Auflösung. |

Hinweis: Standardmäßig hat dieser Wert immer 96, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie können in Erwägung ziehen, die SetResolution-Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Liest oder setzt die vertikale Auflösung dieses `RasterImage` in Pixel pro Zoll.

**Returns:**
double - Die vertikale Auflösung.

Hinweis: Standardmäßig hat dieser Wert immer 96, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie können in Erwägung ziehen, die SetResolution-Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.

**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Horizontale und vertikale Auflösung des Bildes abrufen
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Verwenden Sie die SetResolution-Methode, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // Die Ausgabe könnte so aussehen:
    // Die horizontale Auflösung, in Pixel pro Zoll: 300.0
    // Die vertikale Auflösung, in Pixel pro Zoll: 300.0
    // Auflösungswerte auf 96 dpi setzen
    // Die horizontale Auflösung, in Pixel pro Zoll: 96.0
    // Die vertikale Auflösung, in Pixel pro Zoll: 96.0
} finally {
    image.dispose();
}
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Liest oder setzt die vertikale Auflösung dieses `RasterImage` in Pixel pro Zoll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Die vertikale Auflösung. |

Hinweis: Standardmäßig hat dieser Wert immer 96, da verschiedene Plattformen die Bildschirmauflösung nicht zurückgeben können. Sie können in Erwägung ziehen, die SetResolution-Methode zu verwenden, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren. |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Liest einen Wert, der angibt, ob diese [RasterImage](../../com.aspose.imaging/rasterimage) Instanz eine transparente Farbe hat.

--------------------

Die Basisimplementierung gibt effektiv `` zurück, wenn sie nicht in einer spezifischen Implementierung, die dieses Feature unterstützt, überschrieben wird. Diese Eigenschaft wird hauptsächlich von [FileFormat.Apng](../../com.aspose.imaging/fileformat\#Apng), [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png), [FileFormat.Gif](../../com.aspose.imaging/fileformat\#Gif), [FileFormat.Tga](../../com.aspose.imaging/fileformat\#Tga) verwendet, um eine transparente Farbe festzulegen, falls ein Bild Transparenz über den Alphakanal nicht unterstützt.

**Returns:**
boolean - ein Wert, der angibt, ob diese [RasterImage](../../com.aspose.imaging/rasterimage)-Instanz eine transparente Farbe hat.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Gibt einen Wert zurück, der angibt, ob diese Instanz Alpha hat.

**Returns:**
boolean - `true`, wenn diese Instanz Alpha hat; andernfalls `false`.

**Example: The following example loads raster images and prints information about raw data format and alpha channel.**

``` java

// Die Bilddateien zum Laden.
String[] fileNames = new String[]
        {
                "c:\\temp\\sample.bmp",
                "c:\\temp\\alpha.png",
        };

for (String fileName : fileNames) {
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
    try {
        com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
        System.out.println(
                "ImageFile=" + fileName +
                        " FileFormat=" + rasterImage.getRawDataFormat() +
                        " HasAlpha=" + rasterImage.hasAlpha());
    } finally {
        image.dispose();
    }
}

// Die Ausgabe könnte so aussehen:
// ImageFile=c:\temp\sample.bmp FileFormat=Rgb24Bpp, verwendete Kanäle: 8,8,8 HasAlpha=false
// ImageFile=c:\temp\alpha.png FileFormat=RGBA32Bpp, verwendete Kanäle: 8,8,8,8 HasAlpha=true
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Liest die transparente Farbe des Bildes.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Setzt einen Wert, der angibt, ob diese [RasterImage](../../com.aspose.imaging/rasterimage) Instanz eine transparente Farbe hat.

--------------------

Die Basisimplementierung gibt effektiv `` zurück, wenn sie nicht in einer spezifischen Implementierung, die dieses Feature unterstützt, überschrieben wird. Diese Eigenschaft wird hauptsächlich von [FileFormat.Apng](../../com.aspose.imaging/fileformat\#Apng), [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png), [FileFormat.Gif](../../com.aspose.imaging/fileformat\#Gif), [FileFormat.Tga](../../com.aspose.imaging/fileformat\#Tga) verwendet, um eine transparente Farbe festzulegen, falls ein Bild Transparenz über den Alphakanal nicht unterstützt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean | ein Wert, der angibt, ob diese [RasterImage](../../com.aspose.imaging/rasterimage)-Instanz eine transparente Farbe hat. |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Liest die transparente Farbe des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Ermittelt die Opazität dieses Bildes.

**Returns:**
float - Der Deckkraftwert zwischen 0.0 (vollständig transparent) und 1.0 (vollständig undurchsichtig).
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Entfernt die Metadaten dieser Bildinstanz, indem dieser `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) Wert auf `null` gesetzt wird.

### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Ruft Datum und Uhrzeit ab, zu der das Ressourcenbild zuletzt geändert wurde. Diese Methode liefert wertvolle Metadaten, die es Benutzern ermöglichen, Aktualisierungen der Bilddatei effektiv zu verfolgen und zu verwalten. Durch den Zugriff auf diese Informationen können Benutzer die Integrität und Aktualität ihrer Bildressourcen sicherstellen und fundierte Entscheidungen bezüglich der Bildnutzung und -wartung treffen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| useDefault | boolean | Wenn auf `true` gesetzt, verwendet es die Informationen aus FileInfo als Standardwert. |

**Returns:**
java.util.Date - Das Datum und die Uhrzeit, zu der das Ressourcenbild zuletzt geändert wurde.
### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


Führt Dithering auf dem aktuellen Bild aus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ditheringMethod | int | Die Dithering-Methode. |
| bitsCount | int | Die endgültige Bitanzahl für Dithering. |


**Example: The following example loads a raster image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Führen Sie Schwellenwert-Dithering mit einer 4‑Bit-Farbpalette durch, die 16 Farben enthält.
    // Je mehr Bits angegeben werden, desto höher die Qualität und desto größer die Größe des Ausgabebildes.
    // Beachten Sie, dass derzeit nur 1‑Bit-, 4‑Bit- und 8‑Bit-Paletten unterstützt werden.
    rasterImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.save(dir + "sample.ThresholdDithering4.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Führen Sie Floyd-Dithering mit einer 1‑Bit-Farbpalette durch, die nur 2 Farben enthält – Schwarz und Weiß.
    // Je mehr Bits angegeben werden, desto höher die Qualität und desto größer die Größe des Ausgabebildes.
    // Beachten Sie, dass derzeit nur 1‑Bit-, 4‑Bit- und 8‑Bit-Paletten unterstützt werden.
    rasterImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1);

    rasterImage.save(dir + "sample.FloydSteinbergDithering1.png");
} finally {
    image.dispose();
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public abstract void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Führt Dithering auf dem aktuellen Bild aus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ditheringMethod | int | Die Dithering-Methode. |
| bitsCount | int | Die endgültige Bitanzahl für Dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die benutzerdefinierte Palette für Dithering. |

### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Liest das Standard-Pixel-Array mit dem partiellen Pixel-Loader.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck, für das Pixel abgerufen werden sollen. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader) | Der partielle Pixel‑Lader. |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialRawDataLoader-com.aspose.imaging.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


Liest das Standard‑Rohdaten‑Array mit dem partiellen Pixel‑Loader.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck, für das Pixel abgerufen werden sollen. |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | Der partielle Rohdaten-Lader. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Die Rohdaten-Einstellungen. |

### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


Liest das Standard‑32‑Bit‑ARGB‑Pixel‑Array.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck, für das Pixel abgerufen werden sollen. |

**Returns:**
int[] - Das Standard-Pixel-Array.
### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


Liest das Standard‑Rohdaten‑Array.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck, für das Rohdaten abgerufen werden sollen. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Die Rohdaten-Einstellungen. |

**Returns:**
byte[] - Das Standard‑Rohdaten‑Array.
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


Liest ein 32‑Bit‑ARGB‑Pixel eines Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x‑Position des Pixels. |
| y | int | Die y‑Position des Pixels. |

**Returns:**
int - Das 32‑Bit‑ARGB‑Pixel für die angegebene Position.

**Example: The following example loads a raster image and obtains the color of an arbitrary pixel represented as a 32-bit integer value.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Erhalte eine ganzzahlige Darstellung der Farbe des oberen linken Pixels des Bildes.
    int color = rasterImage.getArgb32Pixel(0, 0);

    // Um die Werte der einzelnen Farbkomponenten zu erhalten, verschiebe den Farbwert um die entsprechende Anzahl von Bits.
    int alpha = (color >> 24) & 0xff;
    int red = (color >> 16) & 0xff;
    int green = (color >> 8) & 0xff;
    int blue = (color >> 0) & 0xff;

    System.out.println("The color of the pixel(0,0) is A=" + alpha + ",R=" + red + ",G=" + green + ",B=" + blue);
} finally {
    image.dispose();
}

// Die Ausgabe könnte so aussehen:
// Die Farbe des Pixels(0,0) ist A=255,R=0,G=0,B=0.
```

### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


Liest ein Bildpixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x‑Position des Pixels. |
| y | int | Die y‑Position des Pixels. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The pixel color for the specified location.

**Example: The following example loads a raster image and obtains the color of an arbitrary pixel.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Erhalte die Farbe des oberen linken Pixels des Bildes.
    com.aspose.imaging.Color color = rasterImage.getPixel(0, 0);

    // Erhalte die Werte der einzelnen Farbkomponenten.
    int alpha = color.getA();
    int red = color.getR();
    int green = color.getG();
    int blue = color.getB();

    System.out.println("The color of the pixel(0,0) is A=" + alpha + ",R=" + red + ",G=" + green + ",B=" + blue);
} finally {
    image.dispose();
}
```

### setArgb32Pixel(int x, int y, int argb32Color) {#setArgb32Pixel-int-int-int-}
```
public void setArgb32Pixel(int x, int y, int argb32Color)
```


Setzt ein 32‑Bit‑ARGB‑Pixel des Bildes für die angegebene Position.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x‑Position des Pixels. |
| y | int | Die y‑Position des Pixels. |
| argb32Color | int | Das 32‑Bit‑ARGB‑Pixel für die angegebene Position. |


**Example: The following example loads a raster image, and sets the color of an arbitrary pixel.**

``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Setzt die Farbe des oberen linken Pixels.
    rasterImage.setArgb32Pixel(0, 0, com.aspose.imaging.Color.getAqua().toArgb());

    // Eine andere Möglichkeit besteht darin, eine Instanz von com.aspose.imaging.Color direkt zu übergeben.
    rasterImage.setPixel(0, 0, com.aspose.imaging.Color.getAqua());
} finally {
    image.dispose();
}
```

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.imaging.Color-}
```
public void setPixel(int x, int y, Color color)
```


Setzt ein Bildpixel für die angegebene Position.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | int | Die x‑Position des Pixels. |
| y | int | Die y‑Position des Pixels. |
| color | [Color](../../com.aspose.imaging/color) | Die Pixel­farbe für die angegebene Position. |


**Example: The following example loads a raster image, and sets the color of an arbitrary pixel.**

``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Setzt die Farbe des oberen linken Pixels.
    rasterImage.setArgb32Pixel(0, 0, com.aspose.imaging.Color.getAqua().toArgb());

    // Eine andere Möglichkeit besteht darin, eine Instanz von com.aspose.imaging.Color direkt zu übergeben.
    rasterImage.setPixel(0, 0, com.aspose.imaging.Color.getAqua());
} finally {
    image.dispose();
}
```

### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


Liest die gesamte Scan‑Zeile anhand des angegebenen Scan‑Zeilen‑Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scanLineIndex | int | Nullbasierter Index der Scan‑Zeile. |

**Returns:**
com.aspose.imaging.Color[] - Das Array der Pixel­farbwerte der Scan‑Zeile.
### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


Liest die gesamte Scan‑Zeile anhand des angegebenen Scan‑Zeilen‑Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scanLineIndex | int | Nullbasierter Index der Scan‑Zeile. |

**Returns:**
int[] - Das Array der 32‑Bit‑ARGB‑Farbwerte der Scan‑Zeile.
### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.imaging.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


Schreibt die gesamte Scan‑Zeile an den angegebenen Scan‑Zeilen‑Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scanLineIndex | int | Nullbasierter Index der Scan‑Zeile. |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | Das Pixel­farben‑Array zum Schreiben. |

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


Schreibt die gesamte Scan‑Zeile an den angegebenen Scan‑Zeilen‑Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scanLineIndex | int | Nullbasierter Index der Scan‑Zeile. |
| argb32Pixels | int[] | Das 32‑Bit‑ARGB‑Farben‑Array zum Schreiben. |

### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Lädt 32‑Bit‑ARGB‑Pixel partiell nach Paketen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das gewünschte Rechteck. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader) | Der 32‑Bit‑ARGB‑Pixel‑Lader. |


**Example: The following example shows how to load and process pixels of a raster image using your own partial processor.**
Das folgende Beispiel zeigt, wie man Pixel eines Raster‑Bildes mit einem eigenen Teil‑Prozessor lädt und verarbeitet. Zum Beispiel betrachtet man das Problem, vollständig transparente Pixel eines Bildes zu zählen. Um transparente Pixel mithilfe des Teil‑Lade‑Mechanismus zu zählen, wird eine separate Klasse TransparentArgb32PixelCounter eingeführt, die com.aspose.imaging.IPartialArgb32PixelLoader implementiert.
``` java

// Zuerst implementieren Sie com.aspose.imaging.IPartialArgb32PixelLoader, um alle vollständig transparenten Pixel zu zählen.
/** Counts the number of fully transparent pixels with alpha channel value of 0. */
class TransparentArgb32PixelCounter implements com.aspose.imaging.IPartialArgb32PixelLoader {
    /**
     * The number of fully transparent pixels.
     */
    private int count;

    /**
     * Gets the number of fully transparent pixels.
     */
    public int getCount() {
        return this.count;
    }

    /**
     * <p>Processes the loaded pixels. This method is called back every time when a new portion of pixels is loaded.</p>                 *
     *
     * @param pixelsRectangle The pixels rectangle.
     * @param pixels          The 32-bit ARGB pixels.
     * @param start           The start pixels point.
     * @param end             The end pixels point.
     */
    public void process(com.aspose.imaging.Rectangle pixelsRectangle, int[] pixels, com.aspose.imaging.Point start, com.aspose.imaging.Point end) {
        for (int pixel : pixels) {
            int alpha = (pixel >> 24) & 0xff;
            if (alpha == 0) {
                this.count++;
            }
        }
    }
}

// Hier ist ein Beispiel für die Verwendung des Zählers.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Erstellen Sie eine Instanz von com.aspose.imaging.IPartialArgb32PixelLoader und übergeben Sie sie an com.aspose.imaging.RasterImage.LoadPartialArgb32Pixels
    TransparentArgb32PixelCounter counter = new TransparentArgb32PixelCounter();

    // Laden Sie Pixel für das gesamte Bild. Jeder rechteckige Teil des Bildes kann als erster Parameter der Methode com.aspose.imaging.RasterImage.loadPartialArgb32Pixels angegeben werden.
    rasterImage.loadPartialArgb32Pixels(rasterImage.getBounds(), counter);

    System.out.println("The number of fully transparent pixels is " + counter.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// Die Ausgabe könnte so aussehen:
// Die Anzahl der vollständig transparenten Pixel beträgt 55157
// Die Gesamtzahl der Pixel beträgt 120400
```

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


Lädt Pixel partiell nach Paketen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das gewünschte Rechteck. |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.imaging/ipartialpixelloader) | Der Pixel-Lader. |


**Example: The following example shows how to load and process pixels of a raster image using your own partial processor.**
Das folgende Beispiel zeigt, wie man Pixel eines Rasterbildes mit Ihrem eigenen Teilprozessor lädt und verarbeitet. Zum Beispiel betrachten Sie ein Problem der Zählung vollständig transparenter Pixel eines Bildes. Um transparente Pixel mithilfe des Teil‑Lade‑Mechanismus zu zählen, wird eine separate Klasse TransparentPixelCounter, die com.aspose.imaging.IPartialPixelLoader implementiert, eingeführt.
``` java

// Zuerst implementieren Sie com.aspose.imaging.IPartialPixelLoader, um alle vollständig transparenten Pixel zu zählen.
/** Counts the number of fully transparent pixels with alpha channel value of 0. */
class TransparentPixelCounter implements com.aspose.imaging.IPartialPixelLoader {
    /**
     * The number of fully transparent pixels.
     */
    private int count;

    /**
     * Gets the number of fully transparent pixels.
     */
    public int getCount() {
        return this.count;
    }

    /**
     * <p>Processes the loaded pixels. This method is called back every time when a new portion of pixels is loaded.</p>
     *
     * @param pixelsRectangle The pixels rectangle.
     * @param pixels          The 32-bit ARGB pixels.
     * @param start           The start pixels point.
     * @param end             The end pixels point.
     */
    public void process(com.aspose.imaging.Rectangle pixelsRectangle, com.aspose.imaging.Color[] pixels, com.aspose.imaging.Point start, com.aspose.imaging.Point end) {
        for (com.aspose.imaging.Color pixel : pixels) {
            if (pixel.getA() == 0) {
                this.count++;
            }
        }
    }
}

// Hier ist ein Beispiel für die Verwendung des Zählers.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Erstellen Sie eine Instanz von com.aspose.imaging.IPartialPixelLoader und übergeben Sie sie an com.aspose.imaging.RasterImage.loadPartialPixels
    TransparentPixelCounter counter = new TransparentPixelCounter();

    // Laden Sie Pixel für das gesamte Bild. Jeder rechteckige Teil des Bildes kann als erster Parameter der Methode com.aspose.imaging.RasterImage.loadPartialPixels angegeben werden.
    rasterImage.loadPartialPixels(rasterImage.getBounds(), counter);

    System.out.println("The number of fully transparent pixels is " + counter.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// Die Ausgabe könnte so aussehen:
// Die Anzahl der vollständig transparenten Pixel beträgt 55157
// Die Gesamtzahl der Pixel beträgt 120400
```

### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


Lädt 32‑Bit‑ARGB‑Pixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck, aus dem Pixel geladen werden sollen. |

**Returns:**
int[] – Das geladene 32‑Bit‑ARGB‑Pixel‑Array.

**Example: The following example shows how to load and process pixels of a raster image.**
Das folgende Beispiel zeigt, wie man Pixel eines Rasterbildes lädt und verarbeitet. Die Pixel werden als 32‑Bit‑Ganzzahlwerte dargestellt. Zum Beispiel betrachten Sie ein Problem der Zählung vollständig transparenter Pixel eines Bildes.
``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Laden Sie Pixel für das gesamte Bild. Jeder rechteckige Teil des Bildes kann als Parameter der Methode com.aspose.imaging.RasterImage.loadArgb32Pixels angegeben werden.
    int[] pixels = rasterImage.loadArgb32Pixels(rasterImage.getBounds());

    int count = 0;
    for (int pixel : pixels) {
        int alpha = (pixel >> 24) & 0xff;
        if (alpha == 0) {
            count++;
        }
    }

    System.out.println("The number of fully transparent pixels is " + count);
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}
```

### loadArgb64Pixels(Rectangle rectangle) {#loadArgb64Pixels-com.aspose.imaging.Rectangle-}
```
public long[] loadArgb64Pixels(Rectangle rectangle)
```


Lädt 64‑Bit‑ARGB‑Pixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck, aus dem Pixel geladen werden sollen. |

**Returns:**
long[] – Das geladene 64‑Bit‑ARGB‑Pixel‑Array.

**Example: The following example shows how to load and process pixels of a raster image.**
Das folgende Beispiel zeigt, wie man Pixel eines Rasterbildes lädt und verarbeitet. Die Pixel werden als 64‑Bit‑Ganzzahlwerte dargestellt. Zum Beispiel betrachten Sie ein Problem der Zählung vollständig transparenter Pixel eines Bildes.
``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\16rgba.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Laden Sie Pixel für das gesamte Bild. Jeder rechteckige Teil des Bildes kann als Parameter der Methode com.aspose.imaging.RasterImage.loadArgb64Pixels angegeben werden.
    // Beachten Sie, dass das Bild selbst 16 Bit pro Sample haben muss, da com.aspose.imaging.RasterImage.loadArgb64Pixels nicht mit 8 Bit pro Sample funktioniert.
    // Um mit 8 Bit pro Sample zu arbeiten, verwenden Sie bitte die bewährte Methode com.aspose.imaging.RasterImage.loadArgb32Pixels.
    long[] pixels = rasterImage.loadArgb64Pixels(rasterImage.getBounds());

    int count = 0;
    for (long pixel : pixels) {
        // Beachten Sie, dass alle Farbkomponenten einschließlich Alpha durch 16‑Bit‑Werte dargestellt werden, sodass ihre zulässigen Werte im Bereich [0, 63535] liegen.
        long alpha = (pixel >> 48) & 0xffff;
        if (alpha == 0) {
            count++;
        }
    }

    System.out.println("The number of fully transparent pixels is " + count);
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}
```

### loadPartialArgb64Pixels(Rectangle rectangle, IPartialArgb64PixelLoader partialPixelLoader) {#loadPartialArgb64Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb64PixelLoader-}
```
public final void loadPartialArgb64Pixels(Rectangle rectangle, IPartialArgb64PixelLoader partialPixelLoader)
```


Lädt 64‑Bit‑ARGB‑Pixel partiell nach Paketen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das gewünschte Rechteck. |
| partialPixelLoader | [IPartialArgb64PixelLoader](../../com.aspose.imaging/ipartialargb64pixelloader) | Der 64‑Bit‑ARGB‑Pixel‑Lader. |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.imaging.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


Lädt Pixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck, aus dem Pixel geladen werden sollen. |

**Returns:**
com.aspose.imaging.Color[] – Das geladene Pixel‑Array.

**Example: The following example shows how to load and process pixels of a raster image.**
Das folgende Beispiel zeigt, wie man Pixel eines Rasterbildes lädt und verarbeitet. Zum Beispiel betrachten Sie ein Problem der Zählung vollständig transparenter Pixel eines Bildes.
``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Laden Sie Pixel für das gesamte Bild. Jeder rechteckige Teil des Bildes kann als Parameter der Methode Aspose.Imaging.RasterImage.LoadPixels angegeben werden.
    com.aspose.imaging.Color[] pixels = rasterImage.loadPixels(rasterImage.getBounds());

    int count = 0;
    for (com.aspose.imaging.Color pixel : pixels) {
        if (pixel.getA() == 0) {
            count++;
        }
    }

    System.out.println("The number of fully transparent pixels is " + count);
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}
```

### loadCmykPixels(Rectangle rectangle) {#loadCmykPixels-com.aspose.imaging.Rectangle-}
```
public CmykColor[] loadCmykPixels(Rectangle rectangle)
```


Lädt Pixel im CMYK‑Format. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere Methode `loadCmyk32Pixels(Rectangle)`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck, aus dem Pixel geladen werden sollen. |

**Returns:**
com.aspose.imaging.CmykColor[] - Das geladene CMYK-Pixel-Array.
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


Lädt Pixel im CMYK‑Format.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck, aus dem Pixel geladen werden sollen. |

**Returns:**
int[] - Die geladenen CMYK-Pixel werden als 32‑Bit‑Ganzzahlen dargestellt.
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Lädt Rohbilddaten mit dem partiellen Verarbeitungsmechanismus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Der gewünschte rechteckige Bereich des Bildes, aus dem Daten geladen werden sollen. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Die Rohdaten-Einstellungen. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | Der Rohdaten‑Lader. |


**Example: The following example shows how to extract pixels from the raw image data using RawDataSettings.**
Das folgende Beispiel zeigt, wie man Pixel aus den Rohbilddaten mit RawDataSettings extrahiert. Zum Beispiel, betrachten Sie ein Problem beim Zählen vollständig transparenter Pixel eines Bildes.
``` java

// Zuerst implementieren Sie einen Zähler. Im Fall von Rohdaten könnte der Zähler so aussehen:
/** Counts the number of fully transparent pixels with alpha channel value of 0. */
class TransparentPixelRawDataCounter implements com.aspose.imaging.IPartialRawDataLoader {
    /**
     * The number of fully transparent pixels.
     */
    private int count;

    /**
     * The raw data settings of the loaded image.
     */
    private com.aspose.imaging.RawDataSettings rawDataSettings;

    /**
     * Gets the number of fully transparent pixels.
     */
    public int getCount() {
        return this.count;
    }

    /**
     * <p>Initializes a new instance of the <see TransparentPixelRawDataCounter /> class.</p>
     *
     * @param settings The raw data settings allow to extract color components from raw data.
     */
    public TransparentPixelRawDataCounter(com.aspose.imaging.RawDataSettings settings) {
        this.rawDataSettings = settings;
        this.count = 0;
    }

    /**
     * <p>Processes the loaded raw data. This method is called back every time when a new portion of raw data is loaded.</p>
     *
     * @param dataRectangle The raw data rectangle.
     * @param data          The raw data.
     * @param start         The start data point.
     * @param end           The end data point.
     */
    public void process(com.aspose.imaging.Rectangle dataRectangle, byte[] data, com.aspose.imaging.Point start, com.aspose.imaging.Point end)// throws java.lang.Exception
    {
        int[] channelBits = this.rawDataSettings.getPixelDataFormat().getChannelBits();

        // Hier werden nur einfache Formate berücksichtigt, um den Code zu vereinfachen.
        // Betrachten wir nur Bilder mit 8 Bit pro Sample.
        for (int i = 0; i < channelBits.length; i++) {
            if (channelBits[i] != 8) {
                throw new java.lang.UnsupportedOperationException();
            }
        }

        switch (this.rawDataSettings.getPixelDataFormat().getPixelFormat()) {
            case com.aspose.imaging.PixelFormat.Rgb:
            case com.aspose.imaging.PixelFormat.Bgr: {
                if (channelBits.length == 4) {
                    // ARGB
                    for (int i = 0; i < data.length; i += 4) {
                        // Der Alpha‑Kanal wird zuletzt, nach den Farbbestandteilen, gespeichert.
                        if (data[i + 3] == 0) {
                            this.count++;
                        }
                    }
                }
            }
            break;

            case com.aspose.imaging.PixelFormat.Grayscale: {
                if (channelBits.length == 2) {
                    // Graustufen‑Alpha
                    for (int i = 0; i < data.length; i += 2) {
                        // Der Alpha‑Kanal wird zuletzt, nach den Farbbestandteilen, gespeichert.
                        if (data[i + 1] == 0) {
                            this.count++;
                        }
                    }
                }
            }
            break;

            default:
                throw new java.lang.IllegalArgumentException("PixelFormat");
        }
    }

    /**
     * <p>Processes the loaded raw data. This method is called back every time when a new portion of raw data is loaded.</p>                 *
     *
     * @param dataRectangle The raw data rectangle.
     * @param data          The raw data.
     * @param start         The start data point.
     * @param end           The end data point.
     * @param loadOptions   The load options.
     */
    public void process(com.aspose.imaging.Rectangle dataRectangle, byte[] data, com.aspose.imaging.Point start, com.aspose.imaging.Point end, com.aspose.imaging.LoadOptions loadOptions) {
        this.process(dataRectangle, data, start, end);
    }
}

// Hier ist das Hauptbeispiel für die Verwendung des Zählers
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
    com.aspose.imaging.RawDataSettings settings = rasterImage.getRawDataSettings();

    TransparentPixelRawDataCounter rawDataLoader = new TransparentPixelRawDataCounter(settings);

    // Laden Sie Pixel für das gesamte Bild. Jeder rechteckige Teil des Bildes kann als Parameter der Methode Aspose.Imaging.RasterImage.LoadRawData angegeben werden.
    rasterImage.loadRawData(rasterImage.getBounds(), settings, rawDataLoader);

    System.out.println("The number of fully transparent pixels is " + rawDataLoader.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// Die Ausgabe könnte so aussehen:
// Die Anzahl der vollständig transparenten Pixel beträgt 55157
// Die Gesamtzahl der Pixel beträgt 120400
```

### loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Lädt Rohdaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck, aus dem Rohdaten geladen werden sollen. |
| dstImageBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Die Grenzen des Zielbildes. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Die Rohdaten‑Einstellungen, die für geladene Daten verwendet werden sollen. Hinweis: Wenn die Daten nicht im angegebenen Format vorliegen, wird eine Datenkonvertierung durchgeführt. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | Der Rohdaten‑Lader. |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


Speichert die Rohdaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] | Die Rohdaten. |
| DatenOffset | int | Der Anfangs‑Offset der Rohdaten. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rohdaten‑Rechteck. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Die Rohdaten‑Einstellungen, in denen sich die Daten befinden. |

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.imaging.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


Speichert die 32‑Bit‑ARGB‑Pixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck, in das die Pixel gespeichert werden sollen. |
| Pixel | int[] | Das 32‑Bit‑ARGB-Pixel‑Array. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
Das folgende Beispiel füllt den zentralen Bereich eines Rasterbildes mit schwarzen Pixeln mithilfe der Methode com.aspose.imaging.RasterImage.saveArgb32Pixels.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Das schwarze Quadrat
    int[] pixels = new int[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getBlack().toArgb();
    }

    // Zeichnen Sie das schwarze Quadrat in der Bildmitte.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    rasterImage.saveArgb32Pixels(area, pixels);

    rasterImage.save(dir + "sample.SaveArgb32Pixels.png");
} finally {
    image.dispose();
}
```

### savePixels(Rectangle rectangle, Color[] pixels) {#savePixels-com.aspose.imaging.Rectangle-com.aspose.imaging.Color---}
```
public void savePixels(Rectangle rectangle, Color[] pixels)
```


Speichert die Pixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck, in das die Pixel gespeichert werden sollen. |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | Das Pixel-Array. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
Das folgende Beispiel füllt den zentralen Bereich eines Rasterbildes mit schwarzen Pixeln unter Verwendung der Methode com.aspose.imaging.RasterImage.savePixels.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Das schwarze Quadrat
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getBlack();
    }

    // Zeichnen Sie das schwarze Quadrat in der Bildmitte.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    rasterImage.savePixels(area, pixels);

    rasterImage.save(dir + "sample.SavePixels.png");
} finally {
    image.dispose();
}
```

### toBitmap() {#toBitmap--}
```
public BufferedImage toBitmap()
```


Konvertiert Rasterbild in das Bitmap.

**Returns:**
java.awt.image.BufferedImage - Das Bitmap

**Example: The following example converts a BMP image to a native Java bitmap.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;
    java.awt.image.BufferedImage bitmap = bmpImage.toBitmap();

    // Verarbeiten Sie das native Java-Bitmap.
} finally {
    image.dispose();
}
```

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


Speichert die Pixel. Diese Methode ist veraltet. Bitte verwenden Sie die effektivere `saveCmyk32Pixels(Rectangle, int[])`-Methode.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck, in das die Pixel gespeichert werden sollen. |
| pixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | Das CMYK-Pixel-Array. |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.imaging.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


Speichert die Pixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck, in das die Pixel gespeichert werden sollen. |
| Pixel | int[] | Die CMYK-Pixel dargestellt als 32‑Bit‑Ganzzahlwerte. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
Das folgende Beispiel füllt den zentralen Bereich eines Rasterbildes mit schwarzen Pixeln unter Verwendung der Methode com.aspose.imaging.RasterImage.saveCmyk32Pixels.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Erhalten Sie eine ganzzahlige Darstellung von Schwarz im CMYK-Farbraum.
    int blackCmyk = com.aspose.imaging.CmykColorHelper.toCmyk(com.aspose.imaging.Color.getBlack());

    // Das schwarze Quadrat.
    int[] pixels = new int[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = blackCmyk;
    }

    // Zeichnen Sie das schwarze Quadrat in der Bildmitte.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    rasterImage.saveCmyk32Pixels(area, pixels);

    rasterImage.save(dir + "sample.SaveCmyk32Pixels.png");
} finally {
    image.dispose();
}
```

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Setzt die Auflösung für dieses `RasterImage`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dpiX | double | Die horizontale Auflösung in Punkten pro Zoll des `RasterImage`. |
| dpiY | double | Die vertikale Auflösung in Punkten pro Zoll des `RasterImage`. |


**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Horizontale und vertikale Auflösung des Bildes abrufen
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Verwenden Sie die SetResolution-Methode, um beide Auflösungswerte in einem einzigen Aufruf zu aktualisieren.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // Die Ausgabe könnte so aussehen:
    // Die horizontale Auflösung, in Pixel pro Zoll: 300.0
    // Die vertikale Auflösung, in Pixel pro Zoll: 300.0
    // Auflösungswerte auf 96 dpi setzen
    // Die horizontale Auflösung, in Pixel pro Zoll: 96.0
    // Die vertikale Auflösung, in Pixel pro Zoll: 96.0
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Legt die Bildpalette fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die zu setzende Palette. |
| updateColors | boolean | Wenn auf `true` gesetzt, werden die Farben gemäß der neuen Palette aktualisiert; andernfalls bleiben die Farbindizes unverändert. Beachten Sie, dass unveränderte Indizes das Bild beim Laden zum Absturz bringen können, wenn einige Indizes keinen entsprechenden Paletteneintrag haben. |

### autoRotate() {#autoRotate--}
```
public final void autoRotate()
```


Dreht das Bild automatisch basierend auf den aus Exif-Metadaten extrahierten Orientierungsdaten. Diese Methode stellt sicher, dass Bilder in der korrekten Ausrichtung angezeigt werden, verbessert die Benutzererfahrung und eliminiert den Bedarf an manuellen Anpassungen. Durch die Analyse der Exif-Informationen wird das Bild entsprechend gedreht, was ein nahtloses Anzeigeerlebnis über verschiedene Plattformen und Geräte hinweg ermöglicht. Dieser automatisierte Drehvorgang vereinfacht die Bildverarbeitung und erhöht die Gesamtbenutzerfreundlichkeit, insbesondere beim Umgang mit großen Bildmengen mit unterschiedlichen Ausrichtungen.

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Skaliert das Bild mit erweiterten Optionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Die Skalierungseinstellungen. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Bild um die Mitte drehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |
| resizeProportionally | boolean | Wenn auf `true` gesetzt, wird die Bildgröße gemäß den Projektionen des rotierten Rechtecks (Eckpunkte) geändert; andernfalls bleiben die Abmessungen unverändert und nur der interne Bildinhalt wird rotiert. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Farbe des Hintergrunds. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Bild um die Mitte drehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarisierung eines Bildes mit vordefiniertem Schwellenwert

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threshold | byte | Schwellenwert. Wenn der entsprechende Grauwert eines Pixels größer als der Schwellenwert ist, wird ihm der Wert 255 zugewiesen, andernfalls 0. |


**Example: The following example binarizes a raster image with the predefined threshold.**
Das folgende Beispiel binarisiert ein Rasterbild mit dem vordefinierten Schwellenwert. Binärbilder enthalten nur 2 Farben – Schwarz und Weiß.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Binarisieren Sie das Bild mit einem Schwellenwert von 127.
    // Wenn der entsprechende Grauwert eines Pixels größer als 127 ist, wird ihm der Wert 255 zugewiesen, sonst 0.
    rasterImage.binarizeFixed((byte) 127);
    rasterImage.save(dir + "sample.BinarizeFixed.png");
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Binarisierung eines Bildes mit Otsu-Schwellenwertbestimmung


**Example: The following example binarizes a raster image with Otsu thresholding.**
Das folgende Beispiel binarisiert ein Rasterbild mit Otsu-Schwellenwertbestimmung. Binärbilder enthalten nur 2 Farben – Schwarz und Weiß.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Binarisieren Sie das Bild mit Otsu‑Schwellenwertverfahren.
    rasterImage.binarizeOtsu();
    rasterImage.save(dir + "sample.BinarizeOtsu.png");
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Binarisierung eines Bildes mittels Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild-Schwellenwertbestimmung

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightnessDifference | double | Der Helligkeitsunterschied zwischen dem Pixel und dem Durchschnitt eines s × s‑Fensters von Pixeln, das um dieses Pixel zentriert ist. |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binarisierung eines Bildes mittels Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild-Schwellenwertbestimmung

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightnessDifference | double | Der Helligkeitsunterschied zwischen dem Pixel und dem Durchschnitt eines s × s‑Fensters von Pixeln, das um dieses Pixel zentriert ist. |
| windowSize | int | Die Größe des s × s‑Fensters von Pixeln, das um dieses Pixel zentriert ist. |


**Example: The following example binarizes a raster image with Bradley's adaptive thresholding algorithm with the specified window size.**
Das folgende Beispiel binarisiert ein Rasterbild mit Bradleys adaptivem Schwellenwertalgorithmus bei der angegebenen Fenstergröße. Binärbilder enthalten nur 2 Farben – Schwarz und Weiß.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Binarisieren Sie das Bild mit einem Helligkeitsunterschied von 5. Die Helligkeit ist die Differenz zwischen einem Pixel und dem Durchschnitt eines 10 × 10‑Pixel‑Fensters, das um diesen Pixel zentriert ist.
    rasterImage.binarizeBradley(5, 10);
    rasterImage.save(dir + "sample.BinarizeBradley5_10x10.png");
} finally {
    image.dispose();
}
```

### blend(Point origin, RasterImage overlay, Rectangle overlayArea) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-}
```
public final void blend(Point origin, RasterImage overlay, Rectangle overlayArea)
```


Mischt diese Bildinstanz mit dem `overlay`-Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | Der Ursprung der Hintergrundbildüberblendung. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Überlagerungsbild. |
| overlayArea | [Rectangle](../../com.aspose.imaging/rectangle) | Der Überlagerungsbereich. |

### blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-}
```
public void blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)
```


Mischt diese Bildinstanz mit dem `overlay`-Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | Der Ursprung der Hintergrundbildüberblendung. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Überlagerungsbild. |
| overlayArea | [Rectangle](../../com.aspose.imaging/rectangle) | Der Überlagerungsbereich. |
| overlayAlpha | byte | Der Overlay‑Alpha. |

### blend(Point origin, RasterImage overlay) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-}
```
public final void blend(Point origin, RasterImage overlay)
```


Mischt diese Bildinstanz mit dem `overlay` bei Alpha == 255.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | Der Ursprung der Hintergrundbildüberblendung. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | Die Überlagerung. |

### blend(Point origin, RasterImage overlay, byte overlayAlpha) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-byte-}
```
public final void blend(Point origin, RasterImage overlay, byte overlayAlpha)
```


Mischt diese Bildinstanz mit dem `overlay`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | Der Ursprung der Hintergrundbildüberblendung. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | Die Überlagerung. |
| overlayAlpha | byte | Der Overlay‑Alpha. |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformation eines Bildes in seine Graustufen-Darstellung


**Example: The following example transforms a colored raster image to its grayscale representation.**
Das folgende Beispiel wandelt ein farbiges Rasterbild in seine Graustufen-Darstellung um. Graustufenbilder bestehen ausschließlich aus Grautönen und enthalten nur Intensitätsinformationen.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    rasterImage.grayscale();
    rasterImage.save(dir + "sample.Grayscale.png");
} finally {
    image.dispose();
}
```

### normalizeHistogram() {#normalizeHistogram--}
```
public void normalizeHistogram()
```


Normalisiert das Bildhistogramm \\u2014 passt Pixelwerte an, um den gesamten verfügbaren Bereich zu nutzen.

### autoBrightnessContrast() {#autoBrightnessContrast--}
```
public void autoBrightnessContrast()
```


Automatische adaptive Helligkeits- und Kontrastnormalisierung für das gesamte Bild.

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Anpassung der Helligkeit des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightness | int | Helligkeitswert. |


**Example: The following example performs brightness correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Legen Sie den Helligkeitswert fest. Die zulässigen Helligkeitswerte liegen im Bereich [-255, 255].
    rasterImage.adjustBrightness(50);
    rasterImage.save(dir + "sample.AdjustBrightness.png");
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Bildkontrastierung

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| contrast | float | Kontrastwert (im Bereich [-100; 100]) |


**Example: The following example performs contrast correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Legen Sie den Kontrastwert fest. Die zulässigen Kontrastwerte liegen im Bereich [-100f, 100f].
    rasterImage.adjustContrast(50);
    rasterImage.save(dir + "sample.AdjustContrast.png");
} finally {
    image.dispose();
}
```

### embedDigitalSignature(String password) {#embedDigitalSignature-java.lang.String-}
```
public void embedDigitalSignature(String password)
```


Betten Sie ein digitales Signatur basierend auf dem bereitgestellten Passwort in das Bild ein, mittels Steganographie.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Passwort | java.lang.String | Das Passwort, das zum Erzeugen digitaler Signaturdaten verwendet wird |


**Example: The example shows how to embed digital signature based on provided password into image pixel data.**

``` java
String imageFilePath = "ball.png";
String password = "veryStr0ngPassword";
try (Image image = Image.load(imageFilePath))
{
    image.embedDigitalSignature(password);
    image.save(outputPath);
}
```

### analyzePercentageDigitalSignature(String password) {#analyzePercentageDigitalSignature-java.lang.String-}
```
public int analyzePercentageDigitalSignature(String password)
```


Berechnet den prozentualen Ähnlichkeitswert zwischen den extrahierten Daten und dem ursprünglichen Passwort.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Passwort | java.lang.String | Das Passwort, das zum Extrahieren der eingebetteten Daten verwendet wird. |

**Returns:**
int – Der prozentuale Ähnlichkeitswert.
### isDigitalSigned(String password) {#isDigitalSigned-java.lang.String-}
```
public boolean isDigitalSigned(String password)
```


Führt eine schnelle Prüfung durch, um festzustellen, ob das Bild digital signiert ist, unter Verwendung des bereitgestellten Passworts und Schwellenwerts.

--------------------

Diese Methode bietet die schnellste Erkennung, indem sie `GetSignPercentage` nutzt. Sobald die extrahierten Daten den angegebenen Schwellenwert erreichen, werden weitere Extraktionsschritte zur Verbesserung der Erkennungsgenauigkeit übersprungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Passwort | java.lang.String | Das Passwort, um die Signatur zu prüfen. |

**Returns:**
boolean – Wahr, wenn das Bild signiert ist, sonst falsch.
### isDigitalSigned(String password, int percentageThreshold) {#isDigitalSigned-java.lang.String-int-}
```
public boolean isDigitalSigned(String password, int percentageThreshold)
```


Führt eine schnelle Prüfung durch, um festzustellen, ob das Bild digital signiert ist, unter Verwendung des bereitgestellten Passworts und Schwellenwerts.

--------------------

Diese Methode bietet die schnellste Erkennung, indem sie `GetSignPercentage` nutzt. Sobald die extrahierten Daten den angegebenen Schwellenwert erreichen, werden weitere Extraktionsschritte zur Verbesserung der Erkennungsgenauigkeit übersprungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Passwort | java.lang.String | Das Passwort, um die Signatur zu prüfen. |
| percentageThreshold | int | Der Schwellenwert (in Prozent)[0-100], der bestimmt, ob das Bild als signiert gilt. Wenn nicht angegeben, wird ein Standardschwellenwert (`75`) verwendet. |

**Returns:**
boolean – Wahr, wenn das Bild signiert ist, sonst falsch.
### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Gammakorrektur eines Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| gammaRed | float | Gamma‑Koeffizient für den Rotkanal |
| gammaGreen | float | Gamma‑Koeffizient für den Grünkanal |
| gammaBlue | float | Gamma für den Blaukanal-Koeffizienten |


**Example: The following example performs gamma-correction of an image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Setzen Sie individuelle Gamma-Koeffizienten für die Rot-, Grün- und Blaukanäle.
    rasterImage.adjustGamma(1.5f, 2.5f, 3.5f);
    rasterImage.save(dir + "sample.AdjustGamma.png");
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Gammakorrektur eines Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gamma | float | Gamma für Rot-, Grün- und Blaukanäle-Koeffizient |


**Example: The following example performs gamma-correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Setzen Sie den Gamma-Koeffizienten für Rot-, Grün- und Blaukanäle.
    rasterImage.adjustGamma(2.5f);
    rasterImage.save(dir + "sample.AdjustGamma.png");
} finally {
    image.dispose();
}
```

### getSkewAngle() {#getSkewAngle--}
```
public final float getSkewAngle()
```


Ermittelt den Schrägwinkel. Diese Methode ist auf gescannte Textdokumente anwendbar, um den Schrägwinkel beim Scannen zu bestimmen.

**Returns:**
float - Der Schrägwinkel in Grad.
### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


Normalisiert den Winkel. Diese Methode ist für gescannte Textdokumente anwendbar, um den schiefen Scan zu entfernen. Diese Methode verwendet \#getSkewAngle.getSkewAngle und die [Image.rotate(float)](../../com.aspose.imaging/image\#rotate-float-) Methoden.

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Normalisiert den Winkel. Diese Methode ist für gescannte Textdokumente anwendbar, um den schiefen Scan zu entfernen. Diese Methode verwendet \#rotate(float, boolean, Color).rotate(float, boolean, Color) Methoden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resizeProportionally | boolean | Wenn auf `true` gesetzt, wird die Bildgröße gemäß den Projektionen des rotierten Rechtecks (Eckpunkte) geändert; andernfalls bleiben die Abmessungen unverändert und nur der interne Bildinhalt wird rotiert. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Farbe des Hintergrunds. |


**Example: Skew is an artifact that might appear during document scanning process when the text/images of the document get rotated at a slight angle.**
Schieflage ist ein Artefakt, das beim Dokumentenscan auftreten kann, wenn der Text/die Bilder des Dokuments um einen kleinen Winkel gedreht werden. Sie kann verschiedene Ursachen haben, am häufigsten jedoch, dass das Papier während des Scans verschoben wird. Daher ist das Deskewen der Prozess, bei dem dieses Problem in gescannten Dateien (d. h. Bitmap) erkannt und behoben wird, sodass deskewte Dokumente den Text/die Bilder korrekt und horizontal ausgerichtet haben.
``` java
String dir = "c:\\aspose.imaging\\issues\\java\\1461\\";

String inputFilePath = dir + "skewed.png";
String outputFilePath = dir + "skewed.out.png";

// Entfernen Sie den schiefen Scan mit den Standardparametern.
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(inputFilePath);
try {
    // Deskew
    image.normalizeAngle(false /*do not resize*/, com.aspose.imaging.Color.getLightGray() /*background color*/);
    image.save(outputFilePath);
} finally {
    image.close();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Filtert das angegebene Rechteck.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Die Optionen. |


**Example: The following example applies various types of filters to a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Wenden Sie einen Medianfilter mit einer Rechteckgröße von 5 auf das gesamte Bild an.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    rasterImage.save(dir + "sample.MedianFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Wenden Sie einen bilateralen Glättungsfilter mit einer Kernelgröße von 5 auf das gesamte Bild an.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    rasterImage.save(dir + "sample.BilateralSmoothingFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Wenden Sie einen Gaußschen Weichzeichner mit einem Radius von 5 und einem Sigma-Wert von 4,0 auf das gesamte Bild an.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussianBlurFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Wenden Sie einen Gauss-Wiener-Filter mit einem Radius von 5 und einem Glättungswert von 4,0 auf das gesamte Bild an.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Wenden Sie einen Bewegungs-Wiener-Filter mit einer Länge von 5, einem Glättungswert von 4,0 und einem Winkel von 90,0 Grad auf das gesamte Bild an.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.save(dir + "sample.MotionWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Wenden Sie einen Schärfungsfilter mit einer Kernelgröße von 5 und einem Sigma-Wert von 4,0 auf das gesamte Bild an.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.SharpenFilter.png");
} finally {
    image.dispose();
}
```

### replaceColor(Color oldColor, byte oldColorDiff, Color newColor) {#replaceColor-com.aspose.imaging.Color-byte-com.aspose.imaging.Color-}
```
public void replaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```


Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.imaging/color) | Alte Farbe, die ersetzt werden soll. |
| oldColorDiff | byte | Erlaubte Differenz im alten Farbwert, um den ersetzten Farbton erweitern zu können. |
| newColor | [Color](../../com.aspose.imaging/color) | Neue Farbe, mit der die alte Farbe ersetzt wird. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oldColorArgb | int | Alter ARGB-Farbwert, der ersetzt werden soll. |
| oldColorDiff | byte | Erlaubte Differenz im alten Farbwert, um den ersetzten Farbton erweitern zu können. |
| newColorArgb | int | Neuer ARGB-Farbwert, mit dem die alte Farbe ersetzt wird. |

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.imaging.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


Ersetzt alle nicht transparenten Farben durch die neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. Hinweis: Wenn Sie es bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.imaging/color) | Neue Farbe, mit der nicht-transparente Farben ersetzt werden. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Ersetzt alle nicht transparenten Farben durch die neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. Hinweis: Wenn Sie es bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorArgb | int | Neuer ARGB-Farbwert, mit dem nicht transparente Farben ersetzt werden. |

