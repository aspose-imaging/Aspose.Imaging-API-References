---
title: "RasterCachedImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Representa una imagen raster que soporta operaciones de gráficos raster."
type: docs
weight: 89
url: /es/java/com.aspose.imaging/rastercachedimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage)
```
public abstract class RasterCachedImage extends RasterImage
```

Representa una imagen raster que admite operaciones gráficas raster. Esta imagen almacena en caché los datos de píxeles cuando es necesario.
## Métodos

| Método | Descripción |
| --- | --- |
| [isCached()](#isCached--) | Obtiene un valor que indica si los datos de la imagen están almacenados en caché actualmente. |
| [cacheData()](#cacheData--) | Cachea los datos y asegura que no se realizará una carga adicional de datos desde el `DataStreamSupporter.DataStreamContainer` subyacente. |
| [blend(Point origin, RasterImage overlay, Rectangle overlayArea, byte overlayAlpha)](#blend-com.aspose.imaging.Point-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-byte-) | Mezcla esta instancia de imagen con la imagen `overlay`. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Redimensiona la imagen. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Redimensiona la imagen. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Rota, voltea o rota y voltea la imagen. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Rota la imagen alrededor del centro. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recorta la imagen. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Realiza dithering en la imagen actual. |
| [grayscale()](#grayscale--) | Transformación de una imagen a su representación en escala de grises |
| [normalizeHistogram()](#normalizeHistogram--) | Normaliza el histograma de la imagen \\u2014 ajusta los valores de píxel para usar todo el rango disponible. |
| [autoBrightnessContrast()](#autoBrightnessContrast--) | Realiza una normalización automática adaptativa de brillo y contraste para toda la imagen. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarización de una imagen con umbral predefinido |
| [binarizeOtsu()](#binarizeOtsu--) | Binarización de una imagen con umbralización de Otsu |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarización de una imagen usando el algoritmo de umbralización adaptativa de Bradley mediante la umbralización de imagen integral |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Binarización de una imagen usando el algoritmo de umbralización adaptativa de Bradley mediante la umbralización de imagen integral |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Ajuste de brillo para la imagen. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Contraste de la imagen |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Corrección gamma de una imagen. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Corrección gamma de una imagen. |
| [embedDigitalSignature(String password)](#embedDigitalSignature-java.lang.String-) | Incrusta una firma digital basada en la contraseña proporcionada en la imagen usando esteganografía. |
| [analyzePercentageDigitalSignature(String password)](#analyzePercentageDigitalSignature-java.lang.String-) | Calcula el porcentaje de similitud entre los datos extraídos y la contraseña original. |
| [isDigitalSigned(String password, int percentageThreshold)](#isDigitalSigned-java.lang.String-int-) | Realiza una verificación rápida para determinar si la imagen está firmada digitalmente, usando la contraseña proporcionada y el umbral. |

## Example: The following example transforms a colored raster cached image to its grayscale representation.
El siguiente ejemplo transforma una imagen rasterizada en caché de color a su representación en escala de grises. Las imágenes en escala de grises están compuestas exclusivamente de tonos de gris y solo contienen información de intensidad.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    rasterImage.grayscale();
    rasterImage.save(dir + "sample.Grayscale.png");
} finally {
    image.dispose();
}
```

### isCached() {#isCached--}
```
public boolean isCached()
```


Obtiene un valor que indica si los datos de la imagen están almacenados en caché actualmente.

**Returns:**
boolean - `true` si los datos de la imagen están en caché; de lo contrario, `false`.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Cachea los datos y asegura que no se realizará una carga adicional de datos desde el `DataStreamSupporter.DataStreamContainer` subyacente.


**Example: The following example shows how raster image caching affects performance.**
El siguiente ejemplo muestra cómo el almacenamiento en caché de imágenes raster afecta el rendimiento. En caso general, la lectura de datos en caché se realiza más rápido que la lectura de datos no almacenados en caché.
``` java
String dir = "c:\\temp\\";

// Carga una imagen desde un archivo PNG.
com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Almacena en caché todos los datos de píxeles para que no se realice una carga adicional de datos desde el flujo de datos subyacente
    image.cacheData();

    long startTime = System.currentTimeMillis();

    // Leer todos los píxeles es bastante rápido.
    for (int y = 0; y < image.getHeight(); y++) {
        for (int x = 0; x < image.getWidth(); x++) {
            int color = image.getArgb32Pixel(x, y);
        }
    }

    long stopTime = System.currentTimeMillis();
    long elapsedMilliseconds = stopTime - startTime;
    System.out.println("Reading all cached pixels took " + elapsedMilliseconds + " ms.");
} finally {
    image.dispose();
}

// Cargar una imagen desde un archivo PNG
image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    long startTime = System.currentTimeMillis();

    // Leer todos los píxeles no es tan rápido como al almacenar en caché
    for (int y = 0; y < image.getHeight(); y++) {
        for (int x = 0; x < image.getWidth(); x++) {
            int color = image.getArgb32Pixel(x, y);
        }
    }

    long stopTime = System.currentTimeMillis();
    long elapsedMilliseconds = stopTime - startTime;
    System.out.println("Reading all pixels without preliminary caching took " + elapsedMilliseconds + " ms.");
} finally {
    image.dispose();
}

// La salida puede verse así:
//Leer todos los píxeles almacenados en caché tomó 2923 ms.
//    java.lang.OutOfMemoryError
//at com.aspose.imaging.internal.G.be.b(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.be.a(Unknown Source)
//at com.aspose.imaging.internal.G.aB.a(Unknown Source)
//at com.aspose.imaging.RasterImage.a(Unknown Source)
//at com.aspose.imaging.RasterImage.getArgb32Pixel(Unknown Source)
//at com.aspose.examples.ExamplesTest.Test(ExamplesTest.java:54)
```

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


**Example: This example loads a raster cached image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Escalar 2 veces usando remuestreo de vecino más cercano.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Guardar como PNG con opciones predeterminadas.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Reducir 2 veces usando remuestreo de vecino más cercano.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Guardar como PNG con opciones predeterminadas.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Escalar 2 veces usando remuestreo bilineal.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Guardar como PNG con opciones predeterminadas.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Reducir 2 veces usando remuestreo bilineal.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Guardar como PNG con opciones predeterminadas.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

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


**Example: This example loads a raster cached image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// El algoritmo adaptativo basado en una función racional ponderada y combinada y en la interpolación lanczos3.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// El pequeño filtro rectangular
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// El número de colores en la paleta.
resizeSettings.setEntriesCount(256);

// La cuantización de color no se usa
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// El método euclidiano
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    // Reducir a la mitad usando remuestreo adaptativo.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);
    image.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Rota, voltea o rota y voltea la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotateFlipType | int | El tipo de volteo rotativo. |


**Example: This example loads a raster cached image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

// Esta es una clase auxiliar.
class LocalHelper {
    // Obtiene una representación en cadena del tipo de volteo rotativo.
    public String rotateFlipTypeToString(int rotateFilpType) {
        switch (rotateFilpType) {
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipNone:
                return "RotateNoneFlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipNone:
                return "Rotate90FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipNone:
                return "Rotate180FlipNone";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipNone:
                return "Rotate270FlipNone";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipX:
                return "RotateNoneFlipX";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipX:
                return "Rotate90FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipX:
                return "Rotate180FlipX";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipX:
                return "Rotate270FlipX";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipY:
                return "RotateNoneFlipY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipY:
                return "Rotate90FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipY:
                return "Rotate180FlipY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipY:
                return "Rotate270FlipY";
            case com.aspose.imaging.RotateFlipType.RotateNoneFlipXY:
                return "RotateNoneFlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate90FlipXY:
                return "Rotate90FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate180FlipXY:
                return "Rotate180FlipXY";
            case com.aspose.imaging.RotateFlipType.Rotate270FlipXY:
                return "Rotate270FlipXY";
            default:
                throw new java.lang.IllegalArgumentException("rotateFlipType");
        }
    }
}

// Aquí está el ejemplo principal
int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

LocalHelper localHelper = new LocalHelper();
for (int rotateFlipType : rotateFlipTypes) {
    // Rotar, voltear y guardar en el archivo de salida.
    com.aspose.imaging.RasterCachedImage image = (com.aspose.imaging.RasterCachedImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + localHelper.rotateFlipTypeToString(rotateFlipType) + ".bmp");
    } finally {
        image.dispose();
    }
}
```

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

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Recorta la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo. |


**Example: The following example crops a raster cached image.**
El siguiente ejemplo recorta una imagen raster en caché. El área de recorte se especifica mediante com.aspose.imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Recorte la imagen. El área de recorte es la zona rectangular central de la imagen.
    int width = rasterImage.getWidth();
    int height = rasterImage.getHeight();
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(width / 4, height / 4, width / 2, height / 2);
    rasterImage.crop(area);

    // Guarde la imagen recortada en PNG
    rasterImage.save(dir + "sample.Crop.png");
} finally {
    image.dispose();
}
```

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


**Example: The following example transforms a colored raster cached image to its grayscale representation.**
El siguiente ejemplo transforma una imagen rasterizada en caché de color a su representación en escala de grises. Las imágenes en escala de grises están compuestas exclusivamente de tonos de gris y solo contienen información de intensidad.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

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


Realiza una normalización automática adaptativa de brillo y contraste para toda la imagen.

--------------------

> ```
> // Example usage in image pre-processing:
>  image.AutoBrightnessContrast();
> ```

--------------------

Este método aplica una cadena de filtros adaptativos avanzados (CLAHE, estiramiento blanco adaptativo y balance de blancos automático) para mejorar la calidad visual de la imagen al realzar el contraste, el brillo local y la fidelidad del color.

`**Pipeline de filtros:**`

1.  Ecualización de histograma adaptativa limitada por contraste (CLAHE) \\u2013 mejora el contraste local y realza los detalles tenues.
2.  Estiramiento blanco adaptativo \\u2013 aumenta el nivel de blanco efectivo mientras protege los detalles oscuros.
3.  Balance de blancos automático \\u2013 corrige los matices de color equilibrando los histogramas de los canales.

`**Nota:**`

 *  
 *  

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarización de una imagen con umbral predefinido

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threshold | byte | Valor del umbral. Si el valor gris correspondiente de un píxel es mayor que el umbral, se le asignará un valor de 255; de lo contrario, 0. |


**Example: The following example binarizes a raster cached image with the predefined threshold.**
El siguiente ejemplo binariza una imagen raster en caché con el umbral predefinido. Las imágenes binarizadas contienen solo 2 colores: negro y blanco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

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


**Example: The following example binarizes a raster cached image with Otsu thresholding.**
El siguiente ejemplo binariza una imagen raster en caché con umbralización de Otsu. Las imágenes binarizadas contienen solo 2 colores: negro y blanco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Binariza la imagen con umbralización de Otsu.
    rasterImage.binarizeOtsu();
    rasterImage.save(dir + "sample.BinarizeOtsu.png");
} finally {
    image.dispose();
}
```

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


**Example: The following example binarizes a raster cached image with Bradley's adaptive thresholding algorithm with the specified window size.**
El siguiente ejemplo binariza una imagen raster en caché con el algoritmo de umbralización adaptativa de Bradley con el tamaño de ventana especificado. Las imágenes binarizadas contienen solo 2 colores: negro y blanco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Binariza la imagen con una diferencia de brillo de 5.
    // El brillo es una diferencia entre un píxel y el promedio de una ventana de 10 x 10 píxeles centrada en este píxel.
    rasterImage.binarizeBradley(5, 10);
    rasterImage.save(dir + "sample.BinarizeBradley5_10x10.png");
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


**Example: The following example binarizes a raster cached image with Bradley's adaptive thresholding algorithm.**
El siguiente ejemplo binariza una imagen raster en caché con el algoritmo de umbralización adaptativa de Bradley. Las imágenes binarizadas contienen solo 2 colores: negro y blanco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Binariza la imagen con una diferencia de brillo de 5.
    // El brillo es una diferencia entre un píxel y el promedio de una ventana de s x s píxeles centrada en este píxel.
    // El tamaño de la ventana se calibrará automáticamente.
    rasterImage.binarizeBradley(5);
    rasterImage.save(dir + "sample.BinarizeBradley5.png");
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Ajuste de brillo para la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightness | int | Valor de brillo. |


**Example: The following example performs brightness correction of a raster cached image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

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


**Example: The following example performs contrast correction of a raster cached image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Establece el valor de contraste. Los valores aceptados de contraste están en el rango [-100f, 100f].
    rasterImage.adjustContrast(50);
    rasterImage.save(dir + "sample.AdjustContrast.png");
} finally {
    image.dispose();
}
```

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


**Example: The following example performs gamma-correction of a raster cached image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

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


**Example: The following example performs gamma-correction of a raster cached image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterCachedImage rasterImage = (com.aspose.imaging.RasterCachedImage) image;

    // Establecer el coeficiente gamma para los canales rojo, verde y azul.
    rasterImage.adjustGamma(2.5f);
    rasterImage.save(dir + "sample.AdjustGamma.png");
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
