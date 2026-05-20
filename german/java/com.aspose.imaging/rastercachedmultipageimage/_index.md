---
title: "RasterCachedMultipageImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das mehrseitige Rasterbild"
type: docs
weight: 90
url: /de/java/com.aspose.imaging/rastercachedmultipageimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImage](../../com.aspose.imaging/imultipageimage)
```
public abstract class RasterCachedMultipageImage extends RasterCachedImage implements IMultipageImage
```

Das mehrseitige Rasterbild
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHeight()](#getHeight--) | Ermittelt die Bildhöhe. |
| [getWidth()](#getWidth--) | Ermittelt die Bildbreite. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Ermittelt die Bit‑Pro‑Pixel‑Anzahl des Bildes. |
| [isCached()](#isCached--) | Gibt einen Wert zurück, der angibt, ob Bilddaten derzeit im Cache sind. |
| [hasAlpha()](#hasAlpha--) | Gibt einen Wert zurück, der angibt, ob diese Instanz Alpha hat. |
| [hasTransparentColor()](#hasTransparentColor--) | Gibt einen Wert zurück, der angibt, ob das Bild eine transparente Farbe hat. |
| [getImageOpacity()](#getImageOpacity--) | Ermittelt die Opazität dieses Bildes. |
| [getBackgroundColor()](#getBackgroundColor--) | Liest einen Wert für die Hintergrundfarbe. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Setzt einen Wert für die Hintergrundfarbe. |
| [getMetadata()](#getMetadata--) | Liest XMP-Daten aus dem Frame. |
| [getPageExportingAction()](#getPageExportingAction--) | Ermittelt die Seitenexportaktion. |
| [setPageExportingAction(PageExportingAction value)](#setPageExportingAction-com.aspose.imaging.PageExportingAction-) | Legt die Seitenexportaktion fest. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Anpassung der `brightness` für das Bild. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | [Image](../../com.aspose.imaging/image) Kontrast |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Gammakorrektur eines Bildes. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Gammakorrektur eines Bildes. |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | Mischt diese Bildinstanz mit dem `overlay`-Bild. |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | Betten Sie die digitale Signatur basierend auf dem bereitgestellten Passwort in jede Seite des Bildes ein. |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | Berechnet den prozentualen Ähnlichkeitswert zwischen den extrahierten Daten und dem ursprünglichen Passwort. |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | Führt eine schnelle Prüfung durch, um festzustellen, ob das Bild digital signiert ist, unter Verwendung des bereitgestellten Passworts und Schwellenwerts. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarisierung eines Bildes mit vordefiniertem Schwellenwert |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarisierung eines Bildes mittels Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild-Schwellenwertbestimmung |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Binarisierung eines Bildes mittels Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild-Schwellenwertbestimmung |
| [binarizeOtsu()](#binarizeOtsu--) | Binarisierung eines Bildes mit Otsu-Schwellenwertbestimmung |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Zuschneiden des Bildes. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Bild mit Verschiebungen zuschneiden. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Führt Dithering auf dem aktuellen Bild aus. |
| [grayscale()](#grayscale--) | Transformation eines Bildes in seine Graustufen-Darstellung |
| [normalizeHistogram()](#normalizeHistogram--) | Normalisiert das Bildhistogramm \\u2014 passt Pixelwerte an, um den gesamten verfügbaren Bereich zu nutzen. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | `RasterCachedMultipageImage.rotate` Bild um das Zentrum drehen. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Dreht, spiegelt oder dreht und spiegelt alle Seiten. |
| [rotateFlipAll(int rotateFlip)](#rotateFlipAll-int-) | Dreht die Spiegelung aller. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ändert die Größe des Bildes. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ändert die Größe des Bildes. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Ändert die Breite proportional. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Ändert die Breite proportional. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Ersetzt alle nicht-transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Filtert das angegebene Rechteck. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | Normalisiert den Winkel. |
| [cacheData()](#cacheData--) | Zwischenspeichert die Daten privat. |

## Example: The following example shows batch conversion before saving (exporting) Tiff images.

``` java
String fileName = "10MB_Tif.tif";
String inputFileName = fileName;

String outputFileNameTif = "output.tif";

//Die Möglichkeit der Batch-Konvertierung vor dem Speichern (Exportieren) von Tiff-Bildern ist implementiert.

try(com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(inputFileName))
{
    // Batch-Operation für Seiten festlegen
    tiffImage.setPageExportingAction(new PageExportingAction()
    {
        @Override
        public void invoke(int pageIndex, Image page)
        {
            // Startet die Garbage Collection, um unnötige Speicheransammlungen von vorherigen Seiten zu vermeiden.
            System.gc();

            ((com.aspose.imaging.RasterImage) page).rotate(90);
        }
    });

    tiffImage.save(outputFileNameTif);

    /* Attention! In batch mode all pages will be released in this line!
     If you want to further perform operations on the original image, you should reload it from the source to another instance. */
}
```

### getHeight() {#getHeight--}
```
public int getHeight()
```


Ermittelt die Bildhöhe.

Wert: Die Bildhöhe.

**Returns:**
int – die Bildhöhe.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Ermittelt die Bildbreite.

Wert: Die Bildbreite.

**Returns:**
int – die Bildbreite.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Ermittelt die Bit‑Pro‑Pixel‑Anzahl des Bildes.

Wert: Die Bit‑Pro‑Pixel‑Anzahl des Bildes.

**Returns:**
int – die Bit‑Pro‑Pixel‑Anzahl des Bildes.
### isCached() {#isCached--}
```
public boolean isCached()
```


Gibt einen Wert zurück, der angibt, ob Bilddaten derzeit im Cache sind.

Wert: `true`, wenn Bilddaten zwischengespeichert sind; andernfalls `false`.

**Returns:**
boolean – ein Wert, der angibt, ob Bilddaten derzeit zwischengespeichert sind.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Gibt einen Wert zurück, der angibt, ob diese Instanz Alpha hat.

Wert: `true`, wenn diese Instanz Alpha hat; andernfalls `false`.

**Returns:**
boolean – ein Wert, der angibt, ob diese Instanz Alpha hat.
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Gibt einen Wert zurück, der angibt, ob das Bild eine transparente Farbe hat.

--------------------

Diese Implementierung prüft den Wert von `RasterImage.HasTransparentColor`([RasterImage.hasTransparentColor](../../com.aspose.imaging/rasterimage\#hasTransparentColor)/[RasterImage.setTransparentColor(boolean)](../../com.aspose.imaging/rasterimage\#setTransparentColor-boolean-)) des `DefaultPage`(\#getDefaultPage\_internalized.getDefaultPage\_internalized).

**Returns:**
boolean – ein Wert, der angibt, ob das Bild eine transparente Farbe hat.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Ermittelt die Opazität dieses Bildes.

Wert: Der Opazitätswert zwischen 0,0 (vollständig transparent) und 1,0 (vollständig undurchsichtig).

**Returns:**
float - Deckkraft dieses Bildes.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Liest einen Wert für die Hintergrundfarbe.

**Returns:**
[Color](../../com.aspose.imaging/color) - a value for the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Setzt einen Wert für die Hintergrundfarbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | ein Wert für die Hintergrundfarbe. |

### getMetadata() {#getMetadata--}
```
public ImageMetadata getMetadata()
```


Liest XMP-Daten aus dem Frame.

Wert: XMP-Paket-Daten-Wrapper

**Returns:**
[ImageMetadata](../../com.aspose.imaging.metadata/imagemetadata) - XMP data from frame.
### getPageExportingAction() {#getPageExportingAction--}
```
public PageExportingAction getPageExportingAction()
```


Ermittelt die Seitenexportaktion. Bitte beachten Sie, dass das Setzen dieser Methode automatisch die Seitenressourcen freigibt, nachdem sie ausgeführt wurde. Sie wird unmittelbar vor dem Speichern jeder Seite ausgeführt.

Wert: Die Seitenexportaktion.

**Returns:**
[PageExportingAction](../../com.aspose.imaging/pageexportingaction) - the page exporting action.
### setPageExportingAction(PageExportingAction value) {#setPageExportingAction-com.aspose.imaging.PageExportingAction-}
```
public void setPageExportingAction(PageExportingAction value)
```


Legt die Seitenexportaktion fest. Bitte beachten Sie, dass das Setzen dieser Methode automatisch die Seitenressourcen freigibt, nachdem sie ausgeführt wurde. Sie wird unmittelbar vor dem Speichern jeder Seite ausgeführt.

Wert: Die Seitenexportaktion.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PageExportingAction](../../com.aspose.imaging/pageexportingaction) | die Seitenexportaktion. |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Anpassung der `brightness` für das Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightness | int | Helligkeitswert. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


[Image](../../com.aspose.imaging/image) contrasting

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| contrast | float | Kontrastwert (im Bereich [-100; 100]) |

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

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Gammakorrektur eines Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gamma | float | Gamma für Rot-, Grün- und Blaukanäle-Koeffizient |

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

### embedDigitalSignature(String password) {#embedDigitalSignature-java.lang.String-}
```
public void embedDigitalSignature(String password)
```


Betten Sie die digitale Signatur basierend auf dem bereitgestellten Passwort in jede Seite des Bildes ein.

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

--------------------

Aufgrund von Mehrseitenbildern stellt das Ergebnis den berechneten `MIDDLE AVERAGED signing percentage` dar

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Passwort | java.lang.String | Das Passwort, das zum Extrahieren der eingebetteten Daten verwendet wird. |

**Returns:**
int – Der prozentuale Ähnlichkeitswert.
### isDigitalSigned(String password, int percentageThreshold) {#isDigitalSigned-java.lang.String-int-}
```
public boolean isDigitalSigned(String password, int percentageThreshold)
```


Führt eine schnelle Prüfung durch, um festzustellen, ob das Bild digital signiert ist, unter Verwendung des bereitgestellten Passworts und Schwellenwerts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Passwort | java.lang.String | Das Passwort, um die Signatur zu prüfen. |
|  | percentageThreshold | int | Der Schwellenwert (in Prozent)[0-100], der bestimmt, ob das Bild als signiert gilt. Wenn nicht angegeben, wird ein Standardschwellenwert (`75`) verwendet. |

--------------------

Diese Methode bietet die schnellste Erkennung, indem sie `GetSignPercentage` nutzt. Sobald die extrahierten Daten den angegebenen Schwellenwert erreichen, werden weitere Extraktionsschritte zur Verbesserung der Erkennungsgenauigkeit übersprungen.

Das Ergebnis ist `true` nur, wenn alle Seiten im Mehrseitenbild als signiert erkannt werden; andernfalls wird das Bild als unsigniert betrachtet. |

**Returns:**
boolean – Wahr, wenn das Bild signiert ist, sonst falsch.
### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarisierung eines Bildes mit vordefiniertem Schwellenwert

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threshold | byte | Schwellenwert. Wenn der entsprechende Grauwert eines Pixels größer als der Schwellenwert ist, wird ihm der Wert 255 zugewiesen, andernfalls 0. |

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

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Binarisierung eines Bildes mittels Bradleys adaptivem Schwellenwertalgorithmus unter Verwendung der Integralbild-Schwellenwertbestimmung

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightnessDifference | double | Der Helligkeitsunterschied zwischen dem Pixel und dem Durchschnitt eines s × s‑Fensters von Pixeln, das um dieses Pixel zentriert ist. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Binarisierung eines Bildes mit Otsu-Schwellenwertbestimmung

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Zuschneiden des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Bild mit Verschiebungen zuschneiden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| leftShift | int | Die linke Verschiebung. |
| rightShift | int | Die rechte Verschiebung. |
| topShift | int | Die obere Verschiebung. |
| bottomShift | int | Die untere Verschiebung. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Führt Dithering auf dem aktuellen Bild aus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ditheringMethod | int | Die Dithering-Methode. |
| bitsCount | int | Die endgültige Bitanzahl für Dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die benutzerdefinierte Palette für Dithering. |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformation eines Bildes in seine Graustufen-Darstellung

### normalizeHistogram() {#normalizeHistogram--}
```
public void normalizeHistogram()
```


Normalisiert das Bildhistogramm \\u2014 passt Pixelwerte an, um den gesamten verfügbaren Bereich zu nutzen.

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


`RasterCachedMultipageImage.rotate` Bild um das Zentrum drehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |
| resizeProportionally | boolean | Wenn auf `true` gesetzt, wird die Bildgröße gemäß den Projektionen des gedrehten Rechtecks (Eckpunkte) geändert; andernfalls bleiben die Abmessungen unverändert und nur die `` Bildinhalte werden rotiert. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Farbe des Hintergrunds. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Dreht, spiegelt oder dreht und spiegelt alle Seiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateFlipType | int | Der Dreh‑/Spiegeltyp. |

### rotateFlipAll(int rotateFlip) {#rotateFlipAll-int-}
```
public void rotateFlipAll(int rotateFlip)
```


Dreht die Spiegelung aller.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateFlip | int | Die Rotationsumkehr. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Ändert die Größe des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| resizeType | int | Der Skalierungstyp. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ändert die Größe des Bildes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Die Skalierungseinstellungen. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Ändert die Breite proportional.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| resizeType | int | Typ der Skalierung. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Ändert die Breite proportional.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newHeight | int | Die neue Höhe. |
| resizeType | int | Typ der Skalierung. |

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

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Ersetzt alle nicht transparenten Farben durch die neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. Hinweis: Wenn Sie es bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newColorArgb | int | Neuer ARGB-Farbwert, mit dem nicht transparente Farben ersetzt werden. |

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

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Normalisiert den Winkel. Diese Methode ist auf gescannten Textdokumenten anwendbar, um die verzerrte Aufnahme zu korrigieren. Diese Methode verwendet die Methoden [RasterImage.getSkewAngle](../../com.aspose.imaging/rasterimage\#getSkewAngle) und [RasterImage.rotate(float, boolean, Color)](../../com.aspose.imaging/rasterimage\#rotate-float--boolean--Color-) Methoden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resizeProportionally | boolean | Wenn auf `true` gesetzt, wird die Bildgröße gemäß den Projektionen des rotierten Rechtecks (Eckpunkte) geändert; andernfalls bleiben die Abmessungen unverändert und nur der interne Bildinhalt wird rotiert. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Farbe des Hintergrunds. |

### cacheData() {#cacheData--}
```
public void cacheData()
```


Zwischenspeichert die Daten privat.

