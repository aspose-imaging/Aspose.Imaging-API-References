---
title: "GifImage.AddBlock"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GifImage 方法。添加新的 GIF 块允许您在图像中包含额外的数据。此方法使您能够向 GIF 图像追加自定义块，这些块可以包含各种类型的信息"
type: docs
weight: 190
url: /zh/net/aspose.imaging.fileformats.gif/gifimage/addblock/
---
## GifImage.AddBlock method

添加新的 GIF 块可让您在图像中包含额外数据。此方法使您能够向 GIF 图像追加自定义块，这些块可以包含各种类型的信息。

```csharp
public void AddBlock(IGifBlock block)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 块 | IGifBlock | 要添加的 GIF 块。 |

## 示例

下面的示例展示了如何从单个 GIF 块组合成动画 GIF 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100 x 100 像素的 GIF 图像。
// 默认情况下，第一个块是全黑的。
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // 第一个圆是红色的
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // 第二个圆是黑色的
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // 逐渐增加红色弧形的角度。
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // 逐渐增加黑色弧形的角度并抹去红色弧形。
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush2, block.Bounds, 0, angle);
        gr.FillPie(brush1, block.Bounds, angle, 360 - angle);

        gifImage.AddBlock(block);
    }

    gifImage.Save(dir + "animated_radar.gif");
}
```

### 另请参见

* interface [IGifBlock](../../igifblock/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


