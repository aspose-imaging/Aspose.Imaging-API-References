---
title: "DngImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La API para procesar el formato de archivo de imagen DNG (Digital Negative) utilizado en fotografía digital, proporcionando soporte integral para archivos RAW y metadatos."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.fileformats.dng/dngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DngImage extends RasterCachedImage
```

La API para procesar el formato de archivo de imagen DNG (Digital Negative) utilizado para las necesidades de fotografía digital, proporcionando soporte integral para archivos RAW y metadatos. Diseñada para su uso con cámaras digitales de varios fabricantes, permite a los desarrolladores manipular aspectos como bits por píxel, extraer datos internos y ajustar el balance de la imagen de manera eficiente. Con capacidades para actualizar y guardar datos de la imagen sin problemas, esta API permite a los desarrolladores trabajar con archivos DNG, garantizando resultados de alta calidad y opciones de procesamiento versátiles.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [DngImage()](#DngImage--) | Inicializa una nueva instancia de la clase [DngImage](../../com.aspose.imaging.fileformats.dng/dngimage) sin esfuerzo. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Descubre el número de bits por píxel en la imagen sin esfuerzo con esta propiedad. |
| [getHeight()](#getHeight--) | Obtén la altura de la imagen con esta propiedad. |
| [getWidth()](#getWidth--) | Accede al ancho de la imagen con esta propiedad. |
| [getFileFormat()](#getFileFormat--) | Identifica el formato de archivo de tu imagen con esta propiedad. |
| [getImgData()](#getImgData--) | Gestiona los datos de la imagen con esta propiedad. |
| [setImgData(RawData value)](#setImgData-com.aspose.imaging.fileformats.dng.decoder.RawData-) | Gestiona los datos de la imagen con esta propiedad. |

## Example: This example shows how to load a DNG image from a file, print its properties and save it to PNG.

``` java
String dir = "c:\\temp\\";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "test.dng");
try {
    com.aspose.imaging.fileformats.dng.DngImage dngImage = (com.aspose.imaging.fileformats.dng.DngImage) image;
    com.aspose.imaging.fileformats.dng.decoder.RawData rawData = dngImage.getImgData();
    com.aspose.imaging.fileformats.dng.decoder.ImageParameters parameters = rawData.getImageDataParameters();
    if (parameters != null) {
        System.out.println("The camera manufacturer:              " + parameters.getCameraManufacturer());
        System.out.println("The camera model:                     " + parameters.getModel());
        System.out.println("The colors count:                     " + parameters.getColorsCount());
        System.out.println("The colors description:               " + parameters.getDescription());
        System.out.println("The DNG version:                      " + parameters.getDngVersion());
        System.out.println("The number of RAW images in the file: " + parameters.getRawCount());
        System.out.println("The software:                         " + parameters.getSoftware());
        System.out.println("The order of the color pixels:        " + Long.toBinaryString(parameters.getFilters()));

        String[] translationCfaDng = parameters.getTranslationCfaDng();
        if (translationCfaDng != null) {
            System.out.printf("The translation array for CFA mosaic %s:\r\n", translationCfaDng.length);
            for (String s : translationCfaDng) {
                System.out.printf("- %s\r\n", s);
            }
        }
    }

    com.aspose.imaging.fileformats.dng.decoder.ImageOtherParameters otherParameters = rawData.getImageOtherParameters();
    if (otherParameters != null) {
        // Convierte la marca de tiempo a una cadena legible por humanos.
        //java.text.SimpleDateFormat sf = new java.text.SimpleDateFormat("yyyy-MM-dd");
        java.util.Date date = new java.util.Date(otherParameters.getTimestamp());
        //System.out.println(sf.format(date));

        System.out.printf("The aperture:                         " + otherParameters.getAperture());
        System.out.printf("The description:                      " + otherParameters.getDescription());
        System.out.printf("The focal length:                     " + otherParameters.getFocalLength());
        System.out.printf("The ISO sensitivity:                  " + otherParameters.getIsoSpeed());
        System.out.printf("The serial number of the image:       " + otherParameters.getShotOrder());
        System.out.printf("The shutter speed:                    " + otherParameters.getShutterSpeed());
        System.out.printf("The date of shooting:                 " + date);
    }

    // Exportar a PNG con opciones predeterminadas.
    dngImage.save(dir + "test.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

// El fabricante de la cámara:              Leica
// El modelo de cámara:                     M8 Digital Camera
// El recuento de colores:                     3
// La descripción de colores:               RGBG
// La versión DNG:                      16777216
// El número de imágenes RAW en el archivo: 1
// El software:                         1.107
// El orden de los píxeles de color:        10110100101101001011010010110100
// La apertura:                         0
// La descripción:
// La distancia focal:                     50
// La sensibilidad ISO:                  160
// El número de serie de la imagen:       0
// La velocidad de obturación:                    12
// La fecha de disparo:                 8/3/2007 3:13:49 AM
```

### DngImage() {#DngImage--}
```
public DngImage()
```


Inicializa una nueva instancia de la clase [DngImage](../../com.aspose.imaging.fileformats.dng/dngimage) sin esfuerzo. Perfecto para desarrolladores que buscan comenzar a usar objetos DngImage rápida y eficientemente en sus proyectos.

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Descubre el número de bits por píxel en la imagen sin esfuerzo con esta propiedad. Ideal para comprender la profundidad de píxeles de la imagen rápida y precisamente.

Valor: El recuento de bits por píxel de la imagen.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtén la altura de la imagen con esta propiedad. Perfecto para determinar el tamaño vertical de la imagen sin complicaciones.

Valor: La altura de la imagen.

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


Accede al ancho de la imagen con esta propiedad. Ideal para obtener el tamaño horizontal de la imagen de forma rápida y eficiente.

Valor: El ancho de la imagen.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Identifica el formato de archivo de tu imagen con esta propiedad. Perfecto para comprender el formato, simplemente detalles claros.

**Returns:**
long
### getImgData() {#getImgData--}
```
public RawData getImgData()
```


Gestiona los datos de la imagen con esta propiedad. Ya sea que estés recuperando o actualizando, esta propiedad brinda acceso sin interrupciones a los datos de la imagen para una manipulación eficiente.

**Returns:**
[RawData](../../com.aspose.imaging.fileformats.dng.decoder/rawdata) - The img data.
### setImgData(RawData value) {#setImgData-com.aspose.imaging.fileformats.dng.decoder.RawData-}
```
public void setImgData(RawData value)
```


Gestiona los datos de la imagen con esta propiedad. Ya sea que estés recuperando o actualizando, esta propiedad brinda acceso sin interrupciones a los datos de la imagen para una manipulación eficiente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [RawData](../../com.aspose.imaging.fileformats.dng.decoder/rawdata) | Los datos de img. |

