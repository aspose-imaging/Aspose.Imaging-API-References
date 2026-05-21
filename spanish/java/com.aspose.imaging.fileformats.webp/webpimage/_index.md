---
title: "WebPImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Manipule imágenes rasterizadas WebP con nuestra API usando sus funciones modernas tanto para compresión sin pérdida como con pérdida, garantizando una calidad de imagen óptima con tamaños de archivo reducidos."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.fileformats.webp/webpimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public final class WebPImage extends RasterCachedMultipageImage implements IMultipageImageExt, IMetadataContainer
```

Manipule imágenes rasterizadas WebP con nuestra API, usando sus funciones modernas tanto para compresión sin pérdida como con pérdida, garantizando una calidad de imagen óptima con tamaños de archivo reducidos. Maneje sin problemas formatos de archivo extendidos, animaciones y canales alfa, mientras actualiza fácilmente las dimensiones, redimensiona proporcionalmente, recorta, rota, aplica filtros, ajusta parámetros de imagen y convierte a otros formatos de imagen para una optimización versátil de imágenes web.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WebPImage(InputStream stream)](#WebPImage-java.io.InputStream-) | Cree una nueva instancia de la clase [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) inicializada a partir de una fuente de flujo proporcionada. |
| [WebPImage(InputStream stream, LoadOptions loadOptions)](#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Cree una nueva instancia de la clase [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) usando un flujo y opciones de carga especificadas, facilitando un manejo versátil de los datos de imagen WebP. |
| [WebPImage(String path)](#WebPImage-java.lang.String-) | Instancie una nueva instancia de la clase [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), inicializada a partir de una fuente de archivo proporcionada. |
| [WebPImage(String path, LoadOptions loadOptions)](#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-) | Cree una nueva instancia de la clase [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) usando un archivo y opciones de carga especificadas, facilitando un manejo flexible de los datos de imagen WebP. |
| [WebPImage(RasterImage rasterImage)](#WebPImage-com.aspose.imaging.RasterImage-) | Instancie una nueva instancia de la clase [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), inicializada a partir de un objeto rasterImage proporcionado. |
| [WebPImage(RasterImage rasterImage, LoadOptions loadOptions)](#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-) | Cree una nueva instancia de la clase [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) usando un objeto rasterImage y opciones de carga especificadas, permitiendo un manejo flexible de los datos de imagen. |
| [WebPImage(int width, int height, WebPOptions options)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-) | Instancie una nueva instancia de la clase [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) con una imagen vacía de dimensiones de ancho y alto especificadas. |
| [WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-com.aspose.imaging.LoadOptions-) | Cree una nueva instancia de la clase [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) con una imagen vacía y opciones de carga especificadas. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getOptions()](#getOptions--) | Recupere o modifique las opciones asociadas a la propiedad especificada, permitiendo una personalización afinada del comportamiento y la configuración. |
| [getPages()](#getPages--) | Acceda a los bloques WebP dentro de la imagen, permitiendo un examen detallado o la manipulación de la estructura subyacente de bloques. |
| [getPageCount()](#getPageCount--) | Obtén el recuento total de páginas dentro del documento especificado, facilitando una navegación eficiente y la gestión de contenido multipágina. |
| [getFileFormat()](#getFileFormat--) | Acceda al valor del formato de archivo asociado a la imagen, proporcionando información sobre el formato en el que la imagen está almacenada. |
| [hasAlpha()](#hasAlpha--) | Recupere si la imagen contiene un canal alfa, indicando la presencia de información de transparencia. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Agregue una nueva página a la imagen, ampliando su contenido y acomodando elementos visuales adicionales. |
| [addBlock(IFrame block)](#addBlock-com.aspose.imaging.fileformats.webp.IFrame-) | Incorpore un nuevo bloque WebP en la imagen, enriqueciendo su contenido y facilitando una manipulación avanzada de la imagen. |
| [clearBlocks()](#clearBlocks--) | Elimine todos los bloques WebP existentes de la imagen, facilitando una hoja en blanco para modificaciones o adiciones posteriores. |
| [insertBlock(int index, IFrame block)](#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-) | Inserte un nuevo bloque WebP en el índice especificado dentro de la imagen, permitiendo un control preciso sobre la secuencia de bloques. |
| [removeBlock(IFrame block)](#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-) | Elimine el bloque WebP especificado de la imagen, facilitando una gestión eficiente de la estructura de datos de la imagen. |
| [getOriginalOptions()](#getOriginalOptions--) | Obtiene las opciones basadas en la configuración original del archivo. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Gire la imagen alrededor de su centro mediante un ángulo especificado, mientras la redimensiona proporcionalmente y aplica los parámetros de color de fondo especificados. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Redimensione la imagen, ajustando sus dimensiones mientras preserva la relación de aspecto. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Ajuste proporcionalmente el ancho de la imagen mientras mantiene su relación de aspecto. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Ajuste la altura de la imagen proporcionalmente, mientras preserva su relación de aspecto para un redimensionado consistente. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Aplique rotación, volteo o ambas operaciones exclusivamente al fotograma activo dentro de la imagen. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Realice tramado en la imagen actual para reducir bandas de color y mejorar la calidad visual. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recorte la imagen usando una región rectangular especificada, eliminando porciones no deseadas mientras conserva el contenido deseado. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Recorta la imagen aplicando desplazamientos izquierda, derecha, superior e inferior, seleccionando efectivamente una región de interés dentro de la imagen. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Realiza la binarización de la imagen utilizando un valor de umbral predefinido, convirtiéndola en una imagen binaria donde los píxeles se clasifican como primer plano o fondo según su intensidad respecto al umbral. |
| [binarizeOtsu()](#binarizeOtsu--) | Realiza la binarización de la imagen usando el método de umbralización de Otsu, determinando automáticamente el valor de umbral óptimo basándose en el histograma de la imagen. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Aplica la binarización a la imagen utilizando el algoritmo de umbralización adaptativa de Bradley con umbralización de imagen integral. |
| [grayscale()](#grayscale--) | Aplica la binarización a la imagen utilizando el algoritmo de umbralización adaptativa de Bradley con umbralización de imagen integral. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Aplica corrección gamma a la imagen, ajustando las intensidades de los píxeles para lograr el brillo y el equilibrio de color deseados. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Realiza corrección gamma en la imagen utilizando coeficientes individuales para los canales rojo, verde y azul, permitiendo ajustes finos del equilibrio de color y el contraste. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Implemente el ajuste de `brightness` para la imagen, permitiendo la modificación de los niveles de luminancia generales. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Mejora el contraste del [Image](../../com.aspose.imaging/image), amplificando las diferencias entre áreas claras y oscuras. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Filtre el contenido dentro del rectángulo especificado, aplicando un filtro de procesamiento de imagen designado para mejorar o modificar la región seleccionada. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Redimensiona la imagen según la configuración especificada, permitiendo un control preciso sobre las dimensiones, la relación de aspecto y el comportamiento de escalado. |

## Example: This example shows how to load a WebP image from a file and save it to PNG.

``` java
String dir = "c:\\temp\\";

// Carga una imagen WebP desde un archivo.
com.aspose.imaging.fileformats.webp.WebPImage webPImage = new com.aspose.imaging.fileformats.webp.WebPImage(dir + "test.webp");
try {
    // Guardar como PNG
    // Ten en cuenta que solo el fotograma activo se almacenará en PNG, ya que PNG no es un formato multipágina.
    webPImage.save(dir + "test.output.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    webPImage.dispose();
}
```

### WebPImage(InputStream stream) {#WebPImage-java.io.InputStream-}
```
public WebPImage(InputStream stream)
```


Instancia una nueva instancia de la clase [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), inicializada a partir de una fuente de flujo proporcionada. Utiliza este constructor para crear sin problemas objetos de imagen WebP directamente desde flujos, permitiendo un manejo y manipulación eficientes de los datos de imagen WebP dentro de tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | La imagen WebP del flujo. |

### WebPImage(InputStream stream, LoadOptions loadOptions) {#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public WebPImage(InputStream stream, LoadOptions loadOptions)
```


Crea una nueva instancia de la clase [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) usando un flujo y opciones de carga especificadas, facilitando un manejo versátil de los datos de imagen WebP. Incorpora este constructor para inicializar sin problemas objetos de imagen WebP desde flujos mientras personalizas los parámetros de carga según sea necesario dentro de tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | La imagen WebP del flujo. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Las opciones de carga. |

### WebPImage(String path) {#WebPImage-java.lang.String-}
```
public WebPImage(String path)
```


Instancia una nueva instancia de la clase [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), inicializada a partir de una fuente de archivo proporcionada. Utiliza este constructor para crear sin problemas objetos de imagen WebP directamente desde archivos, optimizando el proceso de carga y manipulación de los datos de imagen WebP dentro de tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | java.lang.String | La ruta al archivo de imagen WebP |

### WebPImage(String path, LoadOptions loadOptions) {#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public WebPImage(String path, LoadOptions loadOptions)
```


Crea una nueva instancia de la clase [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) usando un archivo y opciones de carga especificadas, facilitando un manejo flexible de los datos de imagen WebP. Utiliza este constructor para inicializar sin problemas objetos de imagen WebP desde archivos mientras personalizas los parámetros de carga de acuerdo con los requisitos de tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | java.lang.String | La ruta al archivo de imagen WebP |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Las opciones de carga. |

### WebPImage(RasterImage rasterImage) {#WebPImage-com.aspose.imaging.RasterImage-}
```
public WebPImage(RasterImage rasterImage)
```


Instancia una nueva instancia de la clase [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage), inicializada a partir de un objeto rasterImage proporcionado. Este constructor permite una conversión sin problemas de imágenes raster a formato WebP, habilitando un manejo y manipulación eficientes de los datos de imagen dentro de tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen raster. |

### WebPImage(RasterImage rasterImage, LoadOptions loadOptions) {#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-}
```
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```


Crea una nueva instancia de la clase [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) usando un objeto rasterImage y opciones de carga especificadas, permitiendo un manejo flexible de los datos de imagen. Utiliza este constructor para inicializar sin problemas objetos de imagen WebP a partir de imágenes raster mientras personalizas los parámetros de carga de acuerdo con los requisitos de tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen raster. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Las opciones de carga. |

### WebPImage(int width, int height, WebPOptions options) {#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-}
```
public WebPImage(int width, int height, WebPOptions options)
```


Instancia una nueva instancia de la clase [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) con una imagen vacía de dimensiones de ancho y alto especificadas. Este constructor permite la creación de imágenes WebP en blanco, proporcionando una base para la posterior manipulación de imágenes y generación de contenido dentro de tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho de la imagen |
| height | int | La altura de la imagen. |
| options | [WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) | Las opciones. |

### WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions) {#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-com.aspose.imaging.LoadOptions-}
```
public WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)
```


Crea una nueva instancia de la clase [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) con una imagen vacía y opciones de carga especificadas. Este constructor permite la inicialización de imágenes WebP con parámetros de carga personalizables, proporcionando flexibilidad en la creación y manipulación de imágenes dentro de tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho de la imagen |
| height | int | La altura de la imagen. |
| options | [WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) | Las opciones. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Las opciones de carga. |

### getOptions() {#getOptions--}
```
public WebPOptions getOptions()
```


Recupera o modifica las opciones asociadas a la propiedad especificada, permitiendo una personalización fina del comportamiento y la configuración. Utiliza esta propiedad para acceder y manipular sin problemas los parámetros configurables, facilitando un control versátil y la optimización dentro de la funcionalidad de tu aplicación.

**Returns:**
[WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) - the options.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Accede a los bloques WebP dentro de la imagen, permitiendo un examen detallado o la manipulación de la estructura subyacente de bloques. Utiliza esta propiedad para analizar o modificar bloques individuales dentro de los datos de imagen WebP, facilitando técnicas avanzadas de procesamiento de imágenes dentro de tu aplicación.

**Returns:**
com.aspose.imaging.Image[]
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Recupere el recuento total de páginas dentro del documento especificado, facilitando una navegación y gestión eficientes del contenido multipágina. Incorpore esta funcionalidad para mejorar la experiencia del usuario, permitiendo un acceso sin interrupciones a estructuras de documentos integrales.

**Returns:**
int - el recuento de páginas.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Accede al valor del formato de archivo asociado a la imagen, proporcionando información sobre el formato en el que se almacena la imagen. Utiliza esta propiedad para determinar el formato de archivo de la imagen, facilitando verificaciones de compatibilidad y procesamiento específico del formato dentro de tu aplicación.

**Returns:**
long - un valor del formato de archivo
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Obtén si la imagen contiene un canal alfa, lo que indica la presencia de información de transparencia. Utiliza esta propiedad para determinar si la imagen incluye transparencia, permitiendo un manejo y procesamiento adecuados de operaciones relacionadas con alfa dentro de tu aplicación.

**Returns:**
boolean - `true` si hay un canal alfa.

**Example: The following example loads a WEBP image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";
String fileName = dir + "sample.webp";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Si el fotograma TIFF activo tiene canal alfa, entonces se considera que toda la imagen TIFF tiene canal alfa.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, webpImage.getRawDataFormat(), webpImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.webp.IFrame frame : webpImage.getBlocks()) {
        if (frame instanceof com.aspose.imaging.fileformats.webp.WebPFrameBlock) {
            com.aspose.imaging.fileformats.webp.WebPFrameBlock frameBlock = (com.aspose.imaging.fileformats.webp.WebPFrameBlock) frame;
            System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", i++, frameBlock.getRawDataFormat(), frameBlock.hasAlpha());
        }
    }
} finally {
    image.dispose();
}

// La salida puede verse así:
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, canales usados: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, canales usados: 1, HasAlpha=False
```

### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Añade una nueva página a la imagen, ampliando su contenido y acomodando elementos visuales adicionales. Integra este método para facilitar la gestión dinámica de páginas dentro de tu aplicación, permitiendo la creación y ampliación sin problemas de documentos o imágenes multipágina.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | La página a agregar. |

### addBlock(IFrame block) {#addBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void addBlock(IFrame block)
```


Incorpora un nuevo bloque WebP en la imagen, enriqueciendo su contenido y facilitando la manipulación avanzada de imágenes. Integra este método para mejorar dinámicamente la estructura y complejidad de los datos de imagen WebP dentro de tu aplicación, permitiendo un control preciso y la optimización de la renderización de imágenes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | El bloque Webp a agregar. |


**Example: This example shows how to create a multi-frame animated WebP image with the specified options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.WebPOptions createOptions = new com.aspose.imaging.imageoptions.WebPOptions();
createOptions.setLossless(true);
createOptions.setQuality(100f);
createOptions.setAnimBackgroundColor((long) com.aspose.imaging.Color.getGray().toArgb());

// El fotograma predeterminado más 36 + 36 fotogramas adicionales.
createOptions.setAnimLoopCount(36 + 36 + 1);

// Crea una imagen WebP de 100x100 px.
com.aspose.imaging.fileformats.webp.WebPImage webPImage = new com.aspose.imaging.fileformats.webp.WebPImage(100, 100, createOptions);
try {
    // El primer círculo es rojo
    com.aspose.imaging.brushes.SolidBrush brush1 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    // El segundo círculo es negro
    com.aspose.imaging.brushes.SolidBrush brush2 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getBlack());

    // Aumenta gradualmente el ángulo de la forma de arco rojo.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.webp.WebPFrameBlock block = new com.aspose.imaging.fileformats.webp.WebPFrameBlock(100, 100);
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(block);
        graphics.fillPie(brush1, block.getBounds(), 0, angle);

        webPImage.addBlock(block);
    }

    // Aumenta gradualmente el ángulo del arco negro y elimina el arco rojo.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.webp.WebPFrameBlock block = new com.aspose.imaging.fileformats.webp.WebPFrameBlock(100, 100);

        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(block);
        graphics.fillPie(brush2, block.getBounds(), 0, angle);
        graphics.fillPie(brush1, block.getBounds(), angle, 360 - angle);

        webPImage.addBlock(block);
    }

    // Guardar en un archivo WebP
    webPImage.save(dir + "output.webp");
} finally {
    webPImage.dispose();
}
```

### clearBlocks() {#clearBlocks--}
```
public void clearBlocks()
```


Elimina todos los bloques WebP existentes de la imagen, facilitando una hoja en blanco para modificaciones o adiciones posteriores. Utiliza este método para restablecer eficazmente la estructura de bloques dentro de los datos de imagen WebP, asegurando una gestión y organización óptimas del contenido de la imagen en tu aplicación.

### insertBlock(int index, IFrame block) {#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void insertBlock(int index, IFrame block)
```


Inserta un nuevo bloque WebP en el índice especificado dentro de la imagen, permitiendo un control preciso sobre la secuencia de bloques. Integra este método para incorporar sin problemas bloques WebP adicionales en la estructura de datos de la imagen, facilitando el procesamiento avanzado de imágenes y la optimización en tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El elemento basado en cero, en el que se insertará `block`. |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | El bloque Webp a agregar. |

### removeBlock(IFrame block) {#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void removeBlock(IFrame block)
```


Elimina el bloque WebP especificado de la imagen, facilitando una gestión eficiente de la estructura de datos de la imagen. Utiliza este método para optimizar los flujos de trabajo de procesamiento de imágenes al eliminar bloques o componentes innecesarios en tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | El bloque a eliminar. |

--------------------

Nota: no olvides disponer de `block` si no lo vas a agregar a otro WebPImage. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Obtiene las opciones basadas en la configuración original del archivo. Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el método [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), se producirá una imagen PNG de salida con 8 bits por píxel. Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas al método [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) como segundo parámetro.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Gira la imagen alrededor de su centro mediante un ángulo especificado, mientras la redimensionas proporcionalmente y aplicas los parámetros de color de fondo especificados. Incorpora este método en tu flujo de trabajo de procesamiento de imágenes para lograr transformaciones precisas con colores de fondo personalizables, asegurando una presentación visual óptima en tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación en grados. Los valores positivos girarán en sentido horario. |
| resizeProportionally | boolean | si se establece en `true` el tamaño de su imagen cambiará según las proyecciones del rectángulo girado (puntos de esquina); de lo contrario, se dejarán las dimensiones sin cambios y solo `` el contenido de la imagen será rotado. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Color del fondo. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Redimensiona la imagen, ajustando sus dimensiones mientras preservas la relación de aspecto. Integra este método en tu flujo de trabajo de procesamiento de imágenes para escalar dinámicamente las imágenes y adaptarlas a diversos requisitos de visualización o almacenamiento en tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| resizeType | int | El tipo de redimensionado. |


**Example: This example loads a WEBP image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.webp.WebPImage image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Escalar 2 veces usando remuestreo de vecino más cercano.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Guardar como PNG con opciones predeterminadas.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Reducir 2 veces usando remuestreo de vecino más cercano.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Guardar como PNG con opciones predeterminadas.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Escalar 2 veces usando remuestreo bilineal.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Guardar como PNG con opciones predeterminadas.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // Reducir 2 veces usando remuestreo bilineal.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Guardar como PNG con opciones predeterminadas.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Ajusta proporcionalmente el ancho de la imagen manteniendo su relación de aspecto. Integra este método en tu flujo de trabajo de procesamiento de imágenes para redimensionar dinámicamente las imágenes con proporciones consistentes, asegurando una visualización o almacenamiento óptimo en tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| resizeType | int | Tipo de redimensionado. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Ajusta la altura de la imagen proporcionalmente, mientras preservas su relación de aspecto para un redimensionamiento consistente. Integra este método en tu flujo de trabajo de procesamiento de imágenes para redimensionar dinámicamente las imágenes con proporciones uniformes, asegurando una visualización o almacenamiento óptimo en tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newHeight | int | El nuevo alto. |
| resizeType | int | Tipo de redimensionado. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Aplica rotación, volteo o ambas operaciones exclusivamente al fotograma activo dentro de la imagen. Integra este método en tu flujo de trabajo de procesamiento de imágenes para lograr una manipulación precisa de fotogramas individuales, mejorando la flexibilidad y el control sobre las transformaciones de fotogramas en tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotateFlipType | int | El tipo de rotación y volteo. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Realiza tramado en la imagen actual para reducir el bandado de colores y mejorar la calidad visual. Integra este método en tu flujo de trabajo de procesamiento de imágenes para lograr transiciones más suaves entre colores y mejorar la apariencia general de la imagen en tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ditheringMethod | int | El método de tramado. |
| bitsCount | int | El recuento final de bits para el tramado. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta personalizada para el tramado. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Recorta la imagen usando una región rectangular especificada, eliminando partes no deseadas mientras conservas el contenido deseado. Integra este método en tu flujo de trabajo de procesamiento de imágenes para extraer y enfocar con precisión áreas específicas de interés dentro de la imagen, mejorando la claridad y composición para diversas aplicaciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Recorta la imagen aplicando desplazamientos izquierda, derecha, superior e inferior, seleccionando efectivamente una región de interés dentro de la imagen. Utiliza este método para extraer dinámicamente las porciones deseadas de la imagen mientras ajustas su composición y enfoque según los requisitos de tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| leftShift | int | El desplazamiento izquierdo. |
| rightShift | int | El desplazamiento derecho. |
| topShift | int | El desplazamiento superior. |
| bottomShift | int | El desplazamiento inferior. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Realiza binarización en la imagen usando un valor de umbral predefinido, convirtiéndola en una imagen binaria donde los píxeles se clasifican como primer plano o fondo según su intensidad respecto al umbral. Integra este método en tu flujo de trabajo de procesamiento de imágenes para facilitar tareas de segmentación y extracción de características, mejorando la precisión y eficiencia del análisis posterior en tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threshold | byte | Valor de umbral. Si el valor gris correspondiente de un píxel es mayor que el umbral, se le asignará un valor de (byte)255, 0 en caso contrario. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Realice la binarización de la imagen usando el método de umbralización de Otsu, determinando automáticamente el valor de umbral óptimo basado en el histograma de la imagen. Integre este método en su flujo de trabajo de procesamiento de imágenes para lograr una segmentación y extracción de características efectivas, mejorando la precisión y fiabilidad de las tareas de análisis de imágenes dentro de su aplicación.

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Aplique la binarización a la imagen usando el algoritmo de umbralización adaptativa de Bradley con umbralización de imagen integral. Este método calcula dinámicamente umbrales locales basados en el vecindario de la imagen, mejorando la adaptabilidad a condiciones de iluminación variables y garantizando una segmentación robusta para tareas de procesamiento posteriores dentro de su aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightnessDifference | double | La diferencia de brillo entre el píxel y el promedio de una ventana de s x s píxeles centrada en este píxel. |
| windowSize | int | El tamaño de la ventana de s x s píxeles centrada en este píxel |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Aplique la binarización a la imagen usando el algoritmo de umbralización adaptativa de Bradley con umbralización de imagen integral. Este método calcula dinámicamente umbrales locales basados en el vecindario de la imagen, mejorando la adaptabilidad a condiciones de iluminación variables y garantizando una segmentación robusta para tareas de procesamiento posteriores dentro de su aplicación.

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Aplique corrección gamma a la imagen, ajustando las intensidades de los píxeles para lograr el brillo y el balance de color deseados. Incorpore este método en su flujo de trabajo de procesamiento de imágenes para mejorar la calidad visual y aumentar la precisión de los análisis o tareas de visualización posteriores dentro de su aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gamma | float | Coeficiente gamma para los canales rojo, verde y azul |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Realice corrección gamma en la imagen usando coeficientes individuales para los canales rojo, verde y azul, permitiendo ajustes finos del balance de color y el contraste. Integre este método en su canal de procesamiento de imágenes para lograr un control preciso sobre la representación del color y mejorar la fidelidad visual dentro de su aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gammaRed | float | Gamma para el coeficiente del canal rojo |
| gammaGreen | float | Gamma para el coeficiente del canal verde |
| gammaBlue | float | Coeficiente gamma para el canal azul |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Implementa el ajuste de `brightness` para la imagen, permitiendo la modificación de los niveles de luminancia generales. Incorpora este método en tu flujo de procesamiento de imágenes para mejorar la visibilidad y la calidad visual de las imágenes dentro de tu aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightness | int | Valor de brillo. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Mejore el contraste del [Image](../../com.aspose.imaging/image), amplificando las diferencias entre áreas claras y oscuras. Integre este método en su flujo de trabajo de procesamiento de imágenes para mejorar la claridad visual y la calidad general de la imagen dentro de su aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contrast | float | Valor de contraste (en el rango [-100; 100]) |

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


**Example: The following example applies various types of filters to a WEBP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Aplica un filtro mediano con un tamaño de rectángulo de 5 a toda la imagen.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    webpImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Aplica un filtro de suavizado bilateral con un tamaño de kernel de 5 a toda la imagen.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    webpImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Aplica un filtro de desenfoque gaussiano con un radio de 5 y un valor sigma de 4.0 a toda la imagen.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Aplica un filtro Gauss-Wiener con un radio de 5 y un valor de suavizado de 4.0 a toda la imagen.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Aplica un filtro wiener de movimiento con una longitud de 5, un valor de suavizado de 4.0 y un ángulo de 90.0 grados a toda la imagen.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    webpImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Aplica un filtro de nitidez con un tamaño de kernel de 5 y un valor sigma de 4.0 a toda la imagen.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Redimensione la imagen según los ajustes especificados, permitiendo un control preciso sobre dimensiones, relación de aspecto y comportamiento de escalado. Integre este método en su flujo de trabajo de procesamiento de imágenes para lograr operaciones de redimensionado personalizadas adaptadas a los requisitos específicos de su aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | La configuración de redimensionado. |

