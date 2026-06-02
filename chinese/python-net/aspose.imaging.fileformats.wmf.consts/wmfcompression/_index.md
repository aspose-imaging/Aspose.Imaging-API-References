---
title: "WmfCompression 枚举"
type: docs
weight: 70
url: /zh/python-net/aspose.imaging.fileformats.wmf.consts/wmfcompression/
---

Compression 枚举指定位图图像的压缩类型。

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfCompression

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| BI_BITFIELDS | 位图未压缩，颜色表由三个 DWORD 颜色掩码组成，分别指定每个像素的红、绿、蓝分量。<br/>                当使用每像素 16 位或 32 位的位图时，此方式有效。 |
| BI_CMYK | 该图像为未压缩的 CMYK 格式。 |
| BI_CMYKRLE4 | 一种针对每像素 4 位位图使用 RLE 压缩的 CMYK 格式。<br/>                压缩采用 2 字节格式，由计数字节后跟两个字长颜色索引组成。 |
| BI_CMYKRLE8 | 一种针对每像素 8 位位图使用 RLE 压缩的 CMYK 格式。<br/>                压缩采用 2 字节格式，由计数字节后跟包含颜色索引的字节组成。 |
| BI_JPEG | 该图像为 JPEG 图像，符合 [JFIF] 的规定。此值仅应在某些位图<br/>                操作中使用，例如 JPEG 直通。应用程序必须查询是否支持直通，<br/>                因为并非所有设备都支持 JPEG 直通。使用非 RGB 位图可能会限制元文件在其他设备上的可移植性。<br/>                例如，显示设备上下文通常不支持此直通。 |
| BI_PNG | 该图像为 PNG 图像，符合 [RFC2083] 的规定。此值仅应在某些位图操作中使用，<br/>                例如 JPEG/PNG 直通。应用程序必须查询是否支持直通，因为并非所有设备<br/>                都支持 JPEG/PNG 直通。使用非 RGB 位图可能会限制元文件在其他设备上的可移植性。<br/>                例如，显示设备上下文通常不支持此直通。 |
| BI_RGB | 该位图采用未压缩的红绿蓝 (RGB) 格式，不进行压缩且不使用颜色掩码。 |
| BI_RLE4 | 一种 RGB 格式，对每像素 4 位的位图使用 RLE 压缩。<br/>                压缩使用 2 字节的格式，由计数字节后跟两个字长颜色索引组成 |
| BI_RLE8 | 一种 RGB 格式，对每像素 8 位的位图使用行程长度编码 (RLE) 压缩。<br/>                压缩使用 2 字节的格式，由计数字节后跟包含颜色索引的字节组成 |
