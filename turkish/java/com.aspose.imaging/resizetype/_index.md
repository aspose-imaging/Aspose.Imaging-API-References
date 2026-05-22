---
title: "ResizeType"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Yeniden boyutlandırma tipini belirtir."
type: docs
weight: 97
url: /tr/java/com.aspose.imaging/resizetype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResizeType extends System.Enum
```

Yeniden boyutlandırma tipini belirtir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [None](#None) | Piksel, yeniden boyutlandırma işlemi sırasında korunmaz. |
| [LeftTopToLeftTop](#LeftTopToLeftTop) | Yeni görüntünün sol üst noktası, orijinal görüntünün sol üst noktasıyla aynı olacaktır. |
| [RightTopToRightTop](#RightTopToRightTop) | Yeni görüntünün sağ üst noktası, orijinal görüntünün sağ üst noktasıyla aynı olacaktır. |
| [RightBottomToRightBottom](#RightBottomToRightBottom) | Yeni görüntünün sağ alt noktası, orijinal görüntünün sağ alt noktasıyla aynı olacaktır. |
| [LeftBottomToLeftBottom](#LeftBottomToLeftBottom) | Yeni görüntünün sol alt noktası, orijinal görüntünün sol alt noktasıyla aynı olacaktır. |
| [CenterToCenter](#CenterToCenter) | Yeni görüntünün merkezi, orijinal görüntünün merkeziyle aynı olacaktır. |
| [LanczosResample](#LanczosResample) | a=3 ile lanczos algoritması kullanılarak yeniden örnekleme yapılır. |
| [NearestNeighbourResample](#NearestNeighbourResample) | En yakın komşu algoritması kullanılarak yeniden örnekleme yapılır. |
| [AdaptiveResample](#AdaptiveResample) | Ağırlıklı ve karıştırılmış rasyonel fonksiyon ve lanczos3 interpolasyon algoritmalarına dayalı uyarlamalı algoritma kullanılarak yeniden örnekleme yapılır. |
| [BilinearResample](#BilinearResample) | İkili doğrusal interpolasyon kullanılarak yeniden örnekleme yapılır. |
| [HighQualityResample](#HighQualityResample) | Yüksek kaliteli yeniden örnekleme |
| [CatmullRom](#CatmullRom) | Catmull-Rom kübik interpolasyon yöntemi. |
| [CubicConvolution](#CubicConvolution) | Kübik Konvolüsyon interpolasyon yöntemi |
| [CubicBSpline](#CubicBSpline) | CubicBSpline kübik interpolasyon yöntemi |
| [Mitchell](#Mitchell) | Mitchell kübik interpolasyon yöntemi |
| [SinC](#SinC) | Sinc (Lanczos3) kübik enterpolasyon yöntemi |
| [Bell](#Bell) | Bell enterpolasyon yöntemi |

## Example: This example loads an image and resizes it using various resizing methods.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat büyüt.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat küçült.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat büyüt.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat küçült.
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


Piksel, yeniden boyutlandırma işlemi sırasında korunmaz.

### LeftTopToLeftTop {#LeftTopToLeftTop}
```
public static final int LeftTopToLeftTop
```


Yeni görüntünün sol üst noktası, orijinal görüntünün sol üst noktasıyla aynı konumda olacaktır. Gerekirse kırpma yapılacaktır.

### RightTopToRightTop {#RightTopToRightTop}
```
public static final int RightTopToRightTop
```


Yeni görüntünün sağ üst noktası, orijinal görüntünün sağ üst noktasıyla aynı konumda olacaktır. Gerekirse kırpma yapılacaktır.

### RightBottomToRightBottom {#RightBottomToRightBottom}
```
public static final int RightBottomToRightBottom
```


Yeni görüntünün sağ alt noktası, orijinal görüntünün sağ alt noktasıyla aynı konumda olacaktır. Gerekirse kırpma yapılacaktır.

### LeftBottomToLeftBottom {#LeftBottomToLeftBottom}
```
public static final int LeftBottomToLeftBottom
```


Yeni görüntünün sol alt noktası, orijinal görüntünün sol alt noktasıyla aynı konumda olacaktır. Gerekirse kırpma yapılacaktır.

### CenterToCenter {#CenterToCenter}
```
public static final int CenterToCenter
```


Yeni görüntünün merkezi, orijinal görüntünün merkeziyle aynı konumda olacaktır. Gerekirse kırpma yapılacaktır.

### LanczosResample {#LanczosResample}
```
public static final int LanczosResample
```


a=3 ile lanczos algoritması kullanılarak yeniden örnekleme yapılır.

### NearestNeighbourResample {#NearestNeighbourResample}
```
public static final int NearestNeighbourResample
```


En yakın komşu algoritması kullanılarak yeniden örnekleme yapılır.

### AdaptiveResample {#AdaptiveResample}
```
public static final int AdaptiveResample
```


Ağırlıklı ve karıştırılmış rasyonel fonksiyon ve lanczos3 interpolasyon algoritmalarına dayalı uyarlamalı algoritma kullanılarak yeniden örnekleme yapılır.

### BilinearResample {#BilinearResample}
```
public static final int BilinearResample
```


İkili doğrusal enterpolasyon kullanarak yeniden örnekleme yapın. Gerektiğinde yeniden örneklemeden önce gürültüyü kaldırmak için görüntü ön filtrelemesine izin verilir.

### HighQualityResample {#HighQualityResample}
```
public static final int HighQualityResample
```


Yüksek kaliteli yeniden örnekleme

### CatmullRom {#CatmullRom}
```
public static final int CatmullRom
```


Catmull-Rom kübik interpolasyon yöntemi.

### CubicConvolution {#CubicConvolution}
```
public static final int CubicConvolution
```


Kübik Konvolüsyon interpolasyon yöntemi

### CubicBSpline {#CubicBSpline}
```
public static final int CubicBSpline
```


CubicBSpline kübik interpolasyon yöntemi

### Mitchell {#Mitchell}
```
public static final int Mitchell
```


Mitchell kübik interpolasyon yöntemi

### SinC {#SinC}
```
public static final int SinC
```


Sinc (Lanczos3) kübik enterpolasyon yöntemi

### Bell {#Bell}
```
public static final int Bell
```


Bell enterpolasyon yöntemi

