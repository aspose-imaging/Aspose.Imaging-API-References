---
title: "GaussWienerFilterOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "用于图像去模糊的高斯维纳滤镜选项。"
type: docs
weight: 18
url: /zh/java/com.aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions), [com.aspose.imaging.imagefilters.filteroptions.GaussianDeconvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussiandeconvolutionfilteroptions)
```
public class GaussWienerFilterOptions extends GaussianDeconvolutionFilterOptions
```

用于图像去模糊的高斯维纳滤镜选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GaussWienerFilterOptions(int size, double sigma)](#GaussWienerFilterOptions-int-double-) | 初始化 [GaussWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions) 类的新实例。 |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions--) | 初始化 [GaussWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getKernel()](#getKernel--) | 获取核。 |

## Example: The following example applies various types of filters to a raster image.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 对整幅图像应用矩形大小为5的中值滤波器。
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    rasterImage.save(dir + "sample.MedianFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 对整幅图像应用核大小为5的双边平滑滤波器。
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    rasterImage.save(dir + "sample.BilateralSmoothingFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 对整幅图像应用半径为5、sigma值为4.0的高斯模糊滤波器。
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussianBlurFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 对整幅图像应用半径为5、平滑值为4.0的Gauss-Wiener滤波器。
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 对整幅图像应用长度为5、平滑值为4.0、角度为90.0度的运动Wiener滤波器。
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.save(dir + "sample.MotionWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 对整幅图像应用核大小为5、sigma值为4.0的锐化滤波器。
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.SharpenFilter.png");
} finally {
    image.dispose();
}
```

### GaussWienerFilterOptions(int size, double sigma) {#GaussWienerFilterOptions-int-double-}
```
public GaussWienerFilterOptions(int size, double sigma)
```


初始化 [GaussWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | int | 高斯核的大小。 |
| sigma | double | 高斯核的 sigma。 |

### GaussWienerFilterOptions() {#GaussWienerFilterOptions--}
```
public GaussWienerFilterOptions()
```


初始化 [GaussWienerFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions) 类的新实例。

### getKernel() {#getKernel--}
```
public Complex[][] getKernel()
```


获取核。

**Returns:**
com.aspose.imaging.imagefilters.complexutils.Complex[][] - 核。
