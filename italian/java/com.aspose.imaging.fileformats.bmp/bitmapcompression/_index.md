---
title: "BitmapCompression"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Specifica diversi metodi di compressione bitmap."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.bmp/bitmapcompression/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class BitmapCompression extends System.Enum
```

Specifica diversi metodi di compressione bitmap.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Rgb](#Rgb) | Nessuna compressione. |
| [Rle8](#Rle8) | Compressione RLE a 8 bit/pixel. |
| [Rle4](#Rle4) | Compressione RLE a 4 bit/pixel. |
| [Bitfields](#Bitfields) | Campi bit RGB. |
| [Jpeg](#Jpeg) | Compressione JPEG. |
| [Png](#Png) | Compressione PNG. |
| [AlphaBitfields](#AlphaBitfields) | Campi bit RGBA. |
| [Dxt1](#Dxt1) | Compressione DXT1. |

## Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.

``` java
String sourcePath = "input.png";
String outputPathPng = "output.png";
String outputPathBmp = "output.bmp";
// Carica un'immagine PNG da un file.
try (Image pngImage = Image.load(sourcePath))
{
    // L'immagine BMP viene salvata con supporto della trasparenza per impostazione predefinita.
    // Se desideri specificare esplicitamente tale modalità, la proprietà Compression di BmpOptions deve essere impostata su BitmapCompression.Bitfields.
    // Il metodo di compressione BitmapCompression.Bitfields è il metodo di compressione predefinito in BmpOptions.
    // Quindi lo stesso risultato dell'esportazione di un'immagine Bmp con trasparenza può essere ottenuto in uno dei seguenti modi.
    // Con opzioni predefinite implicite:
    pngImage.save(outputPathPng);
    // Con opzioni predefinite esplicite:
    pngImage.save(outputPathBmp, new BmpOptions());
    // Specificando il metodo di compressione BitmapCompression.Bitfields:
    pngImage.save(outputPathBmp, new BmpOptions() {{ setCompression(BitmapCompression.Bitfields); }});
}
```


## Example: The example shows how to export a BmpImage with the Rgb compression type.

``` java
String sourcePath = "input.png";
String outputPath = "output.bmp";
// Carica un'immagine PNG da un file.
try (Image pngImage = Image.load(sourcePath))
{
    // L'immagine BMP viene salvata con supporto della trasparenza per impostazione predefinita, ciò è ottenuto utilizzando il metodo di compressione BitmapCompression.Bitfields.
    // Per salvare un'immagine BMP con il metodo di compressione Rgb, è necessario specificare BmpOptions con la proprietà Compression impostata su BitmapCompression.Rgb.
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


Nessuna compressione.

### Rle8 {#Rle8}
```
public static final long Rle8
```


Compressione RLE a 8 bit/pixel. Può essere usata solo con bitmap a 8 bit/pixel.

### Rle4 {#Rle4}
```
public static final long Rle4
```


Compressione RLE a 4 bit/pixel. Può essere usata solo con bitmap a 4 bit/pixel.

### Bitfields {#Bitfields}
```
public static final long Bitfields
```


Campi bit RGB. Può essere usata solo con bitmap a 16 e 32 bit/pixel.

### Jpeg {#Jpeg}
```
public static final long Jpeg
```


Compressione JPEG. Il bitmap contiene un'immagine JPEG.

### Png {#Png}
```
public static final long Png
```


Compressione PNG. Il bitmap contiene un'immagine PNG.

### AlphaBitfields {#AlphaBitfields}
```
public static final long AlphaBitfields
```


Campi bit RGBA. Può essere usata solo con bitmap a 16 e 32 bit/pixel.

### Dxt1 {#Dxt1}
```
public static final long Dxt1
```


Compressione DXT1. Il bitmap contiene una texture.

