---
title: "BilateralSmoothingFilterOptions"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Le opzioni del filtro Bilateral Smoothing."
type: docs
weight: 13
url: /it/java/com.aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class BilateralSmoothingFilterOptions extends FilterOptionsBase
```

Le opzioni del filtro Bilateral Smoothing.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BilateralSmoothingFilterOptions(int size)](#BilateralSmoothingFilterOptions-int-) | Inizializza una nuova istanza della classe `BilateralSmoothingFilterOptions`. |
| [BilateralSmoothingFilterOptions()](#BilateralSmoothingFilterOptions--) | Inizializza una nuova istanza della classe `BilateralSmoothingFilterOptions`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSize()](#getSize--) | Ottiene o imposta la dimensione del kernel. |
| [setSize(int value)](#setSize-int-) | Ottiene o imposta la dimensione del kernel. |
| [getSpatialFactor()](#getSpatialFactor--) | Ottiene o imposta il fattore spaziale. |
| [setSpatialFactor(double value)](#setSpatialFactor-double-) | Ottiene o imposta il fattore spaziale. |
| [getSpatialPower()](#getSpatialPower--) | Ottiene o imposta la potenza spaziale. |
| [setSpatialPower(double value)](#setSpatialPower-double-) | Ottiene o imposta la potenza spaziale. |
| [getColorFactor()](#getColorFactor--) | Ottiene o imposta il fattore di colore. |
| [setColorFactor(double value)](#setColorFactor-double-) | Ottiene o imposta il fattore di colore. |
| [getColorPower()](#getColorPower--) | Ottiene o imposta la potenza di colore. |
| [setColorPower(double value)](#setColorPower-double-) | Ottiene o imposta la potenza di colore. |

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

### BilateralSmoothingFilterOptions(int size) {#BilateralSmoothingFilterOptions-int-}
```
public BilateralSmoothingFilterOptions(int size)
```


Inizializza una nuova istanza della classe `BilateralSmoothingFilterOptions`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dimensione | int | Dimensione del kernal. |

### BilateralSmoothingFilterOptions() {#BilateralSmoothingFilterOptions--}
```
public BilateralSmoothingFilterOptions()
```


Inizializza una nuova istanza della classe `BilateralSmoothingFilterOptions`.

### getSize() {#getSize--}
```
public int getSize()
```


Ottiene o imposta la dimensione del kernel.

Valore: La dimensione del kernel.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Ottiene o imposta la dimensione del kernel.

Valore: La dimensione del kernel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSpatialFactor() {#getSpatialFactor--}
```
public double getSpatialFactor()
```


Ottiene o imposta il fattore spaziale.

Valore: Il fattore spaziale.

**Returns:**
double
### setSpatialFactor(double value) {#setSpatialFactor-double-}
```
public void setSpatialFactor(double value)
```


Ottiene o imposta il fattore spaziale.

Valore: Il fattore spaziale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### getSpatialPower() {#getSpatialPower--}
```
public double getSpatialPower()
```


Ottiene o imposta la potenza spaziale.

Valore: La potenza spaziale.

**Returns:**
double
### setSpatialPower(double value) {#setSpatialPower-double-}
```
public void setSpatialPower(double value)
```


Ottiene o imposta la potenza spaziale.

Valore: La potenza spaziale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### getColorFactor() {#getColorFactor--}
```
public double getColorFactor()
```


Ottiene o imposta il fattore di colore.

Valore: Il fattore di colore.

**Returns:**
double
### setColorFactor(double value) {#setColorFactor-double-}
```
public void setColorFactor(double value)
```


Ottiene o imposta il fattore di colore.

Valore: Il fattore di colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### getColorPower() {#getColorPower--}
```
public double getColorPower()
```


Ottiene o imposta la potenza di colore.

Valore: La potenza di colore.

**Returns:**
double
### setColorPower(double value) {#setColorPower-double-}
```
public void setColorPower(double value)
```


Ottiene o imposta la potenza di colore.

Valore: La potenza di colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

