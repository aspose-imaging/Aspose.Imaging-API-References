---
title: "BitmapCompression"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Especifica diferentes métodos de compresión de mapas de bits."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.bmp/bitmapcompression/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class BitmapCompression extends System.Enum
```

Especifica diferentes métodos de compresión de mapas de bits.
## Campos

| Campo | Descripción |
| --- | --- |
| [Rgb](#Rgb) | Sin compresión. |
| [Rle8](#Rle8) | Compresión RLE de 8 bits/píxel. |
| [Rle4](#Rle4) | Compresión RLE de 4 bits/píxel. |
| [Bitfields](#Bitfields) | Campos de bits RGB. |
| [Jpeg](#Jpeg) | Compresión JPEG. |
| [Png](#Png) | Compresión PNG. |
| [AlphaBitfields](#AlphaBitfields) | Campos de bits RGBA. |
| [Dxt1](#Dxt1) | Compresión DXT1. |

## Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.

``` java
String sourcePath = "input.png";
String outputPathPng = "output.png";
String outputPathBmp = "output.bmp";
// Cargar una imagen PNG desde un archivo.
try (Image pngImage = Image.load(sourcePath))
{
    // La imagen BMP se guarda con soporte de transparencia de forma predeterminada.
    // Si deseas especificar explícitamente dicho modo, la propiedad Compression de BmpOptions debe establecerse en BitmapCompression.Bitfields.
    // El método de compresión BitmapCompression.Bitfields es el método de compresión predeterminado en BmpOptions.
    // Por lo tanto, el mismo resultado de exportar una imagen Bmp con transparencia se puede lograr mediante cualquiera de las siguientes formas.
    // Con opciones predeterminadas implícitas:
    pngImage.save(outputPathPng);
    // Con opciones predeterminadas explícitas:
    pngImage.save(outputPathBmp, new BmpOptions());
    // Especificando el método de compresión BitmapCompression.Bitfields:
    pngImage.save(outputPathBmp, new BmpOptions() {{ setCompression(BitmapCompression.Bitfields); }});
}
```


## Example: The example shows how to export a BmpImage with the Rgb compression type.

``` java
String sourcePath = "input.png";
String outputPath = "output.bmp";
// Cargar una imagen PNG desde un archivo.
try (Image pngImage = Image.load(sourcePath))
{
    // La imagen BMP se guarda con soporte de transparencia de forma predeterminada, lo cual se logra utilizando el método de compresión BitmapCompression.Bitfields.
    // Para guardar una imagen BMP con el método de compresión Rgb, se debe especificar BmpOptions con la propiedad Compression establecida en BitmapCompression.Rgb.
    pngImage.save(outputPath, new BmpOptions()
    {{
        setCompression(BitmapCompression.Rgb);
    }});
}
```

### Rgb {#Rgb}
```
public static final long Rgb
```


Sin compresión.

### Rle8 {#Rle8}
```
public static final long Rle8
```


Compresión RLE de 8 bits/píxel. Solo se puede usar con mapas de bits de 8 bits/píxel.

### Rle4 {#Rle4}
```
public static final long Rle4
```


Compresión RLE de 4 bits/píxel. Solo se puede usar con mapas de bits de 4 bits/píxel.

### Bitfields {#Bitfields}
```
public static final long Bitfields
```


Campos de bits RGB. Solo se puede usar con mapas de bits de 16 y 32 bits/píxel.

### Jpeg {#Jpeg}
```
public static final long Jpeg
```


Compresión JPEG. El mapa de bits contiene una imagen JPEG.

### Png {#Png}
```
public static final long Png
```


Compresión PNG. El mapa de bits contiene una imagen PNG.

### AlphaBitfields {#AlphaBitfields}
```
public static final long AlphaBitfields
```


Campos de bits RGBA. Solo se puede usar con mapas de bits de 16 y 32 bits/píxel.

### Dxt1 {#Dxt1}
```
public static final long Dxt1
```


Compresión DXT1. El mapa de bits contiene una textura.

