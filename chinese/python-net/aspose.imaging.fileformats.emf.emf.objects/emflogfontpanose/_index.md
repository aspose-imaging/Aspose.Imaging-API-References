---
title: "EmfLogFontPanose 类"
type: docs
weight: 160
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/
---

**Summary:** The LogFontPanose object specifies the PANOSE characteristics of a logical font.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogFontPanose

**Inheritance:** EmfLogFont

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfLogFontPanose(emf_log_font)](#EmfLogFontPanose_emf_log_font_1) | 初始化 [EmfLogFontPanose](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| char_set | [WmfCharacterSet](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfcharacterset/) | r/w | 获取或设置一个 8 位无符号整数，用于指定字符字形集合。该值必须 <br/>            是 WMF CharacterSet 枚举（[MS-WMF] 第 2.1.1.5 节）中的一个值。如果字符集未知，元文件处理不应尝试翻译或解释使用该字体渲染的 <br/>            字符串。 |
| clip_precision | [WmfClipPrecisionFlags](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/) | r/w | 获取或设置一个 8 位无符号整数，用于指定裁剪精度。<br/>            裁剪精度定义了如何裁剪部分位于裁剪区域之外的字符。<br/>            它可以是一个或多个 WMF ClipPrecision 标志。 |
| culture | int | r/w | 获取或设置一个 32 位无符号整数，该整数必须设为零且必须被忽略。 |
| escapement | int | r/w | 获取或设置一个 32 位有符号整数，用于指定 escapement 向量与设备 x 轴之间的角度（以十分之一度为单位），<br/>            escapement 向量平行于文本行的基线。 |
| 字体名称 | string | r/w | 获取或设置一个 Facename（64 字节）：一个不超过 32 个 Unicode 字符的字符串，用于指定 <br/>            字体的字形名称。如果该字符串的长度少于 32 个字符，必须存在一个终止 NULL，随后该字段的其余部分必须被忽略。 |
| full_name | string | r/w | 获取或设置一个 64 个 Unicode 字符的字符串，用于定义字体的完整名称。如果<br/>            此字符串的长度小于 64 个字符，则必须存在一个终止的 NULL，随后该字段的其余部分必须被忽略。 |
| height | int | r/w | 获取或设置一个 32 位有符号整数，指定字体的字符单元格或字符的高度（逻辑单位）。<br/>            该字符高度值，也称为 em 大小，是字符单元格高度值减去内部前导值。<br/>            字体映射器 应该 按以下方式解释 Height 字段中指定的值。 |
| 斜体 | System.Byte | r/w | 获取或设置一个 8 位无符号整数，如果设置为 0x01，则指定斜体字体；否则，<br/>            必须设置为 0x00。 |
| match | int | r/w | 获取或设置此字段必须被忽略。 |
| 方向 | int | r/w | 获取或设置一个 32 位有符号整数，以十分之一度为单位，指定每个字符基线与设备 x 轴之间的角度。<br/>             |
| out_precision | [WmfOutPrecision](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfoutprecision/) | r/w | 获取或设置一个 8 位无符号整数，指定输出精度。<br/>            输出精度定义了字体需要多接近匹配请求的高度、宽度、字符方向、倾斜角度、字距和字体类型。它 必须是 WMF OutPrecision 枚举中的一个值。 |
| padding | int | r/w | 获取或设置仅用于确保此结构 32 位对齐的字段。它必须被忽略。 |
| panose | [EmfPanose](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpanose/) | r/w | 获取或设置一个 Panose 对象（第 2.2.21 节），该对象指定逻辑字体的 PANOSE 特性。<br/>            如果该对象的所有字段均为零，则必须被忽略。 |
| pitch_and_family | [WmfPitchAndFamily](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily/) | r/w | 获取或设置一个 WMF PitchAndFamily 对象（[MS-WMF] 第 2.2.2.14 节），<br/>            指定字体的字距和族。字体族以通用方式描述字体的外观。它们用于在指定的字体不可用时指定字体。 |
| quality | [WmfFontQuality](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmffontquality/) | r/w | 获取或设置一个 8 位无符号整数，指定输出质量。输出质量定义了尝试将逻辑字体属性与实际物理字体属性匹配的精确程度。它 必须是 WMF FontQuality 枚举（[MS-WMF] 第 2.1.1.10 节）中的一个值。 |
| 删除线 | System.Byte | r/w | 获取或设置一个 8 位无符号整数，如果设置为 0x01，则指定删除线字体；<br/>            否则，必须设置为 0x00。 |
| 样式 | string | r/w | 获取或设置一个由 32 个 Unicode 字符组成的字符串，定义字体的样式。如果此字符串的长度少于 32 个字符，必须包含一个终止的 NULL，<br/>            其后该字段的其余部分必须被忽略。 |
| style_size | int | r/w | 获取或设置一个 32 位无符号整数，指定执行字体 hinting 的点大小。<br/>            如果设为零，则在 LogFont 对象的 Height 字段对应的点大小执行字体 hinting。 |
| 下划线 | System.Byte | r/w | 获取或设置一个 8 位无符号整数，如果设置为 0x01，则指定下划线字体；<br/>            否则，必须设置为 0x00。 |
| vendor_id | int | r/w | 获取或设置此字段必须被忽略。 |
| 版本 | int | r/w | 获取或设置此字段必须被忽略。 |
| weight | [EmfLogFontWeight](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emflogfontweight/) | r/w | 获取或设置一个 32 位有符号整数，指定字体的粗细，范围为<br/>            零到 1000。示例：400 为常规，700 为粗体。如果此值为零，则可以使用默认<br/>            粗细。 |
| width | int | r/w | 获取或设置一个 32 位有符号整数，指定字体中字符的平均宽度（逻辑单位），<br/>            如果 Width 字段值为零，应该根据其他 LogFont 值计算出适当的值，以找到符合排版师预期的<br/>            宽高比的字体。 |


### Constructor: EmfLogFontPanose(emf_log_font) {#EmfLogFontPanose_emf_log_font_1}


```
 EmfLogFontPanose(emf_log_font) 
```

初始化 [EmfLogFontPanose](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfontpanose/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| emf_log_font | [EmfLogFont](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogfont/) | 基础 log 字体。 |

