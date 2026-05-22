---
title: "类 EmfLogFont"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfLogFont 类。LogFont 对象指定逻辑字体的基本属性"
type: docs
weight: 3120
url: /zh/net/aspose.imaging.fileformats.emf.emf.objects/emflogfont/
---
## EmfLogFont class

LogFont 对象指定了逻辑字体的基本属性。

```csharp
public class EmfLogFont : EmfObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfLogFont](emflogfont/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CharSet](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/charset/) { get; set; } | 获取或设置一个 8 位无符号整数，指定字符字形集合。它必须是 WMF CharacterSet 枚举（[MS-WMF] 第 2.1.1.5 节）中的一个值。如果字符集未知，元文件处理不应尝试翻译或解释使用该字体渲染的字符串。 |
| [ClipPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/clipprecision/) { get; set; } | 获取或设置一个 8 位无符号整数，指定剪裁精度。剪裁精度定义如何剪裁部分位于剪裁区域之外的字符。它可以是一个或多个 WMF ClipPrecision 标志。 |
| [Escapement](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/escapement/) { get; set; } | 获取或设置一个 32 位有符号整数，指定转向向量与设备 X 轴之间的角度（以十分之一度为单位）。转向向量与文本行的基线平行。 |
| [Facename](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/facename/) { get; set; } | 获取或设置一个 Facename（64 字节）：一个不超过 32 个 Unicode 字符的字符串，指定字体的字形名称。如果该字符串长度少于 32 个字符，必须包含一个终止的 NULL，之后的字段内容必须被忽略。 |
| [Height](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/height/) { get; set; } | 获取或设置一个 32 位有符号整数，指定字体字符单元或字符的高度（逻辑单位）。字符高度值，也称为 em 大小，是字符单元高度减去内部前导值。字体映射器应按以下方式解释 Height 字段中指定的值。 |
| [Italic](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/italic/) { get; set; } | 获取或设置一个 8 位无符号整数，如果设置为 0x01 则表示斜体字体；否则必须设置为 0x00。 |
| [Orientation](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/orientation/) { get; set; } | 获取或设置一个 32 位有符号整数，指定每个字符基线与设备 X 轴之间的角度（以十分之一度为单位）。 |
| [OutPrecision](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/outprecision/) { get; set; } | 获取或设置一个 8 位无符号整数，指定输出精度。输出精度定义字体需要多接近匹配请求的高度、宽度、字符方向、倾斜角度、字距和字体类型。它必须是 WMF OutPrecision 枚举中的一个值。 |
| [PitchAndFamily](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/pitchandfamily/) { get; set; } | 获取或设置一个 WMF PitchAndFamily 对象（[MS-WMF] 第 2.2.2.14 节），指定字体的字距和族。字体族以一般方式描述字体的外观。它们用于在指定的字体不可用时指定字体。 |
| [Quality](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/quality/) { get; set; } | 获取或设置一个 8 位无符号整数，指定输出质量。输出质量定义尝试将逻辑字体属性与实际物理字体属性匹配的精确程度。它必须是 WMF FontQuality 枚举（[MS-WMF] 第 2.1.1.10 节）中的一个值。 |
| [Strikeout](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/strikeout/) { get; set; } | 获取或设置一个 8 位无符号整数，如果设为 0x01 则指定删除线字体；否则必须设为 0x00。 |
| [Underline](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/underline/) { get; set; } | 获取或设置一个 8 位无符号整数，如果设为 0x01 则指定下划线字体；否则必须设为 0x00。 |
| [Weight](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/weight/) { get; set; } | 获取或设置一个 32 位有符号整数，指定字体的粗细，范围为 0 到 1000。例如，400 为常规，700 为粗体。如果该值为 0，则可以使用默认粗细。 |
| [Width](../../aspose.imaging.fileformats.emf.emf.objects/emflogfont/width/) { get; set; } | 获取或设置一个 32 位有符号整数，指定字体中字符的平均宽度（逻辑单位）。如果 Width 字段的值为 0，则应根据其他 LogFont 值计算出合适的值，以获得排版师预期的宽高比的字体。 |

### 另请参见

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


