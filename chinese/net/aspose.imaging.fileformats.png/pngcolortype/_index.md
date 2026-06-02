---
title: "枚举 PngColorType"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Png.PngColorType 枚举。表示 PNG 图像的颜色类型"
type: docs
weight: 7540
url: /zh/net/aspose.imaging.fileformats.png/pngcolortype/
---
## PngColorType enumeration

表示 PNG 图像颜色类型。

```csharp
public enum PngColorType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Grayscale | `0` | 表示每个像素为灰度样本的颜色类型。 |
| Truecolor | `2` | 表示每个像素为 R,G,B 三元组的颜色类型。 |
| IndexedColor | `3` | 表示每个像素为调色板索引的颜色类型；应出现 PLTE 块。 |
| GrayscaleWithAlpha | `4` | 表示每个像素为灰度样本后跟 alpha 样本的颜色类型。 |
| TruecolorWithAlpha | `6` | 表示每个像素为 R,G,B 三元组后跟 alpha 样本的颜色类型。 |

## 示例

以下示例展示了如何压缩 PNG 图像，使用带最佳匹配调色板的索引颜色

```csharp
[C#]

// 加载 PNG 图像
    string  sourceFilePath="OriginalRings.png";
    string  outputFilePath="OriginalRingsOutput.png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new Aspose.Imaging.ImageOptions.PngOptions()
    {
         Progressive = true,
             // 使用索引颜色类型
         ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.IndexedColor,
             // 使用最大压缩
         CompressionLevel = 9,
      // 获取最接近的 8 位颜色调色板，覆盖尽可能多的像素，以便调色板图像
         // 几乎在视觉上与非调色板图像无差别。
         Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette((Aspose.Imaging.RasterImage)image, 256, Aspose.Imaging.PaletteMiningMethod.Histogram)
    });
}
    // 输出文件大小应显著减小
```

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Png](../../aspose.imaging.fileformats.png/)
* assembly [Aspose.Imaging](../../)


