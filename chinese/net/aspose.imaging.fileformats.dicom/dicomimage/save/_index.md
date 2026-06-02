---
title: "DicomImage.Save"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DicomImage 方法。使用此便捷方法，轻松将图像数据保存到指定流中并以所需的文件格式保存。无论您使用 JPEG、PNG 还是其他格式，此函数都能确保图像数据高效、准确地保存，非常适合希望简化文件保存流程的开发者。"
type: docs
weight: 300
url: /zh/net/aspose.imaging.fileformats.dicom/dicomimage/save/
---
## DicomImage.Save method

使用此便捷方法轻松将图像数据保存到指定流中的所需文件格式。无论是 JPEG、PNG 还是其他格式，此函数都能确保图像数据高效、准确地保存，非常适合希望简化文件保存流程的开发者。

```csharp
public override void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于保存图像数据的流。 |
| optionsBase | ImageOptionsBase | 保存选项。 |
| boundsRectangle | Rectangle | 目标图像的边界矩形。将空矩形设置为使用源边界。 |

## 示例

以下示例从文件加载 DICOM 图像，然后将图像保存到 PNG 文件流中。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width / 2, image.Height / 2);
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "output.png", System.IO.FileMode.Create))
    {
        // 将图像的左上四分之一保存到文件流中。
        image.Save(outputStream, saveOptions, bounds);
    }
}
```

### 另请参见

* class [ImageOptionsBase](../../../aspose.imaging/imageoptionsbase/)
* struct [Rectangle](../../../aspose.imaging/rectangle/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


