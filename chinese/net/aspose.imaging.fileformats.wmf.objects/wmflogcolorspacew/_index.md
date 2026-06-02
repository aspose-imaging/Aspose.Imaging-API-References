---
title: "类 WmfLogColorSpaceW"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Wmf.Objects.WmfLogColorSpaceW 类。LogColorSpaceW 对象指定一个逻辑颜色空间，可通过名称由 Unicode 16 位字符组成的颜色配置文件来定义。"
type: docs
weight: 8940
url: /zh/net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/
---
## WmfLogColorSpaceW class

该 LogColorSpaceW 对象指定逻辑颜色空间，可以通过名称由 Unicode 16 位字符组成的颜色配置文件来定义。

```csharp
public class WmfLogColorSpaceW : MetaObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [WmfLogColorSpaceW](wmflogcolorspacew/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ColorSpaceType](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/colorspacetype/) { get; set; } | 获取或设置一个 32 位有符号整数，指定颜色空间类型。它必须在 LogicalColorSpace 枚举（第 2.1.1.14 节）中定义。如果该值为 LCS_sRGB 或 LCS_WINDOWS_COLOR_SPACE，则必须使用 sRGB 颜色空间。 |
| [Endpoints](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/endpoints/) { get; set; } | 获取或设置一个 CIEXYZTriple 对象（第 2.2.2.7 节），该对象定义了与位图关联的逻辑颜色空间的 RGB 端点对应的三种颜色的 CIE 色度 x、y、z 坐标。如果 [`ColorSpaceType`](./colorspacetype/) 字段未指定 LCS_CALIBRATED_RGB，则必须忽略此字段。 |
| [Filename](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/filename/) { get; set; } | 获取或设置一个可选的、以空字符结尾的 Unicode UTF16-LE 字符串，指定包含颜色配置文件的文件名。如果指定了文件名，并且 [`ColorSpaceType`](./colorspacetype/) 字段设置为 LCS_CALIBRATED_RGB，则此结构的其他字段应被忽略。 |
| [GammaBlue](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/gammablue/) { get; set; } | 获取或设置一个 32 位定点值，定义蓝色的色调响应曲线。如果 [`ColorSpaceType`](./colorspacetype/) 字段未指定 LCS_CALIBRATED_RGB，则必须忽略此字段。 |
| [GammaGreen](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/gammagreen/) { get; set; } | 获取或设置一个 32 位定点值，用于定义绿色的色调响应曲线。如果 [`ColorSpaceType`](./colorspacetype/) 字段未指定 LCS_CALIBRATED_RGB，则必须忽略此字段。 |
| [GammaRed](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/gammared/) { get; set; } | 获取或设置一个 32 位定点值，用于定义红色的色调响应曲线。如果 [`ColorSpaceType`](./colorspacetype/) 字段未指定 LCS_CALIBRATED_RGB，则必须忽略此字段。 |
| [Intent](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/intent/) { get; set; } | 获取或设置一个 32 位有符号整数，用于定义色域映射意图。它必须在 GamutMappingIntent 枚举中定义（第 2.1.1.11 节）。 |
| [Signature](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/signature/) { get; set; } | 获取或设置一个 32 位无符号整数，指定颜色空间对象的签名；它必须设置为值 0x50534F43，该值是字符串 "PSOC" 的 ASCII 编码。 |
| [Size](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/size/) { get; set; } | 获取或设置定义此对象大小（以字节为单位）的 32 位无符号整数。 |
| [Version](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/version/) { get; set; } | 获取或设置一个 32 位无符号整数，定义版本号；它必须为 0x00000400。 |

## 备注

请参阅 [`WmfLogColorSpace`](../wmflogcolorspace/) 对象（第 2.2.2.11 节），了解有关此对象字段值解释的更多细节。

### 另请参见

* class [MetaObject](../../aspose.imaging.fileformats.emf/metaobject/)
* namespace [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects/)
* assembly [Aspose.Imaging](../../)


