---
title: "GifImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La API para el archivo de imagen GIF (Formato de Intercambio Gráfico) proporciona a los desarrolladores herramientas versátiles para procesar imágenes rasterizadas comprimidas y GIF animados."
type: docs
weight: 13
url: /es/java/com.aspose.imaging.fileformats.gif/gifimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), com.aspose.fileformats.core.interfaces.IInterlaced
```
public final class GifImage extends RasterCachedMultipageImage implements IMultipageImageExt, IInterlaced
```

La API para el archivo de imagen GIF (Formato de Intercambio Gráfico) proporciona a los desarrolladores herramientas versátiles para procesar imágenes rasterizadas comprimidas y GIF animados. Ofrece funciones como manejo de metadatos XMP, configuración de paleta de colores, control de color de fondo y transparente, ajustes de opacidad, redimensionado, recorte, aplicación de filtros, correcciones gamma, ajuste de contraste, transformación a escala de grises y conversión a otros formatos. Esta API permite una manipulación y mejora fluida de imágenes GIF para una amplia gama de aplicaciones.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-) | Inicie un nuevo objeto [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) con los parámetros especificados para el primer fotograma y la paleta global. |
| [GifImage(GifFrameBlock firstFrame)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-) | Crear imágenes GIF se vuelve sencillo con el constructor [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage). |
| [GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-boolean-byte-byte-byte-boolean-) | Comience sin esfuerzo con el constructor [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Recupere el formato de archivo sin esfuerzo con esta propiedad. |
| [hasTrailer()](#hasTrailer--) | Administre la presencia de un trailer en sus archivos GIF con esta propiedad. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Administre la presencia de un trailer en sus archivos GIF con esta propiedad. |
| [isPaletteSorted()](#isPaletteSorted--) | Controle la ordenación de la paleta en sus imágenes GIF usando esta propiedad. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Controle la ordenación de la paleta en sus imágenes GIF usando esta propiedad. |
| [getLoopsCount()](#getLoopsCount--) | Recupere el recuento de bucles sin esfuerzo con esta propiedad. |
| [setLoopsCount(int value)](#setLoopsCount-int-) | Recupere el recuento de bucles sin esfuerzo con esta propiedad. |
| [getPaletteColorResolutionBits()](#getPaletteColorResolutionBits--) | Administre la resolución de color de la paleta de sus imágenes GIF con esta propiedad. |
| [setPaletteColorResolutionBits(byte value)](#setPaletteColorResolutionBits-byte-) | Administre la resolución de color de la paleta de sus imágenes GIF con esta propiedad. |
| [getPageCount()](#getPageCount--) | Recupere el número total de páginas contenidas en la imagen con esta propiedad sencilla. |
| [getPages()](#getPages--) | Obtenga acceso a las páginas dentro de la imagen mediante esta práctica propiedad, permitiendo una navegación fluida y la manipulación de páginas individuales según sea necesario. |
| [getBlocks()](#getBlocks--) | Acceda a los bloques GIF sin problemas con esta propiedad, facilitando la recuperación y manipulación sencilla de las estructuras de datos subyacentes de la imagen. |
| [isInterlaced()](#isInterlaced--) | Determina si la imagen está entrelazada, lo que afecta su visualización durante la carga. |
| [getOriginalOptions()](#getOriginalOptions--) | Recupere las opciones basadas en la configuración original del archivo, cruciales para mantener la fidelidad y consistencia en el procesamiento y manipulación de imágenes. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Incorpore una nueva página sin problemas en la imagen existente, mejorando su contenido y ampliando su alcance. |
| [getActiveFrame()](#getActiveFrame--) | Administre y manipule fotogramas con esta propiedad, permitiendo una navegación fluida y la modificación del fotograma activo dentro de la imagen GIF. |
| [setActiveFrame(GifFrameBlock value)](#setActiveFrame-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-) | Administre y manipule fotogramas con esta propiedad, permitiendo una navegación fluida y la modificación del fotograma activo dentro de la imagen GIF. |
| [getBackgroundColor()](#getBackgroundColor--) | Administre el color de fondo de la imagen GIF con esta propiedad. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Administre el color de fondo de la imagen GIF con esta propiedad. |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Controle el índice del color de fondo de la imagen GIF usando esta propiedad. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Controle el índice del color de fondo de la imagen GIF usando esta propiedad. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Administre la relación de aspecto de píxel de la imagen GIF con esta propiedad. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Administre la relación de aspecto de píxel de la imagen GIF con esta propiedad. |
| [hasTransparentColor()](#hasTransparentColor--) | Determine si el fotograma activo de la imagen GIF incluye un color transparente. |
| [getTransparentColor()](#getTransparentColor--) | Recupere el color transparente del fotograma activo en la imagen GIF. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Determine si el fotograma activo de la imagen GIF incluye un color transparente. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Esta propiedad determina si la imagen GIF contiene un color de fondo. |
| [getImageOpacity()](#getImageOpacity--) | Recupere la opacidad del fotograma activo dentro de la imagen, ofreciendo una visión de su nivel de transparencia. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Redimensiona esta instancia de [Image](../../com.aspose.imaging/image). |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Redimensiona esta instancia de [Image](../../com.aspose.imaging/image). |
| [resizeFullFrame(int newWidth, int newHeight, int resizeType)](#resizeFullFrame-int-int-int-) | Redimensionamiento de la imagen teniendo en cuenta los fotogramas completos de cada página en un GIF, evitando así la aparición de posibles artefactos. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Realice rotación, volteo o ambos en el fotograma activo exclusivamente. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Aplique dithering a la imagen actual. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recorte la imagen usando un área rectangular especificada. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Mejore la calidad de la imagen aplicando corrección gamma. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Aplique un filtro específico al área designada de la imagen, mejorando su calidad visual o alterando su apariencia según se desee. |
| [setFrameTime(int time)](#setFrameTime-int-) | Ajusta la duración de cada fotograma en milisegundos, asegurando una sincronización constante a lo largo de la secuencia de imágenes. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Ajusta el brillo de la imagen según el parámetro `brightness` especificado. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Ajusta el contraste de la imagen, aumentando o reduciendo la diferencia de brillo entre píxeles. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | La corrección gamma de una imagen aplica un ajuste no lineal a los valores de los píxeles, aumentando o reduciendo el brillo según los coeficientes especificados para los canales rojo, verde y azul. |
| [grayscale()](#grayscale--) | La transformación de una imagen a su representación en escala de grises convierte la imagen en color en una versión en escala de grises al eliminar la información de color mientras se conserva la luminancia. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | La binarización de una imagen con un umbral predefinido convierte una imagen en escala de grises o en color en una imagen binaria, donde cada píxel se clasifica como negro o blanco según si su valor de intensidad supera un umbral especificado. |
| [binarizeOtsu()](#binarizeOtsu--) | La binarización de una imagen con umbralización de Otsu es un método utilizado para determinar automáticamente el valor de umbral óptimo para convertir una imagen en escala de grises en una imagen binaria. |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | La binarización de una imagen usando el algoritmo de umbralización adaptativa de Bradley con umbralización de imagen integral es un método para convertir una imagen en escala de grises en una imagen binaria. |
| [orderBlocks()](#orderBlocks--) | Ordenar los bloques GIF de acuerdo con la especificación GIF garantiza una disposición adecuada del GIF y el cumplimiento del estándar. |
| [clearBlocks()](#clearBlocks--) | Borrar todos los bloques GIF elimina cualquier dato existente almacenado dentro de la imagen. |
| [insertBlock(int index, IGifBlock block)](#insertBlock-int-com.aspose.imaging.fileformats.gif.IGifBlock-) | Insertar un nuevo bloque GIF le permite agregar datos personalizados en una posición específica dentro de la imagen. |
| [addBlock(IGifBlock block)](#addBlock-com.aspose.imaging.fileformats.gif.IGifBlock-) | Agregar un nuevo bloque GIF le permite incluir datos adicionales dentro de la imagen. |
| [removeBlock(IGifBlock block)](#removeBlock-com.aspose.imaging.fileformats.gif.IGifBlock-) | Eliminar un bloque GIF elimina datos específicos de la imagen, ofreciendo la posibilidad de limpiar o modificar la estructura de la imagen. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | El redimensionado proporcional mantiene la relación de aspecto de la imagen mientras ajusta su tamaño, asegurando que la imagen no aparezca estirada o distorsionada. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Este método rota la imagen alrededor de su punto central. |

## Example: This example shows how to create a GIF image and save it to a file.

``` java
String dir = "c:\\temp\\";

// Cree un bloque de fotograma GIF de 100x100 px.
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
try {
    // Rellene todo el bloque en rojo.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(firstBlock);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    gr.fillRectangle(brush, firstBlock.getBounds());

    com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
    try {
        gifImage.save(dir + "output.gif");
    } finally {
        gifImage.dispose();
    }
} finally {
    firstBlock.dispose();
}
```


## Example: Create multipage GIF image using single page raster images.

``` java
static void main(String[] args)
{
    // Cargar fotogramas
    RasterImage[] frames = loadFrames("Animation frames");

    // Crear imagen GIF usando el primer fotograma
    try (GifImage image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Agregar fotogramas a la imagen GIF usando el método AddPage
        for (int index = 1; index < frames.length; index++)
        {
            image.addPage(frames[index]);
        }

        // Guardar imagen GIF
        image.save("Multipage.gif");
    }

    // liberar recursos
    for (RasterImage frame : frames)
    {
        frame.close();
    }
}

private static RasterImage[] loadFrames(String directory)
{
    LinkedList<RasterImage> list = new LinkedList<RasterImage>();
    String[] fileList = new File(directory).list();
    if (fileList != null)
    {
        for (String filePath : fileList)
        {
            list.add((RasterImage) Image.load(filePath));
        }
    }
                
    return list.toArray(new RasterImage[0]);
}
```


## Example: Export of part of animation from GIF image based on time interval.

``` java
try (Image image = Image.load("Animation.gif"))
{
    GifOptions options = new GifOptions();
    options.setFullFrame(true);
    final MultiPageOptions multiPageOptions = new MultiPageOptions();
    multiPageOptions.setMode(MultiPageMode.TimeInterval);
    multiPageOptions.setTimeInterval(new TimeInterval(0, 400));
    options.setMultiPageOptions(multiPageOptions);

    image.save("PartOfAnimation.gif", options);
}
```

### GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-}
```
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)
```


Inicie un nuevo objeto [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage) con los parámetros especificados para el primer fotograma y la paleta global. Comience a gestionar imágenes GIF rápidamente, asegurando una representación precisa con configuraciones personalizables para obtener resultados óptimos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | El primer fotograma con el que inicializar la imagen GIF. |
| globalPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta global a usar. Nota: si tanto `firstFrame` como `globalPalette` son nulos, se utiliza la paleta global predeterminada. |

### GifImage(GifFrameBlock firstFrame) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-}
```
public GifImage(GifFrameBlock firstFrame)
```


Crear imágenes GIF se vuelve sencillo con el constructor [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage). Con solo el parámetro firstFrame, se abre un mundo de comunicación visual dinámica.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | El primer fotograma con el que inicializar la imagen GIF. |

### GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-boolean-byte-byte-byte-boolean-}
```
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer)
```


Comienza sin esfuerzo con el constructor [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage). Con este método sencillo, puedes sumergirte en la creación de GIFs animados con facilidad. Simplemente proporciona firstFrame, globalPalette, paletteColorResolution, aspectRatio y otros parámetros, y estarás listo para dar vida a tus imágenes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | El primer fotograma con el que inicializar la imagen GIF. |
| globalPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta global a usar. Nota: si tanto `firstFrame` como `globalPalette` son nulos, se utiliza la paleta global predeterminada. |
| isPaletteSorted | boolean | si se establece en `true` la paleta se ordena. Nota que el parámetro se usa cuando `globalPalette` no es nulo. |
| paletteColorResolution | byte | La resolución de color de la paleta. Nota que el parámetro se usa cuando `globalPalette` no es nulo. |
| paletteBackgroundColorIndex | byte | El índice de color de fondo de la paleta. |
| aspectRatio | byte | La relación de aspecto. |
| hasTrailer | boolean | si se establece en `true` la imagen GIF tiene trailer; de lo contrario, no se escribe ningún trailer al final del flujo. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Obtén el formato de archivo sin esfuerzo con esta propiedad. Es tu fuente principal para identificar el formato de tus archivos. Integrada sin problemas en tu flujo de trabajo, proporciona información vital sin complicaciones.

**Returns:**
long
### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Gestiona la presencia de un trailer en tus archivos GIF con esta propiedad. Ya sea que necesites comprobar si existe un trailer o establecer su presencia, esta propiedad simplifica el proceso. Mantén tus archivos GIF estructurados y conformes con esta característica intuitiva.

**Returns:**
boolean - `true` si el GIF tiene tráiler; de lo contrario, `false`.
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Gestiona la presencia de un trailer en tus archivos GIF con esta propiedad. Ya sea que necesites comprobar si existe un trailer o establecer su presencia, esta propiedad simplifica el proceso. Mantén tus archivos GIF estructurados y conformes con esta característica intuitiva.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | `true` si el GIF tiene tráiler; de lo contrario, `false`. |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Controla la ordenación de la paleta en tus imágenes GIF usando esta propiedad. Ya sea que necesites verificar si la paleta está ordenada o establecer el comportamiento de ordenación, esta propiedad ofrece una forma sencilla de gestionar la organización de la paleta en tus archivos GIF.

**Returns:**
boolean - `true` si la paleta está ordenada; de lo contrario, `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Controla la ordenación de la paleta en tus imágenes GIF usando esta propiedad. Ya sea que necesites verificar si la paleta está ordenada o establecer el comportamiento de ordenación, esta propiedad ofrece una forma sencilla de gestionar la organización de la paleta en tus archivos GIF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | `true` si la paleta está ordenada; de lo contrario, `false`. |

### getLoopsCount() {#getLoopsCount--}
```
public int getLoopsCount()
```


Obtén el recuento de bucles sin esfuerzo con esta propiedad. Si tu imagen GIF incluye información de bucle, esta propiedad te brinda acceso rápido al recuento de bucles, permitiéndote gestionar de forma fluida el comportamiento de repetición en tus archivos GIF.

**Returns:**
int - El recuento de bucles o 1 (valor predeterminado)
### setLoopsCount(int value) {#setLoopsCount-int-}
```
public void setLoopsCount(int value)
```


Obtén el recuento de bucles sin esfuerzo con esta propiedad. Si tu imagen GIF incluye información de bucle, esta propiedad te brinda acceso rápido al recuento de bucles, permitiéndote gestionar de forma fluida el comportamiento de repetición en tus archivos GIF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El recuento de bucles o 1 (valor predeterminado) |

### getPaletteColorResolutionBits() {#getPaletteColorResolutionBits--}
```
public byte getPaletteColorResolutionBits()
```


Gestiona la resolución de color de la paleta de tus imágenes GIF con esta propiedad. Ajusta la cantidad de bits usados para representar los colores en la paleta, proporcionando un control preciso sobre la profundidad de color y la calidad de la imagen.

**Returns:**
byte - Los bits de resolución de color de la paleta.
### setPaletteColorResolutionBits(byte value) {#setPaletteColorResolutionBits-byte-}
```
public void setPaletteColorResolutionBits(byte value)
```


Gestiona la resolución de color de la paleta de tus imágenes GIF con esta propiedad. Ajusta la cantidad de bits usados para representar los colores en la paleta, proporcionando un control preciso sobre la profundidad de color y la calidad de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte | Los bits de resolución de color de la paleta. |

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Obtén el número total de páginas contenidas en la imagen con esta propiedad directa. Ideal para evaluar rápidamente la extensión del contenido de la imagen.

**Returns:**
int - el recuento de páginas.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Obtenga acceso a las páginas dentro de la imagen mediante esta práctica propiedad, permitiendo una navegación fluida y la manipulación de páginas individuales según sea necesario.

**Returns:**
com.aspose.imaging.Image[] - las páginas.
### getBlocks() {#getBlocks--}
```
public IGifBlock[] getBlocks()
```


Acceda a los bloques GIF sin problemas con esta propiedad, facilitando la recuperación y manipulación sencilla de las estructuras de datos subyacentes de la imagen.

**Returns:**
com.aspose.imaging.fileformats.gif.IGifBlock[] - los bloques GIF.
### isInterlaced() {#isInterlaced--}
```
public boolean isInterlaced()
```


Determina si la imagen está entrelazada, lo que afecta su visualización durante la carga. Esta propiedad ofrece información sobre el comportamiento de renderizado de la imagen, esencial para optimizar las estrategias de carga y mejorar la experiencia de visualización en general.

**Returns:**
boolean - `true` si esta instancia de imagen está entrelazada; de lo contrario, `false`.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Recupere las opciones basadas en la configuración original del archivo, cruciales para mantener la fidelidad y consistencia en el procesamiento y manipulación de imágenes. Este método permite la integración sin problemas de los parámetros específicos del archivo en operaciones posteriores, garantizando una representación precisa y el cumplimiento de las características inherentes de la imagen. Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el método [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), se producirá una imagen PNG de salida con 8 bits por píxel. Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas al método [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) como segundo parámetro.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Incorpore una nueva página sin problemas en la imagen existente, mejorando su contenido y ampliando su alcance. Este método aumenta las colecciones de imágenes con contenido adicional, fomentando la creatividad y la flexibilidad en la gestión y composición de imágenes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | La página a agregar. |


**Example: Create multipage GIF image using single page raster images.**

``` java
static void main(String[] args)
{
    // Cargar fotogramas
    RasterImage[] frames = loadFrames("Animation frames");

    // Crear imagen GIF usando el primer fotograma
    try (GifImage image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Agregar fotogramas a la imagen GIF usando el método AddPage
        for (int index = 1; index < frames.length; index++)
        {
            image.addPage(frames[index]);
        }

        // Guardar imagen GIF
        image.save("Multipage.gif");
    }

    // liberar recursos
    for (RasterImage frame : frames)
    {
        frame.close();
    }
}

private static RasterImage[] loadFrames(String directory)
{
    LinkedList<RasterImage> list = new LinkedList<RasterImage>();
    String[] fileList = new File(directory).list();
    if (fileList != null)
    {
        for (String filePath : fileList)
        {
            list.add((RasterImage) Image.load(filePath));
        }
    }
                
    return list.toArray(new RasterImage[0]);
}
```

### getActiveFrame() {#getActiveFrame--}
```
public GifFrameBlock getActiveFrame()
```


Administre y manipule fotogramas con esta propiedad, permitiendo una navegación fluida y la modificación del fotograma activo dentro de la imagen GIF.

**Returns:**
[GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) - the active frame.

**Example: The following example shows how to remove all blocks from a GIF image.**

``` java
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }

    System.out.println("Clear all the blocks");
    gifImage.clearBlocks();

    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}

// La salida se ve así:
// Tamaño del fotograma activo: { Width = 100, Height = 100}
// Borrar todos los bloques
// El fotograma activo no está establecido
```

### setActiveFrame(GifFrameBlock value) {#setActiveFrame-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-}
```
public void setActiveFrame(GifFrameBlock value)
```


Administre y manipule fotogramas con esta propiedad, permitiendo una navegación fluida y la modificación del fotograma activo dentro de la imagen GIF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | el fotograma activo. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Gestione el color de fondo de la imagen GIF con esta propiedad. Puede establecer o recuperar el color de fondo para garantizar la consistencia y mejorar el atractivo visual.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Gestione el color de fondo de la imagen GIF con esta propiedad. Puede establecer o recuperar el color de fondo para garantizar la consistencia y mejorar el atractivo visual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | el color de fondo. |

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Controle el índice del color de fondo de la imagen GIF usando esta propiedad. Establezca o recupere el índice para mantener la consistencia o lograr los efectos visuales deseados.

**Returns:**
byte - el índice del color de fondo.
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Controle el índice del color de fondo de la imagen GIF usando esta propiedad. Establezca o recupere el índice para mantener la consistencia o lograr los efectos visuales deseados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte | el índice del color de fondo. |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Gestione la relación de aspecto de píxel de la imagen GIF con esta propiedad. Establezca o recupere la relación de aspecto para garantizar una renderización precisa y mantener la fidelidad visual.

**Returns:**
byte - la relación de aspecto de píxel.
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Gestione la relación de aspecto de píxel de la imagen GIF con esta propiedad. Establezca o recupere la relación de aspecto para garantizar una renderización precisa y mantener la fidelidad visual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte | la relación de aspecto de píxel. |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Determine si el fotograma activo de la imagen GIF incluye un color transparente. Esta propiedad ofrece una forma conveniente de verificar la transparencia dentro de la imagen.

**Returns:**
boolean - un valor que indica si el fotograma activo tiene color transparente.
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Recupere el color transparente del fotograma activo en la imagen GIF. Esta propiedad le permite acceder al color específico que ha sido designado como transparente dentro del fotograma activo actual.

**Returns:**
[Color](../../com.aspose.imaging/color) - active frame transparent color.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Determine si el fotograma activo de la imagen GIF incluye un color transparente. Esta propiedad ofrece una forma conveniente de verificar la transparencia dentro de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si el fotograma activo tiene color transparente. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Esta propiedad determina si la imagen GIF contiene un color de fondo. Si es true, indica que la imagen incluye un color de fondo.

**Returns:**
boolean - un valor que indica si la imagen tiene color de fondo.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Recupere la opacidad del fotograma activo dentro de la imagen, ofreciendo información sobre su nivel de transparencia. Esta propiedad es particularmente útil para comprender el grado de transparencia u opacidad del fotograma activo en la imagen.

El valor de opacidad entre 0.0 (totalmente transparente) y 1.0 (totalmente opaco).

**Returns:**
float - opacidad de esta imagen (fotograma activo).
### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Redimensiona esta instancia de [Image](../../com.aspose.imaging/image).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| resizeType | int | El tipo de redimensionado. |


**Example: This example loads a GIF image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.gif.GifImage image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Escalar 2 veces usando remuestreo de vecino más cercano.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Reducir 2 veces usando remuestreo de vecino más cercano.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Escalar 2 veces usando remuestreo bilineal.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Reducir 2 veces usando remuestreo bilineal.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Redimensiona esta instancia de [Image](../../com.aspose.imaging/image).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Los ajustes. |


**Example: This example loads a GIF image and resizes it using various resizing settings.**

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

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Reducir a la mitad usando remuestreo adaptativo.
    gifImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Guardar como PNG
    gifImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeFullFrame(int newWidth, int newHeight, int resizeType) {#resizeFullFrame-int-int-int-}
```
public void resizeFullFrame(int newWidth, int newHeight, int resizeType)
```


Redimensionamiento de la imagen teniendo en cuenta todos los fotogramas de cada página en un GIF, evitando así la aparición de artefactos potenciales. Este método es esencial para mantener la integridad y calidad de la imagen, especialmente al trabajar con GIFs animados o secuencias de fotogramas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| resizeType | int | El tipo de redimensionado. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Realiza rotación, volteo o ambos en el fotograma activo exclusivamente. Esta operación aplica transformaciones únicamente al fotograma actualmente activo de la imagen, preservando la integridad de los demás fotogramas en la secuencia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotateFlipType | int | El tipo de rotación y volteo. |


**Example: This example loads a GIF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java

// La clase auxiliar utilizada en el ejemplo principal a continuación.
class Utils {
    // El método auxiliar para obtener una representación en cadena del formato de archivo.
    public String getRotateFlipTypeString(int rotateFlipType) {
        if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipNone) {
            return "RotateNoneFlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipNone) {
            return "Rotate90FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipNone) {
            return "Rotate180FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipNone) {
            return "Rotate270FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipX) {
            return "RotateNoneFlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipX) {
            return "Rotate90FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipX) {
            return "Rotate180FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipX) {
            return "Rotate270FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipY) {
            return "RotateNoneFlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipY) {
            return "Rotate90FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipY) {
            return "Rotate180FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipY) {
            return "Rotate270FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipXY) {
            return "RotateNoneFlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipXY) {
            return "Rotate90FlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipXY) {
            return "Rotate180FlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipXY) {
            return "Rotate270FlipXY";
        } else {
            return "UNDEFINED";
        }
    }
}

// Aquí está el ejemplo principal
Utils utils = new Utils();

String dir = "c:\\temp\\";

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Rotar, voltear y guardar en el archivo de salida.
    com.aspose.imaging.fileformats.gif.GifImage image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + utils.getRotateFlipTypeString(rotateFlipType) + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Aplica dithering a la imagen actual. Este proceso mejora la calidad de la imagen al reducir el banding de color y mejorar las transiciones de color, resultando en una apariencia más suave.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ditheringMethod | int | El método de tramado. |
| bitsCount | int | El recuento final de bits para el tramado. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta personalizada para el tramado. |


**Example: The following example loads a GIF image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Realizar dithering por umbral usando una paleta de colores de 4 bits que contiene 16 colores.
    // Cuantos más bits se especifiquen, mayor será la calidad y mayor el tamaño de la imagen de salida.
    // Tenga en cuenta que solo se admiten paletas de 1 bit, 4 bits y 8 bits en este momento.
    gifImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    gifImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Realizar dithering Floyd usando una paleta de colores de 1 bit que contiene solo 2 colores: negro y blanco.
    // Cuantos más bits se especifiquen, mayor será la calidad y mayor el tamaño de la imagen de salida.
    // Tenga en cuenta que solo se admiten paletas de 1 bit, 4 bits y 8 bits en este momento.
    gifImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    gifImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Recorta la imagen usando un área rectangular especificada. Esta operación elimina la porción exterior de la imagen, dejando solo la región seleccionada definida por el rectángulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo. |


**Example: The following example crops a GIF image.**
El siguiente ejemplo recorta una imagen GIF. El área de recorte se especifica mediante Aspose.Imaging.Rectangle.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Recorte la imagen. El área de recorte es la zona rectangular central de la imagen.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            gifImage.getWidth() / 4,
            gifImage.getHeight() / 4,
            gifImage.getWidth() / 2,
            gifImage.getHeight() / 2);
    gifImage.crop(area);

    // Guarde la imagen recortada en PNG
    gifImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Mejora la calidad de la imagen aplicando corrección gamma. Este método ajusta la gamma de color de la imagen para lograr una claridad visual óptima. Modifica el valor gamma de cada píxel, resultando en una mejor reproducción del color y una apariencia general de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gamma | float | Coeficiente gamma para los canales rojo, verde y azul |


**Example: The following example performs gamma-correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Establecer el coeficiente gamma para los canales rojo, verde y azul.
    gifImage.adjustGamma(2.5f);
    gifImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Aplica un filtro específico al área designada de la imagen, mejorando su calidad visual o alterando su apariencia según se desee. Este método procesa selectivamente los píxeles dentro del rectángulo definido, permitiendo realizar ajustes dirigidos mientras se preserva la integridad de los datos de la imagen circundante.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Las opciones. |


**Example: The following example applies various types of filters to a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Aplica un filtro mediano con un tamaño de rectángulo de 5 a toda la imagen.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    gifImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Aplica un filtro de suavizado bilateral con un tamaño de kernel de 5 a toda la imagen.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    gifImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Aplica un filtro de desenfoque gaussiano con un radio de 5 y un valor sigma de 4.0 a toda la imagen.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Aplica un filtro Gauss-Wiener con un radio de 5 y un valor de suavizado de 4.0 a toda la imagen.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Aplica un filtro wiener de movimiento con una longitud de 5, un valor de suavizado de 4.0 y un ángulo de 90.0 grados a toda la imagen.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    gifImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Aplica un filtro de nitidez con un tamaño de kernel de 5 y un valor sigma de 4.0 a toda la imagen.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### setFrameTime(int time) {#setFrameTime-int-}
```
public void setFrameTime(int time)
```


Ajusta la duración de cada fotograma en milisegundos, asegurando una sincronización constante a lo largo de la secuencia de imágenes. Este método establece uniformemente el tiempo de visualización para cada fotograma, permitiendo un control preciso de la velocidad de la animación. Cambiar este valor restablecerá el retraso para todos los fotogramas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tiempo | int | El tiempo de duración del fotograma en milisegundos. |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Ajusta el brillo de la imagen según el parámetro `brightness` especificado. Este método modifica uniformemente el brillo de toda la imagen, aumentando o reduciendo la luminancia general para lograr el efecto deseado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightness | int | Valor de brillo. |


**Example: The following example performs brightness correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Establece el valor de brillo. Los valores aceptados de brillo están en el rango [-255, 255].
    gifImage.adjustBrightness(50);
    gifImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Ajusta el contraste de la imagen, aumentando o reduciendo la diferencia de brillo entre los píxeles. Este método modifica el rango tonal general de la imagen, haciendo que las áreas más oscuras sean más oscuras y las áreas más claras más claras para mejorar la claridad visual y el detalle.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contrast | float | Valor de contraste (en el rango [-100; 100]) |


**Example: The following example performs contrast correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Establece el valor de contraste. Los valores aceptados de contraste están en el rango [-100f, 100f].
    gifImage.adjustContrast(50f);
    gifImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


La corrección gamma de una imagen aplica un ajuste no lineal a los valores de los píxeles, aumentando o reduciendo el brillo según los coeficientes especificados para los canales rojo, verde y azul. Este método ayuda a afinar el equilibrio de color y la luminancia de la imagen, mejorando su apariencia general y calidad visual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| gammaRed | float | Gamma para el coeficiente del canal rojo |
| gammaGreen | float | Gamma para el coeficiente del canal verde |
| gammaBlue | float | Coeficiente gamma para el canal azul |


**Example: The following example performs gamma-correction of a GIF image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Establecer coeficientes gamma individuales para los canales rojo, verde y azul.
    gifImage.adjustGamma(1.5f, 2.5f, 3.5f);
    gifImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


La transformación de una imagen a su representación en escala de grises convierte la imagen a color en una versión en escala de grises al eliminar la información de color mientras se preserva la luminancia. Este proceso simplifica la imagen a tonos de gris, haciéndola adecuada para diversas aplicaciones como impresión, procesamiento de documentos y análisis en escala de grises.


**Example: The following example transforms a colored GIF image to its grayscale representation.**
El siguiente ejemplo transforma una imagen GIF coloreada a su representación en escala de grises. Las imágenes en escala de grises están compuestas exclusivamente por tonos de gris y solo contienen información de intensidad.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    gifImage.grayscale();
    gifImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


La binarización de una imagen con un umbral predefinido convierte una imagen en escala de grises o en color en una imagen binaria, donde cada píxel se clasifica como negro o blanco según si su valor de intensidad supera un umbral especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threshold | byte | Valor del umbral. Si el valor gris correspondiente de un píxel es mayor que el umbral, se le asignará un valor de 255; de lo contrario, 0. |


**Example: The following example binarizes a GIF image with the predefined threshold.**
El siguiente ejemplo binariza una imagen GIF con el umbral predefinido. Las imágenes binarizadas contienen solo 2 colores: negro y blanco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage djvuImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Binariza la imagen con un valor de umbral de 127.
    // Si el valor gris correspondiente de un píxel es mayor que 127, se le asignará un valor de 255, 0 en caso contrario.
    djvuImage.binarizeFixed((byte) 127);
    djvuImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


La binarización de una imagen con umbralización Otsu es un método utilizado para determinar automáticamente el valor de umbral óptimo para convertir una imagen en escala de grises en una imagen binaria. El algoritmo de umbralización Otsu calcula el umbral que minimiza la varianza intra-clase de las intensidades de los píxeles en las dos clases resultantes (primer plano y fondo). Esta técnica es particularmente útil cuando el valor de umbral óptimo es desconocido y necesita determinarse de forma adaptativa basándose en el histograma de la imagen.


**Example: The following example binarizes a GIF image with Otsu thresholding.**
El siguiente ejemplo binariza una imagen GIF con umbralización Otsu. Las imágenes binarizadas contienen solo 2 colores: negro y blanco.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Binariza la imagen con umbralización de Otsu.
    gifImage.binarizeOtsu();
    gifImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


La binarización de una imagen usando el algoritmo de umbralización adaptativa de Bradley con umbralización por imagen integral es un método para convertir una imagen en escala de grises en una imagen binaria. Este algoritmo calcula un umbral local para cada píxel basado en la intensidad promedio de los píxeles circundantes dentro de una ventana especificada. Al ajustar adaptativamente el umbral según las intensidades locales de los píxeles, el método de Bradley es eficaz para manejar variaciones de iluminación y contraste en la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightnessDifference | double | La diferencia de brillo entre el píxel y el promedio de una ventana de s x s píxeles centrada en este píxel. |

### orderBlocks() {#orderBlocks--}
```
public void orderBlocks()
```


Ordenar los bloques GIF de acuerdo con la especificación GIF garantiza una disposición adecuada del GIF y el cumplimiento del estándar. Este proceso implica organizar los bloques en la secuencia correcta según lo definido por la especificación. Además, puede implicar la eliminación de ciertas instancias de [GifGraphicsControlBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) que no son necesarias para la disposición final. Al adherirse a la especificación GIF, la imagen resultante estará estructurada correctamente y será compatible con las aplicaciones de visualización de GIF.

### clearBlocks() {#clearBlocks--}
```
public void clearBlocks()
```


Limpiar todos los bloques GIF elimina cualquier dato existente almacenado dentro de la imagen. Esta operación restablece efectivamente la imagen a un estado vacío, eliminando cualquier bloque añadido previamente. Use este método cuando necesite comenzar de nuevo con una hoja limpia para crear o modificar una imagen GIF.


**Example: The following example shows how to remove all blocks from a GIF image.**

``` java
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }

    System.out.println("Clear all the blocks");
    gifImage.clearBlocks();

    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}

// La salida se ve así:
// Tamaño del fotograma activo: { Width = 100, Height = 100}
// Borrar todos los bloques
// El fotograma activo no está establecido
```

### insertBlock(int index, IGifBlock block) {#insertBlock-int-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void insertBlock(int index, IGifBlock block)
```


Insertar un nuevo bloque GIF le permite agregar datos personalizados en una posición específica dentro de la imagen. Este método le permite colocar bloques personalizados en la ubicación deseada en la imagen GIF, proporcionando flexibilidad en la organización y estructuración de los datos de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El elemento basado en cero, en el que se insertará el bloque. |
| block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | El bloque GIF a agregar. |

### addBlock(IGifBlock block) {#addBlock-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void addBlock(IGifBlock block)
```


Agregar un nuevo bloque GIF le permite incluir datos adicionales dentro de la imagen. Este método le permite anexar bloques personalizados al GIF, los cuales pueden contener varios tipos de información.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | El bloque GIF a agregar. |


**Example: The following example shows how to compose an animated GIF image from individual GIF blocks.**

``` java
String dir = "c:\\temp\\";

// Crear una imagen GIF de 100 x 100 px.
// El primer bloque es completamente negro por defecto.
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    // El primer círculo es rojo
    com.aspose.imaging.brushes.SolidBrush brush1 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    // El segundo círculo es negro
    com.aspose.imaging.brushes.SolidBrush brush2 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getBlack());

    // Aumenta gradualmente el ángulo de la forma de arco rojo.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock block = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);

        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(block);
        gr.fillPie(brush1, block.getBounds(), 0, angle);

        gifImage.addBlock(block);
    }

    // Aumenta gradualmente el ángulo del arco negro y elimina el arco rojo.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock block = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);

        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(block);
        gr.fillPie(brush2, block.getBounds(), 0, angle);
        gr.fillPie(brush1, block.getBounds(), angle, 360 - angle);

        gifImage.addBlock(block);
    }

    gifImage.save(dir + "animated_radar.gif");
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}
```

### removeBlock(IGifBlock block) {#removeBlock-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void removeBlock(IGifBlock block)
```


Eliminar un bloque GIF elimina datos específicos de la imagen, ofreciendo la capacidad de limpiar o modificar la estructura de la imagen. Este método le permite eliminar bloques no deseados o innecesarios, optimizando la imagen GIF para un almacenamiento eficiente. Utilice esta funcionalidad para eliminar información desactualizada de la imagen mientras preserva su integridad y calidad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | El bloque a eliminar. |

--------------------

Nota: no olvide llamar a Dispose al bloque si no lo va a agregar a otra GifImage. |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public void resizeProportional(int newWidth, int newHeight, int resizeType)
```


El redimensionado proporcional mantiene la relación de aspecto de la imagen mientras ajusta su tamaño, asegurando que la imagen no aparezca estirada o distorsionada. Este método redimensiona la imagen proporcionalmente, escalando tanto el ancho como la altura por el mismo factor. El redimensionado proporcional ajustará cada fotograma según la proporción de `newWidth`/width y `newHeight`/height.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| resizeType | int | El tipo de redimensionado. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Este método rota la imagen alrededor de su punto central. Al especificar el ángulo de rotación, puede girar la imagen en sentido horario o antihorario para lograr la orientación deseada. Esta rotación ayuda a ajustar la presentación o alineación de la imagen sin distorsionar su contenido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación en grados. Los valores positivos girarán en sentido horario. |
| resizeProportionally | boolean | si se establece en `true` el tamaño de su imagen cambiará según las proyecciones del rectángulo girado (puntos de esquina); de lo contrario, se dejarán las dimensiones sin cambios y solo `` el contenido de la imagen será rotado. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Color del fondo. |

