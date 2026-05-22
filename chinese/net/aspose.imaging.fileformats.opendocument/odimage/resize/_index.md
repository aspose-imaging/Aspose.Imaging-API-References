---
title: "OdImage.Resize"
second_title: "Aspose.Imaging for .NET API 参考"
description: "OdImage 方法。根据指定的宽度、高度和缩放设置调整图像的尺寸。此方法在保持期望比例并遵循定义的缩放配置的同时，提供了图像缩放的灵活性，确保图像尺寸的精确调整以满足特定需求或显示标准。"
type: docs
weight: 90
url: /zh/net/aspose.imaging.fileformats.opendocument/odimage/resize/
---
## Resize(int, int, ImageResizeSettings) {#resize_1}

根据指定的宽度、高度和缩放设置调整图像的尺寸。此方法在保持期望比例并遵循已定义的缩放配置的同时，提供了图像缩放的灵活性，确保图像尺寸的精确调整以满足特定需求或显示标准。

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |
| newHeight | Int32 | 新的高度。 |
| 设置 | ImageResizeSettings | 缩放设置。 |

### 另请参见

* class [ImageResizeSettings](../../../aspose.imaging/imageresizesettings/)
* class [OdImage](../)
* namespace [Aspose.Imaging.FileFormats.OpenDocument](../../odimage/)
* assembly [Aspose.Imaging](../../../)

---

## Resize(int, int, ResizeType) {#resize_2}

此方法对图像进行缩放，根据指定的尺寸和缩放类型同时调整宽度和高度。它提供了全面的缩放方案，在保持图像质量和完整性的同时实现精确调整。通过加入缩放类型参数，用户可以在多种缩放算法或方法中进行选择，以在不同使用场景或偏好下获得最佳效果。

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |
| newHeight | Int32 | 新的高度。 |
| resizeType | ResizeType | 缩放类型。 |

### 另请参见

* enum [ResizeType](../../../aspose.imaging/resizetype/)
* class [OdImage](../)
* namespace [Aspose.Imaging.FileFormats.OpenDocument](../../odimage/)
* assembly [Aspose.Imaging](../../../)


