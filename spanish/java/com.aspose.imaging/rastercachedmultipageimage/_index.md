---
title: "RasterCachedMultipageImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La imagen raster multipágina"
type: docs
weight: 90
url: /es/java/com.aspose.imaging/rastercachedmultipageimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImage](../../com.aspose.imaging/imultipageimage)
```
public abstract class RasterCachedMultipageImage extends RasterCachedImage implements IMultipageImage
```

La imagen raster multipágina
## Métodos

| Método | Descripción |
| --- | --- |
| [getHeight()](#getHeight--) | Obtiene la altura de la imagen. |
| [getWidth()](#getWidth--) | Obtiene el ancho de la imagen. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtiene la cantidad de bits por píxel de la imagen. |
| [isCached()](#isCached--) | Obtiene un valor que indica si los datos de la imagen están almacenados en caché actualmente. |
| [hasAlpha()](#hasAlpha--) | Obtiene un valor que indica si esta instancia tiene alfa. |
| [hasTransparentColor()](#hasTransparentColor--) | Obtiene un valor que indica si la imagen tiene un color transparente. |
| [getImageOpacity()](#getImageOpacity--) | Obtiene la opacidad de esta imagen. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtiene un valor para el color de fondo. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Establece un valor para el color de fondo. |
| [getMetadata()](#getMetadata--) | Obtiene datos XMP del fotograma. |
| [getPageExportingAction()](#getPageExportingAction--) | Obtiene la acción de exportación de la página. |
| [setPageExportingAction(PageExportingAction value)](#setPageExportingAction-com.aspose.imaging.PageExportingAction-) | Establece la acción de exportación de la página. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Ajuste de `brightness` para la imagen. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | [Imagen](../../com.aspose.imaging/image) contrastando |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Corrección gamma de una imagen. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Corrección gamma de una imagen. |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | Mezcla esta instancia de imagen con la imagen `overlay`. |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | Incrusta una firma digital basada en la contraseña proporcionada en cada página de la imagen. |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | Calcula el porcentaje de similitud entre los datos extraídos y la contraseña original. |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | Realiza una verificación rápida para determinar si la imagen está firmada digitalmente, usando la contraseña proporcionada y el umbral. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarización de una imagen con umbral predefinido |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarización de una imagen usando el algoritmo de umbralización adaptativa de Bradley mediante la umbralización de imagen integral |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Binarización de una imagen usando el algoritmo de umbralización adaptativa de Bradley mediante la umbralización de imagen integral |
| [binarizeOtsu()](#binarizeOtsu--) | Binarización de una imagen con umbralización de Otsu |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recorta la imagen. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Recorta la imagen con desplazamientos. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Realiza dithering en la imagen actual. |
| [grayscale()](#grayscale--) | Transformación de una imagen a su representación en escala de grises |
| [normalizeHistogram()](#normalizeHistogram--) | Normaliza el histograma de la imagen \\u2014 ajusta los valores de píxel para usar todo el rango disponible. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | `RasterCachedMultipageImage.rotate` gira la imagen alrededor del centro. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Rota, voltea o rota y voltea todas las páginas. |
| [rotateFlipAll(int rotateFlip)](#rotateFlipAll-int-) | Rota todo el volteo. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Redimensiona la imagen. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Redimensiona la imagen. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Redimensiona el ancho proporcionalmente. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Redimensiona el ancho proporcionalmente. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Reemplaza un color por otro con diferencia permitida y conserva el valor alfa original para mantener bordes suaves. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Reemplaza todos los colores no transparentes con un nuevo color y conserva el valor alfa original para mantener bordes suaves. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Filtra el rectángulo especificado. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | Normaliza el ángulo. |
| [cacheData()](#cacheData--) | Almacena en caché los datos de forma privada. |

## Example: The following example shows batch conversion before saving (exporting) Tiff images.

``` java
String fileName = "10MB_Tif.tif";
String inputFileName = fileName;

String outputFileNameTif = "output.tif";

//Se implementa la posibilidad de conversión por lotes antes de guardar (exportar) imágenes Tiff.

try(com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(inputFileName))
{
    // Establece la operación por lotes para las páginas.
    tiffImage.setPageExportingAction(new PageExportingAction()
    {
        @Override
        public void invoke(int pageIndex, Image page)
        {
            // Ejecuta la recolección de basura para evitar el almacenamiento innecesario de basura de páginas anteriores.
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


Obtiene la altura de la imagen.

Valor: La altura de la imagen.

**Returns:**
int - la altura de la imagen.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene el ancho de la imagen.

Valor: El ancho de la imagen.

**Returns:**
int - el ancho de la imagen.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtiene la cantidad de bits por píxel de la imagen.

Valor: El recuento de bits por píxel de la imagen.

**Returns:**
int - el recuento de bits por píxel de la imagen.
### isCached() {#isCached--}
```
public boolean isCached()
```


Obtiene un valor que indica si los datos de la imagen están almacenados en caché actualmente.

Valor: `true` si los datos de la imagen están en caché; de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si los datos de la imagen están en caché actualmente.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Obtiene un valor que indica si esta instancia tiene alfa.

Valor: `true` si esta instancia tiene alfa; de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si esta instancia tiene alfa.
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Obtiene un valor que indica si la imagen tiene un color transparente.

--------------------

Esta implementación verifica el valor de `RasterImage.HasTransparentColor`([RasterImage.hasTransparentColor](../../com.aspose.imaging/rasterimage\\#hasTransparentColor)/[RasterImage.setTransparentColor(boolean)](../../com.aspose.imaging/rasterimage\\#setTransparentColor-boolean-)) de la `DefaultPage`(\\#getDefaultPage\\_internalized.getDefaultPage\\_internalized).

**Returns:**
boolean - un valor que indica si la imagen tiene un color transparente.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Obtiene la opacidad de esta imagen.

Valor: El valor de opacidad entre 0.0 (totalmente transparente) y 1.0 (totalmente opaco).

**Returns:**
float - opacidad de esta imagen.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtiene un valor para el color de fondo.

**Returns:**
[Color](../../com.aspose.imaging/color) - a value for the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Establece un valor para el color de fondo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | un valor para el color de fondo. |

### getMetadata() {#getMetadata--}
```
public ImageMetadata getMetadata()
```


Obtiene datos XMP del fotograma.

Valor: contenedor de datos del paquete XMP

**Returns:**
[ImageMetadata](../../com.aspose.imaging.metadata/imagemetadata) - XMP data from frame.
### getPageExportingAction() {#getPageExportingAction--}
```
public PageExportingAction getPageExportingAction()
```


Obtiene la acción de exportación de la página. Tenga en cuenta que establecer este método liberará automáticamente los recursos de la página después de que se ejecute. Se ejecutará justo antes de que cada página se guarde.

Valor: La acción de exportación de la página.

**Returns:**
[PageExportingAction](../../com.aspose.imaging/pageexportingaction) - the page exporting action.
### setPageExportingAction(PageExportingAction value) {#setPageExportingAction-com.aspose.imaging.PageExportingAction-}
```
public void setPageExportingAction(PageExportingAction value)
```


Establece la acción de exportación de la página. Tenga en cuenta que establecer este método liberará automáticamente los recursos de la página después de que se ejecute. Se ejecutará justo antes de que cada página se guarde.

Valor: La acción de exportación de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PageExportingAction](../../com.aspose.imaging/pageexportingaction) | la acción de exportación de la página. |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Ajuste de `brightness` para la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightness | int | Valor de brillo. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


[Image](../../com.aspose.imaging/image) contrasting

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contrast | float | Valor de contraste (en el rango [-100; 100]) |

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

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Corrección gamma de una imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gamma | float | Coeficiente gamma para los canales rojo, verde y azul |

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

### embedDigitalSignature(String password) {#embedDigitalSignature-java.lang.String-}
```
public void embedDigitalSignature(String password)
```


Incrusta una firma digital basada en la contraseña proporcionada en cada página de la imagen.

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

--------------------

Debido a imágenes multipágina, el resultado representa el `MIDDLE AVERAGED signing percentage` calculado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contraseña | java.lang.String | La contraseña utilizada para extraer los datos incrustados. |

**Returns:**
int - El valor de porcentaje de similitud.
### isDigitalSigned(String password, int percentageThreshold) {#isDigitalSigned-java.lang.String-int-}
```
public boolean isDigitalSigned(String password, int percentageThreshold)
```


Realiza una verificación rápida para determinar si la imagen está firmada digitalmente, usando la contraseña proporcionada y el umbral.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contraseña | java.lang.String | La contraseña para verificar la firma. |
|  | percentageThreshold | int | El umbral (en porcentaje)[0-100] que determina si la imagen se considera firmada. Si no se especifica, se aplicará un umbral predeterminado (`75`). |

--------------------

Este método proporciona la detección más rápida al aprovechar `GetSignPercentage`. Una vez que los datos extraídos cumplen con el umbral especificado, se omiten los pasos de extracción adicionales destinados a mejorar la precisión de la detección.

El resultado es `true` solo si todas las páginas en la imagen multipágina se reconocen como firmadas; de lo contrario, la imagen se considera no firmada. |

**Returns:**
boolean - Verdadero si la imagen está firmada, de lo contrario falso.
### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarización de una imagen con umbral predefinido

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threshold | byte | Valor del umbral. Si el valor gris correspondiente de un píxel es mayor que el umbral, se le asignará un valor de 255; de lo contrario, 0. |

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

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Binarización de una imagen usando el algoritmo de umbralización adaptativa de Bradley mediante la umbralización de imagen integral

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightnessDifference | double | La diferencia de brillo entre el píxel y el promedio de una ventana de s x s píxeles centrada en este píxel. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Binarización de una imagen con umbralización de Otsu

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Recorta la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Recorta la imagen con desplazamientos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| leftShift | int | El desplazamiento izquierdo. |
| rightShift | int | El desplazamiento derecho. |
| topShift | int | El desplazamiento superior. |
| bottomShift | int | El desplazamiento inferior. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Realiza dithering en la imagen actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ditheringMethod | int | El método de tramado. |
| bitsCount | int | El recuento final de bits para el tramado. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta personalizada para el tramado. |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformación de una imagen a su representación en escala de grises

### normalizeHistogram() {#normalizeHistogram--}
```
public void normalizeHistogram()
```


Normaliza el histograma de la imagen \\u2014 ajusta los valores de píxel para usar todo el rango disponible.

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


`RasterCachedMultipageImage.rotate` gira la imagen alrededor del centro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación en grados. Los valores positivos girarán en sentido horario. |
| resizeProportionally | boolean | si se establece en `true` el tamaño de su imagen cambiará según las proyecciones del rectángulo girado (puntos de esquina); de lo contrario, se dejarán las dimensiones sin cambios y solo `` el contenido de la imagen será rotado. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Color del fondo. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Rota, voltea o rota y voltea todas las páginas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotateFlipType | int | El tipo de rotación y volteo. |

### rotateFlipAll(int rotateFlip) {#rotateFlipAll-int-}
```
public void rotateFlipAll(int rotateFlip)
```


Rota todo el volteo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotateFlip | int | El volteo de rotación. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Redimensiona la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| resizeType | int | El tipo de redimensionado. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Redimensiona la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | La configuración de redimensionado. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Redimensiona el ancho proporcionalmente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| resizeType | int | Tipo de redimensionado. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Redimensiona el ancho proporcionalmente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newHeight | int | El nuevo alto. |
| resizeType | int | Tipo de redimensionado. |

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

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Reemplaza todos los colores no transparentes con el nuevo color y preserva el valor alfa original para mantener bordes suaves. Nota: si lo usas en imágenes sin transparencia, todos los colores se reemplazarán por uno único.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newColorArgb | int | Nuevo valor ARGB del color para reemplazar los colores no transparentes. |

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

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Normaliza el ángulo. Este método es aplicable a documentos de texto escaneados para eliminar la distorsión del escaneo. Este método usa [RasterImage.getSkewAngle](../../com.aspose.imaging/rasterimage\#getSkewAngle) y [RasterImage.rotate(float, boolean, Color)](../../com.aspose.imaging/rasterimage\#rotate-float--boolean--Color-) métodos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resizeProportionally | boolean | Si se establece en `true` el tamaño de su imagen cambiará según las proyecciones del rectángulo rotado (puntos de esquina); en otro caso, las dimensiones permanecerán sin tocar y solo se rotará el contenido interno de la imagen. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Color del fondo. |

### cacheData() {#cacheData--}
```
public void cacheData()
```


Almacena en caché los datos de forma privada.

