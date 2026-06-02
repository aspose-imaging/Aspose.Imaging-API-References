---
title: "GifImage.GifImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GifImage 构造函数。使用指定的首帧和全局调色板参数初始化新的 GifImage 对象。快速开始管理 GIF 图像，确保准确呈现，并通过可自定义设置获得最佳效果。"
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.gif/gifimage/gifimage/
---
## GifImage(GifFrameBlock, IColorPalette) {#constructor_1}

初始化一个新的 [`GifImage`](../) 对象，使用指定的首帧和全局调色板参数。快速开始管理 GIF 图像，确保准确呈现，并通过可自定义设置获得最佳效果。

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstFrame | GifFrameBlock | 用于初始化 GIF 图像的第一帧。 |
| globalPalette | IColorPalette | 要使用的全局调色板。注意，如果 *firstFrame* 和 *globalPalette* 均为 null，则使用默认全局调色板。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *firstFrame* 不能为空 |
| ArgumentException | *firstFrame* 已经属于其他图像。请检查 Container 属性。 |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception/) | 指定的 *globalPalette* 应包含条目数量为 2 的幂。最小调色板大小为 2，最大为 256。 |

## 示例

本示例展示了如何使用自定义调色板创建 GIF 图像并将其保存到文件。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100x100 像素的 GIF 帧块。
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // 将整个块填充为红色。
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    // 使用 4 位调色板可减小图像大小。质量可能会下降。
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.Create4Bit();

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock, palette))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

### 另请参见

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock/)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)

---

## GifImage(GifFrameBlock) {#constructor}

使用 [`GifImage`](../) 构造函数创建 GIF 图像变得轻而易举。只需提供 firstFrame 参数，即可进入动态视觉交流的世界。

```csharp
public GifImage(GifFrameBlock firstFrame)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstFrame | GifFrameBlock | 用于初始化 GIF 图像的第一帧。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *firstFrame* 不能为空 |
| ArgumentException | *firstFrame* 已经属于其他图像。请检查 Container 属性。 |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception/) | 指定的调色板必须包含条目数量为 2 的幂。最小调色板大小为 2，最大为 256。 |

## 示例

此示例展示了如何创建 GIF 图像并将其保存到文件。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100x100 像素的 GIF 帧块。
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // 将整个块填充为红色。
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

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

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)

---

## GifImage(GifFrameBlock, IColorPalette, bool, byte, byte, byte, bool) {#constructor_2}

使用 [`GifImage`](../) 构造函数轻松入门。通过此简便方法，您可以轻松创建动画 GIF。只需提供 firstFrame、globalPalette、paletteColorResolution、aspectRatio 等参数，即可让您的视觉作品栩栩如生。

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, bool isPaletteSorted, 
    byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, 
    bool hasTrailer)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| firstFrame | GifFrameBlock | 用于初始化 GIF 图像的第一帧。 |
| globalPalette | IColorPalette | 要使用的全局调色板。注意，如果 *firstFrame* 和 *globalPalette* 均为 null，则使用默认全局调色板。 |
| isPaletteSorted | Boolean | 如果设置为 `true`，调色板将被排序。注意，当 *globalPalette* 不为 null 时使用此参数。 |
| paletteColorResolution | Byte | 调色板颜色分辨率。注意，当 *globalPalette* 不为 null 时使用此参数。 |
| paletteBackgroundColorIndex | Byte | 调色板背景颜色索引。 |
| aspectRatio | Byte | 宽高比。 |
| hasTrailer | Boolean | 如果设置为 `true`，gif 图像将包含尾部；否则在流的末尾不写入尾部。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *firstFrame* 不能为空 |
| ArgumentException | *firstFrame* 已经属于其他图像。请检查 Container 属性。 |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception/) | 指定的 *globalPalette* 应包含条目数量为 2 的幂。最小调色板大小为 2，最大为 256。 |

### 另请参见

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock/)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


