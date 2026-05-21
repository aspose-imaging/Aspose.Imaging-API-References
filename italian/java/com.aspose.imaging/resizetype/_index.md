---
title: "ResizeType"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Specifica il tipo di ridimensionamento."
type: docs
weight: 97
url: /it/java/com.aspose.imaging/resizetype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResizeType extends System.Enum
```

Specifica il tipo di ridimensionamento.
## Campi

| Campo | Descrizione |
| --- | --- |
| [None](#None) | I pixel non sono conservati durante l'operazione di ridimensionamento. |
| [LeftTopToLeftTop](#LeftTopToLeftTop) | Il punto in alto a sinistra della nuova immagine coinciderà con il punto in alto a sinistra dell'immagine originale. |
| [RightTopToRightTop](#RightTopToRightTop) | Il punto in alto a destra della nuova immagine coinciderà con il punto in alto a destra dell'immagine originale. |
| [RightBottomToRightBottom](#RightBottomToRightBottom) | Il punto in basso a destra della nuova immagine coinciderà con il punto in basso a destra dell'immagine originale. |
| [LeftBottomToLeftBottom](#LeftBottomToLeftBottom) | Il punto in basso a sinistra della nuova immagine coinciderà con il punto in basso a sinistra dell'immagine originale. |
| [CenterToCenter](#CenterToCenter) | Il centro della nuova immagine coinciderà con il centro dell'immagine originale. |
| [LanczosResample](#LanczosResample) | Ricampiona usando l'algoritmo Lanczos con a=3. |
| [NearestNeighbourResample](#NearestNeighbourResample) | Ricampiona usando l'algoritmo del vicino più prossimo. |
| [AdaptiveResample](#AdaptiveResample) | Ricampiona usando un algoritmo adattivo basato su funzione razionale pesata e mescolata e sugli algoritmi di interpolazione Lanczos3. |
| [BilinearResample](#BilinearResample) | Ricampiona usando l'interpolazione bilineare. |
| [HighQualityResample](#HighQualityResample) | Il ricampionamento ad alta qualità |
| [CatmullRom](#CatmullRom) | Il metodo di interpolazione cubica Catmull-Rom. |
| [CubicConvolution](#CubicConvolution) | Il metodo di interpolazione Cubic Convolution |
| [CubicBSpline](#CubicBSpline) | Il metodo di interpolazione cubica CubicBSpline |
| [Mitchell](#Mitchell) | Il metodo di interpolazione cubica Mitchell |
| [SinC](#SinC) | Il metodo di interpolazione cubica Sinc (Lanczos3) |
| [Bell](#Bell) | Il metodo di interpolazione Bell |

## Example: This example loads an image and resizes it using various resizing methods.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Riduci di 2 volte usando il ricampionamento Nearest Neighbour.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Ingrandisci di 2 volte usando il ricampionamento Bilineare.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Riduci di 2 volte usando il ricampionamento Bilineare.
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


I pixel non sono conservati durante l'operazione di ridimensionamento.

### LeftTopToLeftTop {#LeftTopToLeftTop}
```
public static final int LeftTopToLeftTop
```


Il punto in alto a sinistra della nuova immagine coinciderà con il punto in alto a sinistra dell'immagine originale. Il ritaglio avverrà se necessario.

### RightTopToRightTop {#RightTopToRightTop}
```
public static final int RightTopToRightTop
```


Il punto in alto a destra della nuova immagine coinciderà con il punto in alto a destra dell'immagine originale. Il ritaglio avverrà se necessario.

### RightBottomToRightBottom {#RightBottomToRightBottom}
```
public static final int RightBottomToRightBottom
```


Il punto in basso a destra della nuova immagine coinciderà con il punto in basso a destra dell'immagine originale. Il ritaglio avverrà se necessario.

### LeftBottomToLeftBottom {#LeftBottomToLeftBottom}
```
public static final int LeftBottomToLeftBottom
```


Il punto in basso a sinistra della nuova immagine coinciderà con il punto in basso a sinistra dell'immagine originale. Il ritaglio avverrà se necessario.

### CenterToCenter {#CenterToCenter}
```
public static final int CenterToCenter
```


Il centro della nuova immagine coinciderà con il centro dell'immagine originale. Il ritaglio avverrà se necessario.

### LanczosResample {#LanczosResample}
```
public static final int LanczosResample
```


Ricampiona usando l'algoritmo Lanczos con a=3.

### NearestNeighbourResample {#NearestNeighbourResample}
```
public static final int NearestNeighbourResample
```


Ricampiona usando l'algoritmo del vicino più prossimo.

### AdaptiveResample {#AdaptiveResample}
```
public static final int AdaptiveResample
```


Ricampiona usando un algoritmo adattivo basato su funzione razionale pesata e mescolata e sugli algoritmi di interpolazione Lanczos3.

### BilinearResample {#BilinearResample}
```
public static final int BilinearResample
```


Ricampiona usando l'interpolazione bilineare. È consentito il pre-filtraggio dell'immagine per rimuovere il rumore prima del ricampionamento, quando necessario.

### HighQualityResample {#HighQualityResample}
```
public static final int HighQualityResample
```


Il ricampionamento ad alta qualità

### CatmullRom {#CatmullRom}
```
public static final int CatmullRom
```


Il metodo di interpolazione cubica Catmull-Rom.

### CubicConvolution {#CubicConvolution}
```
public static final int CubicConvolution
```


Il metodo di interpolazione Cubic Convolution

### CubicBSpline {#CubicBSpline}
```
public static final int CubicBSpline
```


Il metodo di interpolazione cubica CubicBSpline

### Mitchell {#Mitchell}
```
public static final int Mitchell
```


Il metodo di interpolazione cubica Mitchell

### SinC {#SinC}
```
public static final int SinC
```


Il metodo di interpolazione cubica Sinc (Lanczos3)

### Bell {#Bell}
```
public static final int Bell
```


Il metodo di interpolazione Bell

