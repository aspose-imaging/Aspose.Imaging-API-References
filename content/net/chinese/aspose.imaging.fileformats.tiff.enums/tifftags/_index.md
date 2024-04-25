---
title: TiffTags
second_title: Aspose.Imaging for .NET API 参考
description: tiff 标签枚举
type: docs
weight: 7740
url: /zh/aspose.imaging.fileformats.tiff.enums/tifftags/
---
## TiffTags enumeration

tiff 标签枚举。

```csharp
public enum TiffTags
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| SubFileType | `254` | 子文件数据描述符。 |
| OsubfileType | `255` | [已被 TIFF 修订版淘汰。 5.0] 子文件中的数据种类。 |
| ImageWidth | `256` | 以像素为单位的图像宽度。 |
| ImageLength | `257` | 图像高度（以像素为单位）。 |
| BitsPerSample | `258` | 每通道位数（样本）。 |
| Compression | `259` | 数据压缩技术. |
| Photometric | `262` | 光度解释。 |
| Thresholding | `263` | [已被 TIFF 修订版淘汰。 5.0] 对数据使用的阈值。 |
| CellWidth | `264` | [已被 TIFF 修订版淘汰。 5.0] 抖动矩阵宽度。 |
| CellLength | `265` | [已被 TIFF 修订版淘汰。 5.0] 抖动矩阵高度。 |
| FillOrder | `266` | 一个字节内的数据顺序。 |
| DocumentName | `269` | 为图像保存的文档的名称。 |
| ImageDescription | `270` | 有关图像的信息。 |
| Make | `271` | 扫描仪制造商名称。 |
| Model | `272` | 扫描仪型号名称/编号。 |
| StripOffsets | `273` | 数据条的偏移量。 |
| Orientation | `274` | [已被 TIFF 修订版淘汰。 5.0] 图像方向。 |
| SamplesPerPixel | `277` | 每个像素的样本数。 |
| RowsPerStrip | `278` | 每条数据的行数。 |
| StripByteCounts | `279` | 条带的字节数。 |
| MinSampleValue | `280` | [已被 TIFF 修订版淘汰。 5.0] 最小样本值。 |
| MaxSampleValue | `281` | [已被 TIFF 修订版淘汰。 5.0] 最大样本值。 |
| Xresolution | `282` | x. 中的像素/分辨率 |
| Yresolution | `283` | y. 中的像素/分辨率 |
| PlanarConfig | `284` | 存储组织。 |
| PageName | `285` | 页面名称图片来自. |
| Xposition | `286` | 图像 lhs 的 X 页偏移量。 |
| Yposition | `287` | 图像 lhs 的 Y 页偏移量。 |
| FreeOffsets | `288` | [已被 TIFF 修订版淘汰。 5.0] 到空闲块的字节偏移量。 |
| FreeByteCounts | `289` | [已被 TIFF 修订版淘汰。 5.0] 空闲块的大小。 |
| GrayResponseUnit | `290` | [已被 TIFF 修订版淘汰。 6.0] 灰度曲线精度。 |
| GrayResponseCurve | `291` | [已被 TIFF 修订版淘汰。 6.0] 灰度响应曲线。 |
| T4Options | `292` | GROUP3OPTIONS 的 TIFF 6.0 专有名称别名。 CCITT Group 3 传真编码的选项。 32 个标志位。 |
| T6Options | `293` | CCITT Group 4 传真编码选项。 32 个标志位。 GROUP4OPTIONS 的 TIFF 6.0 专有名称别名。 |
| ResolutionUnit | `296` | 分辨率单位。 |
| PageNumber | `297` | 多页的页码。 |
| ColorResponseUnit | `300` | [已被 TIFF 修订版淘汰。 6.0] 颜色曲线精度。 |
| TransferFunction | `301` | 比色法信息。 |
| Software | `305` | 名称和版本。 |
| DateTime | `306` | 创建日期和时间。 |
| Artist | `315` | 图像的创建者。 |
| HostComputer | `316` | 创建机器的位置。 |
| Predictor | `317` | 预测方案 w/ LZW. |
| WhitePoint | `318` | 图像白点。 |
| PrimaryChromaticities | `319` | 原色度。 |
| ColorMap | `320` | 调色板图像的 RGB 映射。 |
| HalftoneHints | `321` | 高光 + 阴影信息。 |
| TileWidth | `322` | 平铺宽度（以像素为单位）。 |
| TileLength | `323` | 平铺高度（以像素为单位）。 |
| TileOffsets | `324` | 数据切片的偏移量。 |
| TileByteCounts | `325` | 切片的字节数。 |
| BadFaxLines | `326` | 像素数错误的行。 |
| CleanFaxData | `327` | 重新生成的线路信息。 |
| ConsecutiveBadFaxLines | `328` | 最大连续坏行数。 |
| SubIfd | `330` | 子图像描述符。 |
| InkSet | `332` | 分离图像中的墨水。 |
| InkNames | `333` | 墨水的 ASCII 名称。 |
| NumberOfInks | `334` | 墨水数。 |
| DotRange | `336` | 0% 和 100% 点码。 |
| TargetPrinter | `337` | 分离目标。 |
| ExtraSamples | `338` | 有关额外样本的信息。 |
| SampleFormat | `339` | 数据样本格式. |
| SminSampleValue | `340` | 变量 MinSampleValue. |
| SmaxSampleValue | `341` | 变量 MaxSampleValue. |
| TransferRange | `342` | 变量 TransferRange |
| ClipPath | `343` | 剪辑路径。 Adobe TIFF 技术说明 2. 在 TIFF rev 6.0 后引入 |
| Xclippathunits | `344` | XClipPathUnits。 Adobe TIFF 技术说明 2. 在 TIFF rev 6.0 后引入 |
| Yclippathunits | `345` | YClipPathUnits。 Adobe TIFF 技术说明 2. 在 TIFF rev 6.0 后引入 |
| Indexed | `346` | 已编入索引。 Adobe TIFF Technote 3. 在 TIFF rev 6.0 后引入 |
| JpegTables | `347` | JPEG 表流。在 TIFF rev 6.0. 后引入 |
| OpiProxy | `351` | OPI 代理。 Adobe TIFF technote. 在 TIFF rev 6.0 后引入 |
| JpegProc | `512` | [被技术说明 #2 废弃，它指定了一个修订的 JPEG-in-TIFF 方案] JPEG处理算法。 |
| JpegInerchangeFormat | `513` | [被技术说明 #2 废弃，它指定了一个修订的 JPEG-in-TIFF 方案] 指向 SOI 标记的指针。 |
| JpegInterchangeFormatLength | `514` | [被技术说明 #2 废弃，它指定了一个修订的 JPEG-in-TIFF 方案] JFIF 流长度 |
| JpegRestartInterval | `515` | [被技术说明 #2 废弃，它指定了一个修订的 JPEG-in-TIFF 方案] 重启间隔长度。 |
| JpegLosslessPredictors | `517` | [被技术说明 #2 废弃，它指定了一个修订的 JPEG-in-TIFF 方案] 无损过程预测器。 |
| JpegPointTransform | `518` | [被技术说明 #2 废弃，它指定了一个修订的 JPEG-in-TIFF 方案] 无损点变换。 |
| JpegQTables | `519` | [被技术说明 #2 废弃，它指定了一个修订的 JPEG-in-TIFF 方案] Q 矩阵偏移量。 |
| JpegDCtables | `520` | [被技术说明 #2 废弃，它指定了一个修订的 JPEG-in-TIFF 方案] DCT 表偏移量。 |
| JpegACtables | `521` | [被技术说明 #2 废弃，它指定了一个修订的 JPEG-in-TIFF 方案] 交流系数偏移量。 |
| YcbcrCoefficients | `529` | RGB -&gt; YCbCr 变换。 |
| YcbcrSubSampling | `530` | YCbCr 子采样因子。 |
| YcbcrPositioning | `531` | 子样本定位。 |
| ReferenceBlackWhite | `532` | 比色法信息。 |
| XmlPacket | `700` | XML 数据包。 Adobe XMP 规范于 2004 年 1 月在 TIFF rev 6.0 后引入。 |
| OpiImageid | `32781` | OPI 图像 ID。 Adobe TIFF technote. 在 TIFF rev 6.0 后引入 |
| Refpts | `32953` | 图像参考点。注册到 Island Graphics. 的私有标签 |
| Copyright | `33432` | 版权字符串。此标签在 TIFF rev 中列出。 6.0 w/未知所有权. |
| PhotoshopResources | `34377` | Photoshop 图像资源。 |
| IccProfile | `34675` | 嵌入式 ICC 设备配置文件 |
| ExifIfdPointer | `34665` | 指向 Exif IFD 的指针。 |
| XPTitle | `40091` | 有关图像的信息，供 Windows 资源管理器使用。 XPTitle如果ImageDescription标签存在。 |
| XPComment | `40092` | 对图像的评论，由 Windows 资源管理器使用。 |
| XPAuthor | `40093` | 图像作者，由 Windows 资源管理器使用。 XPAuthor如果Artist标签存在。 |
| XPKeywords | `40094` | 图像关键字，由 Windows 资源管理器使用。 |
| XPSubject | `40095` | 主题图像，由 Windows 资源管理器使用。 |

### 也可以看看

* 命名空间 [Aspose.Imaging.FileFormats.Tiff.Enums](../../aspose.imaging.fileformats.tiff.enums)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
