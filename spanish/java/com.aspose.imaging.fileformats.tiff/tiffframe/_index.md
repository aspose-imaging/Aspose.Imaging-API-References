---
title: "TiffFrame"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El marco tiff."
type: docs
weight: 12
url: /es/java/com.aspose.imaging.fileformats.tiff/tiffframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class TiffFrame extends RasterCachedImage
```

El marco tiff.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffFrame(InputStream stream)](#TiffFrame-java.io.InputStream-) | Inicializa una nueva instancia de la clase `TiffFrame`. |
| [TiffFrame(InputStream stream, TiffOptions options)](#TiffFrame-java.io.InputStream-com.aspose.imaging.imageoptions.TiffOptions-) | Inicializa una nueva instancia de la clase `TiffFrame`. |
| [TiffFrame(String path)](#TiffFrame-java.lang.String-) | Inicializa una nueva instancia de la clase `TiffFrame`. |
| [TiffFrame(String path, TiffOptions options)](#TiffFrame-java.lang.String-com.aspose.imaging.imageoptions.TiffOptions-) | Inicializa una nueva instancia de la clase `TiffFrame`. |
| [TiffFrame(RasterImage image)](#TiffFrame-com.aspose.imaging.RasterImage-) | Inicializa una nueva instancia de la clase `TiffFrame`. |
| [TiffFrame(RasterImage image, TiffOptions options)](#TiffFrame-com.aspose.imaging.RasterImage-com.aspose.imaging.imageoptions.TiffOptions-) | Inicializa una nueva instancia de la clase `TiffFrame`. |
| [TiffFrame(TiffOptions options, int width, int height)](#TiffFrame-com.aspose.imaging.imageoptions.TiffOptions-int-int-) | Inicializa una nueva instancia de la clase `TiffFrame`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBackgroundColor()](#getBackgroundColor--) | Obtiene un valor para el color de fondo. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Establece un valor para el color de fondo. |
| [hasAlpha()](#hasAlpha--) | Obtiene un valor que indica si esta instancia tiene alfa. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtiene la cantidad de bits por píxel de la imagen. |
| [getFrameOptions()](#getFrameOptions--) | Obtiene las opciones de creación del frame. |
| [getHeight()](#getHeight--) | Obtiene la altura de la imagen. |
| [getWidth()](#getWidth--) | Obtiene el ancho de la imagen. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Obtiene la resolución horizontal, en píxeles por pulgada, de este `RasterImage`. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Establece la resolución horizontal, en píxeles por pulgada, de este `RasterImage`. |
| [getVerticalResolution()](#getVerticalResolution--) | Obtiene la resolución vertical, en píxeles por pulgada, de este `RasterImage`. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Establece la resolución vertical, en píxeles por pulgada, de este `RasterImage`. |
| [getPathResources()](#getPathResources--) | Obtiene los recursos de ruta. |
| [setPathResources(List<PathResource> value)](#setPathResources-java.util.List-com.aspose.imaging.fileformats.tiff.pathresources.PathResource--) | Establece los recursos de ruta. |
| [removeMetadata()](#removeMetadata--) | Elimina los metadatos de esta instancia de imagen estableciendo los valores de IHasXmpData.XmpData ([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) y `IHasExifData.ExifData`([IHasExifData.getExifData](../../com.aspose.imaging.exif/ihasexifdata\#getExifData)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-) IHasExifData.setExifData) a `null`. |
| [getOriginalOptions()](#getOriginalOptions--) | Obtiene las opciones basadas en la configuración original del archivo. |
| [alignResolutions()](#alignResolutions--) | Método auxiliar para igualar las resoluciones horizontal y vertical. |
| [copyFrame(TiffFrame tiffFrame)](#copyFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Copia todo el frame (duplicados). |
| [createFrameFrom(TiffFrame tiffFrame, TiffOptions options)](#createFrameFrom-com.aspose.imaging.fileformats.tiff.TiffFrame-com.aspose.imaging.imageoptions.TiffOptions-) | Crea el frame a partir del `tiffFrame` especificado usando las `options` especificadas. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Redimensiona la imagen. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Rota, voltea o rota y voltea la imagen. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Rota la imagen alrededor del centro. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recorta la imagen. |

## Example: This example shows how to create a TIFF image from scratch and save it to a file.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createOptions =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Establece 8 bits para cada componente de color.
createOptions.setBitsPerSample(new int[]{8, 8, 8});

// Establece el orden de bytes Big Endian (Motorola)
createOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// Establece la compresión LZW.
createOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// Establece el modelo de color RGB.
createOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Todos los componentes de color se almacenarán en un solo plano.
createOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// Crea un Frame TIFF de 100x100 px.
// Ten en cuenta que no tienes que liberar un frame explícitamente si está incluido en TiffImage.
// Cuando el contenedor se libera, todos los frames se liberarán automáticamente.
com.aspose.imaging.fileformats.tiff.TiffFrame firstFrame = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions, 100, 100);

// Rellena todo el frame con el degradado azul-amarillo.
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(firstFrame.getWidth(), firstFrame.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(firstFrame);
graphics.fillRectangle(gradientBrush, firstFrame.getBounds());

// Crea una imagen TIFF.
com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(firstFrame);
try {
    tiffImage.save(dir + "output.tif");
} finally {
    tiffImage.dispose();
}
```

### TiffFrame(InputStream stream) {#TiffFrame-java.io.InputStream-}
```
public TiffFrame(InputStream stream)
```


Inicializa una nueva instancia de la clase `TiffFrame`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo para cargar una imagen e inicializar los datos de píxeles y paleta del fotograma. |

### TiffFrame(InputStream stream, TiffOptions options) {#TiffFrame-java.io.InputStream-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffFrame(InputStream stream, TiffOptions options)
```


Inicializa una nueva instancia de la clase `TiffFrame`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.InputStream | El flujo para cargar una imagen e inicializar los datos de píxeles y paleta del fotograma. |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Las opciones a usar para el fotograma recién creado. |

### TiffFrame(String path) {#TiffFrame-java.lang.String-}
```
public TiffFrame(String path)
```


Inicializa una nueva instancia de la clase `TiffFrame`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | java.lang.String | La ruta desde la cual cargar una imagen e inicializar los datos de píxeles y paleta del fotograma. |

### TiffFrame(String path, TiffOptions options) {#TiffFrame-java.lang.String-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffFrame(String path, TiffOptions options)
```


Inicializa una nueva instancia de la clase `TiffFrame`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ruta | java.lang.String | La ruta desde la cual cargar una imagen e inicializar los datos de píxeles y paleta del fotograma. |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Las opciones a usar para el fotograma recién creado. |

### TiffFrame(RasterImage image) {#TiffFrame-com.aspose.imaging.RasterImage-}
```
public TiffFrame(RasterImage image)
```


Inicializa una nueva instancia de la clase `TiffFrame`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen con la que inicializar los datos de píxeles y paleta del fotograma. |

### TiffFrame(RasterImage image, TiffOptions options) {#TiffFrame-com.aspose.imaging.RasterImage-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffFrame(RasterImage image, TiffOptions options)
```


Inicializa una nueva instancia de la clase `TiffFrame`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen con la que inicializar los datos de píxeles y paleta del fotograma. |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Las opciones a usar para el fotograma recién creado. |

### TiffFrame(TiffOptions options, int width, int height) {#TiffFrame-com.aspose.imaging.imageoptions.TiffOptions-int-int-}
```
public TiffFrame(TiffOptions options, int width, int height)
```


Inicializa una nueva instancia de la clase `TiffFrame`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Las opciones del fotograma. |
| width | int | El ancho. |
| height | int | La altura. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtiene un valor para el color de fondo.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Establece un valor para el color de fondo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Obtiene un valor que indica si esta instancia tiene alfa.

**Returns:**
boolean - `true` si esta instancia tiene alfa; de lo contrario, `false`.

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

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtiene la cantidad de bits por píxel de la imagen.

**Returns:**
int - El recuento de bits por píxel de la imagen.
### getFrameOptions() {#getFrameOptions--}
```
public TiffOptions getFrameOptions()
```


Obtiene las opciones de creación del frame.

**Returns:**
[TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtiene la altura de la imagen.

**Returns:**
int - La altura de la imagen.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene el ancho de la imagen.

**Returns:**
int - El ancho de la imagen.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Obtiene la resolución horizontal, en píxeles por pulgada, de este `RasterImage`.

**Returns:**
double - La resolución horizontal.

**Example: The following example shows how to set horizontal/vertical resolution of a separate TIFF frame.**

``` java
String dir = "c:\\temp\\";

// Cargar una imagen TIFF desde un archivo.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    int i = 0;
    for (com.aspose.imaging.fileformats.tiff.TiffFrame frame : tiffImage.getFrames()) {
        // Obtener la resolución horizontal y vertical del TiffFrame.
        double horizontalResolution = frame.getHorizontalResolution();
        double verticalResolution = frame.getVerticalResolution();
        System.out.printf("The horizontal resolution of frame %s, pixels per inch: %s\r\n", i, horizontalResolution);
        System.out.printf("The vertical resolution, of frame %s, pixels per inch: %s\r\n", i, verticalResolution);

        if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
            // Utilice el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
            System.out.println("Set resolution values to 96 dpi");
            frame.setResolution(96.0, 96.0);

            System.out.printf("The horizontal resolution of frame %s, pixels per inch: %s\r\n", i, horizontalResolution);
            System.out.printf("The vertical resolution, of frame %s, pixels per inch: %s\r\n", i, verticalResolution);
        }

        ++i;
    }
} finally {
    image.dispose();
}
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Establece la resolución horizontal, en píxeles por pulgada, de este `RasterImage`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | La resolución horizontal. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Obtiene la resolución vertical, en píxeles por pulgada, de este `RasterImage`.

**Returns:**
double - La resolución vertical.

**Example: The following example shows how to set horizontal/vertical resolution of a separate TIFF frame.**

``` java
String dir = "c:\\temp\\";

// Cargar una imagen TIFF desde un archivo.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    int i = 0;
    for (com.aspose.imaging.fileformats.tiff.TiffFrame frame : tiffImage.getFrames()) {
        // Obtener la resolución horizontal y vertical del TiffFrame.
        double horizontalResolution = frame.getHorizontalResolution();
        double verticalResolution = frame.getVerticalResolution();
        System.out.printf("The horizontal resolution of frame %s, pixels per inch: %s\r\n", i, horizontalResolution);
        System.out.printf("The vertical resolution, of frame %s, pixels per inch: %s\r\n", i, verticalResolution);

        if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
            // Utilice el método SetResolution para actualizar ambos valores de resolución en una sola llamada.
            System.out.println("Set resolution values to 96 dpi");
            frame.setResolution(96.0, 96.0);

            System.out.printf("The horizontal resolution of frame %s, pixels per inch: %s\r\n", i, horizontalResolution);
            System.out.printf("The vertical resolution, of frame %s, pixels per inch: %s\r\n", i, verticalResolution);
        }

        ++i;
    }
} finally {
    image.dispose();
}
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Establece la resolución vertical, en píxeles por pulgada, de este `RasterImage`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | La resolución vertical. |

### getPathResources() {#getPathResources--}
```
public List<PathResource> getPathResources()
```


Obtiene los recursos de ruta.

Valor: Los recursos de ruta.

**Returns:**
java.util.List<com.aspose.imaging.fileformats.tiff.pathresources.PathResource> - los recursos de ruta.

**Example: The following example shows how to retrieve paths from TIFF image and display their names in the console.**

``` java
try (TiffImage image = (TiffImage) Image.load("Sample.tif"))
{
    for (PathResource path : image.getActiveFrame().getPathResources())
    {
        System.out.println(path.getName());
    }
}
```


**Example: The following example shows how to modify already existing Clipping Paths.**
El siguiente ejemplo muestra cómo modificar rutas de recorte ya existentes. Por ejemplo, puedes conservar solo una ruta de recorte en la imagen.
``` java
try (TiffImage image = (TiffImage) Image.load("Sample.tif"))
{
    List<PathResource> paths = image.getActiveFrame().getPathResources();
    image.getActiveFrame().setPathResources(Collections.singletonList(paths.get(0)));
    image.save();
}
```


**Example: Transfer Clipping Paths during export from TIFF to PSD image.**

``` java
try (Image image = Image.load("Sample.tif"))
{
    image.save("SampleWithPaths.psd", new PsdOptions());
}
```


**Example: Create Clipping Path manually.**

``` java
static void main()
{
    try (TiffImage image = (TiffImage)Image.load("Sample.tif"))
    {
        PathResource res = new PathResource();
        res.setBlockId((short) 2000);                                                  // Block Id according to Photoshop specification
        res.setName("My Clipping Path");                                               // Path name
        res.setRecords(createRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)); // Create path records using coordinates
                    
        image.getActiveFrame().setPathResources(Collections.singletonList(res));

        image.save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> createRecords(float ... coordinates)
{
    List<VectorPathRecord>  records = createBezierRecords(coordinates);                                  // Create Bezier records using coordinates

    LengthRecord lr = new LengthRecord(); // LengthRecord required by Photoshop specification
    lr.setOpen(false);                    // Lets create closed path
    lr.setRecordCount(records.size());    // Record count in the path
                
    records.add(0, lr);

    return records;
}

private static List<VectorPathRecord> createBezierRecords(float[] coordinates)
{
    List<VectorPathRecord> l = new LinkedList<VectorPathRecord>();
                
    for (int index = 0; index < coordinates.length - 1; index += 2)
    {
        PointF pt = new PointF(coordinates[index], coordinates[index + 1]);
        BezierKnotRecord br = new BezierKnotRecord();
        br.setPathPoints(new PointF[] {pt, pt, pt});
        l.add(br);
    }
                    
    return l;
}

```

### setPathResources(List<PathResource> value) {#setPathResources-java.util.List-com.aspose.imaging.fileformats.tiff.pathresources.PathResource--}
```
public void setPathResources(List<PathResource> value)
```


Establece los recursos de ruta.

Valor: Los recursos de ruta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.List<com.aspose.imaging.fileformats.tiff.pathresources.PathResource> | los recursos de ruta. |

### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Elimina los metadatos de esta instancia de imagen estableciendo los valores de IHasXmpData.XmpData ([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) y `IHasExifData.ExifData`([IHasExifData.getExifData](../../com.aspose.imaging.exif/ihasexifdata\#getExifData)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-) IHasExifData.setExifData) a `null`.

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Obtiene las opciones basadas en la configuración original del archivo. Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el método [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), se producirá una imagen PNG de salida con 8 bits por píxel. Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas al método [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) como segundo parámetro.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### alignResolutions() {#alignResolutions--}
```
public void alignResolutions()
```


Método auxiliar para igualar las resoluciones horizontal y vertical.

### copyFrame(TiffFrame tiffFrame) {#copyFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public static TiffFrame copyFrame(TiffFrame tiffFrame)
```


Copia todo el frame (duplicados).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tiffFrame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | El fotograma TIFF a copiar. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The newly copied tiff frame.
### createFrameFrom(TiffFrame tiffFrame, TiffOptions options) {#createFrameFrom-com.aspose.imaging.fileformats.tiff.TiffFrame-com.aspose.imaging.imageoptions.TiffOptions-}
```
public static TiffFrame createFrameFrom(TiffFrame tiffFrame, TiffOptions options)
```


Crea el fotograma a partir del `tiffFrame` especificado usando las `options` especificadas. Los datos de píxeles se conservan pero se convierten al formato deseado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tiffFrame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | El fotograma TIFF del cual crear. |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Las nuevas opciones a usar. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The newly created frame.

**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Crear una fuente de archivo permanente, no temporal.
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // El degradado lineal desde la esquina superior izquierda a la esquina inferior derecha de la imagen.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Rellenar el fotograma activo con un pincel de degradado lineal.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // Opciones de escala de grises
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // Crear una copia en escala de grises del fotograma activo.
    // Los datos de píxeles se conservan pero se convierten al formato deseado.
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // Agregar el fotograma recién creado a la imagen TIFF.
    tiffImage.addFrame(grayscaleFrame);

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

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

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Rota, voltea o rota y voltea la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotateFlipType | int | El tipo de rotación y volteo. |

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

