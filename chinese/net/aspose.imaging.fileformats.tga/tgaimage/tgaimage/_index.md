---
title: TgaImage
second_title: Aspose.Imaging for .NET API 参考
description: 初始化TgaImageaspose.imaging.fileformats.tga/tgaimage类.
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.tga/tgaimage/tgaimage/
---
## TgaImage(string) {#constructor_2}

初始化[`TgaImage`](../../tgaimage)类.

```csharp
public TgaImage(string path)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 加载图片的路径。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 指定路径为空。 |

### 也可以看看

* class [TgaImage](../../tgaimage)
* 命名空间 [Aspose.Imaging.FileFormats.Tga](../../tgaimage)
* 部件 [Aspose.Imaging](../../../)

---

## TgaImage(RasterImage) {#constructor}

初始化[`TgaImage`](../../tgaimage)类.

```csharp
public TgaImage(RasterImage rasterImage)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rasterImage | RasterImage | 光栅图像。 |

### 例子

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

### 也可以看看

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [TgaImage](../../tgaimage)
* 命名空间 [Aspose.Imaging.FileFormats.Tga](../../tgaimage)
* 部件 [Aspose.Imaging](../../../)

---

## TgaImage(Stream) {#constructor_1}

初始化[`TgaImage`](../../tgaimage)类.

```csharp
public TgaImage(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 加载图像的流。 |

### 也可以看看

* class [TgaImage](../../tgaimage)
* 命名空间 [Aspose.Imaging.FileFormats.Tga](../../tgaimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
