---
title: "类 BitmapV5Header"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Bmp.BitmapV5Header 类。BitmapV5Header 结构是位图信息头文件。它是 BITMAPINFOHEADER 结构的扩展版本。如果 bV5Height 为负，表示自上而下的 DIB，则 bV5Compression 必须是 BI_RGB 或 BI_BITFIELDS。自上而下的 DIB 不能被压缩。独立颜色管理接口 ICM 2.0 允许国际色彩联盟 ICC 色彩配置文件在 DIB 中被链接或嵌入。有关更多信息，请参阅 Using Structures。当 DIB 加载到内存时，如果存在配置文件数据，应紧随颜色表之后，bV5ProfileData 应提供配置文件数据相对于 BITMAPV5HEADER 结构起始位置的偏移。由于 bV5ProfileData 是从 BITMAPV5HEADER 结构起始处到配置文件数据开始的字节偏移，其存储的值将不同于对 BITMAPV5HEADER 参数使用 sizeof 运算符返回的值。位图位数据在内存中不跟随颜色表。应用程序应在将 DIB 加载到内存后修改 bV5ProfileData 成员。对于打包的 DIB，配置文件数据应像文件格式一样位于位图位之后。bV5ProfileData 成员仍应提供配置文件数据相对于 BITMAPV5HEADER 起始位置的偏移。仅当 bV5Size 等于 BITMAPV5HEADER 的大小且 bV5CSType 等于 PROFILE_EMBEDDED 或 PROFILE_LINKED 时，应用程序才应访问配置文件数据。"
type: docs
weight: 1420
url: /zh/net/aspose.imaging.fileformats.bmp/bitmapv5header/
---
## BitmapV5Header class

BitmapV5Header 结构是位图信息头文件。它是 BITMAPINFOHEADER 结构的扩展版本。如果 bV5Height 为负，表示自上而下的 DIB，则 bV5Compression 必须是 BI_RGB 或 BI_BITFIELDS。自上而下的 DIB 不能被压缩。独立颜色管理接口 (ICM) 2.0 允许将国际色彩联盟 (ICC) 色彩配置文件链接或嵌入到 DIB 中（DIB）。有关更多信息，请参阅 Using Structures。当 DIB 加载到内存中时，若存在配置文件数据，应位于颜色表之后，bV5ProfileData 应提供配置文件数据相对于 BITMAPV5HEADER 结构起始位置的偏移量。存储在 bV5ProfileData 中的值将不同于对 BITMAPV5HEADER 参数使用 sizeof 运算符返回的值，因为 bV5ProfileData 是从 BITMAPV5HEADER 结构起始到配置文件数据起始的字节偏移。（位图位数据在内存中不跟随颜色表）。应用程序应在将 DIB 加载到内存后修改 bV5ProfileData 成员。对于打包的 DIB，配置文件数据应像文件格式一样位于位图位数据之后。bV5ProfileData 成员仍应给出配置文件数据相对于 BITMAPV5HEADER 起始的偏移量。只有当 bV5Size 等于 BITMAPV5HEADER 的大小且 bV5CSType 等于 PROFILE_EMBEDDED 或 PROFILE_LINKED 时，应用程序才应访问配置文件数据。

```csharp
public class BitmapV5Header : BitmapV4Header
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlphaMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/alphamask/) { get; set; } | 获取或设置指定每个像素的 alpha 分量的颜色掩码。 |
| [BitmapColorsImportant](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsimportant/) { get; set; } | 获取或设置重要调色板颜色的数量。 |
| [BitmapColorsUsed](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsused/) { get; set; } | 获取或设置使用的调色板颜色数量。 |
| [BitmapCompression](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcompression/) { get; set; } | 获取或设置位图压缩方式。 |
| [BitmapHeight](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapheight/) { get; set; } | 获取或设置位图高度。 |
| [BitmapImageSize](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapimagesize/) { get; set; } | 获取或设置位图原始数据的字节大小。 |
| [BitmapPlanes](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapplanes/) { get; set; } | 获取或设置平面数量。 |
| [BitmapWidth](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapwidth/) { get; set; } | 获取或设置位图宽度。 |
| [BitmapXPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapxpelspermeter/) { get; set; } | 获取或设置水平像素分辨率。 |
| [BitmapYPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapypelspermeter/) { get; set; } | 获取或设置垂直像素分辨率。 |
| [BitsPerPixel](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitsperpixel/) { get; set; } | 获取或设置每像素位数。 |
| [BlueMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/bluemask/) { get; set; } | 获取或设置指定每个像素的蓝色分量的颜色掩码，仅在 bV4Compression 设置为 BI_BITFIELDS 时有效。 |
| [CSType](../../aspose.imaging.fileformats.bmp/bitmapv4header/cstype/) { get; set; } | 获取或设置 DIB 的颜色空间。 |
| [Endpoints](../../aspose.imaging.fileformats.bmp/bitmapv4header/endpoints/) { get; set; } | 获取或设置 CoordinatesTriple 类。 |
| [ExtraBitMasks](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/extrabitmasks/) { get; set; } | 获取或设置额外的位掩码。仅当 DIB 头为 BITMAPINFOHEADER 且 [`BitmapCompression`](../bitmapinfoheader/bitmapcompression/) 设置为 Bitfields (RGB) 或 AlphaBitfields (RGBA) 时存在。 |
| [GammaBlue](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammablue/) { get; set; } | 获取或设置蓝色伽马值。 |
| [GammaGreen](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammagreen/) { get; set; } | 获取或设置伽玛绿色。 |
| [GammaRed](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammared/) { get; set; } | 获取或设置伽玛红色。 |
| [GreenMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/greenmask/) { get; set; } | 获取或设置颜色掩码，该掩码指定每个像素的绿色分量，仅当 bV4Compression 设置为 BI_BITFIELDS 时有效。 |
| [HeaderSize](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/headersize/) { get; set; } | 获取或设置此结构的大小（字节）。 |
| [Intent](../../aspose.imaging.fileformats.bmp/bitmapv5header/intent/) { get; set; } | 获取或设置位图的渲染意图。 |
| [ProfileData](../../aspose.imaging.fileformats.bmp/bitmapv5header/profiledata/) { get; set; } | 获取或设置配置文件数据。 |
| [ProfileSize](../../aspose.imaging.fileformats.bmp/bitmapv5header/profilesize/) { get; set; } | 获取或设置配置文件的大小。 |
| [RedMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/redmask/) { get; set; } | 获取或设置颜色掩码，该掩码指定每个像素的红色分量，仅当 bV4Compression 设置为 BI_BITFIELDS 时有效。 |
| [Reserved](../../aspose.imaging.fileformats.bmp/bitmapv5header/reserved/) { get; set; } | 获取或设置保留成员。 |

### 另请参见

* class [BitmapV4Header](../bitmapv4header/)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../aspose.imaging.fileformats.bmp/)
* assembly [Aspose.Imaging](../../)


