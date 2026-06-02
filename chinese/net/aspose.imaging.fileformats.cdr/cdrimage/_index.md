---
title: "类 CdrImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Cdr.CdrImage 类。CorelDRAW CDR 矢量图像格式支持的 API 是面向矢量图形开发者的必备工具包。该 API 能够无缝处理 CDR 文件，支持存储和操作文本、线条、形状、图像、颜色和效果等多种元素。凭借其全面的功能，开发者可以高效地处理图像内容的矢量表示，确保在以编程方式创建和编辑 CorelDRAW 矢量图形时的精确性和灵活性。"
type: docs
weight: 1470
url: /zh/net/aspose.imaging.fileformats.cdr/cdrimage/
---
## CdrImage class

针对 CorelDRAW CDR 矢量图像格式的 API 是面向矢量图形开发者的必备工具包。该 API 实现对 CDR 文件的无缝处理，支持对文本、线条、形状、图像、颜色和特效等多种元素的存储和操作。凭借其全面的功能，开发者能够高效地处理图像内容的矢量表示，确保在以编程方式创建和编辑 CorelDRAW 矢量图形时的精确性和灵活性。

```csharp
public class CdrImage : VectorMultipageImage, ICdrImage
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CdrImage](cdrimage/)(Stream, LoadOptions) | 通过使用流和 loadOptions 参数初始化新实例，轻松开始使用 `CdrImage` 类。对于希望以便捷方式从各种数据源加载 CDR 图像并根据需要自定义加载过程的开发者而言，这是理想的选择。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | 获取或设置指示是否自动调整调色板的值。 |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| override [BitsPerPixel](../../aspose.imaging.fileformats.cdr/cdrimage/bitsperpixel/) { get; } | 使用此用户友好的属性，轻松获取图像的位深度。对于希望确定图像细节级别或颜色深度，以确保准确处理和操作的开发者而言，这是理想的选择。 |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | 获取图像的边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [CdrDocument](../../aspose.imaging.fileformats.cdr/cdrimage/cdrdocument/) { get; } | 使用此直观属性，轻松检索或更新 CDR 文档。对于希望访问或修改 CDR 文档，以确保应用程序灵活高效的开发者而言，这是理想的选择。 |
| [Container](../../aspose.imaging/image/container/) { get; } | 获取 [`Image`](../../aspose.imaging/image/) 容器。 |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| override [FileFormat](../../aspose.imaging.fileformats.cdr/cdrimage/fileformat/) { get; } | 使用此直观属性，轻松获取图像的文件格式。对于希望动态确定图像格式，以确保兼容性和准确处理的开发者而言，这是理想的选择。 |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | 获取或设置指示图像是否具有背景颜色的值。 |
| override [Height](../../aspose.imaging.fileformats.cdr/cdrimage/height/) { get; } | 获取图像高度。 |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf/) { get; } | 获取对象的高度（英寸）。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.imaging.fileformats.cdr/cdrimage/iscached/) { get; } | 轻松判断对象的数据是否已缓存，消除读取数据的需求。对于希望通过高效利用缓存数据来优化性能、确保更快访问信息的开发者而言，这是理想的选择。 |
| override [Metadata](../../aspose.imaging/vectormultipageimage/metadata/) { get; } | 获取图像元数据。 |
| override [PageCount](../../aspose.imaging.fileformats.cdr/cdrimage/pagecount/) { get; } | 使用此直观属性，轻松检索或更新图像的总页数。对于希望动态管理多页图像、确保高效导航和操作图像内容的开发者而言，这是理想的选择。 |
| virtual [PageExportingAction](../../aspose.imaging/vectormultipageimage/pageexportingaction/) { get; set; } | 获取或设置页面导出操作。请注意，设置此方法后将在执行后自动释放页面资源。它将在每个页面保存之前执行。 |
| override [Pages](../../aspose.imaging.fileformats.cdr/cdrimage/pages/) { get; } | 无缝检索图像的页面，使用此直观属性。适用于希望访问和操作多页图像中各个页面的开发者，确保高效的导航和处理。 |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | 获取或设置颜色调色板。当像素直接表示时，调色板不被使用。 |
| [Size](../../aspose.imaging/image/size/) { get; } | 获取图像尺寸。 |
| [SizeF](../../aspose.imaging/vectorimage/sizef/) { get; } | 获取对象的尺寸（英寸）。 |
| virtual [UsePalette](../../aspose.imaging/image/usepalette/) { get; } | 获取一个值，指示是否使用图像调色板。 |
| override [Width](../../aspose.imaging.fileformats.cdr/cdrimage/width/) { get; } | 获取图像宽度。 |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf/) { get; } | 获取对象的宽度（英寸）。 |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | 获取或设置 Xmp 数据。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.cdr/cdrimage/cachedata/)() | 轻松缓存数据，以防止从底层源额外加载，使用此用户友好方法。适用于希望通过预加载数据来优化性能的开发者，确保更快的访问和更流畅的应用操作。[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer/)。 |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为传入保存选项所表示的指定文件格式。 |
| override [Crop](../../aspose.imaging/vectormultipageimage/crop/)(Rectangle) | 裁剪指定的矩形。 |
| virtual [Crop](../../aspose.imaging/image/crop/)(int, int, int, int) | 使用位移裁剪图像。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| override [GetDefaultOptions](../../aspose.imaging/vectorimage/getdefaultoptions/)(object[]) | 获取默认的图像选项。 |
| override [GetEmbeddedImages](../../aspose.imaging/vectormultipageimage/getembeddedimages/)() | 获取嵌入的图像。 |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions/)() | 根据原始文件设置获取选项。这有助于保持原始图像的位深度和其他参数不变。例如，如果我们加载一幅每像素 1 位的黑白 PNG 图像，然后使用 [`Save`](../../aspose.imaging/datastreamsupporter/save/) 方法保存，输出的 PNG 图像将是每像素 8 位。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 [`Save`](../../aspose.imaging/image/save/) 方法。 |
| override [GetSerializedStream](../../aspose.imaging/vectormultipageimage/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | 转换为 aps。 |
| override [RemoveBackground](../../aspose.imaging/vectormultipageimage/removebackground/)() | 移除背景。 |
| override [RemoveBackground](../../aspose.imaging/vectormultipageimage/removebackground/)(RemoveBackgroundSettings) | 移除背景。 |
| virtual [RemoveMetadata](../../aspose.imaging/image/removemetadata/)() | 移除元数据。 |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | 调整图像大小。默认使用 NearestNeighbourResample。 |
| override [Resize](../../aspose.imaging/vectormultipageimage/resize/)(int, int, ImageResizeSettings) | 调整图像大小。 |
| override [Resize](../../aspose.imaging/vectormultipageimage/resize/)(int, int, ResizeType) | 调整图像大小。 |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | 按比例调整高度。默认使用 NearestNeighbourResample。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | 按比例调整宽度。使用默认的 NearestNeighbourResample。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ResizeType) | 按比例调整宽度。 |
| override [Rotate](../../aspose.imaging/vectormultipageimage/rotate/)(float) | 围绕中心旋转图像。 |
| override [RotateFlip](../../aspose.imaging/vectormultipageimage/rotateflip/)(RotateFlipType) | 旋转、翻转或同时旋转和翻转图像。 |
| [Save](../../aspose.imaging/image/save/)() | 将图像数据保存到底层流。 |
| [Save](../../aspose.imaging/datastreamsupporter/save/)(Stream) | 将对象的数据保存到指定的流。 |
| override [Save](../../aspose.imaging/image/save/)(string) | 将图像保存到指定的文件位置。 |
| [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase) | 根据保存选项，将图像数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| virtual [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase, Rectangle) | 根据保存选项，将图像数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase, Rectangle) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| override [SetPalette](../../aspose.imaging.fileformats.cdr/cdrimage/setpalette/)(IColorPalette, bool) | 使用此直观方法自定义图像的颜色调色板。适用于希望动态应用特定配色方案或调整的开发者，确保对图像视觉外观的精确控制。 |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | 尝试设置 *metadata* 实例，前提是此 [`Image`](../../aspose.imaging/image/) 实例支持并实现了 [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) 类型。 |

## 示例

以下示例展示了如何缓存 CDR 图像的所有页面。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从 CDR 文件加载图像。
using (Aspose.Imaging.FileFormats.Cdr.CdrImage image = (Aspose.Imaging.FileFormats.Cdr.CdrImage)Aspose.Imaging.Image.Load(dir + "sample.cdr"))
{
    // 此调用仅缓存默认页面。
    image.CacheData();

    // 缓存所有页面，以便不再从底层数据流执行额外的数据加载。
    foreach (Aspose.Imaging.FileFormats.Cdr.CdrImagePage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### 另请参见

* class [Image](../../aspose.imaging/image/)
* interface [ICdrImage](../icdrimage/)
* class [VectorMultipageImage](../../aspose.imaging/vectormultipageimage/)
* namespace [Aspose.Imaging.FileFormats.Cdr](../../aspose.imaging.fileformats.cdr/)
* assembly [Aspose.Imaging](../../)


