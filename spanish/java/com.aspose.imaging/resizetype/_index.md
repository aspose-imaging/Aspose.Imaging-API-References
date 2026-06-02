---
title: "ResizeType"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Especifica el tipo de redimensionamiento."
type: docs
weight: 97
url: /es/java/com.aspose.imaging/resizetype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResizeType extends System.Enum
```

Especifica el tipo de redimensionamiento.
## Campos

| Campo | Descripción |
| --- | --- |
| [None](#None) | Los píxeles no se conservan durante la operación de cambio de tamaño. |
| [LeftTopToLeftTop](#LeftTopToLeftTop) | El punto superior izquierdo de la nueva imagen coincidirá con el punto superior izquierdo de la imagen original. |
| [RightTopToRightTop](#RightTopToRightTop) | El punto superior derecho de la nueva imagen coincidirá con el punto superior derecho de la imagen original. |
| [RightBottomToRightBottom](#RightBottomToRightBottom) | El punto inferior derecho de la nueva imagen coincidirá con el punto inferior derecho de la imagen original. |
| [LeftBottomToLeftBottom](#LeftBottomToLeftBottom) | El punto inferior izquierdo de la nueva imagen coincidirá con el punto inferior izquierdo de la imagen original. |
| [CenterToCenter](#CenterToCenter) | El centro de la nueva imagen coincidirá con el centro de la imagen original. |
| [LanczosResample](#LanczosResample) | Remuestrear usando el algoritmo Lanczos con a=3. |
| [NearestNeighbourResample](#NearestNeighbourResample) | Remuestrear usando el algoritmo del vecino más cercano. |
| [AdaptiveResample](#AdaptiveResample) | Remuestrear usando un algoritmo adaptativo basado en funciones racionales ponderadas y combinadas y algoritmos de interpolación Lanczos3. |
| [BilinearResample](#BilinearResample) | Remuestrear usando interpolación bilineal. |
| [HighQualityResample](#HighQualityResample) | El remuestreo de alta calidad |
| [CatmullRom](#CatmullRom) | El método de interpolación cúbica Catmull-Rom. |
| [CubicConvolution](#CubicConvolution) | El método de interpolación Convolución Cúbica |
| [CubicBSpline](#CubicBSpline) | El método de interpolación cúbica CubicBSpline |
| [Mitchell](#Mitchell) | El método de interpolación cúbica Mitchell |
| [SinC](#SinC) | El método de interpolación cúbica Sinc (Lanczos3) |
| [Bell](#Bell) | El método de interpolación Bell |

## Example: This example loads an image and resizes it using various resizing methods.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Escalar 2 veces usando remuestreo de vecino más cercano.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Reducir 2 veces usando remuestreo de vecino más cercano.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Escalar 2 veces usando remuestreo bilineal.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Reducir 2 veces usando remuestreo bilineal.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```


## Example: Resize image using specific Resize Type.

``` java
try (Image image = Image.load("Photo.jpg"))
{
    image.resize(640, 480, ResizeType.CatmullRom);
    image.save("ResizedPhoto.jpg");

    image.resize(1024, 768, ResizeType.CubicConvolution);
    image.save("ResizedPhoto2.jpg");

    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    resizeSettings.setMode(ResizeType.CubicBSpline);
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);

    image.resize(800, 800, resizeSettings);
    image.save("ResizedPhoto3.jpg");
}
```

### None {#None}
```
public static final int None
```


Los píxeles no se conservan durante la operación de cambio de tamaño.

### LeftTopToLeftTop {#LeftTopToLeftTop}
```
public static final int LeftTopToLeftTop
```


El punto superior izquierdo de la nueva imagen coincidirá con el punto superior izquierdo de la imagen original. Se recortará si es necesario.

### RightTopToRightTop {#RightTopToRightTop}
```
public static final int RightTopToRightTop
```


El punto superior derecho de la nueva imagen coincidirá con el punto superior derecho de la imagen original. Se recortará si es necesario.

### RightBottomToRightBottom {#RightBottomToRightBottom}
```
public static final int RightBottomToRightBottom
```


El punto inferior derecho de la nueva imagen coincidirá con el punto inferior derecho de la imagen original. Se recortará si es necesario.

### LeftBottomToLeftBottom {#LeftBottomToLeftBottom}
```
public static final int LeftBottomToLeftBottom
```


El punto inferior izquierdo de la nueva imagen coincidirá con el punto inferior izquierdo de la imagen original. Se recortará si es necesario.

### CenterToCenter {#CenterToCenter}
```
public static final int CenterToCenter
```


El centro de la nueva imagen coincidirá con el centro de la imagen original. Se recortará si es necesario.

### LanczosResample {#LanczosResample}
```
public static final int LanczosResample
```


Remuestrear usando el algoritmo Lanczos con a=3.

### NearestNeighbourResample {#NearestNeighbourResample}
```
public static final int NearestNeighbourResample
```


Remuestrear usando el algoritmo del vecino más cercano.

### AdaptiveResample {#AdaptiveResample}
```
public static final int AdaptiveResample
```


Remuestrear usando un algoritmo adaptativo basado en funciones racionales ponderadas y combinadas y algoritmos de interpolación Lanczos3.

### BilinearResample {#BilinearResample}
```
public static final int BilinearResample
```


Remuestrear usando interpolación bilineal. Se permite el prefiltrado de la imagen para eliminar el ruido antes del remuestreo, cuando sea necesario.

### HighQualityResample {#HighQualityResample}
```
public static final int HighQualityResample
```


El remuestreo de alta calidad

### CatmullRom {#CatmullRom}
```
public static final int CatmullRom
```


El método de interpolación cúbica Catmull-Rom.

### CubicConvolution {#CubicConvolution}
```
public static final int CubicConvolution
```


El método de interpolación Convolución Cúbica

### CubicBSpline {#CubicBSpline}
```
public static final int CubicBSpline
```


El método de interpolación cúbica CubicBSpline

### Mitchell {#Mitchell}
```
public static final int Mitchell
```


El método de interpolación cúbica Mitchell

### SinC {#SinC}
```
public static final int SinC
```


El método de interpolación cúbica Sinc (Lanczos3)

### Bell {#Bell}
```
public static final int Bell
```


El método de interpolación Bell

