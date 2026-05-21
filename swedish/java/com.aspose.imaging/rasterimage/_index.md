---
title: "RasterImage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar en rasterbild som stödjer rastergrafikoperationer."
type: docs
weight: 91
url: /sv/java/com.aspose.imaging/rasterimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image)

**All Implemented Interfaces:**
[com.aspose.imaging.IRasterImageArgb32PixelLoader](../../com.aspose.imaging/irasterimageargb32pixelloader), com.aspose.internal.IPixelsSaver, [com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public abstract class RasterImage extends Image implements IRasterImageArgb32PixelLoader, IPixelsSaver, IHasXmpData
```

Representerar en rasterbild som stödjer rastergrafikoperationer.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Hämtar eller anger ett värde som indikerar om bildkomponenterna måste vara förmultiplicerade. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Hämtar eller anger ett värde som indikerar om bildkomponenterna måste vara förmultiplicerade. |
| [getUseRawData()](#getUseRawData--) | Hämtar eller anger ett värde som indikerar om rådatainläsning ska användas när rådatainläsning är tillgänglig. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Hämtar eller anger ett värde som indikerar om rådatainläsning ska användas när rådatainläsning är tillgänglig. |
| [getUpdateXmpData()](#getUpdateXmpData--) | Hämtar eller anger ett värde som indikerar om XMP-metadata ska uppdateras. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Hämtar eller anger ett värde som indikerar om XMP-metadata ska uppdateras. |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Hämtar eller anger den indexerade färgkonverteraren |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-) | Hämtar eller anger den indexerade färgkonverteraren |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Hämtar eller anger den anpassade färgkonverteraren |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.imaging.IColorConverter-) | Hämtar eller anger den anpassade färgkonverteraren |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Hämtar eller anger reservindexen att använda när palettindexet är utanför gränserna |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Hämtar eller anger reservindexen att använda när palettindexet är utanför gränserna |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [isUsePalette()](#isUsePalette--) | Hämtar ett värde som indikerar om bildpaletten används. |
| [getRawDataFormat()](#getRawDataFormat--) | Hämtar rådataformatet. |
| [getRawLineSize()](#getRawLineSize--) | Hämtar den råa radstorleken i byte. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Hämtar ett värde som indikerar om rådatainläsning är tillgänglig. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Hämtar eller anger den horisontella upplösningen, i pixlar per tum, för detta `RasterImage`. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Hämtar eller anger den horisontella upplösningen, i pixlar per tum, för detta `RasterImage`. |
| [getVerticalResolution()](#getVerticalResolution--) | Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för detta `RasterImage`. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för detta `RasterImage`. |
| [hasTransparentColor()](#hasTransparentColor--) | Hämtar ett värde som indikerar om denna [RasterImage](../../com.aspose.imaging/rasterimage)‑instans har en transparent färg. |
| [hasAlpha()](#hasAlpha--) | Hämtar ett värde som indikerar om detta objekt har alfa. |
| [getTransparentColor()](#getTransparentColor--) | Hämtar bildens transparenta färg. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Anger ett värde som indikerar om denna [RasterImage](../../com.aspose.imaging/rasterimage)‑instans har en transparent färg. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Hämtar bildens transparenta färg. |
| [getImageOpacity()](#getImageOpacity--) | Hämtar opaciteten för den här bilden. |
| [removeMetadata()](#removeMetadata--) | Tar bort metadata för denna bildinstans genom att sätta detta `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) värde till `null`. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Hämtar datum och tid när resursbilden genomgick sin senaste ändring. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | Utför dithering på den aktuella bilden. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Utför dithering på den aktuella bilden. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-) | Hämtar standardpixelarrayen med hjälp av partiell pixel‑läsare. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialRawDataLoader-com.aspose.imaging.RawDataSettings-) | Hämtar standardrådataarrayen med hjälp av partiell pixel‑läsare. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.imaging.Rectangle-) | Hämtar standard 32‑bit ARGB‑pixelarrayen. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-) | Hämtar standardrådataarrayen. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Hämtar en bilds 32‑bit ARGB‑pixel. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Hämtar en bildpixel. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Ställer in en bilds 32‑bit ARGB‑pixel för den angivna positionen. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.imaging.Color-) | Ställer in en bildpixel för den angivna positionen. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Läser hela skanningslinjen med det angivna skanningslinje‑indexet. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Läser hela skanningslinjen med det angivna skanningslinje‑indexet. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.imaging.Color---) | Skriver hela skanningslinjen till det angivna skanningslinje‑indexet. |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Skriver hela skanningslinjen till det angivna skanningslinje‑indexet. |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-) | Laddar 32‑bit ARGB‑pixlar partiellt i paket. |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-) | Laddar pixlar partiellt i paket. |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.imaging.Rectangle-) | Laddar 32‑bit ARGB‑pixlar. |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.imaging.Rectangle-) | Laddar 64‑bit ARGB‑pixlar. |
| [loadPartialArgb64Pixels(Rectangle rectangle, IPartialArgb64PixelLoader partialPixelLoader)](#loadPartialArgb64Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb64PixelLoader-) | Laddar 64‑bit ARGB‑pixlar partiellt i paket. |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.imaging.Rectangle-) | Laddar pixlar. |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.imaging.Rectangle-) | Laddar pixlar i CMYK‑format. |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.imaging.Rectangle-) | Laddar pixlar i CMYK‑format. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-) | Laddar rå bilddata med hjälp av den partiella bearbetningsmekanismen. |
| [loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-) | Laddar rådata. |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-) | Sparar rådata. |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.imaging.Rectangle-int---) | Sparar 32‑bit ARGB‑pixlarna. |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.imaging.Rectangle-com.aspose.imaging.Color---) | Sparar pixlarna. |
| [toBitmap()](#toBitmap--) | Konverterar rasterbild till bitmapen. |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.CmykColor---) | Sparar pixlarna. |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.imaging.Rectangle-int---) | Sparar pixlarna. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Ställer in upplösningen för detta `RasterImage`. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Ställer in bildpaletten. |
| [autoRotate()](#autoRotate--) | Roterar automatiskt bilden baserat på orienteringsdata som extraheras från Exif-metadata. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ändrar bildens storlek med utökade alternativ. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Rotera bilden kring centrum. |
| [rotate(float angle)](#rotate-float-) | Rotera bilden kring centrum. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarisering av en bild med fördefinierad tröskel |
| [binarizeOtsu()](#binarizeOtsu--) | Binarisering av en bild med Otsu-tröskling |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integralbildströskling |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integralbildströskling |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-) | Blandar denna bildinstans med `overlay`-bilden. |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | Blandar denna bildinstans med `overlay`-bilden. |
| [blend(Point origin, RasterImage overlay)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-) | Blandar den här bildinstansen med `overlay` med alfa == 255. |
| [blend(Point origin, RasterImage overlay, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-byte-) | Blandar den här bildinstansen med `overlay`. |
| [grayscale()](#grayscale--) | Transformation av en bild till dess gråskale-representation |
| [normalizeHistogram()](#normalizeHistogram--) | Normaliserar bildens histogram \\u2014 justera pixelvärden för att använda hela tillgängliga intervallet. |
| [autoBrightnessContrast()](#autoBrightnessContrast--) | Automatisk adaptiv ljusstyrke- och kontrastnormalisering för hela bilden. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Justering av bildens ljusstyrka. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Bildkontrast |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | Bädda in digital signatur baserad på angivet lösenord i bilden med hjälp av steganografi. |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | Beräknar procentuell likhet mellan den extraherade datan och det ursprungliga lösenordet. |
| [isDigitalSigned(String password)](#isDigitalSigned-java.lang.String-) | Utför en snabb kontroll för att avgöra om bilden är digitalt signerad, med det angivna lösenordet och tröskeln. |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | Utför en snabb kontroll för att avgöra om bilden är digitalt signerad, med det angivna lösenordet och tröskeln. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Gamma-korrigering av en bild. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Gamma-korrigering av en bild. |
| [getSkewAngle()](#getSkewAngle--) | Hämtar snedvinkel. |
| [normalizeAngle()](#normalizeAngle--) | Normaliserar vinkeln. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | Normaliserar vinkeln. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Filtrerar den angivna rektangeln. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.imaging.Color-byte-com.aspose.imaging.Color-) | Ersätter en färg med en annan med tillåten skillnad och bevarar original‑alfavärdet för att spara mjuka kanter. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Ersätter en färg med en annan med tillåten skillnad och bevarar original‑alfavärdet för att spara mjuka kanter. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.imaging.Color-) | Ersätter alla icke‑transparenta färger med en ny färg och bevarar original‑alfavärdet för att spara mjuka kanter. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Ersätter alla icke‑transparenta färger med en ny färg och bevarar original‑alfavärdet för att spara mjuka kanter. |

## Example: This example shows how to load pixel information in an array of colors, manipulates the array and set it back to the image.

``` java
String dir = "c:\\temp\\";

// Skapa en instans av GifOptions och ställ in dess olika egenskaper inklusive Source-egenskapen
com.aspose.imaging.imageoptions.GifOptions gifOptions = new com.aspose.imaging.imageoptions.GifOptions();
gifOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "output.gif", false));

// Skapa en instans av Image
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(gifOptions, 500, 500);
try {
    // Hämta bildens pixlar genom att ange området som bildens gräns
    com.aspose.imaging.Color[] pixels = image.loadPixels(image.getBounds());

    // Loopa över arrayen och sätt färg på alternativ indexerad pixel
    for (int index = 0; index < pixels.length; index++) {
        if (index % 2 == 0) {
            // Sätt den indexerade pixelns färg till gul
            pixels[index] = com.aspose.imaging.Color.getYellow();
        } else {
            // Sätt den indexerade pixelns färg till blå
            pixels[index] = com.aspose.imaging.Color.getBlue();
        }
    }

    // Applicera pixeländringarna på bilden
    image.savePixels(image.getBounds(), pixels);

    // Spara alla ändringar.
    image.save();
} finally {
    image.dispose();
}
```

### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Hämtar eller anger ett värde som indikerar om bildkomponenterna måste vara förmultiplicerade.

**Returns:**
boolean - `true` om bildkomponenterna måste vara förmultiplicerade; annars `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Hämtar eller anger ett värde som indikerar om bildkomponenterna måste vara förmultiplicerade.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | `true` om bildkomponenterna måste vara förmultiplicerade; annars `false`. |


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

    // Spara pixlar för hela bilden.
    rasterImage.savePixels(rasterImage.getBounds(), colors);

    // Pixlarna lagras i den ursprungliga bilden i icke‑premultipliserad form.
    // Det krävs att ange motsvarande alternativ explicit för att få premultipliserade färgkomponenter.
    // De premultipliserade färgkomponenterna beräknas med formlerna:
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


Hämtar eller anger ett värde som indikerar om rådatainläsning ska användas när rådatainläsning är tillgänglig.

**Returns:**
boolean - `true` om rådata‑laddning ska användas när rådata‑laddning är tillgänglig; annars `false`.
### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


Hämtar eller anger ett värde som indikerar om rådatainläsning ska användas när rådatainläsning är tillgänglig.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | `true` om rådata‑laddning ska användas när rådata‑laddning är tillgänglig; annars `false`. |

### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


Hämtar eller anger ett värde som indikerar om XMP-metadata ska uppdateras.

**Returns:**
boolean - `true` om XMP‑metadata ska uppdateras; annars `false`.
### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


Hämtar eller anger ett värde som indikerar om XMP-metadata ska uppdateras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | `true` om XMP‑metadata ska uppdateras; annars `false`. |

### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


Hämtar eller anger den indexerade färgkonverteraren

**Returns:**
[IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) - The indexed color converter
### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


Hämtar eller anger den indexerade färgkonverteraren

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) | Den indexerade färgkonverteraren |

### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


Hämtar eller anger den anpassade färgkonverteraren

**Returns:**
[IColorConverter](../../com.aspose.imaging/icolorconverter) - The custom color converter
### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.imaging.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


Hämtar eller anger den anpassade färgkonverteraren

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.imaging/icolorconverter) | Den anpassade färgkonverteraren |

### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


Hämtar eller anger reservindexen att använda när palettindexet är utanför gränserna

**Returns:**
int - Reservindexet som ska användas när palettindexet är utanför gränserna
### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


Hämtar eller anger reservindexen att använda när palettindexet är utanför gränserna

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Reservindexet som ska användas när palettindexet är utanför gränserna |

### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


Hämtar de aktuella rådata‑inställningarna. Observera att när dessa inställningar används laddas data utan konvertering.

**Returns:**
[RawDataSettings](../../com.aspose.imaging/rawdatasettings)
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Hämtar ett värde som indikerar om bildpaletten används.

Värde: `true` om paletten används i bilden; annars `false`.

**Returns:**
boolean - ett värde som indikerar om bildpaletten används.
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Hämtar rådataformatet.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.

**Example: The following example loads raster images and prints information about raw data format and alpha channel.**

``` java

// Bildfilerna att läsa in.
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

// Utdata kan se ut så här:
// ImageFile=c:\\temp\\sample.bmp FileFormat=Rgb24Bpp, använda kanaler: 8,8,8 HasAlpha=false
// ImageFile=c:\\temp\\alpha.png FileFormat=RGBA32Bpp, använda kanaler: 8,8,8,8 HasAlpha=true
```

### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Hämtar den råa radstorleken i byte.

**Returns:**
int - Den råa radstorleken i byte.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


Hämtar ett värde som indikerar om rådatainläsning är tillgänglig.

**Returns:**
boolean - `true` om denna rådata‑laddning är tillgänglig; annars `false`.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Hämtar eller anger den horisontella upplösningen, i pixlar per tum, för detta `RasterImage`.

**Returns:**
double - Den horisontella upplösningen.

Observera att detta värde som standard alltid är 96 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.

**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Hämta horisontell och vertikal upplösning för bilden
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Använd SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // Utdata kan se ut så här:
    // Den horisontella upplösningen, i pixlar per tum: 300.0
    // Den vertikala upplösningen, i pixlar per tum: 300.0
    // Ställ in upplösningsvärden till 96 dpi
    // Den horisontella upplösningen, i pixlar per tum: 96.0
    // Den vertikala upplösningen, i pixlar per tum: 96.0
} finally {
    image.dispose();
}
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Hämtar eller anger den horisontella upplösningen, i pixlar per tum, för detta `RasterImage`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Den horisontella upplösningen. |

Observera att detta värde som standard alltid är 96 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för detta `RasterImage`.

**Returns:**
double - Den vertikala upplösningen.

Observera att detta värde som standard alltid är 96 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.

**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Hämta horisontell och vertikal upplösning för bilden
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Använd SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // Utdata kan se ut så här:
    // Den horisontella upplösningen, i pixlar per tum: 300.0
    // Den vertikala upplösningen, i pixlar per tum: 300.0
    // Ställ in upplösningsvärden till 96 dpi
    // Den horisontella upplösningen, i pixlar per tum: 96.0
    // Den vertikala upplösningen, i pixlar per tum: 96.0
} finally {
    image.dispose();
}
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för detta `RasterImage`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Den vertikala upplösningen. |

Observera att detta värde som standard alltid är 96 eftersom olika plattformar inte kan returnera skärmupplösningen. Du kan överväga att använda SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop. |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Hämtar ett värde som indikerar om denna [RasterImage](../../com.aspose.imaging/rasterimage)‑instans har en transparent färg.

--------------------

Basimplementationen returnerar effektivt `` om den inte åsidosätts i en specifik implementation som stödjer denna funktion. Denna egenskap används främst av [FileFormat.Apng](../../com.aspose.imaging/fileformat\#Apng), [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png), [FileFormat.Gif](../../com.aspose.imaging/fileformat\#Gif), [FileFormat.Tga](../../com.aspose.imaging/fileformat\#Tga) för att ange en transparent färg om en bild inte stödjer transparens via alfakanal.

**Returns:**
boolean - ett värde som indikerar om denna [RasterImage](../../com.aspose.imaging/rasterimage) instans har en transparent färg.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Hämtar ett värde som indikerar om detta objekt har alfa.

**Returns:**
boolean - `true` om denna instans har alfa; annars `false`.

**Example: The following example loads raster images and prints information about raw data format and alpha channel.**

``` java

// Bildfilerna att läsa in.
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

// Utdata kan se ut så här:
// ImageFile=c:\\temp\\sample.bmp FileFormat=Rgb24Bpp, använda kanaler: 8,8,8 HasAlpha=false
// ImageFile=c:\\temp\\alpha.png FileFormat=RGBA32Bpp, använda kanaler: 8,8,8,8 HasAlpha=true
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Hämtar bildens transparenta färg.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Anger ett värde som indikerar om denna [RasterImage](../../com.aspose.imaging/rasterimage)‑instans har en transparent färg.

--------------------

Basimplementationen returnerar effektivt `` om den inte åsidosätts i en specifik implementation som stödjer denna funktion. Denna egenskap används främst av [FileFormat.Apng](../../com.aspose.imaging/fileformat\#Apng), [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png), [FileFormat.Gif](../../com.aspose.imaging/fileformat\#Gif), [FileFormat.Tga](../../com.aspose.imaging/fileformat\#Tga) för att ange en transparent färg om en bild inte stödjer transparens via alfakanal.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean | ett värde som indikerar om denna [RasterImage](../../com.aspose.imaging/rasterimage) instans har en transparent färg. |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Hämtar bildens transparenta färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Hämtar opaciteten för den här bilden.

**Returns:**
float - Opacitetsvärdet mellan 0.0 (fullt transparent) och 1.0 (fullt opakt).
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Tar bort metadata för denna bildinstans genom att sätta detta `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) värde till `null`.

### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Hämtar datum och tid då resursbilden genomgick sin senaste ändring. Denna metod tillhandahåller värdefull metadata som gör det möjligt för användare att spåra och hantera uppdateringar av bildfilen effektivt. Genom att komma åt denna information kan användare säkerställa integriteten och aktualiteten för sina bildresurser, vilket underlättar välgrundade beslut om bildanvändning och underhåll.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| useDefault | boolean | om den är satt till `true` använder informationen från FileInfo som standardvärde. |

**Returns:**
java.util.Date - Datum och tid då resursbilden senast ändrades.
### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


Utför dithering på den aktuella bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ditheringMethod | int | Dithermetoden. |
| bitsCount | int | Det slutgiltiga bitantalet för dithering. |


**Example: The following example loads a raster image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Utför tröskel-dithering med en 4-bitars färgpalett som innehåller 16 färger.
    // Ju fler bitar som anges, desto högre kvalitet och desto större storlek på den resulterande bilden.
    // Observera att endast 1-bitars, 4-bitars och 8-bitars paletter stöds för närvarande.
    rasterImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.save(dir + "sample.ThresholdDithering4.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Utför Floyd-dithering med en 1-bitars färgpalett som endast innehåller 2 färger – svart och vit.
    // Ju fler bitar som anges, desto högre kvalitet och desto större storlek på den resulterande bilden.
    // Observera att endast 1-bitars, 4-bitars och 8-bitars paletter stöds för närvarande.
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


Utför dithering på den aktuella bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ditheringMethod | int | Dithermetoden. |
| bitsCount | int | Det slutgiltiga bitantalet för dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Den anpassade paletten för dithering. |

### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Hämtar standardpixelarrayen med hjälp av partiell pixel‑läsare.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln för att hämta pixlar för. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader) | Den partiella pixel-laddaren. |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialRawDataLoader-com.aspose.imaging.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


Hämtar standardrådataarrayen med hjälp av partiell pixel‑läsare.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln för att hämta pixlar för. |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | Den partiella rådata‑laddaren. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Inställningarna för rådata. |

### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


Hämtar standard 32‑bit ARGB‑pixelarrayen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln för att hämta pixlar för. |

**Returns:**
int[] - Standardpixelarrayen.
### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


Hämtar standardrådataarrayen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln att hämta rådata för. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Inställningarna för rådata. |

**Returns:**
byte[] - Standardarrayen för rådata.
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


Hämtar en bilds 32‑bit ARGB‑pixel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | Pixelns x‑position. |
| y | int | Pixelns y‑position. |

**Returns:**
int - 32‑bits ARGB‑pixel för den angivna platsen.

**Example: The following example loads a raster image and obtains the color of an arbitrary pixel represented as a 32-bit integer value.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Hämta en heltalsrepresentation av färgen på bildens övre vänstra pixel.
    int color = rasterImage.getArgb32Pixel(0, 0);

    // För att erhålla värdena för de enskilda färgkomponenterna, skifta färgvärdet med motsvarande antal bitar.
    int alpha = (color >> 24) & 0xff;
    int red = (color >> 16) & 0xff;
    int green = (color >> 8) & 0xff;
    int blue = (color >> 0) & 0xff;

    System.out.println("The color of the pixel(0,0) is A=" + alpha + ",R=" + red + ",G=" + green + ",B=" + blue);
} finally {
    image.dispose();
}

// Utdata kan se ut så här:
// Färgen på pixel(0,0) är A=255,R=0,G=0,B=0.
```

### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


Hämtar en bildpixel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | Pixelns x‑position. |
| y | int | Pixelns y‑position. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The pixel color for the specified location.

**Example: The following example loads a raster image and obtains the color of an arbitrary pixel.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Hämta färgen på bildens övre vänstra pixel.
    com.aspose.imaging.Color color = rasterImage.getPixel(0, 0);

    // Erhåll värdena för de enskilda färgkomponenterna.
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


Ställer in en bilds 32‑bit ARGB‑pixel för den angivna positionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | Pixelns x‑position. |
| y | int | Pixelns y‑position. |
| argb32Color | int | 32‑bits ARGB‑pixel för den angivna positionen. |


**Example: The following example loads a raster image, and sets the color of an arbitrary pixel.**

``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Ställer in färgen på den övre vänstra pixeln.
    rasterImage.setArgb32Pixel(0, 0, com.aspose.imaging.Color.getAqua().toArgb());

    // Ett annat sätt är att skicka en instans av com.aspose.imaging.Color direkt.
    rasterImage.setPixel(0, 0, com.aspose.imaging.Color.getAqua());
} finally {
    image.dispose();
}
```

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.imaging.Color-}
```
public void setPixel(int x, int y, Color color)
```


Ställer in en bildpixel för den angivna positionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | Pixelns x‑position. |
| y | int | Pixelns y‑position. |
| color | [Color](../../com.aspose.imaging/color) | Pixelns färg för den angivna positionen. |


**Example: The following example loads a raster image, and sets the color of an arbitrary pixel.**

``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Ställer in färgen på den övre vänstra pixeln.
    rasterImage.setArgb32Pixel(0, 0, com.aspose.imaging.Color.getAqua().toArgb());

    // Ett annat sätt är att skicka en instans av com.aspose.imaging.Color direkt.
    rasterImage.setPixel(0, 0, com.aspose.imaging.Color.getAqua());
} finally {
    image.dispose();
}
```

### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


Läser hela skanningslinjen med det angivna skanningslinje‑indexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scanLineIndex | int | Nollbaserat index för skanningslinjen. |

**Returns:**
com.aspose.imaging.Color[] - Arrayen med pixelns färgvärden för skanningslinjen.
### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


Läser hela skanningslinjen med det angivna skanningslinje‑indexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scanLineIndex | int | Nollbaserat index för skanningslinjen. |

**Returns:**
int[] - Arrayen med 32‑bits ARGB‑färgvärden för skanningslinjen.
### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.imaging.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


Skriver hela skanningslinjen till det angivna skanningslinje‑indexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scanLineIndex | int | Nollbaserat index för skanningslinjen. |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | Arrayen med pixelns färger att skriva. |

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


Skriver hela skanningslinjen till det angivna skanningslinje‑indexet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scanLineIndex | int | Nollbaserat index för skanningslinjen. |
| argb32Pixels | int[] | Arrayen med 32‑bits ARGB‑färger att skriva. |

### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Laddar 32‑bit ARGB‑pixlar partiellt i paket.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Den önskade rektangeln. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader) | 32‑bits ARGB‑pixel‑laddaren. |


**Example: The following example shows how to load and process pixels of a raster image using your own partial processor.**
Följande exempel visar hur man laddar och bearbetar pixlar i en rasterbild med din egen partiella processor. Till exempel, överväg ett problem med att räkna helt transparenta pixlar i en bild. För att räkna transparenta pixlar med hjälp av partiell laddningsmekanism introduceras en separat klass TransparentArgb32PixelCounter som implementerar com.aspose.imaging.IPartialArgb32PixelLoader.
``` java

// Först, implementera com.aspose.imaging.IPartialArgb32PixelLoader för att räkna alla helt transparenta pixlar.
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

// Här är ett exempel på hur man använder räknaren.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Skapa en instans av com.aspose.imaging.IPartialArgb32PixelLoader och skicka den till com.aspose.imaging.RasterImage.LoadPartialArgb32Pixels
    TransparentArgb32PixelCounter counter = new TransparentArgb32PixelCounter();

    // Läs in pixlar för hela bilden. Vilken som helst rektangulär del av bilden kan anges som den första parametern till metoden com.aspose.imaging.RasterImage.loadPartialArgb32Pixels.
    rasterImage.loadPartialArgb32Pixels(rasterImage.getBounds(), counter);

    System.out.println("The number of fully transparent pixels is " + counter.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// Utdata kan se ut så här:
// Antalet helt transparenta pixlar är 55157
// Det totala antalet pixlar är 120400
```

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


Laddar pixlar partiellt i paket.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Den önskade rektangeln. |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.imaging/ipartialpixelloader) | Pixel‑laddaren. |


**Example: The following example shows how to load and process pixels of a raster image using your own partial processor.**
Följande exempel visar hur man läser in och bearbetar pixlar i en rasterbild med hjälp av din egen partiella processor. Till exempel, överväg ett problem med att räkna helt transparenta pixlar i en bild. För att räkna transparenta pixlar med hjälp av partiell inläsningsmekanism introduceras en separat klass TransparentPixelCounter som implementerar com.aspose.imaging.IPartialPixelLoader.
``` java

// Först, implementera com.aspose.imaging.IPartialPixelLoader för att räkna alla helt transparenta pixlar.
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

// Här är ett exempel på hur man använder räknaren.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Skapa en instans av com.aspose.imaging.IPartialPixelLoader och skicka den till com.aspose.imaging.RasterImage.loadPartialPixels
    TransparentPixelCounter counter = new TransparentPixelCounter();

    // Läs in pixlar för hela bilden. Vilken som helst rektangulär del av bilden kan anges som den första parametern till metoden com.aspose.imaging.RasterImage.loadPartialPixels.
    rasterImage.loadPartialPixels(rasterImage.getBounds(), counter);

    System.out.println("The number of fully transparent pixels is " + counter.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// Utdata kan se ut så här:
// Antalet helt transparenta pixlar är 55157
// Det totala antalet pixlar är 120400
```

### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


Laddar 32‑bit ARGB‑pixlar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln att ladda pixlar från. |

**Returns:**
int[] – Den inlästa 32‑bitars ARGB‑pixelarrayen.

**Example: The following example shows how to load and process pixels of a raster image.**
Följande exempel visar hur man läser in och bearbetar pixlar i en rasterbild. Pixlarna representeras som 32‑bitars heltalsvärden. Till exempel, överväg ett problem med att räkna helt transparenta pixlar i en bild.
``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Läs in pixlar för hela bilden. Vilken som helst rektangulär del av bilden kan anges som en parameter till metoden com.aspose.imaging.RasterImage.loadArgb32Pixels.
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


Laddar 64‑bit ARGB‑pixlar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln att ladda pixlar från. |

**Returns:**
long[] – Den inlästa 64‑bitars ARGB‑pixelarrayen.

**Example: The following example shows how to load and process pixels of a raster image.**
Följande exempel visar hur man läser in och bearbetar pixlar i en rasterbild. Pixlarna representeras som 64‑bitars heltalsvärden. Till exempel, överväg ett problem med att räkna helt transparenta pixlar i en bild.
``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\16rgba.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Läs in pixlar för hela bilden. Vilken som helst rektangulär del av bilden kan anges som en parameter till metoden com.aspose.imaging.RasterImage.loadArgb64Pixels.
    // Observera att själva bilden måste ha 16 bitar per prov, eftersom com.aspose.imaging.RasterImage.loadArgb64Pixels inte fungerar med 8 bitar per prov.
    // För att arbeta med 8 bitar per prov, använd den gamla goda metoden com.aspose.imaging.RasterImage.loadArgb32Pixels.
    long[] pixels = rasterImage.loadArgb64Pixels(rasterImage.getBounds());

    int count = 0;
    for (long pixel : pixels) {
        // Observera att alla färgkomponenter inklusive alfa representeras av 16‑bitars värden, så deras tillåtna värden ligger i intervallet [0, 63535].
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


Laddar 64‑bit ARGB‑pixlar partiellt i paket.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Den önskade rektangeln. |
| partialPixelLoader | [IPartialArgb64PixelLoader](../../com.aspose.imaging/ipartialargb64pixelloader) | Den 64‑bitars ARGB‑pixel‑laddaren. |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.imaging.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


Laddar pixlar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln att ladda pixlar från. |

**Returns:**
com.aspose.imaging.Color[] – Den inlästa pixelarrayen.

**Example: The following example shows how to load and process pixels of a raster image.**
Följande exempel visar hur man läser in och bearbetar pixlar i en rasterbild. Till exempel, överväg ett problem med att räkna helt transparenta pixlar i en bild.
``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Läs in pixlar för hela bilden. Vilken som helst rektangulär del av bilden kan anges som en parameter till metoden Aspose.Imaging.RasterImage.LoadPixels.
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


Läser in pixlar i CMYK‑format. Denna metod är föråldrad. Använd den mer effektiva `loadCmyk32Pixels(Rectangle)`‑metoden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln att ladda pixlar från. |

**Returns:**
com.aspose.imaging.CmykColor[] - Den laddade CMYK-pixelarrayen.
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


Laddar pixlar i CMYK‑format.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln att ladda pixlar från. |

**Returns:**
int[] - De laddade CMYK-pixlarna presenteras som 32-bitars heltalsvärden.
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Laddar rå bilddata med hjälp av den partiella bearbetningsmekanismen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Det önskade rektangulära området i bilden att ladda data från. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Inställningarna för rådata. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | Den rådata-läsaren. |


**Example: The following example shows how to extract pixels from the raw image data using RawDataSettings.**
Följande exempel visar hur man extraherar pixlar från råbilddata med hjälp av RawDataSettings. Till exempel, överväg ett problem med att räkna helt transparenta pixlar i en bild.
``` java

// Först, implementera en räknare. Vid rådata kan räknaren se ut så här:
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

        // Endast enkla format beaktas här för att förenkla koden.
        // Låt oss bara överväga bilder med 8 bitar per prov.
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
                        // Alfakanalen lagras sist, efter färgkomponenterna.
                        if (data[i + 3] == 0) {
                            this.count++;
                        }
                    }
                }
            }
            break;

            case com.aspose.imaging.PixelFormat.Grayscale: {
                if (channelBits.length == 2) {
                    // Gråskala Alfa
                    for (int i = 0; i < data.length; i += 2) {
                        // Alfakanalen lagras sist, efter färgkomponenterna.
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

// Här är huvudexemplet för att använda räknaren
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
    com.aspose.imaging.RawDataSettings settings = rasterImage.getRawDataSettings();

    TransparentPixelRawDataCounter rawDataLoader = new TransparentPixelRawDataCounter(settings);

    // Ladda pixlar för hela bilden. Vilken rektangulär del av bilden som helst kan anges som en parameter till metoden Aspose.Imaging.RasterImage.LoadRawData.
    rasterImage.loadRawData(rasterImage.getBounds(), settings, rawDataLoader);

    System.out.println("The number of fully transparent pixels is " + rawDataLoader.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// Utdata kan se ut så här:
// Antalet helt transparenta pixlar är 55157
// Det totala antalet pixlar är 120400
```

### loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Laddar rådata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln att ladda rådata från. |
| dstImageBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Målbildernas gränser. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Rådata-inställningarna att använda för laddade data. Observera att om data inte är i det angivna formatet kommer datakonvertering att utföras. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | Den rådata-läsaren. |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


Sparar rådata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Rådata. |
| dataOffset | int | Startoffset för rådata. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rådata-rektangeln. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Rådata-inställningarna som data befinner sig i. |

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.imaging.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


Sparar 32‑bit ARGB‑pixlarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln att spara pixlar till. |
| pixlar | int[] | Den 32-bitars ARGB-pixelarrayen. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
Följande exempel fyller det centrala området i en rasterbild med svarta pixlar med hjälp av metoden com.aspose.imaging.RasterImage.saveArgb32Pixels.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Den svarta fyrkanten
    int[] pixels = new int[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getBlack().toArgb();
    }

    // Rita den svarta fyrkanten i bildens centrum.
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


Sparar pixlarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln att spara pixlar till. |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | Pixelarrayen. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
Följande exempel fyller det centrala området i en rasterbild med svarta pixlar med hjälp av metoden com.aspose.imaging.RasterImage.savePixels.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Den svarta fyrkanten
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getBlack();
    }

    // Rita den svarta fyrkanten i bildens centrum.
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


Konverterar rasterbild till bitmapen.

**Returns:**
java.awt.image.BufferedImage - bitmapen

**Example: The following example converts a BMP image to a native Java bitmap.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;
    java.awt.image.BufferedImage bitmap = bmpImage.toBitmap();

    // Bearbeta den inhemska Java-bitmapen.
} finally {
    image.dispose();
}
```

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


Sparar pixlarna. Denna metod är föråldrad. Använd den mer effektiva `saveCmyk32Pixels(Rectangle, int[])`‑metoden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln att spara pixlar till. |
| pixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | CMYK-pixelarrayen. |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.imaging.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


Sparar pixlarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln att spara pixlar till. |
| pixlar | int[] | CMYK-pixlarna presenterade som 32‑bits heltalsvärden. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
Följande exempel fyller det centrala området i en rasterbild med svarta pixlar med hjälp av metoden com.aspose.imaging.RasterImage.saveCmyk32Pixels.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Hämta en heltalsrepresentation av svart i CMYK-färgrymden.
    int blackCmyk = com.aspose.imaging.CmykColorHelper.toCmyk(com.aspose.imaging.Color.getBlack());

    // Den svarta fyrkanten.
    int[] pixels = new int[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = blackCmyk;
    }

    // Rita den svarta fyrkanten i bildens centrum.
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


Ställer in upplösningen för detta `RasterImage`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dpiX | double | Den horisontella upplösningen, i punkter per tum, för `RasterImage`. |
| dpiY | double | Den vertikala upplösningen, i punkter per tum, för `RasterImage`. |


**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Hämta horisontell och vertikal upplösning för bilden
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Använd SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // Utdata kan se ut så här:
    // Den horisontella upplösningen, i pixlar per tum: 300.0
    // Den vertikala upplösningen, i pixlar per tum: 300.0
    // Ställ in upplösningsvärden till 96 dpi
    // Den horisontella upplösningen, i pixlar per tum: 96.0
    // Den vertikala upplösningen, i pixlar per tum: 96.0
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Ställer in bildpaletten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Paletten att ställa in. |
| updateColors | boolean | om den är inställd på `true` uppdateras färgerna enligt den nya paletten; annars förblir färgindexen oförändrade. Observera att oförändrade index kan krascha bilden vid inläsning om vissa index saknar motsvarande palettposter. |

### autoRotate() {#autoRotate--}
```
public final void autoRotate()
```


Roterar automatiskt bilden baserat på orienteringsdata som extraheras från Exif‑metadata. Denna metod säkerställer att bilder visas i korrekt orientering, förbättrar användarupplevelsen och eliminerar behovet av manuella justeringar. Genom att analysera Exif‑information roteras bilden därefter, vilket ger en sömlös visningsupplevelse på olika plattformar och enheter. Denna automatiserade rotationsprocess förenklar bildhantering och förbättrar den övergripande användbarheten, särskilt vid hantering av stora bildbatcher med varierande orienteringar.

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ändrar bildens storlek med utökade alternativ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | int | Den nya bredden. |
| newHeight | int | Den nya höjden. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Inställningarna för storleksändring. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Rotera bilden kring centrum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |
| resizeProportionally | boolean | om den är inställd på `true` kommer bildens storlek att ändras enligt den roterade rektangelns (hörnpunkternas) projektioner, i annat fall lämnas dimensionerna orörda och endast bildens innehåll roteras. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Färgen på bakgrunden. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Rotera bilden kring centrum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| angle | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarisering av en bild med fördefinierad tröskel

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| threshold | byte | Tröskelvärde. Om motsvarande gråvärde för en pixel är större än tröskeln tilldelas värdet 255, annars 0. |


**Example: The following example binarizes a raster image with the predefined threshold.**
Följande exempel binariserar en rasterbild med den fördefinierade tröskeln. Binariserade bilder innehåller endast två färger – svart och vit.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Binarisera bilden med ett tröskelvärde på 127.
    // Om ett motsvarande gråvärde för en pixel är större än 127, tilldelas ett värde på 255, annars 0.
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


Binarisering av en bild med Otsu-tröskling


**Example: The following example binarizes a raster image with Otsu thresholding.**
Följande exempel binariserar en rasterbild med Otsu‑tröskling. Binariserade bilder innehåller endast två färger – svart och vit.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Binarisera bilden med Otsu-tröskling.
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


Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integralbildströskling

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightnessDifference | double | Ljusstyrkeskillnaden mellan pixeln och medelvärdet av ett s x s-fönster av pixlar centrerade kring denna pixel. |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integralbildströskling

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightnessDifference | double | Ljusstyrkeskillnaden mellan pixeln och medelvärdet av ett s x s-fönster av pixlar centrerade kring denna pixel. |
| windowSize | int | Storleken på ett s x s-fönster av pixlar centrerade kring denna pixel. |


**Example: The following example binarizes a raster image with Bradley's adaptive thresholding algorithm with the specified window size.**
Följande exempel binariserar en rasterbild med Bradleys adaptiva trösklingsalgoritm med den angivna fönsterstorleken. Binariserade bilder innehåller endast två färger – svart och vit.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Binarisera bilden med en ljusstyrkeskillnad på 5. Ljusstyrkan är skillnaden mellan en pixel och medelvärdet av ett 10 × 10‑fönster av pixlar centrerade kring den pixeln.
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


Blandar denna bildinstans med `overlay`-bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | Bakgrundsbildens blandningsursprung. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | Överlagringsbilden. |
| overlayArea | [Rectangle](../../com.aspose.imaging/rectangle) | Överlagringsområdet. |

### blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-}
```
public void blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)
```


Blandar denna bildinstans med `overlay`-bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | Bakgrundsbildens blandningsursprung. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | Överlagringsbilden. |
| overlayArea | [Rectangle](../../com.aspose.imaging/rectangle) | Överlagringsområdet. |
| overlayAlpha | byte | Överlagringsalfa. |

### blend(Point origin, RasterImage overlay) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-}
```
public final void blend(Point origin, RasterImage overlay)
```


Blandar den här bildinstansen med `overlay` med alfa == 255.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | Bakgrundsbildens blandningsursprung. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | Överlagringen. |

### blend(Point origin, RasterImage overlay, byte overlayAlpha) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-byte-}
```
public final void blend(Point origin, RasterImage overlay, byte overlayAlpha)
```


Blandar den här bildinstansen med `overlay`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | Bakgrundsbildens blandningsursprung. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | Överlagringen. |
| overlayAlpha | byte | Överlagringsalfa. |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformation av en bild till dess gråskale-representation


**Example: The following example transforms a colored raster image to its grayscale representation.**
Följande exempel omvandlar en färgad rasterbild till dess gråskale‑representation. Gråskalebilder består uteslutande av gråtoner och innehåller endast intensitetsinformation.
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


Normaliserar bildens histogram \\u2014 justera pixelvärden för att använda hela tillgängliga intervallet.

### autoBrightnessContrast() {#autoBrightnessContrast--}
```
public void autoBrightnessContrast()
```


Automatisk adaptiv ljusstyrke- och kontrastnormalisering för hela bilden.

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Justering av bildens ljusstyrka.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightness | int | Ljusstyrkevärde. |


**Example: The following example performs brightness correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Ställ in ljusstyrkevärdet. De accepterade värdena för ljusstyrka ligger i intervallet [-255, 255].
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


Bildkontrast

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| contrast | float | Kontrastvärde (i intervallet [-100; 100]) |


**Example: The following example performs contrast correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Ställ in kontrastvärdet. De accepterade värdena för kontrast ligger i intervallet [-100f, 100f].
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


Bädda in digital signatur baserad på angivet lösenord i bilden med hjälp av steganografi.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lösenord | java.lang.String | Lösenordet som används för att generera digitala signaturdata |


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


Beräknar procentuell likhet mellan den extraherade datan och det ursprungliga lösenordet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lösenord | java.lang.String | Lösenordet som används för att extrahera den inbäddade datan. |

**Returns:**
int - Procentuell likhetsvärde.
### isDigitalSigned(String password) {#isDigitalSigned-java.lang.String-}
```
public boolean isDigitalSigned(String password)
```


Utför en snabb kontroll för att avgöra om bilden är digitalt signerad, med det angivna lösenordet och tröskeln.

--------------------

Denna metod tillhandahåller den snabbaste detektionen genom att utnyttja `GetSignPercentage`. När den extraherade datan uppfyller det angivna tröskelvärdet, hoppar över ytterligare extraktionssteg som syftar till att förbättra detekteringsnoggrannheten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lösenord | java.lang.String | Lösenordet för att kontrollera signeringen. |

**Returns:**
boolean - Sant om bilden är signerad, annars falskt.
### isDigitalSigned(String password, int percentageThreshold) {#isDigitalSigned-java.lang.String-int-}
```
public boolean isDigitalSigned(String password, int percentageThreshold)
```


Utför en snabb kontroll för att avgöra om bilden är digitalt signerad, med det angivna lösenordet och tröskeln.

--------------------

Denna metod tillhandahåller den snabbaste detektionen genom att utnyttja `GetSignPercentage`. När den extraherade datan uppfyller det angivna tröskelvärdet, hoppar över ytterligare extraktionssteg som syftar till att förbättra detekteringsnoggrannheten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lösenord | java.lang.String | Lösenordet för att kontrollera signeringen. |
| percentageThreshold | int | Tröskelvärdet (i procent)[0-100] som avgör om bilden anses vara signerad. Om det inte anges, kommer ett standardtröskelvärde (`75`) att tillämpas. |

**Returns:**
boolean - Sant om bilden är signerad, annars falskt.
### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Gamma-korrigering av en bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gammaRed | float | Gamma för röd kanalkoefficient |
| gammaGreen | float | Gamma för grön kanalkoefficient |
| gammaBlue | float | Gamma för blå kanalens koefficient |


**Example: The following example performs gamma-correction of an image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Ange individuella gamma-koefficienter för röd, grön och blå kanaler.
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


Gamma-korrigering av en bild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| gamma | float | Gamma för röd, grön och blå kanalernas koefficient |


**Example: The following example performs gamma-correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Ange gamma-koefficient för röd, grön och blå kanaler.
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


Hämtar snedvinkeln. Denna metod är tillämplig på skannade textdokument för att bestämma snedvinkeln vid skanning.

**Returns:**
float - Snedvinkeln, i grader.
### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


Normaliserar vinkeln. Denna metod är tillämplig på skannade textdokument för att bli av med den snedvridna skanningen. Metoden använder \#getSkewAngle.getSkewAngle och [Image.rotate(float)](../../com.aspose.imaging/image\#rotate-float-) metoder.

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Normaliserar vinkeln. Denna metod är tillämplig på skannade textdokument för att bli av med den snedvridna skanningen. Metoden använder \#getSkewAngle.getSkewAngle och \#rotate(float, boolean, Color).rotate(float, boolean, Color) metoder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resizeProportionally | boolean | om den är inställd på `true` kommer bildens storlek att ändras enligt den roterade rektangelns (hörnpunkternas) projektioner, i annat fall lämnas dimensionerna orörda och endast bildens innehåll roteras. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Färgen på bakgrunden. |


**Example: Skew is an artifact that might appear during document scanning process when the text/images of the document get rotated at a slight angle.**
Snedvridning är ett artefakt som kan uppstå under dokumentskanningsprocessen när texten/bilderna i dokumentet roteras med en liten vinkel. Det kan ha olika orsaker men den vanligaste är att papperet hamnar fel under en skanning. Därför är deskew processen för att upptäcka och åtgärda detta problem på skannade filer (dvs. bitmap) så att deskewade dokument har texten/bilderna korrekt och horisontellt justerade.
``` java
String dir = "c:\\aspose.imaging\\issues\\java\\1461\\";

String inputFilePath = dir + "skewed.png";
String outputFilePath = dir + "skewed.out.png";

// Bli av med den snedvridna skanningen med standardparametrar
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


Filtrerar den angivna rektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Alternativen. |


**Example: The following example applies various types of filters to a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applicera ett medianfilter med en rektangelstorlek på 5 på hela bilden.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    rasterImage.save(dir + "sample.MedianFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applicera ett bilateralt utjämningsfilter med en kärnstorlek på 5 på hela bilden.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    rasterImage.save(dir + "sample.BilateralSmoothingFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applicera ett Gaussiskt oskärpefilter med en radie på 5 och ett sigma‑värde på 4,0 på hela bilden.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussianBlurFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applicera ett Gauss‑Wiener-filter med en radie på 5 och ett jämnvärde på 4,0 på hela bilden.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applicera ett rörelse‑Wiener-filter med en längd på 5, ett jämnvärde på 4,0 och en vinkel på 90,0 grader på hela bilden.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.save(dir + "sample.MotionWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applicera ett skärpningsfilter med en kärnstorlek på 5 och ett sigma‑värde på 4,0 på hela bilden.
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


Ersätter en färg med en annan med tillåten skillnad och bevarar original‑alfavärdet för att spara mjuka kanter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.imaging/color) | Gammal färg att ersätta. |
| oldColorDiff | byte | Tillåten skillnad i gammal färg för att kunna bredda den ersatta färgtonen. |
| newColor | [Color](../../com.aspose.imaging/color) | Ny färg att ersätta den gamla färgen med. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Ersätter en färg med en annan med tillåten skillnad och bevarar original‑alfavärdet för att spara mjuka kanter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oldColorArgb | int | Gammalt färg-ARGB-värde som ska ersättas. |
| oldColorDiff | byte | Tillåten skillnad i gammal färg för att kunna bredda den ersatta färgtonen. |
| newColorArgb | int | Nytt färg-ARGB-värde att ersätta den gamla färgen med. |

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.imaging.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


Ersätter alla icke‑transparenta färger med ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. Obs: om du använder den på bilder utan transparens kommer alla färger att ersättas med en enda.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.imaging/color) | Ny färg att ersätta icke‑transparenta färger med. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Ersätter alla icke‑transparenta färger med ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. Obs: om du använder den på bilder utan transparens kommer alla färger att ersättas med en enda.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newColorArgb | int | Nytt färg-ARGB‑värde att ersätta icke‑transparenta färger med. |

