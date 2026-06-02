---
title: "WebPImage.AddBlock"
second_title: "Aspose.Imaging for .NET API 参考"
description: "WebPImage 方法。将新的 WebP 块加入图像，丰富其内容并促进高级图像操作。整合此方法可在应用程序中动态增强 WebP 图像数据的结构和复杂度，实现对图像渲染的精确控制和优化。"
type: docs
weight: 70
url: /zh/net/aspose.imaging.fileformats.webp/webpimage/addblock/
---
## WebPImage.AddBlock method

在图像中加入新的 WebP 块，丰富其内容并促进高级图像操作。将此方法集成到应用程序中，以动态增强 WebP 图像数据的结构和复杂度，实现对图像渲染的精确控制和优化。

```csharp
public void AddBlock(IFrame block)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 块 | IFrame | 要添加的 Webp 块。 |

## 示例

此示例展示了如何使用指定的选项创建多帧动画 WebP 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
createOptions.AnimBackgroundColor = (uint)Aspose.Imaging.Color.Gray.ToArgb();

// 默认帧加上 36 + 36 个额外帧。
createOptions.AnimLoopCount = 36 + 36 + 1;

// 创建一个 100x100 像素的 WebP 图像。
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    // 第一个圆是红色的
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // 第二个圆是黑色的
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // 逐渐增加红色弧形的角度。
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush1, block.Bounds, 0, angle);

        webPImage.AddBlock(block);
    }

    // 逐渐增加黑色弧形的角度并抹去红色弧形。
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);

        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush2, block.Bounds, 0, angle);
        graphics.FillPie(brush1, block.Bounds, angle, 360 - angle);

        webPImage.AddBlock(block);
    }

    // 保存为 WebP 文件
    webPImage.Save(dir + "output.webp");
}
```

### 另请参见

* interface [IFrame](../../iframe/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)


