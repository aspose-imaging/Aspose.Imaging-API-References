---
title: GifImage
second_title: Aspose.Imaging for .NET API 参考
description: 初始化GifImageaspose.imaging.fileformats.gif/gifimage类.
type: docs
weight: 10
url: /zh/aspose.imaging.fileformats.gif/gifimage/gifimage/
---
## GifImage(GifFrameBlock, IColorPalette) {#constructor_1}

初始化[`GifImage`](../../gifimage)类.

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| firstFrame | GifFrameBlock | 用于初始化 gif 图像的第一帧。 |
| globalPalette | IColorPalette | 要使用的全局调色板。注意如果两者*firstFrame*和*globalPalette*为 null 则使用默认的全局调色板。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 帧不能为空；firstFrame |
| ArgumentException | 第一帧已经属于某个其他图像。检查 Container 属性。;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | 指定的调色板应包含等于 2 次方的条目数。最小调色板大小为 2，最大为 256。 |

### 例子

此示例说明如何使用自定义调色板创建 GIF 图像并将其保存到文件中。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100x100 像素的 GIF 帧块。
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // 用红色填充整个块。
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    // 使用 4 位调色板来减小图像大小。质量可能会变得更糟。
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.Create4Bit();

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock, palette))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

### 也可以看看

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifImage](../../gifimage)
* 命名空间 [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* 部件 [Aspose.Imaging](../../../)

---

## GifImage(GifFrameBlock) {#constructor}

初始化[`GifImage`](../../gifimage)类.

```csharp
public GifImage(GifFrameBlock firstFrame)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| firstFrame | GifFrameBlock | 用于初始化 gif 图像的第一帧。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 帧不能为空；firstFrame |
| ArgumentException | 第一帧已经属于某个其他图像。检查 Container 属性。;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | 指定的调色板应包含等于 2 次方的条目数。最小调色板大小为 2，最大为 256。 |

### 例子

此示例说明如何创建 GIF 图像并将其保存到文件中。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100x100 像素的 GIF 帧块。
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // 用红色填充整个块。
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

以下示例显示如何从单个 GIF 块组成动画 GIF 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 创建一个 100 x 100 像素的 GIF 图片。
// 默认情况下，第一个块是全黑的。
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // 第一个圆圈是红色的
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    //第二个圆圈是黑色的
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // 逐渐增加红色弧形的角度。
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // 逐渐增加黑色弧线的角度，将红色弧线抹去。
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

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* class [GifImage](../../gifimage)
* 命名空间 [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* 部件 [Aspose.Imaging](../../../)

---

## GifImage(GifFrameBlock, IColorPalette, bool, byte, byte, byte, bool) {#constructor_2}

初始化[`GifImage`](../../gifimage)类.

```csharp
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, bool isPaletteSorted, 
    byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, 
    bool hasTrailer)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| firstFrame | GifFrameBlock | 用于初始化 gif 图像的第一帧。 |
| globalPalette | IColorPalette | 要使用的全局调色板。注意如果两者*firstFrame*和*globalPalette*为 null 则使用默认的全局调色板。 |
| isPaletteSorted | Boolean | 如果设置为`真的`调色板已排序。注意该参数在使用时*globalPalette*不为空。 |
| paletteColorResolution | Byte | 调色板颜色分辨率。注意该参数在使用时*globalPalette*不为空。 |
| paletteBackgroundColorIndex | Byte | 调色板背景颜色索引。 |
| aspectRatio | Byte | 纵横比。 |
| hasTrailer | Boolean | 如果设置为`真的` gif 图像有预告片，否则在流的末尾没有写预告片。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 帧不能为空；firstFrame |
| ArgumentException | 第一帧已经属于某个其他图像。检查 Container 属性。;firstFrame |
| [GifImageException](../../../aspose.imaging.coreexceptions.imageformats/gifimageexception) | 指定的调色板应包含等于 2 次方的条目数。最小调色板大小为 2，最大为 256。 |

### 也可以看看

* class [GifFrameBlock](../../../aspose.imaging.fileformats.gif.blocks/gifframeblock)
* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifImage](../../gifimage)
* 命名空间 [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
