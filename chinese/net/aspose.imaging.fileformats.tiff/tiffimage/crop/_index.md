---
title: "TiffImage.Crop"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 方法。使用指定的矩形区域裁剪图像，精确选择所需内容。将此方法整合到您的图像处理工作流中，以高效去除不需要的区域，聚焦关键细节，提升图像的整体清晰度和构图。"
type: docs
weight: 230
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/crop/
---
## Crop(Rectangle) {#crop}

使用指定的矩形区域裁剪图像，实现对所需内容的精确选择。将此方法纳入图像处理工作流，以高效去除不需要的区域，聚焦关键细节，提升图像的整体清晰度和构图。

```csharp
public override void Crop(Rectangle rectangle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩形 | Rectangle | 矩形。 |

## 示例

以下示例裁剪 TIFF 图像。裁剪区域通过 Aspose.Imaging.Rectangle 指定。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // 裁剪图像。裁剪区域是图像的矩形中心区域。
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(tiffImage.Width / 4, tiffImage.Height / 4, tiffImage.Width / 2, tiffImage.Height / 2);
    tiffImage.Crop(area);

    // 将裁剪后的图像保存为 PNG
    tiffImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)

---

## Crop(int, int, int, int) {#crop_1}

通过指定左、右、上、下方向的偏移量对图像进行裁剪。此方法实现对图像所需部分的精确选取，便于高效去除不需要的区域并聚焦关键内容。将此功能集成到图像处理管线中，根据需要提升图像的清晰度和构图。

```csharp
public override void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| leftShift | Int32 | 左移。 |
| rightShift | Int32 | 右移。 |
| topShift | Int32 | 上移。 |
| bottomShift | Int32 | 下移。 |

## 示例

以下示例裁剪 TIFF 图像。裁剪区域通过左、上、右、下边距指定。

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // 再次裁剪。设置图像尺寸 10% 的边距。
    int horizontalMargin = tiffImage.Width / 10;
    int verticalMargin = tiffImage.Height / 10;
    tiffImage.Crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // 将裁剪后的图像保存为 PNG。
    tiffImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


