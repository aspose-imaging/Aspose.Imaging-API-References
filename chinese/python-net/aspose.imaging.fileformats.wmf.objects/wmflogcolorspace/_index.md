---
title: "WmfLogColorSpace 类"
type: docs
weight: 380
url: /zh/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/
---

**Summary:** The LogColorSpace object specifies a logical color space for the<br/>                playback device context, which can be the name of a color profile in<br/>                ASCII characters.

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [WmfLogColorSpace()](#WmfLogColorSpace__1) | 初始化 WmfLogColorSpace 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| color_space_type | [WmfLogicalColorSpaceEnum](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmflogicalcolorspaceenum/) | r/w | 获取或设置一个 32 位有符号整数，指定颜色空间<br/>                类型。它必须在 LogicalColorSpace 枚举中定义<br/>                （第 2.1.1.14 节）。如果此值为 LCS_sRGB 或<br/>                LCS_WINDOWS_COLOR_SPACE，则必须使用 sRGB 颜色空间。 |
| endpoints | [WmfCieXyzTriple](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfciexyztriple/) | r/w | 获取或设置一个 CIEXYZTriple 对象（第 2.2.2.7 节），该对象定义<br/>                三种颜色的 CIE 色度 x、y、z 坐标，这些颜色对应于位图关联的逻辑<br/>                颜色空间的 RGB [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/)。如果<br/>                [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) 字段未指定 LCS_CALIBRATED_RGB，则此字段必须被忽略。 |
| filename | string | r/w | 获取或设置一个可选的 ASCII 字符串，指定包含颜色配置文件的文件名。如果指定了文件名，并且<br/>                [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) 字段被设置为 LCS_CALIBRATED_RGB，则此结构的其他字段应被忽略。 |
| gamma_blue | int | r/w | 获取或设置一个 32 位定点值，定义蓝色的色调响应曲线。如果 [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) 字段未指定 LCS_CALIBRATED_RGB，则必须忽略此字段。 |
| gamma_green | int | r/w | 获取或设置一个 32 位定点值，定义绿色的色调响应曲线。如果 [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) 字段未指定 LCS_CALIBRATED_RGB，则必须忽略此字段。 |
| gamma_red | int | r/w | 获取或设置一个 32 位定点值，定义红色的色调响应曲线。如果 [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) 字段未指定 LCS_CALIBRATED_RGB，则必须忽略此字段。 |
| intent | [WmfGamutMappingIntent](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/) | r/w | 获取或设置一个 32 位有符号整数，定义色域映射<br/>                目标。它必须在 GamutMappingIntent 枚举中定义（第 2.1.1.11 节）。 |
| signature | int | r/w | 获取或设置一个 32 位无符号整数，指定颜色空间对象的 [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/)；它必须设置为值 0x50534F43，即字符串 "PSOC" 的 ASCII 编码。 |
| size | int | r/w | 获取或设置一个 32 位无符号整数，定义此对象的 [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/)，单位为字节。 |
| version | int | r/w | 获取或设置一个 32 位无符号整数，定义一个 [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) 数值；它必须为 0x00000400。 |


### Constructor: WmfLogColorSpace() {#WmfLogColorSpace__1}


```
 WmfLogColorSpace() 
```

初始化 WmfLogColorSpace 类的新实例

