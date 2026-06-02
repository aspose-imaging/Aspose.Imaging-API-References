---
title: "MedianFilterOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Filtro mediano"
type: docs
weight: 22
url: /it/java/com.aspose.imaging.imagefilters.filteroptions/medianfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class MedianFilterOptions extends FilterOptionsBase
```

Filtro mediano
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MedianFilterOptions(int size)](#MedianFilterOptions-int-) | Inizializza una nuova istanza della classe `MedianFilterOptions`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSize()](#getSize--) | Ottiene o imposta la dimensione. |
| [setSize(int value)](#setSize-int-) | Ottiene o imposta la dimensione. |

## Example: The following example applies various types of filters to a raster image.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applica un filtro mediano con una dimensione del rettangolo di 5 all'intera immagine.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    rasterImage.save(dir + "sample.MedianFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applica un filtro di levigatura bilaterale con una dimensione del kernel di 5 all'intera immagine.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    rasterImage.save(dir + "sample.BilateralSmoothingFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applica un filtro di sfocatura gaussiana con un raggio di 5 e un valore sigma di 4.0 all'intera immagine.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussianBlurFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applica un filtro Gauss-Wiener con un raggio di 5 e un valore di levigatura di 4.0 all'intera immagine.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applica un filtro motion Wiener con una lunghezza di 5, un valore di levigatura di 4.0 e un angolo di 90.0 gradi all'intera immagine.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.save(dir + "sample.MotionWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Applica un filtro di nitidezza con una dimensione del kernel di 5 e un valore sigma di 4.0 all'intera immagine.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.SharpenFilter.png");
} finally {
    image.dispose();
}
```

### MedianFilterOptions(int size) {#MedianFilterOptions-int-}
```
public MedianFilterOptions(int size)
```


Inizializza una nuova istanza della classe `MedianFilterOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dimensione | int | La dimensione del rettangolo del filtro. |

### getSize() {#getSize--}
```
public int getSize()
```


Ottiene o imposta la dimensione.

Valore: La dimensione del rettangolo del filtro.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Ottiene o imposta la dimensione.

Valore: La dimensione del rettangolo del filtro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

