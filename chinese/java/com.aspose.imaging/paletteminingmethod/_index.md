---
title: "PaletteMiningMethod"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "图像调色板挖掘方法"
type: docs
weight: 79
url: /zh/java/com.aspose.imaging/paletteminingmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PaletteMiningMethod extends System.Enum
```

图像调色板挖掘方法
## 字段

| 字段 | 描述 |
| --- | --- |
| [UseCurrentPalette](#UseCurrentPalette) | 使用图像的现有调色板 |
| [ColorClustering](#ColorClustering) | 颜色聚类方法 |
| [Histogram](#Histogram) | 直方图方法 |

## Example: The following example shows how to compress a PNG image, using indexed color with best fit palette

``` java

// 加载 png 图像        
String sourceFilePath = "OriginalRings.png";
String outputFilePath = "OriginalRingsOutput.png";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(sourceFilePath))
{
    com.aspose.imaging.imageoptions.PngOptions options = new com.aspose.imaging.imageoptions.PngOptions();
    options.setProgressive(true);
    // 使用索引颜色类型
    options.setColorType(com.aspose.imaging.fileformats.png.PngColorType.IndexedColor);
    // 使用最大压缩
    options.setCompressionLevel(9);
    // 获取最接近的 8 位颜色调色板，覆盖尽可能多的像素，以便调色板图像
    // 几乎在视觉上与非调色板图像无法区分。
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// 输出文件大小应显著减小
```

### UseCurrentPalette {#UseCurrentPalette}
```
public static final int UseCurrentPalette
```


使用图像的现有调色板

### ColorClustering {#ColorClustering}
```
public static final int ColorClustering
```


颜色聚类方法

### Histogram {#Histogram}
```
public static final int Histogram
```


直方图方法

