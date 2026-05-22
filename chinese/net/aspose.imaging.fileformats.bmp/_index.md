---
title: "Aspose.Imaging.FileFormats.Bmp"
second_title: "Aspose.Imaging for .NET API 参考"
description: "该命名空间处理 Bmp 文件格式"
type: docs
weight: 170
url: /zh/net/aspose.imaging.fileformats.bmp/
---
该命名空间处理 Bmp 文件格式。

## 类

| 类 | 描述 |
| --- | --- |
| [BitmapCoreHeader](./bitmapcoreheader/) | DIB 的尺寸和颜色格式。头部名称 BITMAPCOREHEADER，也称为 OS21XBITMAPHEADER。 |
| [BitmapInfoHeader](./bitmapinfoheader/) | 指定 BITMAPINFOHEADER。操作系统支持：Windows NT、3.1x 或更高版本。特性：添加了 16 位和 32 位每像素格式。添加了 RLE 压缩。 |
| [BitmapV4Header](./bitmapv4header/) | BitmapV4Header 结构是位图信息头文件。它是 BITMAPINFOHEADER 结构的扩展版本。BitmapV4Header 结构被扩展，以允许将 JPEG 或 PNG 图像作为源图像传递给 StretchDIBits。 |
| [BitmapV5Header](./bitmapv5header/) | BitmapV5Header 结构是位图信息头文件。它是 BITMAPINFOHEADER 结构的扩展版本。如果 bV5Height 为负，表示自上而下的 DIB，则 bV5Compression 必须是 BI_RGB 或 BI_BITFIELDS。自上而下的 DIB 不能被压缩。独立颜色管理接口 (ICM) 2.0 允许将国际色彩联盟 (ICC) 色彩配置文件链接或嵌入到 DIB 中（DIB）。有关更多信息，请参阅 Using Structures。当 DIB 加载到内存中时，若存在配置文件数据，应位于颜色表之后，bV5ProfileData 应提供配置文件数据相对于 BITMAPV5HEADER 结构起始位置的偏移量。存储在 bV5ProfileData 中的值将不同于对 BITMAPV5HEADER 参数使用 sizeof 运算符返回的值，因为 bV5ProfileData 是从 BITMAPV5HEADER 结构起始到配置文件数据起始的字节偏移。（位图位数据在内存中不跟随颜色表）。应用程序应在将 DIB 加载到内存后修改 bV5ProfileData 成员。对于打包的 DIB，配置文件数据应像文件格式一样位于位图位数据之后。bV5ProfileData 成员仍应给出配置文件数据相对于 BITMAPV5HEADER 起始的偏移量。只有当 bV5Size 等于 BITMAPV5HEADER 的大小且 bV5CSType 等于 PROFILE_EMBEDDED 或 PROFILE_LINKED 时，应用程序才应访问配置文件数据。 |
| [BmpImage](./bmpimage/) | 您可以轻松处理 Bitmap (BMP) 和 Device Independent Bitmap (DIB) 文件，从而高效地操作和处理光栅图像。通过对图像执行各种操作，此 API 简化了工作流程，为开发人员提供了在其软件应用中使用 BMP 和 DIB 格式的可靠工具包。 |
| [Os22XBitmapHeader](./os22xbitmapheader/) | OS/2 2.x OS22XBITMAPHEADER，也称为 BITMAPCOREHEADER2。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [BitmapCompression](./bitmapcompression/) | 指定不同的位图压缩方法。 |


