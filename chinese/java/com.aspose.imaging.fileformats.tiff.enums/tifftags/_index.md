---
title: "TiffTags"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "tiff 标记枚举。"
type: docs
weight: 25
url: /zh/java/com.aspose.imaging.fileformats.tiff.enums/tifftags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TiffTags extends System.Enum
```

tiff 标记枚举。
## 字段

| 字段 | 描述 |
| --- | --- |
| [SubFileType](#SubFileType) | 子文件数据描述符。 |
| [OsubfileType](#OsubfileType) | [已被 TIFF 版本淘汰。 |
| [ImageWidth](#ImageWidth) | 图像宽度（像素）。 |
| [ImageLength](#ImageLength) | 图像高度（像素）。 |
| [BitsPerSample](#BitsPerSample) | 每通道位数（样本）。 |
| [Compression](#Compression) | 数据压缩技术。 |
| [Photometric](#Photometric) | 光度解释。 |
| [Thresholding](#Thresholding) | [已被 TIFF 版本淘汰。 |
| [CellWidth](#CellWidth) | [已被 TIFF 版本淘汰。 |
| [CellLength](#CellLength) | [已被 TIFF 版本淘汰。 |
| [FillOrder](#FillOrder) | 字节内的数据顺序。 |
| [DocumentName](#DocumentName) | 保存图像的文档名称。 |
| [ImageDescription](#ImageDescription) | 关于图像的信息。 |
| [Make](#Make) | 扫描仪制造商名称。 |
| [Model](#Model) | 扫描仪型号名称/编号。 |
| [StripOffsets](#StripOffsets) | 数据条带的偏移量。 |
| [Orientation](#Orientation) | [已被 TIFF 版本淘汰。 |
| [SamplesPerPixel](#SamplesPerPixel) | 每像素样本数。 |
| [RowsPerStrip](#RowsPerStrip) | 每条数据的行数。 |
| [StripByteCounts](#StripByteCounts) | 条带的字节计数。 |
| [MinSampleValue](#MinSampleValue) | [已被 TIFF 版本淘汰。 |
| [MaxSampleValue](#MaxSampleValue) | [已被 TIFF 版本淘汰。 |
| [Xresolution](#Xresolution) | X 方向像素/分辨率。 |
| [Yresolution](#Yresolution) | Y 方向像素/分辨率。 |
| [PlanarConfig](#PlanarConfig) | 存储组织。 |
| [PageName](#PageName) | 图像来源的页面名称。 |
| [Xposition](#Xposition) | 图像左侧的 X 页面偏移。 |
| [Yposition](#Yposition) | 图像左侧的 Y 页面偏移。 |
| [FreeOffsets](#FreeOffsets) | [已被 TIFF 版本淘汰。 |
| [FreeByteCounts](#FreeByteCounts) | [已被 TIFF 版本淘汰。 |
| [GrayResponseUnit](#GrayResponseUnit) | [已被 TIFF 版本淘汰。 |
| [GrayResponseCurve](#GrayResponseCurve) | [已被 TIFF 版本淘汰。 |
| [T4Options](#T4Options) | TIFF 6.0 正式名称别名为 GROUP3OPTIONS。 |
| [T6Options](#T6Options) | CCITT 第四组传真编码的选项。 |
| [ResolutionUnit](#ResolutionUnit) | 分辨率的单位。 |
| [PageNumber](#PageNumber) | 多页的页面编号。 |
| [ColorResponseUnit](#ColorResponseUnit) | [已被 TIFF 版本淘汰。 |
| [TransferFunction](#TransferFunction) | 色度信息。 |
| [Software](#Software) | 名称和版本。 |
| [DateTime](#DateTime) | 创建日期和时间。 |
| [Artist](#Artist) | 图像创建者。 |
| [HostComputer](#HostComputer) | 创建所在的机器。 |
| [Predictor](#Predictor) | 使用 LZW 的预测方案。 |
| [WhitePoint](#WhitePoint) | 图像白点。 |
| [PrimaryChromaticities](#PrimaryChromaticities) | 主色度。 |
| [ColorMap](#ColorMap) | 调色板图像的 RGB 映射。 |
| [HalftoneHints](#HalftoneHints) | 高光和阴影信息。 |
| [TileWidth](#TileWidth) | 瓦片宽度（像素）。 |
| [TileLength](#TileLength) | 瓦片高度（像素）。 |
| [TileOffsets](#TileOffsets) | 数据瓦片的偏移量。 |
| [TileByteCounts](#TileByteCounts) | 瓦片的字节计数。 |
| [BadFaxLines](#BadFaxLines) | 像素计数错误的行。 |
| [CleanFaxData](#CleanFaxData) | 重新生成的行信息。 |
| [ConsecutiveBadFaxLines](#ConsecutiveBadFaxLines) | 最大连续错误行数。 |
| [SubIfd](#SubIfd) | 子图像描述符。 |
| [InkSet](#InkSet) | 分离图像中的墨水。 |
| [InkNames](#InkNames) | 墨水的 ASCII 名称。 |
| [NumberOfInks](#NumberOfInks) | 墨水数量。 |
| [DotRange](#DotRange) | 0% 和 100% 点代码。 |
| [TargetPrinter](#TargetPrinter) | 分离目标。 |
| [ExtraSamples](#ExtraSamples) | 关于额外样本的信息。 |
| [SampleFormat](#SampleFormat) | 数据样本格式。 |
| [SminSampleValue](#SminSampleValue) | 变量 MinSampleValue。 |
| [SmaxSampleValue](#SmaxSampleValue) | 变量 MaxSampleValue。 |
| [TransferRange](#TransferRange) | 变量 TransferRange |
| [ClipPath](#ClipPath) | ClipPath. |
| [Xclippathunits](#Xclippathunits) | XClipPathUnits. |
| [Yclippathunits](#Yclippathunits) | YClipPathUnits. |
| [Indexed](#Indexed) | 已索引。 |
| [JpegTables](#JpegTables) | JPEG 表流。 |
| [OpiProxy](#OpiProxy) | OPI 代理。 |
| [JpegProc](#JpegProc) | [已被技术说明 \#2 废弃，且该说明指定了修订后的 JPEG-in-TIFF 方案] JPEG 处理算法。 |
| [JpegInerchangeFormat](#JpegInerchangeFormat) | [已被技术说明 \#2 废弃，且该说明指定了修订后的 JPEG-in-TIFF 方案] 指向 SOI 标记。 |
| [JpegInterchangeFormatLength](#JpegInterchangeFormatLength) | [已被技术说明 \#2 废弃，且该说明指定了修订后的 JPEG-in-TIFF 方案] JFIF 流长度 |
| [JpegRestartInterval](#JpegRestartInterval) | [已被技术说明 \#2 废弃，且该说明指定了修订后的 JPEG-in-TIFF 方案] 重启间隔长度。 |
| [JpegLosslessPredictors](#JpegLosslessPredictors) | [已被技术说明 \#2 废弃，且该说明指定了修订后的 JPEG-in-TIFF 方案] 无损 proc 预测器。 |
| [JpegPointTransform](#JpegPointTransform) | [已被技术说明 \#2 废弃，且该说明指定了修订后的 JPEG-in-TIFF 方案] 无损点变换。 |
| [JpegQTables](#JpegQTables) | [已被技术说明 \#2 废弃，且该说明指定了修订后的 JPEG-in-TIFF 方案] Q 矩阵偏移。 |
| [JpegDCtables](#JpegDCtables) | [已被技术说明 \#2 废弃，且该说明指定了修订后的 JPEG-in-TIFF 方案] DCT 表偏移。 |
| [JpegACtables](#JpegACtables) | [已被技术说明 \#2 废弃，且该说明指定了修订后的 JPEG-in-TIFF 方案] AC 系数偏移。 |
| [YcbcrCoefficients](#YcbcrCoefficients) | RGB -> YCbCr 变换。 |
| [YcbcrSubSampling](#YcbcrSubSampling) | YCbCr 子采样因子。 |
| [YcbcrPositioning](#YcbcrPositioning) | 子采样定位。 |
| [ReferenceBlackWhite](#ReferenceBlackWhite) | 色度信息。 |
| [XmlPacket](#XmlPacket) | XML 包。 |
| [OpiImageid](#OpiImageid) | OPI ImageID。 |
| [Refpts](#Refpts) | 图像参考点。 |
| [Copyright](#Copyright) | 版权字符串。 |
| [PhotoshopResources](#PhotoshopResources) | Photoshop 图像资源。 |
| [IccProfile](#IccProfile) | 嵌入的 ICC 设备配置文件 |
| [ExifIfdPointer](#ExifIfdPointer) | 指向 Exif IFD 的指针。 |
| [XPTitle](#XPTitle) | 关于图像的信息，供 Windows Explorer 使用。 |
| [XPComment](#XPComment) | 关于图像的注释，供 Windows Explorer 使用。 |
| [XPAuthor](#XPAuthor) | 图像作者，供 Windows Explorer 使用。 |
| [XPKeywords](#XPKeywords) | 图像关键字，供 Windows Explorer 使用。 |
| [XPSubject](#XPSubject) | 图像主题，供 Windows Explorer 使用。 |
### SubFileType {#SubFileType}
```
public static final int SubFileType
```


子文件数据描述符。

### OsubfileType {#OsubfileType}
```
public static final int OsubfileType
```


[obsoleted by TIFF rev. 5.0] Kind of data in subfile.

### ImageWidth {#ImageWidth}
```
public static final int ImageWidth
```


图像宽度（像素）。

### ImageLength {#ImageLength}
```
public static final int ImageLength
```


图像高度（像素）。

### BitsPerSample {#BitsPerSample}
```
public static final int BitsPerSample
```


每通道位数（样本）。

### Compression {#Compression}
```
public static final int Compression
```


数据压缩技术。

### Photometric {#Photometric}
```
public static final int Photometric
```


光度解释。

### Thresholding {#Thresholding}
```
public static final int Thresholding
```


[obsoleted by TIFF rev. 5.0] Thresholding used on data.

### CellWidth {#CellWidth}
```
public static final int CellWidth
```


[obsoleted by TIFF rev. 5.0] Dithering matrix width.

### CellLength {#CellLength}
```
public static final int CellLength
```


[obsoleted by TIFF rev. 5.0] Dithering matrix height.

### FillOrder {#FillOrder}
```
public static final int FillOrder
```


字节内的数据顺序。

### DocumentName {#DocumentName}
```
public static final int DocumentName
```


保存图像的文档名称。

### ImageDescription {#ImageDescription}
```
public static final int ImageDescription
```


关于图像的信息。

### Make {#Make}
```
public static final int Make
```


扫描仪制造商名称。

### Model {#Model}
```
public static final int Model
```


扫描仪型号名称/编号。

### StripOffsets {#StripOffsets}
```
public static final int StripOffsets
```


数据条带的偏移量。

### Orientation {#Orientation}
```
public static final int Orientation
```


[obsoleted by TIFF rev. 5.0] Image orientation.

### SamplesPerPixel {#SamplesPerPixel}
```
public static final int SamplesPerPixel
```


每像素样本数。

### RowsPerStrip {#RowsPerStrip}
```
public static final int RowsPerStrip
```


每条数据的行数。

### StripByteCounts {#StripByteCounts}
```
public static final int StripByteCounts
```


条带的字节计数。

### MinSampleValue {#MinSampleValue}
```
public static final int MinSampleValue
```


[obsoleted by TIFF rev. 5.0] Minimum sample value.

### MaxSampleValue {#MaxSampleValue}
```
public static final int MaxSampleValue
```


[obsoleted by TIFF rev. 5.0] Maximum sample value.

### Xresolution {#Xresolution}
```
public static final int Xresolution
```


X 方向像素/分辨率。

### Yresolution {#Yresolution}
```
public static final int Yresolution
```


Y 方向像素/分辨率。

### PlanarConfig {#PlanarConfig}
```
public static final int PlanarConfig
```


存储组织。

### PageName {#PageName}
```
public static final int PageName
```


图像来源的页面名称。

### Xposition {#Xposition}
```
public static final int Xposition
```


图像左侧的 X 页面偏移。

### Yposition {#Yposition}
```
public static final int Yposition
```


图像左侧的 Y 页面偏移。

### FreeOffsets {#FreeOffsets}
```
public static final int FreeOffsets
```


[obsoleted by TIFF rev. 5.0] Byte offset to free block.

### FreeByteCounts {#FreeByteCounts}
```
public static final int FreeByteCounts
```


[obsoleted by TIFF rev. 5.0] Sizes of free blocks.

### GrayResponseUnit {#GrayResponseUnit}
```
public static final int GrayResponseUnit
```


[obsoleted by TIFF rev. 6.0] Gray scale curve accuracy.

### GrayResponseCurve {#GrayResponseCurve}
```
public static final int GrayResponseCurve
```


[obsoleted by TIFF rev. 6.0] Gray scale response curve.

### T4Options {#T4Options}
```
public static final int T4Options
```


TIFF 6.0 正式名称别名为 GROUP3OPTIONS。CCITT 第 3 组传真编码的选项。32 位标志位。

### T6Options {#T6Options}
```
public static final int T6Options
```


CCITT 第 4 组传真编码的选项。32 位标志位。TIFF 6.0 正式名称别名为 GROUP4OPTIONS。

### ResolutionUnit {#ResolutionUnit}
```
public static final int ResolutionUnit
```


分辨率的单位。

### PageNumber {#PageNumber}
```
public static final int PageNumber
```


多页的页面编号。

### ColorResponseUnit {#ColorResponseUnit}
```
public static final int ColorResponseUnit
```


[obsoleted by TIFF rev. 6.0] Color curve accuracy.

### TransferFunction {#TransferFunction}
```
public static final int TransferFunction
```


色度信息。

### Software {#Software}
```
public static final int Software
```


名称和版本。

### DateTime {#DateTime}
```
public static final int DateTime
```


创建日期和时间。

### Artist {#Artist}
```
public static final int Artist
```


图像创建者。

### HostComputer {#HostComputer}
```
public static final int HostComputer
```


创建所在的机器。

### Predictor {#Predictor}
```
public static final int Predictor
```


使用 LZW 的预测方案。

### WhitePoint {#WhitePoint}
```
public static final int WhitePoint
```


图像白点。

### PrimaryChromaticities {#PrimaryChromaticities}
```
public static final int PrimaryChromaticities
```


主色度。

### ColorMap {#ColorMap}
```
public static final int ColorMap
```


调色板图像的 RGB 映射。

### HalftoneHints {#HalftoneHints}
```
public static final int HalftoneHints
```


高光和阴影信息。

### TileWidth {#TileWidth}
```
public static final int TileWidth
```


瓦片宽度（像素）。

### TileLength {#TileLength}
```
public static final int TileLength
```


瓦片高度（像素）。

### TileOffsets {#TileOffsets}
```
public static final int TileOffsets
```


数据瓦片的偏移量。

### TileByteCounts {#TileByteCounts}
```
public static final int TileByteCounts
```


瓦片的字节计数。

### BadFaxLines {#BadFaxLines}
```
public static final int BadFaxLines
```


像素计数错误的行。

### CleanFaxData {#CleanFaxData}
```
public static final int CleanFaxData
```


重新生成的行信息。

### ConsecutiveBadFaxLines {#ConsecutiveBadFaxLines}
```
public static final int ConsecutiveBadFaxLines
```


最大连续错误行数。

### SubIfd {#SubIfd}
```
public static final int SubIfd
```


子图像描述符。

### InkSet {#InkSet}
```
public static final int InkSet
```


分离图像中的墨水。

### InkNames {#InkNames}
```
public static final int InkNames
```


墨水的 ASCII 名称。

### NumberOfInks {#NumberOfInks}
```
public static final int NumberOfInks
```


墨水数量。

### DotRange {#DotRange}
```
public static final int DotRange
```


0% 和 100% 点代码。

### TargetPrinter {#TargetPrinter}
```
public static final int TargetPrinter
```


分离目标。

### ExtraSamples {#ExtraSamples}
```
public static final int ExtraSamples
```


关于额外样本的信息。

### SampleFormat {#SampleFormat}
```
public static final int SampleFormat
```


数据样本格式。

### SminSampleValue {#SminSampleValue}
```
public static final int SminSampleValue
```


变量 MinSampleValue。

### SmaxSampleValue {#SmaxSampleValue}
```
public static final int SmaxSampleValue
```


变量 MaxSampleValue。

### TransferRange {#TransferRange}
```
public static final int TransferRange
```


变量 TransferRange

### ClipPath {#ClipPath}
```
public static final int ClipPath
```


ClipPath。由 Adobe TIFF 技术说明 2 在 TIFF 6.0 之后引入。

### Xclippathunits {#Xclippathunits}
```
public static final int Xclippathunits
```


XClipPathUnits。由 Adobe TIFF 技术说明 2 在 TIFF 6.0 之后引入。

### Yclippathunits {#Yclippathunits}
```
public static final int Yclippathunits
```


YClipPathUnits。由 Adobe TIFF 技术说明 2 在 TIFF 6.0 之后引入。

### Indexed {#Indexed}
```
public static final int Indexed
```


Indexed。由 Adobe TIFF 技术说明 3 在 TIFF 6.0 之后引入。

### JpegTables {#JpegTables}
```
public static final int JpegTables
```


JPEG 表流。于 TIFF 6.0 之后引入。

### OpiProxy {#OpiProxy}
```
public static final int OpiProxy
```


OPI Proxy。由 Adobe TIFF 技术说明在 TIFF 6.0 之后引入。

### JpegProc {#JpegProc}
```
public static final int JpegProc
```


[obsoleted by Technical Note \#2 which specifies a revised JPEG-in-TIFF scheme] JPEG processing algorithm.

### JpegInerchangeFormat {#JpegInerchangeFormat}
```
public static final int JpegInerchangeFormat
```


[obsoleted by Technical Note \#2 which specifies a revised JPEG-in-TIFF scheme] Pointer to SOI marker.

### JpegInterchangeFormatLength {#JpegInterchangeFormatLength}
```
public static final int JpegInterchangeFormatLength
```


[obsoleted by Technical Note \#2 which specifies a revised JPEG-in-TIFF scheme] JFIF stream length

### JpegRestartInterval {#JpegRestartInterval}
```
public static final int JpegRestartInterval
```


[obsoleted by Technical Note \#2 which specifies a revised JPEG-in-TIFF scheme] Restart interval length.

### JpegLosslessPredictors {#JpegLosslessPredictors}
```
public static final int JpegLosslessPredictors
```


[obsoleted by Technical Note \#2 which specifies a revised JPEG-in-TIFF scheme] Lossless proc predictor.

### JpegPointTransform {#JpegPointTransform}
```
public static final int JpegPointTransform
```


[obsoleted by Technical Note \#2 which specifies a revised JPEG-in-TIFF scheme] Lossless point transform.

### JpegQTables {#JpegQTables}
```
public static final int JpegQTables
```


[obsoleted by Technical Note \#2 which specifies a revised JPEG-in-TIFF scheme] Q matrice offsets.

### JpegDCtables {#JpegDCtables}
```
public static final int JpegDCtables
```


[obsoleted by Technical Note \#2 which specifies a revised JPEG-in-TIFF scheme] DCT table offsets.

### JpegACtables {#JpegACtables}
```
public static final int JpegACtables
```


[obsoleted by Technical Note \#2 which specifies a revised JPEG-in-TIFF scheme] AC coefficient offsets.

### YcbcrCoefficients {#YcbcrCoefficients}
```
public static final int YcbcrCoefficients
```


RGB -> YCbCr 变换。

### YcbcrSubSampling {#YcbcrSubSampling}
```
public static final int YcbcrSubSampling
```


YCbCr 子采样因子。

### YcbcrPositioning {#YcbcrPositioning}
```
public static final int YcbcrPositioning
```


子采样定位。

### ReferenceBlackWhite {#ReferenceBlackWhite}
```
public static final int ReferenceBlackWhite
```


色度信息。

### XmlPacket {#XmlPacket}
```
public static final int XmlPacket
```


XML 包。由 Adobe XMP 规范（2004 年 1 月）在 TIFF 6.0 之后引入。

### OpiImageid {#OpiImageid}
```
public static final int OpiImageid
```


OPI ImageID。由 Adobe TIFF 技术说明在 TIFF 6.0 之后引入。

### Refpts {#Refpts}
```
public static final int Refpts
```


图像参考点。已向 Island Graphics 注册的私有标签。

### Copyright {#Copyright}
```
public static final int Copyright
```


版权字符串。此标签在 TIFF 6.0 版中列出，所有权未知。

### PhotoshopResources {#PhotoshopResources}
```
public static final int PhotoshopResources
```


Photoshop 图像资源。

### IccProfile {#IccProfile}
```
public static final int IccProfile
```


嵌入的 ICC 设备配置文件

### ExifIfdPointer {#ExifIfdPointer}
```
public static final int ExifIfdPointer
```


指向 Exif IFD 的指针。

### XPTitle {#XPTitle}
```
public static final int XPTitle
```


关于图像的信息，供 Windows Explorer 使用。如果存在 [ImageDescription](../../com.aspose.imaging.fileformats.tiff.enums/tifftags\#ImageDescription) 标签，Windows Explorer 将忽略 `TiffTags.XPTitle`。

### XPComment {#XPComment}
```
public static final int XPComment
```


关于图像的注释，供 Windows Explorer 使用。

### XPAuthor {#XPAuthor}
```
public static final int XPAuthor
```


图像作者，供 Windows Explorer 使用。如果存在 [Artist](../../com.aspose.imaging.fileformats.tiff.enums/tifftags\#Artist) 标签，Windows Explorer 将忽略 `TiffTags.XPAuthor`。

### XPKeywords {#XPKeywords}
```
public static final int XPKeywords
```


图像关键字，供 Windows Explorer 使用。

### XPSubject {#XPSubject}
```
public static final int XPSubject
```


图像主题，供 Windows Explorer 使用。

