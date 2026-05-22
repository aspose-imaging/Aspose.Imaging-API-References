---
title: "TgaImage.TgaImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TgaImage 构造函数。使用提供的文件路径加载图像内容来初始化新的 TgaImage 对象。此构造函数高效地初始化图像实例，允许无缝访问 TGA 图像文件，简化在应用程序工作流中的集成。"
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.tga/tgaimage/tgaimage/
---
## TgaImage(string) {#constructor_2}

使用提供的文件路径加载图像内容，初始化一个新的 [`TgaImage`](../) 对象。此构造函数高效地初始化图像实例，允许无缝访问 TGA 图像文件，简化在应用程序工作流中的集成。

```csharp
public TgaImage(string path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 用于加载图像的路径。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 指定的路径为 null。 |

### 另请参见

* class [TgaImage](../)
* namespace [Aspose.Imaging.FileFormats.Tga](../../tgaimage/)
* assembly [Aspose.Imaging](../../../)

---

## TgaImage(RasterImage) {#constructor}

通过提供光栅图像对象，创建一个新的 [`TgaImage`](../) 类实例。此构造函数促进现有光栅图像直接集成到 TGA 图像格式中，简化转换过程，以提升软件系统的兼容性。

```csharp
public TgaImage(RasterImage rasterImage)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | RasterImage | 栅格图像。 |

## 示例

加载 PNG 图像，将其转换为 TgaImage 并保存为 TGA 图像。

```csharp
[C#]

using (RasterImage image = (RasterImage)Image.Load("test.png"))
{
    using (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.Save("test.tga");
    }
}
```

### 另请参见

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [TgaImage](../)
* namespace [Aspose.Imaging.FileFormats.Tga](../../tgaimage/)
* assembly [Aspose.Imaging](../../../)

---

## TgaImage(Stream) {#constructor_1}

使用流加载图像，初始化一个新的 [`TgaImage`](../) 类实例。此构造函数允许从流中无缝集成图像数据，促进在软件应用中高效处理 TGA 图像。

```csharp
public TgaImage(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像的流。 |

### 另请参见

* class [TgaImage](../)
* namespace [Aspose.Imaging.FileFormats.Tga](../../tgaimage/)
* assembly [Aspose.Imaging](../../../)


