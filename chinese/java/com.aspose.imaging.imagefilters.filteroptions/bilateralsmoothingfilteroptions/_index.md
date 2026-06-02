---
title: "BilateralSmoothingFilterOptions"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "该双边平滑过滤器选项。"
type: docs
weight: 13
url: /zh/java/com.aspose.imaging.imagefilters.filteroptions/bilateralsmoothingfilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class BilateralSmoothingFilterOptions extends FilterOptionsBase
```

该双边平滑过滤器选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BilateralSmoothingFilterOptions(int size)](#BilateralSmoothingFilterOptions-int-) | 初始化 `BilateralSmoothingFilterOptions` 类的新实例。 |
| [BilateralSmoothingFilterOptions()](#BilateralSmoothingFilterOptions--) | 初始化 `BilateralSmoothingFilterOptions` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSize()](#getSize--) | 获取或设置内核的大小。 |
| [setSize(int value)](#setSize-int-) | 获取或设置内核的大小。 |
| [getSpatialFactor()](#getSpatialFactor--) | 获取或设置空间因子。 |
| [setSpatialFactor(double value)](#setSpatialFactor-double-) | 获取或设置空间因子。 |
| [getSpatialPower()](#getSpatialPower--) | 获取或设置空间幂。 |
| [setSpatialPower(double value)](#setSpatialPower-double-) | 获取或设置空间幂。 |
| [getColorFactor()](#getColorFactor--) | 获取或设置颜色因子。 |
| [setColorFactor(double value)](#setColorFactor-double-) | 获取或设置颜色因子。 |
| [getColorPower()](#getColorPower--) | 获取或设置颜色幂。 |
| [setColorPower(double value)](#setColorPower-double-) | 获取或设置颜色幂。 |

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

### BilateralSmoothingFilterOptions(int size) {#BilateralSmoothingFilterOptions-int-}
```
public BilateralSmoothingFilterOptions(int size)
```


初始化 `BilateralSmoothingFilterOptions` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 大小 | int | 核的大小。 |

### BilateralSmoothingFilterOptions() {#BilateralSmoothingFilterOptions--}
```
public BilateralSmoothingFilterOptions()
```


初始化 `BilateralSmoothingFilterOptions` 类的新实例。

### getSize() {#getSize--}
```
public int getSize()
```


获取或设置内核的大小。

值：内核的大小。

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


获取或设置内核的大小。

值：内核的大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getSpatialFactor() {#getSpatialFactor--}
```
public double getSpatialFactor()
```


获取或设置空间因子。

值：空间因子。

**Returns:**
double
### setSpatialFactor(double value) {#setSpatialFactor-double-}
```
public void setSpatialFactor(double value)
```


获取或设置空间因子。

值：空间因子。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getSpatialPower() {#getSpatialPower--}
```
public double getSpatialPower()
```


获取或设置空间幂。

值：空间幂。

**Returns:**
double
### setSpatialPower(double value) {#setSpatialPower-double-}
```
public void setSpatialPower(double value)
```


获取或设置空间幂。

值：空间幂。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getColorFactor() {#getColorFactor--}
```
public double getColorFactor()
```


获取或设置颜色因子。

值：颜色因子。

**Returns:**
double
### setColorFactor(double value) {#setColorFactor-double-}
```
public void setColorFactor(double value)
```


获取或设置颜色因子。

值：颜色因子。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getColorPower() {#getColorPower--}
```
public double getColorPower()
```


获取或设置颜色幂。

值：颜色幂。

**Returns:**
double
### setColorPower(double value) {#setColorPower-double-}
```
public void setColorPower(double value)
```


获取或设置颜色幂。

值：颜色幂。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

