---
title: EmfPlusStringTrimming
second_title: Aspose.Imaging for .NET API 参考
description: StringTrimming 枚举定义了如何从对于文本布局矩形来说太大的字符串中修剪字符
type: docs
weight: 5090
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringtrimming/
---
## EmfPlusStringTrimming enumeration

StringTrimming 枚举定义了如何从对于文本布局矩形来说太大的字符串中修剪字符。

```csharp
public enum EmfPlusStringTrimming
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| StringTrimmingNone | `0` | 指定不进行修剪。 |
| StringTrimmingCharacter | `1` | 指定字符串在布局矩形内的最后一个字符的边界处断开。这是默认设置。 |
| StringTrimmingWord | `2` | 指定字符串在布局矩形内的最后一个单词的边界处断开。 |
| StringTrimmingEllipsisCharacter | `3` | 指定字符串在布局矩形内的最后一个字符的边界处断开，并在字符后插入省略号 (...)。 |
| StringTrimmingEllipsisWord | `4` | 指定字符串在布局矩形内的最后一个单词的边界处断开，并在单词之后插入省略号 (...)。 |
| StringTrimmingEllipsisPath | `5` | 指定从字符串中删除中心并用省略号替换。该算法尽可能多地保留字符串的最后一部分。 |

### 也可以看看

* 命名空间 [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->