---
title: "DicomImage.RotateFlip"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DicomImage 方法。通过旋转、翻转或同时执行这两种操作，轻松操作活动帧，使用此简洁的方法。适用于需要在图像序列中动态调整特定帧方向的开发者，确保最佳的呈现和对齐。"
type: docs
weight: 290
url: /zh/net/aspose.imaging.fileformats.dicom/dicomimage/rotateflip/
---
## DicomImage.RotateFlip method

使用此简洁方法轻松对活动帧进行旋转、翻转或同时执行两者操作。适用于需要在图像序列中动态调整特定帧方向的开发者，确保最佳展示和对齐。

```csharp
public override void RotateFlip(RotateFlipType rotateFlipType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | 旋转翻转类型。 |

## 示例

此示例加载一幅 DICOM 图像，将其顺时针旋转 90 度，并可选择水平和（或）垂直翻转图像。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.RotateFlipType[] rotateFlipTypes = new Aspose.Imaging.RotateFlipType[]
{
    Aspose.Imaging.RotateFlipType.Rotate90FlipNone,
    Aspose.Imaging.RotateFlipType.Rotate90FlipX,
    Aspose.Imaging.RotateFlipType.Rotate90FlipXY,
    Aspose.Imaging.RotateFlipType.Rotate90FlipY,
};

foreach (Aspose.Imaging.RotateFlipType rotateFlipType in rotateFlipTypes)
{
    // 旋转、翻转并保存到输出文件。
    using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
    {
        image.RotateFlip(rotateFlipType);
        image.Save(dir + "sample." + rotateFlipType + ".png", new Aspose.Imaging.ImageOptions.PngOptions());
    }
}
```

### 另请参见

* enum [RotateFlipType](../../../aspose.imaging/rotatefliptype/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


