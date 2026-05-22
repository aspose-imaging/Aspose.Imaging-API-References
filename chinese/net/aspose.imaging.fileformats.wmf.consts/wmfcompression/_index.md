---
title: "枚举 WmfCompression"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Wmf.Consts.WmfCompression 枚举。Compression 枚举指定位图图像的压缩类型。"
type: docs
weight: 8330
url: /zh/net/aspose.imaging.fileformats.wmf.consts/wmfcompression/
---
## WmfCompression enumeration

此 Compression 枚举指定位图图像的压缩类型

```csharp
public enum WmfCompression
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| BI_RGB | `0` | 该位图采用未压缩的红绿蓝 (RGB) 格式，不进行压缩且不使用颜色掩码。 |
| BI_RLE8 | `1` | 一种针对每像素 8 位的位图使用行程长度编码 (RLE) 压缩的 RGB 格式。压缩采用 2 字节格式，由计数字节后跟包含颜色索引的字节组成。 |
| BI_RLE4 | `2` | 一种针对每像素 4 位的位图使用 RLE 压缩的 RGB 格式。压缩采用 2 字节格式，由计数字节后跟两个字长的颜色索引组成。 |
| BI_BITFIELDS | `3` | 该位图未压缩，颜色表由三个 DWORD 颜色掩码组成，分别指定每个像素的红、绿、蓝分量。此方式在每像素 16 位和 32 位的位图中有效。 |
| BI_JPEG | `4` | 该图像是 JPEG 图像，符合 [JFIF] 的规定。此值应仅在某些位图操作中使用，例如 JPEG 直通。应用程序必须查询是否支持直通，因为并非所有设备都支持 JPEG 直通。使用非 RGB 位图可能会限制元文件在其他设备上的可移植性。例如，显示设备上下文通常不支持此直通。 |
| BI_PNG | `5` | 该图像是 PNG 图像，符合 [RFC2083] 的规定。此值应仅在某些位图操作中使用，例如 JPEG/PNG 直通。应用程序必须查询是否支持直通，因为并非所有设备都支持 JPEG/PNG 直通。使用非 RGB 位图可能会限制元文件在其他设备上的可移植性。例如，显示设备上下文通常不支持此直通。 |
| BI_CMYK | `11` | 该图像是未压缩的 CMYK 格式。 |
| BI_CMYKRLE8 | `12` | 一种针对每像素 8 位的位图使用 RLE 压缩的 CMYK 格式。压缩采用 2 字节格式，由计数字节后跟包含颜色索引的字节组成。 |
| BI_CMYKRLE4 | `13` | 一种针对每像素 4 位的位图使用 RLE 压缩的 CMYK 格式。压缩采用 2 字节格式，由计数字节后跟两个字长的颜色索引组成。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


