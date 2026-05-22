---
title: "MetafileRecorderGraphics2D.SetTransform"
second_title: "Aspose.Imaging for .NET API 参考"
description: "MetafileRecorderGraphics2D 方法。设置变换"
type: docs
weight: 290
url: /zh/net/aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/settransform/
---
## MetafileRecorderGraphics2D.SetTransform method

设置变换。

```csharp
public void SetTransform(Matrix transform)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 变换 | 矩阵 | 新的变换矩阵。 |

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

* class [Matrix](../../../aspose.imaging/matrix/)
* class [MetafileRecorderGraphics2D](../)
* namespace [Aspose.Imaging.FileFormats.Emf.Graphics](../../metafilerecordergraphics2d/)
* assembly [Aspose.Imaging](../../../)


