---
title: "BilateralSmoothingFilterOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les options du filtre Bilateral Smoothing."
type: docs
weight: 13
url: /fr/java/com.aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class BilateralSmoothingFilterOptions extends FilterOptionsBase
```

Les options du filtre Bilateral Smoothing.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BilateralSmoothingFilterOptions(int size)](#BilateralSmoothingFilterOptions-int-) | Initialise une nouvelle instance de la classe `BilateralSmoothingFilterOptions`. |
| [BilateralSmoothingFilterOptions()](#BilateralSmoothingFilterOptions--) | Initialise une nouvelle instance de la classe `BilateralSmoothingFilterOptions`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSize()](#getSize--) | Obtient ou définit la taille du noyau. |
| [setSize(int value)](#setSize-int-) | Obtient ou définit la taille du noyau. |
| [getSpatialFactor()](#getSpatialFactor--) | Obtient ou définit le facteur spatial. |
| [setSpatialFactor(double value)](#setSpatialFactor-double-) | Obtient ou définit le facteur spatial. |
| [getSpatialPower()](#getSpatialPower--) | Obtient ou définit la puissance spatiale. |
| [setSpatialPower(double value)](#setSpatialPower-double-) | Obtient ou définit la puissance spatiale. |
| [getColorFactor()](#getColorFactor--) | Obtient ou définit le facteur de couleur. |
| [setColorFactor(double value)](#setColorFactor-double-) | Obtient ou définit le facteur de couleur. |
| [getColorPower()](#getColorPower--) | Obtient ou définit la puissance de couleur. |
| [setColorPower(double value)](#setColorPower-double-) | Obtient ou définit la puissance de couleur. |

## Example: The following example applies various types of filters to a raster image.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Appliquez un filtre médian avec une taille de rectangle de 5 à l'ensemble de l'image.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    rasterImage.save(dir + "sample.MedianFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Appliquez un filtre de lissage bilatéral avec une taille de noyau de 5 à l'ensemble de l'image.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    rasterImage.save(dir + "sample.BilateralSmoothingFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Appliquez un filtre de flou gaussien avec un rayon de 5 et une valeur sigma de 4,0 à l'ensemble de l'image.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussianBlurFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Appliquez un filtre Gauss-Wiener avec un rayon de 5 et une valeur de lissage de 4,0 à l'ensemble de l'image.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Appliquez un filtre wiener de mouvement avec une longueur de 5, une valeur de lissage de 4,0 et un angle de 90,0 degrés à l'ensemble de l'image.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.save(dir + "sample.MotionWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Appliquez un filtre d'accentuation avec une taille de noyau de 5 et une valeur sigma de 4,0 à l'ensemble de l'image.
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


Initialise une nouvelle instance de la classe `BilateralSmoothingFilterOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| taille | int | Taille du noyau. |

### BilateralSmoothingFilterOptions() {#BilateralSmoothingFilterOptions--}
```
public BilateralSmoothingFilterOptions()
```


Initialise une nouvelle instance de la classe `BilateralSmoothingFilterOptions`.

### getSize() {#getSize--}
```
public int getSize()
```


Obtient ou définit la taille du noyau.

Valeur: La taille du noyau.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Obtient ou définit la taille du noyau.

Valeur: La taille du noyau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSpatialFactor() {#getSpatialFactor--}
```
public double getSpatialFactor()
```


Obtient ou définit le facteur spatial.

Valeur: Le facteur spatial.

**Returns:**
double
### setSpatialFactor(double value) {#setSpatialFactor-double-}
```
public void setSpatialFactor(double value)
```


Obtient ou définit le facteur spatial.

Valeur: Le facteur spatial.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### getSpatialPower() {#getSpatialPower--}
```
public double getSpatialPower()
```


Obtient ou définit la puissance spatiale.

Valeur: La puissance spatiale.

**Returns:**
double
### setSpatialPower(double value) {#setSpatialPower-double-}
```
public void setSpatialPower(double value)
```


Obtient ou définit la puissance spatiale.

Valeur: La puissance spatiale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### getColorFactor() {#getColorFactor--}
```
public double getColorFactor()
```


Obtient ou définit le facteur de couleur.

Valeur: Le facteur de couleur.

**Returns:**
double
### setColorFactor(double value) {#setColorFactor-double-}
```
public void setColorFactor(double value)
```


Obtient ou définit le facteur de couleur.

Valeur: Le facteur de couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### getColorPower() {#getColorPower--}
```
public double getColorPower()
```


Obtient ou définit la puissance de couleur.

Valeur: La puissance de couleur.

**Returns:**
double
### setColorPower(double value) {#setColorPower-double-}
```
public void setColorPower(double value)
```


Obtient ou définit la puissance de couleur.

Valeur: La puissance de couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

