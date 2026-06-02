---
title: "ImageParameters"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Parámetros de imagen DNG"
type: docs
weight: 11
url: /es/java/com.aspose.imaging.fileformats.dng.decoder/imageparameters/
---
**Inheritance:**
java.lang.Object
```
public class ImageParameters
```

Parámetros de imagen DNG
## Métodos

| Método | Descripción |
| --- | --- |
| [getDngVersion()](#getDngVersion--) | Obtiene la versión DNG. |
| [getDescription()](#getDescription--) | Obtiene la descripción de los colores (RGBG,RGBE,GMCY, o GBTG). |
| [getModel()](#getModel--) | Obtiene el modelo de la cámara. |
| [getCameraManufacturer()](#getCameraManufacturer--) | Obtiene el fabricante de la cámara. |
| [isFoveon()](#isFoveon--) | Obtiene la matriz foveon. |
| [getSoftware()](#getSoftware--) | Obtiene el software. |
| [getRawCount()](#getRawCount--) | Obtiene el número de imágenes RAW en el archivo (0 significa que el archivo no ha sido reconocido). |
| [getFilters()](#getFilters--) | Obtiene la máscara de bits que describe el orden de los píxeles de color en la matriz. |
| [getColorsCount()](#getColorsCount--) | Obtiene los colores. |
| [getXmpData()](#getXmpData--) | Obtiene los datos XMP. |
| [getTranslationCfaDng()](#getTranslationCfaDng--) | Obtiene la matriz de traducción para el formato DNG de mosaico CFA. |

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

### getDngVersion() {#getDngVersion--}
```
public long getDngVersion()
```


Obtiene la versión DNG.

Valor: La versión DNG.

**Returns:**
long
### getDescription() {#getDescription--}
```
public String getDescription()
```


Obtiene la descripción de los colores (RGBG,RGBE,GMCY, o GBTG).

Valor: La cdesc.

**Returns:**
java.lang.String
### getModel() {#getModel--}
```
public String getModel()
```


Obtiene el modelo de la cámara.

Valor: El modelo.

**Returns:**
java.lang.String
### getCameraManufacturer() {#getCameraManufacturer--}
```
public String getCameraManufacturer()
```


Obtiene el fabricante de la cámara.

Valor: La marca.

**Returns:**
java.lang.String
### isFoveon() {#isFoveon--}
```
public long isFoveon()
```


Obtiene la matriz foveon.

Valor: Es foveon.

**Returns:**
long
### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


Obtiene el software.

Valor: El software.

**Returns:**
java.lang.String
### getRawCount() {#getRawCount--}
```
public long getRawCount()
```


Obtiene el número de imágenes RAW en el archivo (0 significa que el archivo no ha sido reconocido).

Valor: El recuento RAW.

**Returns:**
long
### getFilters() {#getFilters--}
```
public long getFilters()
```


Obtiene la máscara de bits que describe el orden de los píxeles de color en la matriz.

Valor: Los filtros.

**Returns:**
long
### getColorsCount() {#getColorsCount--}
```
public int getColorsCount()
```


Obtiene los colores.

Valor: Los colores.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public String getXmpData()
```


Obtiene los datos XMP.

Valor: Los datos XMP.

**Returns:**
java.lang.String
### getTranslationCfaDng() {#getTranslationCfaDng--}
```
public String[] getTranslationCfaDng()
```


Obtiene la matriz de traducción para el formato DNG de mosaico CFA.

Valor: El xtrans.

**Returns:**
java.lang.String[]
