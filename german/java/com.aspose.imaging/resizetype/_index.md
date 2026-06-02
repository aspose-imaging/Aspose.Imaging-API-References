---
title: "ResizeType"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Gibt den Skalierungstyp an."
type: docs
weight: 97
url: /de/java/com.aspose.imaging/resizetype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResizeType extends System.Enum
```

Gibt den Skalierungstyp an.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [None](#None) | Die Pixel werden während des Resize-Vorgangs nicht beibehalten. |
| [LeftTopToLeftTop](#LeftTopToLeftTop) | Der linke obere Punkt des neuen Bildes wird mit dem linken oberen Punkt des Originalbildes übereinstimmen. |
| [RightTopToRightTop](#RightTopToRightTop) | Der rechte obere Punkt des neuen Bildes wird mit dem rechten oberen Punkt des Originalbildes übereinstimmen. |
| [RightBottomToRightBottom](#RightBottomToRightBottom) | Der rechte untere Punkt des neuen Bildes wird mit dem rechten unteren Punkt des Originalbildes übereinstimmen. |
| [LeftBottomToLeftBottom](#LeftBottomToLeftBottom) | Der linke untere Punkt des neuen Bildes wird mit dem linken unteren Punkt des Originalbildes übereinstimmen. |
| [CenterToCenter](#CenterToCenter) | Die Mitte des neuen Bildes wird mit der Mitte des Originalbildes übereinstimmen. |
| [LanczosResample](#LanczosResample) | Neu abtasten mit dem Lanczos-Algorithmus bei a=3. |
| [NearestNeighbourResample](#NearestNeighbourResample) | Neu abtasten mit dem Nächster-Nachbar-Algorithmus. |
| [AdaptiveResample](#AdaptiveResample) | Neu abtasten mit einem adaptiven Algorithmus, basierend auf gewichteten und gemischten rationalen Funktionen und Lanczos3-Interpolationsalgorithmen. |
| [BilinearResample](#BilinearResample) | Neu abtasten mit bilinearer Interpolation. |
| [HighQualityResample](#HighQualityResample) | Das hochqualitative Resampling |
| [CatmullRom](#CatmullRom) | Die Catmull-Rom-Kubische Interpolationsmethode. |
| [CubicConvolution](#CubicConvolution) | Die Kubische Konvolutions-Interpolationsmethode |
| [CubicBSpline](#CubicBSpline) | Die CubicBSpline-Kubische Interpolationsmethode |
| [Mitchell](#Mitchell) | Die Mitchell-Kubische Interpolationsmethode |
| [SinC](#SinC) | Die Sinc (Lanczos3) kubische Interpolationsmethode |
| [Bell](#Bell) | Die Bell-Interpolationsmethode |

## Example: This example loads an image and resizes it using various resizing methods.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Vergrößern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Verkleinern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Vergrößern um das 2‑fache mit bilinearer Resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Verkleinern um das 2‑fache mit bilinearer Resampling.
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


Die Pixel werden während des Resize-Vorgangs nicht beibehalten.

### LeftTopToLeftTop {#LeftTopToLeftTop}
```
public static final int LeftTopToLeftTop
```


Der linke obere Punkt des neuen Bildes wird mit dem linken oberen Punkt des Originalbildes übereinstimmen. Ein Beschnitt wird bei Bedarf durchgeführt.

### RightTopToRightTop {#RightTopToRightTop}
```
public static final int RightTopToRightTop
```


Der rechte obere Punkt des neuen Bildes wird mit dem rechten oberen Punkt des Originalbildes übereinstimmen. Ein Beschnitt wird bei Bedarf durchgeführt.

### RightBottomToRightBottom {#RightBottomToRightBottom}
```
public static final int RightBottomToRightBottom
```


Der rechte untere Punkt des neuen Bildes wird mit dem rechten unteren Punkt des Originalbildes übereinstimmen. Ein Beschnitt wird bei Bedarf durchgeführt.

### LeftBottomToLeftBottom {#LeftBottomToLeftBottom}
```
public static final int LeftBottomToLeftBottom
```


Der linke untere Punkt des neuen Bildes wird mit dem linken unteren Punkt des Originalbildes übereinstimmen. Ein Beschnitt wird bei Bedarf durchgeführt.

### CenterToCenter {#CenterToCenter}
```
public static final int CenterToCenter
```


Die Mitte des neuen Bildes wird mit der Mitte des Originalbildes übereinstimmen. Ein Beschnitt wird bei Bedarf durchgeführt.

### LanczosResample {#LanczosResample}
```
public static final int LanczosResample
```


Neu abtasten mit dem Lanczos-Algorithmus bei a=3.

### NearestNeighbourResample {#NearestNeighbourResample}
```
public static final int NearestNeighbourResample
```


Neu abtasten mit dem Nächster-Nachbar-Algorithmus.

### AdaptiveResample {#AdaptiveResample}
```
public static final int AdaptiveResample
```


Neu abtasten mit einem adaptiven Algorithmus, basierend auf gewichteten und gemischten rationalen Funktionen und Lanczos3-Interpolationsalgorithmen.

### BilinearResample {#BilinearResample}
```
public static final int BilinearResample
```


Neu abtasten mit bilinearer Interpolation. Bildvorfilterung ist erlaubt, um das Rauschen vor dem Neusampling zu entfernen, wenn nötig.

### HighQualityResample {#HighQualityResample}
```
public static final int HighQualityResample
```


Das hochqualitative Resampling

### CatmullRom {#CatmullRom}
```
public static final int CatmullRom
```


Die Catmull-Rom-Kubische Interpolationsmethode.

### CubicConvolution {#CubicConvolution}
```
public static final int CubicConvolution
```


Die Kubische Konvolutions-Interpolationsmethode

### CubicBSpline {#CubicBSpline}
```
public static final int CubicBSpline
```


Die CubicBSpline-Kubische Interpolationsmethode

### Mitchell {#Mitchell}
```
public static final int Mitchell
```


Die Mitchell-Kubische Interpolationsmethode

### SinC {#SinC}
```
public static final int SinC
```


Die Sinc (Lanczos3) kubische Interpolationsmethode

### Bell {#Bell}
```
public static final int Bell
```


Die Bell-Interpolationsmethode

