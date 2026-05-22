---
title: "类 EmfPlusLanguageIdentifier"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects.EmfPlusLanguageIdentifier 类。EmfPlusLanguageIdentifier 对象指定一个语言标识符，对应于区域设置中的自然语言，包括国家、地理区域和行政区。每个语言标识符由主语言值和子语言值编码组成。"
type: docs
weight: 5650
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslanguageidentifier/
---
## EmfPlusLanguageIdentifier class

EmfPlusLanguageIdentifier 对象指定对应于区域设置中自然语言的语言标识符，包括国家、地理区域和行政区划。每个语言标识符都是对主要语言值和子语言值的编码。

```csharp
public sealed class EmfPlusLanguageIdentifier : EmfPlusStructureObjectType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfPlusLanguageIdentifier](emfpluslanguageidentifier/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Value](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluslanguageidentifier/value/) { get; set; } | 获取或设置字段的值 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId&#x7C; PrimaryLanguageId &#x7C; SubLanguageId (6 位)：用于在 PrimaryLanguageId 字段中指定的自然语言的国家、地理区域或行政区。子语言标识符可由供应商扩展。供应商定义的子语言标识符必须在 0x20 到 0x3F（含）范围内。PrimaryLanguageId（10 位）：自然语言。主语言标识符可由供应商扩展。供应商定义的主语言标识符必须在 0x0200 到 0x03FF（含）范围内。 |

### 另请参见

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects/)
* assembly [Aspose.Imaging](../../)


