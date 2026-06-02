---
title: "类 Font"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Font 类。定义文本的特定格式，包括字体大小和样式属性。此类不可被继承。"
type: docs
weight: 9510
url: /zh/net/aspose.imaging/font/
---
## Font class

定义文本的特定格式，包括字体、大小和样式属性。此类不可被继承。

```csharp
public sealed class Font
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | 初始化一个使用指定现有 `Font` 和 [`FontStyle`](../fontstyle/) 枚举的新 `Font`。 |
| [Font](font/#constructor_1)(string, float) | 使用指定的大小初始化一个新 `Font`。字符集设置为 Default，图形单位设置为 Point，字体样式设置为 Regular。 |
| [Font](font/#constructor_2)(string, float, FontStyle) | 使用指定的大小和样式初始化一个新 `Font`。字符集设置为 Default，图形单位设置为 Point。 |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | 使用指定的大小和单位初始化一个新 `Font`。字符集设置为 Default，样式设置为 Regular。 |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | 使用指定的大小、样式和单位初始化一个新的 `Font`。 |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | 使用指定的大小、样式、单位和字符集初始化一个新的 `Font`。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Bold](../../aspose.imaging/font/bold/) { get; } | 获取一个值，指示此 `Font` 是否为粗体。 |
| [CharacterSet](../../aspose.imaging/font/characterset/) { get; } | 获取一个字节值，指定此 `Font` 使用的字符集。 |
| [Italic](../../aspose.imaging/font/italic/) { get; } | 获取一个值，指示此 `Font` 是否为斜体。 |
| [Name](../../aspose.imaging/font/name/) { get; } | 获取此 `Font` 的字体名称。 |
| [Size](../../aspose.imaging/font/size/) { get; } | 获取此 `Font` 的 em 大小，使用由 [`Unit`](./unit/) 属性指定的单位进行测量。 |
| [Strikeout](../../aspose.imaging/font/strikeout/) { get; } | 获取一个值，指示此 `Font` 是否在字体上指定水平划线。 |
| [Style](../../aspose.imaging/font/style/) { get; } | 获取此 `Font` 的样式信息。 |
| [Underline](../../aspose.imaging/font/underline/) { get; } | 获取一个值，指示此 `Font` 是否带下划线。 |
| [Unit](../../aspose.imaging/font/unit/) { get; } | 获取此 `Font` 的度量单位。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [DeepClone](../../aspose.imaging/font/deepclone/)() | 创建此 `Font` 的精确深拷贝。 |
| override [Equals](../../aspose.imaging/font/equals/)(object) | 指示指定的对象是否为 `Font` 且具有与此 `Font` 相同的属性值。 |
| override [GetHashCode](../../aspose.imaging/font/gethashcode/)() | 获取此 `Font` 的哈希码。 |
| override [ToString](../../aspose.imaging/font/tostring/)() | 返回此 `Font` 的可读字符串表示。 |

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


