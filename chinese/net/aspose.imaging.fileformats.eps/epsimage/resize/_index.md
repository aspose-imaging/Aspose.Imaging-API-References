---
title: "EpsImage.Resize"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EpsImage 方法。此方法根据指定参数调整图像尺寸，改变其维度。它提供了一种直接的方式来修改图像大小，确保开发者的灵活性和易用性。"
type: docs
weight: 200
url: /zh/net/aspose.imaging.fileformats.eps/epsimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

此方法调整图像尺寸，根据指定参数改变其维度。它提供了一种直接的方式来修改图像大小，确保开发者的灵活性和易用性。

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |
| newHeight | Int32 | 新的高度。 |
| resizeType | ResizeType | 缩放类型。 |

## 示例

调整 EPS 图像大小并导出为 PNG 格式。

```csharp
[C#]

// 加载 EPS 图像
using (var image = Image.Load("AstrixObelix.eps"))
{
    // 使用 Mitchell 三次插值方法调整图像大小
    image.Resize(400, 400, ResizeType.Mitchell);

    // 将图像导出为 PNG 格式
    image.Save("ExportResult.png", new PngOptions());
}
```

### 另请参见

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [EpsImage](../)
* namespace [Aspose.Imaging.FileFormats.Eps](../../epsimage/)
* assembly [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

此方法使用预定义设置来调整图像尺寸，能够高效地改变维度。它提供了一种便捷的方式来修改图像大小，同时保持对各种参数的控制，确保在不同使用场景下获得最佳结果。

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |
| newHeight | Int32 | 新的高度。 |
| 设置 | ImageResizeSettings | 缩放设置。 |

## 示例

使用高级设置调整 EPS 图像大小。

```csharp
[C#]

// 加载 EPS 图像
using (var image = Image.Load("AstrixObelix.eps"))
{
    // 使用高级缩放设置调整图像大小
    image.Resize(400, 400, new ImageResizeSettings
    {
        // 设置插值模式
        Mode = ResizeType.LanczosResample,

        // 设置过滤器类型
        FilterType = ImageFilterType.SmallRectangular,

        // 设置颜色比较方法
        ColorCompareMethod = ColorCompareMethod.Euclidian,

        // 设置颜色量化方法
        ColorQuantizationMethod = ColorQuantizationMethod.Popularity
    });

    // 将图像导出为 PNG 格式
    image.Save("ExportResult.png", new PngOptions());
}
```

### 另请参见

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings/)
* class [EpsImage](../)
* namespace [Aspose.Imaging.FileFormats.Eps](../../epsimage/)
* assembly [Aspose.Imaging](../../../)


