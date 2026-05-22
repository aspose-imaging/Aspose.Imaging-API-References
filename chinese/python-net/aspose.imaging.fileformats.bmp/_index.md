---
title: "aspose.imaging.fileformats.bmp"
type: docs
weight: 140
url: /zh/python-net/aspose.imaging.fileformats.bmp/
---


该模块处理 Bmp 文件格式。

## **Classes**
| **Class** | **描述** |
| :- | :- |
| [BitmapCoreHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcoreheader/) | DIB 的尺寸和颜色格式。<br/>            标头名称 BITMAPCOREHEADER，也称为 OS21XBITMAPHEADER。 |
| [BitmapInfoHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) | 指定 BITMAPINFOHEADER。 <br/>                操作系统支持：Windows NT、3.1x 或更高版本。<br/>                功能：添加 16 位和 32 位像素格式。添加 RLE 压缩。 |
| [BitmapV4Header](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapv4header/) | BitmapV4Header 结构是位图信息头文件。它是 BITMAPINFOHEADER 结构的扩展版本。<br/>            <br/>BitmapV4Header 结构已扩展，以允许将 JPEG 或 PNG 图像作为源图像传递给 StretchDIBits。<br/> |
| [BitmapV5Header](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapv5header/) | BitmapV5Header 结构是位图信息头文件。它是 BITMAPINFOHEADER 结构的扩展版本。<br/>            <br/>如果 bV5Height 为负，表示自上而下的 DIB，则 bV5Compression 必须是 BI_RGB 或 BI_BITFIELDS。自上而下的 DIB 不能被压缩。<br/>            独立颜色管理接口 (ICM) 2.0 允许将国际色彩联盟 (ICC) 色彩配置文件链接或嵌入到 DIB（DIB）中。<br/>            请参阅 Using Structures 获取更多信息。当 DIB 加载到内存时，若存在配置文件数据，应位于颜色表之后，<br/>            并且 bV5ProfileData 应提供从 BITMAPV5HEADER 结构起始处到配置文件数据的偏移量。<br/>            存储在 bV5ProfileData 中的值将不同于对 BITMAPV5HEADER 参数使用 sizeof 运算符返回的值，<br/>            因为 bV5ProfileData 是从 BITMAPV5HEADER 结构起始处到配置文件数据起始处的字节偏移量。<br/>            （位图位数据在内存中不跟随颜色表）。应用程序应在将 DIB 加载到内存后修改 bV5ProfileData 成员。<br/>            对于打包的 DIB，配置文件数据应像文件格式一样位于位图位之后。<br/>            bV5ProfileData 成员仍应给出从 BITMAPV5HEADER 起始处到配置文件数据的偏移量。<br/>            当 bV5Size 等于 BITMAPV5HEADER 的大小且 bV5CSType 等于 PROFILE_EMBEDDED 或 PROFILE_LINKED 时，应用程序才应访问配置文件数据。<br/> |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) | 您可以轻松处理位图（BMP）和设备无关位图<br/>            （DIB）文件，促进对栅格图像的高效操作和处理。对图像执行各种操作，此 API 简化了工作流，<br/>            为开发人员提供可靠的工具包，以在其软件应用中使用 BMP 和<br/>            DIB 格式。 |
| [Os22XBitmapHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/os22xbitmapheader/) | OS/2 2.x OS22XBITMAPHEADER，也称为 BITMAPCOREHEADER2。 |
## **Enumerations**
| **Enumeration** | **描述** |
| :- | :- |
| [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | 指定不同的位图压缩方法。 |
