---
title: "GifFrameBlock.GifFrameBlock"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GifFrameBlock 构造函数。初始化 GifFrameBlock 类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.gif.blocks/gifframeblock/gifframeblock/
---
## GifFrameBlock(ushort, ushort) {#constructor_9}

初始化 [`GifFrameBlock`](../) 类的新实例。

```csharp
public GifFrameBlock(ushort width, ushort height)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | UInt16 | 图像宽度。 |
| 高度 | UInt16 | 图像高度。 |

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

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort) {#constructor_10}

初始化 [`GifFrameBlock`](../) 类的新实例。

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 左 | UInt16 | 图像左侧位置。 |
| 上 | UInt16 | 图像顶部位置。 |
| 宽度 | UInt16 | 图像宽度。 |
| 高度 | UInt16 | 图像高度。 |

### 另请参见

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort, IColorPalette, bool, bool, byte) {#constructor_11}

初始化 [`GifFrameBlock`](../) 类的新实例。

```csharp
public GifFrameBlock(ushort left, ushort top, ushort width, ushort height, 
    IColorPalette colorPalette, bool isPaletteSorted, bool isGifFrameInterlaced, byte bitsPerPixel)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 左 | UInt16 | 图像左侧位置。 |
| 上 | UInt16 | 图像顶部位置。 |
| 宽度 | UInt16 | 图像宽度。 |
| 高度 | UInt16 | 图像高度。 |
| colorPalette | IColorPalette | 颜色调色板。 |
| isPaletteSorted | Boolean | 如果设置为 `true`，颜色调色板将被排序。 |
| isGifFrameInterlaced | Boolean | 如果设置为 `true`，GIF 帧将是交错的。 |
| bitsPerPixel | Byte | 每像素位数。 |

### 另请参见

* interface [IColorPalette](../../../aspose.imaging/icolorpalette/)
* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage) {#constructor}

初始化 [`GifFrameBlock`](../) 类的新实例。

```csharp
public GifFrameBlock(RasterImage image)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 用于初始化帧像素和调色板数据的图像。 |

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort) {#constructor_1}

初始化 [`GifFrameBlock`](../) 类的新实例。

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 用于初始化帧像素和调色板数据的图像。 |
| 左 | UInt16 | 图像左侧位置。 |
| 上 | UInt16 | 图像顶部位置。 |

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage, ushort, ushort, bool, bool, byte) {#constructor_2}

初始化 [`GifFrameBlock`](../) 类的新实例。

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 用于初始化帧像素和调色板数据的图像。 |
| 左 | UInt16 | 图像左侧位置。 |
| 上 | UInt16 | 图像顶部位置。 |
| isPaletteSorted | Boolean | 如果设置为 `true`，颜色调色板将被排序。 |
| isGifFrameInterlaced | Boolean | 如果设置为 `true`，GIF 帧将是交错的。 |
| lzwCodeSize | Byte | 每像素位数。 |

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream) {#constructor_3}

初始化 [`GifFrameBlock`](../) 类的新实例。

```csharp
public GifFrameBlock(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像并初始化帧像素和调色板数据的流。 |

### 另请参见

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort) {#constructor_4}

初始化 [`GifFrameBlock`](../) 类的新实例。

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像并初始化帧像素和调色板数据的流。 |
| 左 | UInt16 | 图像左侧位置。 |
| 上 | UInt16 | 图像顶部位置。 |

### 另请参见

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort, bool, bool, byte) {#constructor_5}

初始化 [`GifFrameBlock`](../) 类的新实例。

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像并初始化帧像素和调色板数据的流。 |
| 左 | UInt16 | 图像左侧位置。 |
| 上 | UInt16 | 图像顶部位置。 |
| isPaletteSorted | Boolean | 如果设置为 `true`，颜色调色板将被排序。 |
| isGifFrameInterlaced | Boolean | 如果设置为 `true`，GIF 帧将是交错的。 |
| lzwCodeSize | Byte | 每像素位数。 |

### 另请参见

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(string) {#constructor_6}

初始化 [`GifFrameBlock`](../) 类的新实例。

```csharp
public GifFrameBlock(string path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 用于加载图像并初始化帧像素和调色板数据的路径。 |

### 另请参见

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort) {#constructor_7}

初始化 [`GifFrameBlock`](../) 类的新实例。

```csharp
public GifFrameBlock(string path, ushort left, ushort top)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 用于加载图像并初始化帧像素和调色板数据的路径。 |
| 左 | UInt16 | 图像左侧位置。 |
| 上 | UInt16 | 图像顶部位置。 |

### 另请参见

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort, bool, bool, byte) {#constructor_8}

初始化 [`GifFrameBlock`](../) 类的新实例。

```csharp
public GifFrameBlock(string path, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 用于加载图像并初始化帧像素和调色板数据的路径。 |
| 左 | UInt16 | 图像左侧位置。 |
| 上 | UInt16 | 图像顶部位置。 |
| isPaletteSorted | Boolean | 如果设置为 `true`，颜色调色板将被排序。 |
| isGifFrameInterlaced | Boolean | 如果设置为 `true`，GIF 帧将是交错的。 |
| lzwCodeSize | Byte | 每像素位数。 |

### 另请参见

* class [GifFrameBlock](../)
* namespace [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock/)
* assembly [Aspose.Imaging](../../../)


