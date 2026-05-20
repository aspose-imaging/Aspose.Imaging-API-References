---
title: "RasterImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta un'immagine raster che supporta operazioni grafiche raster."
type: docs
weight: 91
url: /it/java/com.aspose.imaging/rasterimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image)

**All Implemented Interfaces:**
[com.aspose.imaging.IRasterImageArgb32PixelLoader](../../com.aspose.imaging/irasterimageargb32pixelloader), com.aspose.internal.IPixelsSaver, [com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public abstract class RasterImage extends Image implements IRasterImageArgb32PixelLoader, IPixelsSaver, IHasXmpData
```

Rappresenta un'immagine raster che supporta operazioni grafiche raster.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Ottiene o imposta un valore che indica se i componenti dell'immagine devono essere premoltiplicati. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Ottiene o imposta un valore che indica se i componenti dell'immagine devono essere premoltiplicati. |
| [getUseRawData()](#getUseRawData--) | Ottiene o imposta un valore che indica se utilizzare il caricamento di dati grezzi quando è disponibile. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Ottiene o imposta un valore che indica se utilizzare il caricamento di dati grezzi quando è disponibile. |
| [getUpdateXmpData()](#getUpdateXmpData--) | Ottiene o imposta un valore che indica se aggiornare i metadati XMP. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Ottiene o imposta un valore che indica se aggiornare i metadati XMP. |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Ottiene o imposta il convertitore di colore indicizzato |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-) | Ottiene o imposta il convertitore di colore indicizzato |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Ottiene o imposta il convertitore di colore personalizzato |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.imaging.IColorConverter-) | Ottiene o imposta il convertitore di colore personalizzato |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Ottiene o imposta l'indice di fallback da utilizzare quando l'indice della palette è fuori dai limiti |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Ottiene o imposta l'indice di fallback da utilizzare quando l'indice della palette è fuori dai limiti |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [isUsePalette()](#isUsePalette--) | Restituisce un valore che indica se la tavolozza dell'immagine è utilizzata. |
| [getRawDataFormat()](#getRawDataFormat--) | Ottiene il formato dei dati grezzi. |
| [getRawLineSize()](#getRawLineSize--) | Ottiene la dimensione della riga grezza in byte. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Ottiene un valore che indica se il caricamento di dati grezzi è disponibile. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Ottiene o imposta la risoluzione orizzontale, in pixel per pollice, di questo `RasterImage`. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Ottiene o imposta la risoluzione orizzontale, in pixel per pollice, di questo `RasterImage`. |
| [getVerticalResolution()](#getVerticalResolution--) | Ottiene o imposta la risoluzione verticale, in pixel per pollice, di questo `RasterImage`. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Ottiene o imposta la risoluzione verticale, in pixel per pollice, di questo `RasterImage`. |
| [hasTransparentColor()](#hasTransparentColor--) | Ottiene un valore che indica se questa istanza di [RasterImage](../../com.aspose.imaging/rasterimage) ha un colore trasparente. |
| [hasAlpha()](#hasAlpha--) | Ottiene un valore che indica se questa istanza ha alfa. |
| [getTransparentColor()](#getTransparentColor--) | Ottiene il colore trasparente dell'immagine. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Imposta un valore che indica se questa istanza di [RasterImage](../../com.aspose.imaging/rasterimage) ha un colore trasparente. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Ottiene il colore trasparente dell'immagine. |
| [getImageOpacity()](#getImageOpacity--) | Ottiene l'opacità di questa immagine. |
| [removeMetadata()](#removeMetadata--) | Rimuove i metadati di questa istanza di immagine impostando il valore di `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) a `null`. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Recupera la data e l'ora in cui l'immagine della risorsa ha subito l'ultima modifica. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | Esegue il dithering sull'immagine corrente. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Esegue il dithering sull'immagine corrente. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-) | Ottiene l'array di pixel predefinito utilizzando il caricatore di pixel parziali. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialRawDataLoader-com.aspose.imaging.RawDataSettings-) | Ottiene l'array di dati grezzi predefinito utilizzando il caricatore di pixel parziali. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.imaging.Rectangle-) | Ottiene l'array di pixel ARGB a 32 bit predefinito. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-) | Ottiene l'array di dati grezzi predefinito. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Ottiene un pixel ARGB a 32 bit dell'immagine. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Ottiene un pixel dell'immagine. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Imposta un pixel ARGB a 32 bit dell'immagine per la posizione specificata. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.imaging.Color-) | Imposta un pixel dell'immagine per la posizione specificata. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Legge l'intera riga di scansione mediante l'indice di riga di scansione specificato. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Legge l'intera riga di scansione mediante l'indice di riga di scansione specificato. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.imaging.Color---) | Scrive l'intera riga di scansione nell'indice di riga di scansione specificato. |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Scrive l'intera riga di scansione nell'indice di riga di scansione specificato. |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-) | Carica parzialmente i pixel ARGB a 32 bit per pacchetti. |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-) | Carica i pixel parzialmente per pacchetti. |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.imaging.Rectangle-) | Carica i pixel ARGB a 32 bit. |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.imaging.Rectangle-) | Carica i pixel ARGB a 64 bit. |
| [loadPartialArgb64Pixels(Rectangle rectangle, IPartialArgb64PixelLoader partialPixelLoader)](#loadPartialArgb64Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb64PixelLoader-) | Carica parzialmente i pixel ARGB a 64 bit per pacchetti. |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.imaging.Rectangle-) | Carica i pixel. |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.imaging.Rectangle-) | Carica i pixel in formato CMYK. |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.imaging.Rectangle-) | Carica i pixel in formato CMYK. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-) | Carica i dati grezzi dell'immagine utilizzando il meccanismo di elaborazione parziale. |
| [loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-) | Carica i dati grezzi. |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-) | Salva i dati grezzi. |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.imaging.Rectangle-int---) | Salva i pixel ARGB a 32 bit. |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.imaging.Rectangle-com.aspose.imaging.Color---) | Salva i pixel. |
| [toBitmap()](#toBitmap--) | Converte l'immagine raster in bitmap. |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.CmykColor---) | Salva i pixel. |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.imaging.Rectangle-int---) | Salva i pixel. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Imposta la risoluzione per questo `RasterImage`. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Imposta la tavolozza dell'immagine. |
| [autoRotate()](#autoRotate--) | Ruota automaticamente l'immagine in base ai dati di orientamento estratti dai metadati Exif. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ridimensiona l'immagine con opzioni estese. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Ruota l'immagine attorno al centro. |
| [rotate(float angle)](#rotate-float-) | Ruota l'immagine attorno al centro. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarizzazione di un'immagine con soglia predefinita |
| [binarizeOtsu()](#binarizeOtsu--) | Binarizzazione di un'immagine con soglia di Otsu |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley basato sulla sogliatura dell'immagine integrale |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley basato sulla sogliatura dell'immagine integrale |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-) | Mescola questa istanza di immagine con l'immagine `overlay`. |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | Mescola questa istanza di immagine con l'immagine `overlay`. |
| [blend(Point origin, RasterImage overlay)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-) | Unisce questa istanza di immagine con il `overlay` con alfa == 255. |
| [blend(Point origin, RasterImage overlay, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-byte-) | Unisce questa istanza di immagine con il `overlay`. |
| [grayscale()](#grayscale--) | Trasformazione di un'immagine nella sua rappresentazione in scala di grigi |
| [normalizeHistogram()](#normalizeHistogram--) | Normalizza l'istogramma dell'immagine \\u2014 regola i valori dei pixel per utilizzare l'intera gamma disponibile. |
| [autoBrightnessContrast()](#autoBrightnessContrast--) | Normalizzazione automatica adattiva di luminosità e contrasto per l'intera immagine. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Regola la luminosità dell'immagine. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Contrasto dell'immagine |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | Incorpora una firma digitale basata sulla password fornita nell'immagine usando la steganografia. |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | Calcola la percentuale di somiglianza tra i dati estratti e la password originale. |
| [isDigitalSigned(String password)](#isDigitalSigned-java.lang.String-) | Esegue un controllo rapido per determinare se l'immagine è firmata digitalmente, usando la password fornita e la soglia. |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | Esegue un controllo rapido per determinare se l'immagine è firmata digitalmente, usando la password fornita e la soglia. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Correzione gamma di un'immagine. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Correzione gamma di un'immagine. |
| [getSkewAngle()](#getSkewAngle--) | Ottiene l'angolo di inclinazione. |
| [normalizeAngle()](#normalizeAngle--) | Normalizza l'angolo. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | Normalizza l'angolo. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Filtra il rettangolo specificato. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.imaging.Color-byte-com.aspose.imaging.Color-) | Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.imaging.Color-) | Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci. |

## Example: This example shows how to load pixel information in an array of colors, manipulates the array and set it back to the image.

``` java
String dir = "c:\\temp\\";

// Crea un'istanza di GifOptions e imposta le sue varie proprietà, inclusa la proprietà Source
com.aspose.imaging.imageoptions.GifOptions gifOptions = new com.aspose.imaging.imageoptions.GifOptions();
gifOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "output.gif", false));

// Crea un'istanza di Image
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(gifOptions, 500, 500);
try {
    // Ottieni i pixel dell'immagine specificando l'area come confine dell'immagine
    com.aspose.imaging.Color[] pixels = image.loadPixels(image.getBounds());

    // Itera sull'array e imposta il colore dei pixel indicizzati alternativi
    for (int index = 0; index < pixels.length; index++) {
        if (index % 2 == 0) {
            // Imposta il colore del pixel indicizzato su giallo
            pixels[index] = com.aspose.imaging.Color.getYellow();
        } else {
            // Imposta il colore del pixel indicizzato su blu
            pixels[index] = com.aspose.imaging.Color.getBlue();
        }
    }

    // Applica le modifiche dei pixel all'immagine
    image.savePixels(image.getBounds(), pixels);

    // Salva tutte le modifiche.
    image.save();
} finally {
    image.dispose();
}
```

### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Ottiene o imposta un valore che indica se i componenti dell'immagine devono essere premoltiplicati.

**Returns:**
boolean - `true` se i componenti dell'immagine devono essere premoltiplicati; altrimenti, `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Ottiene o imposta un valore che indica se i componenti dell'immagine devono essere premoltiplicati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | `true` se i componenti dell'immagine devono essere premoltiplicati; altrimenti, `false`. |


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

    // Salva i pixel per l'intera immagine.
    rasterImage.savePixels(rasterImage.getBounds(), colors);

    // I pixel sono memorizzati nell'immagine originale nella forma non premoltiplicata.
    // È necessario specificare esplicitamente l'opzione corrispondente per ottenere componenti di colore premoltiplicati.
    // I componenti di colore premoltiplicati sono calcolati con le formule:
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


Ottiene o imposta un valore che indica se utilizzare il caricamento di dati grezzi quando è disponibile.

**Returns:**
boolean - `true` se si utilizza il caricamento di dati grezzi quando è disponibile; altrimenti, `false`.
### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


Ottiene o imposta un valore che indica se utilizzare il caricamento di dati grezzi quando è disponibile.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | `true` se si utilizza il caricamento di dati grezzi quando è disponibile; altrimenti, `false`. |

### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


Ottiene o imposta un valore che indica se aggiornare i metadati XMP.

**Returns:**
boolean - `true` se si aggiornano i metadati XMP; altrimenti, `false`.
### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


Ottiene o imposta un valore che indica se aggiornare i metadati XMP.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | `true` se si aggiornano i metadati XMP; altrimenti, `false`. |

### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


Ottiene o imposta il convertitore di colore indicizzato

**Returns:**
[IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) - The indexed color converter
### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


Ottiene o imposta il convertitore di colore indicizzato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) | Il convertitore di colore indicizzato |

### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


Ottiene o imposta il convertitore di colore personalizzato

**Returns:**
[IColorConverter](../../com.aspose.imaging/icolorconverter) - The custom color converter
### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.imaging.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


Ottiene o imposta il convertitore di colore personalizzato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.imaging/icolorconverter) | Il convertitore di colore personalizzato |

### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


Ottiene o imposta l'indice di fallback da utilizzare quando l'indice della palette è fuori dai limiti

**Returns:**
int - L'indice di fallback da utilizzare quando l'indice della tavolozza è fuori dai limiti
### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


Ottiene o imposta l'indice di fallback da utilizzare quando l'indice della palette è fuori dai limiti

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | L'indice di fallback da utilizzare quando l'indice della tavolozza è fuori dai limiti |

### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


Ottiene le impostazioni attuali dei dati grezzi. Nota che, quando si usano queste impostazioni, i dati vengono caricati senza conversione.

**Returns:**
[RawDataSettings](../../com.aspose.imaging/rawdatasettings)
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Restituisce un valore che indica se la tavolozza dell'immagine è utilizzata.

Valore: `true` se la tavolozza è usata nell'immagine; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se la tavolozza dell'immagine è usata.
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Ottiene il formato dei dati grezzi.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.

**Example: The following example loads raster images and prints information about raw data format and alpha channel.**

``` java

// I file immagine da caricare.
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

// L'output potrebbe apparire così:
// ImageFile=c:\temp\sample.bmp FileFormat=Rgb24Bpp, used channels: 8,8,8 HasAlpha=false
// ImageFile=c:\temp\alpha.png FileFormat=RGBA32Bpp, used channels: 8,8,8,8 HasAlpha=true
```

### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Ottiene la dimensione della riga grezza in byte.

**Returns:**
int - La dimensione della riga grezza in byte.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


Ottiene un valore che indica se il caricamento di dati grezzi è disponibile.

**Returns:**
boolean - `true` se questo caricamento di dati grezzi è disponibile; altrimenti, `false`.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Ottiene o imposta la risoluzione orizzontale, in pixel per pollice, di questo `RasterImage`.

**Returns:**
double - La risoluzione orizzontale.

Nota: per impostazione predefinita questo valore è sempre 96 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. Potresti considerare l'uso del metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.

**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Ottieni la risoluzione orizzontale e verticale dell'immagine
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Usa il metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // L'output potrebbe apparire così:
    // La risoluzione orizzontale, in pixel per pollice: 300.0
    // La risoluzione verticale, in pixel per pollice: 300.0
    // Imposta i valori di risoluzione a 96 dpi
    // La risoluzione orizzontale, in pixel per pollice: 96.0
    // La risoluzione verticale, in pixel per pollice: 96.0
} finally {
    image.dispose();
}
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Ottiene o imposta la risoluzione orizzontale, in pixel per pollice, di questo `RasterImage`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | La risoluzione orizzontale. |

Nota: per impostazione predefinita questo valore è sempre 96 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. Potresti considerare l'uso del metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Ottiene o imposta la risoluzione verticale, in pixel per pollice, di questo `RasterImage`.

**Returns:**
double - La risoluzione verticale.

Nota: per impostazione predefinita questo valore è sempre 96 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. Potresti considerare l'uso del metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.

**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Ottieni la risoluzione orizzontale e verticale dell'immagine
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Usa il metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // L'output potrebbe apparire così:
    // La risoluzione orizzontale, in pixel per pollice: 300.0
    // La risoluzione verticale, in pixel per pollice: 300.0
    // Imposta i valori di risoluzione a 96 dpi
    // La risoluzione orizzontale, in pixel per pollice: 96.0
    // La risoluzione verticale, in pixel per pollice: 96.0
} finally {
    image.dispose();
}
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Ottiene o imposta la risoluzione verticale, in pixel per pollice, di questo `RasterImage`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | La risoluzione verticale. |

Nota: per impostazione predefinita questo valore è sempre 96 poiché le diverse piattaforme non possono restituire la risoluzione dello schermo. Potresti considerare l'uso del metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata. |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Ottiene un valore che indica se questa istanza di [RasterImage](../../com.aspose.imaging/rasterimage) ha un colore trasparente.

--------------------

L'implementazione di base restituisce effettivamente `` se non viene sovrascritta in un'implementazione specifica che supporta questa funzionalità. Questa proprietà è principalmente utilizzata da [FileFormat.Apng](../../com.aspose.imaging/fileformat\#Apng), [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png), [FileFormat.Gif](../../com.aspose.imaging/fileformat\#Gif), [FileFormat.Tga](../../com.aspose.imaging/fileformat\#Tga) per impostare un colore trasparente se un'immagine non supporta la trasparenza tramite canale alfa.

**Returns:**
boolean - un valore che indica se questa istanza di [RasterImage](../../com.aspose.imaging/rasterimage) ha un colore trasparente.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Ottiene un valore che indica se questa istanza ha alfa.

**Returns:**
boolean - `true` se questa istanza ha alfa; altrimenti, `false`.

**Example: The following example loads raster images and prints information about raw data format and alpha channel.**

``` java

// I file immagine da caricare.
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

// L'output potrebbe apparire così:
// ImageFile=c:\temp\sample.bmp FileFormat=Rgb24Bpp, used channels: 8,8,8 HasAlpha=false
// ImageFile=c:\temp\alpha.png FileFormat=RGBA32Bpp, used channels: 8,8,8,8 HasAlpha=true
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Ottiene il colore trasparente dell'immagine.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Imposta un valore che indica se questa istanza di [RasterImage](../../com.aspose.imaging/rasterimage) ha un colore trasparente.

--------------------

L'implementazione di base restituisce effettivamente `` se non viene sovrascritta in un'implementazione specifica che supporta questa funzionalità. Questa proprietà è principalmente utilizzata da [FileFormat.Apng](../../com.aspose.imaging/fileformat\#Apng), [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png), [FileFormat.Gif](../../com.aspose.imaging/fileformat\#Gif), [FileFormat.Tga](../../com.aspose.imaging/fileformat\#Tga) per impostare un colore trasparente se un'immagine non supporta la trasparenza tramite canale alfa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean | un valore che indica se questa istanza di [RasterImage](../../com.aspose.imaging/rasterimage) ha un colore trasparente. |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Ottiene il colore trasparente dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Ottiene l'opacità di questa immagine.

**Returns:**
float - Il valore di opacità compreso tra 0.0 (completamente trasparente) e 1.0 (completamente opaco).
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Rimuove i metadati di questa istanza di immagine impostando il valore di `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) a `null`.

### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Recupera la data e l'ora in cui l'immagine di risorsa ha subito l'ultima modifica. Questo metodo fornisce metadati preziosi, consentendo agli utenti di tracciare e gestire efficacemente gli aggiornamenti del file immagine. Accedendo a queste informazioni, gli utenti possono garantire l'integrità e l'aggiornamento delle proprie risorse immagine, facilitando decisioni informate sull'uso e la manutenzione delle immagini.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| useDefault | boolean | se impostato su `true` utilizza le informazioni da FileInfo come valore predefinito. |

**Returns:**
java.util.Date - La data e l'ora in cui l'immagine di risorsa è stata modificata l'ultima volta.
### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


Esegue il dithering sull'immagine corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ditheringMethod | int | Il metodo di dithering. |
| bitsCount | int | Il conteggio finale dei bit per il dithering. |


**Example: The following example loads a raster image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Esegui il dithering a soglia usando una palette di colori a 4 bit che contiene 16 colori.
    // Più bit sono specificati, maggiore è la qualità e più grande è la dimensione dell'immagine di output.
    // Nota che al momento sono supportate solo palette a 1 bit, 4 bit e 8 bit.
    rasterImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.save(dir + "sample.ThresholdDithering4.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Esegui il dithering Floyd usando una palette di colori a 1 bit che contiene solo 2 colori - nero e bianco.
    // Più bit sono specificati, maggiore è la qualità e più grande è la dimensione dell'immagine di output.
    // Nota che al momento sono supportate solo palette a 1 bit, 4 bit e 8 bit.
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


Esegue il dithering sull'immagine corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ditheringMethod | int | Il metodo di dithering. |
| bitsCount | int | Il conteggio finale dei bit per il dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette personalizzata per il dithering. |

### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Ottiene l'array di pixel predefinito utilizzando il caricatore di pixel parziali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo per cui ottenere i pixel. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader) | Il caricatore di pixel parziale. |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialRawDataLoader-com.aspose.imaging.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


Ottiene l'array di dati grezzi predefinito utilizzando il caricatore di pixel parziali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo per cui ottenere i pixel. |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | Il caricatore parziale di dati grezzi. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Le impostazioni dei dati grezzi. |

### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


Ottiene l'array di pixel ARGB a 32 bit predefinito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo per cui ottenere i pixel. |

**Returns:**
int[] - L'array di pixel predefinito.
### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


Ottiene l'array di dati grezzi predefinito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo da cui ottenere i dati grezzi. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Le impostazioni dei dati grezzi. |

**Returns:**
byte[] - L'array di dati grezzi predefinito.
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


Ottiene un pixel ARGB a 32 bit dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La posizione x del pixel. |
| y | int | La posizione y del pixel. |

**Returns:**
int - Il pixel ARGB a 32 bit per la posizione specificata.

**Example: The following example loads a raster image and obtains the color of an arbitrary pixel represented as a 32-bit integer value.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Ottieni una rappresentazione intera del colore del pixel in alto a sinistra dell'immagine.
    int color = rasterImage.getArgb32Pixel(0, 0);

    // Per ottenere i valori dei singoli componenti di colore, sposta il valore del colore di un numero corrispondente di bit.
    int alpha = (color >> 24) & 0xff;
    int red = (color >> 16) & 0xff;
    int green = (color >> 8) & 0xff;
    int blue = (color >> 0) & 0xff;

    System.out.println("The color of the pixel(0,0) is A=" + alpha + ",R=" + red + ",G=" + green + ",B=" + blue);
} finally {
    image.dispose();
}

// L'output potrebbe apparire così:
// Il colore del pixel(0,0) è A=255,R=0,G=0,B=0
```

### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


Ottiene un pixel dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La posizione x del pixel. |
| y | int | La posizione y del pixel. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The pixel color for the specified location.

**Example: The following example loads a raster image and obtains the color of an arbitrary pixel.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Ottieni il colore del pixel in alto a sinistra dell'immagine.
    com.aspose.imaging.Color color = rasterImage.getPixel(0, 0);

    // Ottieni i valori dei singoli componenti di colore
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


Imposta un pixel ARGB a 32 bit dell'immagine per la posizione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La posizione x del pixel. |
| y | int | La posizione y del pixel. |
| argb32Color | int | Il pixel ARGB a 32 bit per la posizione specificata. |


**Example: The following example loads a raster image, and sets the color of an arbitrary pixel.**

``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Imposta il colore del pixel in alto a sinistra.
    rasterImage.setArgb32Pixel(0, 0, com.aspose.imaging.Color.getAqua().toArgb());

    // Un altro modo è passare direttamente un'istanza di com.aspose.imaging.Color
    rasterImage.setPixel(0, 0, com.aspose.imaging.Color.getAqua());
} finally {
    image.dispose();
}
```

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.imaging.Color-}
```
public void setPixel(int x, int y, Color color)
```


Imposta un pixel dell'immagine per la posizione specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | int | La posizione x del pixel. |
| y | int | La posizione y del pixel. |
| color | [Color](../../com.aspose.imaging/color) | Il colore del pixel per la posizione specificata. |


**Example: The following example loads a raster image, and sets the color of an arbitrary pixel.**

``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Imposta il colore del pixel in alto a sinistra.
    rasterImage.setArgb32Pixel(0, 0, com.aspose.imaging.Color.getAqua().toArgb());

    // Un altro modo è passare direttamente un'istanza di com.aspose.imaging.Color
    rasterImage.setPixel(0, 0, com.aspose.imaging.Color.getAqua());
} finally {
    image.dispose();
}
```

### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


Legge l'intera riga di scansione mediante l'indice di riga di scansione specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scanLineIndex | int | Indice basato su zero della riga di scansione. |

**Returns:**
com.aspose.imaging.Color[] - L'array dei valori di colore dei pixel della riga di scansione.
### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


Legge l'intera riga di scansione mediante l'indice di riga di scansione specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scanLineIndex | int | Indice basato su zero della riga di scansione. |

**Returns:**
int[] - L'array dei valori di colore ARGB a 32 bit della riga di scansione.
### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.imaging.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


Scrive l'intera riga di scansione nell'indice di riga di scansione specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scanLineIndex | int | Indice basato su zero della riga di scansione. |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | L'array dei colori dei pixel da scrivere. |

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


Scrive l'intera riga di scansione nell'indice di riga di scansione specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scanLineIndex | int | Indice basato su zero della riga di scansione. |
| argb32Pixels | int[] | L'array dei colori ARGB a 32 bit da scrivere. |

### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Carica parzialmente i pixel ARGB a 32 bit per pacchetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo desiderato. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader) | Il caricatore di pixel ARGB a 32 bit. |


**Example: The following example shows how to load and process pixels of a raster image using your own partial processor.**
Il seguente esempio mostra come caricare e elaborare i pixel di un'immagine raster utilizzando il proprio processore parziale. Ad esempio, considerare un problema di conteggio dei pixel completamente trasparenti di un'immagine. Per contare i pixel trasparenti usando il meccanismo di caricamento parziale, viene introdotta una classe separata TransparentArgb32PixelCounter che implementa com.aspose.imaging.IPartialArgb32PixelLoader.
``` java

// Per prima cosa, implementa com.aspose.imaging.IPartialArgb32PixelLoader per contare tutti i pixel completamente trasparenti.
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

// Ecco un esempio di utilizzo del contatore.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Crea un'istanza di com.aspose.imaging.IPartialArgb32PixelLoader e passala a com.aspose.imaging.RasterImage.LoadPartialArgb32Pixels
    TransparentArgb32PixelCounter counter = new TransparentArgb32PixelCounter();

    // Carica i pixel per l'intera immagine. Qualsiasi parte rettangolare dell'immagine può essere specificata come primo parametro del metodo com.aspose.imaging.RasterImage.loadPartialArgb32Pixels.
    rasterImage.loadPartialArgb32Pixels(rasterImage.getBounds(), counter);

    System.out.println("The number of fully transparent pixels is " + counter.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// L'output potrebbe apparire così:
// Il numero di pixel completamente trasparenti è 55157
// Il numero totale di pixel è 120400
```

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


Carica i pixel parzialmente per pacchetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo desiderato. |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.imaging/ipartialpixelloader) | Il caricatore di pixel. |


**Example: The following example shows how to load and process pixels of a raster image using your own partial processor.**
Il seguente esempio mostra come caricare e elaborare i pixel di un'immagine raster utilizzando il proprio processore parziale. Ad esempio, considera un problema di conteggio dei pixel completamente trasparenti di un'immagine. Per contare i pixel trasparenti usando il meccanismo di caricamento parziale, viene introdotta una classe separata TransparentPixelCounter che implementa com.aspose.imaging.IPartialPixelLoader.
``` java

// Per prima cosa, implementa com.aspose.imaging.IPartialPixelLoader per contare tutti i pixel completamente trasparenti.
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

// Ecco un esempio di utilizzo del contatore.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Crea un'istanza di com.aspose.imaging.IPartialPixelLoader e passala a com.aspose.imaging.RasterImage.loadPartialPixels
    TransparentPixelCounter counter = new TransparentPixelCounter();

    // Carica i pixel per l'intera immagine. Qualsiasi parte rettangolare dell'immagine può essere specificata come primo parametro del metodo com.aspose.imaging.RasterImage.loadPartialPixels.
    rasterImage.loadPartialPixels(rasterImage.getBounds(), counter);

    System.out.println("The number of fully transparent pixels is " + counter.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// L'output potrebbe apparire così:
// Il numero di pixel completamente trasparenti è 55157
// Il numero totale di pixel è 120400
```

### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


Carica i pixel ARGB a 32 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo da cui caricare i pixel. |

**Returns:**
int[] - L'array di pixel ARGB a 32 bit caricato.

**Example: The following example shows how to load and process pixels of a raster image.**
Il seguente esempio mostra come caricare e elaborare i pixel di un'immagine raster. I pixel sono rappresentati come valori interi a 32 bit. Ad esempio, considera un problema di conteggio dei pixel completamente trasparenti di un'immagine.
``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Carica i pixel per l'intera immagine. Qualsiasi parte rettangolare dell'immagine può essere specificata come parametro del metodo com.aspose.imaging.RasterImage.loadArgb32Pixels.
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


Carica i pixel ARGB a 64 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo da cui caricare i pixel. |

**Returns:**
long[] - L'array di pixel ARGB a 64 bit caricato.

**Example: The following example shows how to load and process pixels of a raster image.**
Il seguente esempio mostra come caricare e elaborare i pixel di un'immagine raster. I pixel sono rappresentati come valori interi a 64 bit. Ad esempio, considera un problema di conteggio dei pixel completamente trasparenti di un'immagine.
``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\16rgba.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Carica i pixel per l'intera immagine. Qualsiasi parte rettangolare dell'immagine può essere specificata come parametro del metodo com.aspose.imaging.RasterImage.loadArgb64Pixels.
    // Nota che l'immagine stessa deve avere 16 bit per campione, perché com.aspose.imaging.RasterImage.loadArgb64Pixels non funziona con 8 bit per campione.
    // Per lavorare con 8 bit per campione, utilizza il classico metodo com.aspose.imaging.RasterImage.loadArgb32Pixels.
    long[] pixels = rasterImage.loadArgb64Pixels(rasterImage.getBounds());

    int count = 0;
    for (long pixel : pixels) {
        // Nota che tutti i componenti di colore, inclusa l'alpha, sono rappresentati da valori a 16 bit, quindi i loro valori consentiti sono nell'intervallo [0, 63535].
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


Carica parzialmente i pixel ARGB a 64 bit per pacchetti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo desiderato. |
| partialPixelLoader | [IPartialArgb64PixelLoader](../../com.aspose.imaging/ipartialargb64pixelloader) | Il caricatore di pixel ARGB a 64 bit. |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.imaging.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


Carica i pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo da cui caricare i pixel. |

**Returns:**
com.aspose.imaging.Color[] - L'array di pixel caricato.

**Example: The following example shows how to load and process pixels of a raster image.**
Il seguente esempio mostra come caricare e elaborare i pixel di un'immagine raster. Ad esempio, considera un problema di conteggio dei pixel completamente trasparenti di un'immagine.
``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Carica i pixel per l'intera immagine. Qualsiasi parte rettangolare dell'immagine può essere specificata come parametro del metodo Aspose.Imaging.RasterImage.LoadPixels.
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


Carica i pixel in formato CMYK. Questo metodo è deprecato. Si prega di utilizzare in modo più efficace il metodo `loadCmyk32Pixels(Rectangle)`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo da cui caricare i pixel. |

**Returns:**
com.aspose.imaging.CmykColor[] - L'array di pixel CMYK caricato.
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


Carica i pixel in formato CMYK.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo da cui caricare i pixel. |

**Returns:**
int[] - I pixel CMYK caricati sono presentati come valori interi a 32 bit.
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Carica i dati grezzi dell'immagine utilizzando il meccanismo di elaborazione parziale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | L'area rettangolare desiderata dell'immagine da cui caricare i dati. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Le impostazioni dei dati grezzi. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | Il caricatore di dati grezzi. |


**Example: The following example shows how to extract pixels from the raw image data using RawDataSettings.**
Il seguente esempio mostra come estrarre i pixel dai dati grezzi dell'immagine usando RawDataSettings. Ad esempio, considerare un problema di conteggio dei pixel completamente trasparenti di un'immagine.
``` java

// Prima, implementare un contatore. Nel caso di dati grezzi, il contatore può apparire così:
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

        // Solo i formati semplici sono considerati qui per semplificare il codice.
        // Consideriamo solo immagini con 8 bit per campione.
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
                        // Il canale alfa è memorizzato per ultimo, dopo i componenti di colore.
                        if (data[i + 3] == 0) {
                            this.count++;
                        }
                    }
                }
            }
            break;

            case com.aspose.imaging.PixelFormat.Grayscale: {
                if (channelBits.length == 2) {
                    // Alfa in scala di grigi
                    for (int i = 0; i < data.length; i += 2) {
                        // Il canale alfa è memorizzato per ultimo, dopo i componenti di colore.
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

// Ecco l'esempio principale di utilizzo del contatore
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
    com.aspose.imaging.RawDataSettings settings = rasterImage.getRawDataSettings();

    TransparentPixelRawDataCounter rawDataLoader = new TransparentPixelRawDataCounter(settings);

    // Carica i pixel per l'intera immagine. Qualsiasi parte rettangolare dell'immagine può essere specificata come parametro del metodo Aspose.Imaging.RasterImage.LoadRawData.
    rasterImage.loadRawData(rasterImage.getBounds(), settings, rawDataLoader);

    System.out.println("The number of fully transparent pixels is " + rawDataLoader.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// L'output potrebbe apparire così:
// Il numero di pixel completamente trasparenti è 55157
// Il numero totale di pixel è 120400
```

### loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Carica i dati grezzi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo da cui caricare i dati grezzi. |
| dstImageBounds | [Rectangle](../../com.aspose.imaging/rectangle) | I limiti dell'immagine di destinazione. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Le impostazioni dei dati grezzi da utilizzare per i dati caricati. Nota: se i dati non sono nel formato specificato, verrà eseguita la conversione dei dati. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | Il caricatore di dati grezzi. |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


Salva i dati grezzi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] | I dati grezzi. |
| dataOffset | int | L'offset iniziale dei dati grezzi. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo dei dati grezzi. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | Le impostazioni dei dati grezzi in cui si trovano i dati. |

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.imaging.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


Salva i pixel ARGB a 32 bit.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo in cui salvare i pixel. |
| pixel | int[] | L'array di pixel ARGB a 32 bit. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
Il seguente esempio riempie l'area centrale di un'immagine raster con pixel neri usando il metodo com.aspose.imaging.RasterImage.saveArgb32Pixels.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Il quadrato nero
    int[] pixels = new int[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getBlack().toArgb();
    }

    // Disegna il quadrato nero al centro dell'immagine.
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


Salva i pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo in cui salvare i pixel. |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | L'array di pixel. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
Il seguente esempio riempie l'area centrale di un'immagine raster con pixel neri utilizzando il metodo com.aspose.imaging.RasterImage.savePixels.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Il quadrato nero
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getBlack();
    }

    // Disegna il quadrato nero al centro dell'immagine.
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


Converte l'immagine raster in bitmap.

**Returns:**
java.awt.image.BufferedImage - Il bitmap

**Example: The following example converts a BMP image to a native Java bitmap.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;
    java.awt.image.BufferedImage bitmap = bmpImage.toBitmap();

    // Elabora il bitmap Java nativo.
} finally {
    image.dispose();
}
```

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


Salva i pixel. Questo metodo è deprecato. Si prega di utilizzare il metodo più efficace `saveCmyk32Pixels(Rectangle, int[])`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo in cui salvare i pixel. |
| pixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | L'array di pixel CMYK. |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.imaging.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


Salva i pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo in cui salvare i pixel. |
| pixel | int[] | I pixel CMYK presentati come valori interi a 32 bit. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
Il seguente esempio riempie l'area centrale di un'immagine raster con pixel neri utilizzando il metodo com.aspose.imaging.RasterImage.saveCmyk32Pixels.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Ottieni una rappresentazione intera del nero nello spazio colore CMYK.
    int blackCmyk = com.aspose.imaging.CmykColorHelper.toCmyk(com.aspose.imaging.Color.getBlack());

    // Il quadrato nero.
    int[] pixels = new int[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = blackCmyk;
    }

    // Disegna il quadrato nero al centro dell'immagine.
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


Imposta la risoluzione per questo `RasterImage`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dpiX | double | La risoluzione orizzontale, in punti per pollice, del `RasterImage`. |
| dpiY | double | La risoluzione verticale, in punti per pollice, del `RasterImage`. |


**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Ottieni la risoluzione orizzontale e verticale dell'immagine
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Usa il metodo SetResolution per aggiornare entrambi i valori di risoluzione in una singola chiamata.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // L'output potrebbe apparire così:
    // La risoluzione orizzontale, in pixel per pollice: 300.0
    // La risoluzione verticale, in pixel per pollice: 300.0
    // Imposta i valori di risoluzione a 96 dpi
    // La risoluzione orizzontale, in pixel per pollice: 96.0
    // La risoluzione verticale, in pixel per pollice: 96.0
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Imposta la tavolozza dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La tavolozza da impostare. |
| updateColors | boolean | se impostato su `true` i colori verranno aggiornati secondo la nuova tavolozza; altrimenti gli indici dei colori rimarranno invariati. Nota che gli indici invariati possono causare il crash dell'immagine durante il caricamento se alcuni indici non hanno voci corrispondenti nella tavolozza. |

### autoRotate() {#autoRotate--}
```
public final void autoRotate()
```


Ruota automaticamente l'immagine in base ai dati di orientamento estratti dai metadati Exif. Questo metodo garantisce che le immagini vengano visualizzate nella corretta orientazione, migliorando l'esperienza dell'utente ed eliminando la necessità di regolazioni manuali. Analizzando le informazioni Exif, l'immagine viene ruotata di conseguenza, offrendo un'esperienza di visualizzazione fluida su diverse piattaforme e dispositivi. Questo processo di rotazione automatizzato semplifica la gestione delle immagini e migliora l'usabilità complessiva, soprattutto quando si lavora con grandi lotti di immagini con orientamenti variabili.

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ridimensiona l'immagine con opzioni estese.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | int | La nuova larghezza. |
| newHeight | int | La nuova altezza. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Le impostazioni di ridimensionamento. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Ruota l'immagine attorno al centro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione in gradi. I valori positivi ruoteranno in senso orario. |
| resizeProportionally | boolean | se impostato su `true` le dimensioni dell'immagine verranno modificate in base alle proiezioni del rettangolo ruotato (punti d'angolo); altrimenti le dimensioni rimarranno inalterate e solo il contenuto interno dell'immagine verrà ruotato. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Colore dello sfondo. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Ruota l'immagine attorno al centro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | float | L'angolo di rotazione in gradi. I valori positivi ruoteranno in senso orario. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarizzazione di un'immagine con soglia predefinita

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threshold | byte | Valore di soglia. Se il valore grigio corrispondente di un pixel è maggiore della soglia, verrà assegnato il valore 255, altrimenti 0. |


**Example: The following example binarizes a raster image with the predefined threshold.**
Il seguente esempio binarizza un'immagine raster con la soglia predefinita. Le immagini binarie contengono solo 2 colori - nero e bianco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Binarizza l'immagine con un valore di soglia di 127.
    // Se il valore di grigio corrispondente di un pixel è maggiore di 127, gli verrà assegnato un valore di 255, altrimenti 0.
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


Binarizzazione di un'immagine con soglia di Otsu


**Example: The following example binarizes a raster image with Otsu thresholding.**
Il seguente esempio binarizza un'immagine raster con la soglia di Otsu. Le immagini binarie contengono solo 2 colori - nero e bianco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Binarizza l'immagine con la sogliatura di Otsu.
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


Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley basato sulla sogliatura dell'immagine integrale

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightnessDifference | double | La differenza di luminosità tra il pixel e la media di una finestra s x s di pixel centrata su questo pixel. |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley basato sulla sogliatura dell'immagine integrale

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightnessDifference | double | La differenza di luminosità tra il pixel e la media di una finestra s x s di pixel centrata su questo pixel. |
| windowSize | int | La dimensione della finestra s x s di pixel centrata su questo pixel. |


**Example: The following example binarizes a raster image with Bradley's adaptive thresholding algorithm with the specified window size.**
Il seguente esempio binarizza un'immagine raster con l'algoritmo di soglia adattiva di Bradley con la dimensione della finestra specificata. Le immagini binarie contengono solo 2 colori - nero e bianco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Binarizza l'immagine con una differenza di luminosità di 5. La luminosità è la differenza tra un pixel e la media di una finestra 10 x 10 di pixel centrata su quel pixel.
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


Mescola questa istanza di immagine con l'immagine `overlay`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | L'origine della fusione dell'immagine di sfondo. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine di sovrapposizione. |
| overlayArea | [Rectangle](../../com.aspose.imaging/rectangle) | L'area di sovrapposizione. |

### blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-}
```
public void blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)
```


Mescola questa istanza di immagine con l'immagine `overlay`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | L'origine della fusione dell'immagine di sfondo. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | L'immagine di sovrapposizione. |
| overlayArea | [Rectangle](../../com.aspose.imaging/rectangle) | L'area di sovrapposizione. |
| overlayAlpha | byte | L'alpha di sovrapposizione. |

### blend(Point origin, RasterImage overlay) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-}
```
public final void blend(Point origin, RasterImage overlay)
```


Unisce questa istanza di immagine con il `overlay` con alfa == 255.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | L'origine della fusione dell'immagine di sfondo. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | La sovrapposizione. |

### blend(Point origin, RasterImage overlay, byte overlayAlpha) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-byte-}
```
public final void blend(Point origin, RasterImage overlay, byte overlayAlpha)
```


Unisce questa istanza di immagine con il `overlay`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | L'origine della fusione dell'immagine di sfondo. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | La sovrapposizione. |
| overlayAlpha | byte | L'alpha di sovrapposizione. |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Trasformazione di un'immagine nella sua rappresentazione in scala di grigi


**Example: The following example transforms a colored raster image to its grayscale representation.**
Il seguente esempio trasforma un'immagine raster a colori nella sua rappresentazione in scala di grigi. Le immagini in scala di grigi sono composte esclusivamente da sfumature di grigio e contengono solo informazioni di intensità.
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


Normalizza l'istogramma dell'immagine \\u2014 regola i valori dei pixel per utilizzare l'intera gamma disponibile.

### autoBrightnessContrast() {#autoBrightnessContrast--}
```
public void autoBrightnessContrast()
```


Normalizzazione automatica adattiva di luminosità e contrasto per l'intera immagine.

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Regola la luminosità dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightness | int | Valore di luminosità. |


**Example: The following example performs brightness correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Imposta il valore di luminosità. I valori accettati per la luminosità sono nell'intervallo [-255, 255].
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


Contrasto dell'immagine

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contrast | float | Valore di contrasto (nell'intervallo [-100; 100]) |


**Example: The following example performs contrast correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Imposta il valore di contrasto. I valori accettati per il contrasto sono nell'intervallo [-100f, 100f].
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


Incorpora una firma digitale basata sulla password fornita nell'immagine usando la steganografia.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | java.lang.String | La password utilizzata per generare i dati della firma digitale |


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


Calcola la percentuale di somiglianza tra i dati estratti e la password originale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | java.lang.String | La password utilizzata per estrarre i dati incorporati. |

**Returns:**
int - Il valore di percentuale di somiglianza.
### isDigitalSigned(String password) {#isDigitalSigned-java.lang.String-}
```
public boolean isDigitalSigned(String password)
```


Esegue un controllo rapido per determinare se l'immagine è firmata digitalmente, usando la password fornita e la soglia.

--------------------

Questo metodo fornisce la rilevazione più veloce sfruttando `GetSignPercentage`. Una volta che i dati estratti raggiungono la soglia specificata, i passaggi di estrazione successivi volti a migliorare la precisione della rilevazione vengono saltati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | java.lang.String | La password per verificare la firma. |

**Returns:**
boolean - True se l'immagine è firmata, altrimenti false.
### isDigitalSigned(String password, int percentageThreshold) {#isDigitalSigned-java.lang.String-int-}
```
public boolean isDigitalSigned(String password, int percentageThreshold)
```


Esegue un controllo rapido per determinare se l'immagine è firmata digitalmente, usando la password fornita e la soglia.

--------------------

Questo metodo fornisce la rilevazione più veloce sfruttando `GetSignPercentage`. Una volta che i dati estratti raggiungono la soglia specificata, i passaggi di estrazione successivi volti a migliorare la precisione della rilevazione vengono saltati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| password | java.lang.String | La password per verificare la firma. |
| percentageThreshold | int | La soglia (in percentuale)[0-100] che determina se l'immagine è considerata firmata. Se non specificata, verrà applicata una soglia predefinita (`75`). |

**Returns:**
boolean - True se l'immagine è firmata, altrimenti false.
### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Correzione gamma di un'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gammaRed | float | Gamma per il coefficiente del canale rosso |
| gammaGreen | float | Gamma per il coefficiente del canale verde |
| gammaBlue | float | Coefficiente gamma per il canale blu |


**Example: The following example performs gamma-correction of an image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Imposta i coefficienti gamma individuali per i canali rosso, verde e blu.
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


Correzione gamma di un'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| gamma | float | Coefficiente gamma per i canali rosso, verde e blu |


**Example: The following example performs gamma-correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Imposta il coefficiente gamma per i canali rosso, verde e blu.
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


Ottiene l'angolo di inclinazione. Questo metodo è applicabile ai documenti di testo scansionati, per determinare l'angolo di inclinazione durante la scansione.

**Returns:**
float - L'angolo di inclinazione, in gradi.
### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


Normalizza l'angolo. Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione inclinata. Questo metodo utilizza \#getSkewAngle.getSkewAngle e i metodi [Image.rotate(float)](../../com.aspose.imaging/image\#rotate-float-).

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Normalizza l'angolo. Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione inclinata. Questo metodo utilizza \#getSkewAngle.getSkewAngle e i metodi \#rotate(float, boolean, Color).rotate(float, boolean, Color).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resizeProportionally | boolean | se impostato su `true` le dimensioni dell'immagine verranno modificate in base alle proiezioni del rettangolo ruotato (punti d'angolo); altrimenti le dimensioni rimarranno inalterate e solo il contenuto interno dell'immagine verrà ruotato. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Colore dello sfondo. |


**Example: Skew is an artifact that might appear during document scanning process when the text/images of the document get rotated at a slight angle.**
La distorsione è un artefatto che può comparire durante il processo di scansione di un documento quando il testo/immagini del documento vengono ruotati di un leggero angolo. Può avere varie cause, ma la più comune è che la carta venga spostata durante la scansione. Pertanto, la correzione dell'inclinazione (deskew) è il processo di rilevare e correggere questo problema sui file scansionati (i.e. bitmap) in modo che i documenti corretti abbiano il testo/immagini correttamente e orizzontalmente allineati.
``` java
String dir = "c:\\aspose.imaging\\issues\\java\\1461\\";

String inputFilePath = dir + "skewed.png";
String outputFilePath = dir + "skewed.out.png";

// Elimina la scansione inclinata con i parametri predefiniti
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


Filtra il rettangolo specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Il rettangolo. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Le opzioni. |


**Example: The following example applies various types of filters to a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applica un filtro mediano con una dimensione del rettangolo di 5 all'intera immagine.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    rasterImage.save(dir + "sample.MedianFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applica un filtro di levigatura bilaterale con una dimensione del kernel di 5 all'intera immagine.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    rasterImage.save(dir + "sample.BilateralSmoothingFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applica un filtro di sfocatura gaussiana con un raggio di 5 e un valore sigma di 4.0 all'intera immagine.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussianBlurFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applica un filtro Gauss-Wiener con un raggio di 5 e un valore di levigatura di 4.0 all'intera immagine.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applica un filtro motion Wiener con una lunghezza di 5, un valore di levigatura di 4.0 e un angolo di 90.0 gradi all'intera immagine.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.save(dir + "sample.MotionWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applica un filtro di nitidezza con una dimensione del kernel di 5 e un valore sigma di 4.0 all'intera immagine.
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


Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.imaging/color) | Colore vecchio da sostituire. |
| oldColorDiff | byte | Differenza consentita nel colore vecchio per poter ampliare la tonalità del colore sostituito. |
| newColor | [Color](../../com.aspose.imaging/color) | Nuovo colore con cui sostituire il colore vecchio. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| oldColorArgb | int | Valore ARGB del colore vecchio da sostituire. |
| oldColorDiff | byte | Differenza consentita nel colore vecchio per poter ampliare la tonalità del colore sostituito. |
| newColorArgb | int | Nuovo valore ARGB del colore da utilizzare per sostituire il colore vecchio. |

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.imaging.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


Sostituisce tutti i colori non trasparenti con il nuovo colore e preserva il valore alfa originale per mantenere bordi lisci. Nota: se lo utilizzi su immagini senza trasparenza, tutti i colori saranno sostituiti con un unico colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.imaging/color) | Nuovo colore con cui sostituire i colori non trasparenti. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Sostituisce tutti i colori non trasparenti con il nuovo colore e preserva il valore alfa originale per mantenere bordi lisci. Nota: se lo utilizzi su immagini senza trasparenza, tutti i colori saranno sostituiti con un unico colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newColorArgb | int | Nuovo valore ARGB del colore da utilizzare per sostituire i colori non trasparenti. |

