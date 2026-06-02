---
title: "BilateralSmoothingFilterOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Las opciones del filtro de suavizado bilateral."
type: docs
weight: 13
url: /es/java/com.aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class BilateralSmoothingFilterOptions extends FilterOptionsBase
```

Las opciones del filtro de suavizado bilateral.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [BilateralSmoothingFilterOptions(int size)](#BilateralSmoothingFilterOptions-int-) | Inicializa una nueva instancia de la clase `BilateralSmoothingFilterOptions`. |
| [BilateralSmoothingFilterOptions()](#BilateralSmoothingFilterOptions--) | Inicializa una nueva instancia de la clase `BilateralSmoothingFilterOptions`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSize()](#getSize--) | Obtiene o establece el tamaño del kernel. |
| [setSize(int value)](#setSize-int-) | Obtiene o establece el tamaño del kernel. |
| [getSpatialFactor()](#getSpatialFactor--) | Obtiene o establece el factor espacial. |
| [setSpatialFactor(double value)](#setSpatialFactor-double-) | Obtiene o establece el factor espacial. |
| [getSpatialPower()](#getSpatialPower--) | Obtiene o establece la potencia espacial. |
| [setSpatialPower(double value)](#setSpatialPower-double-) | Obtiene o establece la potencia espacial. |
| [getColorFactor()](#getColorFactor--) | Obtiene o establece el factor de color. |
| [setColorFactor(double value)](#setColorFactor-double-) | Obtiene o establece el factor de color. |
| [getColorPower()](#getColorPower--) | Obtiene o establece la potencia de color. |
| [setColorPower(double value)](#setColorPower-double-) | Obtiene o establece la potencia de color. |

## Example: The following example applies various types of filters to a raster image.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Aplica un filtro mediano con un tamaño de rectángulo de 5 a toda la imagen.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    rasterImage.save(dir + "sample.MedianFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Aplica un filtro de suavizado bilateral con un tamaño de kernel de 5 a toda la imagen.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    rasterImage.save(dir + "sample.BilateralSmoothingFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Aplica un filtro de desenfoque gaussiano con un radio de 5 y un valor sigma de 4.0 a toda la imagen.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussianBlurFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Aplica un filtro Gauss-Wiener con un radio de 5 y un valor de suavizado de 4.0 a toda la imagen.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Aplica un filtro wiener de movimiento con una longitud de 5, un valor de suavizado de 4.0 y un ángulo de 90.0 grados a toda la imagen.
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.save(dir + "sample.MotionWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // Aplica un filtro de nitidez con un tamaño de kernel de 5 y un valor sigma de 4.0 a toda la imagen.
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


Inicializa una nueva instancia de la clase `BilateralSmoothingFilterOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | int | Tamaño del kernal. |

### BilateralSmoothingFilterOptions() {#BilateralSmoothingFilterOptions--}
```
public BilateralSmoothingFilterOptions()
```


Inicializa una nueva instancia de la clase `BilateralSmoothingFilterOptions`.

### getSize() {#getSize--}
```
public int getSize()
```


Obtiene o establece el tamaño del kernel.

Valor: El tamaño del kernel.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Obtiene o establece el tamaño del kernel.

Valor: El tamaño del kernel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSpatialFactor() {#getSpatialFactor--}
```
public double getSpatialFactor()
```


Obtiene o establece el factor espacial.

Valor: El factor espacial.

**Returns:**
double
### setSpatialFactor(double value) {#setSpatialFactor-double-}
```
public void setSpatialFactor(double value)
```


Obtiene o establece el factor espacial.

Valor: El factor espacial.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### getSpatialPower() {#getSpatialPower--}
```
public double getSpatialPower()
```


Obtiene o establece la potencia espacial.

Valor: La potencia espacial.

**Returns:**
double
### setSpatialPower(double value) {#setSpatialPower-double-}
```
public void setSpatialPower(double value)
```


Obtiene o establece la potencia espacial.

Valor: La potencia espacial.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### getColorFactor() {#getColorFactor--}
```
public double getColorFactor()
```


Obtiene o establece el factor de color.

Valor: El factor de color.

**Returns:**
double
### setColorFactor(double value) {#setColorFactor-double-}
```
public void setColorFactor(double value)
```


Obtiene o establece el factor de color.

Valor: El factor de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### getColorPower() {#getColorPower--}
```
public double getColorPower()
```


Obtiene o establece la potencia de color.

Valor: La potencia de color.

**Returns:**
double
### setColorPower(double value) {#setColorPower-double-}
```
public void setColorPower(double value)
```


Obtiene o establece la potencia de color.

Valor: La potencia de color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

