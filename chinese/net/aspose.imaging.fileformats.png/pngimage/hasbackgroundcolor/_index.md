---
title: "PngImage.HasBackgroundColor"
second_title: "Aspose.Imaging for .NET API 参考"
description: "PngImage 属性。检索一个布尔值，指示图像是否具有背景颜色。此属性对需要确定图像是否包含背景颜色的应用程序很有用，这在合成、渲染或导出等各种处理任务中可能很重要。"
type: docs
weight: 60
url: /zh/net/aspose.imaging.fileformats.png/pngimage/hasbackgroundcolor/
---
## PngImage.HasBackgroundColor property

检索一个布尔值，指示图像是否具有背景颜色。此属性对需要判断图像是否包含背景颜色的应用程序有用，这在合成、渲染或导出等各种处理任务中可能很重要。

```csharp
public override bool HasBackgroundColor { get; set; }
```

## 示例

以下示例展示了如何为不支持 alpha 通道的 TrueColor PNG 图像的部分设置完全透明的颜色。

```csharp
[C#]

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource("c:\\temp\\transparent.png", false);
createOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.Truecolor;

// 创建一个 100x100 像素的 TrueColor PNG 图像。
using (Aspose.Imaging.Image image = Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)image;
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(pngImage);

    // 所有红色像素将被视为完全透明。
    pngImage.TransparentColor = Aspose.Imaging.Color.Red;
    pngImage.HasTransparentColor = true;

    // 所有透明像素将拥有背景颜色。
    pngImage.BackgroundColor = Aspose.Imaging.Color.Green;
    pngImage.HasBackgroundColor = true;

    // 用白色填充整个图像。
    gr.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.White), pngImage.Bounds);

    // 用透明颜色填充图像的左上四分之一区域。
    // 这会使左上四分之一区域呈现背景颜色。
    Rectangle rect = new Rectangle(0, 0, pngImage.Width / 2, pngImage.Height / 2);
    gr.FillRectangle(new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red), rect);

    pngImage.Save();
}
```

### 另请参见

* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)


