---
title: "EmfRecorderGraphics2D.FromEmfImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EmfRecorderGraphics2D 方法。获取一个包含来自 Emf 图像的所有记录的 EmfRecorderGraphics2D 实例"
type: docs
weight: 20
url: /zh/net/aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/fromemfimage/
---
## EmfRecorderGraphics2D.FromEmfImage method

获取一个包含来自 Emf 图像的所有记录的 [`EmfRecorderGraphics2D`](../) 实例。

```csharp
public static EmfRecorderGraphics2D FromEmfImage(EmfImage emfImage)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| emfImage | EmfImage | 要读取记录的 Emf 图像。 |

### 返回值

[`EmfRecorderGraphics2D`](../) 的实例

## 示例

本示例展示了如何从文件加载 EMF 图像并在其上绘制文本字符串。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D graphics =
        Aspose.Imaging.FileFormats.Emf.Graphics.EmfRecorderGraphics2D.FromEmfImage(emfImage);

    // 第一步，获取图像尺寸
    int width = emfImage.Width;
    int height = emfImage.Height;

    // 第二步，计算一个变换，以将文本字符串放置在图像的主对角线上 -
    // 从左上角到右下角。
    float emFontSize = 96f;
    float d = (float)System.Math.Sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float)height) / width;                
    double radians = System.Math.Atan(tan);
    double degrees = (180 * radians) / System.Math.PI;

    Aspose.Imaging.Matrix transform = new Aspose.Imaging.Matrix();
    transform.Rotate((float)degrees);
    transform.Scale(scaleFactor, scaleFactor);

    // 然后，设置变换。
    graphics.SetTransform(transform);

    // 最后，在主对角线上放置水印（粉色文本字符串）。
    graphics.DrawString("WATERMARK", new Aspose.Imaging.Font("Courier New", emFontSize), Aspose.Imaging.Color.LightPink, 0, 0/*, (float)degrees*/);

    // 将带有水印的图像保存为另一个 EMF 文件。
    using (Aspose.Imaging.FileFormats.Emf.EmfImage scaledEmfImage = graphics.EndRecording())
    {
        scaledEmfImage.Save(dir + "test.scaled.emf");
    }
}
```

### 另请参见

* class [EmfImage](../../../aspose.imaging.fileformats.emf/emfimage/)
* class [EmfRecorderGraphics2D](../)
* namespace [Aspose.Imaging.FileFormats.Emf.Graphics](../../emfrecordergraphics2d/)
* assembly [Aspose.Imaging](../../../)


