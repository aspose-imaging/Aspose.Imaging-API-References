---
title: "DitheringMethod"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "抖动方法。"
type: docs
weight: 41
url: /zh/java/com.aspose.imaging/ditheringmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DitheringMethod extends System.Enum
```

抖动方法。
## 字段

| 字段 | 描述 |
| --- | --- |
| [ThresholdDithering](#ThresholdDithering) | 阈值抖动。 |
| [FloydSteinbergDithering](#FloydSteinbergDithering) | Floyd-Steinberg 抖动。 |

## Example: The following example loads a raster image and performs threshold and floyd dithering using different palette depth.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 使用包含 16 种颜色的 4 位色彩调色板执行阈值抖动。
    // 指定的位数越多，输出图像的质量越高且尺寸越大。
    // 请注意，目前仅支持 1 位、4 位和 8 位调色板。
    rasterImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4);

    rasterImage.save(dir + "sample.ThresholdDithering4.png");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.RasterImage rasterImage = (com.aspose.imaging.RasterImage) image;

    // 使用仅包含 2 种颜色（黑色和白色）的 1 位色彩调色板执行 Floyd 抖动。
    // 指定的位数越多，输出图像的质量越高且尺寸越大。
    // 请注意，目前仅支持 1 位、4 位和 8 位调色板。
    rasterImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1);

    rasterImage.save(dir + "sample.FloydSteinbergDithering1.png");
} finally {
    image.dispose();
}
```

### ThresholdDithering {#ThresholdDithering}
```
public static final int ThresholdDithering
```


阈值抖动。最简单、最快速的抖动算法。

### FloydSteinbergDithering {#FloydSteinbergDithering}
```
public static final int FloydSteinbergDithering
```


Floyd-Steinberg 抖动。更复杂的抖动算法，使用最近邻的强度值。

