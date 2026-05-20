---
title: "DitheringMethod"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Metodo di dithering."
type: docs
weight: 41
url: /it/java/com.aspose.imaging/ditheringmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DitheringMethod extends System.Enum
```

Metodo di dithering.
## Campi

| Campo | Descrizione |
| --- | --- |
| [ThresholdDithering](#ThresholdDithering) | Dithering a soglia. |
| [FloydSteinbergDithering](#FloydSteinbergDithering) | Il dithering Floyd-Steinberg. |

## Example: The following example loads a raster image and performs threshold and floyd dithering using different palette depth.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Esegui il dithering a soglia usando una palette di colori a 4 bit che contiene 16 colori.
    // Più bit sono specificati, maggiore è la qualità e più grande è la dimensione dell'immagine di output.
    // Nota che al momento sono supportate solo palette a 1 bit, 4 bit e 8 bit.
    rasterImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.save(dir + "sample.ThresholdDithering4.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Esegui il dithering Floyd usando una palette di colori a 1 bit che contiene solo 2 colori - nero e bianco.
    // Più bit sono specificati, maggiore è la qualità e più grande è la dimensione dell'immagine di output.
    // Nota che al momento sono supportate solo palette a 1 bit, 4 bit e 8 bit.
    rasterImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1);

    rasterImage.save(dir + "sample.FloydSteinbergDithering1.png");
} finally {
    image.dispose();
}
```

### ThresholdDithering {#ThresholdDithering}
```
public static final int ThresholdDithering
```


Dithering a soglia. L'algoritmo di dithering più semplice e veloce.

### FloydSteinbergDithering {#FloydSteinbergDithering}
```
public static final int FloydSteinbergDithering
```


Il dithering Floyd-Steinberg. Un algoritmo di dithering più complesso, utilizza i valori di intensità dei vicini più prossimi.

