---
title: "ResizeType"
second_title: "Aspose.Imaging för Java API-referens"
description: "Anger typ av storleksändring."
type: docs
weight: 97
url: /sv/java/com.aspose.imaging/resizetype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResizeType extends System.Enum
```

Anger typ av storleksändring.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [None](#None) | Pixlarna bevaras inte under storleksändringsoperationen. |
| [LeftTopToLeftTop](#LeftTopToLeftTop) | Den vänstra övre punkten på den nya bilden kommer att sammanfalla med den vänstra övre punkten på originalbilden. |
| [RightTopToRightTop](#RightTopToRightTop) | Den högra övre punkten på den nya bilden kommer att sammanfalla med den högra övre punkten på originalbilden. |
| [RightBottomToRightBottom](#RightBottomToRightBottom) | Den högra nedre punkten på den nya bilden kommer att sammanfalla med den högra nedre punkten på originalbilden. |
| [LeftBottomToLeftBottom](#LeftBottomToLeftBottom) | Den vänstra nedre punkten på den nya bilden kommer att sammanfalla med den vänstra nedre punkten på originalbilden. |
| [CenterToCenter](#CenterToCenter) | Centrum av den nya bilden kommer att sammanfalla med centrum av originalbilden. |
| [LanczosResample](#LanczosResample) | Omprovsampla med lanczos-algoritmen med a=3. |
| [NearestNeighbourResample](#NearestNeighbourResample) | Omprovsampla med närmaste granne-algoritmen. |
| [AdaptiveResample](#AdaptiveResample) | Omprovsampla med adaptiv algoritm baserad på viktad och blandad rationell funktion samt lanczos3-interpolationsalgoritmer. |
| [BilinearResample](#BilinearResample) | Omprovsampla med bilinjär interpolation. |
| [HighQualityResample](#HighQualityResample) | Den högkvalitativa omprovsamplingen |
| [CatmullRom](#CatmullRom) | Den Catmull-Rom kubiska interpolationsmetoden. |
| [CubicConvolution](#CubicConvolution) | Den kubiska konvolutionsinterpolationsmetoden |
| [CubicBSpline](#CubicBSpline) | Den CubicBSpline kubiska interpolationsmetoden |
| [Mitchell](#Mitchell) | Den Mitchell kubiska interpolationsmetoden |
| [SinC](#SinC) | Sinc (Lanczos3) kubisk interpolationsmetod |
| [Bell](#Bell) | Bell interpolationsmetod |

## Example: This example loads an image and resizes it using various resizing methods.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Skala upp 2 gånger med Nearest Neighbour-omprovning.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Skala ner 2 gånger med Nearest Neighbour-omprovning.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Skala upp 2 gånger med bilinjär omprovning.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Skala ner 2 gånger med bilinjär omprovning.
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


Pixlarna bevaras inte under storleksändringsoperationen.

### LeftTopToLeftTop {#LeftTopToLeftTop}
```
public static final int LeftTopToLeftTop
```


Den vänstra övre punkten i den nya bilden kommer att sammanfalla med den vänstra övre punkten i originalbilden. Beskärning sker om det behövs.

### RightTopToRightTop {#RightTopToRightTop}
```
public static final int RightTopToRightTop
```


Den högra övre punkten i den nya bilden kommer att sammanfalla med den högra övre punkten i originalbilden. Beskärning sker om det behövs.

### RightBottomToRightBottom {#RightBottomToRightBottom}
```
public static final int RightBottomToRightBottom
```


Den högra nedre punkten i den nya bilden kommer att sammanfalla med den högra nedre punkten i originalbilden. Beskärning sker om det behövs.

### LeftBottomToLeftBottom {#LeftBottomToLeftBottom}
```
public static final int LeftBottomToLeftBottom
```


Den vänstra nedre punkten i den nya bilden kommer att sammanfalla med den vänstra nedre punkten i originalbilden. Beskärning sker om det behövs.

### CenterToCenter {#CenterToCenter}
```
public static final int CenterToCenter
```


Centrum av den nya bilden kommer att sammanfalla med centrum av originalbilden. Beskärning sker om det behövs.

### LanczosResample {#LanczosResample}
```
public static final int LanczosResample
```


Omprovsampla med lanczos-algoritmen med a=3.

### NearestNeighbourResample {#NearestNeighbourResample}
```
public static final int NearestNeighbourResample
```


Omprovsampla med närmaste granne-algoritmen.

### AdaptiveResample {#AdaptiveResample}
```
public static final int AdaptiveResample
```


Omprovsampla med adaptiv algoritm baserad på viktad och blandad rationell funktion samt lanczos3-interpolationsalgoritmer.

### BilinearResample {#BilinearResample}
```
public static final int BilinearResample
```


Omprovisionera med bilinjär interpolation. Bildförfiltrering är tillåten för att ta bort brus innan omprovning, när det behövs.

### HighQualityResample {#HighQualityResample}
```
public static final int HighQualityResample
```


Den högkvalitativa omprovsamplingen

### CatmullRom {#CatmullRom}
```
public static final int CatmullRom
```


Den Catmull-Rom kubiska interpolationsmetoden.

### CubicConvolution {#CubicConvolution}
```
public static final int CubicConvolution
```


Den kubiska konvolutionsinterpolationsmetoden

### CubicBSpline {#CubicBSpline}
```
public static final int CubicBSpline
```


Den CubicBSpline kubiska interpolationsmetoden

### Mitchell {#Mitchell}
```
public static final int Mitchell
```


Den Mitchell kubiska interpolationsmetoden

### SinC {#SinC}
```
public static final int SinC
```


Sinc (Lanczos3) kubisk interpolationsmetod

### Bell {#Bell}
```
public static final int Bell
```


Bell interpolationsmetod

