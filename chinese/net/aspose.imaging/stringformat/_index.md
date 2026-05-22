---
title: "类 StringFormat"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.StringFormat 类。封装文本布局信息，例如对齐方向和制表位显示的操作，如插入省略号、国家数字替换以及 OpenType 功能。此类不可被继承。"
type: docs
weight: 11750
url: /zh/net/aspose.imaging/stringformat/
---
## StringFormat class

封装文本布局信息（如对齐、方向和制表位）、显示操作（如省略号插入和数字本地化替换）以及 OpenType 功能。此类不可被继承。

```csharp
public sealed class StringFormat : DisposableObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | 初始化一个新的 `StringFormat` 对象。 |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | 从指定的现有 `StringFormat` 对象初始化一个新的 `StringFormat` 对象。 |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | 使用指定的 [`StringFormatFlags`](../stringformatflags/) 枚举和语言初始化一个新的 `StringFormat` 对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [GenericDefault](../../aspose.imaging/stringformat/genericdefault/) { get; } | 获取一个通用默认的 `StringFormat` 对象。 |
| static [GenericTypographic](../../aspose.imaging/stringformat/generictypographic/) { get; } | 获取一个通用排版的 `StringFormat` 对象。 |
| [Alignment](../../aspose.imaging/stringformat/alignment/) { get; set; } | 获取或设置垂直平面上的文本对齐信息。 |
| [CustomCharIdent](../../aspose.imaging/stringformat/customcharident/) { get; set; } | 获取或设置自定义字符标识。 |
| [DigitSubstitutionLanguage](../../aspose.imaging/stringformat/digitsubstitutionlanguage/) { get; set; } | 获取或设置在本地数字替换为西方数字时使用的语言。 |
| [DigitSubstitutionMethod](../../aspose.imaging/stringformat/digitsubstitutionmethod/) { get; set; } | 获取或设置用于数字替换的方法。 |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | 获取一个值，指示此实例是否已释放。 |
| [FirstTabOffset](../../aspose.imaging/stringformat/firsttaboffset/) { get; } | 获取文本行起始与第一个制表位之间的空格数。 |
| [FormatFlags](../../aspose.imaging/stringformat/formatflags/) { get; set; } | 获取或设置包含格式信息的 [`StringFormatFlags`](../stringformatflags/) 枚举。 |
| [HotkeyPrefix](../../aspose.imaging/stringformat/hotkeyprefix/) { get; set; } | 获取或设置此 `StringFormat` 对象的 [`HotkeyPrefix`](../hotkeyprefix/) 对象。 |
| [LineAlignment](../../aspose.imaging/stringformat/linealignment/) { get; set; } | 获取或设置水平平面上的行对齐方式。 |
| [TabStops](../../aspose.imaging/stringformat/tabstops/) { get; } | 获取一个数组，包含制表位之间的距离，单位由 [`PageUnit`](../graphics/pageunit/) 属性指定。 |
| [Trimming](../../aspose.imaging/stringformat/trimming/) { get; set; } | 获取或设置此 `StringFormat` 对象的 [`StringTrimming`](../stringtrimming/) 枚举。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [DeepClone](../../aspose.imaging/stringformat/deepclone/)() | 创建此 `StringFormat` 对象的深度克隆。 |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | 释放当前实例。 |
| override [Equals](../../aspose.imaging/stringformat/equals/)(object) | 检查对象是否相等。 |
| override [GetHashCode](../../aspose.imaging/stringformat/gethashcode/)() | 获取当前对象的哈希码。 |
| [SetTabStops](../../aspose.imaging/stringformat/settabstops/)(float, float[]) | 为此 `StringFormat` 对象设置制表位。 |
| override [ToString](../../aspose.imaging/stringformat/tostring/)() | 将此 `StringFormat` 对象转换为可读的字符串。 |

### 另请参见

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


