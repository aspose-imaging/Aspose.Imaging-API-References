---
title: "SharpenFilterOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Las opciones del filtro de enfoque."
type: docs
weight: 25
url: /es/java/com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions), [com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions)
```
public class SharpenFilterOptions extends GaussianBlurFilterOptions
```

Las opciones del filtro de enfoque.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [SharpenFilterOptions(int size, double sigma)](#SharpenFilterOptions-int-double-) | Inicializa una nueva instancia de la clase [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions). |
| [SharpenFilterOptions()](#SharpenFilterOptions--) | Inicializa una nueva instancia de la clase [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getKernel()](#getKernel--) | Obtiene el kernel. |
| [getSize()](#getSize--) | Obtiene el tamaño del núcleo gaussiano. |
| [setSize(int value)](#setSize-int-) | El tamaño del kernel gaussiano. |
| [getSigma()](#getSigma--) | Obtiene la sigma del núcleo gaussiano (suavizado). |
| [setSigma(double value)](#setSigma-double-) | El sigma del kernel gaussiano (suavizado). |

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

### SharpenFilterOptions(int size, double sigma) {#SharpenFilterOptions-int-double-}
```
public SharpenFilterOptions(int size, double sigma)
```


Inicializa una nueva instancia de la clase [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| size | int | El tamaño del kernel. |
| sigma | double | La sigma. |

### SharpenFilterOptions() {#SharpenFilterOptions--}
```
public SharpenFilterOptions()
```


Inicializa una nueva instancia de la clase [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions).

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


Obtiene el kernel.

**Returns:**
double[][] - el núcleo.
### getSize() {#getSize--}
```
public int getSize()
```


Obtiene el tamaño del kernel gaussiano. Debe ser un valor impar positivo distinto de cero.

**Returns:**
int - el tamaño del kernel gaussiano.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


El tamaño del kernel gaussiano. Debe ser un valor impar positivo distinto de cero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el tamaño del kernel gaussiano. |

### getSigma() {#getSigma--}
```
public double getSigma()
```


Obtiene el sigma del kernel gaussiano (suavizado). Debe ser un valor positivo distinto de cero.

**Returns:**
double - el sigma del kernel gaussiano (suavizado).
### setSigma(double value) {#setSigma-double-}
```
public void setSigma(double value)
```


El sigma del kernel gaussiano (suavizado). Debe ser un valor positivo distinto de cero.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | el sigma del kernel gaussiano (suavizado). |

