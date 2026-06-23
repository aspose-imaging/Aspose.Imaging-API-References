---
title: "PngColorType"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示 PNG 图像颜色类型。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.png/pngcolortype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PngColorType extends System.Enum
```

表示 PNG 图像颜色类型。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Grayscale](#Grayscale) | 表示每个像素为灰度样本的颜色类型。 |
| [Truecolor](#Truecolor) | 表示每个像素为 R,G,B 三元组的颜色类型。 |
| [IndexedColor](#IndexedColor) | 表示每个像素为调色板索引的颜色类型；应出现 PLTE 块。 |
| [GrayscaleWithAlpha](#GrayscaleWithAlpha) | 表示每个像素为灰度样本后跟 alpha 样本的颜色类型。 |
| [TruecolorWithAlpha](#TruecolorWithAlpha) | 表示每个像素为 R,G,B 三元组后跟 alpha 样本的颜色类型。 |

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
    // 获取最接近的 8 位颜色调色板，以覆盖尽可能多的像素，从而得到调色板图像
    // 几乎在视觉上与非调色的图像没有区别。
    options.setPalette(com.aspose.imaging.ColorPaletteHelper.getCloseImagePalette((com.aspose.imaging.RasterImage)image, 
                                256, Aspose.Imaging.PaletteMiningMethod.Histogram));
                     
    image.save(outputFilePath, options);
}
// 输出文件大小应显著减小
```

### Grayscale {#Grayscale}
```
public static final int Grayscale
```


表示每个像素为灰度样本的颜色类型。

### Truecolor {#Truecolor}
```
public static final int Truecolor
```


表示每个像素为 R,G,B 三元组的颜色类型。

### IndexedColor {#IndexedColor}
```
public static final int IndexedColor
```


表示每个像素为调色板索引的颜色类型；应出现 PLTE 块。

### GrayscaleWithAlpha {#GrayscaleWithAlpha}
```
public static final int GrayscaleWithAlpha
```


表示每个像素为灰度样本后跟 alpha 样本的颜色类型。

### TruecolorWithAlpha {#TruecolorWithAlpha}
```
public static final int TruecolorWithAlpha
```


表示每个像素为 R,G,B 三元组后跟 alpha 样本的颜色类型。

