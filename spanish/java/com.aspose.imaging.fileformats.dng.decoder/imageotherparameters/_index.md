---
title: "ImageOtherParameters"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Otros parámetros de imagen"
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.dng.decoder/imageotherparameters/
---
**Inheritance:**
java.lang.Object
```
public class ImageOtherParameters
```

Otros parámetros de imagen
## Métodos

| Método | Descripción |
| --- | --- |
| [getDescription()](#getDescription--) | Obtiene la descripción de la imagen. |
| [getArtist()](#getArtist--) | Obtiene el autor de la imagen. |
| [getTimestamp()](#getTimestamp--) | Obtiene la fecha de disparo. |
| [getShotOrder()](#getShotOrder--) | Obtiene el número de serie de la imagen. |
| [getAperture()](#getAperture--) | Obtiene la apertura. |
| [getShutterSpeed()](#getShutterSpeed--) | Obtiene la velocidad de obturación. |
| [getGpsData()](#getGpsData--) | Obtiene los datos GPS. |
| [getFocalLength()](#getFocalLength--) | Obtiene la longitud focal. |
| [getIsoSpeed()](#getIsoSpeed--) | Obtiene la sensibilidad ISO. |

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

### getDescription() {#getDescription--}
```
public String getDescription()
```


Obtiene la descripción de la imagen.

Valor: La descripción.

**Returns:**
java.lang.String
### getArtist() {#getArtist--}
```
public String getArtist()
```


Obtiene el autor de la imagen.

Valor: El artista.

**Returns:**
java.lang.String
### getTimestamp() {#getTimestamp--}
```
public long getTimestamp()
```


Obtiene la fecha de disparo.

Valor: La marca de tiempo.

**Returns:**
long
### getShotOrder() {#getShotOrder--}
```
public long getShotOrder()
```


Obtiene el número de serie de la imagen.

Valor: El orden de disparo.

**Returns:**
long
### getAperture() {#getAperture--}
```
public float getAperture()
```


Obtiene la apertura.

Valor: La apertura.

**Returns:**
float
### getShutterSpeed() {#getShutterSpeed--}
```
public float getShutterSpeed()
```


Obtiene la velocidad de obturación.

Valor: El obturador.

**Returns:**
float
### getGpsData() {#getGpsData--}
```
public long[] getGpsData()
```


Obtiene los datos GPS.

Valor: Los datos GPS.

**Returns:**
long[]
### getFocalLength() {#getFocalLength--}
```
public float getFocalLength()
```


Obtiene la longitud focal.

Valor: La longitud focal.

**Returns:**
float
### getIsoSpeed() {#getIsoSpeed--}
```
public float getIsoSpeed()
```


Obtiene la sensibilidad ISO.

Valor: La velocidad ISO.

**Returns:**
float
