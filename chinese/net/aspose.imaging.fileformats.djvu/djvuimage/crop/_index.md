---
title: "DjvuImage.Crop"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DjvuImage 方法。Crop 裁剪可修剪图像，以聚焦特定细节或去除不需要的元素，提升构图和视觉冲击力。无论是为社交媒体调整照片、创建网站横幅，还是设计印刷材料，此工具都能帮助您以精确和清晰的方式完善图像。"
type: docs
weight: 220
url: /zh/net/aspose.imaging.fileformats.djvu/djvuimage/crop/
---
## Crop(Rectangle) {#crop}

\"Crop\"裁剪图像以聚焦特定细节或去除不需要的元素，提升构图和视觉冲击力。无论是为社交媒体调整照片、创建网站横幅，还是设计印刷材料，此工具都能帮助您以精确和清晰的方式完善图像。

```csharp
public override void Crop(Rectangle rectangle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩形 | Rectangle | 矩形。 |

## 示例

以下示例裁剪 DJVU 图像。裁剪区域通过 Aspose.Imaging.Rectangle 指定。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // 裁剪图像。裁剪区域是图像的矩形中心区域。
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(djvuImage.Width / 4, djvuImage.Height / 4, djvuImage.Width / 2, djvuImage.Height / 2);
    djvuImage.Crop(area);

    // 将裁剪后的图像保存为 PNG
    djvuImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)

---

## Crop(int, int, int, int) {#crop_1}

带位移的 Crop 允许您精确调整图像中裁剪区域的位置和尺寸。此功能在优化构图、对齐元素以及突出视觉焦点方面极为宝贵。通过在裁剪过程中加入位移，您可以轻松实现像素级的精确度，并微调图像的框架。

```csharp
public override void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| leftShift | Int32 | 左移。 |
| rightShift | Int32 | 右移。 |
| topShift | Int32 | 上移。 |
| bottomShift | Int32 | 下移。 |

### 另请参见

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


