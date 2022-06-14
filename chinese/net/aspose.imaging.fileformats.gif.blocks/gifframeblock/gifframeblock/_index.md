---
title: GifFrameBlock
second_title: Aspose.Imaging for .NET API 参考
description: 初始化GifFrameBlockaspose.imaging.fileformats.gif.blocks/gifframeblock类的新实例
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.gif.blocks/gifframeblock/gifframeblock/
---
## GifFrameBlock(ushort, ushort) {#constructor_9}

初始化[`GifFrameBlock`](../../gifframeblock)类的新实例。

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

此示例说明如何使用自定义调色板创建 GIF 图像并将其保存到文件中。

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

* class [GifFrameBlock](../../gifframeblock)
* 命名空间 [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* 部件 [Aspose.Imaging](../../../)

---

## GifFrameBlock(ushort, ushort, ushort, ushort) {#constructor_10}

初始化[`GifFrameBlock`](../../gifframeblock)类的新实例。

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

初始化[`GifFrameBlock`](../../gifframeblock)类的新实例。

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
| isPaletteSorted | Boolean | 如果设置为` true` 调色板被排序。 |
| isGifFrameInterlaced | Boolean | 如果设置为` true` GIF 帧是隔行扫描的。 |
| bitsPerPixel | Byte | 每个像素的位数。 |

### 也可以看看

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [GifFrameBlock](../../gifframeblock)
* 命名空间 [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* 部件 [Aspose.Imaging](../../../)

---

## GifFrameBlock(RasterImage) {#constructor}

初始化[`GifFrameBlock`](../../gifframeblock)类的新实例。

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

初始化[`GifFrameBlock`](../../gifframeblock)类的新实例。

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

初始化[`GifFrameBlock`](../../gifframeblock)类的新实例。

```csharp
public GifFrameBlock(RasterImage image, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | RasterImage | 用于初始化帧像素和调色板数据的图像。 |
| left | UInt16 | 左侧图像位置。 |
| top | UInt16 | 顶部图像位置。 |
| isPaletteSorted | Boolean | 如果设置为` true` 调色板被排序。 |
| isGifFrameInterlaced | Boolean | 如果设置为` true` GIF 帧是隔行扫描的。 |
| lzwCodeSize | Byte | 每像素位数。 |

### 也可以看看

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [GifFrameBlock](../../gifframeblock)
* 命名空间 [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* 部件 [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream) {#constructor_3}

初始化[`GifFrameBlock`](../../gifframeblock)类的新实例。

```csharp
public GifFrameBlock(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像和初始化帧像素和调色板数据的流。 |

### 也可以看看

* class [GifFrameBlock](../../gifframeblock)
* 命名空间 [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* 部件 [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort) {#constructor_4}

初始化[`GifFrameBlock`](../../gifframeblock)类的新实例。

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像和初始化帧像素和调色板数据的流。 |
| left | UInt16 | 左侧图像位置。 |
| top | UInt16 | 顶部图像位置。 |

### 也可以看看

* class [GifFrameBlock](../../gifframeblock)
* 命名空间 [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* 部件 [Aspose.Imaging](../../../)

---

## GifFrameBlock(Stream, ushort, ushort, bool, bool, byte) {#constructor_5}

初始化[`GifFrameBlock`](../../gifframeblock)类的新实例。

```csharp
public GifFrameBlock(Stream stream, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像和初始化帧像素和调色板数据的流。 |
| left | UInt16 | 左侧图像位置。 |
| top | UInt16 | 顶部图像位置。 |
| isPaletteSorted | Boolean | 如果设置为` true` 调色板被排序。 |
| isGifFrameInterlaced | Boolean | 如果设置为` true` GIF 帧是隔行扫描的。 |
| lzwCodeSize | Byte | 每像素位数。 |

### 也可以看看

* class [GifFrameBlock](../../gifframeblock)
* 命名空间 [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* 部件 [Aspose.Imaging](../../../)

---

## GifFrameBlock(string) {#constructor_6}

初始化[`GifFrameBlock`](../../gifframeblock)类的新实例。

```csharp
public GifFrameBlock(string path)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 加载图像和初始化帧像素和调色板数据的路径。 |

### 也可以看看

* class [GifFrameBlock](../../gifframeblock)
* 命名空间 [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* 部件 [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort) {#constructor_7}

初始化[`GifFrameBlock`](../../gifframeblock)类的新实例。

```csharp
public GifFrameBlock(string path, ushort left, ushort top)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 加载图像和初始化帧像素和调色板数据的路径。 |
| left | UInt16 | 左侧图像位置。 |
| top | UInt16 | 顶部图像位置。 |

### 也可以看看

* class [GifFrameBlock](../../gifframeblock)
* 命名空间 [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* 部件 [Aspose.Imaging](../../../)

---

## GifFrameBlock(string, ushort, ushort, bool, bool, byte) {#constructor_8}

初始化[`GifFrameBlock`](../../gifframeblock)类的新实例。

```csharp
public GifFrameBlock(string path, ushort left, ushort top, bool isPaletteSorted, 
    bool isGifFrameInterlaced, byte lzwCodeSize)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 加载图像和初始化帧像素和调色板数据的路径。 |
| left | UInt16 | 左侧图像位置。 |
| top | UInt16 | 顶部图像位置。 |
| isPaletteSorted | Boolean | 如果设置为` true` 调色板被排序。 |
| isGifFrameInterlaced | Boolean | 如果设置为` true` GIF 帧是隔行扫描的。 |
| lzwCodeSize | Byte | 每像素位数。 |

### 也可以看看

* class [GifFrameBlock](../../gifframeblock)
* 命名空间 [Aspose.Imaging.FileFormats.Gif.Blocks](../../gifframeblock)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
