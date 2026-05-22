---
title: "类 BigTiffOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.ImageOptions.BigTiffOptions 类。针对使用扫描仪的大规模成像数据的应用程序的独特需求，专门设计了用于创建 BigTIFF 栅格图像格式的 API。此 API 促进无缝生成将多个 TIFF 图像合并为单个综合图像的 BigTIFF 格式。它确保对大量图像数据的高效处理，为开发者提供创建和操作高分辨率多图像格式的强大工具。"
type: docs
weight: 10250
url: /zh/net/aspose.imaging.imageoptions/bigtiffoptions/
---
## BigTiffOptions class

BigTIFF 栅格图像格式创建的 API 专为满足使用扫描仪的大规模成像数据的应用程序的独特需求而设计。该 API 促进了 BigTIFF 格式的无缝生成，能够将多个 TIFF 图像合并为单个完整图像。它确保对海量图像数据的高效处理，为开发者提供了创建和操作高分辨率、多图像格式的强大工具。

```csharp
public sealed class BigTiffOptions : TiffOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [BigTiffOptions](bigtiffoptions/#constructor_2)(TiffDataType[]) | 初始化 `BigTiffOptions` 类的新实例。 |
| [BigTiffOptions](bigtiffoptions/#constructor)(TiffExpectedFormat) | 初始化 `BigTiffOptions` 类的新实例。默认使用小端字节序约定。 |
| [BigTiffOptions](bigtiffoptions/#constructor_3)(TiffOptions) | 初始化 `BigTiffOptions` 类的新实例。 |
| [BigTiffOptions](bigtiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | 初始化 `BigTiffOptions` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlphaStorage](../../aspose.imaging.imageoptions/tiffoptions/alphastorage/) { get; set; } | 获取或设置 alpha 存储选项。当定义的 [`SamplesPerPixel`](../tiffoptions/samplesperpixel/) 超过 3 时，使用除 Unspecified 之外的选项。 |
| [Artist](../../aspose.imaging.imageoptions/tiffoptions/artist/) { get; set; } | 获取或设置艺术家。 |
| [BitsPerPixel](../../aspose.imaging.imageoptions/tiffoptions/bitsperpixel/) { get; } | 获取每像素的位数。 |
| [BitsPerSample](../../aspose.imaging.imageoptions/tiffoptions/bitspersample/) { get; set; } | 获取或设置每个样本的位数。 |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| [ByteOrder](../../aspose.imaging.imageoptions/tiffoptions/byteorder/) { get; set; } | 获取或设置一个值，指示 TIFF 字节顺序。 |
| [ColorMap](../../aspose.imaging.imageoptions/tiffoptions/colormap/) { get; set; } | 获取或设置颜色映射表。 |
| [CompressedQuality](../../aspose.imaging.imageoptions/tiffoptions/compressedquality/) { get; set; } | 获取或设置压缩图像质量。与 JPEG 压缩一起使用。 |
| [Compression](../../aspose.imaging.imageoptions/tiffoptions/compression/) { get; set; } | 获取或设置压缩。 |
| [Copyright](../../aspose.imaging.imageoptions/tiffoptions/copyright/) { get; set; } | 获取或设置版权。 |
| [DateTime](../../aspose.imaging.imageoptions/tiffoptions/datetime/) { get; set; } | 获取或设置日期和时间。 |
| [DisableIccExport](../../aspose.imaging.imageoptions/tiffoptions/disableiccexport/) { get; set; } | 获取或设置一个值，指示是否禁用 ICC 配置文件导出（ICC 配置文件会预先应用于源像素）。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [DocumentName](../../aspose.imaging.imageoptions/tiffoptions/documentname/) { get; set; } | 获取或设置文档名称。 |
| override [ExifData](../../aspose.imaging.imageoptions/tiffoptions/exifdata/) { get; set; } | 获取或设置 Exif 数据。 |
| [ExifIfd](../../aspose.imaging.imageoptions/tiffoptions/exififd/) { get; } | 获取或设置指向 EXIF IFD 的指针。 |
| [ExtraSamples](../../aspose.imaging.imageoptions/tiffoptions/extrasamples/) { get; } | 获取额外样本值。 |
| [FaxT4Options](../../aspose.imaging.imageoptions/tiffoptions/faxt4options/) { get; set; } | 获取或设置传真 T4 选项。 |
| [FileStandard](../../aspose.imaging.imageoptions/tiffoptions/filestandard/) { get; set; } | 获取或设置 TIFF 文件标准。 |
| [FillOrder](../../aspose.imaging.imageoptions/tiffoptions/fillorder/) { get; set; } | 获取或设置字节位填充顺序。 |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | 获取或设置指示是否为 [full frame] 的值。 |
| [HalfToneHints](../../aspose.imaging.imageoptions/tiffoptions/halftonehints/) { get; set; } | 获取或设置半色调提示。 |
| [IccProfile](../../aspose.imaging.imageoptions/tiffoptions/iccprofile/) { get; set; } | 获取或设置 ICC 配置文件流。 |
| [ImageDescription](../../aspose.imaging.imageoptions/tiffoptions/imagedescription/) { get; set; } | 获取或设置图像描述。 |
| [ImageLength](../../aspose.imaging.imageoptions/tiffoptions/imagelength/) { get; set; } | 获取或设置图像长度。 |
| [ImageWidth](../../aspose.imaging.imageoptions/tiffoptions/imagewidth/) { get; set; } | 获取或设置图像宽度。 |
| [InkNames](../../aspose.imaging.imageoptions/tiffoptions/inknames/) { get; set; } | 获取或设置墨水名称。 |
| [IsExtraSamplesPresent](../../aspose.imaging.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | 获取一个值，指示是否存在额外样本。 |
| [IsTiled](../../aspose.imaging.imageoptions/tiffoptions/istiled/) { get; } | 获取一个指示图像是否已平铺的值。 |
| [IsValid](../../aspose.imaging.imageoptions/tiffoptions/isvalid/) { get; } | 获取一个指示[`TiffOptions`](../tiffoptions/)是否已正确配置的值。使用 Validate 方法来查找失败原因。 |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | 获取在导出时是否保留原始图像元数据的值。 |
| [MaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | 获取或设置最大样本值。 |
| [MinSampleValue](../../aspose.imaging.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | 获取或设置最小样本值。 |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | 多页选项 |
| [Orientation](../../aspose.imaging.imageoptions/tiffoptions/orientation/) { get; set; } | 获取或设置方向。 |
| [PageName](../../aspose.imaging.imageoptions/tiffoptions/pagename/) { get; set; } | 获取或设置页面名称。 |
| [PageNumber](../../aspose.imaging.imageoptions/tiffoptions/pagenumber/) { get; set; } | 获取或设置页码标签。 |
| override [Palette](../../aspose.imaging.imageoptions/tiffoptions/palette/) { get; set; } | 获取或设置颜色调色板。 |
| [Photometric](../../aspose.imaging.imageoptions/tiffoptions/photometric/) { get; set; } | 获取或设置光度。 |
| [PlanarConfiguration](../../aspose.imaging.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | 获取或设置平面配置。 |
| [Predictor](../../aspose.imaging.imageoptions/tiffoptions/predictor/) { get; set; } | 获取或设置 LZW 压缩的预测器。 |
| [PremultiplyComponents](../../aspose.imaging.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | 获取或设置一个指示组件是否必须预乘的值。 |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler/) { get; set; } | 获取或设置进度事件处理程序。 |
| override [ResolutionSettings](../../aspose.imaging.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | 获取或设置分辨率设置。 |
| [ResolutionUnit](../../aspose.imaging.imageoptions/tiffoptions/resolutionunit/) { get; set; } | 获取或设置分辨率单位。 |
| [RowsPerStrip](../../aspose.imaging.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | 获取或设置每条带的行数。 |
| [SampleFormat](../../aspose.imaging.imageoptions/tiffoptions/sampleformat/) { get; set; } | 获取或设置样本格式。 |
| [SamplesPerPixel](../../aspose.imaging.imageoptions/tiffoptions/samplesperpixel/) { get; } | 获取每像素的样本数。要更改此属性值，请使用 [`BitsPerSample`](../tiffoptions/bitspersample/) 属性设置器。 |
| [ScannerManufacturer](../../aspose.imaging.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | 获取或设置扫描仪制造商。 |
| [ScannerModel](../../aspose.imaging.imageoptions/tiffoptions/scannermodel/) { get; set; } | 获取或设置扫描仪型号。 |
| [SmaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | 获取或设置最大样本值。该值具有最匹配样本数据的字段类型（Byte、Short 或 Long 类型）。 |
| [SminSampleValue](../../aspose.imaging.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | 获取或设置最小样本值。该值具有最匹配样本数据的字段类型（Byte、Short 或 Long 类型）。 |
| [SoftwareType](../../aspose.imaging.imageoptions/tiffoptions/softwaretype/) { get; set; } | 获取或设置软件类型。 |
| [Source](../../aspose.imaging/imageoptionsbase/source/) { get; set; } | 获取或设置创建图像的来源。 |
| [StripByteCounts](../../aspose.imaging.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | 获取或设置条带字节计数。 |
| [StripOffsets](../../aspose.imaging.imageoptions/tiffoptions/stripoffsets/) { get; set; } | 获取或设置条带偏移。 |
| [SubFileType](../../aspose.imaging.imageoptions/tiffoptions/subfiletype/) { get; set; } | 获取或设置对该子文件中包含的数据类型的一般指示。 |
| [TagCount](../../aspose.imaging.imageoptions/tiffoptions/tagcount/) { get; } | 获取标签计数。 |
| [Tags](../../aspose.imaging.imageoptions/tiffoptions/tags/) { get; set; } | 获取或设置标签。 |
| [TargetPrinter](../../aspose.imaging.imageoptions/tiffoptions/targetprinter/) { get; set; } | 获取或设置目标打印机。 |
| [Threshholding](../../aspose.imaging.imageoptions/tiffoptions/threshholding/) { get; set; } | 获取或设置阈值化。 |
| [TileByteCounts](../../aspose.imaging.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | 获取或设置瓦片字节计数。 |
| [TileLength](../../aspose.imaging.imageoptions/tiffoptions/tilelength/) { get; set; } | 获取或设置瓦片长度。 |
| [TileOffsets](../../aspose.imaging.imageoptions/tiffoptions/tileoffsets/) { get; set; } | 获取或设置瓦片偏移量。 |
| [TileWidth](../../aspose.imaging.imageoptions/tiffoptions/tilewidth/) { get; set; } | 获取或设置瓦片宽度。 |
| [TotalPages](../../aspose.imaging.imageoptions/tiffoptions/totalpages/) { get; } | 获取总页数。 |
| [ValidTagCount](../../aspose.imaging.imageoptions/tiffoptions/validtagcount/) { get; } | 获取有效标签计数。这不是标签总数，而是可能被保留的标签数量。 |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 获取或设置矢量光栅化选项。 |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata/) { get; set; } | 获取或设置 XMP 元数据容器。 |
| [XPAuthor](../../aspose.imaging.imageoptions/tiffoptions/xpauthor/) { get; set; } | 获取或设置图像作者，此信息由 Windows Explorer 使用。 |
| [XPComment](../../aspose.imaging.imageoptions/tiffoptions/xpcomment/) { get; set; } | 获取或设置图像注释，此信息由 Windows Explorer 使用。 |
| [XPKeywords](../../aspose.imaging.imageoptions/tiffoptions/xpkeywords/) { get; set; } | 获取或设置图像主题，此信息由 Windows Explorer 使用。 |
| [Xposition](../../aspose.imaging.imageoptions/tiffoptions/xposition/) { get; set; } | 获取或设置 x 位置。 |
| [XPSubject](../../aspose.imaging.imageoptions/tiffoptions/xpsubject/) { get; set; } | 获取或设置信息关于图像，此信息由 Windows Explorer 使用。 |
| [XPTitle](../../aspose.imaging.imageoptions/tiffoptions/xptitle/) { get; set; } | 获取或设置信息关于图像，此信息由 Windows Explorer 使用。 |
| [Xresolution](../../aspose.imaging.imageoptions/tiffoptions/xresolution/) { get; set; } | 获取或设置 x 分辨率。 |
| [YCbCrCoefficients](../../aspose.imaging.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | 获取或设置 YCbCrCoefficients。 |
| [YCbCrSubsampling](../../aspose.imaging.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | 获取或设置 YCbCr 颜色空间的子采样因子。 |
| [Yposition](../../aspose.imaging.imageoptions/tiffoptions/yposition/) { get; set; } | 获取或设置 y 位置。 |
| [Yresolution](../../aspose.imaging.imageoptions/tiffoptions/yresolution/) { get; set; } | 获取或设置 y 分辨率。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddTag](../../aspose.imaging.imageoptions/tiffoptions/addtag/)(TiffDataType) | 添加新标签。 |
| [AddTags](../../aspose.imaging.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | 添加标签。 |
| override [Clone](../../aspose.imaging.imageoptions/bigtiffoptions/clone/)() | 克隆此实例。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| [GetTagByType](../../aspose.imaging.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | 按类型获取标签实例。 |
| [IsTagPresent](../../aspose.imaging.imageoptions/tiffoptions/istagpresent/)(TiffTags) | 确定标签是否存在于选项中。 |
| [RemoveTag](../../aspose.imaging.imageoptions/tiffoptions/removetag/)(TiffTags) | 移除标签。 |
| [RemoveTags](../../aspose.imaging.imageoptions/tiffoptions/removetags/)(params TiffTags[]) | 移除标签。 |
| [TrySetMetadata](../../aspose.imaging/imageoptionsbase/trysetmetadata/)(IImageMetadataFormat) | 尝试设置一个 *metadata* 实例，如果此 [`Image`](../../aspose.imaging/image/) 实例支持并实现了 [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) 实例。 |
| [Validate](../../aspose.imaging.imageoptions/tiffoptions/validate/)() | 验证选项是否具有有效的标签组合。 |

### 另请参见

* class [TiffOptions](../tiffoptions/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


