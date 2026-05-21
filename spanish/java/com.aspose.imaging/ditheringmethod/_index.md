---
title: "DitheringMethod"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Método de tramado."
type: docs
weight: 41
url: /es/java/com.aspose.imaging/ditheringmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DitheringMethod extends System.Enum
```

Método de tramado.
## Campos

| Campo | Descripción |
| --- | --- |
| [ThresholdDithering](#ThresholdDithering) | Dithering por umbral. |
| [FloydSteinbergDithering](#FloydSteinbergDithering) | El dithering Floyd‑Steinberg. |

## Example: The following example loads a raster image and performs threshold and floyd dithering using different palette depth.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Realizar dithering por umbral usando una paleta de colores de 4 bits que contiene 16 colores.
    // Cuantos más bits se especifiquen, mayor será la calidad y mayor el tamaño de la imagen de salida.
    // Tenga en cuenta que solo se admiten paletas de 1 bit, 4 bits y 8 bits en este momento.
    rasterImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.save(dir + "sample.ThresholdDithering4.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Realizar dithering Floyd usando una paleta de colores de 1 bit que contiene solo 2 colores: negro y blanco.
    // Cuantos más bits se especifiquen, mayor será la calidad y mayor el tamaño de la imagen de salida.
    // Tenga en cuenta que solo se admiten paletas de 1 bit, 4 bits y 8 bits en este momento.
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


Dithering por umbral. El algoritmo de dithering más simple y rápido.

### FloydSteinbergDithering {#FloydSteinbergDithering}
```
public static final int FloydSteinbergDithering
```


El dithering Floyd‑Steinberg. Un algoritmo de dithering más complejo, utiliza los valores de intensidad de los vecinos más cercanos.

