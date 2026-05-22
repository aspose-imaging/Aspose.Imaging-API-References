---
title: "类 DxfOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageOptions.DxfOptions 类。用于绘图交换格式 DXF 矢量图像创建的 API 提供了针对生成 AutoCAD 绘图文件的精确且灵活的定制解决方案。专门为处理文本线条和贝塞尔曲线而设计，开发者可以高效地操作这些元素、计数贝塞尔点并将曲线转换为多段线，以实现无缝导出，确保 DXF 矢量图像的兼容性和保真度"
type: docs
weight: 10310
url: /zh/net/aspose.imaging.imageoptions/dxfoptions/
---
## DxfOptions class

Drawing Interchange Format（DXF）矢量图像创建的 API 提供了生成 AutoCAD 绘图文件的精准且灵活的定制解决方案。专为处理文本线条和贝塞尔曲线而设计，开发者可以高效地操作这些元素，统计贝塞尔点数，并将曲线转换为折线以实现无缝导出，确保 DXF 矢量图像的兼容性和保真度。

```csharp
public class DxfOptions : ImageOptionsBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DxfOptions](dxfoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BezierPointCount](../../aspose.imaging.imageoptions/dxfoptions/bezierpointcount/) { get; set; } | 在将贝塞尔曲线转换为多段线时生成的点数，最少 4。用于当  和  都被 /// 设置为 `true` 时 |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [ConvertTextBeziers](../../aspose.imaging.imageoptions/dxfoptions/converttextbeziers/) { get; set; } | 当  被设置为 `true` 时生效。是否将文本轮廓中的贝塞尔曲线转换为多点多段线。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | 获取或设置指示是否为 [full frame] 的值。 |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | 获取在导出时是否保留原始图像元数据的值。 |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | 多页选项 |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler/) { get; set; } | 获取或设置进度事件处理程序。 |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings/) { get; set; } | 获取或设置分辨率设置。 |
| [Source](../../aspose.imaging/imageoptionsbase/source/) { get; set; } | 获取或设置创建图像的来源。 |
| [TextAsLines](../../aspose.imaging.imageoptions/dxfoptions/textaslines/) { get; set; } | 文本是应导出为由多段线组成的轮廓（默认）还是可编辑的 Autocad TEXT 实体。如果设置了此选项 |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 获取或设置矢量光栅化选项。 |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata/) { get; set; } | 获取或设置 XMP 元数据容器。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone/)() | 创建此实例的成员逐一克隆。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| [TrySetMetadata](../../aspose.imaging/imageoptionsbase/trysetmetadata/)(IImageMetadataFormat) | 尝试设置一个 *metadata* 实例，如果此 [`Image`](../../aspose.imaging/image/) 实例支持并实现了 [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) 实例。 |

## 示例

此示例演示导出为 Dxf 格式

```csharp
[C#]

//创建 Image 实例并使用磁盘位置的现有图像文件进行初始化
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"input.svg"))
{
    Aspose.Imaging.ImageOptions.DxfOptions options = new Aspose.Imaging.ImageOptions.DxfOptions();
    options.TextAsLines = true;
    options.ConvertTextBeziers = true;
    options.BezierPointCount = 20;
    image.Save("output.dxf", options);
}
```

### 另请参见

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


