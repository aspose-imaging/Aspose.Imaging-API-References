---
title: "类 Html5CanvasOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageOptions.Html5CanvasOptions 类。使用我们的 API 轻松创建 HTML5 Canvas 文件，能够无缝组合表单、文本、图像、动画和链接等元素。受益于包括标签标识符和编码设置支持在内的强大功能，确保您的 Web 项目获得最佳性能和可定制性。"
type: docs
weight: 10360
url: /zh/net/aspose.imaging.imageoptions/html5canvasoptions/
---
## Html5CanvasOptions class

使用我们的 API 轻松创建 HTML5 Canvas 文件，能够无缝地组合表单、文本、图像、动画和链接等元素。受益于包括标签标识符和编码设置支持在内的强大功能，确保您的网页项目拥有最佳性能和可定制性。

```csharp
public class Html5CanvasOptions : ImageOptionsBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Html5CanvasOptions](html5canvasoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [CanvasTagId](../../aspose.imaging.imageoptions/html5canvasoptions/canvastagid/) { get; set; } | 获取或设置 canvas 标签标识符。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [Encoding](../../aspose.imaging.imageoptions/html5canvasoptions/encoding/) { get; set; } | 获取或设置编码。 |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | 获取或设置指示是否为 [full frame] 的值。 |
| [FullHtmlPage](../../aspose.imaging.imageoptions/html5canvasoptions/fullhtmlpage/) { get; set; } | 获取或设置一个值，指示是否应生成完整的 HTML 页面。 |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | 获取在导出时是否保留原始图像元数据的值。 |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | 多页选项 |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler/) { get; set; } | 获取或设置进度事件处理程序。 |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings/) { get; set; } | 获取或设置分辨率设置。 |
| [Source](../../aspose.imaging/imageoptionsbase/source/) { get; set; } | 获取或设置创建图像的来源。 |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 获取或设置矢量光栅化选项。 |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata/) { get; set; } | 获取或设置 XMP 元数据容器。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone/)() | 创建此实例的成员逐一克隆。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| [TrySetMetadata](../../aspose.imaging/imageoptionsbase/trysetmetadata/)(IImageMetadataFormat) | 尝试设置一个 *metadata* 实例，如果此 [`Image`](../../aspose.imaging/image/) 实例支持并实现了 [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) 实例。 |

## 示例

任何矢量图像（SVG、WMF、CMX 等）都可以用作 Canvas 图像的来源。以下代码创建一个简单的 Canvas 图像。

```csharp
[C#]

using (var image = Image.Load(@"Sample.svg"))
{
    image.Save(@"Canvas.html", new Html5CanvasOptions
    {
        VectorRasterizationOptions = new SvgRasterizationOptions()
    });
}
```

您可以在 HTML 页面中嵌入多个 Canvas 图像或更新已有页面。为此，您只需导出 Canvas 标签。

```csharp
[C#]

using (var image = Image.Load(@"Sample.svg"))
{
    image.Save(@"Canvas.html", new Html5CanvasOptions
    {
        VectorRasterizationOptions = new SvgRasterizationOptions(),
        FullHtmlPage = false
    });
}
```

### 另请参见

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


