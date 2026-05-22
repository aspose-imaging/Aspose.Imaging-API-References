---
title: "DjvuImage.BinarizeFixed"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DjvuImage method. 使用预定义阈值进行二值化，可将复杂图像简化为二进制表示，像素根据其强度与指定阈值的比较被分类为黑或白。此技术常用于图像处理，以提升清晰度、简化分析并为后续处理步骤（如光学字符识别 OCR）做好准备。通过应用固定阈值，您可以快速将灰度图像转换为二进制形式，便于解释并提取有意义的信息。"
type: docs
weight: 190
url: /zh/net/aspose.imaging.fileformats.djvu/djvuimage/binarizefixed/
---
## DjvuImage.BinarizeFixed method

使用预定义阈值的二值化将复杂图像简化为二进制表示，像素根据其强度与指定阈值的比较被归类为黑或白。此技术常用于图像处理，以提升清晰度、简化分析，并为后续处理步骤（如光学字符识别（OCR））准备图像。通过应用固定阈值，您可以快速将灰度图像转换为二进制形式，使其更易于解释和提取有意义的信息。

```csharp
public override void BinarizeFixed(byte threshold)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| threshold | Byte | 阈值。如果像素的对应灰度值大于阈值，则赋值为255，否则为0。 |

## 示例

以下示例使用预定义阈值对 DJVU 图像进行二值化。二值化图像仅包含两种颜色——黑色和白色。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)image;

    // 使用阈值 127 对图像进行二值化。
    // 如果像素的对应灰度值大于 127，则赋值为255，否则为0。
    djvuImage.BinarizeFixed(127);
    djvuImage.Save(dir + "sample.BinarizeFixed.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### 另请参见

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


