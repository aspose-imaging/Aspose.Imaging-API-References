---
title: "枚举 PaletteMiningMethod"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.PaletteMiningMethod 枚举。图像调色板挖掘方法"
type: docs
weight: 11240
url: /zh/net/aspose.imaging/paletteminingmethod/
---
## PaletteMiningMethod enumeration

图像调色板挖掘方法

```csharp
public enum PaletteMiningMethod
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| UseCurrentPalette | `0` | 使用图像的现有调色板 |
| ColorClustering | `1` | 颜色聚类方法 |
| Histogram | `2` | 直方图方法 |

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

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


