---
title: "GaussWienerFilterOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Opzioni del filtro Gauss Wiener per la rimozione della sfocatura dell'immagine."
type: docs
weight: 18
url: /it/java/com.aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions), [com.aspose.imaging.imagefilters.filteroptions.GaussianDeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions)
```
public class GaussWienerFilterOptions extends GaussianDeconvolutionFilterOptions
```

Opzioni del filtro Gauss Wiener per la rimozione della sfocatura dell'immagine.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GaussWienerFilterOptions(int size, double sigma)](#GaussWienerFilterOptions-int-double-) | Inizializza una nuova istanza della classe [GaussWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions). |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions--) | Inizializza una nuova istanza della classe [GaussWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getKernel()](#getKernel--) | Ottiene il kernel. |

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

### GaussWienerFilterOptions(int size, double sigma) {#GaussWienerFilterOptions-int-double-}
```
public GaussWienerFilterOptions(int size, double sigma)
```


Inizializza una nuova istanza della classe [GaussWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dimensione | int | La dimensione del kernel gaussiano. |
| sigma | double | Il sigma del kernel gaussiano. |

### GaussWienerFilterOptions() {#GaussWienerFilterOptions--}
```
public GaussWienerFilterOptions()
```


Inizializza una nuova istanza della classe [GaussWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions).

### getKernel() {#getKernel--}
```
public Complex[][] getKernel()
```


Ottiene il kernel.

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - il kernel.
