---
title: "类 WmfBitmapInfoHeader"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Wmf.Objects.WmfBitmapInfoHeader 类。BitmapInfoHeader 对象包含关于设备无关位图 DIB 的尺寸和颜色格式的信息"
type: docs
weight: 8650
url: /zh/net/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---
## WmfBitmapInfoHeader class

BitmapInfoHeader 对象包含关于设备无关位图（DIB）尺寸和颜色格式的信息。

```csharp
public class WmfBitmapInfoHeader : WmfBitmapBaseHeader
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [WmfBitmapInfoHeader](wmfbitmapinfoheader/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BitCount](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/bitcount/) { get; set; } | 获取或设置定义每个像素格式以及 DIB 中最大颜色数的 16 位无符号整数。此值必须位于 [`BitCount`](../wmfbitmapbaseheader/bitcount/) 枚举中（第 2.1.1.3 节）。 |
| [ColorImportant](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorimportant/) { get; set; } | 获取或设置一个 32 位无符号整数，定义显示 DIB 所需的颜色索引数量。如果此值为零，则需要所有颜色索引。 |
| [ColorUsed](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorused/) { get; set; } | 获取或设置一个 32 位无符号整数，指定 DIB 使用的颜色表中的索引数量，规则如下：如果此值为零，DIB 使用与 BitCount 值对应的最大颜色数。如果此值非零且 BitCount 值小于 16，则此值指定 DIB 使用的颜色数量。如果此值非零且 BitCount 值大于等于 16，则此值指定用于优化系统调色板性能的颜色表大小。注意：如果此值非零且大于基于 BitCount 值的颜色表最大可能大小，则应假定最大颜色表大小。 |
| [Compression](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/compression/) { get; set; } | 获取或设置一个 32 位无符号整数，定义 DIB 的压缩模式。此值必须位于 Compression 枚举（第 2.1.1.7 节）中。如果 DIB 是自上而下的位图（由 Height 值指示），此值不得指定压缩格式。 |
| [HeaderSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/headersize/) { get; set; } | 获取或设置定义此对象大小（以字节为单位）的 32 位无符号整数。 |
| [Height](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/height/) { get; set; } | 获取或设置 32 位有符号整数，定义 DIB 的高度（像素）。此值不得为零。如果此值为正，DIB 为自下而上的位图，原点位于左下角。如果此值为负，DIB 为自上而下的位图，原点位于左上角。自上而下的位图不支持压缩。如果 Compression 值指定 JPEG 或 PNG 格式，则此字段应指定解压缩后图像文件的高度。 |
| [ImageSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/imagesize/) { get; set; } | 获取或设置一个 32 位无符号整数，定义图像的大小（字节）。如果 Compression 值为 BI_RGB，则此值应为零并必须被忽略。如果 Compression 值为 BI_JPEG 或 BI_PNG，则此值必须分别指定 JPEG 或 PNG 图像缓冲区的大小。 |
| [Planes](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/planes/) { get; set; } | 获取或设置一个 16 位无符号整数，定义目标设备的平面数。此值必须为 0x0001。 |
| [Width](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/width/) { get; set; } | 获取或设置一个 32 位有符号整数，定义 DIB 的宽度（像素）。此值必须为正。如果 Compression 值指定 JPEG 或 PNG 格式，则此字段应指定解压缩后图像文件的宽度。 |
| [XPelsPerMeter](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/xpelspermeter/) { get; set; } | 获取或设置一个 32 位有符号整数，定义 DIB 目标设备的水平分辨率（像素每米）。 |
| [YPelsPerMeter](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/ypelspermeter/) { get; set; } | 获取或设置一个 32 位有符号整数，定义 DIB 目标设备的垂直分辨率（像素每米）。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [StructureSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/structuresize/) | 结构大小 |

### 另请参见

* class [WmfBitmapBaseHeader](../wmfbitmapbaseheader/)
* namespace [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects/)
* assembly [Aspose.Imaging](../../)


