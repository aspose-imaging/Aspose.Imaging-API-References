---
title: "ResizeType"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "指定调整大小的类型。"
type: docs
weight: 97
url: /zh/java/com.aspose.imaging/resizetype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResizeType extends System.Enum
```

指定调整大小的类型。
## 字段

| 字段 | 描述 |
| --- | --- |
| [None](#None) | 在调整大小操作期间，像素不会被保留。 |
| [LeftTopToLeftTop](#LeftTopToLeftTop) | 新图像的左上点将与原始图像的左上点重合。 |
| [RightTopToRightTop](#RightTopToRightTop) | 新图像的右上点将与原始图像的右上点重合。 |
| [RightBottomToRightBottom](#RightBottomToRightBottom) | 新图像的右下点将与原始图像的右下点重合。 |
| [LeftBottomToLeftBottom](#LeftBottomToLeftBottom) | 新图像的左下点将与原始图像的左下点重合。 |
| [CenterToCenter](#CenterToCenter) | 新图像的中心将与原始图像的中心重合。 |
| [LanczosResample](#LanczosResample) | 使用 a=3 的 lanczos 算法重新采样。 |
| [NearestNeighbourResample](#NearestNeighbourResample) | 使用最近邻算法重新采样。 |
| [AdaptiveResample](#AdaptiveResample) | 使用基于加权和混合有理函数以及 lanczos3 插值算法的自适应算法重新采样。 |
| [BilinearResample](#BilinearResample) | 使用双线性插值重新采样。 |
| [HighQualityResample](#HighQualityResample) | 高质量重新采样 |
| [CatmullRom](#CatmullRom) | Catmull-Rom 三次插值方法。 |
| [CubicConvolution](#CubicConvolution) | 该 Cubic Convolution 插值方法 |
| [CubicBSpline](#CubicBSpline) | 该 CubicBSpline 三次插值方法 |
| [Mitchell](#Mitchell) | 该 Mitchell 三次插值方法 |
| [SinC](#SinC) | 该 Sinc（Lanczos3）三次插值方法 |
| [Bell](#Bell) | 该 Bell 插值方法 |

## Example: This example loads an image and resizes it using various resizing methods.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // 使用最近邻重采样将尺寸放大 2 倍。
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // 使用最近邻重采样将尺寸缩小 2 倍。
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // 使用双线性重采样将尺寸放大 2 倍。
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // 使用双线性重采样将尺寸缩小 2 倍。
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


在调整大小操作期间，像素不会被保留。

### LeftTopToLeftTop {#LeftTopToLeftTop}
```
public static final int LeftTopToLeftTop
```


新图像的左上点将与原始图像的左上点重合。如有需要，将进行裁剪。

### RightTopToRightTop {#RightTopToRightTop}
```
public static final int RightTopToRightTop
```


新图像的右上点将与原始图像的右上点重合。如有需要，将进行裁剪。

### RightBottomToRightBottom {#RightBottomToRightBottom}
```
public static final int RightBottomToRightBottom
```


新图像的右下点将与原始图像的右下点重合。如有需要，将进行裁剪。

### LeftBottomToLeftBottom {#LeftBottomToLeftBottom}
```
public static final int LeftBottomToLeftBottom
```


新图像的左下点将与原始图像的左下点重合。如有需要，将进行裁剪。

### CenterToCenter {#CenterToCenter}
```
public static final int CenterToCenter
```


新图像的中心将与原始图像的中心重合。如有需要，将进行裁剪。

### LanczosResample {#LanczosResample}
```
public static final int LanczosResample
```


使用 a=3 的 lanczos 算法重新采样。

### NearestNeighbourResample {#NearestNeighbourResample}
```
public static final int NearestNeighbourResample
```


使用最近邻算法重新采样。

### AdaptiveResample {#AdaptiveResample}
```
public static final int AdaptiveResample
```


使用基于加权和混合有理函数以及 lanczos3 插值算法的自适应算法重新采样。

### BilinearResample {#BilinearResample}
```
public static final int BilinearResample
```


使用双线性插值进行重采样。需要时，可在重采样前进行图像预过滤以去除噪声。

### HighQualityResample {#HighQualityResample}
```
public static final int HighQualityResample
```


高质量重新采样

### CatmullRom {#CatmullRom}
```
public static final int CatmullRom
```


Catmull-Rom 三次插值方法。

### CubicConvolution {#CubicConvolution}
```
public static final int CubicConvolution
```


该 Cubic Convolution 插值方法

### CubicBSpline {#CubicBSpline}
```
public static final int CubicBSpline
```


该 CubicBSpline 三次插值方法

### Mitchell {#Mitchell}
```
public static final int Mitchell
```


该 Mitchell 三次插值方法

### SinC {#SinC}
```
public static final int SinC
```


该 Sinc（Lanczos3）三次插值方法

### Bell {#Bell}
```
public static final int Bell
```


该 Bell 插值方法

