---
title: WmfLogColorSpaceW
second_title: Aspose.Imaging for .NET API 参考
description: LogColorSpaceW 对象指定一个逻辑颜色空间可以是 由名称由 Unicode 16 位组成的颜色配置文件定义 字符
type: docs
weight: 8760
url: /zh/net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/
---
## WmfLogColorSpaceW class

LogColorSpaceW 对象指定一个逻辑颜色空间，可以是 由名称由 Unicode 16 位组成的颜色配置文件定义 字符。

```csharp
public class WmfLogColorSpaceW : MetaObject
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [WmfLogColorSpaceW](wmflogcolorspacew)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ColorSpaceType](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/colorspacetype) { get; set; } | 获取或设置指定颜色空间 类型的 32 位有符号整数。它必须在 LogicalColorSpace 枚举 中定义（第 2.1.1.14 节）。如果此值为 LCS_sRGB 或 LCS_WINDOWS_COLOR_SPACE，则必须使用 sRGB 颜色空间。 |
| [Endpoints](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/endpoints) { get; set; } | 获取或设置定义 三种颜色的 CIE 色度 x、y 和 z 坐标的 CIEXYZTriple 对象（第 2.2.2.7 节） 对应于 RGBendpoints用于与位图。如果 [`ColorSpaceType`](./colorspacetype)字段未指定 LCS_CALIBRATED_RGB，则必须忽略此字段. |
| [Filename](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/filename) { get; set; } | 获取或设置一个可选的、以 null 结尾的 Unicode UTF16-LE 字符 字符串，它指定包含颜色的文件的名称 个人资料。如果指定了文件名，并且 [`ColorSpaceType`](./colorspacetype)字段设置为 LCS_CALIBRATED_RGB，则 这个结构的其他字段应该被忽略。 |
| [GammaBlue](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/gammablue) { get; set; } | 获取或设置一个 32 位定点值，该值定义了蓝色的色调 响应曲线。如果[`ColorSpaceType`](./colorspacetype)字段 未指定 LCS_CALIBRATED_RGB，则必须忽略此字段。 |
| [GammaGreen](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/gammagreen) { get; set; } | 获取或设置一个 32 位定点值，该值定义绿色的色调 响应曲线。如果[`ColorSpaceType`](./colorspacetype)字段 未指定 LCS_CALIBRATED_RGB，则必须忽略此字段。 |
| [GammaRed](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/gammared) { get; set; } | 获取或设置一个 32 位定点值，该值定义红色的色调 响应曲线。如果[`ColorSpaceType`](./colorspacetype)字段 未指定 LCS_CALIBRATED_RGB，则必须忽略此字段。 |
| [Intent](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/intent) { get; set; } | 获取或设置定义色域映射 意图的 32 位有符号整数。它必须在 GamutMappingIntent 枚举 中定义（第 2.1.1.11 节）。 |
| [Signature](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/signature) { get; set; } | 获取或设置指定 signature颜色空间对象；它必须设置为 值 0x50534F43，这是字符串 "PSOC" 的 ASCII 编码。 |
| [Size](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/size) { get; set; } | 获取或设置定义 size，以字节为单位。 |
| [Version](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/version) { get; set; } | 获取或设置定义 versionnumber;它必须是 0x00000400。 |

### 评论

参见[`WmfLogColorSpace`](../wmflogcolorspace)对象（第 2.2.2.11 节）用于 有关此 对象的字段值解释的其他详细信息。

### 也可以看看

* class [MetaObject](../../aspose.imaging.fileformats.emf/metaobject)
* 命名空间 [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->