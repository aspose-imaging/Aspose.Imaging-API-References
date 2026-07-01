---
title: "GaussianBlurFilterOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "高斯模糊滤镜选项。"
type: docs
weight: 19
url: /zh/java/com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase), [com.aspose.imaging.imagefilters.filteroptions.ConvolutionFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/convolutionfilteroptions)

**All Implemented Interfaces:**
com.aspose.internal.imagefilters.convolution.gaussianblur.IGaussianBlurOptions, com.aspose.internal.imagefilters.convolution.ISquareConvolutionKernel
```
public class GaussianBlurFilterOptions extends ConvolutionFilterOptions implements IGaussianBlurOptions, ISquareConvolutionKernel
```

高斯模糊滤镜选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GaussianBlurFilterOptions(int size, double sigma)](#GaussianBlurFilterOptions-int-double-) | 初始化 [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions) 类的新实例。 |
| [GaussianBlurFilterOptions()](#GaussianBlurFilterOptions--) | 初始化 [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getKernel()](#getKernel--) | 获取 Gaussian 核的大小。 |
| [getSize()](#getSize--) | 获取 Gaussian 核的大小。 |
| [setSize(int value)](#setSize-int-) | 高斯核的大小。 |
| [getSigma()](#getSigma--) | 获取 Gaussian 核 sigma（平滑）。 |
| [setSigma(double value)](#setSigma-double-) | Gaussian 核 sigma（平滑）。 |
| [getRadius()](#getRadius--) | 获取 Gaussian ISquareConvolutionKernel 的半径。 |
| [setRadius(int value)](#setRadius-int-) | Gaussian ISquareConvolutionKernel 的半径。 |

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

### GaussianBlurFilterOptions(int size, double sigma) {#GaussianBlurFilterOptions-int-double-}
```
public GaussianBlurFilterOptions(int size, double sigma)
```


初始化 [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| size | int | Gaussian 核大小.. |
| sigma | double | 高斯核的 sigma。 |

### GaussianBlurFilterOptions() {#GaussianBlurFilterOptions--}
```
public GaussianBlurFilterOptions()
```


初始化 [GaussianBlurFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/gaussianblurfilteroptions) 类的新实例。

### getKernel() {#getKernel--}
```
public double[][] getKernel()
```


获取 Gaussian 核的大小。

**Returns:**
double[][] - Gaussian 核大小。
### getSize() {#getSize--}
```
public int getSize()
```


获取 Gaussian 核大小。必须是正的、非零的奇数值。

**Returns:**
int - Gaussian 核大小。
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Gaussian 核大小。必须是正的、非零的奇数值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | Gaussian 核大小。 |

### getSigma() {#getSigma--}
```
public double getSigma()
```


获取 Gaussian 核 sigma（平滑）。必须是正的、非零的值。

**Returns:**
double - Gaussian 核 sigma（平滑）。
### setSigma(double value) {#setSigma-double-}
```
public void setSigma(double value)
```


Gaussian 核 sigma（平滑）。必须是正的、非零的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | Gaussian 核 sigma（平滑）。 |

### getRadius() {#getRadius--}
```
public final int getRadius()
```


获取 Gaussian ISquareConvolutionKernel 的半径。

**Returns:**
int - Gaussian ISquareConvolutionKernel 的半径。
### setRadius(int value) {#setRadius-int-}
```
public final void setRadius(int value)
```


Gaussian ISquareConvolutionKernel 的半径。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | Gaussian ISquareConvolutionKernel 的半径。 |

