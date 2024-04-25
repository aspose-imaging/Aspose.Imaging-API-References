---
title: GifFrameBlock
second_title: Aspose.Imaging for .NET API 参考
description: 初始化GifFrameBlockaspose.imaging.fileformats.gif.blocks/gifframeblock类.
type: docs
weight: 10
url: /zh/aspose.imaging.fileformats.gif.blocks/gifframeblock/gifframeblock/
---
## GifFrameBlock(ushort, ushort) {#constructor_9}

初始化[`GifFrameBlock`](../../gifframeblock)类.

```csharp
public GifFrameBlock(ushort width, ushort height)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | UInt16 | 图像宽度。 |
| height | UInt16 | 图像高度。 |

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

* class [GifFrameBlock](../../gifframeblock)
* 命名空间 [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* 部件 [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort) {#constructor_10}

初始化[`GifFrameBlock`](../../gifframeblock)类.

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| left | UInt16 | 左侧图像位置。 |
| top | UInt16 | 顶部图像位置。 |
| width | UInt16 | 图像宽度。 |
| height | UInt16 | 图像高度。 |

### 也可以看看

* class [GifFrameBlock](../../gifframeblock)
* 命名空间 [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* 部件 [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort, IColorPalette, bool, bool, byte) {#constructor_11}

初始化[`GifFrameBlock`](../../gifframeblock)类.

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height, 
    IColorPalette colorPalette, bool isPaletteSorted, bool isGifFrameInterlaced, byte bitsPerPixel)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| left | UInt16 | 左侧图像位置。 |
| top | UInt16 | 顶部图像位置。 |
| width | UInt16 | 图像宽度。 |
| height | UInt16 | 图像高度。 |
| colorPalette | IColorPalette | 调色板。 |
| isPaletteSorted | Boolean | 如果设置为`真的`调色板已排序。 |
| isGifFrameInterlaced | Boolean | 如果设置为`真的` GIF 帧是交错的。 |
| bitsPerPixel | Byte | 每像素位数。 |

### 也可以看看

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifFrameBlock](../../gifframeblock)
* 命名空间 [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* 部件 [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage) {#constructor}

初始化[`GifFrameBlock`](../../gifframeblock)类.

```csharp
public GifFrameBlock(RasterImage image)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 用于初始化帧像素和调色板数据的图像。 |

### 也可以看看

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* 命名空间 [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* 部件 [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort) {#constructor_1}

初始化[`GifFrameBlock`](../../gifframeblock)类.

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 用于初始化帧像素和调色板数据的图像。 |
| left | UInt16 | 左侧图像位置。 |
| top | UInt16 | 顶部图像位置。 |

### 也可以看看

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* 命名空间 [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* 部件 [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort, bool, bool, byte) {#constructor_2}

初始化[`GifFrameBlock`](../../gifframeblock)类.

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 用于初始化帧像素和调色板数据的图像。 |
| left | UInt16 | 左侧图像位置。 |
| top | UInt16 | 顶部图像位置。 |
| isPaletteSorted | Boolean | 如果设置为`真的`调色板已排序。 |
| isGifFrameInterlaced | Boolean | 如果设置为`真的` GIF 帧是交错的。 |
| lzwCodeSize | Byte | 每像素位数。 |

### 也可以看看

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* 命名空间 [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* 部件 [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream) {#constructor_3}

初始化[`GifFrameBlock`](../../gifframeblock)类.

```csharp
public GifFrameBlock(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于从中加载图像并用于初始化帧像素和调色板数据的流。 |

### 也可以看看

* class [GifFrameBlock](../../gifframeblock)
* 命名空间 [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* 部件 [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort) {#constructor_4}

初始化[`GifFrameBlock`](../../gifframeblock)类.

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于从中加载图像并用于初始化帧像素和调色板数据的流。 |
| left | UInt16 | 左侧图像位置。 |
| top | UInt16 | 顶部图像位置。 |

### 也可以看看

* class [GifFrameBlock](../../gifframeblock)
* 命名空间 [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* 部件 [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort, bool, bool, byte) {#constructor_5}

初始化[`GifFrameBlock`](../../gifframeblock)类.

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于从中加载图像并用于初始化帧像素和调色板数据的流。 |
| left | UInt16 | 左侧图像位置。 |
| top | UInt16 | 顶部图像位置。 |
| isPaletteSorted | Boolean | 如果设置为`真的`调色板已排序。 |
| isGifFrameInterlaced | Boolean | 如果设置为`真的` GIF 帧是交错的。 |
| lzwCodeSize | Byte | 每像素位数。 |

### 也可以看看

* class [GifFrameBlock](../../gifframeblock)
* 命名空间 [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* 部件 [Aspose.Imaging](../../../)

---

## GifFrameBlock(string) {#constructor_6}

初始化[`GifFrameBlock`](../../gifframeblock)类.

```csharp
public GifFrameBlock(string path)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 从中加载图像和初始化帧像素和调色板数据的路径。 |

### 也可以看看

* class [GifFrameBlock](../../gifframeblock)
* 命名空间 [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* 部件 [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort) {#constructor_7}

初始化[`GifFrameBlock`](../../gifframeblock)类.

```csharp
public GifFrameBlock(string path, ushort left, ushort top)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 从中加载图像和初始化帧像素和调色板数据的路径。 |
| left | UInt16 | 左侧图像位置。 |
| top | UInt16 | 顶部图像位置。 |

### 也可以看看

* class [GifFrameBlock](../../gifframeblock)
* 命名空间 [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* 部件 [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort, bool, bool, byte) {#constructor_8}

初始化[`GifFrameBlock`](../../gifframeblock)类.

```csharp
public GifFrameBlock(string path, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 从中加载图像和初始化帧像素和调色板数据的路径。 |
| left | UInt16 | 左侧图像位置。 |
| top | UInt16 | 顶部图像位置。 |
| isPaletteSorted | Boolean | 如果设置为`真的`调色板已排序。 |
| isGifFrameInterlaced | Boolean | 如果设置为`真的` GIF 帧是交错的。 |
| lzwCodeSize | Byte | 每像素位数。 |

### 也可以看看

* class [GifFrameBlock](../../gifframeblock)
* 命名空间 [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
