---
title: TiffOptions
second_title: Aspose.Imaging for .NET API 参考
description: tiff 文件格式选项 请注意宽度和高度标签将在创建图像时被宽度和高度参数覆盖因此无需直接指定它们 请注意许多选项返回默认值但这并不意味着此选项明确设置为标记值要验证标签是否存在请使用 Tags 属性或相应的 IsTagPresent 方法
type: docs
weight: 10220
url: /zh/net/aspose.imaging.imageoptions/tiffoptions/
---
## TiffOptions class

tiff 文件格式选项。 请注意，宽度和高度标签将在创建图像时被宽度和高度参数覆盖，因此无需直接指定它们。 请注意，许多选项返回默认值，但这并不意味着此选项明确设置为标记值。要验证标签是否存在，请使用 Tags 属性或相应的 IsTagPresent 方法。

```csharp
public class TiffOptions : ImageOptionsBase
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [TiffOptions](tiffoptions#constructor_2)(TiffDataType[]) | 初始化[`TiffOptions`](../tiffoptions)类. |
| [TiffOptions](tiffoptions#constructor)(TiffExpectedFormat) | 初始化[`TiffOptions`](../tiffoptions)班级。默认情况下使用小端约定。 |
| [TiffOptions](tiffoptions#constructor_3)(TiffOptions) | 初始化[`TiffOptions`](../tiffoptions)类. |
| [TiffOptions](tiffoptions#constructor_1)(TiffExpectedFormat, TiffByteOrder) | 初始化[`TiffOptions`](../tiffoptions)类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AlphaStorage](../../aspose.imaging.imageoptions/tiffoptions/alphastorage) { get; set; } | 获取或设置 alpha 存储选项。以外的选项Unspecified 多于 3 个时使用[`SamplesPerPixel`](./samplesperpixel)定义. |
| [Artist](../../aspose.imaging.imageoptions/tiffoptions/artist) { get; set; } | 获取或设置艺术家。 |
| [BitsPerPixel](../../aspose.imaging.imageoptions/tiffoptions/bitsperpixel) { get; } | 获取每个像素的位数。 |
| [BitsPerSample](../../aspose.imaging.imageoptions/tiffoptions/bitspersample) { get; set; } | 获取或设置每个样本的位数。 |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [ByteOrder](../../aspose.imaging.imageoptions/tiffoptions/byteorder) { get; set; } | 获取或设置一个表示tiff字节顺序的值。 |
| [ColorMap](../../aspose.imaging.imageoptions/tiffoptions/colormap) { get; set; } | 获取或设置颜色图。 |
| [CompressedQuality](../../aspose.imaging.imageoptions/tiffoptions/compressedquality) { get; set; } | 获取或设置压缩图像质量。 与 Jpeg 压缩一起使用。 |
| [Compression](../../aspose.imaging.imageoptions/tiffoptions/compression) { get; set; } | 获取或设置压缩。 |
| [Copyright](../../aspose.imaging.imageoptions/tiffoptions/copyright) { get; set; } | 获取或设置版权。 |
| [DateTime](../../aspose.imaging.imageoptions/tiffoptions/datetime) { get; set; } | 获取或设置日期和时间。 |
| [DisableIccExport](../../aspose.imaging.imageoptions/tiffoptions/disableiccexport) { get; set; } | 获取或设置一个值，该值指示是否禁用 ICC 配置文件导出（ICC 配置文件预先应用于源像素）。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | 获取一个值，该值指示此实例是否被释放。 |
| [DocumentName](../../aspose.imaging.imageoptions/tiffoptions/documentname) { get; set; } | 获取或设置文档的名称。 |
| [ExifIfd](../../aspose.imaging.imageoptions/tiffoptions/exififd) { get; } | 获取或设置指向 EXIF IFD 的指针。 |
| [ExtraSamples](../../aspose.imaging.imageoptions/tiffoptions/extrasamples) { get; } | 获取额外的样本值。 |
| [FaxT4Options](../../aspose.imaging.imageoptions/tiffoptions/faxt4options) { get; set; } | 获取或设置传真 t4 选项。 |
| [FileStandard](../../aspose.imaging.imageoptions/tiffoptions/filestandard) { get; set; } | 获取或设置 TIFF 文件标准。 |
| [FillOrder](../../aspose.imaging.imageoptions/tiffoptions/fillorder) { get; set; } | 获取或设置字节位填充顺序。 |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | 获取或设置一个值，指示是否[全帧]. |
| [HalfToneHints](../../aspose.imaging.imageoptions/tiffoptions/halftonehints) { get; set; } | 获取或设置半色调提示。 |
| [IccProfile](../../aspose.imaging.imageoptions/tiffoptions/iccprofile) { get; set; } | 获取或设置 Icc 配置文件流。 |
| [ImageDescription](../../aspose.imaging.imageoptions/tiffoptions/imagedescription) { get; set; } | 获取或设置图片描述。 |
| [ImageLength](../../aspose.imaging.imageoptions/tiffoptions/imagelength) { get; set; } | 获取或设置图像长度。 |
| [ImageWidth](../../aspose.imaging.imageoptions/tiffoptions/imagewidth) { get; set; } | 获取或设置图像宽度。 |
| [InkNames](../../aspose.imaging.imageoptions/tiffoptions/inknames) { get; set; } | 获取或设置墨迹名称。 |
| [IsExtraSamplesPresent](../../aspose.imaging.imageoptions/tiffoptions/isextrasamplespresent) { get; } | 获取指示是否存在额外样本的值。 |
| [IsTiled](../../aspose.imaging.imageoptions/tiffoptions/istiled) { get; } | 获取一个表示图像是否平铺的值。 |
| [IsValid](../../aspose.imaging.imageoptions/tiffoptions/isvalid) { get; } | 获取一个值，该值指示是否[`TiffOptions`](../tiffoptions)已正确配置。使用 Validate 方法查找失败原因。 |
| [MaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/maxsamplevalue) { get; set; } | 获取或设置最大样本值。 |
| [MinSampleValue](../../aspose.imaging.imageoptions/tiffoptions/minsamplevalue) { get; set; } | 获取或设置最小样本值。 |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | 多页选项 |
| [Orientation](../../aspose.imaging.imageoptions/tiffoptions/orientation) { get; set; } | 获取或设置方向。 |
| [PageName](../../aspose.imaging.imageoptions/tiffoptions/pagename) { get; set; } | 获取或设置页面名称。 |
| [PageNumber](../../aspose.imaging.imageoptions/tiffoptions/pagenumber) { get; set; } | 获取或设置页码标签。 |
| override [Palette](../../aspose.imaging.imageoptions/tiffoptions/palette) { get; set; } | 获取或设置调色板。 |
| [Photometric](../../aspose.imaging.imageoptions/tiffoptions/photometric) { get; set; } | 获取或设置光度。 |
| [PlanarConfiguration](../../aspose.imaging.imageoptions/tiffoptions/planarconfiguration) { get; set; } | 获取或设置平面配置。 |
| [Predictor](../../aspose.imaging.imageoptions/tiffoptions/predictor) { get; set; } | 获取或设置 LZW 压缩的预测器。 |
| [PremultiplyComponents](../../aspose.imaging.imageoptions/tiffoptions/premultiplycomponents) { get; set; } | 获取或设置一个值，该值指示是否必须对分量进行预乘。 |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | 获取或设置进度事件处理程序。 |
| override [ResolutionSettings](../../aspose.imaging.imageoptions/tiffoptions/resolutionsettings) { get; set; } | 获取或设置分辨率设置。 |
| [ResolutionUnit](../../aspose.imaging.imageoptions/tiffoptions/resolutionunit) { get; set; } | 获取或设置分辨率单位。 |
| [RowsPerStrip](../../aspose.imaging.imageoptions/tiffoptions/rowsperstrip) { get; set; } | 获取或设置每个条带的行数。 |
| [SampleFormat](../../aspose.imaging.imageoptions/tiffoptions/sampleformat) { get; set; } | 获取或设置样本格式。 |
| [SamplesPerPixel](../../aspose.imaging.imageoptions/tiffoptions/samplesperpixel) { get; } | 获取每个像素的样本。要更改此属性值，请使用[`BitsPerSample`](./bitspersample)属性设置器. |
| [ScannerManufacturer](../../aspose.imaging.imageoptions/tiffoptions/scannermanufacturer) { get; set; } | 获取或设置扫描仪制造商。 |
| [ScannerModel](../../aspose.imaging.imageoptions/tiffoptions/scannermodel) { get; set; } | 获取或设置扫描仪型号。 |
| [SmaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/smaxsamplevalue) { get; set; } | 获取或设置最大样本值。该值具有与样本数据最匹配的字段类型（字节、短或长类型）。 |
| [SminSampleValue](../../aspose.imaging.imageoptions/tiffoptions/sminsamplevalue) { get; set; } | 获取或设置最小样本值。该值具有与样本数据最匹配的字段类型（字节、短或长类型）。 |
| [SoftwareType](../../aspose.imaging.imageoptions/tiffoptions/softwaretype) { get; set; } | 获取或设置软件类型。 |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | 获取或设置要在其中创建图像的源。 |
| [StripByteCounts](../../aspose.imaging.imageoptions/tiffoptions/stripbytecounts) { get; set; } | 获取或设置条带字节数。 |
| [StripOffsets](../../aspose.imaging.imageoptions/tiffoptions/stripoffsets) { get; set; } | 获取或设置条带偏移量。 |
| [SubFileType](../../aspose.imaging.imageoptions/tiffoptions/subfiletype) { get; set; } | 获取或设置此子文件中包含的数据类型的一般指示。 |
| [Tags](../../aspose.imaging.imageoptions/tiffoptions/tags) { get; set; } | 获取或设置标签。 |
| [TargetPrinter](../../aspose.imaging.imageoptions/tiffoptions/targetprinter) { get; set; } | 获取或设置目标打印机。 |
| [Threshholding](../../aspose.imaging.imageoptions/tiffoptions/threshholding) { get; set; } | 获取或设置阈值。 |
| [TileByteCounts](../../aspose.imaging.imageoptions/tiffoptions/tilebytecounts) { get; set; } | 获取或设置图块字节数。 |
| [TileLength](../../aspose.imaging.imageoptions/tiffoptions/tilelength) { get; set; } | 获取 ot 设置图块长度。 |
| [TileOffsets](../../aspose.imaging.imageoptions/tiffoptions/tileoffsets) { get; set; } | 获取或设置瓦片偏移量。 |
| [TileWidth](../../aspose.imaging.imageoptions/tiffoptions/tilewidth) { get; set; } | 获取 ot 设置图块宽度。 |
| [TotalPages](../../aspose.imaging.imageoptions/tiffoptions/totalpages) { get; } | 获取总页数。 |
| [ValidTagCount](../../aspose.imaging.imageoptions/tiffoptions/validtagcount) { get; } | 获取有效标签计数。这不是标签总数，而是可以保留的标签数量。 |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | 获取或设置矢量光栅化选项。 |
| override [XmpData](../../aspose.imaging.imageoptions/tiffoptions/xmpdata) { get; set; } | 获取或设置 XMP 元数据容器。 |
| [XPAuthor](../../aspose.imaging.imageoptions/tiffoptions/xpauthor) { get; set; } | 获取或设置图片作者，供 Windows Explorer 使用。 |
| [XPComment](../../aspose.imaging.imageoptions/tiffoptions/xpcomment) { get; set; } | 获取或设置图像的注释，供 Windows 资源管理器使用。 |
| [XPKeywords](../../aspose.imaging.imageoptions/tiffoptions/xpkeywords) { get; set; } | 获取或设置主题图像，供 Windows Explorer 使用。 |
| [Xposition](../../aspose.imaging.imageoptions/tiffoptions/xposition) { get; set; } | 获取或设置 x 位置。 |
| [XPSubject](../../aspose.imaging.imageoptions/tiffoptions/xpsubject) { get; set; } | 获取或设置图像信息，供 Windows Explorer 使用。 |
| [XPTitle](../../aspose.imaging.imageoptions/tiffoptions/xptitle) { get; set; } | 获取或设置图像信息，供 Windows Explorer 使用。 |
| [Xresolution](../../aspose.imaging.imageoptions/tiffoptions/xresolution) { get; set; } | 获取或设置 x 分辨率。 |
| [YCbCrCoefficients](../../aspose.imaging.imageoptions/tiffoptions/ycbcrcoefficients) { get; set; } | 获取或设置 YCbCrCoefficients. |
| [YCbCrSubsampling](../../aspose.imaging.imageoptions/tiffoptions/ycbcrsubsampling) { get; set; } | 获取或设置 YCbCr 光度计的子采样因子。 |
| [Yposition](../../aspose.imaging.imageoptions/tiffoptions/yposition) { get; set; } | 获取或设置 y 位置。 |
| [Yresolution](../../aspose.imaging.imageoptions/tiffoptions/yresolution) { get; set; } | 获取或设置 y 分辨率。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddTag](../../aspose.imaging.imageoptions/tiffoptions/addtag)(TiffDataType) | 添加一个新标签。 |
| [AddTags](../../aspose.imaging.imageoptions/tiffoptions/addtags)(TiffDataType[]) | 添加标签。 |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | 克隆此实例。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | 处理当前实例。 |
| [GetTagByType](../../aspose.imaging.imageoptions/tiffoptions/gettagbytype)(TiffTags) | 按类型获取标签的实例。 |
| [IsTagPresent](../../aspose.imaging.imageoptions/tiffoptions/istagpresent)(TiffTags) | 确定选项中是否存在标签。 |
| [RemoveTag](../../aspose.imaging.imageoptions/tiffoptions/removetag)(TiffTags) | 删除标签。 |
| [Validate](../../aspose.imaging.imageoptions/tiffoptions/validate)() | 验证选项是否具有有效的标签组合 |
| static [GetValidTagsCount](../../aspose.imaging.imageoptions/tiffoptions/getvalidtagscount)(TiffDataType[]) | 获取有效标签计数。 |

### 例子

此示例演示了将 SaveOptions 命名空间中的不同类用于导出目的。将 Gif 类型的图像加载到 Image 的实例中，然后导出为多种格式。

```csharp
[C#]

string dir = "c:\\temp\\";

//在 Image 类的实例中加载现有图像（Gif 类型）
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    //使用默认选项导出为BMP文件格式
    image.Save(dir + "output.bmp", new Aspose.Imaging.ImageOptions.BmpOptions());

    //使用默认选项导出为JPEG文件格式
    image.Save(dir + "output.jpg", new Aspose.Imaging.ImageOptions.JpegOptions());

    //使用默认选项导出为PNG文件格式
    image.Save(dir + "output.png", new Aspose.Imaging.ImageOptions.PngOptions());

    //使用默认选项导出为 TIFF 文件格式
    image.Save(dir + "output.tif", new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

以下示例显示了如何在不引用特定图像类型的情况下以一般方式将多页矢量图像转换为 TIFF 格式。

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.tiff");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // 只导出前两页。这些页面将在输出 TIFF 中显示为帧。
    Aspose.Imaging.IMultipageImage multipageImage = image as Aspose.Imaging.IMultipageImage;
    if (multipageImage != null && (multipageImage.Pages != null && multipageImage.PageCount > 2))
    {
        exportOptions.MultiPageOptions = new Aspose.Imaging.ImageOptions.MultiPageOptions(new Aspose.Imaging.IntRange(0, 2));
    }

    if (image is Aspose.Imaging.VectorImage)
    {
        exportOptions.VectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Aspose.Imaging.Color.White, image.Width, image.Height });
        exportOptions.VectorRasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel;
        exportOptions.VectorRasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.None;
    }

    image.Save(outputFilePath, exportOptions);
}
```

此示例使用 GraphicsPath 和 Graphics 类在图像表面上创建和操作图形。示例在 GraphicsPath 类的帮助下创建一个新图像（Tiff 类型），清除表面并绘制路径。最后调用 Graphics 类公开的 DrawPath 方法来渲染表面上的路径。

```csharp
[C#]

//创建一个FileStream实例
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    //创建一个TiffOptions实例并设置它的各种属性
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    //设置ImageOptions实例的来源
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //创建一个Image实例 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        //创建并初始化一个Graphics类的实例
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //清除图形表面
        graphics.Clear(Color.Wheat);

        //创建GraphicsPath类的实例
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        //创建一个Figure类的实例
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        //将形状添加到图形对象
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        //将Figure对象添加到GraphicsPath
        graphicspath.AddFigure(figure);

        //使用颜色为黑色的 Pen 对象绘制路径
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // 保存所有更改。
        image.Save();
    }
}
```

### 也可以看看

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* 命名空间 [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
