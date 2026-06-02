---
title: "WebPFrameBlock.WebPFrameBlock"
second_title: "Aspose.Imaging for .NET API 参考"
description: "WebPFrameBlock 构造函数。初始化 WebPFrameBlock 的新实例"
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.webp/webpframeblock/webpframeblock/
---
## WebPFrameBlock(RasterImage) {#constructor}

初始化 [`WebPFrameBlock`](../) 的新实例

类。

```csharp
public WebPFrameBlock(RasterImage rasterImage)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | RasterImage | 栅格图像。 |

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [WebPFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## WebPFrameBlock(int, int) {#constructor_1}

初始化 [`WebPFrameBlock`](../) 类的新实例。

```csharp
public WebPFrameBlock(int width, int height)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | Int32 | 宽度。 |
| 高度 | Int32 | 高度。 |

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

* class [WebPFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpframeblock/)
* assembly [Aspose.Imaging](../../../)


