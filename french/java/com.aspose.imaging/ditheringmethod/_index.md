---
title: "DitheringMethod"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Méthode de tramage."
type: docs
weight: 41
url: /fr/java/com.aspose.imaging/ditheringmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DitheringMethod extends System.Enum
```

Méthode de tramage.
## Champs

| Champ | Description |
| --- | --- |
| [ThresholdDithering](#ThresholdDithering) | Dithering par seuil. |
| [FloydSteinbergDithering](#FloydSteinbergDithering) | Le dithering Floyd‑Steinberg. |

## Example: The following example loads a raster image and performs threshold and floyd dithering using different palette depth.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Effectuer un dithering par seuil en utilisant une palette de couleurs 4 bits contenant 16 couleurs.
    // Plus le nombre de bits spécifié est élevé, meilleure est la qualité et plus grande est la taille de l'image de sortie.
    // Notez que seules les palettes de 1 bit, 4 bits et 8 bits sont prises en charge pour le moment.
    rasterImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.save(dir + "sample.ThresholdDithering4.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Effectuer un dithering Floyd en utilisant une palette de couleurs 1 bit contenant uniquement 2 couleurs - noir et blanc.
    // Plus le nombre de bits spécifié est élevé, meilleure est la qualité et plus grande est la taille de l'image de sortie.
    // Notez que seules les palettes de 1 bit, 4 bits et 8 bits sont prises en charge pour le moment.
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


Dithering par seuil. L'algorithme de dithering le plus simple et le plus rapide.

### FloydSteinbergDithering {#FloydSteinbergDithering}
```
public static final int FloydSteinbergDithering
```


Le dithérisation Floyd‑Steinberg. Un algorithme de dithérisation plus complexe, utilise les valeurs d'intensité des voisins les plus proches.

