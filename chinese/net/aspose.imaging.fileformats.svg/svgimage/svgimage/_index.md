---
title: "SvgImage.SvgImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "SvgImage 构造函数。实例化一个新的 SvgImage 类对象，使用指定的路径定位并加载图像。此构造函数便于从外部文件创建 SVG 图像实例，实现与软件系统和工作流的无缝集成。"
type: docs
weight: 10
url: /zh/net/aspose.imaging.fileformats.svg/svgimage/svgimage/
---
## SvgImage(string) {#constructor_3}

实例化一个新的 [`SvgImage`](../) 类对象，使用指定的路径定位并加载图像。此构造函数便于从外部文件创建 SVG 图像实例，实现与软件系统和工作流的无缝集成。

```csharp
public SvgImage(string path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 加载图像的路径，并使用该路径初始化像素和调色板数据。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 路径为 null。 |

### 另请参见

* class [SvgImage](../)
* namespace [Aspose.Imaging.FileFormats.Svg](../../svgimage/)
* assembly [Aspose.Imaging](../../../)

---

## SvgImage(Stream) {#constructor_2}

创建一个新的 [`SvgImage`](../) 类实例，从提供的流中加载图像。此构造函数实现了从流直接加载 SVG 图像，提升了在软件应用中处理图像资源的灵活性和效率。

```csharp
public SvgImage(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于加载图像并初始化像素和调色板数据的流。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 流为 null。 |

## 示例

此示例展示了如何从文件流加载 SVG 图像并将其光栅化为 PNG。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件流加载 SVG 图像。
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "test.svg"))
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = new Aspose.Imaging.FileFormats.Svg.SvgImage(stream))
{
    // 为了光栅化 SVG，我们需要指定光栅化选项。
    Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    svgImage.Save(dir + "test.output.png", saveOptions);
}
```

### 另请参见

* class [SvgImage](../)
* namespace [Aspose.Imaging.FileFormats.Svg](../../svgimage/)
* assembly [Aspose.Imaging](../../../)

---

## SvgImage(int, int) {#constructor_1}

实例化一个具有指定宽度和高度的新 [`SvgImage`](../) 对象。此构造函数允许开发者创建具有预定义尺寸的 SVG 图像，便于在初始化期间精确控制图像大小。

```csharp
public SvgImage(int width, int height)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | Int32 | 图像宽度。 |
| 高度 | Int32 | 图像高度。 |

### 另请参见

* class [SvgImage](../)
* namespace [Aspose.Imaging.FileFormats.Svg](../../svgimage/)
* assembly [Aspose.Imaging](../../../)

---

## SvgImage(SvgOptions, int, int) {#constructor}

使用指定的 SVG 选项、图像宽度和高度参数创建 [`SvgImage`](../) 类的新实例。此构造函数使开发者能够使用自定义选项和尺寸初始化 SVG 图像，提供了在管理 SVG 内容和布局时的灵活性。

```csharp
public SvgImage(SvgOptions svgOptions, int width, int height)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| svgOptions | SvgOptions | SVG 选项。 |
| 宽度 | Int32 | 图像宽度。 |
| 高度 | Int32 | 图像高度。 |

### 另请参见

* class [SvgOptions](../../../aspose.imaging.imageoptions/svgoptions/)
* class [SvgImage](../)
* namespace [Aspose.Imaging.FileFormats.Svg](../../svgimage/)
* assembly [Aspose.Imaging](../../../)


