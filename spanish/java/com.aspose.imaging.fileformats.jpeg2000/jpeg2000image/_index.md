---
title: "Jpeg2000Image"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Manipule eficientemente archivos de imagen JPEG2000 JP2 con nuestra API, que admite una variedad de profundidades de bits por píxel y el procesamiento sin problemas de los metadatos XMP que contienen información esencial de la imagen."
type: docs
weight: 12
url: /es/java/com.aspose.imaging.fileformats.jpeg2000/jpeg2000image/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class Jpeg2000Image extends RasterCachedImage
```

Manipule eficientemente archivos de imagen JPEG2000 (JP2) con nuestra API, admitiendo una variedad de profundidades de bits por píxel y el procesamiento sin problemas de los metadatos XMP que contienen información esencial de la imagen. Con capacidades de compresión sin pérdida, garantice una calidad óptima de la imagen mientras mantiene la integridad del archivo, permitiéndole adaptar las imágenes JP2 a sus especificaciones exactas con facilidad.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Jpeg2000Image(String path)](#Jpeg2000Image-java.lang.String-) | Comience a trabajar con la clase [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) inicializando una nueva instancia con la ruta a la imagen que desea cargar. |
| [Jpeg2000Image(String path, int bitsPerPixel)](#Jpeg2000Image-java.lang.String-int-) | Inicie rápidamente con la clase [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) creando una nueva instancia con la ruta del archivo y el parámetro de bits por píxel deseado. |
| [Jpeg2000Image(InputStream stream)](#Jpeg2000Image-java.io.InputStream-) | Inicialice fácilmente una nueva instancia de la clase [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) proporcionando un objeto de flujo. |
| [Jpeg2000Image(InputStream stream, int bitsPerPixel)](#Jpeg2000Image-java.io.InputStream-int-) | Inicialice una nueva instancia de la clase [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) con un flujo para cargar la imagen, junto con los parámetros de bits por píxel. |
| [Jpeg2000Image(int width, int height)](#Jpeg2000Image-int-int-) | Cree una nueva instancia de la clase [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), especificando los parámetros de ancho y alto. |
| [Jpeg2000Image(int width, int height, Jpeg2000Options options)](#Jpeg2000Image-int-int-com.aspose.imaging.imageoptions.Jpeg2000Options-) | Instancie un nuevo objeto [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), proporcionando los parámetros de ancho, alto y opciones de imagen. |
| [Jpeg2000Image(int width, int height, int bitsCount)](#Jpeg2000Image-int-int-int-) | Cree una nueva instancia de la clase [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) con parámetros de ancho, alto y recuento de bits. |
| [Jpeg2000Image(RasterImage image)](#Jpeg2000Image-com.aspose.imaging.RasterImage-) | Instancie una nueva clase [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) con una imagen raster. |
| [Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)](#Jpeg2000Image-com.aspose.imaging.RasterImage-int-) | Inicialice una nueva instancia de [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) con una imagen raster y parámetros de bits por píxel. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Recupere el formato del archivo de imagen. |
| [getRawDataFormat()](#getRawDataFormat--) | Esta propiedad recupera el formato de datos sin procesar de la imagen. |
| [getRawLineSize()](#getRawLineSize--) | Esta propiedad recupera el tamaño de una única línea de datos de imagen sin procesar en bytes. |
| [getWidth()](#getWidth--) | Esta propiedad devuelve el ancho de la imagen en píxeles. |
| [getHeight()](#getHeight--) | Esta propiedad recupera la altura de la imagen en píxeles. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Esta propiedad devuelve la profundidad de la imagen, medida en bits por píxel (bpp). |
| [getHorizontalResolution()](#getHorizontalResolution--) | Esta propiedad le permite recuperar o modificar la resolución horizontal del [RasterImage](../../com.aspose.imaging/rasterimage), medida en píxeles por pulgada (PPI). |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Esta propiedad le permite recuperar o modificar la resolución horizontal del [RasterImage](../../com.aspose.imaging/rasterimage), medida en píxeles por pulgada (PPI). |
| [getVerticalResolution()](#getVerticalResolution--) | Esta propiedad proporciona acceso a la resolución vertical del [RasterImage](../../com.aspose.imaging/rasterimage), medida en píxeles por pulgada (PPI). |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Esta propiedad proporciona acceso a la resolución vertical del [RasterImage](../../com.aspose.imaging/rasterimage), medida en píxeles por pulgada (PPI). |
| [getComments()](#getComments--) | Esta propiedad permite recuperar o actualizar los comentarios asociados a la imagen. |
| [setComments(String[] value)](#setComments-java.lang.String---) | Esta propiedad permite recuperar o actualizar los comentarios asociados a la imagen. |
| [getCodec()](#getCodec--) | Esta propiedad recupera el códec JPEG2000 asociado a la imagen. |
| [getOriginalOptions()](#getOriginalOptions--) | Recupere las opciones de imagen basándose en la configuración original del archivo. |

## Example: This example shows how to load a JPEG2000 image from a file and save it to PNG.

``` java
String dir = "c:\\temp\\";

// Cargue una imagen JPEG2000.
com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = new com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image(dir + "sample.jp2");
try {
    // Guardar como PNG
    jpeg2000Image.save(dir + "sample.output.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    jpeg2000Image.dispose();
}
```

### Jpeg2000Image(String path) {#Jpeg2000Image-java.lang.String-}
```
public Jpeg2000Image(String path)
```


Comience a trabajar con la clase [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) inicializando una nueva instancia con la ruta a la imagen que desea cargar. Este constructor permite un acceso fácil a las imágenes JPEG2000, simplificando el proceso de carga y manejo de archivos de imagen. Al proporcionar la ruta del archivo, puede comenzar rápidamente a procesar y manipular imágenes JPEG2000 en su aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | java.lang.String | La ruta desde la cual cargar la imagen e inicializar los datos de píxeles y paleta. |

### Jpeg2000Image(String path, int bitsPerPixel) {#Jpeg2000Image-java.lang.String-int-}
```
public Jpeg2000Image(String path, int bitsPerPixel)
```


Comience fácilmente con la clase [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) creando una nueva instancia con la ruta del archivo y el parámetro de bits por píxel deseado. Este constructor permite afinar el proceso de carga de la imagen, garantizando la compatibilidad con varios formatos de imagen y configuraciones de calidad. Con esta flexibilidad, puede gestionar y manipular eficientemente imágenes JPEG2000 según sus requisitos específicos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | java.lang.String | La ruta desde la cual cargar la imagen e inicializar los datos de píxeles y paleta |
| bitsPerPixel | int | Los bits por píxel. |

### Jpeg2000Image(InputStream stream) {#Jpeg2000Image-java.io.InputStream-}
```
public Jpeg2000Image(InputStream stream)
```


Inicialice fácilmente una nueva instancia de la clase [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) proporcionando un objeto de flujo. Este constructor simplifica el proceso de carga de imágenes JPEG2000 directamente desde flujos, ofreciendo flexibilidad y comodidad para manejar datos de imagen provenientes de diversas fuentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo desde el cual cargar la imagen e inicializar los datos de píxeles y paleta. |

### Jpeg2000Image(InputStream stream, int bitsPerPixel) {#Jpeg2000Image-java.io.InputStream-int-}
```
public Jpeg2000Image(InputStream stream, int bitsPerPixel)
```


Inicialice una nueva instancia de la clase [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) con un flujo para cargar la imagen, junto con los parámetros de bits por píxel. Este constructor ofrece flexibilidad al permitir especificar tanto la fuente de datos de la imagen como los bits por píxel deseados, proporcionando un control más fino sobre el proceso de carga de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo desde el cual cargar la imagen e inicializar los datos de píxeles y paleta. |
| bitsPerPixel | int | Los bits por píxel. |

### Jpeg2000Image(int width, int height) {#Jpeg2000Image-int-int-}
```
public Jpeg2000Image(int width, int height)
```


Cree una nueva instancia de la clase [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), especificando los parámetros de ancho y alto. Este constructor le permite inicializar una imagen JPEG2000 con dimensiones específicas, lo que resulta útil en escenarios donde necesita crear una imagen de un tamaño determinado de forma programática.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho de la imagen |
| height | int | El alto de la imagen |

### Jpeg2000Image(int width, int height, Jpeg2000Options options) {#Jpeg2000Image-int-int-com.aspose.imaging.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```


Instancie un nuevo objeto [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image), proporcionando los parámetros de ancho, alto y opciones de imagen. Este constructor permite la creación de imágenes JPEG2000 con dimensiones específicas y opciones adicionales, ofreciendo flexibilidad en la generación de imágenes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho de la imagen |
| height | int | El alto de la imagen |
| options | [Jpeg2000Options](../../com.aspose.imaging.imageoptions/jpeg2000options) | Las opciones. |

### Jpeg2000Image(int width, int height, int bitsCount) {#Jpeg2000Image-int-int-int-}
```
public Jpeg2000Image(int width, int height, int bitsCount)
```


Cree una nueva instancia de la clase [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) con parámetros de ancho, alto y recuento de bits. Este constructor permite la creación de imágenes JPEG2000 con dimensiones específicas y profundidades de bits, proporcionando flexibilidad para diversas necesidades de imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho de la imagen |
| height | int | El alto de la imagen |
| bitsCount | int | El recuento de bits. |

### Jpeg2000Image(RasterImage image) {#Jpeg2000Image-com.aspose.imaging.RasterImage-}
```
public Jpeg2000Image(RasterImage image)
```


Instancie una nueva clase [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) con una imagen raster. Este constructor facilita la creación de una imagen JPEG2000 a partir de una imagen raster existente, ofreciendo una integración y conversión sin problemas entre diferentes formatos de imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen. |

### Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel) {#Jpeg2000Image-com.aspose.imaging.RasterImage-int-}
```
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```


Inicializa una nueva instancia de [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) con una imagen raster y parámetros de bits por píxel. Este constructor permite un control preciso sobre la calidad y el tamaño de la imagen JPEG2000 resultante, lo que lo hace ideal para escenarios donde la personalización es crucial.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen con la que se inicializan los datos de píxeles y paleta. |
| bitsPerPixel | int | Los bits por píxel. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Obtenga el formato del archivo de imagen. Esta propiedad proporciona información sobre el formato de archivo de la imagen. Utilice esta propiedad para determinar programáticamente el formato del archivo de imagen, facilitando el manejo y procesamiento adecuados según el formato del archivo.

**Returns:**
long
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Esta propiedad recupera el formato de datos sin procesar de la imagen. Proporciona información sobre cómo se almacenan los datos de píxeles en la memoria. Use esta propiedad para comprender el formato de datos subyacente de la imagen, lo que puede ser crucial para diversas operaciones de procesamiento de imágenes como conversión de color, compresión o descompresión.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Esta propiedad recupera el tamaño de una sola línea de datos sin procesar de la imagen en bytes. Indica la cantidad de memoria ocupada por una fila única de píxeles en el formato de datos sin procesar de la imagen. Comprender el tamaño de la línea sin procesar es esencial para tareas como la asignación de memoria, la manipulación de datos y los algoritmos de procesamiento de imágenes que operan sobre líneas individuales.

**Returns:**
int - El tamaño de línea sin procesar en bytes.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Esta propiedad devuelve el ancho de la imagen en píxeles. Proporciona una información fundamental sobre las dimensiones de la imagen, crucial para diversas tareas de procesamiento de imágenes, incluyendo redimensionado, recorte y renderizado.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Esta propiedad recupera la altura de la imagen en píxeles. Sirve como información esencial para comprender las dimensiones verticales de la imagen, ayudando en diversas tareas de manipulación de imágenes como redimensionado, recorte y renderizado. Acceder a esta propiedad permite a los usuarios determinar el tamaño vertical de la imagen, habilitando un diseño y visualización precisos en las aplicaciones.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Esta propiedad devuelve la profundidad de la imagen, medida en bits por píxel (bpp). Indica la cantidad de información de color almacenada en cada píxel de la imagen. Comprender la profundidad de la imagen es crucial para determinar la fidelidad del color y la calidad de la imagen. Con esta información, los usuarios pueden evaluar el nivel de detalle y la riqueza de colores presentes en la imagen.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Esta propiedad le permite recuperar o modificar la resolución horizontal del [RasterImage](../../com.aspose.imaging/rasterimage), medida en píxeles por pulgada (PPI). Ajustar esta resolución puede afectar el tamaño y la calidad de la imagen al imprimirse o mostrarse. Al establecer la resolución horizontal, los usuarios pueden optimizar la imagen para dispositivos de salida o aplicaciones específicas, garantizando los mejores resultados visuales posibles.

**Returns:**
double - La resolución horizontal.

Nota: por defecto este valor siempre es 96 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG2000 image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jp2");
try {
    com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = (com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image) image;

    // Obtenga la resolución horizontal y vertical del Jpeg2000Image.
    double horizontalResolution = jpeg2000Image.getHorizontalResolution();
    double verticalResolution = jpeg2000Image.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilice el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
        System.out.println("Set resolution values to 96 dpi");
        jpeg2000Image.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpeg2000Image.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpeg2000Image.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// La salida puede verse así:
// La resolución horizontal, en píxeles por pulgada: 72.0
// La resolución vertical, en píxeles por pulgada: 72.0
// Establecer los valores de resolución a 96 dpi
// La resolución horizontal, en píxeles por pulgada: 72.0
// La resolución vertical, en píxeles por pulgada: 72.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Esta propiedad le permite recuperar o modificar la resolución horizontal del [RasterImage](../../com.aspose.imaging/rasterimage), medida en píxeles por pulgada (PPI). Ajustar esta resolución puede afectar el tamaño y la calidad de la imagen al imprimirse o mostrarse. Al establecer la resolución horizontal, los usuarios pueden optimizar la imagen para dispositivos de salida o aplicaciones específicas, garantizando los mejores resultados visuales posibles.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | La resolución horizontal. |

Nota: por defecto este valor siempre es 96 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Esta propiedad brinda acceso a la resolución vertical del [RasterImage](../../com.aspose.imaging/rasterimage), medida en píxeles por pulgada (PPI). Modificar esta resolución puede afectar la calidad y el tamaño de la imagen al imprimirse o mostrarse. Al ajustar la resolución vertical, los usuarios pueden optimizar la imagen para diferentes dispositivos de salida o aplicaciones, garantizando una representación visual óptima.

**Returns:**
double - La resolución vertical.

Nota: por defecto este valor siempre es 96 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG2000 image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jp2");
try {
    com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = (com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image) image;

    // Obtenga la resolución horizontal y vertical del Jpeg2000Image.
    double horizontalResolution = jpeg2000Image.getHorizontalResolution();
    double verticalResolution = jpeg2000Image.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilice el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
        System.out.println("Set resolution values to 96 dpi");
        jpeg2000Image.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpeg2000Image.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpeg2000Image.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// La salida puede verse así:
// La resolución horizontal, en píxeles por pulgada: 72.0
// La resolución vertical, en píxeles por pulgada: 72.0
// Establecer los valores de resolución a 96 dpi
// La resolución horizontal, en píxeles por pulgada: 72.0
// La resolución vertical, en píxeles por pulgada: 72.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Esta propiedad brinda acceso a la resolución vertical del [RasterImage](../../com.aspose.imaging/rasterimage), medida en píxeles por pulgada (PPI). Modificar esta resolución puede afectar la calidad y el tamaño de la imagen al imprimirse o mostrarse. Al ajustar la resolución vertical, los usuarios pueden optimizar la imagen para diferentes dispositivos de salida o aplicaciones, garantizando una representación visual óptima.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | La resolución vertical. |

Nota: por defecto este valor siempre es 96 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada. |

### getComments() {#getComments--}
```
public String[] getComments()
```


Esta propiedad permite recuperar o actualizar los comentarios asociados a la imagen. Los comentarios proporcionan información adicional sobre el contenido de la imagen, como anotaciones, descripciones o metadatos. Modificar estos comentarios puede ser útil para organizar y categorizar imágenes, así como para transmitir detalles importantes a los espectadores o usuarios.

**Returns:**
java.lang.String[] - Los comentarios.
### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


Esta propiedad permite recuperar o actualizar los comentarios asociados a la imagen. Los comentarios proporcionan información adicional sobre el contenido de la imagen, como anotaciones, descripciones o metadatos. Modificar estos comentarios puede ser útil para organizar y categorizar imágenes, así como para transmitir detalles importantes a los espectadores o usuarios.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String[] | Los comentarios. |

### getCodec() {#getCodec--}
```
public int getCodec()
```


Esta propiedad recupera el códec JPEG2000 asociado a la imagen. El códec JPEG2000 es responsable de codificar y decodificar los datos de la imagen en el formato JPEG2000, proporcionando compresión eficiente mientras mantiene alta calidad de imagen. Acceder a este códec puede ser útil para realizar operaciones avanzadas de procesamiento de imágenes u optimizar la configuración de compresión de imágenes adaptada a requisitos específicos.

**Returns:**
int - El códec.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Recupere las opciones de imagen basadas en la configuración del archivo original. Este método es útil para mantener la profundidad de bits y otros parámetros de la imagen original, garantizando consistencia y preservando la integridad de los datos de la imagen. Acceder a estas opciones facilita el manejo y procesamiento sin problemas de la imagen mientras se conservan sus características originales. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el método [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), se producirá una imagen PNG de salida con 8 bits por píxel. Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas al método [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) como segundo parámetro.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
