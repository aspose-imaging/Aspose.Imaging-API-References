---
title: "类 DicomOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageOptions.DicomOptions 类。用于医学数字成像与通信（DICOM）光栅图像格式创建的 API 是为医疗设备应用量身定制的专用工具。它实现了 DICOM 图像的无缝生成，这对于存储医疗数据和包含重要标识信息至关重要。通过设置压缩、定义颜色类型并嵌入 XMP 元数据等功能，开发人员可以确保合规性并在管理医学成像的 DICOM 图像时具备灵活性。"
type: docs
weight: 10290
url: /zh/net/aspose.imaging.imageoptions/dicomoptions/
---
## DicomOptions class

Digital Imaging and Communications in Medicine（DICOM）栅格图像格式创建的 API 是为医疗设备应用量身定制的专业工具。它实现了 DICOM 图像的无缝生成，这对于存储医疗数据和包含关键识别信息至关重要。通过设置压缩、定义颜色类型以及嵌入 XMP 元数据等功能，开发者可以确保在管理用于医学成像的 DICOM 图像时的合规性和灵活性。

```csharp
public class DicomOptions : ImageOptionsBase
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DicomOptions](dicomoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [ColorType](../../aspose.imaging.imageoptions/dicomoptions/colortype/) { get; set; } | 获取或设置颜色的类型。 |
| [Compression](../../aspose.imaging.imageoptions/dicomoptions/compression/) { get; set; } | 获取或设置压缩。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
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

## 示例

更改 DICOM 压缩中的颜色类型。

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions { ColorType = ColorType.Grayscale8Bit };

    inputImage.Save("original_8Bit.dcm", options);
}
```

在 DICOM 图像中使用 RLE 压缩。

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression { Type = CompressionType.Rle }
    };

    inputImage.Save("original_RLE.dcm", options);
}
```

在 DICOM 图像中使用 JPEG 2000 压缩。

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression
        {
            Type = CompressionType.Jpeg2000,
            Jpeg2000 = new Jpeg2000Options
            {
                Codec = Jpeg2000Codec.Jp2,
                Irreversible = false
            }
        }
    };

    inputImage.Save("original_JPEG2000.dcm", options);
}
```

在 DICOM 图像中使用 JPEG 压缩。

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression
        {
            Type = CompressionType.Jpeg,
            Jpeg = new JpegOptions
            {
                CompressionType = JpegCompressionMode.Baseline,
                SampleRoundingMode = SampleRoundingMode.Truncate,
                Quality = 50
            }
        }
    };

    inputImage.Save("original_JPEG.dcm", options);
}
```

以下示例展示了导出为 DICOM 文件格式（单页和多页）。

```csharp
[C#]

string fileName = "sample.jpg";
string inputFileNameSingle = fileName;
string inputFileNameMultipage = "multipage.tif";
string outputFileNameSingleDcm = "output.dcm";
string outputFileNameMultipageDcm = "outputMultipage.dcm";

// 下面的代码示例将 JPEG 图像转换为 DICOM 文件格式
using (var image = Aspose.Imaging.Image.Load(inputFileNameSingle))
{
    image.Save(outputFileNameSingleDcm, new Aspose.Imaging.ImageOptions.DicomOptions());
}

// DICOM 格式支持多页图像。您可以像处理 JPEG 图像一样，将 GIF 或 TIFF 图像转换为 DICOM。
using (var imageMultiple = Aspose.Imaging.Image.Load(inputFileNameMultipage))
{
    imageMultiple.Save(outputFileNameMultipageDcm, new Aspose.Imaging.ImageOptions.DicomOptions());
}
```

创建多页 Dicom 图像。

```csharp
[C#]

using (DicomImage image = (DicomImage)Image.Create(
        new DicomOptions() { Source = new StreamSource(new MemoryStream()) },
        100,
        100))
{
    // 使用矢量图形绘制内容
    Graphics graphics = new Graphics(image);
    graphics.FillRectangle(new SolidBrush(Color.BlueViolet), image.Bounds);
    graphics.FillRectangle(new SolidBrush(Color.Aqua), 10, 20, 50, 20);
    graphics.FillEllipse(new SolidBrush(Color.Orange), 30, 50, 70, 30);

    // 保存绘制图像的像素。它们现在位于 Dicom 图像的第一页。
    int[] pixels = image.LoadArgb32Pixels(image.Bounds);

    // 在后面添加几页，使其更暗
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.AddPage();
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(i * 30);
    }

    // 在主页面前添加几页，使其更亮
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.InsertPage(0);
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(-i * 30);
    }

    // 将创建的多页图像保存到输出文件
    image.Save("MultiPage.dcm");
}
```

### 另请参见

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


