---
title: "RasterImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa una imagen raster que soporta operaciones de gráficos raster."
type: docs
weight: 91
url: /es/java/com.aspose.imaging/rasterimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image)

**All Implemented Interfaces:**
[com.aspose.imaging.IRasterImageArgb32PixelLoader](../../com.aspose.imaging/irasterimageargb32pixelloader), com.aspose.internal.IPixelsSaver, [com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public abstract class RasterImage extends Image implements IRasterImageArgb32PixelLoader, IPixelsSaver, IHasXmpData
```

Representa una imagen raster que soporta operaciones de gráficos raster.
## Métodos

| Método | Descripción |
| --- | --- |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Obtiene o establece un valor que indica si los componentes de la imagen deben estar premultiplicados. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Obtiene o establece un valor que indica si los componentes de la imagen deben estar premultiplicados. |
| [getUseRawData()](#getUseRawData--) | Obtiene o establece un valor que indica si se debe usar la carga de datos sin formato cuando la carga de datos sin formato está disponible. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Obtiene o establece un valor que indica si se debe usar la carga de datos sin formato cuando la carga de datos sin formato está disponible. |
| [getUpdateXmpData()](#getUpdateXmpData--) | Obtiene o establece un valor que indica si se debe actualizar los metadatos XMP. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Obtiene o establece un valor que indica si se debe actualizar los metadatos XMP. |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Obtiene o establece el convertidor de color indexado |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-) | Obtiene o establece el convertidor de color indexado |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Obtiene o establece el convertidor de color personalizado |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.imaging.IColorConverter-) | Obtiene o establece el convertidor de color personalizado |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Obtiene o establece el índice de reserva a usar cuando el índice de la paleta está fuera de los límites |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Obtiene o establece el índice de reserva a usar cuando el índice de la paleta está fuera de los límites |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [isUsePalette()](#isUsePalette--) | Obtiene un valor que indica si se usa la paleta de la imagen. |
| [getRawDataFormat()](#getRawDataFormat--) | Obtiene el formato de datos sin formato. |
| [getRawLineSize()](#getRawLineSize--) | Obtiene el tamaño de línea sin formato en bytes. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Obtiene un valor que indica si la carga de datos sin formato está disponible. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este `RasterImage`. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este `RasterImage`. |
| [getVerticalResolution()](#getVerticalResolution--) | Obtiene o establece la resolución vertical, en píxeles por pulgada, de este `RasterImage`. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Obtiene o establece la resolución vertical, en píxeles por pulgada, de este `RasterImage`. |
| [hasTransparentColor()](#hasTransparentColor--) | Obtiene un valor que indica si esta instancia de [RasterImage](../../com.aspose.imaging/rasterimage) tiene un color transparente. |
| [hasAlpha()](#hasAlpha--) | Obtiene un valor que indica si esta instancia tiene alfa. |
| [getTransparentColor()](#getTransparentColor--) | Obtiene el color transparente de la imagen. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Establece un valor que indica si esta instancia de [RasterImage](../../com.aspose.imaging/rasterimage) tiene un color transparente. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Obtiene el color transparente de la imagen. |
| [getImageOpacity()](#getImageOpacity--) | Obtiene la opacidad de esta imagen. |
| [removeMetadata()](#removeMetadata--) | Elimina los metadatos de esta instancia de imagen estableciendo este `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) valor a `null`. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Recupera la fecha y hora en que la imagen del recurso sufrió su última modificación. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | Realiza dithering en la imagen actual. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Realiza dithering en la imagen actual. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-) | Obtiene la matriz de píxeles predeterminada usando el cargador parcial de píxeles. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialRawDataLoader-com.aspose.imaging.RawDataSettings-) | Obtiene la matriz de datos sin procesar predeterminada usando el cargador parcial de píxeles. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.imaging.Rectangle-) | Obtiene la matriz predeterminada de píxeles ARGB de 32 bits. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-) | Obtiene la matriz predeterminada de datos sin procesar. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Obtiene un píxel ARGB de 32 bits de la imagen. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Obtiene un píxel de la imagen. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Establece un píxel ARGB de 32 bits de la imagen para la posición especificada. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.imaging.Color-) | Establece un píxel de la imagen para la posición especificada. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Lee toda la línea de escaneo mediante el índice de línea de escaneo especificado. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Lee toda la línea de escaneo mediante el índice de línea de escaneo especificado. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.imaging.Color---) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Escribe toda la línea de escaneo en el índice de línea de escaneo especificado. |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-) | Carga píxeles ARGB de 32 bits parcialmente por paquetes. |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-) | Carga píxeles parcialmente por paquetes. |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.imaging.Rectangle-) | Carga píxeles ARGB de 32 bits. |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.imaging.Rectangle-) | Carga píxeles ARGB de 64 bits. |
| [loadPartialArgb64Pixels(Rectangle rectangle, IPartialArgb64PixelLoader partialPixelLoader)](#loadPartialArgb64Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb64PixelLoader-) | Carga píxeles ARGB de 64 bits parcialmente por paquetes. |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.imaging.Rectangle-) | Carga píxeles. |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.imaging.Rectangle-) | Carga píxeles en formato CMYK. |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.imaging.Rectangle-) | Carga píxeles en formato CMYK. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-) | Carga datos de imagen sin procesar usando el mecanismo de procesamiento parcial. |
| [loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-) | Carga datos sin procesar. |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-) | Guarda los datos sin procesar. |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.imaging.Rectangle-int---) | Guarda los píxeles ARGB de 32 bits. |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.imaging.Rectangle-com.aspose.imaging.Color---) | Guarda los píxeles. |
| [toBitmap()](#toBitmap--) | Convierte la imagen raster a bitmap. |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.CmykColor---) | Guarda los píxeles. |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.imaging.Rectangle-int---) | Guarda los píxeles. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Establece la resolución para este `RasterImage`. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Establece la paleta de la imagen. |
| [autoRotate()](#autoRotate--) | Rota automáticamente la imagen según los datos de orientación extraídos de los metadatos Exif. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Redimensiona la imagen con opciones extendidas. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Rota la imagen alrededor del centro. |
| [rotate(float angle)](#rotate-float-) | Rota la imagen alrededor del centro. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarización de una imagen con umbral predefinido |
| [binarizeOtsu()](#binarizeOtsu--) | Binarización de una imagen con umbralización de Otsu |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Binarización de una imagen usando el algoritmo de umbralización adaptativa de Bradley mediante la umbralización de imagen integral |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarización de una imagen usando el algoritmo de umbralización adaptativa de Bradley mediante la umbralización de imagen integral |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-) | Mezcla esta instancia de imagen con la imagen `overlay`. |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | Mezcla esta instancia de imagen con la imagen `overlay`. |
| [blend(Point origin, RasterImage overlay)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-) | Mezcla esta instancia de imagen con el `overlay` con alfa == 255. |
| [blend(Point origin, RasterImage overlay, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-byte-) | Mezcla esta instancia de imagen con el `overlay`. |
| [grayscale()](#grayscale--) | Transformación de una imagen a su representación en escala de grises |
| [normalizeHistogram()](#normalizeHistogram--) | Normaliza el histograma de la imagen \\u2014 ajusta los valores de píxel para usar todo el rango disponible. |
| [autoBrightnessContrast()](#autoBrightnessContrast--) | Normalización automática adaptativa de brillo y contraste para toda la imagen. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Ajuste de brillo para la imagen. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Contraste de la imagen |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | Incrusta una firma digital basada en la contraseña proporcionada en la imagen usando esteganografía. |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | Calcula el porcentaje de similitud entre los datos extraídos y la contraseña original. |
| [isDigitalSigned(String password)](#isDigitalSigned-java.lang.String-) | Realiza una verificación rápida para determinar si la imagen está firmada digitalmente, usando la contraseña proporcionada y el umbral. |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | Realiza una verificación rápida para determinar si la imagen está firmada digitalmente, usando la contraseña proporcionada y el umbral. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Corrección gamma de una imagen. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Corrección gamma de una imagen. |
| [getSkewAngle()](#getSkewAngle--) | Obtiene el ángulo de sesgo. |
| [normalizeAngle()](#normalizeAngle--) | Normaliza el ángulo. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | Normaliza el ángulo. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Filtra el rectángulo especificado. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.imaging.Color-byte-com.aspose.imaging.Color-) | Reemplaza un color por otro con diferencia permitida y conserva el valor alfa original para mantener bordes suaves. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Reemplaza un color por otro con diferencia permitida y conserva el valor alfa original para mantener bordes suaves. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.imaging.Color-) | Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para mantener bordes suaves. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para mantener bordes suaves. |

## Example: This example shows how to load pixel information in an array of colors, manipulates the array and set it back to the image.

``` java
String dir = "c:\\temp\\";

// Crea una instancia de GifOptions y establece sus diversas propiedades, incluida la propiedad Source
com.aspose.imaging.imageoptions.GifOptions gifOptions = new com.aspose.imaging.imageoptions.GifOptions();
gifOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "output.gif", false));

// Crear una instancia de Image
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.create(gifOptions, 500, 500);
try {
    // Obtén los píxeles de la imagen especificando el área como límite de la imagen
    com.aspose.imaging.Color[] pixels = image.loadPixels(image.getBounds());

    // Recorre el arreglo y establece el color del píxel indexado alternativo
    for (int index = 0; index < pixels.length; index++) {
        if (index % 2 == 0) {
            // Establece el color del píxel indexado a amarillo
            pixels[index] = com.aspose.imaging.Color.getYellow();
        } else {
            // Establece el color del píxel indexado a azul
            pixels[index] = com.aspose.imaging.Color.getBlue();
        }
    }

    // Aplica los cambios de píxeles a la imagen
    image.savePixels(image.getBounds(), pixels);

    // Guardar todos los cambios.
    image.save();
} finally {
    image.dispose();
}
```

### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Obtiene o establece un valor que indica si los componentes de la imagen deben estar premultiplicados.

**Returns:**
boolean - `true` si los componentes de la imagen deben estar premultiplicados; de lo contrario, `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Obtiene o establece un valor que indica si los componentes de la imagen deben estar premultiplicados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | `true` si los componentes de la imagen deben estar premultiplicados; de lo contrario, `false`. |


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

    // Guardar píxeles para toda la imagen.
    rasterImage.savePixels(rasterImage.getBounds(), colors);

    // Los píxeles se almacenan en la imagen original en forma no premultiplicada.
    // Es necesario especificar la opción correspondiente explícitamente para obtener componentes de color premultiplicados.
    // Los componentes de color premultiplicados se calculan mediante las fórmulas:
    // rojo = original_rojo * alfa / 255;
    // verde = original_verde * alfa / 255;
    // azul = original_azul * alfa / 255;
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


Obtiene o establece un valor que indica si se debe usar la carga de datos sin formato cuando la carga de datos sin formato está disponible.

**Returns:**
boolean - `true` si se usa la carga de datos sin procesar cuando está disponible; de lo contrario, `false`.
### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


Obtiene o establece un valor que indica si se debe usar la carga de datos sin formato cuando la carga de datos sin formato está disponible.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | `true` si se usa la carga de datos sin procesar cuando está disponible.; de lo contrario, `false`. |

### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


Obtiene o establece un valor que indica si se debe actualizar los metadatos XMP.

**Returns:**
boolean - `true` si se actualiza la metadata XMP; de lo contrario, `false`.
### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


Obtiene o establece un valor que indica si se debe actualizar los metadatos XMP.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | `true` si se actualiza la metadata XMP; de lo contrario, `false`. |

### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


Obtiene o establece el convertidor de color indexado

**Returns:**
[IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) - The indexed color converter
### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


Obtiene o establece el convertidor de color indexado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) | El convertidor de color indexado |

### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


Obtiene o establece el convertidor de color personalizado

**Returns:**
[IColorConverter](../../com.aspose.imaging/icolorconverter) - The custom color converter
### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.imaging.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


Obtiene o establece el convertidor de color personalizado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.imaging/icolorconverter) | El convertidor de color personalizado |

### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


Obtiene o establece el índice de reserva a usar cuando el índice de la paleta está fuera de los límites

**Returns:**
int - El índice de reserva a usar cuando el índice de la paleta está fuera de los límites
### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


Obtiene o establece el índice de reserva a usar cuando el índice de la paleta está fuera de los límites

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El índice de reserva a usar cuando el índice de la paleta está fuera de los límites |

### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


Obtiene la configuración actual de datos sin procesar. Nota: al usar estas configuraciones, los datos se cargan sin conversión.

**Returns:**
[RawDataSettings](../../com.aspose.imaging/rawdatasettings)
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Obtiene un valor que indica si se usa la paleta de la imagen.

Valor: `true` si la paleta se usa en la imagen; de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si se usa la paleta de la imagen.
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Obtiene el formato de datos sin formato.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.

**Example: The following example loads raster images and prints information about raw data format and alpha channel.**

``` java

// Los archivos de imagen a cargar.
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

// La salida puede verse así:
// ImageFile=c:\temp\sample.bmp FileFormat=Rgb24Bpp, canales usados: 8,8,8 HasAlpha=false
// ImageFile=c:\temp\alpha.png FileFormat=RGBA32Bpp, canales usados: 8,8,8,8 HasAlpha=true
```

### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Obtiene el tamaño de línea sin formato en bytes.

**Returns:**
int - El tamaño de línea sin procesar en bytes.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


Obtiene un valor que indica si la carga de datos sin formato está disponible.

**Returns:**
boolean - `true` si esta carga de datos sin procesar está disponible; de lo contrario, `false`.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este `RasterImage`.

**Returns:**
double - La resolución horizontal.

Nota: por defecto este valor siempre es 96 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada.

**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Obtener la resolución horizontal y vertical de la imagen
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilice el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // La salida puede verse así:
    // La resolución horizontal, en píxeles por pulgada: 300.0
    // La resolución vertical, en píxeles por pulgada: 300.0
    // Establecer los valores de resolución a 96 dpi
    // La resolución horizontal, en píxeles por pulgada: 96.0
    // La resolución vertical, en píxeles por pulgada: 96.0
} finally {
    image.dispose();
}
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este `RasterImage`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | La resolución horizontal. |

Nota: por defecto este valor siempre es 96 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Obtiene o establece la resolución vertical, en píxeles por pulgada, de este `RasterImage`.

**Returns:**
double - La resolución vertical.

Nota: por defecto este valor siempre es 96 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada.

**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Obtener la resolución horizontal y vertical de la imagen
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilice el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // La salida puede verse así:
    // La resolución horizontal, en píxeles por pulgada: 300.0
    // La resolución vertical, en píxeles por pulgada: 300.0
    // Establecer los valores de resolución a 96 dpi
    // La resolución horizontal, en píxeles por pulgada: 96.0
    // La resolución vertical, en píxeles por pulgada: 96.0
} finally {
    image.dispose();
}
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Obtiene o establece la resolución vertical, en píxeles por pulgada, de este `RasterImage`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | La resolución vertical. |

Nota: por defecto este valor siempre es 96 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada. |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Obtiene un valor que indica si esta instancia de [RasterImage](../../com.aspose.imaging/rasterimage) tiene un color transparente.

--------------------

La implementación base devuelve efectivamente `` si no se sobrescribe en una implementación específica que admite esta característica. Esta propiedad se utiliza principalmente por [FileFormat.Apng](../../com.aspose.imaging/fileformat\#Apng), [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png), [FileFormat.Gif](../../com.aspose.imaging/fileformat\#Gif), [FileFormat.Tga](../../com.aspose.imaging/fileformat\#Tga) para establecer un color transparente si una imagen no admite transparencia mediante canal alfa.

**Returns:**
boolean - un valor que indica si esta instancia de [RasterImage](../../com.aspose.imaging/rasterimage) tiene un color transparente.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Obtiene un valor que indica si esta instancia tiene alfa.

**Returns:**
boolean - `true` si esta instancia tiene alfa; de lo contrario, `false`.

**Example: The following example loads raster images and prints information about raw data format and alpha channel.**

``` java

// Los archivos de imagen a cargar.
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

// La salida puede verse así:
// ImageFile=c:\temp\sample.bmp FileFormat=Rgb24Bpp, canales usados: 8,8,8 HasAlpha=false
// ImageFile=c:\temp\alpha.png FileFormat=RGBA32Bpp, canales usados: 8,8,8,8 HasAlpha=true
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Obtiene el color transparente de la imagen.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Establece un valor que indica si esta instancia de [RasterImage](../../com.aspose.imaging/rasterimage) tiene un color transparente.

--------------------

La implementación base devuelve efectivamente `` si no se sobrescribe en una implementación específica que admite esta característica. Esta propiedad se utiliza principalmente por [FileFormat.Apng](../../com.aspose.imaging/fileformat\#Apng), [FileFormat.Png](../../com.aspose.imaging/fileformat\#Png), [FileFormat.Gif](../../com.aspose.imaging/fileformat\#Gif), [FileFormat.Tga](../../com.aspose.imaging/fileformat\#Tga) para establecer un color transparente si una imagen no admite transparencia mediante canal alfa.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean | un valor que indica si esta instancia de [RasterImage](../../com.aspose.imaging/rasterimage) tiene un color transparente. |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Obtiene el color transparente de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Obtiene la opacidad de esta imagen.

**Returns:**
float - El valor de opacidad entre 0.0 (totalmente transparente) y 1.0 (totalmente opaco).
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Elimina los metadatos de esta instancia de imagen estableciendo este `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) valor a `null`.

### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Obtiene la fecha y hora en que la imagen de recurso sufrió su última modificación. Este método proporciona metadatos valiosos, permitiendo a los usuarios rastrear y gestionar las actualizaciones del archivo de imagen de manera eficaz. Al acceder a esta información, los usuarios pueden garantizar la integridad y actualidad de sus activos de imagen, facilitando la toma de decisiones informadas sobre el uso y mantenimiento de las imágenes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| useDefault | boolean | si se establece en `true` utiliza la información de FileInfo como valor predeterminado. |

**Returns:**
java.util.Date - La fecha y hora en que la imagen de recurso fue modificada por última vez.
### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


Realiza dithering en la imagen actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ditheringMethod | int | El método de tramado. |
| bitsCount | int | El recuento final de bits para el tramado. |


**Example: The following example loads a raster image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Realizar dithering por umbral usando una paleta de colores de 4 bits que contiene 16 colores.
    // Cuantos más bits se especifiquen, mayor será la calidad y mayor el tamaño de la imagen de salida.
    // Tenga en cuenta que solo se admiten paletas de 1 bit, 4 bits y 8 bits en este momento.
    rasterImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.save(dir + "sample.ThresholdDithering4.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Realizar dithering Floyd usando una paleta de colores de 1 bit que contiene solo 2 colores: negro y blanco.
    // Cuantos más bits se especifiquen, mayor será la calidad y mayor el tamaño de la imagen de salida.
    // Tenga en cuenta que solo se admiten paletas de 1 bit, 4 bits y 8 bits en este momento.
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


Realiza dithering en la imagen actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ditheringMethod | int | El método de tramado. |
| bitsCount | int | El recuento final de bits para el tramado. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta personalizada para el tramado. |

### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Obtiene la matriz de píxeles predeterminada usando el cargador parcial de píxeles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo del que obtener los píxeles. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader) | El cargador parcial de píxeles. |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialRawDataLoader-com.aspose.imaging.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


Obtiene la matriz de datos sin procesar predeterminada usando el cargador parcial de píxeles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo del que obtener los píxeles. |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | El cargador parcial de datos sin procesar. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | La configuración de datos sin procesar. |

### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


Obtiene la matriz predeterminada de píxeles ARGB de 32 bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo del que obtener los píxeles. |

**Returns:**
int[] - La matriz de píxeles predeterminada.
### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


Obtiene la matriz predeterminada de datos sin procesar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo para obtener datos sin procesar. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | La configuración de datos sin procesar. |

**Returns:**
byte[] - La matriz de datos sin procesar predeterminada.
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


Obtiene un píxel ARGB de 32 bits de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La ubicación x del píxel. |
| y | int | La ubicación y del píxel. |

**Returns:**
int - El píxel ARGB de 32 bits para la ubicación especificada.

**Example: The following example loads a raster image and obtains the color of an arbitrary pixel represented as a 32-bit integer value.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Obtenga una representación entera del color del píxel superior izquierdo de la imagen.
    int color = rasterImage.getArgb32Pixel(0, 0);

    // Para obtener los valores de los componentes de color individuales, desplace el valor del color un número correspondiente de bits.
    int alpha = (color >> 24) & 0xff;
    int red = (color >> 16) & 0xff;
    int green = (color >> 8) & 0xff;
    int blue = (color >> 0) & 0xff;

    System.out.println("The color of the pixel(0,0) is A=" + alpha + ",R=" + red + ",G=" + green + ",B=" + blue);
} finally {
    image.dispose();
}

// La salida puede verse así:
// El color del píxel(0,0) es A=255,R=0,G=0,B=0
```

### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


Obtiene un píxel de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La ubicación x del píxel. |
| y | int | La ubicación y del píxel. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The pixel color for the specified location.

**Example: The following example loads a raster image and obtains the color of an arbitrary pixel.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Obtenga el color del píxel superior izquierdo de la imagen.
    com.aspose.imaging.Color color = rasterImage.getPixel(0, 0);

    // Obtenga los valores de los componentes de color individuales
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


Establece un píxel ARGB de 32 bits de la imagen para la posición especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La ubicación x del píxel. |
| y | int | La ubicación y del píxel. |
| argb32Color | int | El píxel ARGB de 32 bits para la posición especificada. |


**Example: The following example loads a raster image, and sets the color of an arbitrary pixel.**

``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Establece el color del píxel superior izquierdo.
    rasterImage.setArgb32Pixel(0, 0, com.aspose.imaging.Color.getAqua().toArgb());

    // Otra forma es pasar una instancia de com.aspose.imaging.Color directamente
    rasterImage.setPixel(0, 0, com.aspose.imaging.Color.getAqua());
} finally {
    image.dispose();
}
```

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.imaging.Color-}
```
public void setPixel(int x, int y, Color color)
```


Establece un píxel de la imagen para la posición especificada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | int | La ubicación x del píxel. |
| y | int | La ubicación y del píxel. |
| color | [Color](../../com.aspose.imaging/color) | El color del píxel para la posición especificada. |


**Example: The following example loads a raster image, and sets the color of an arbitrary pixel.**

``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Establece el color del píxel superior izquierdo.
    rasterImage.setArgb32Pixel(0, 0, com.aspose.imaging.Color.getAqua().toArgb());

    // Otra forma es pasar una instancia de com.aspose.imaging.Color directamente
    rasterImage.setPixel(0, 0, com.aspose.imaging.Color.getAqua());
} finally {
    image.dispose();
}
```

### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


Lee toda la línea de escaneo mediante el índice de línea de escaneo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scanLineIndex | int | Índice basado en cero de la línea de escaneo. |

**Returns:**
com.aspose.imaging.Color[] - La matriz de valores de color de píxeles de la línea de escaneo.
### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


Lee toda la línea de escaneo mediante el índice de línea de escaneo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scanLineIndex | int | Índice basado en cero de la línea de escaneo. |

**Returns:**
int[] - La matriz de valores de color ARGB de 32 bits de la línea de escaneo.
### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.imaging.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


Escribe toda la línea de escaneo en el índice de línea de escaneo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scanLineIndex | int | Índice basado en cero de la línea de escaneo. |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | La matriz de colores de píxeles a escribir. |

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


Escribe toda la línea de escaneo en el índice de línea de escaneo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scanLineIndex | int | Índice basado en cero de la línea de escaneo. |
| argb32Pixels | int[] | La matriz de colores ARGB de 32 bits a escribir. |

### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Carga píxeles ARGB de 32 bits parcialmente por paquetes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo deseado. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.imaging/ipartialargb32pixelloader) | El cargador de píxeles ARGB de 32 bits. |


**Example: The following example shows how to load and process pixels of a raster image using your own partial processor.**
El siguiente ejemplo muestra cómo cargar y procesar píxeles de una imagen raster utilizando su propio procesador parcial. Por ejemplo, considere un problema de contar píxeles totalmente transparentes de una imagen. Para contar píxeles transparentes usando el mecanismo de carga parcial, se introduce una clase separada TransparentArgb32PixelCounter que implementa com.aspose.imaging.IPartialArgb32PixelLoader.
``` java

// Primero, implemente com.aspose.imaging.IPartialArgb32PixelLoader para contar todos los píxeles totalmente transparentes.
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

// Este es un ejemplo de uso del contador.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Crear una instancia de com.aspose.imaging.IPartialArgb32PixelLoader y pasarla a com.aspose.imaging.RasterImage.LoadPartialArgb32Pixels
    TransparentArgb32PixelCounter counter = new TransparentArgb32PixelCounter();

    // Cargar píxeles para toda la imagen. Cualquier parte rectangular de la imagen puede especificarse como el primer parámetro del método com.aspose.imaging.RasterImage.loadPartialArgb32Pixels.
    rasterImage.loadPartialArgb32Pixels(rasterImage.getBounds(), counter);

    System.out.println("The number of fully transparent pixels is " + counter.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// La salida puede verse así:
// El número de píxeles totalmente transparentes es 55157
// El número total de píxeles es 120400
```

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


Carga píxeles parcialmente por paquetes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo deseado. |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.imaging/ipartialpixelloader) | El cargador de píxeles. |


**Example: The following example shows how to load and process pixels of a raster image using your own partial processor.**
El siguiente ejemplo muestra cómo cargar y procesar píxeles de una imagen raster usando su propio procesador parcial. Por ejemplo, considere un problema de contar píxeles totalmente transparentes de una imagen. Para contar los transparentes usando el mecanismo de carga parcial, se introduce una clase separada TransparentPixelCounter que implementa com.aspose.imaging.IPartialPixelLoader.
``` java

// Primero, implemente com.aspose.imaging.IPartialPixelLoader para contar todos los píxeles totalmente transparentes.
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

// Este es un ejemplo de uso del contador.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Crear una instancia de com.aspose.imaging.IPartialPixelLoader y pasarla a com.aspose.imaging.RasterImage.loadPartialPixels
    TransparentPixelCounter counter = new TransparentPixelCounter();

    // Cargar píxeles para toda la imagen. Cualquier parte rectangular de la imagen puede especificarse como el primer parámetro del método com.aspose.imaging.RasterImage.loadPartialPixels.
    rasterImage.loadPartialPixels(rasterImage.getBounds(), counter);

    System.out.println("The number of fully transparent pixels is " + counter.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// La salida puede verse así:
// El número de píxeles totalmente transparentes es 55157
// El número total de píxeles es 120400
```

### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


Carga píxeles ARGB de 32 bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo del cual cargar los píxeles. |

**Returns:**
int[] - La matriz de píxeles ARGB de 32 bits cargada.

**Example: The following example shows how to load and process pixels of a raster image.**
El siguiente ejemplo muestra cómo cargar y procesar píxeles de una imagen raster. Los píxeles se representan como valores enteros de 32 bits. Por ejemplo, considere un problema de contar píxeles totalmente transparentes de una imagen.
``` java

com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Cargar píxeles para toda la imagen. Cualquier parte rectangular de la imagen puede especificarse como un parámetro del método com.aspose.imaging.RasterImage.loadArgb32Pixels.
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


Carga píxeles ARGB de 64 bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo del cual cargar los píxeles. |

**Returns:**
long[] - La matriz de píxeles ARGB de 64 bits cargada.

**Example: The following example shows how to load and process pixels of a raster image.**
El siguiente ejemplo muestra cómo cargar y procesar píxeles de una imagen raster. Los píxeles se representan como valores enteros de 64 bits. Por ejemplo, considere un problema de contar píxeles totalmente transparentes de una imagen.
``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\16rgba.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Cargar píxeles para toda la imagen. Cualquier parte rectangular de la imagen puede especificarse como un parámetro del método com.aspose.imaging.RasterImage.loadArgb64Pixels.
    // Tenga en cuenta que la propia imagen debe tener 16 bits por muestra, porque com.aspose.imaging.RasterImage.loadArgb64Pixels no funciona con 8 bits por muestra.
    // Para trabajar con 8 bits por muestra, por favor use el clásico método com.aspose.imaging.RasterImage.loadArgb32Pixels.
    long[] pixels = rasterImage.loadArgb64Pixels(rasterImage.getBounds());

    int count = 0;
    for (long pixel : pixels) {
        // Tenga en cuenta que todos los componentes de color, incluido el alfa, se representan con valores de 16 bits, por lo que sus valores permitidos están en el rango [0, 63535].
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


Carga píxeles ARGB de 64 bits parcialmente por paquetes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo deseado. |
| partialPixelLoader | [IPartialArgb64PixelLoader](../../com.aspose.imaging/ipartialargb64pixelloader) | El cargador de píxeles ARGB de 64 bits. |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.imaging.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


Carga píxeles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo del cual cargar los píxeles. |

**Returns:**
com.aspose.imaging.Color[] - La matriz de píxeles cargada.

**Example: The following example shows how to load and process pixels of a raster image.**
El siguiente ejemplo muestra cómo cargar y procesar píxeles de una imagen raster. Por ejemplo, considere un problema de contar píxeles totalmente transparentes de una imagen.
``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Cargar píxeles para toda la imagen. Cualquier parte rectangular de la imagen puede especificarse como un parámetro del método Aspose.Imaging.RasterImage.LoadPixels.
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


Carga píxeles en formato CMYK. Este método está obsoleto. Por favor use de manera más eficaz el método `loadCmyk32Pixels(Rectangle)`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo del cual cargar los píxeles. |

**Returns:**
com.aspose.imaging.CmykColor[] - La matriz de píxeles CMYK cargada.
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.imaging.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


Carga píxeles en formato CMYK.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo del cual cargar los píxeles. |

**Returns:**
int[] - Los píxeles CMYK cargados se presentan como valores enteros de 32 bits.
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Carga datos de imagen sin procesar usando el mecanismo de procesamiento parcial.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El área rectangular deseada de la imagen desde la cual cargar datos. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | La configuración de datos sin procesar. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | El cargador de datos sin procesar. |


**Example: The following example shows how to extract pixels from the raw image data using RawDataSettings.**
El siguiente ejemplo muestra cómo extraer píxeles de los datos sin procesar de la imagen usando RawDataSettings. Por ejemplo, considere un problema de contar los píxeles totalmente transparentes de una imagen.
``` java

// Primero, implemente un contador. En el caso de datos sin procesar, el contador puede verse así:
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

        // Solo se consideran formatos simples aquí para simplificar el código.
        // Consideremos solo imágenes con 8 bits por muestra.
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
                        // El canal alfa se almacena al final, después de los componentes de color.
                        if (data[i + 3] == 0) {
                            this.count++;
                        }
                    }
                }
            }
            break;

            case com.aspose.imaging.PixelFormat.Grayscale: {
                if (channelBits.length == 2) {
                    // Grayscale Alpha
                    for (int i = 0; i < data.length; i += 2) {
                        // El canal alfa se almacena al final, después de los componentes de color.
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

// Aquí está el ejemplo principal de uso del contador
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\alpha.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;
    com.aspose.imaging.RawDataSettings settings = rasterImage.getRawDataSettings();

    TransparentPixelRawDataCounter rawDataLoader = new TransparentPixelRawDataCounter(settings);

    // Cargue píxeles para toda la imagen. Cualquier parte rectangular de la imagen puede especificarse como un parámetro del método Aspose.Imaging.RasterImage.LoadRawData.
    rasterImage.loadRawData(rasterImage.getBounds(), settings, rawDataLoader);

    System.out.println("The number of fully transparent pixels is " + rawDataLoader.getCount());
    System.out.println("The total number of pixels is " + (image.getWidth() * image.getHeight()));
} finally {
    image.dispose();
}

// La salida puede verse así:
// El número de píxeles totalmente transparentes es 55157
// El número total de píxeles es 120400
```

### loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-com.aspose.imaging.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle dstImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Carga datos sin procesar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo desde el cual cargar los datos sin procesar. |
| dstImageBounds | [Rectangle](../../com.aspose.imaging/rectangle) | Los límites de la imagen de destino. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | La configuración de datos sin procesar a usar para los datos cargados. Nota: si los datos no están en el formato especificado, se realizará una conversión de datos. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.imaging/ipartialrawdataloader) | El cargador de datos sin procesar. |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.imaging.Rectangle-com.aspose.imaging.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


Guarda los datos sin procesar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | byte[] | Los datos sin procesar. |
| dataOffset | int | El desplazamiento inicial de los datos sin procesar. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo de datos sin procesar. |
| rawDataSettings | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | La configuración de datos sin procesar en la que se encuentran los datos. |

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.imaging.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


Guarda los píxeles ARGB de 32 bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo donde guardar los píxeles. |
| píxeles | int[] | La matriz de píxeles ARGB de 32 bits. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
El siguiente ejemplo llena el área central de una imagen raster con píxeles negros usando el método com.aspose.imaging.RasterImage.saveArgb32Pixels.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // El cuadrado negro
    int[] pixels = new int[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getBlack().toArgb();
    }

    // Dibuja el cuadrado negro en el centro de la imagen.
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


Guarda los píxeles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo donde guardar los píxeles. |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | La matriz de píxeles. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
El siguiente ejemplo llena el área central de una imagen raster con píxeles negros usando el método com.aspose.imaging.RasterImage.savePixels.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // El cuadrado negro
    com.aspose.imaging.Color[] pixels = new com.aspose.imaging.Color[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = com.aspose.imaging.Color.getBlack();
    }

    // Dibuja el cuadrado negro en el centro de la imagen.
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


Convierte la imagen raster a bitmap.

**Returns:**
java.awt.image.BufferedImage - El mapa de bits

**Example: The following example converts a BMP image to a native Java bitmap.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;
    java.awt.image.BufferedImage bitmap = bmpImage.toBitmap();

    // Procesa el mapa de bits nativo de Java.
} finally {
    image.dispose();
}
```

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.imaging.Rectangle-com.aspose.imaging.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


Guarda los píxeles. Este método está obsoleto. Por favor, use el método más eficaz `saveCmyk32Pixels(Rectangle, int[])`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo donde guardar los píxeles. |
| pixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | La matriz de píxeles CMYK. |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.imaging.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


Guarda los píxeles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo donde guardar los píxeles. |
| píxeles | int[] | Los píxeles CMYK presentados como valores enteros de 32 bits. |


**Example: The following example fills the central area of a raster image with black pixels using the com.**
El siguiente ejemplo llena el área central de una imagen raster con píxeles negros usando el método com.aspose.imaging.RasterImage.saveCmyk32Pixels.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Obtén una representación entera del negro en el espacio de color CMYK.
    int blackCmyk = com.aspose.imaging.CmykColorHelper.toCmyk(com.aspose.imaging.Color.getBlack());

    // El cuadrado negro.
    int[] pixels = new int[(rasterImage.getWidth() / 2) * (rasterImage.getHeight() / 2)];
    for (int i = 0; i < pixels.length; i++) {
        pixels[i] = blackCmyk;
    }

    // Dibuja el cuadrado negro en el centro de la imagen.
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


Establece la resolución para este `RasterImage`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dpiX | double | La resolución horizontal, en puntos por pulgada, del `RasterImage`. |
| dpiY | double | La resolución vertical, en puntos por pulgada, del `RasterImage`. |


**Example: The following example shows how to set horizontal/vertical resolution of a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Obtener la resolución horizontal y vertical de la imagen
    double horizontalResolution = rasterImage.getHorizontalResolution();
    double verticalResolution = rasterImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilice el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
        System.out.println("Set resolution values to 96 dpi");
        rasterImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + rasterImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + rasterImage.getVerticalResolution());
    }

    // La salida puede verse así:
    // La resolución horizontal, en píxeles por pulgada: 300.0
    // La resolución vertical, en píxeles por pulgada: 300.0
    // Establecer los valores de resolución a 96 dpi
    // La resolución horizontal, en píxeles por pulgada: 96.0
    // La resolución vertical, en píxeles por pulgada: 96.0
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Establece la paleta de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta a establecer. |
| updateColors | boolean | si se establece en `true` los colores se actualizarán según la nueva paleta; de lo contrario, los índices de color permanecerán sin cambios. Tenga en cuenta que los índices sin cambios pueden provocar un error al cargar la imagen si algunos índices no tienen entradas correspondientes en la paleta. |

### autoRotate() {#autoRotate--}
```
public final void autoRotate()
```


Rota automáticamente la imagen según los datos de orientación extraídos de los metadatos Exif. Este método garantiza que las imágenes se muestren en la orientación correcta, mejorando la experiencia del usuario y eliminando la necesidad de ajustes manuales. Al analizar la información Exif, la imagen se rota en consecuencia, proporcionando una experiencia de visualización fluida en diferentes plataformas y dispositivos. Este proceso de rotación automatizado simplifica la gestión de imágenes y mejora la usabilidad general, especialmente al trabajar con grandes lotes de imágenes con orientaciones variables.

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Redimensiona la imagen con opciones extendidas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | La configuración de redimensionado. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Rota la imagen alrededor del centro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación en grados. Los valores positivos girarán en sentido horario. |
| resizeProportionally | boolean | Si se establece en `true` el tamaño de su imagen cambiará según las proyecciones del rectángulo rotado (puntos de esquina); en otro caso, las dimensiones permanecerán sin tocar y solo se rotará el contenido interno de la imagen. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Color del fondo. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Rota la imagen alrededor del centro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación en grados. Los valores positivos girarán en sentido horario. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarización de una imagen con umbral predefinido

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threshold | byte | Valor del umbral. Si el valor gris correspondiente de un píxel es mayor que el umbral, se le asignará un valor de 255; de lo contrario, 0. |


**Example: The following example binarizes a raster image with the predefined threshold.**
El siguiente ejemplo binariza una imagen raster con el umbral predefinido. Las imágenes binarizadas contienen solo 2 colores: negro y blanco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Binariza la imagen con un valor de umbral de 127.
    // Si el valor gris correspondiente de un píxel es mayor que 127, se le asignará un valor de 255, 0 en caso contrario.
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


Binarización de una imagen con umbralización de Otsu


**Example: The following example binarizes a raster image with Otsu thresholding.**
El siguiente ejemplo binariza una imagen raster con umbralización de Otsu. Las imágenes binarizadas contienen solo 2 colores: negro y blanco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Binariza la imagen con umbralización de Otsu.
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


Binarización de una imagen usando el algoritmo de umbralización adaptativa de Bradley mediante la umbralización de imagen integral

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightnessDifference | double | La diferencia de brillo entre el píxel y el promedio de una ventana de s x s píxeles centrada en este píxel. |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binarización de una imagen usando el algoritmo de umbralización adaptativa de Bradley mediante la umbralización de imagen integral

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightnessDifference | double | La diferencia de brillo entre el píxel y el promedio de una ventana de s x s píxeles centrada en este píxel. |
| windowSize | int | El tamaño de la ventana de s x s píxeles centrada en este píxel |


**Example: The following example binarizes a raster image with Bradley's adaptive thresholding algorithm with the specified window size.**
El siguiente ejemplo binariza una imagen raster con el algoritmo de umbral adaptativo de Bradley con el tamaño de ventana especificado. Las imágenes binarizadas contienen solo 2 colores: negro y blanco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Binariza la imagen con una diferencia de brillo de 5. El brillo es la diferencia entre un píxel y el promedio de una ventana de 10 x 10 píxeles centrada en ese píxel.
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


Mezcla esta instancia de imagen con la imagen `overlay`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | El origen de la fusión de la imagen de fondo. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen superpuesta. |
| overlayArea | [Rectangle](../../com.aspose.imaging/rectangle) | El área superpuesta. |

### blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-}
```
public void blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)
```


Mezcla esta instancia de imagen con la imagen `overlay`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | El origen de la fusión de la imagen de fondo. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen superpuesta. |
| overlayArea | [Rectangle](../../com.aspose.imaging/rectangle) | El área superpuesta. |
| overlayAlpha | byte | El alfa de la superposición. |

### blend(Point origin, RasterImage overlay) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-}
```
public final void blend(Point origin, RasterImage overlay)
```


Mezcla esta instancia de imagen con el `overlay` con alfa == 255.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | El origen de la fusión de la imagen de fondo. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | La superposición. |

### blend(Point origin, RasterImage overlay, byte overlayAlpha) {#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-byte-}
```
public final void blend(Point origin, RasterImage overlay, byte overlayAlpha)
```


Mezcla esta instancia de imagen con el `overlay`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origin | [Point](../../com.aspose.imaging/point) | El origen de la fusión de la imagen de fondo. |
| overlay | [RasterImage](../../com.aspose.imaging/rasterimage) | La superposición. |
| overlayAlpha | byte | El alfa de la superposición. |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformación de una imagen a su representación en escala de grises


**Example: The following example transforms a colored raster image to its grayscale representation.**
El siguiente ejemplo transforma una imagen raster a color a su representación en escala de grises. Las imágenes en escala de grises están compuestas exclusivamente por tonos de gris y solo contienen información de intensidad.
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


Normaliza el histograma de la imagen \\u2014 ajusta los valores de píxel para usar todo el rango disponible.

### autoBrightnessContrast() {#autoBrightnessContrast--}
```
public void autoBrightnessContrast()
```


Normalización automática adaptativa de brillo y contraste para toda la imagen.

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Ajuste de brillo para la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightness | int | Valor de brillo. |


**Example: The following example performs brightness correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Establece el valor de brillo. Los valores aceptados de brillo están en el rango [-255, 255].
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


Contraste de la imagen

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contrast | float | Valor de contraste (en el rango [-100; 100]) |


**Example: The following example performs contrast correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Establece el valor de contraste. Los valores aceptados de contraste están en el rango [-100f, 100f].
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


Incrusta una firma digital basada en la contraseña proporcionada en la imagen usando esteganografía.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contraseña | java.lang.String | La contraseña utilizada para generar datos de firma digital |


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


Calcula el porcentaje de similitud entre los datos extraídos y la contraseña original.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contraseña | java.lang.String | La contraseña utilizada para extraer los datos incrustados. |

**Returns:**
int - El valor de porcentaje de similitud.
### isDigitalSigned(String password) {#isDigitalSigned-java.lang.String-}
```
public boolean isDigitalSigned(String password)
```


Realiza una verificación rápida para determinar si la imagen está firmada digitalmente, usando la contraseña proporcionada y el umbral.

--------------------

Este método proporciona la detección más rápida al aprovechar `GetSignPercentage`. Una vez que los datos extraídos cumplen con el umbral especificado, se omiten los pasos de extracción adicionales destinados a mejorar la precisión de la detección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contraseña | java.lang.String | La contraseña para verificar la firma. |

**Returns:**
boolean - Verdadero si la imagen está firmada, de lo contrario falso.
### isDigitalSigned(String password, int percentageThreshold) {#isDigitalSigned-java.lang.String-int-}
```
public boolean isDigitalSigned(String password, int percentageThreshold)
```


Realiza una verificación rápida para determinar si la imagen está firmada digitalmente, usando la contraseña proporcionada y el umbral.

--------------------

Este método proporciona la detección más rápida al aprovechar `GetSignPercentage`. Una vez que los datos extraídos cumplen con el umbral especificado, se omiten los pasos de extracción adicionales destinados a mejorar la precisión de la detección.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contraseña | java.lang.String | La contraseña para verificar la firma. |
| percentageThreshold | int | El umbral (en porcentaje)[0-100] que determina si la imagen se considera firmada. Si no se especifica, se aplicará un umbral predeterminado (`75`). |

**Returns:**
boolean - Verdadero si la imagen está firmada, de lo contrario falso.
### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Corrección gamma de una imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gammaRed | float | Gamma para el coeficiente del canal rojo |
| gammaGreen | float | Gamma para el coeficiente del canal verde |
| gammaBlue | float | Coeficiente gamma para el canal azul |


**Example: The following example performs gamma-correction of an image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Establecer coeficientes gamma individuales para los canales rojo, verde y azul.
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


Corrección gamma de una imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gamma | float | Coeficiente gamma para los canales rojo, verde y azul |


**Example: The following example performs gamma-correction of an image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Establecer el coeficiente gamma para los canales rojo, verde y azul.
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


Obtiene el ángulo de sesgo. Este método es aplicable a documentos de texto escaneados, para determinar el ángulo de sesgo al escanear.

**Returns:**
float - El ángulo de sesgo, en grados.
### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


Normaliza el ángulo. Este método es aplicable a documentos de texto escaneados para eliminar el escaneo sesgado. Este método usa \#getSkewAngle.getSkewAngle y [Image.rotate(float)](../../com.aspose.imaging/image\#rotate-float-) métodos.

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Normaliza el ángulo. Este método es aplicable a documentos de texto escaneados para eliminar el escaneo sesgado. Este método usa \#getSkewAngle.getSkewAngle y \#rotate(float, boolean, Color).rotate(float, boolean, Color) métodos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resizeProportionally | boolean | Si se establece en `true` el tamaño de su imagen cambiará según las proyecciones del rectángulo rotado (puntos de esquina); en otro caso, las dimensiones permanecerán sin tocar y solo se rotará el contenido interno de la imagen. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Color del fondo. |


**Example: Skew is an artifact that might appear during document scanning process when the text/images of the document get rotated at a slight angle.**
La distorsión (skew) es un artefacto que puede aparecer durante el proceso de escaneo de documentos cuando el texto/las imágenes del documento se rotan ligeramente. Puede tener varias causas, pero la más común es que el papel se desplace durante el escaneo. Por lo tanto, deskew es el proceso de detectar y corregir este problema en archivos escaneados (es decir, bitmap) de modo que los documentos corregidos tengan el texto/las imágenes correctamente y horizontalmente ajustados.
``` java
String dir = "c:\\aspose.imaging\\issues\\java\\1461\\";

String inputFilePath = dir + "skewed.png";
String outputFilePath = dir + "skewed.out.png";

// Elimina el escaneo sesgado con los parámetros predeterminados.
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


Filtra el rectángulo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Las opciones. |


**Example: The following example applies various types of filters to a raster image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Aplica un filtro mediano con un tamaño de rectángulo de 5 a toda la imagen.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    rasterImage.save(dir + "sample.MedianFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Aplica un filtro de suavizado bilateral con un tamaño de kernel de 5 a toda la imagen.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    rasterImage.save(dir + "sample.BilateralSmoothingFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Aplica un filtro de desenfoque gaussiano con un radio de 5 y un valor sigma de 4.0 a toda la imagen.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussianBlurFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Aplica un filtro Gauss-Wiener con un radio de 5 y un valor de suavizado de 4.0 a toda la imagen.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Aplica un filtro wiener de movimiento con una longitud de 5, un valor de suavizado de 4.0 y un ángulo de 90.0 grados a toda la imagen.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.save(dir + "sample.MotionWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Aplica un filtro de nitidez con un tamaño de kernel de 5 y un valor sigma de 4.0 a toda la imagen.
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


Reemplaza un color por otro con diferencia permitida y conserva el valor alfa original para mantener bordes suaves.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.imaging/color) | Color antiguo a ser reemplazado. |
| oldColorDiff | byte | Diferencia permitida en el color antiguo para poder ampliar el tono del color reemplazado. |
| newColor | [Color](../../com.aspose.imaging/color) | Nuevo color para reemplazar el color antiguo. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Reemplaza un color por otro con diferencia permitida y conserva el valor alfa original para mantener bordes suaves.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oldColorArgb | int | Valor ARGB del color antiguo que será reemplazado. |
| oldColorDiff | byte | Diferencia permitida en el color antiguo para poder ampliar el tono del color reemplazado. |
| newColorArgb | int | Nuevo valor ARGB del color para reemplazar el color antiguo. |

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.imaging.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


Reemplaza todos los colores no transparentes con el nuevo color y preserva el valor alfa original para mantener bordes suaves. Nota: si lo usas en imágenes sin transparencia, todos los colores se reemplazarán por uno único.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.imaging/color) | Nuevo color para reemplazar colores no transparentes. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Reemplaza todos los colores no transparentes con el nuevo color y preserva el valor alfa original para mantener bordes suaves. Nota: si lo usas en imágenes sin transparencia, todos los colores se reemplazarán por uno único.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorArgb | int | Nuevo valor ARGB del color para reemplazar los colores no transparentes. |

