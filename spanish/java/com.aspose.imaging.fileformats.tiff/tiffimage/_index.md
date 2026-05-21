---
title: "TiffImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Procesa imágenes rasterizadas Tagged Image File Format (TIFF) con nuestra API, ofreciendo soporte integral para diversas resoluciones y capacidades avanzadas de edición como la manipulación de datos EXIF y canales alfa."
type: docs
weight: 13
url: /es/java/com.aspose.imaging.fileformats.tiff/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public class TiffImage extends RasterCachedMultipageImage implements IMultipageImageExt, IMetadataContainer
```

Procesa imágenes rasterizadas Tagged Image File Format (TIFF) con nuestra API, ofreciendo soporte integral para diversas resoluciones y capacidades avanzadas de edición como la manipulación de datos EXIF y canales alfa. Normaliza ángulos para imágenes escaneadas, redimensiona, transforma a escala de grises y aplica filtros, correcciones gamma y ajustes de parámetros de imagen con facilidad. Maneja sin problemas archivos TIFF multiframe, crea rutas gráficas, agrega formas y guarda imágenes en diferentes formatos sin esfuerzo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffImage(TiffFrame frame)](#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Inicializa un nuevo objeto de la clase [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage), especificando el parámetro de fotograma. |
| [TiffImage(TiffFrame[] frames)](#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame---) | Crea una nueva instancia de la clase [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage), proporcionando una lista de fotogramas como parámetro. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Obtén el valor del formato de archivo asociado a la imagen. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Indica si los componentes requieren pre-multiplicación, garantizando un manejo eficiente de los elementos visuales. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Indica si los componentes requieren pre-multiplicación, garantizando un manejo eficiente de los elementos visuales. |
| [getByteOrder()](#getByteOrder--) | Alterna el orden de bytes de los archivos TIFF sin problemas, asegurando un control preciso sobre la interpretación de datos. |
| [setByteOrder(int value)](#setByteOrder-int-) | Alterna el orden de bytes de los archivos TIFF sin problemas, asegurando un control preciso sobre la interpretación de datos. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Obtén la resolución horizontal del [Image](../../com.aspose.imaging/image) especificado en píxeles por pulgada, facilitando ajustes precisos y capacidades de renderizado. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Modifica la resolución horizontal del [Image](../../com.aspose.imaging/image) especificado en píxeles por pulgada, facilitando ajustes precisos y capacidades de renderizado. |
| [getVerticalResolution()](#getVerticalResolution--) | Accede a la resolución vertical del [Image](../../com.aspose.imaging/image) designado en píxeles por pulgada, permitiendo ajustes precisos y optimizaciones de renderizado. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Accede a la resolución vertical del [Image](../../com.aspose.imaging/image) designado en píxeles por pulgada, permitiendo ajustes precisos y optimizaciones de renderizado. |
| [getActiveFrame()](#getActiveFrame--) | Gestiona el fotograma activo sin problemas, facilitando la navegación dinámica y la manipulación dentro del contexto designado. |
| [setActiveFrame(TiffFrame value)](#setActiveFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Gestiona el fotograma activo sin problemas, facilitando la navegación dinámica y la manipulación dentro del contexto designado. |
| [getFrames()](#getFrames--) | Obtén una matriz de instancias de [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe), permitiendo un acceso y manipulación exhaustivos de los fotogramas individuales dentro de la imagen TIFF. |
| [getPageCount()](#getPageCount--) | Obtén el recuento total de páginas dentro del documento especificado, facilitando una navegación eficiente y la gestión de contenido multipágina. |
| [getPages()](#getPages--) | Accede a las páginas del documento sin problemas, permitiendo una navegación dinámica y manipulación dentro de la estructura de contenido. |
| [hasAlpha()](#hasAlpha--) | Determina si la imagen tiene un canal alfa, proporcionando información crucial para operaciones de renderizado y composición. |
| [removeMetadata()](#removeMetadata--) | Elimina los metadatos de esta instancia de imagen estableciendo este `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) valor a `null`. |
| [getOriginalOptions()](#getOriginalOptions--) | Obtén opciones derivadas de la configuración del archivo original, facilitando la preservación sin problemas de parámetros clave como la profundidad de bits y otros atributos esenciales de la imagen original. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Incorpora una nueva página en la imagen existente sin problemas, ampliando su contenido y versatilidad. |
| [alignResolutions()](#alignResolutions--) | Implementa el método auxiliar AlignResolutions para sincronizar las resoluciones horizontal y vertical, asegurando uniformidad en las dimensiones de la imagen. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Establece la resolución para el [RasterImage](../../com.aspose.imaging/rasterimage) especificado, permitiendo un control preciso sobre el renderizado y las propiedades de visualización de la imagen. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.imaging.Color-) | Utilice el método NormalizeAngle diseñado específicamente para documentos de texto escaneados para rectificar escaneos sesgados, garantizando una alineación precisa. |
| [addFrame(TiffFrame frame)](#addFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Incorpore el marco especificado sin problemas en la imagen, ampliando su contenido y versatilidad. |
| [add(TiffImage image)](#add-com.aspose.imaging.fileformats.tiff.TiffImage-) | Agregue los marcos de la imagen especificada sin problemas al marco actual, consolidando su contenido y mejorando la flexibilidad compositiva. |
| [addFrames(TiffFrame[] frames)](#addFrames-com.aspose.imaging.fileformats.tiff.TiffFrame---) | Integre la matriz de marcos sin problemas en la imagen, enriqueciendo su contenido y versatilidad. |
| [insertFrame(int index, TiffFrame frame)](#insertFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Inserte el nuevo marco en el índice especificado dentro de la secuencia de marcos, asegurando un control preciso sobre la disposición de los marcos. |
| [replaceFrame(int index, TiffFrame newFrame)](#replaceFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Sustituya el marco en la posición designada por otro marco sin problemas, facilitando la gestión dinámica de marcos dentro de la secuencia de imágenes. |
| [removeFrame(int index)](#removeFrame-int-) | Elimine sin esfuerzo el marco identificado por su índice de la secuencia de imágenes, simplificando la gestión de marcos dentro de su aplicación. |
| [removeFrame(TiffFrame frame)](#removeFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Elimine de manera eficiente el marco especificado de la secuencia de imágenes, facilitando una gestión simplificada de marcos dentro de su aplicación. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | Realice una operación de redimensionado proporcional en la imagen, preservando su relación de aspecto mientras ajusta sus dimensiones. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Ajuste el ancho de la imagen manteniendo su relación de aspecto, asegurando un redimensionado proporcional para una presentación visual óptima. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Realice un ajuste proporcional de la altura de la imagen, preservando su relación de aspecto para una integridad visual constante. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Realice rotación, volteo o una combinación de ambas operaciones exclusivamente en el marco activo. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Ejecute dithering en la imagen actual para mejorar su calidad visual y reducir artefactos de bandas de color. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recorte la imagen usando una región rectangular especificada, permitiendo una selección precisa del contenido deseado. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Realice recorte en la imagen especificando desplazamientos hacia la izquierda, derecha, arriba y abajo. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Aplique binarización a la imagen usando un umbral predefinido, convirtiéndola en una imagen binaria con regiones de primer plano y fondo distintas. |
| [binarizeOtsu()](#binarizeOtsu--) | Utilice el umbral de Otsu para realizar binarización en la imagen, determinando automáticamente el valor de umbral óptimo basado en el histograma de la imagen. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Implemente binarización en la imagen empleando el algoritmo de umbral adaptativo de Bradley con umbralado de imagen integral. |
| [grayscale()](#grayscale--) | Convierta la imagen a su representación en escala de grises, transformándola en una imagen de un solo canal donde cada píxel representa intensidad. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Aplique corrección gamma a la imagen, ajustando las intensidades de los píxeles para lograr el balance de color deseado. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Realice corrección gamma en la imagen usando coeficientes individuales para los canales rojo, verde y azul, permitiendo ajustes finos del balance de color y contraste. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Implemente el ajuste de `brightness` para la imagen, permitiendo la modificación de los niveles de luminancia generales. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Mejore el contraste de la instancia [Image](../../com.aspose.imaging/image), amplificando las diferencias entre sus áreas claras y oscuras. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Filtre el contenido dentro del rectángulo especificado, aplicando un filtro de procesamiento de imagen designado para mejorar o modificar la región seleccionada. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ajuste el tamaño de la imagen según la configuración especificada, permitiendo un control preciso sobre dimensiones, relación de aspecto y comportamiento de escalado. |

## Example: Create Graphics Path from Path Resources in TIFF image.

``` java
try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
{
    // Crear el GraphicsPath usando PathResources de una imagen TIFF
    GraphicsPath graphicsPath = PathResourceConverter.toGraphicsPath(
            image.getActiveFrame().getPathResources().toArray(new PathResource[0]), 
            image.getActiveFrame().getSize());
    Graphics graphics = new Graphics(image);

    // Dibujar una línea roja y guardar la imagen
    graphics.drawPath(new Pen(Color.getRed(), 10), graphicsPath);
    image.save("BottleWithRedBorder.tif");
}
```


## Example: Create Path Resources using Graphics Path.

``` java
static void main()
{
    try (TiffImage image = (TiffImage)Image.load("Bottle.tif"))
    {
        // Crear una Figure rectangular para GraphicsPath
        Figure figure = new Figure();
        figure.addShape(createBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Crear GraphicsPath usando nuestra Figure
        GraphicsPath graphicsPath = new GraphicsPath();
        graphicsPath.addFigure(figure);

        // Establecer PathResources usando GraphicsPath
        PathResource[] pathResource = PathResourceConverter.fromGraphicsPath(graphicsPath, image.getSize());
        image.getActiveFrame().setPathResources(Arrays.asList(pathResource));

        // Guardar la imagen
        image.save("BottleWithRectanglePath.tif");
    }
}

private static BezierShape createBezierShape(float ... coordinates)
{
    PointF[] bezierPoints = coordinatesToBezierPoints(coordinates);
    return new BezierShape(bezierPoints, true);
}

private static PointF[] coordinatesToBezierPoints(float[] coordinates)
{
    PointF[] bezierPoints = new PointF[3 * coordinates.length / 2];
    int i = 0;
    for (int coordinateIndex = 0; coordinateIndex < coordinates.length - 1; coordinateIndex += 2)
        for (int index = 0; index < 3; index++)
        {
            bezierPoints[i++] = new PointF(coordinates[coordinateIndex], coordinates[coordinateIndex + 1]);
        }
                
    return bezierPoints;
}
```

### TiffImage(TiffFrame frame) {#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public TiffImage(TiffFrame frame)
```


Inicializar un nuevo objeto de la clase [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage), especificando el parámetro frame. Este constructor facilita la creación de una instancia de TiffImage, permitiendo a los desarrolladores especificar el frame que se cargará o procesará, optimizando las tareas de manejo de imágenes Tiff dentro de sus aplicaciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | El frame tiff con el que inicializar la imagen. |

### TiffImage(TiffFrame[] frames) {#TiffImage-com.aspose.imaging.fileformats.tiff.TiffFrame---}
```
public TiffImage(TiffFrame[] frames)
```


Crear una nueva instancia de la clase [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage), proporcionando una lista de frames como parámetro. Este constructor permite la inicialización de un objeto TiffImage con múltiples frames, facilitando el manejo y procesamiento eficiente de secuencias de imágenes TIFF dentro de aplicaciones de software.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| frames | [TiffFrame\[\]](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Los frames. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Obtener el valor del formato de archivo asociado a la imagen. Esta propiedad sirve como un aspecto crítico de la recuperación de metadatos de la imagen, permitiendo a las aplicaciones de software identificar e interpretar el formato de los datos de la imagen de manera eficiente.

**Returns:**
long - un valor del formato de archivo
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Indicar si los componentes requieren premultiplicación, asegurando un manejo eficiente de los elementos visuales. Mejore los procesos de renderizado activando o desactivando esta propiedad, optimizando los flujos de trabajo gráfico para un rendimiento mejorado.

**Returns:**
boolean - `true` si los componentes deben estar premultiplicados; de lo contrario, `false`.
### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Indicar si los componentes requieren premultiplicación, asegurando un manejo eficiente de los elementos visuales. Mejore los procesos de renderizado activando o desactivando esta propiedad, optimizando los flujos de trabajo gráfico para un rendimiento mejorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | `true` si los componentes deben estar premultiplicados; de lo contrario, `false`. |


**Example: The following example creates a new TIFF image, saves the specified semi-transparent pixels, then loads those pixels and gets final colors in the premultiplied form.**

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

com.aspose.imaging.imageoptions.TiffOptions createOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.TiffDeflateRgba);
createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0]), true));

com.aspose.imaging.fileformats.tiff.TiffImage image =
        (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createOptions, imageWidth, imageHeight);
try {
    // Guardar píxeles para toda la imagen.
    image.savePixels(image.getBounds(), colors);

    // Los píxeles se almacenan en la imagen original en forma no premultiplicada.
    // Es necesario especificar la opción correspondiente explícitamente para obtener componentes de color premultiplicados.
    // Los componentes de color premultiplicados se calculan mediante las fórmulas:
    // rojo = original_rojo * alfa / 255;
    // verde = original_verde * alfa / 255;
    // azul = original_azul * alfa / 255;
    image.setPremultiplyComponents(true);
    com.aspose.imaging.Color[] premultipliedColors = image.loadPixels(image.getBounds());

    for (int i = 0; i < colors.length; i++) {
        System.out.println("Original color: " + colors[i].toString());
        System.out.println("Premultiplied color: " + premultipliedColors[i].toString());
    }
} finally {
    image.dispose();
}

//La salida se verá así:
//Color original: Color [A=127, R=255, G=0, B=0]
//Color premultiplicado: Color [A=127, R=127, G=0, B=0]
//Color original: Color [A=127, R=0, G=255, B=0]
//Color premultiplicado: Color [A=127, R=0, G=127, B=0]
//Color original: Color [A=127, R=0, G=0, B=255]
//Color premultiplicado: Color [A=127, R=0, G=0, B=127]
//Color original: Color [A=127, R=255, G=255, B=0]
//Color premultiplicado: Color [A=127, R=127, G=127, B=0]
//Color original: Color [A=127, R=255, G=0, B=255]
//Color premultiplicado: Color [A=127, R=127, G=0, B=127]
//Color original: Color [A=127, R=0, G=255, B=255]
//Color premultiplicado: Color [A=127, R=0, G=127, B=127]
```

### getByteOrder() {#getByteOrder--}
```
public final int getByteOrder()
```


Cambie el orden de bytes de los archivos TIFF sin problemas, garantizando un control preciso sobre la interpretación de datos. Potencie sus aplicaciones con la flexibilidad para adaptarse a diversas especificaciones de archivos, mejorando la compatibilidad y la eficiencia en el procesamiento de datos.

**Returns:**
int - El orden de bytes del TIFF.
### setByteOrder(int value) {#setByteOrder-int-}
```
public final void setByteOrder(int value)
```


Cambie el orden de bytes de los archivos TIFF sin problemas, garantizando un control preciso sobre la interpretación de datos. Potencie sus aplicaciones con la flexibilidad para adaptarse a diversas especificaciones de archivos, mejorando la compatibilidad y la eficiencia en el procesamiento de datos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El orden de bytes del TIFF. |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Recupere la resolución horizontal de la [Image](../../com.aspose.imaging/image) especificada en píxeles por pulgada, facilitando ajustes precisos y capacidades de renderizado. Acceda sin esfuerzo a los metadatos esenciales de la imagen, impulsando flujos de trabajo de procesamiento de imágenes simplificados para mejorar la experiencia del usuario.

**Returns:**
double - La resolución horizontal.

Nota: por defecto este valor siempre es 96 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada.

**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Obtenga la resolución horizontal y vertical del TiffImage.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilice el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// La salida puede verse así:
// La resolución horizontal, en píxeles por pulgada: 96.0
// La resolución vertical, en píxeles por pulgada: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Modifica la resolución horizontal de la [Image](../../com.aspose.imaging/image) especificada en píxeles por pulgada, facilitando ajustes precisos y capacidades de renderizado. Acceda sin esfuerzo a los metadatos esenciales de la imagen, impulsando flujos de trabajo de procesamiento de imágenes simplificados para mejorar la experiencia del usuario.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | La resolución horizontal. |

Nota: por defecto este valor siempre es 96 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Acceda a la resolución vertical de la [Image](../../com.aspose.imaging/image) designada en píxeles por pulgada, permitiendo ajustes precisos y optimizaciones de renderizado. Utilice sin esfuerzo los datos esenciales de la imagen para simplificar los flujos de trabajo de procesamiento de imágenes, garantizando una calidad y rendimiento superiores en sus aplicaciones.

**Returns:**
double - La resolución vertical.

Nota: por defecto este valor siempre es 96 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada.

**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Obtenga la resolución horizontal y vertical del TiffImage.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilice el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// La salida puede verse así:
// La resolución horizontal, en píxeles por pulgada: 96.0
// La resolución vertical, en píxeles por pulgada: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Acceda a la resolución vertical de la [Image](../../com.aspose.imaging/image) designada en píxeles por pulgada, permitiendo ajustes precisos y optimizaciones de renderizado. Utilice sin esfuerzo los datos esenciales de la imagen para simplificar los flujos de trabajo de procesamiento de imágenes, garantizando una calidad y rendimiento superiores en sus aplicaciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | La resolución vertical. |

Nota: por defecto este valor siempre es 96 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada. |

### getActiveFrame() {#getActiveFrame--}
```
public final TiffFrame getActiveFrame()
```


Gestione el marco activo sin problemas, facilitando la navegación y manipulación dinámicas dentro del contexto designado. Potencie su aplicación para interactuar eficientemente con contenido multimedia, mejorando la participación y productividad del usuario.

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - Active frame.

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Esto es Font y Brush para dibujar texto en fotogramas individuales.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Crear 5 fotogramas
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Crear una imagen PNG y dibujar el número de página en ella.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Crear un fotograma basado en la imagen PNG.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Agregar el fotograma a la imagen TIFF.
        tiffImage.addFrame(frame);
    }

    // La imagen fue creada con un solo fotograma predeterminado. Vamos a eliminarlo.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // No olvides descartar el fotograma si no lo vas a agregar a otro TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### setActiveFrame(TiffFrame value) {#setActiveFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void setActiveFrame(TiffFrame value)
```


Gestione el marco activo sin problemas, facilitando la navegación y manipulación dinámicas dentro del contexto designado. Potencie su aplicación para interactuar eficientemente con contenido multimedia, mejorando la participación y productividad del usuario.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Marco activo. |


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Esto es Font y Brush para dibujar texto en fotogramas individuales.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Crear 5 fotogramas
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Crear una imagen PNG y dibujar el número de página en ella.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Crear un fotograma basado en la imagen PNG.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Agregar el fotograma a la imagen TIFF.
        tiffImage.addFrame(frame);
    }

    // La imagen fue creada con un solo fotograma predeterminado. Vamos a eliminarlo.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // No olvides descartar el fotograma si no lo vas a agregar a otro TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getFrames() {#getFrames--}
```
public final TiffFrame[] getFrames()
```


Recupere una matriz de instancias de [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe), que permite un acceso y manipulación completos de los fotogramas individuales dentro de la imagen TIFF. Aproveche el poder de esta matriz para simplificar los flujos de trabajo de procesamiento de imágenes, garantizando un control preciso y la optimización del contenido visual.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffFrame[] - la matriz de [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe).

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Esto es Font y Brush para dibujar texto en fotogramas individuales.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Crear 5 fotogramas
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Crear una imagen PNG y dibujar el número de página en ella.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Crear un fotograma basado en la imagen PNG.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Agregar el fotograma a la imagen TIFF.
        tiffImage.addFrame(frame);
    }

    // La imagen fue creada con un solo fotograma predeterminado. Vamos a eliminarlo.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // No olvides descartar el fotograma si no lo vas a agregar a otro TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Recupere el recuento total de páginas dentro del documento especificado, facilitando una navegación y gestión eficientes del contenido multipágina. Incorpore esta funcionalidad para mejorar la experiencia del usuario, permitiendo un acceso sin interrupciones a estructuras de documentos integrales.

**Returns:**
int - el recuento de páginas.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Acceda a las páginas del documento sin problemas, permitiendo una navegación y manipulación dinámicas dentro de la estructura de contenido. Potencie su aplicación con un acceso eficiente a páginas individuales, facilitando un procesamiento de documentos simplificado y una interacción mejorada del usuario.

**Returns:**
com.aspose.imaging.Image[] - las páginas.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Determine si la imagen tiene un canal alfa, proporcionando información crucial para operaciones de renderizado y composición. Integre esta función para optimizar los flujos de trabajo de procesamiento visual, garantizando una representación y manipulación precisas de los elementos transparentes.

**Returns:**
boolean - `true` si hay un canal alfa.

**Example: The following example loads a TIFF image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";

String fileName = dir + "sample.tif";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Si el fotograma TIFF activo tiene canal alfa, entonces se considera que toda la imagen TIFF tiene canal alfa.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, tiffImage.getRawDataFormat(), tiffImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.tiff.TiffFrame frame : tiffImage.getFrames()) {
        System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", ++i, frame.getRawDataFormat(), frame.hasAlpha());
    }
} finally {
    image.dispose();
}

// La salida puede verse así:
// ImageFile=c:\temp\sample.tif, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=1, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=2, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
```

### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Elimina los metadatos de esta instancia de imagen estableciendo este `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) valor a `null`.

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Recupere las opciones derivadas de la configuración del archivo original, facilitando la preservación sin problemas de parámetros clave como la profundidad de bits y otros atributos esenciales de la imagen original. Utilice este método para mantener la fidelidad y consistencia en tareas de procesamiento de imágenes, asegurando resultados óptimos sin alteraciones innecesarias. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el método [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), se producirá una imagen PNG de salida con 8 bits por píxel. Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas al método [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) como segundo parámetro.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Incorpore una nueva página en la imagen existente de forma fluida, ampliando su contenido y versatilidad. Utilice este método para mejorar la composición y gestión de documentos, facilitando el manejo eficiente de imágenes multipágina dentro de su aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | La página a agregar. |

### alignResolutions() {#alignResolutions--}
```
public final void alignResolutions()
```


Implemente el método auxiliar AlignResolutions para sincronizar las resoluciones horizontal y vertical, garantizando la uniformidad en las dimensiones de la imagen. Esta funcionalidad facilita flujos de trabajo de procesamiento de imágenes simplificados al armonizar los parámetros de resolución, optimizando la calidad visual y la consistencia en diversas plataformas y dispositivos.

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Establece la resolución para el [RasterImage](../../com.aspose.imaging/rasterimage) especificado, permitiendo un control preciso sobre la renderización y las propiedades de visualización de la imagen. Integre esta funcionalidad para optimizar la salida visual y garantizar la compatibilidad con diversos dispositivos y plataformas de salida, mejorando la experiencia general del usuario.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dpiX | double | La resolución horizontal, en puntos por pulgada, del [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | La resolución vertical, en puntos por pulgada, del [RasterImage](../../com.aspose.imaging/rasterimage). |


**Example: The following example shows how to set horizontal/vertical resolution of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Obtenga la resolución horizontal y vertical del TiffImage.
    double horizontalResolution = tiffImage.getHorizontalResolution();
    double verticalResolution = tiffImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilice el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
        System.out.println("Set resolution values to 96 dpi");
        tiffImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + tiffImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + tiffImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// La salida puede verse así:
// La resolución horizontal, en píxeles por pulgada: 96.0
// La resolución vertical, en píxeles por pulgada: 96.0
```

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.imaging.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Utilice el método NormalizeAngle, diseñado específicamente para documentos de texto escaneados, para corregir escaneos sesgados, garantizando una alineación precisa. Integre de forma fluida esta funcionalidad en sus flujos de procesamiento de texto para mejorar la legibilidad y calidad de los documentos, aumentando la eficiencia general en tareas de reconocimiento y análisis de texto. Este método utiliza los métodos [RasterImage.getSkewAngle](../../com.aspose.imaging/rasterimage\#getSkewAngle) y [RasterImage.rotate(float, boolean, Color)](../../com.aspose.imaging/rasterimage\#rotate-float--boolean--Color-).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resizeProportionally | boolean | Si se establece en `true` el tamaño de su imagen cambiará según las proyecciones del rectángulo rotado (puntos de esquina); en otro caso, las dimensiones permanecerán sin tocar y solo se rotará el contenido interno de la imagen. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Color del fondo. |

### addFrame(TiffFrame frame) {#addFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void addFrame(TiffFrame frame)
```


Incorpore el fotograma especificado de forma fluida en la imagen, ampliando su contenido y versatilidad. Utilice este método para mejorar la composición y gestión de imágenes, facilitando el manejo eficiente de imágenes multi‑fotograma dentro de su aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | El fotograma a agregar. |


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Esto es Font y Brush para dibujar texto en fotogramas individuales.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Crear 5 fotogramas
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Crear una imagen PNG y dibujar el número de página en ella.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Crear un fotograma basado en la imagen PNG.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Agregar el fotograma a la imagen TIFF.
        tiffImage.addFrame(frame);
    }

    // La imagen fue creada con un solo fotograma predeterminado. Vamos a eliminarlo.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // No olvides descartar el fotograma si no lo vas a agregar a otro TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### add(TiffImage image) {#add-com.aspose.imaging.fileformats.tiff.TiffImage-}
```
public final void add(TiffImage image)
```


Agregue los fotogramas de la imagen especificada de forma fluida al fotograma actual, consolidando su contenido y mejorando la flexibilidad compositiva. Integre este método para simplificar la gestión y manipulación de fotogramas dentro de su aplicación, facilitando el manejo eficiente de imágenes multi‑fotograma.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [TiffImage](../../com.aspose.imaging.fileformats.tiff/tiffimage) | La imagen fuente. |

### addFrames(TiffFrame[] frames) {#addFrames-com.aspose.imaging.fileformats.tiff.TiffFrame---}
```
public final void addFrames(TiffFrame[] frames)
```


Integre la matriz de fotogramas de forma fluida en la imagen, enriqueciendo su contenido y versatilidad. Utilice este método para mejorar la composición y gestión de imágenes, permitiendo el manejo eficiente de imágenes multi‑fotograma dentro de su aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| frames | [TiffFrame\[\]](../../com.aspose.imaging.fileformats.tiff/tiffframe) | La matriz de fotogramas a agregar |

### insertFrame(int index, TiffFrame frame) {#insertFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void insertFrame(int index, TiffFrame frame)
```


Inserte el nuevo fotograma en el índice especificado dentro de la secuencia de fotogramas, garantizando un control preciso sobre la disposición de los fotogramas. Utilice este método para gestionar secuencias de fotogramas de manera eficaz, facilitando la manipulación dinámica y la organización del contenido de la imagen dentro de su aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice de `frame`. |
| frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | El fotograma para inserción. |

### replaceFrame(int index, TiffFrame newFrame) {#replaceFrame-int-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final TiffFrame replaceFrame(int index, TiffFrame newFrame)
```


Sustituya el fotograma en la posición designada por otro fotograma de forma fluida, facilitando la gestión dinámica de fotogramas dentro de la secuencia de imágenes. Integre este método para mejorar la flexibilidad y precisión en la manipulación de fotogramas, garantizando una organización y presentación óptimas del contenido de la imagen dentro de su aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | La posición del fotograma basada en cero. |
|  | newFrame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | El fotograma a reemplazar. |

Nota: no olvide disponer/cerrar el fotograma si no lo va a agregar a otro TiffImage. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The removed frame.
### removeFrame(int index) {#removeFrame-int-}
```
public final TiffFrame removeFrame(int index)
```


Elimine sin esfuerzo el fotograma identificado por su índice de la secuencia de imágenes, simplificando la gestión de fotogramas dentro de su aplicación. Integre esta funcionalidad para mejorar la eficiencia y precisión en la manipulación de fotogramas, facilitando una organización y presentación fluida del contenido de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | index | int | Índice del fotograma a eliminar. |

--------------------

Nota: no olvide disponer el fotograma si no lo va a agregar a otro TiffImage. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The removed frame.

**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Esto es Font y Brush para dibujar texto en fotogramas individuales.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Crear 5 fotogramas
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Crear una imagen PNG y dibujar el número de página en ella.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Crear un fotograma basado en la imagen PNG.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Agregar el fotograma a la imagen TIFF.
        tiffImage.addFrame(frame);
    }

    // La imagen fue creada con un solo fotograma predeterminado. Vamos a eliminarlo.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // No olvides descartar el fotograma si no lo vas a agregar a otro TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### removeFrame(TiffFrame frame) {#removeFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public final void removeFrame(TiffFrame frame)
```


Elimine de manera eficiente el fotograma especificado de la secuencia de imágenes, facilitando una gestión simplificada de fotogramas dentro de su aplicación. Integre esta funcionalidad para mejorar la precisión y flexibilidad en la manipulación de fotogramas, garantizando una organización y presentación fluida del contenido de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | frame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | El fotograma a eliminar. |

--------------------

Nota: no olvide disponer el fotograma si no lo va a agregar a otro TiffImage. |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public final void resizeProportional(int newWidth, int newHeight, int resizeType)
```


Realice una operación de redimensionado proporcional en la imagen, preservando su relación de aspecto mientras ajusta sus dimensiones. Utilice este método para escalar dinámicamente imágenes dentro de su aplicación, asegurando una representación visual coherente de la integridad del contenido. El redimensionado proporcional cambiará el tamaño de cada fotograma según la proporción de `newWidth`/width y `newHeight`/height.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| resizeType | int | El tipo de redimensionado. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Ajusta el ancho de la imagen manteniendo su relación de aspecto, garantizando un redimensionado proporcional para una presentación visual óptima. Utiliza este método para escalar dinámicamente las imágenes dentro de tu aplicación, facilitando una renderización coherente y estéticamente agradable en varios contextos de visualización.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| resizeType | int | Tipo de redimensionado. |


**Example: This example loads a TIFF image and resizes it proportionally using various resizing methods.**
Este ejemplo carga una imagen TIFF y la redimensiona proporcionalmente usando varios métodos de redimensionado. Sólo se especifica el ancho, la altura se calcula automáticamente.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Escalar 2 veces usando remuestreo de vecino más cercano.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Reducir 2 veces usando remuestreo de vecino más cercano.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Escalar 2 veces usando remuestreo bilineal.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Reducir 2 veces usando remuestreo bilineal.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Realiza un ajuste proporcional de la altura de la imagen, preservando su relación de aspecto para una integridad visual consistente. Emplea este método para redimensionar dinámicamente las imágenes dentro de tu aplicación, garantizando una visualización óptima en diversas plataformas y dispositivos sin comprometer la calidad del contenido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newHeight | int | El nuevo alto. |
| resizeType | int | Tipo de redimensionado. |


**Example: This example loads a TIFF image and resizes it proportionally using various resizing methods.**
Este ejemplo carga una imagen TIFF y la redimensiona proporcionalmente usando varios métodos de redimensionado. Sólo se especifica la altura, el ancho se calcula automáticamente.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Escalar 2 veces usando remuestreo de vecino más cercano.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Reducir 2 veces usando remuestreo de vecino más cercano.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Escalar 2 veces usando remuestreo bilineal.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    // Reducir 2 veces usando remuestreo bilineal.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Guardar como PNG con las opciones predeterminadas.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Realiza rotación, volteo o una combinación de ambas operaciones exclusivamente en el fotograma activo. Este método permite una manipulación precisa de fotogramas individuales dentro de la secuencia de imágenes, mejorando la flexibilidad en la edición y composición de imágenes dentro de tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotateFlipType | int | El tipo de rotación y volteo. |


**Example: This example loads a TIFF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

// Esta es una clase auxiliar.
class Utils {
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
Utils utils = new Utils();

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Rotar, voltear y guardar en el archivo de salida.
    com.aspose.imaging.fileformats.tiff.TiffImage image = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.load(dir + "sample.tif");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + utils.rotateFlipTypeToString(rotateFlipType) + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Ejecuta dithering en la imagen actual para mejorar su calidad visual y reducir los artefactos de bandas de color. Integra este método en tu flujo de procesamiento de imágenes para garantizar transiciones más suaves entre colores, lo que resulta en una apariencia y claridad general de la imagen mejoradas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ditheringMethod | int | El método de tramado. |
| bitsCount | int | El recuento final de bits para el tramado. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta personalizada para el tramado. |


**Example: The following example loads a TIFF image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Realizar dithering por umbral usando una paleta de colores de 4 bits que contiene 16 colores.
    // Cuantos más bits se especifiquen, mayor será la calidad y mayor el tamaño de la imagen de salida.
    // Tenga en cuenta que solo se admiten paletas de 1 bit, 4 bits y 8 bits en este momento.
    tiffImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    tiffImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Realizar dithering Floyd usando una paleta de colores de 1 bit que contiene solo 2 colores: negro y blanco.
    // Cuantos más bits se especifiquen, mayor será la calidad y mayor el tamaño de la imagen de salida.
    // Tenga en cuenta que solo se admiten paletas de 1 bit, 4 bits y 8 bits en este momento.
    tiffImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    tiffImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Recorta la imagen usando una región rectangular especificada, permitiendo una selección precisa del contenido deseado. Integra este método en tu flujo de procesamiento de imágenes para eliminar eficientemente áreas no deseadas y enfocarte en los detalles esenciales, mejorando la claridad y composición general de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo. |


**Example: The following example crops a TIFF image.**
El siguiente ejemplo recorta una imagen TIFF. El área de recorte se especifica mediante **Aspose.Imaging.Rectangle**.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Recorte la imagen. El área de recorte es la zona rectangular central de la imagen.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            tiffImage.getWidth() / 4, tiffImage.getHeight() / 4, tiffImage.getWidth() / 2, tiffImage.getHeight() / 2);
    tiffImage.crop(area);

    // Guarde la imagen recortada en PNG
    tiffImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Realiza recorte en la imagen especificando desplazamientos hacia la izquierda, derecha, arriba y abajo. Este método permite una selección precisa de la porción deseada de la imagen, facilitando la eliminación eficiente de áreas no deseadas y enfocándose en el contenido esencial. Integra esta funcionalidad en tu canal de procesamiento de imágenes para mejorar la claridad y composición según sea necesario dentro de tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| leftShift | int | El desplazamiento izquierdo. |
| rightShift | int | El desplazamiento derecho. |
| topShift | int | El desplazamiento superior. |
| bottomShift | int | El desplazamiento inferior. |


**Example: The following example crops a TIFF image.**
El siguiente ejemplo recorta una imagen TIFF. El área de recorte se especifica mediante los márgenes Izquierda, Arriba, Derecha, Abajo.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Recorte nuevamente. Establezca un margen del 10 % del tamaño de la imagen.
    int horizontalMargin = tiffImage.getWidth() / 10;
    int verticalMargin = tiffImage.getHeight() / 10;
    tiffImage.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Guarde la imagen recortada en PNG.
    tiffImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Aplica binarización a la imagen usando un umbral predefinido, convirtiéndola en una imagen binaria con regiones de primer plano y fondo distintas. Incorpora este método en tu flujo de procesamiento de imágenes para facilitar tareas de segmentación y extracción de características, mejorando la precisión y eficiencia del análisis de imágenes dentro de tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threshold | byte | Valor del umbral. Si el valor gris correspondiente de un píxel es mayor que el umbral, se le asignará un valor de 255; de lo contrario, 0. |


**Example: The following example binarizes a TIFF image with the predefined threshold.**
El siguiente ejemplo binariza una imagen TIFF con el umbral predefinido. Las imágenes binarizadas contienen solo 2 colores: negro y blanco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Binariza la imagen con un valor de umbral de 127.
    // Si el valor gris correspondiente de un píxel es mayor que 127, se le asignará un valor de 255, 0 en caso contrario.
    tiffImage.binarizeFixed((byte) 127);
    tiffImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Utiliza el umbral de Otsu para realizar binarización en la imagen, determinando automáticamente el valor de umbral óptimo basado en el histograma de la imagen. Integra este método en tu flujo de procesamiento de imágenes para lograr una segmentación y extracción de características efectivas, mejorando la precisión y fiabilidad de las tareas de análisis de imágenes dentro de tu aplicación.


**Example: The following example binarizes a TIFF image with Otsu thresholding.**
El siguiente ejemplo binariza una imagen TIFF con umbral de Otsu. Las imágenes binarizadas contienen solo 2 colores: negro y blanco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Binariza la imagen con umbralización de Otsu.
    tiffImage.binarizeOtsu();
    tiffImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Implementa binarización en la imagen empleando el algoritmo de umbral adaptativo de Bradley con umbralado de imagen integral. Este enfoque calcula dinámicamente umbrales locales basados en el vecindario de la imagen, mejorando la adaptabilidad a condiciones de iluminación variables y garantizando una segmentación robusta para tareas de procesamiento posteriores dentro de tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightnessDifference | double | La diferencia de brillo entre el píxel y el promedio de una ventana de s x s píxeles centrada en este píxel. |
| windowSize | int | El tamaño de la ventana de s x s píxeles centrada en este píxel |


**Example: The following example binarizes a TIFF image with Bradley's adaptive thresholding algorithm with the specified window size.**
El siguiente ejemplo binariza una imagen TIFF con el algoritmo de umbral adaptativo de Bradley con el tamaño de ventana especificado. Las imágenes binarizadas contienen solo 2 colores: negro y blanco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Binariza la imagen con una diferencia de brillo de 5. El brillo es la diferencia entre un píxel y el promedio de una ventana de 10 x 10 píxeles centrada en ese píxel.
    tiffImage.binarizeBradley(5, 10);
    tiffImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Convierte la imagen a su representación en escala de grises, transformándola en una imagen de un solo canal donde cada píxel representa intensidad. Integra este método en tu canal de procesamiento de imágenes para simplificar el análisis y mejorar la compatibilidad con algoritmos basados en escala de grises, facilitando diversas tareas de visión por computadora y análisis de imágenes dentro de tu aplicación.


**Example: The following example transforms a colored TIFF image to its grayscale representation.**
El siguiente ejemplo transforma una imagen TIFF a color a su representación en escala de grises. Las imágenes en escala de grises están compuestas exclusivamente por tonos de gris y solo contienen información de intensidad.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    tiffImage.grayscale();
    tiffImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Aplica corrección gamma a la imagen, ajustando las intensidades de los píxeles para lograr el equilibrio de color deseado. Incorpora este método en tu flujo de procesamiento de imágenes para mejorar la calidad visual y aumentar la precisión de análisis o tareas de visualización posteriores dentro de tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gamma | float | Coeficiente gamma para los canales rojo, verde y azul |


**Example: The following example performs gamma-correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Establecer el coeficiente gamma para los canales rojo, verde y azul.
    tiffImage.adjustGamma(2.5f);
    tiffImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Realiza corrección gamma en la imagen usando coeficientes individuales para los canales rojo, verde y azul, permitiendo ajustes finos del equilibrio de color y contraste. Integra este método en tu canal de procesamiento de imágenes para lograr un control preciso sobre la representación del color y mejorar la fidelidad visual dentro de tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gammaRed | float | Gamma para el coeficiente del canal rojo |
| gammaGreen | float | Gamma para el coeficiente del canal verde |
| gammaBlue | float | Coeficiente gamma para el canal azul |


**Example: The following example performs gamma-correction of a TIFF image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Establecer coeficientes gamma individuales para los canales rojo, verde y azul.
    tiffImage.adjustGamma(1.5f, 2.5f, 3.5f);
    tiffImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Implementa el ajuste de `brightness` para la imagen, permitiendo la modificación de los niveles de luminancia generales. Incorpora este método en tu flujo de procesamiento de imágenes para mejorar la visibilidad y la calidad visual de las imágenes dentro de tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightness | int | Valor de brillo. |


**Example: The following example performs brightness correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Establece el valor de brillo. Los valores aceptados de brillo están en el rango [-255, 255].
    tiffImage.adjustBrightness(50);
    tiffImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Mejora el contraste de la [Imagen](../../com.aspose.imaging/image) instancia, amplificando las diferencias entre sus áreas claras y oscuras. Integra esta funcionalidad para mejorar la claridad visual y la calidad general de la imagen dentro de tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contrast | float | Valor de contraste (en el rango [-100; 100]) |


**Example: The following example performs contrast correction of a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Establece el valor de contraste. Los valores aceptados de contraste están en el rango [-100f, 100f].
    tiffImage.adjustContrast(50f);
    tiffImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Filtra el contenido dentro del rectángulo especificado, aplicando un filtro de procesamiento de imágenes designado para mejorar o modificar la región seleccionada. Integra este método en tu flujo de manipulación de imágenes para lograr mejoras o transformaciones específicas dentro de tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Las opciones. |


**Example: The following example applies various types of filters to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Aplica un filtro mediano con un tamaño de rectángulo de 5 a toda la imagen.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    tiffImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Aplica un filtro de suavizado bilateral con un tamaño de kernel de 5 a toda la imagen.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    tiffImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Aplica un filtro de desenfoque gaussiano con un radio de 5 y un valor sigma de 4.0 a toda la imagen.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Aplica un filtro Gauss-Wiener con un radio de 5 y un valor de suavizado de 4.0 a toda la imagen.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Aplica un filtro wiener de movimiento con una longitud de 5, un valor de suavizado de 4.0 y un ángulo de 90.0 grados a toda la imagen.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    tiffImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Aplica un filtro de nitidez con un tamaño de kernel de 5 y un valor sigma de 4.0 a toda la imagen.
    tiffImage.filter(tiffImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    tiffImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ajusta el tamaño de la imagen según los ajustes especificados, permitiendo un control preciso sobre las dimensiones, la relación de aspecto y el comportamiento de escalado. Integra este método en tu flujo de procesamiento de imágenes para lograr operaciones de redimensionado personalizadas adaptadas a los requisitos específicos de tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | La configuración de redimensionado. |


**Example: This example loads a TIFF image and resizes it using various resizing settings.**

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

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Reducir a la mitad usando remuestreo adaptativo.
    tiffImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Guardar como PNG
    tiffImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

