---
title: "TgaImage.Rotate"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TgaImage 方法。围绕图像中心按指定角度旋转图像，同时保持尺寸比例并保留背景颜色。此方法实现精确的图像操作，确保旋转后视觉平衡且与指定的背景颜色保持一致。适用于需要围绕中心精确旋转的任务，如方向校正或艺术调整。"
type: docs
weight: 350
url: /zh/net/aspose.imaging.fileformats.tga/tgaimage/rotate/
---
## TgaImage.Rotate method

围绕图像中心按指定角度旋转图像，同时保持缩放比例并保留背景颜色。此方法允许精确的图像操作，确保旋转保持视觉平衡并与指定的背景颜色保持一致。它非常适合需要围绕中心进行精确旋转的任务，例如方向校正或艺术调整。

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | 单精度 | 旋转角度（单位：度）。正值将顺时针旋转。 |
| resizeProportionally | Boolean | 如果设置为 `true`，图像尺寸将根据旋转矩形（角点）投影进行更改；否则保持尺寸不变，仅旋转 `internal` 图像内容。 |
| backgroundColor | 颜色 | 背景颜色。 |

### 另请参见

* struct [Color](../../../aspose.imaging/color/)
* class [TgaImage](../)
* namespace [Aspose.Imaging.FileFormats.Tga](../../tgaimage/)
* assembly [Aspose.Imaging](../../../)


