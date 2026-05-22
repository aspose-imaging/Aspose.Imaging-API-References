---
title: "TgaImage.Crop"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TgaImage 方法。将图像裁剪到指定区域。此方法允许您定义图像内的矩形区域以保留，丢弃其余部分。此操作有助于聚焦图像中的特定内容或去除不需要的部分。"
type: docs
weight: 310
url: /zh/net/aspose.imaging.fileformats.tga/tgaimage/crop/
---
## Crop(Rectangle) {#crop}

将图像裁剪到指定区域。此方法允许您定义图像中要保留的矩形区域，丢弃其余部分。此操作有助于聚焦图像的特定内容或去除不需要的部分。

```csharp
public override void Crop(Rectangle rectangle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩形 | Rectangle | 矩形。 |

### 另请参见

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [TgaImage](../)
* namespace [Aspose.Imaging.FileFormats.Tga](../../tgaimage/)
* assembly [Aspose.Imaging](../../../)

---

## Crop(int, int, int, int) {#crop_1}

通过指定左、右、上、下边界的偏移量来裁剪图像。此方法允许您沿水平和垂直轴独立移动边界来修剪图像。通过调整这些偏移量，您可以精确控制保留的图像部分，有效地将其裁剪到所需尺寸。

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

* class [TgaImage](../)
* namespace [Aspose.Imaging.FileFormats.Tga](../../tgaimage/)
* assembly [Aspose.Imaging](../../../)


