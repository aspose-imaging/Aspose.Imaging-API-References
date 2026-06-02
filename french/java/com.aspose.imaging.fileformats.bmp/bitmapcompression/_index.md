---
title: "BitmapCompression"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Spécifie différentes méthodes de compression de bitmap."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.bmp/bitmapcompression/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class BitmapCompression extends System.Enum
```

Spécifie différentes méthodes de compression de bitmap.
## Champs

| Champ | Description |
| --- | --- |
| [Rgb](#Rgb) | Pas de compression. |
| [Rle8](#Rle8) | Compression RLE 8 bits/par pixel. |
| [Rle4](#Rle4) | Compression RLE 4 bits/par pixel. |
| [Bitfields](#Bitfields) | Champs de bits RGB. |
| [Jpeg](#Jpeg) | Compression JPEG. |
| [Png](#Png) | Compression PNG. |
| [AlphaBitfields](#AlphaBitfields) | Champs de bits RGBA. |
| [Dxt1](#Dxt1) | Compression DXT1. |

## Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.

``` java
String sourcePath = "input.png";
String outputPathPng = "output.png";
String outputPathBmp = "output.bmp";
// Charger une image PNG depuis un fichier.
try (Image pngImage = Image.load(sourcePath))
{
    // L'image BMP est enregistrée avec prise en charge de la transparence par défaut.
    // Si vous souhaitez spécifier explicitement ce mode, la propriété Compression de BmpOptions doit être définie sur BitmapCompression.Bitfields.
    // La méthode de compression BitmapCompression.Bitfields est la méthode de compression par défaut dans BmpOptions.
    // Ainsi, le même résultat d'exportation d'une image Bmp avec transparence peut être obtenu par l'une des méthodes suivantes.
    // Avec des options par défaut implicites :
    pngImage.save(outputPathPng);
    // Avec des options par défaut explicites :
    pngImage.save(outputPathBmp, new BmpOptions());
    // Spécification de la méthode de compression BitmapCompression.Bitfields :
    pngImage.save(outputPathBmp, new BmpOptions() {{ setCompression(BitmapCompression.Bitfields); }});
}
```


## Example: The example shows how to export a BmpImage with the Rgb compression type.

``` java
String sourcePath = "input.png";
String outputPath = "output.bmp";
// Charger une image PNG depuis un fichier.
try (Image pngImage = Image.load(sourcePath))
{
    // L'image BMP est enregistrée avec prise en charge de la transparence par défaut, ce qui est réalisé en utilisant la méthode de compression BitmapCompression.Bitfields.
    // Pour enregistrer une image BMP avec la méthode de compression Rgb, il faut spécifier les BmpOptions dont la propriété Compression est définie sur BitmapCompression.Rgb.
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


Pas de compression.

### Rle8 {#Rle8}
```
public static final long Rle8
```


Compression RLE 8-bit/pixel. Ne peut être utilisée que avec des bitmaps 8-bit/pixel.

### Rle4 {#Rle4}
```
public static final long Rle4
```


Compression RLE 4-bit/pixel. Ne peut être utilisée que avec des bitmaps 4-bit/pixel.

### Bitfields {#Bitfields}
```
public static final long Bitfields
```


Champs de bits RGB. Ne peut être utilisée que avec des bitmaps 16 et 32-bit/pixel.

### Jpeg {#Jpeg}
```
public static final long Jpeg
```


Compression JPEG. Le bitmap contient une image JPEG.

### Png {#Png}
```
public static final long Png
```


Compression PNG. Le bitmap contient une image PNG.

### AlphaBitfields {#AlphaBitfields}
```
public static final long AlphaBitfields
```


Champs de bits RGBA. Ne peut être utilisée que avec des bitmaps 16 et 32-bit/pixel.

### Dxt1 {#Dxt1}
```
public static final long Dxt1
```


Compression DXT1. Le bitmap contient une texture.

