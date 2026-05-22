---
title: "RasterImage.NormalizeAngle"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage 方法。规范化角度。此方法适用于扫描的文本文档，以消除倾斜扫描。该方法使用 GetSkewAngle 和 Rotate 方法。"
type: docs
weight: 480
url: /zh/net/aspose.imaging/rasterimage/normalizeangle/
---
## NormalizeAngle() {#normalizeangle}

规范化角度。此方法适用于扫描的文本文档，以消除倾斜扫描。该方法使用 [`GetSkewAngle`](../getskewangle/) 和 [`Rotate`](../rotate/) 方法。

```csharp
public void NormalizeAngle()
```

### 另请参见

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)

---

## NormalizeAngle(bool, Color) {#normalizeangle_1}

规范化角度。此方法适用于扫描的文本文档，以消除倾斜扫描。该方法使用 [`GetSkewAngle`](../getskewangle/) 和 [`Rotate`](../rotate/) 方法。

```csharp
public virtual void NormalizeAngle(bool resizeProportionally, Color backgroundColor)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resizeProportionally | Boolean | 如果设置为 `true`，图像尺寸将根据旋转矩形（角点）投影进行更改；否则保持尺寸不变，仅旋转内部图像内容。 |
| backgroundColor | 颜色 | 背景颜色。 |

## 示例

倾斜是文档扫描过程中可能出现的伪影，当文档的文字/图像略微旋转时会产生。其原因多种，但最常见的是扫描时纸张位置偏移。因此，去倾斜（deskew）是检测并修复扫描文件（即位图）中此问题的过程，使去倾斜后的文档文字/图像正确且水平对齐。

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3567\\";

string inputFilePath = dir + "skewed.png";
string outputFilePath = dir + "skewed.out.png";

// 使用默认参数消除倾斜扫描
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(inputFilePath))
{
    // 去倾斜
    image.NormalizeAngle(false /*do not resize*/, Aspose.Imaging.Color.LightGray /*background color*/);
    image.Save(outputFilePath);
}
```

### 另请参见

* struct [Color](../../color/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


