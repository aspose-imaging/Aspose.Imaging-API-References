---
title: "类 WmfImage"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Wmf.WmfImage 类。使用我们的 API 无缝操作 Microsoft Windows Metafile WMF 图像，能够处理存储在可变长度记录中的矢量和位图数据。轻松调整大小、旋转和翻转图像，同时设置自定义图像调色板。将 WMF 文件转换为压缩的 WMZ 格式或保存为光栅图像格式，以实现跨平台和应用的多用途使用。"
type: docs
weight: 9460
url: /zh/net/aspose.imaging.fileformats.wmf/wmfimage/
---
## WmfImage class

使用我们的 API 操作 Microsoft Windows Metafile (WMF) 图像，能够无缝处理存储在可变长度记录中的矢量和位图数据。轻松调整大小、旋转和翻转图像，同时设置自定义图像调色板。将 WMF 文件转换为压缩的 WMZ 格式或保存为栅格图像格式，以实现跨平台和应用的多用途使用。

```csharp
public class WmfImage : MetaImage
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [WmfImage](wmfimage/#constructor)() | 创建 `WmfImage` 类的新实例，为进一步操作和处理 Windows Metafile (WMF) 图像数据进行初始化。此构造函数提供了一个用于处理 WMF 图像的基础对象，使 WMF 图像处理功能能够无缝集成到您的应用程序功能中。 |
| [WmfImage](wmfimage/#constructor_1)(int, int) | 实例化 `WmfImage` 类的新对象，并可自定义宽度和高度参数，以便创建符合特定尺寸的空白 WMF 图像。使用此构造函数动态生成具有精确尺寸的 WMF 图像，实现您应用程序中灵活的图像创建和操作。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | 获取或设置指示是否自动调整调色板的值。 |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | 获取或设置背景颜色的值。 |
| override [BitsPerPixel](../../aspose.imaging.fileformats.wmf/wmfimage/bitsperpixel/) { get; } | 检索图像的每像素位数计数，以指示颜色深度或粒度水平。利用此属性确定图像的颜色表示和精度，帮助在您的应用程序中进行兼容性检查和与颜色相关的处理。 |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | 获取图像的边界。 |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [Container](../../aspose.imaging/image/container/) { get; } | 获取 [`Image`](../../aspose.imaging/image/) 容器。 |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | 获取对象的数据流。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| override [FileFormat](../../aspose.imaging.fileformats.wmf/wmfimage/fileformat/) { get; } | 访问与图像关联的文件格式值，提供图像存储格式的信息。利用此属性可确定图像的文件格式，便于在您的应用程序中进行兼容性检查和特定格式的处理。 |
| [FrameBounds](../../aspose.imaging.fileformats.wmf/wmfimage/framebounds/) { get; } | 访问帧的边界，指示其在图像中的位置和尺寸。利用此属性获取帧空间位置的详细信息，以实现您应用程序中精确的操作和渲染。 |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | 获取或设置指示图像是否具有背景颜色的值。 |
| override [Height](../../aspose.imaging/vectorimage/height/) { get; } | 获取图像高度。 |
| override [HeightF](../../aspose.imaging.fileformats.wmf/wmfimage/heightf/) { get; } | 访问图像的高度，表示垂直轴上的像素数量。利用此属性确定图像的空间尺寸和宽高比，以便在您的应用程序中进行精确的布局和渲染调整。 |
| [Inch](../../aspose.imaging.fileformats.wmf/wmfimage/inch/) { get; set; } | 访问或修改 inch 属性，该属性表示通常用于在打印或显示环境中指定物理尺寸的度量单位。利用此属性设置或获取与图像关联的英寸值，以便在您的应用程序中准确表示物理尺寸。 |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | 获取或设置中断监视器。 |
| override [IsCached](../../aspose.imaging.fileformats.wmf/wmfimage/iscached/) { get; } | 检索一个布尔值，指示对象的数据是否已缓存，从而消除额外的数据读取操作。利用此属性通过判断对象的数据是否已随时可用来优化性能，避免在您的应用程序中进行昂贵的数据检索过程。 |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | 获取图像元数据。 |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | 获取或设置颜色调色板。当像素直接表示时，调色板不被使用。 |
| virtual [Records](../../aspose.imaging.fileformats.emf/metaimage/records/) { get; set; } | 获取或设置记录。 |
| [Size](../../aspose.imaging/image/size/) { get; } | 获取图像尺寸。 |
| [SizeF](../../aspose.imaging/vectorimage/sizef/) { get; } | 获取对象的尺寸（英寸）。 |
| virtual [UsePalette](../../aspose.imaging/image/usepalette/) { get; } | 获取一个值，指示是否使用图像调色板。 |
| override [Width](../../aspose.imaging/vectorimage/width/) { get; } | 获取图像宽度。 |
| override [WidthF](../../aspose.imaging.fileformats.wmf/wmfimage/widthf/) { get; } | 访问图像的宽度，指示水平轴上的像素数量。利用此属性确定图像的空间尺寸和宽高比，以便在您的应用程序中进行精确的布局和渲染调整。 |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | 获取或设置 Xmp 数据。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddRecord](../../aspose.imaging.fileformats.wmf/wmfimage/addrecord/)(WmfObject) | 将指定的记录对象合并到图像中，为其内容添加额外的数据或元数据。使用此方法可无缝将记录对象集成到图像中，促进您应用程序中全面的数据存储和组织。 |
| override [CacheData](../../aspose.imaging.fileformats.wmf/wmfimage/cachedata/)() | 高效缓存数据，消除从底层 [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) 进行额外加载的需求。使用此方法通过存储和访问本地数据缓存来优化性能并最小化您应用程序的资源使用。 |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | 确定图像是否可以保存为传入保存选项所表示的指定文件格式。 |
| override [Crop](../../aspose.imaging/vectorimage/crop/)(Rectangle) | 裁剪指定的矩形。 |
| virtual [Crop](../../aspose.imaging/image/crop/)(int, int, int, int) | 使用位移裁剪图像。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| override [GetDefaultOptions](../../aspose.imaging/vectorimage/getdefaultoptions/)(object[]) | 获取默认的图像选项。 |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages/)() | 获取嵌入的图像。 |
| [GetMissedFonts](../../aspose.imaging.fileformats.emf/metaimage/getmissedfonts/)() | 返回在元文件中使用但未找到的字体列表。 |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.wmf/wmfimage/getoriginaloptions/)() | 获取原始图像选项。 |
| [GetPostScript](../../aspose.imaging.fileformats.wmf/wmfimage/getpostscript/)() | 访问与图像关联的 PostScript 数据，提供其结构或内容的详细信息。使用此方法检索 PostScript 数据，以便在您的应用程序中进行进一步分析或处理，实现与 PostScript 渲染或操作相关的高级功能。 |
| virtual [GetSerializedStream](../../aspose.imaging/image/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | 转换为 aps。 |
| override [GetUsedFonts](../../aspose.imaging.fileformats.wmf/wmfimage/getusedfonts/)() | 检索元文件中使用的字体列表，提供对图像中使用的字体资源的洞察。使用此方法分析字体使用情况，并确保在您的应用程序中进行渲染或进一步处理时字体可用。 |
| virtual [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)() | 移除背景。 |
| virtual [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)(RemoveBackgroundSettings) | 移除背景。 |
| virtual [RemoveMetadata](../../aspose.imaging/image/removemetadata/)() | 移除元数据。 |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | 调整图像大小。默认使用 NearestNeighbourResample。 |
| override [Resize](../../aspose.imaging/vectorimage/resize/)(int, int, ImageResizeSettings) | 使用扩展选项调整图像大小。 |
| override [Resize](../../aspose.imaging/vectorimage/resize/)(int, int, ResizeType) | 调整指定的新宽度。 |
| override [ResizeCanvas](../../aspose.imaging.fileformats.wmf/wmfimage/resizecanvas/)(Rectangle) | 调整图像的画布大小，在保持图像内容的同时修改其尺寸。使用此方法在不改变内容的前提下更改画布大小，帮助您在应用程序中进行布局调整和构图更改。 |
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
| override [SetPalette](../../aspose.imaging.fileformats.wmf/wmfimage/setpalette/)(IColorPalette, bool) | 对图像应用指定的调色板，以实现颜色表示的自定义。使用此方法提升视觉渲染效果，并在您的应用程序中实现特定的颜色效果。 |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | 尝试设置 *metadata* 实例，前提是此 [`Image`](../../aspose.imaging/image/) 实例支持并实现了 [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) 类型。 |

## 示例

以下示例展示了如何将 wmz 图像转换为 wmf 格式。

```csharp
[C#]

string file = "example.wmz";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".wmf";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.WmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions});
}
```

以下示例展示了如何将 wmf 图像转换为 wmz 格式。

```csharp
[C#]

string file = "castle.wmf";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".wmz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.WmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
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

此示例展示了如何使用 WmfRasterizationOptions 从文件加载 WMF 图像并将其转换为 SVG。

```csharp
[C#]

string dir = "c:\\temp\\";

// 使用 Aspose.Imaging.Image.Load 是加载包括 WMF 在内的所有类型图像的统一方式。
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "test.wmf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();
        
    // 文本将被转换为形状。
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.WmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions();

    // 绘图表面的背景颜色。
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // 页面大小。
    rasterizationOptions.PageSize = wmfImage.Size;

    // 如果存在嵌入的 emf，则渲染 emf；否则渲染 wmf。
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Wmf.WmfRenderMode.Auto;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    wmfImage.Save(dir + "test.output.svg", saveOptions);
}
```

### 另请参见

* class [MetaImage](../../aspose.imaging.fileformats.emf/metaimage/)
* namespace [Aspose.Imaging.FileFormats.Wmf](../../aspose.imaging.fileformats.wmf/)
* assembly [Aspose.Imaging](../../)


