---
title: "类 OdgImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.OpenDocument.OdgImage 类。使用我们的 API 操作 OpenDocument 图形 ODG 矢量图像文件格式，该格式被 OpenOffice 和 LibreOffice Draw 应用广泛用于以矢量格式存储绘图元素。能够无缝解析文档、访问页面、调整大小和旋转图像，确保高效处理并可定制 ODG 文件以满足您的特定需求。"
type: docs
weight: 7500
url: /zh/net/aspose.imaging.fileformats.opendocument/odgimage/
---
## OdgImage class

使用我们的 API 操作 OpenDocument Graphic（ODG）矢量图像文件格式，该格式被 OpenOffice 和 LibreOffice Draw 应用广泛用于以矢量形式存储绘图元素。能够无缝解析文档、访问页面、调整图像大小和旋转，确保对 ODG 文件进行高效处理和定制，以满足您的特定需求。

```csharp
public class OdgImage : OdImage
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [OdgImage](odgimage/#constructor)(StreamContainer) | 为在软件解决方案中实现无缝集成而构建，`OdgImage` 构造函数通过利用流容器初始化新实例。此方法确保在软件环境中高效处理 ODG 图像数据，优化资源利用并促进简化的图像处理工作流。 |
| [OdgImage](odgimage/#constructor_1)(StreamContainer, LoadOptions) | 通过初始化全新实例开始创建 `OdgImage` 类对象。利用流容器与加载选项参数的组合，保持多功能构造函数以无缝加载图像。此构造函数提升了高效的图像处理能力，提供可自定义的加载配置，以在各种场景中实现更强的适应性和性能。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | 获取或设置指示是否自动调整调色板的值。 |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| override [BitsPerPixel](../../aspose.imaging.fileformats.opendocument/odimage/bitsperpixel/) { get; } | 检索图像的每像素位数。此属性提供图像细节级别和颜色深度的信息，有助于各种图像处理任务和优化。 |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | 获取图像的边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Container](../../aspose.imaging/image/container/) { get; } | 获取 [`Image`](../../aspose.imaging/image/) 容器。 |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| override [FileFormat](../../aspose.imaging.fileformats.opendocument/odgimage/fileformat/) { get; } | 获取文件格式的值 |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | 获取或设置指示图像是否具有背景颜色的值。 |
| override [Height](../../aspose.imaging/vectormultipageimage/height/) { get; } | 获取图像高度。 |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf/) { get; } | 获取对象的高度（英寸）。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.imaging.fileformats.opendocument/odimage/iscached/) { get; } | 获取一个布尔值，指示对象的数据是否已被缓存，从而消除读取数据的需求。此属性作为优化指示器，通过最小化冗余数据访问操作来提升性能。 |
| [Metadata](../../aspose.imaging.fileformats.opendocument/odimage/metadata/) { get; } | 检索特定于 OpenDocument 文件的元数据。此属性允许访问嵌入在 OD 文件中的关键信息，便于执行诸如提取、修改或分析元数据等各种操作。 |
| override [Metadata](../../aspose.imaging/vectormultipageimage/metadata/) { get; } | 获取图像元数据。 |
| override [PageCount](../../aspose.imaging.fileformats.opendocument/odimage/pagecount/) { get; } | 检索图像中页面的总数。此属性对于管理多页图像的应用程序至关重要，使它们能够准确确定可用于处理或显示的页面数量。 |
| virtual [PageExportingAction](../../aspose.imaging/vectormultipageimage/pageexportingaction/) { get; set; } | 获取或设置页面导出操作。请注意，设置此方法后将在执行后自动释放页面资源。它将在每个页面保存之前执行。 |
| override [Pages](../../aspose.imaging.fileformats.opendocument/odgimage/pages/) { get; } | 检索页面集合时，此属性使得能够访问与图像关联的全部页面。通过访问此属性，开发人员可以遍历各个页面、根据索引检索特定页面，或对整个集合执行批量操作。 |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | 获取或设置颜色调色板。当像素直接表示时，调色板不被使用。 |
| [Records](../../aspose.imaging.fileformats.opendocument/odimage/records/) { get; } | 检索存储在图像中的 OpenDocument 记录。此属性提供对嵌入在 OpenDocument 文件中的特定结构化数据元素的访问，便于检索或操作相关信息以进行进一步处理或分析。 |
| [Size](../../aspose.imaging/image/size/) { get; } | 获取图像尺寸。 |
| [SizeF](../../aspose.imaging/vectorimage/sizef/) { get; } | 获取对象的尺寸（英寸）。 |
| virtual [UsePalette](../../aspose.imaging/image/usepalette/) { get; } | 获取一个值，指示是否使用图像调色板。 |
| override [Width](../../aspose.imaging/vectormultipageimage/width/) { get; } | 获取图像宽度。 |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf/) { get; } | 获取对象的宽度（英寸）。 |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | 获取或设置 Xmp 数据。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [CacheData](../../aspose.imaging/vectormultipageimage/cachedata/)() | 缓存数据并确保不会从底层 [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) 加载额外数据。 |
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
| override [SetPalette](../../aspose.imaging/vectormultipageimage/setpalette/)(IColorPalette, bool) | 设置图像调色板。 |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | 尝试设置 *metadata* 实例，前提是此 [`Image`](../../aspose.imaging/image/) 实例支持并实现了 [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) 类型。 |

## 示例

此示例加载一个多页 ODG 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 使用 Aspose.Imaging.Image.Load 是加载图像的统一方式。
using (Aspose.Imaging.FileFormats.OpenDocument.OdImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // 转换为 OdgImage
    Aspose.Imaging.FileFormats.OpenDocument.OdgImage odgImage = (Aspose.Imaging.FileFormats.OpenDocument.OdgImage)image;

    // 获取所有页面
    Aspose.Imaging.Image[] pages = odgImage.Pages;

    // 进行一些图像处理
}
```

以下示例展示如何将 FODG（Flat XML ODF Template）图像导出为 PDF 格式。

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3635";

string inputFileName = System.IO.Path.Combine(dir, "VariousObjectsMultiPage.fodg");
string outputFileName = inputFileName + ".pdf";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFileName))
{
    Aspose.Imaging.ImageOptions.OdgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.OdgRasterizationOptions();
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.White;
    rasterizationOptions.PageSize = image.Size;

    Aspose.Imaging.ImageOptions.PdfOptions saveOptions = new Aspose.Imaging.ImageOptions.PdfOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    image.Save(outputFileName, saveOptions);
}
```

### 另请参见

* class [OdImage](../odimage/)
* namespace [Aspose.Imaging.FileFormats.OpenDocument](../../aspose.imaging.fileformats.opendocument/)
* assembly [Aspose.Imaging](../../)


