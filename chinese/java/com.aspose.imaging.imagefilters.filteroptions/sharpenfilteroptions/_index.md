---
title: "SharpenFilterOptions"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "锐化滤镜选项。"
type: docs
weight: 25
url: /zh/java/com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions), [com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions)
```
public class SharpenFilterOptions extends GaussianBlurFilterOptions
```

锐化滤镜选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SharpenFilterOptions(int size, double sigma)](#SharpenFilterOptions-int-double-) | 初始化 [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions) 类的新实例。 |
| [SharpenFilterOptions()](#SharpenFilterOptions--) | 初始化 [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getKernel()](#getKernel--) | 获取核。 |
| [getSize()](#getSize--) | 获取高斯内核大小。 |
| [setSize(int value)](#setSize-int-) | 高斯核的大小。 |
| [getSigma()](#getSigma--) | 获取高斯内核 sigma（平滑）。 |
| [setSigma(double value)](#setSigma-double-) | 高斯核 sigma（平滑）。 |

## Example: The following example applies various types of filters to a raster image.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 对整幅图像应用矩形大小为 5 的中值滤波器。
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    rasterImage.save(dir + "sample.MedianFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 对整幅图像应用核大小为 5 的双边平滑滤波器。
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    rasterImage.save(dir + "sample.BilateralSmoothingFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 对整幅图像应用半径为 5、sigma 值为 4.0 的高斯模糊滤波器。
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussianBlurFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 对整幅图像应用半径为 5、平滑值为 4.0 的 Gauss-Wiener 滤波器。
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    rasterImage.save(dir + "sample.GaussWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 对整幅图像应用长度为 5、平滑值为 4.0、角度为 90.0 度的运动 Wiener 滤波器。
    rasterImage.filter(rasterImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    rasterImage.save(dir + "sample.MotionWienerFilter.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 对整幅图像应用核大小为 5、sigma 值为 4.0 的锐化滤波器。
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


初始化 [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 大小 | int | 内核的大小。 |
| sigma | double | Sigma 值。 |

### SharpenFilterOptions() {#SharpenFilterOptions--}
```
public SharpenFilterOptions()
```


初始化 [SharpenFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/sharpenfilteroptions) 类的新实例。

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


获取核。

**Returns:**
double[][] - 内核。
### getSize() {#getSize--}
```
public int getSize()
```


获取高斯核大小。必须是正的非零奇数值。

**Returns:**
int - 高斯核大小。
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


高斯核大小。必须是正的非零奇数值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 高斯核大小。 |

### getSigma() {#getSigma--}
```
public double getSigma()
```


获取高斯核 sigma（平滑）。必须是正的非零值。

**Returns:**
double - 高斯核 sigma（平滑）。
### setSigma(double value) {#setSigma-double-}
```
public void setSigma(double value)
```


高斯核 sigma（平滑）。必须是正的非零值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 高斯核 sigma（平滑）。 |

