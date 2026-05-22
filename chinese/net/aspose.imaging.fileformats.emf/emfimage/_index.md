---
title: "类 EmfImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfImage 类。增强型元文件格式（EMF）矢量图像格式支持的 API 是一个用于以设备无关方式处理图形图像并保持其原始属性的综合工具。该工具旨在保持比例、尺寸、颜色和其他图形属性，包含对 EMF Plus 格式的支持，并具备裁剪区域、调整画布和图像大小、旋转、翻转、设置图像调色板、导出和导入到 APS 设备上下文、压缩以及将 EMF 转换为其他格式的功能，确保对 EMF 图像的多样化操作和在各应用程序中的无缝集成。"
type: docs
weight: 4790
url: /zh/net/aspose.imaging.fileformats.emf/emfimage/
---
## EmfImage class

针对增强型元文件格式 (EMF) 矢量图像格式支持的 API 是一个全面的工具，用于以设备无关的方式处理图形图像，同时保留其原始属性。该工具旨在保持比例、尺寸、颜色及其他图形属性，包含对 EMF Plus 格式的支持，并提供裁剪区域、调整画布和图像大小、旋转、翻转、设置图像调色板、导出和导入到 APS 设备上下文、压缩以及将 EMF 转换为其他格式等功能，确保对 EMF 图像的多功能操作并实现无缝集成于各类应用中。

```csharp
public sealed class EmfImage : MetaImage
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfImage](emfimage/#constructor)() | 通过初始化 `EmfImage` 类的新实例开始使用 EMF 图像。非常适合轻松高效地将 EMF 图像快速集成到您的项目中。 |
| [EmfImage](emfimage/#constructor_1)(int, int) | 通过指定宽度和高度参数创建 `EmfImage` 类的新实例。此构造函数简化了使用特定尺寸初始化 EMF 图像的过程，提高了开发工作流的效率。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | 获取或设置指示是否自动调整调色板的值。 |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| override [BitsPerPixel](../../aspose.imaging.fileformats.emf/emfimage/bitsperpixel/) { get; } | 获取光栅图像特有的每像素位数，因为该参数不适用于矢量图像。快速确定光栅图像的像素深度，以便进行精确分析和操作，确保图像数据的准确处理。 |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | 获取图像的边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Container](../../aspose.imaging/image/container/) { get; } | 获取 [`Image`](../../aspose.imaging/image/) 容器。 |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| override [FileFormat](../../aspose.imaging.fileformats.emf/emfimage/fileformat/) { get; } | 访问与对象关联的文件格式值。轻松确定对象关联文件的格式，以实现流畅的处理和兼容性检查。通过轻松获取文件格式信息简化工作流。 |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | 获取或设置指示图像是否具有背景颜色的值。 |
| [Header](../../aspose.imaging.fileformats.emf/emfimage/header/) { get; set; } | 使用此属性检索或修改 EMF 元文件头记录。非常适合在应用程序中高效管理元文件数据。通过简化对元文件头信息的访问来提升工作流。 |
| override [Height](../../aspose.imaging/vectorimage/height/) { get; } | 获取图像高度。 |
| override [HeightF](../../aspose.imaging.fileformats.emf/emfimage/heightf/) { get; } | 检索图像的高度，以便实现精确渲染和布局调整。访问高度属性可确保在不同平台和应用之间的兼容性和无缝集成。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.imaging.fileformats.emf/emfimage/iscached/) { get; } | 访问一个指示对象数据当前是否已缓存的值，避免额外的数据读取。通过快速判断缓存数据是否可立即访问来提升效率。通过简化的数据检索过程优化工作流。 |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | 获取图像元数据。 |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | 获取或设置颜色调色板。当像素直接表示时，调色板不被使用。 |
| override [Records](../../aspose.imaging.fileformats.emf/emfimage/records/) { get; set; } | 检索或修改与对象关联的记录。高效访问和管理记录集合，以增强数据操作和处理。通过无缝交互对象的记录来优化工作流。 |
| [Size](../../aspose.imaging/image/size/) { get; } | 获取图像尺寸。 |
| [SizeF](../../aspose.imaging/vectorimage/sizef/) { get; } | 获取对象的尺寸（英寸）。 |
| virtual [UsePalette](../../aspose.imaging/image/usepalette/) { get; } | 获取一个值，指示是否使用图像调色板。 |
| override [Width](../../aspose.imaging/vectorimage/width/) { get; } | 获取图像宽度。 |
| override [WidthF](../../aspose.imaging.fileformats.emf/emfimage/widthf/) { get; } | 访问图像的宽度，提供精确渲染和处理所需的关键信息。快速检索图像宽度，以确保在各种应用程序和平台中的兼容性和正确布局。 |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | 获取或设置 Xmp 数据。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.emf/emfimage/cachedata/)() | 使用此方法高效缓存数据，防止从底层[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer/)重复加载。提升性能并简化应用程序中的数据访问，优化资源利用以提高响应速度。 |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为传入保存选项所表示的指定文件格式。 |
| override [Crop](../../aspose.imaging/vectorimage/crop/)(Rectangle) | 裁剪指定的矩形。 |
| virtual [Crop](../../aspose.imaging/image/crop/)(int, int, int, int) | 使用位移裁剪图像。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| override [GetDefaultOptions](../../aspose.imaging/vectorimage/getdefaultoptions/)(object[]) | 获取默认的图像选项。 |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages/)() | 获取嵌入的图像。 |
| [GetMissedFonts](../../aspose.imaging.fileformats.emf/metaimage/getmissedfonts/)() | 返回在元文件中使用但未找到的字体列表。 |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.emf/emfimage/getoriginaloptions/)() | 获取原始图像选项。 |
| virtual [GetSerializedStream](../../aspose.imaging/image/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | 转换为 aps。 |
| override [GetUsedFonts](../../aspose.imaging.fileformats.emf/emfimage/getusedfonts/)() | 使用此方法检索元文件中使用的字体列表。深入了解字体使用情况，帮助高效管理和优化字体资源，以提升渲染和显示的保真度。 |
| virtual [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)() | 移除背景。 |
| virtual [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)(RemoveBackgroundSettings) | 移除背景。 |
| virtual [RemoveMetadata](../../aspose.imaging/image/removemetadata/)() | 移除元数据。 |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | 调整图像大小。默认使用 NearestNeighbourResample。 |
| override [Resize](../../aspose.imaging/vectorimage/resize/)(int, int, ImageResizeSettings) | 使用扩展选项调整图像大小。 |
| override [Resize](../../aspose.imaging/vectorimage/resize/)(int, int, ResizeType) | 调整指定的新宽度。 |
| override [ResizeCanvas](../../aspose.imaging.fileformats.emf/emfimage/resizecanvas/)(Rectangle) | 使用此函数轻松调整画布大小。非常适合在不改变内容的情况下调整图像的整体尺寸。提升展示效果，并轻松为各种显示尺寸准备图像。 |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | 按比例调整高度。默认使用 NearestNeighbourResample。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | 按比例调整高度。 |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ResizeType) | 按比例调整高度。 |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | 按比例调整宽度。使用默认的 NearestNeighbourResample。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | 按比例调整宽度。 |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ResizeType) | 按比例调整宽度。 |
| override [Rotate](../../aspose.imaging/vectorimage/rotate/)(float) | 围绕中心旋转图像。 |
| override [RotateFlip](../../aspose.imaging/vectorimage/rotateflip/)(RotateFlipType) | 旋转、翻转或同时旋转和翻转图像。 |
| [Save](../../aspose.imaging/image/save/)() | 将图像数据保存到底层流。 |
| [Save](../../aspose.imaging/datastreamsupporter/save/)(Stream) | 将对象的数据保存到指定的流。 |
| override [Save](../../aspose.imaging/image/save/)(string) | 将图像保存到指定的文件位置。 |
| [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase) | 根据保存选项，将图像数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/)(string, bool) | 将对象的数据保存到指定的文件位置。 |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| virtual [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase, Rectangle) | 根据保存选项，将图像数据以指定的文件格式保存到指定的流中。 |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase, Rectangle) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| override [SetPalette](../../aspose.imaging.fileformats.emf/emfimage/setpalette/)(IColorPalette, bool) | 设置图像调色板。 |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | 尝试设置 *metadata* 实例，前提是此 [`Image`](../../aspose.imaging/image/) 实例支持并实现了 [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) 类型。 |

## 示例

以下示例展示了如何将 emz 图像转换为 emf 格式

```csharp
[C#]

string file = "example.emz";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".emf";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions {PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.EmfOptions {VectorRasterizationOptions = vectorRasterizationOptions});
}
```

以下示例展示了如何将 emf 图像转换为 emz 格式

```csharp
[C#]

string file = "input.emf";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".emz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.EmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
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

此示例展示了如何使用 EmfRasterizationOptions 从文件加载 EMF 图像并将其转换为 SVG。

```csharp
[C#]

string dir = "c:\\temp\\";

// 使用 Aspose.Imaging.Image.Load 是加载包括 EMF 在内的所有类型图像的统一方式。
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();

    // 文本将被转换为形状。
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.EmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions();

    // 绘图表面的背景颜色。
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // 页面大小。
    rasterizationOptions.PageSize = emfImage.Size;

    // 如果存在嵌入的 emf，则渲染 emf；否则渲染 wmf。
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Emf.EmfRenderMode.Auto;

    // 设置水平边距
    rasterizationOptions.BorderX = 50;

    // 设置垂直边距
    rasterizationOptions.BorderY = 50;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    emfImage.Save(dir + "test.output.svg", saveOptions);
}
```

### 另请参见

* class [MetaImage](../metaimage/)
* namespace [Aspose.Imaging.FileFormats.Emf](../../aspose.imaging.fileformats.emf/)
* assembly [Aspose.Imaging](../../)


