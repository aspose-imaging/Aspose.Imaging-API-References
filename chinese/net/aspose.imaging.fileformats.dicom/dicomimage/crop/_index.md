---
title: "DicomImage.Crop"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DicomImage 方法。使用此简单方法裁剪图像以去除不需要的区域并聚焦关键内容。适用于希望自定义图像视觉构图、确保其有效传达所需信息的开发者。"
type: docs
weight: 180
url: /zh/net/aspose.imaging.fileformats.dicom/dicomimage/crop/
---
## Crop(Rectangle) {#crop}

使用此简易方法裁剪图像，去除不需要的区域并聚焦核心内容。适用于希望自定义图像视觉构图、确保有效传达预期信息的开发者。

```csharp
public override void Crop(Rectangle rectangle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩形 | Rectangle | 矩形。 |

## 示例

以下示例裁剪 DICOM 图像。裁剪区域可通过 Aspose.Imaging.Rectangle 指定。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // 裁剪图像。裁剪区域是图像的矩形中心区域。
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(dicomImage.Width / 4, dicomImage.Height / 4, dicomImage.Width / 2, dicomImage.Height / 2);
    dicomImage.Crop(area);

    // 将裁剪后的图像保存为 PNG
    dicomImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)

---

## Crop(int, int, int, int) {#crop_1}

通过此多功能方法应用位移来调整图像的裁剪区域。非常适合需要对裁剪过程进行精确控制、在保留重要细节的同时去除不必要元素的开发者。

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

以下示例裁剪 DICOM 图像。裁剪区域通过 Left、Top、Right、Bottom 边距指定。

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = (Aspose.Imaging.FileFormats.Dicom.DicomImage)image;

    // 再次裁剪。设置图像尺寸 10% 的边距。
    int horizontalMargin = dicomImage.Width / 10;
    int verticalMargin = dicomImage.Height / 10;
    dicomImage.Crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // 将裁剪后的图像保存为 PNG。
    dicomImage.Save(dir + "sample.Crop.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


