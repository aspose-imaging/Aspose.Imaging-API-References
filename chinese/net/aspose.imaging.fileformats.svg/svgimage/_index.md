---
title: "类 SvgImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Svg.SvgImage 类。使用我们的 API 操作标量矢量图形 SVG 图像文件，利用基于 XML 的文本格式的强大功能，实现无缝定制和可伸缩性。轻松加载 SVG 图像、光栅化矢量元素并转换为其他格式，同时控制压缩级别，以优化文件大小和质量，满足您的项目需求。"
type: docs
weight: 7660
url: /zh/net/aspose.imaging.fileformats.svg/svgimage/
---
## SvgImage class

使用我们的 API 操作标量矢量图形（SVG）图像文件，利用基于 XML 的文本格式的强大功能，实现无缝的自定义和可伸缩性。可以轻松加载 SVG 图像、栅格化矢量元素并转换为其他格式，同时控制压缩级别以优化文件大小和质量，满足您的项目需求。

```csharp
public sealed class SvgImage : VectorImage
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SvgImage](svgimage/#constructor_2)(Stream) | 创建 `SvgImage` 类的新实例，从提供的流中加载图像。此构造函数支持直接从流中加载 SVG 图像，提升在软件应用中处理图像资源的灵活性和效率。 |
| [SvgImage](svgimage/#constructor_3)(string) | 实例化 `SvgImage` 类的新对象，使用指定的路径定位并加载图像。此构造函数便于从外部文件创建 SVG 图像实例，实现与软件系统和工作流的无缝集成。 |
| [SvgImage](svgimage/#constructor_1)(int, int) | 使用指定的宽度和高度实例化新的 `SvgImage` 对象。此构造函数允许开发者创建具有预定义尺寸的 SVG 图像，便于在初始化期间精确控制图像大小。 |
| [SvgImage](svgimage/#constructor)(SvgOptions, int, int) | 使用指定的 SVG 选项、图像宽度和高度参数创建 `SvgImage` 类的新实例。此构造函数使开发者能够使用自定义选项和尺寸初始化 SVG 图像，提供在管理 SVG 内容和布局方面的灵活性。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | 获取或设置指示是否自动调整调色板的值。 |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| override [BitsPerPixel](../../aspose.imaging.fileformats.svg/svgimage/bitsperpixel/) { get; } | 检索图像的每像素位数。需要注意的是，此参数不适用于矢量图像，因为它们不是以像素为单位测量的。此属性提供有关图像颜色深度的关键信息，有助于处理和操作任务。 |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | 获取图像的边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Container](../../aspose.imaging/image/container/) { get; } | 获取 [`Image`](../../aspose.imaging/image/) 容器。 |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| override [FileFormat](../../aspose.imaging.fileformats.svg/svgimage/fileformat/) { get; } | 检索图像的文件格式，提供用于处理和兼容性检查的关键元数据。此属性对于确定在不同系统和应用中有效处理图像数据的适当解码和编码策略至关重要。 |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | 获取或设置指示图像是否具有背景颜色的值。 |
| override [Height](../../aspose.imaging/vectorimage/height/) { get; } | 获取图像高度。 |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf/) { get; } | 获取对象的高度（英寸）。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.imaging.fileformats.svg/svgimage/iscached/) { get; } | 检索一个布尔值，指示对象的数据当前是否已缓存，从而消除额外的数据读取操作的需求。此属性提供对当前缓存状态的洞察，优化数据检索和处理工作流，以提升性能和效率。 |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | 获取图像元数据。 |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | 获取或设置颜色调色板。当像素直接表示时，调色板不被使用。 |
| [Size](../../aspose.imaging/image/size/) { get; } | 获取图像尺寸。 |
| [SizeF](../../aspose.imaging/vectorimage/sizef/) { get; } | 获取对象的尺寸（英寸）。 |
| virtual [UsePalette](../../aspose.imaging/image/usepalette/) { get; } | 获取一个值，指示是否使用图像调色板。 |
| override [Width](../../aspose.imaging/vectorimage/width/) { get; } | 获取图像宽度。 |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf/) { get; } | 获取对象的宽度（英寸）。 |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | 获取或设置 Xmp 数据。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.svg/svgimage/cachedata/)() | 缓存数据并确保不再从底层[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer/)加载数据。此优化通过消除冗余的数据检索操作来提升性能，特别适用于需要频繁访问图像数据的场景。 |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为传入保存选项所表示的指定文件格式。 |
| override [Crop](../../aspose.imaging.fileformats.svg/svgimage/crop/#crop)(Rectangle) | 裁剪指定的矩形。 |
| virtual [Crop](../../aspose.imaging/image/crop/)(int, int, int, int) | 使用位移裁剪图像。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| override [GetDefaultOptions](../../aspose.imaging/vectorimage/getdefaultoptions/)(object[]) | 获取默认的图像选项。 |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages/)() | 获取嵌入的图像。 |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions/)() | 根据原始文件设置获取选项。这有助于保持原始图像的位深度和其他参数不变。例如，如果我们加载一幅每像素 1 位的黑白 PNG 图像，然后使用 [`Save`](../../aspose.imaging/datastreamsupporter/save/) 方法保存，输出的 PNG 图像将是每像素 8 位。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 [`Save`](../../aspose.imaging/image/save/) 方法。 |
| virtual [GetSerializedStream](../../aspose.imaging/image/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | 转换为 aps。 |
| virtual [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)() | 移除背景。 |
| virtual [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)(RemoveBackgroundSettings) | 移除背景。 |
| virtual [RemoveMetadata](../../aspose.imaging/image/removemetadata/)() | 移除元数据。 |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | 调整图像大小。默认使用 NearestNeighbourResample。 |
| override [Resize](../../aspose.imaging/vectorimage/resize/)(int, int, ImageResizeSettings) | 使用扩展选项调整图像大小。 |
| override [Resize](../../aspose.imaging.fileformats.svg/svgimage/resize/#resize_2)(int, int, ResizeType) | 调整图像大小以适应指定的尺寸，同时保持其纵横比。此方法提供了一种方便的方式来在不失真比例的情况下调整图像大小，确保根据所需尺寸实现最佳显示或存储。 |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | 按比例调整高度。默认使用 NearestNeighbourResample。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | 按比例调整宽度。使用默认的 NearestNeighbourResample。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ResizeType) | 按比例调整宽度。 |
| override [Rotate](../../aspose.imaging.fileformats.svg/svgimage/rotate/)(float) | 围绕中心旋转图像。 |
| override [RotateFlip](../../aspose.imaging/vectorimage/rotateflip/)(RotateFlipType) | 旋转、翻转或同时旋转和翻转图像。 |
| [Save](../../aspose.imaging/image/save/)() | 将图像数据保存到底层流。 |
| [Save](../../aspose.imaging/datastreamsupporter/save/)(Stream) | 将对象的数据保存到指定的流。 |
| override [Save](../../aspose.imaging/image/save/)(string) | 将图像保存到指定的文件位置。 |
| [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase) | 根据保存选项，将图像数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| virtual [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase, Rectangle) | 根据保存选项，将图像数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase, Rectangle) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| override [SetPalette](../../aspose.imaging.fileformats.svg/svgimage/setpalette/)(IColorPalette, bool) | 将指定的调色板应用于图像，实现对色彩方案的美观或功能性定制。此方法在管理色彩调色板以满足各种设计或应用需求方面提供了灵活性。 |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | 尝试设置 *metadata* 实例，前提是此 [`Image`](../../aspose.imaging/image/) 实例支持并实现了 [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) 类型。 |

## 示例

以下示例展示了如何将 svgz 图像转换为 svg 格式

```csharp
[C#]

string file = "example.svgz";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".svg";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.SvgOptions() {VectorRasterizationOptions = vectorRasterizationOptions});
}
```

以下示例展示了如何将 svg 图像转换为 svgz 格式

```csharp
[C#]

string file = "juanmontoya_lingerie.svg";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".svgz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.SvgOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
}
```

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

以下示例展示了如何将压缩图像（*.emz, *.wmz, *.svgz）转换为光栅格式

```csharp
[C#]

string[] files = new[] {"example.emz", "example.wmz", "example.svgz"};
string baseFolder = System.IO.Path.Combine("D:","Compressed");
foreach (var file in files)
{
    string inputFile = System.IO.Path.Combine(baseFolder, file);
    string outFile = inputFile + ".png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
    {
        Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Color.White, image.Width, image.Height });
        image.Save(outFile, new Aspose.Imaging.ImageOptions.PngOptions(){VectorRasterizationOptions = vectorRasterizationOptions});
    }
}
```

### 另请参见

* class [VectorImage](../../aspose.imaging/vectorimage/)
* namespace [Aspose.Imaging.FileFormats.Svg](../../aspose.imaging.fileformats.svg/)
* assembly [Aspose.Imaging](../../)


