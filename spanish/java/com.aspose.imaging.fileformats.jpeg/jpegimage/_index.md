---
title: "JpegImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Manipule eficientemente imágenes raster JPEG con nuestra API, ofreciendo soporte para varios perfiles de color como RGB y CMYK, bits personalizables por píxel y procesamiento de contenedores de metadatos EXIF, JFIF y XMP."
type: docs
weight: 14
url: /es/java/com.aspose.imaging.fileformats.jpeg/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasJpegExifData](../../com.aspose.imaging.exif/ihasjpegexifdata)
```
public final class JpegImage extends RasterCachedImage implements IHasJpegExifData
```

Manipule eficientemente imágenes raster JPEG con nuestra API, ofreciendo soporte para varios perfiles de color como RGB y CMYK, bits personalizables por píxel y procesamiento de contenedores de metadatos EXIF, JFIF y XMP. Disfrute de rotación automática basada en datos de orientación y elija entre diferentes niveles de compresión, incluido JPEG sin pérdida, para lograr un equilibrio óptimo entre calidad de imagen y tamaño de archivo en sus proyectos.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [JpegImage(String path)](#JpegImage-java.lang.String-) | La clase [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) se inicia sin esfuerzo invocando su constructor con el parámetro de ruta especificado. |
| [JpegImage(InputStream stream)](#JpegImage-java.io.InputStream-) | Inicialice un objeto de imagen JPEG con la clase [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) usando un parámetro de flujo. |
| [JpegImage(RasterImage rasterImage)](#JpegImage-com.aspose.imaging.RasterImage-) | Inicialice una nueva instancia de la clase [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) con un parámetro de imagen raster. |
| [JpegImage(int width, int height)](#JpegImage-int-int-) | Cree una nueva instancia de la clase [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) con los parámetros de ancho y alto especificados. |
| [JpegImage(JpegOptions jpegOptions, int width, int height)](#JpegImage-com.aspose.imaging.imageoptions.JpegOptions-int-int-) | Inicialice un nuevo objeto [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) con las opciones JPEG proporcionadas. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Recupere el formato de la imagen sin esfuerzo con esta propiedad. |
| [getJpegOptions()](#getJpegOptions--) | Obtenga acceso a las opciones JPEG utilizadas durante la creación o carga de esta instancia de [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) con facilidad. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Recupere la profundidad de píxeles de la imagen sin esfuerzo con esta propiedad, ofreciendo información sobre la riqueza de la representación en color o escala de grises. |
| [getComment()](#getComment--) | Gestione los comentarios de archivos JPEG con esta propiedad, lo que le permite agregar o recuperar anotaciones descriptivas asociadas a la imagen. |
| [setComment(String value)](#setComment-java.lang.String-) | Gestione los comentarios de archivos JPEG con esta propiedad, lo que le permite agregar o recuperar anotaciones descriptivas asociadas a la imagen. |
| [getJpegExifData()](#getJpegExifData--) | Obtiene la instancia Exif. |
| [setJpegExifData(JpegExifData value)](#setJpegExifData-com.aspose.imaging.exif.JpegExifData-) | Gestione los datos EXIF con esta propiedad, lo que le permite agregar o recuperar metadatos asociados a la imagen. |
| [getExifData()](#getExifData--) | Obtiene datos Exif; |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Establece datos Exif; |
| [getHeight()](#getHeight--) | Recupere sin esfuerzo la altura de la imagen con esta propiedad. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Esta propiedad le brinda acceso a la resolución horizontal del [RasterImage](../../com.aspose.imaging/rasterimage), medida en píxeles por pulgada. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Esta propiedad le brinda acceso a la resolución horizontal del [RasterImage](../../com.aspose.imaging/rasterimage), medida en píxeles por pulgada. |
| [getJfif()](#getJfif--) | Esta propiedad le permite acceder o modificar los datos JFIF (Formato de Intercambio de Archivos JPEG) asociados a la imagen JPEG. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-) | Esta propiedad le permite acceder o modificar los datos JFIF (Formato de Intercambio de Archivos JPEG) asociados a la imagen JPEG. |
| [getRawDataFormat()](#getRawDataFormat--) | Esta propiedad recupera el formato de datos sin procesar de la imagen, lo que indica cómo están estructurados y codificados los datos de la imagen. |
| [getVerticalResolution()](#getVerticalResolution--) | Esta propiedad gestiona la resolución vertical, expresada en píxeles por pulgada, para el [RasterImage](../../com.aspose.imaging/rasterimage) asociado. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Esta propiedad gestiona la resolución vertical, expresada en píxeles por pulgada, para el [RasterImage](../../com.aspose.imaging/rasterimage) asociado. |
| [getWidth()](#getWidth--) | Esta propiedad recupera el ancho de la imagen, expresado en píxeles. |
| [getRgbColorProfile()](#getRgbColorProfile--) | El perfil de color RGB para imágenes JPEG CMYK y YCCK garantiza una conversión y representación de color precisas. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | El perfil de color RGB para imágenes JPEG CMYK y YCCK garantiza una conversión y representación de color precisas. |
| [getCmykColorProfile()](#getCmykColorProfile--) | El perfil de color CMYK asociado con imágenes JPEG CMYK y YCCK asegura una conversión de color precisa y fidelidad. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | El perfil de color CMYK asociado con imágenes JPEG CMYK y YCCK asegura una conversión de color precisa y fidelidad. |
| [getDestinationRgbColorProfile()](#getDestinationRgbColorProfile--) | El RGBColorProfile es esencial para la conversión de color precisa de imágenes JPEG CMYK y YCCK durante el proceso de guardado. |
| [setDestinationRgbColorProfile(StreamSource value)](#setDestinationRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | El RGBColorProfile es esencial para la conversión de color precisa de imágenes JPEG CMYK y YCCK durante el proceso de guardado. |
| [getDestinationCmykColorProfile()](#getDestinationCmykColorProfile--) | El perfil de color CMYK es vital para la conversión de color precisa de imágenes JPEG CMYK y YCCK durante el proceso de guardado. |
| [setDestinationCmykColorProfile(StreamSource value)](#setDestinationCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | El perfil de color CMYK es vital para la conversión de color precisa de imágenes JPEG CMYK y YCCK durante el proceso de guardado. |
| [getIgnoreEmbeddedColorProfile()](#getIgnoreEmbeddedColorProfile--) | Recupera o modifica la bandera que indica si se ignora el perfil de color incrustado. |
| [setIgnoreEmbeddedColorProfile(boolean value)](#setIgnoreEmbeddedColorProfile-boolean-) | Recupera o modifica la bandera que indica si se ignora el perfil de color incrustado. |
| [getOriginalOptions()](#getOriginalOptions--) | Obtiene las opciones originales de imagen de esta instancia de [Image](../../com.aspose.imaging/image). |
| [removeMetadata()](#removeMetadata--) | Elimina los metadatos de esta instancia de imagen estableciendo los valores de `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) y `IHasExifData.ExifData`([IHasExifData.getExifData()](../../com.aspose.imaging.exif/ihasexifdata\#getExifData--)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-)) a `null`. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Establece la resolución para el [RasterImage](../../com.aspose.imaging/rasterimage) especificado, garantizando una escala y capacidades de impresión precisas. |

## Example: The example shows how to load a JpegImage from a file.

``` java
String dir = "c:\\temp\\";

// Cargue una imagen JPEG desde un archivo.
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(dir + "sample.jpg");
try {
    // Realizar algún procesamiento de imagen.
    // Guarde en otro archivo JPEG.
    jpegImage.save(dir + "sample.output.jpg");
} finally {
    jpegImage.dispose();
}
```


## Example: Access camera manufacturer maker notes in Jpeg image.

``` java
try (JpegImage image = (JpegImage)Image.load("Sample.jpg"))
{
    for (MakerNote makerNote : image.getExifData().getMakerNotes())
    {
        System.out.format("Name = %s, Value = %s", makerNote.getName(), makerNote.getValue());
    }
}
```

### JpegImage(String path) {#JpegImage-java.lang.String-}
```
public JpegImage(String path)
```


La clase [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) se inicia sin esfuerzo al invocar su constructor con el parámetro de ruta especificado. Este constructor permite la creación fluida de imágenes JPEG, garantizando una integración rápida en sus proyectos con facilidad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | java.lang.String | La ruta desde la cual cargar la imagen e inicializar los datos de píxeles y paleta. |

### JpegImage(InputStream stream) {#JpegImage-java.io.InputStream-}
```
public JpegImage(InputStream stream)
```


Inicialice un objeto de imagen JPEG con la clase [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) utilizando un parámetro de flujo. Este constructor simplifica el proceso de trabajo con imágenes JPEG, ofreciendo un enfoque sencillo para integrar sus proyectos sin esfuerzo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo desde el cual cargar la imagen e inicializar los datos de píxeles y paleta. |

### JpegImage(RasterImage rasterImage) {#JpegImage-com.aspose.imaging.RasterImage-}
```
public JpegImage(RasterImage rasterImage)
```


Inicializa una nueva instancia de la clase [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) con un parámetro de imagen raster. Este constructor ofrece una forma conveniente de crear imágenes JPEG directamente a partir de imágenes raster, optimizando el flujo de trabajo para trabajar con imágenes JPEG en sus aplicaciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen con la que se inicializan los datos de píxeles y paleta. |

### JpegImage(int width, int height) {#JpegImage-int-int-}
```
public JpegImage(int width, int height)
```


Crea una nueva instancia de la clase [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) con los parámetros de ancho y alto especificados. Este constructor le permite crear imágenes JPEG con dimensiones personalizadas, brindándole flexibilidad para gestionar los tamaños de imagen en su aplicación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho de la imagen. |
| height | int | La altura de la imagen. |

### JpegImage(JpegOptions jpegOptions, int width, int height) {#JpegImage-com.aspose.imaging.imageoptions.JpegOptions-int-int-}
```
public JpegImage(JpegOptions jpegOptions, int width, int height)
```


Inicializa un nuevo objeto [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) con las opciones JPEG proporcionadas. Este constructor le permite personalizar diversas configuraciones para la imagen JPEG, como el nivel de compresión, la calidad y parámetros adicionales, otorgándole un control preciso sobre el formato de imagen resultante.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) | Las opciones JPEG. |
| width | int | Ancho de imagen. |
| height | int | Altura de la imagen. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Recupere el formato de la imagen sin esfuerzo con esta propiedad. Proporciona información valiosa sobre el formato de archivo, facilitando la integración fluida y las verificaciones de compatibilidad en diversas plataformas y aplicaciones.

**Returns:**
long
### getJpegOptions() {#getJpegOptions--}
```
public JpegOptions getJpegOptions()
```


Obtenga acceso a las opciones JPEG utilizadas durante la creación o carga de esta instancia [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) con facilidad. Esta propiedad ofrece detalles valiosos sobre la configuración específica empleada, permitiendo a los usuarios comprender y replicar los flujos de trabajo de procesamiento de imágenes de manera eficaz. Ya sean niveles de compresión, configuraciones de calidad u otros parámetros, esta propiedad brinda información esencial para una manipulación de imágenes sin problemas.

**Returns:**
[JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) - The JPEG options.

**Example: The following example shows how to extract the header information from a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.jpeg.JpegImage image = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "original.jpg");
try {
    com.aspose.imaging.imageoptions.JpegOptions jpegOptions = image.getJpegOptions();

    System.out.println("The number of bits per channel: " + jpegOptions.getBitsPerChannel());
    System.out.println("The max allowed size for all internal buffers: " + jpegOptions.getBufferSizeHint());
    System.out.println("The color type: " + jpegOptions.getColorType());
    System.out.println("The compression type: " + jpegOptions.getCompressionType());
    System.out.println("The image quality: " + jpegOptions.getQuality());

    if (jpegOptions.getResolutionSettings() != null) {
        System.out.println("The horizontal resolution: " + jpegOptions.getResolutionSettings().getHorizontalResolution());
        System.out.println("The vertical resolution: " + jpegOptions.getResolutionSettings().getVerticalResolution());
    }

    for (int i = 0; i < jpegOptions.getHorizontalSampling().length; i++) {
        System.out.printf("The sampling for component %s: %sx%s\r\n", i, jpegOptions.getHorizontalSampling()[i], jpegOptions.getVerticalSampling()[i]);
    }
} finally {
    image.dispose();
}

//La salida se ve así:
//El número de bits por canal: 8
//El tamaño máximo permitido para todos los búferes internos: 0
//El tipo de color: YCbCr
//El tipo de compresión: Baseline
//La calidad de la imagen: 75
//El muestreo para el componente 0: 1x1
//El muestreo para el componente 1: 1x1
//El muestreo para el componente 2: 1x1
```

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Recupere la profundidad de píxeles de la imagen sin esfuerzo con esta propiedad, ofreciendo información sobre la riqueza de la representación en color o escala de grises. Ya sea una fotografía vibrante o una ilustración monocromática, esta propiedad brinda información crucial sobre la complejidad visual de la imagen.

**Returns:**
int - El recuento de bits por píxel de la imagen.
### getComment() {#getComment--}
```
public String getComment()
```


Gestione los comentarios de archivos JPEG con esta propiedad, permitiéndole agregar o recuperar anotaciones descriptivas asociadas a la imagen. Ya sea etiquetando imágenes con metadatos o añadiendo contexto adicional, esta propiedad ofrece flexibilidad para organizar y categorizar sus archivos JPEG.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Gestione los comentarios de archivos JPEG con esta propiedad, permitiéndole agregar o recuperar anotaciones descriptivas asociadas a la imagen. Ya sea etiquetando imágenes con metadatos o añadiendo contexto adicional, esta propiedad ofrece flexibilidad para organizar y categorizar sus archivos JPEG.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getJpegExifData() {#getJpegExifData--}
```
public JpegExifData getJpegExifData()
```


Obtiene la instancia Exif.

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif instance.
### setJpegExifData(JpegExifData value) {#setJpegExifData-com.aspose.imaging.exif.JpegExifData-}
```
public void setJpegExifData(JpegExifData value)
```


Gestione los datos EXIF con esta propiedad, permitiéndole agregar o recuperar metadatos asociados a la imagen. Ya sea extrayendo información sobre la configuración de la cámara o modificando metadatos existentes, esta propiedad brinda flexibilidad en la gestión del contenedor de datos EXIF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) |  |

### getExifData() {#getExifData--}
```
public JpegExifData getExifData()
```


Obtiene datos Exif;

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif data;

**Example: The following example shows how to extract EXIF tags from a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.jpeg.JpegImage image = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "original.jpg");
try {
    com.aspose.imaging.exif.ExifData exifData = image.getExifData();

    System.out.println("The general EXIF data");
    System.out.println("------------------------------------------");
    if (exifData != null) {
        System.out.println("The EXIF version: " + exifData.getExifVersion());
        System.out.println("The camera serial number: " + exifData.getBodySerialNumber());
        System.out.println("The color space: " + exifData.getColorSpace());
        System.out.println("The brightness: " + exifData.getBrightnessValue());
        System.out.println("The contrast: " + exifData.getContrast());
        System.out.println("The gamma: " + exifData.getGamma());
        System.out.println("The sharpness: " + exifData.getSharpness());
        System.out.println("The aperture: " + exifData.getApertureValue());
        System.out.println("The exposure mode: " + exifData.getExposureMode());
        System.out.println("The exposure bias: " + exifData.getExposureBiasValue());
        System.out.println("The exposure time: " + exifData.getExposureTime());
        System.out.println("The focal length: " + exifData.getFocalLength());
        System.out.println("The focal plane resolution unit: " + exifData.getFocalPlaneResolutionUnit());
        System.out.println("The lens model: " + exifData.getLensModel());
        System.out.println("The shutter speed: " + exifData.getShutterSpeedValue());
    }

    System.out.println("The JPEG EXIF data");
    System.out.println("------------------------------------------");
    if (exifData instanceof com.aspose.imaging.exif.JpegExifData) {
        com.aspose.imaging.exif.JpegExifData jpegExifData = (com.aspose.imaging.exif.JpegExifData) exifData;

        System.out.println("The camera manufacturer: " + jpegExifData.getMake());
        System.out.println("The camera model: " + jpegExifData.getModel());
        System.out.println("The photometric interpretation: " + jpegExifData.getPhotometricInterpretation());
        System.out.println("The artist: " + jpegExifData.getArtist());
        System.out.println("The copyright: " + jpegExifData.getCopyright());
        System.out.println("The image description: " + jpegExifData.getImageDescription());
        System.out.println("The orientation: " + jpegExifData.getOrientation());
        System.out.println("The software: " + jpegExifData.getSoftware());
    }
} finally {
    image.dispose();
}

//La salida se ve así:
//Los datos EXIF generales
//------------------------------------------
//La versión EXIF: [B@163e4e87
//El número de serie de la cámara: 7100536
//El espacio de color: SRgb
//El brillo:
//El contraste: Normal
//La gamma:
//La nitidez: 0
//La apertura: 4.64(4643856 / 1000000)
//El modo de exposición: Manual
//El sesgo de exposición: 0.67(4 / 6)
//El tiempo de exposición: 0.01(1 / 160)
//La distancia focal: 145.00(1450 / 10)
//La unidad de resolución del plano focal: Cm
//El modelo de lente: 70.0 - 200.0 mm f/ 4.0
//La velocidad de obturación: 7.32(7321928 / 1000000)
//Los datos EXIF JPEG
//------------------------------------------
//El fabricante de la cámara: NIKON CORPORATION
//El modelo de cámara: NIKON D5
//La interpretación fotométrica: 0
//El artista:
//Los derechos de autor:
//La descripción de la imagen:
//La orientación: TopLeft
//El software: Adobe Photoshop Camera Raw 9.9(Macintosh)
```

### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Establece datos Exif;

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Datos Exif; |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Recupere la altura de la imagen sin esfuerzo con esta propiedad. Proporciona un acceso rápido a la dimensión vertical de la imagen, permitiéndole determinar de manera eficiente su tamaño y relación de aspecto sin necesidad de cálculos complejos ni métodos adicionales.

**Returns:**
int - La altura de la imagen en píxeles.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Esta propiedad le brinda acceso a la resolución horizontal del [RasterImage](../../com.aspose.imaging/rasterimage), medida en píxeles por pulgada. Al establecer o recuperar este valor, puede controlar con precisión la resolución de la imagen, asegurándose de que cumpla con sus requisitos específicos de calidad y claridad.

**Returns:**
double - La resolución horizontal.

Nota: por defecto este valor siempre es 96 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // Obtener la resolución horizontal y vertical del BmpImage
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilice el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// La salida puede verse así:
// La resolución horizontal, en píxeles por pulgada: 300.0
// La resolución vertical, en píxeles por pulgada: 300.0
// Establecer los valores de resolución a 96 dpi
// La resolución horizontal, en píxeles por pulgada: 96.0
// La resolución vertical, en píxeles por pulgada: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Esta propiedad le brinda acceso a la resolución horizontal del [RasterImage](../../com.aspose.imaging/rasterimage), medida en píxeles por pulgada. Al establecer o recuperar este valor, puede controlar con precisión la resolución de la imagen, asegurándose de que cumpla con sus requisitos específicos de calidad y claridad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | La resolución horizontal. |

Nota: por defecto este valor es siempre 96 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método `setResolution` para actualizar ambos valores de resolución en una sola llamada. |

### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


Esta propiedad le permite acceder o modificar los datos JFIF (Formato de Intercambio de Archivos JPEG) asociados con la imagen JPEG. JFIF es un formato estándar para intercambiar imágenes comprimidas en JPEG entre computadoras y otros dispositivos. Al obtener o establecer esta propiedad, puede interactuar con los datos JFIF, que pueden incluir información como la resolución de la imagen, la relación de aspecto y la miniatura.

**Returns:**
[JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata)
### setJfif(JFIFData value) {#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


Esta propiedad le permite acceder o modificar los datos JFIF (Formato de Intercambio de Archivos JPEG) asociados con la imagen JPEG. JFIF es un formato estándar para intercambiar imágenes comprimidas en JPEG entre computadoras y otros dispositivos. Al obtener o establecer esta propiedad, puede interactuar con los datos JFIF, que pueden incluir información como la resolución de la imagen, la relación de aspecto y la miniatura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata) |  |

### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Esta propiedad recupera el formato de datos sin procesar de la imagen, lo que indica cómo están estructurados y codificados los datos de la imagen. Comprender el formato de datos sin procesar es esencial para procesar o manipular los datos de la imagen de manera eficaz. Proporciona información sobre la representación subyacente de la imagen, como si está comprimida, codificada en un espacio de color específico o almacenada en un formato de archivo particular. Acceder a esta propiedad le permite obtener información valiosa sobre la estructura de datos de la imagen, habilitándole a realizar diversas operaciones u optimizaciones adaptadas a su formato específico.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat)
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Esta propiedad gestiona la resolución vertical, expresada en píxeles por pulgada, para el [RasterImage](../../com.aspose.imaging/rasterimage) asociado. Ajustar esta resolución afecta el tamaño y la calidad de la imagen al imprimirse o mostrarse en un tamaño físico fijo. Al establecer esta propiedad, controla cuán densamente se empaquetan verticalmente los píxeles de la imagen, lo que influye en su nitidez y claridad general.

**Returns:**
double - La resolución vertical.

Nota: por defecto este valor es siempre 72 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // Obtener la resolución horizontal y vertical del BmpImage
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilice el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// La salida puede verse así:
// La resolución horizontal, en píxeles por pulgada: 300.0
// La resolución vertical, en píxeles por pulgada: 300.0
// Establecer los valores de resolución a 96 dpi
// La resolución horizontal, en píxeles por pulgada: 96.0
// La resolución vertical, en píxeles por pulgada: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Esta propiedad gestiona la resolución vertical, expresada en píxeles por pulgada, para el [RasterImage](../../com.aspose.imaging/rasterimage) asociado. Ajustar esta resolución afecta el tamaño y la calidad de la imagen al imprimirse o mostrarse en un tamaño físico fijo. Al establecer esta propiedad, controla cuán densamente se empaquetan verticalmente los píxeles de la imagen, lo que influye en su nitidez y claridad general.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | double | La resolución vertical. |

Nota: por defecto este valor es siempre 72 ya que diferentes plataformas no pueden devolver la resolución de pantalla. Puede considerar usar el método SetResolution para actualizar ambos valores de resolución en una sola llamada. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Esta propiedad recupera el ancho de la imagen, expresado en píxeles. Proporciona información esencial sobre las dimensiones de la imagen, permitiendo una renderización, manipulación o visualización precisa de los datos de la imagen.

**Returns:**
int - El ancho de la imagen en píxeles.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


El perfil de color RGB para imágenes JPEG CMYK y YCCK garantiza una conversión y representación de color precisas. Debe combinarse con el CMYKColorProfile para mantener la consistencia y fidelidad en la renderización del color. Esta combinación es esencial para aplicaciones que requieren una gestión y reproducción de color exactas, asegurando que los datos RGB se interpreten y muestren correctamente.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


El perfil de color RGB para imágenes JPEG CMYK y YCCK garantiza una conversión y representación de color precisas. Debe combinarse con el CMYKColorProfile para mantener la consistencia y fidelidad en la renderización del color. Esta combinación es esencial para aplicaciones que requieren una gestión y reproducción de color exactas, asegurando que los datos RGB se interpreten y muestren correctamente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
El siguiente ejemplo carga un PNG y lo guarda como JPEG CMYK usando un perfil ICC personalizado. Luego carga el JPEG CMYK y lo guarda nuevamente como PNG. La conversión de color de RGB a CMYK y de CMYK a RGB se realiza utilizando perfiles ICC personalizados.
``` java
String dir = "c:\\temp\\";

// Cargar PNG y guardarlo como JPEG CMYK
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Usar perfiles ICC personalizados
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// Cargar JPEG CMYK y guardarlo como PNG
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Usar perfiles ICC personalizados
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getCmykColorProfile() {#getCmykColorProfile--}
```
public StreamSource getCmykColorProfile()
```


El perfil de color CMYK asociado a imágenes JPEG CMYK y YCCK garantiza una conversión de color precisa y fidelidad. Funciona en conjunto con el RGBColorProfile para asegurar una representación de color exacta en diversos dispositivos y aplicaciones. Esta combinación es crucial para mantener la consistencia en la renderización del color y lograr una calidad de imagen óptima.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


El perfil de color CMYK asociado a imágenes JPEG CMYK y YCCK garantiza una conversión de color precisa y fidelidad. Funciona en conjunto con el RGBColorProfile para asegurar una representación de color exacta en diversos dispositivos y aplicaciones. Esta combinación es crucial para mantener la consistencia en la renderización del color y lograr una calidad de imagen óptima.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
El siguiente ejemplo carga un PNG y lo guarda como JPEG CMYK usando un perfil ICC personalizado. Luego carga el JPEG CMYK y lo guarda nuevamente como PNG. La conversión de color de RGB a CMYK y de CMYK a RGB se realiza utilizando perfiles ICC personalizados.
``` java
String dir = "c:\\temp\\";

// Cargar PNG y guardarlo como JPEG CMYK
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Usar perfiles ICC personalizados
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// Cargar JPEG CMYK y guardarlo como PNG
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Usar perfiles ICC personalizados
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getDestinationRgbColorProfile() {#getDestinationRgbColorProfile--}
```
public StreamSource getDestinationRgbColorProfile()
```


El RGBColorProfile es esencial para la conversión precisa de color de imágenes JPEG CMYK y YCCK durante el proceso de guardado. Cuando se combina con el CMYKColorProfile, garantiza que los colores se rendericen correctamente y mantiene la consistencia en diferentes dispositivos y aplicaciones. Esta combinación es crucial para preservar la representación de color prevista y lograr una salida de imagen de alta calidad.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setDestinationRgbColorProfile(StreamSource value) {#setDestinationRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setDestinationRgbColorProfile(StreamSource value)
```


El RGBColorProfile es esencial para la conversión precisa de color de imágenes JPEG CMYK y YCCK durante el proceso de guardado. Cuando se combina con el CMYKColorProfile, garantiza que los colores se rendericen correctamente y mantiene la consistencia en diferentes dispositivos y aplicaciones. Esta combinación es crucial para preservar la representación de color prevista y lograr una salida de imagen de alta calidad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |

### getDestinationCmykColorProfile() {#getDestinationCmykColorProfile--}
```
public StreamSource getDestinationCmykColorProfile()
```


El perfil de color CMYK es vital para la conversión precisa de color de imágenes JPEG CMYK y YCCK durante el proceso de guardado. Funciona en conjunto con el RGBColorProfile para asegurar una representación de color correcta, manteniendo la consistencia y calidad en diferentes dispositivos y software. Esta sincronización es crucial para lograr una renderización de color exacta y fiable en las imágenes guardadas final.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setDestinationCmykColorProfile(StreamSource value) {#setDestinationCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setDestinationCmykColorProfile(StreamSource value)
```


El perfil de color CMYK es vital para la conversión precisa de color de imágenes JPEG CMYK y YCCK durante el proceso de guardado. Funciona en conjunto con el RGBColorProfile para asegurar una representación de color correcta, manteniendo la consistencia y calidad en diferentes dispositivos y software. Esta sincronización es crucial para lograr una renderización de color exacta y fiable en las imágenes guardadas final.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |

### getIgnoreEmbeddedColorProfile() {#getIgnoreEmbeddedColorProfile--}
```
public boolean getIgnoreEmbeddedColorProfile()
```


Recupera o modifica la bandera que indica si se ignora el perfil de color incrustado. Al establecer esta bandera, los usuarios pueden especificar si se debe usar el perfil de color predeterminado en lugar del incrustado. Esta opción brinda un mayor control sobre la gestión del color, facilitando ajustes para la consistencia y compatibilidad en diversas plataformas y aplicaciones.

**Returns:**
boolean
### setIgnoreEmbeddedColorProfile(boolean value) {#setIgnoreEmbeddedColorProfile-boolean-}
```
public void setIgnoreEmbeddedColorProfile(boolean value)
```


Recupera o modifica la bandera que indica si se ignora el perfil de color incrustado. Al establecer esta bandera, los usuarios pueden especificar si se debe usar el perfil de color predeterminado en lugar del incrustado. Esta opción brinda un mayor control sobre la gestión del color, facilitando ajustes para la consistencia y compatibilidad en diversas plataformas y aplicaciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Obtiene las opciones originales de imagen de esta instancia de [Image](../../com.aspose.imaging/image).

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - A clone of original image options.
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Elimina los metadatos de esta instancia de imagen estableciendo los valores de `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) y `IHasExifData.ExifData`([IHasExifData.getExifData()](../../com.aspose.imaging.exif/ihasexifdata\#getExifData--)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-)) a `null`.

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Establece la resolución para el [RasterImage](../../com.aspose.imaging/rasterimage) especificado, garantizando una escala e impresión precisas. Este método permite a los usuarios adaptar la resolución de la imagen a sus requisitos específicos, ya sea para visualización digital o reproducción física. Al establecer la resolución, los usuarios pueden optimizar la calidad de la imagen y asegurar la compatibilidad con diversos dispositivos y medios de salida, mejorando la experiencia visual general y la usabilidad de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dpiX | double | La resolución horizontal, en puntos por pulgada, del `RasterImage`. |
| dpiY | double | La resolución vertical, en puntos por pulgada, del `RasterImage`. |


**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // Obtener la resolución horizontal y vertical del BmpImage
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Utilice el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// La salida puede verse así:
// La resolución horizontal, en píxeles por pulgada: 300.0
// La resolución vertical, en píxeles por pulgada: 300.0
// Establecer los valores de resolución a 96 dpi
// La resolución horizontal, en píxeles por pulgada: 96.0
// La resolución vertical, en píxeles por pulgada: 96.0
```

