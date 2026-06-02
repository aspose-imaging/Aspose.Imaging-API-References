---
title: "MedianFilterOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Filtro mediano"
type: docs
weight: 22
url: /es/java/com.aspose.imaging.imagefilters.filteroptions/medianfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class MedianFilterOptions extends FilterOptionsBase
```

Filtro mediano
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MedianFilterOptions(int size)](#MedianFilterOptions-int-) | Inicializa una nueva instancia de la clase `MedianFilterOptions`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSize()](#getSize--) | Obtiene o establece el tamaño. |
| [setSize(int value)](#setSize-int-) | Obtiene o establece el tamaño. |

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

### MedianFilterOptions(int size) {#MedianFilterOptions-int-}
```
public MedianFilterOptions(int size)
```


Inicializa una nueva instancia de la clase `MedianFilterOptions`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | int | El tamaño del rectángulo del filtro. |

### getSize() {#getSize--}
```
public int getSize()
```


Obtiene o establece el tamaño.

Valor: El tamaño del rectángulo del filtro.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Obtiene o establece el tamaño.

Valor: El tamaño del rectángulo del filtro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

