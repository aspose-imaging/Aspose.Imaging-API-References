---
title: "DitheringMethod"
second_title: "Aspose.Imaging för Java API-referens"
description: "Dithermetod."
type: docs
weight: 41
url: /sv/java/com.aspose.imaging/ditheringmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DitheringMethod extends System.Enum
```

Dithermetod.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ThresholdDithering](#ThresholdDithering) | Tröskel-dithering. |
| [FloydSteinbergDithering](#FloydSteinbergDithering) | Floyd-Steinberg-dithering. |

## Example: The following example loads a raster image and performs threshold and floyd dithering using different palette depth.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Utför tröskel-dithering med en 4-bitars färgpalett som innehåller 16 färger.
    // Ju fler bitar som anges, desto högre kvalitet och desto större storlek på den resulterande bilden.
    // Observera att endast 1-bitars, 4-bitars och 8-bitars paletter stöds för närvarande.
    rasterImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.save(dir + "sample.ThresholdDithering4.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Utför Floyd-dithering med en 1-bitars färgpalett som endast innehåller 2 färger – svart och vit.
    // Ju fler bitar som anges, desto högre kvalitet och desto större storlek på den resulterande bilden.
    // Observera att endast 1-bitars, 4-bitars och 8-bitars paletter stöds för närvarande.
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


Tröskel-dithering. Den enklaste och snabbaste ditheringalgoritmen.

### FloydSteinbergDithering {#FloydSteinbergDithering}
```
public static final int FloydSteinbergDithering
```


Floyd‑Steinberg‑dithering. En mer komplex dithering‑algoritm, använder närmaste grannars intensitetsvärden.

