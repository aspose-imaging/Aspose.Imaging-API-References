---
title: "WmfCompression"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "该 Compression 枚举指定位图图像的压缩类型"
type: docs
weight: 16
url: /zh/java/com.aspose.imaging.fileformats.wmf.consts/wmfcompression/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfCompression extends System.Enum
```

该 Compression 枚举指定位图图像的压缩类型
## 字段

| 字段 | 描述 |
| --- | --- |
| [BI_RGB](#BI-RGB) | 位图采用未压缩的红绿蓝 (RGB) 格式，不进行压缩且不使用颜色掩码。 |
| [BI_RLE8](#BI-RLE8) | 一种针对每像素 8 位的位图使用行程长度编码 (RLE) 压缩的 RGB 格式。 |
| [BI_RLE4](#BI-RLE4) | 一种针对每像素 4 位的位图使用 RLE 压缩的 RGB 格式。 |
| [BI_BITFIELDS](#BI-BITFIELDS) | 该位图未压缩，颜色表由三个 DWORD 颜色掩码组成，分别指定每个像素的红色、绿色和蓝色分量。 |
| [BI_JPEG](#BI-JPEG) | 该图像是 JPEG 图像，符合 [JFIF] 的规定。 |
| [BI_PNG](#BI-PNG) | 该图像是 PNG 图像，符合 [RFC2083] 的规定。 |
| [BI_CMYK](#BI-CMYK) | 该图像是未压缩的 CMYK 格式。 |
| [BI_CMYKRLE8](#BI-CMYKRLE8) | 一种对每像素 8 位的位图使用 RLE 压缩的 CMYK 格式。 |
| [BI_CMYKRLE4](#BI-CMYKRLE4) | 一种对每像素 4 位的位图使用 RLE 压缩的 CMYK 格式。 |
### BI_RGB {#BI-RGB}
```
public static final int BI_RGB
```


位图采用未压缩的红绿蓝 (RGB) 格式，不进行压缩且不使用颜色掩码。

### BI_RLE8 {#BI-RLE8}
```
public static final int BI_RLE8
```


一种对每像素 8 位的位图使用行程长度编码 (RLE) 压缩的 RGB 格式。该压缩采用 2 字节格式，由计数字节后跟包含颜色索引的字节组成。

### BI_RLE4 {#BI-RLE4}
```
public static final int BI_RLE4
```


一种对每像素 4 位的位图使用 RLE 压缩的 RGB 格式。该压缩采用 2 字节格式，由计数字节后跟两个字长的颜色索引组成。

### BI_BITFIELDS {#BI-BITFIELDS}
```
public static final int BI_BITFIELDS
```


该位图未压缩，颜色表由三个 DWORD 颜色掩码组成，分别指定每个像素的红色、绿色和蓝色分量。当用于每像素 16 位和 32 位的位图时此方式有效。

### BI_JPEG {#BI-JPEG}
```
public static final int BI_JPEG
```


该图像是 JPEG 图像，符合 [JFIF] 的规定。此值应仅在特定位图操作中使用，例如 JPEG 直通。应用程序必须查询直通支持，因为并非所有设备都支持 JPEG 直通。使用非 RGB 位图可能会限制元文件在其他设备上的可移植性。例如，显示设备上下文通常不支持此直通。

### BI_PNG {#BI-PNG}
```
public static final int BI_PNG
```


该图像是 PNG 图像，符合 [RFC2083] 的规定。此值应仅在特定位图操作中使用，例如 JPEG/PNG 直通。应用程序必须查询直通支持，因为并非所有设备都支持 JPEG/PNG 直通。使用非 RGB 位图可能会限制元文件在其他设备上的可移植性。例如，显示设备上下文通常不支持此直通。

### BI_CMYK {#BI-CMYK}
```
public static final int BI_CMYK
```


该图像是未压缩的 CMYK 格式。

### BI_CMYKRLE8 {#BI-CMYKRLE8}
```
public static final int BI_CMYKRLE8
```


一种对每像素 8 位的位图使用 RLE 压缩的 CMYK 格式。该压缩采用 2 字节格式，由计数字节后跟包含颜色索引的字节组成。

### BI_CMYKRLE4 {#BI-CMYKRLE4}
```
public static final int BI_CMYKRLE4
```


一种对每像素 4 位的位图使用 RLE 压缩的 CMYK 格式。该压缩采用 2 字节格式，由计数字节后跟两个字长的颜色索引组成。

