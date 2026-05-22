---
title: "类 EmfRecord"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfRecord 类。EMF 记录的基类。所有 EMF 记录的长度必须是 4 字节的倍数。这通过在前述 EMF 记录类型的通用结构中在适当位置的结构末尾包含 AlignmentPadding 字段来体现。AlignmentPadding 字段的内容必须始终被忽略。为简洁起见，这些字段未在每个单独的 EMF 记录定义中显示。"
type: docs
weight: 4270
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfrecord/
---
## EmfRecord class

EMF 记录的基类。所有 EMF 记录的长度必须是 4 字节的倍数。这在前述 EMF 记录类型的通用结构中通过在这些结构的末尾适当加入 AlignmentPadding 字段来体现。AlignmentPadding 字段的内容必须始终被忽略。为简洁起见，这些字段未在每个单独的 EMF 记录定义中显示。

```csharp
public class EmfRecord : MetaObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfRecord](emfrecord/#constructor)() | 初始化 `EmfRecord` 类的新实例。 |
| [EmfRecord](emfrecord/#constructor_2)(EmfRecord) | 初始化 `EmfRecord` 类的新实例。 |
| [EmfRecord](emfrecord/#constructor_1)(EmfRecordType) | 初始化 `EmfRecord` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [MetaObject](../../aspose.imaging.fileformats.emf/metaobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


