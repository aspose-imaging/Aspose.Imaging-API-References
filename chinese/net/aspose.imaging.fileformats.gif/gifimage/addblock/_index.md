---
title: AddBlock
second_title: Aspose.Imaging for .NET API 参考
description: 添加一个新的 GIF 块
type: docs
weight: 210
url: /zh/net/aspose.imaging.fileformats.gif/gifimage/addblock/
---
## GifImage.AddBlock method

添加一个新的 GIF 块。

```csharp
public void AddBlock(IGifBlock block)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| block | IGifBlock | 要添加的 GIF 块。 |

### 例子

以下示例展示了如何从单个 GIF 块组成动画 GIF 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

    // 创建一个 100 x 100 像素的 GIF 图片。
    // 第一个块默认是全黑的
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
        // 第一个圆圈是red
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

        //第二个圆圈是black
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

        // 逐渐增加红色圆弧形状的角度。
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

        // 逐渐增加黑弧的角度，抹去红弧。
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

### 也可以看看

* interface [IGifBlock](../../igifblock)
* class [GifImage](../../gifimage)
* 命名空间 [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
