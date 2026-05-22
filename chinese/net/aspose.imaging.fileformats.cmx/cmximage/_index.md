---
title: "类 CmxImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Cmx.CmxImage 类。针对 Corel Metafile Exchange CMX 矢量图像格式并支持元数据描述的 API 是面向处理 CMX 文件的开发者的综合解决方案。该 API 允许无缝加载 CMX 图像并提取元数据，如每像素位数、对象尺寸等。通过额外的功能，如调整大小、旋转、设置调色板以及转换为其他格式，此 API 使开发者能够高效地操作和定制 CMX 矢量图像，以满足其特定的应用需求。"
type: docs
weight: 1950
url: /zh/net/aspose.imaging.fileformats.cmx/cmximage/
---
## CmxImage class

针对 Corel Metafile Exchange (CMX) 矢量图像格式并支持元数据描述的 API 是面向处理 CMX 文件的开发者的综合解决方案。该 API 允许无缝加载 CMX 图像，提取诸如每像素位数、对象尺寸等元数据。通过额外的功能，如调整大小、旋转、设置调色板以及转换为其他格式，该 API 使开发者能够高效地操作和定制 CMX 矢量图像，以满足其特定的应用需求。

```csharp
public class CmxImage : VectorMultipageImage, ICmxImage
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CmxImage](cmximage/)(StreamContainer, LoadOptions) | 通过使用 `CmxImage` 类并使用 streamContainer 和 loadOptions 参数初始化新实例，即可无缝开始工作。对于希望以便捷方式从各种数据源加载 CMX 图像并根据需要自定义加载过程的开发者而言，这是理想选择。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | 获取或设置指示是否自动调整调色板的值。 |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| override [BitsPerPixel](../../aspose.imaging.fileformats.cmx/cmximage/bitsperpixel/) { get; } | 使用此用户友好的属性，轻松获取图像的位深度。对于希望确定图像细节级别或颜色深度，以确保准确处理和操作的开发者而言，这是理想的选择。 |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | 获取图像的边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [CmxPage](../../aspose.imaging.fileformats.cmx/cmximage/cmxpage/) { get; } | 使用此直观属性即可轻松检索图像的 CMX 页面。对于希望快速访问 CMX 图像中各个页面、确保高效导航和管理的开发者而言，这是理想选择。 |
| [Container](../../aspose.imaging/image/container/) { get; } | 获取 [`Image`](../../aspose.imaging/image/) 容器。 |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [Document](../../aspose.imaging.fileformats.cmx/cmximage/document/) { get; } | 使用此直观属性即可轻松获取 CMX 文档。对于希望访问或修改 CMX 图像、在应用中确保灵活性和高效性的开发者而言，这是理想选择。 |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| override [FileFormat](../../aspose.imaging.fileformats.cmx/cmximage/fileformat/) { get; } | 使用此用户友好属性即可轻松获取图像的文件格式。对于希望动态确定图像格式、确保在应用中兼容性和准确处理的开发者而言，这是理想选择。 |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | 获取或设置指示图像是否具有背景颜色的值。 |
| override [Height](../../aspose.imaging/vectormultipageimage/height/) { get; } | 获取图像高度。 |
| override [HeightF](../../aspose.imaging.fileformats.cmx/cmximage/heightf/) { get; } | 使用此用户友好属性即可轻松获取对象的高度（以英寸为单位）。对于希望获取精确尺寸信息以实现有效布局和展示的开发者而言，这是理想选择。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.imaging.fileformats.cmx/cmximage/iscached/) { get; } | 确定对象的数据是否已缓存，从而消除读取数据的需求。对于希望通过高效利用缓存数据来优化性能、确保更快访问信息的开发者而言，这是理想选择。 |
| override [Metadata](../../aspose.imaging/vectormultipageimage/metadata/) { get; } | 获取图像元数据。 |
| override [PageCount](../../aspose.imaging.fileformats.cmx/cmximage/pagecount/) { get; } | 使用此直观属性即可获取图像的总页数。对于希望动态管理多页图像、确保高效导航和操作图像内容的开发者而言，这是理想选择。 |
| virtual [PageExportingAction](../../aspose.imaging/vectormultipageimage/pageexportingaction/) { get; set; } | 获取或设置页面导出操作。请注意，设置此方法后将在执行后自动释放页面资源。它将在每个页面保存之前执行。 |
| override [Pages](../../aspose.imaging.fileformats.cmx/cmximage/pages/) { get; } | 无缝检索图像的页面，使用此直观属性。适用于希望访问和操作多页图像中各个页面的开发者，确保高效的导航和处理。 |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | 获取或设置颜色调色板。当像素直接表示时，调色板不被使用。 |
| [Size](../../aspose.imaging/image/size/) { get; } | 获取图像尺寸。 |
| [SizeF](../../aspose.imaging/vectorimage/sizef/) { get; } | 获取对象的尺寸（英寸）。 |
| virtual [UsePalette](../../aspose.imaging/image/usepalette/) { get; } | 获取一个值，指示是否使用图像调色板。 |
| override [Width](../../aspose.imaging/vectormultipageimage/width/) { get; } | 获取图像宽度。 |
| override [WidthF](../../aspose.imaging.fileformats.cmx/cmximage/widthf/) { get; } | 使用此直观属性即可获取对象的宽度（以英寸为单位）。对于希望在应用中获得对象精确测量、确保准确布局和展示的开发者而言，这是理想选择。 |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | 获取或设置 Xmp 数据。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.cmx/cmximage/cachedata/)() | 使用此便捷方法缓存数据，以防止从底层源 [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) 进行额外加载。对于希望通过预加载数据来优化性能的开发者而言，这可确保更快的访问和更流畅的应用程序运行。 |
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
| override [SetPalette](../../aspose.imaging.fileformats.cmx/cmximage/setpalette/)(IColorPalette, bool) | 使用此直观方法自定义图像的颜色调色板。适用于希望动态应用特定配色方案或调整的开发者，确保对图像视觉外观的精确控制。 |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | 尝试设置 *metadata* 实例，前提是此 [`Image`](../../aspose.imaging/image/) 实例支持并实现了 [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) 类型。 |

## 示例

以下示例展示了如何缓存 CMX 图像的所有页面。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从 CMX 文件加载图像。
using (Aspose.Imaging.FileFormats.Cmx.CmxImage image = (Aspose.Imaging.FileFormats.Cmx.CmxImage)Aspose.Imaging.Image.Load(dir + "sample.cmx"))
{
    // 此调用仅缓存默认页面。
    image.CacheData();

    // 缓存所有页面，以便不再从底层数据流执行额外的数据加载。
    foreach (Aspose.Imaging.FileFormats.Cmx.CmxImagePage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### 另请参见

* class [Image](../../aspose.imaging/image/)
* class [VectorMultipageImage](../../aspose.imaging/vectormultipageimage/)
* interface [ICmxImage](../icmximage/)
* namespace [Aspose.Imaging.FileFormats.Cmx](../../aspose.imaging.fileformats.cmx/)
* assembly [Aspose.Imaging](../../)


