---
title: "GifImage.Rotate"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GifImage 方法。此方法围绕图像中心点旋转图像。通过指定旋转角度，您可以顺时针或逆时针旋转图像以实现所需方向。此旋转有助于在不扭曲内容的情况下调整图像的呈现或对齐。"
type: docs
weight: 390
url: /zh/net/aspose.imaging.fileformats.gif/gifimage/rotate/
---
## GifImage.Rotate method

此方法围绕图像的中心点旋转图像。通过指定旋转角度，您可以顺时针或逆时针旋转图像，以实现所需的方向。此旋转有助于在不失真内容的情况下调整图像的呈现或对齐。

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
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


