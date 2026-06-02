---
title: "类 IcoOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageOptions.IcoOptions 类。使用我们的 API 轻松创建用于应用程序图标的自定义 ICO 图像文件，使您能够无缝呈现软件。我们的 API 支持 PNG 和 BMP 图像帧，并提供多种每像素位数，确保在图标创建需求中的多样性和兼容性。"
type: docs
weight: 10370
url: /zh/net/aspose.imaging.imageoptions/icooptions/
---
## IcoOptions class

使用我们的 API 轻松创建用于应用程序图标的自定义 ICO 图像文件，使您能够无缝地展示软件形象。我们的 API 支持具有不同每像素位数的 PNG 和 BMP 图像帧，确保在图标创建需求中具备多样性和兼容性。

```csharp
public class IcoOptions : ImageOptionsBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [IcoOptions](icooptions/#constructor)() | 使用 ICO 帧格式为 Png 且 bitsPerPixel 为 32 初始化 `IcoOptions` 类的新实例。 |
| [IcoOptions](icooptions/#constructor_1)(FileFormat, int) | 初始化 `IcoOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BitsPerPixel](../../aspose.imaging.imageoptions/icooptions/bitsperpixel/) { get; set; } | 获取或设置每像素位数值。 |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| [Format](../../aspose.imaging.imageoptions/icooptions/format/) { get; set; } | 获取或设置 ICO 帧格式。 |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | 获取或设置指示是否为 [full frame] 的值。 |
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

### 另请参见

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


