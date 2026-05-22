---
title: "类 EmfBeginPath"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfBeginPath 类。此记录在当前回放设备上下文中打开一个路径括号。路径括号打开后，应用程序可以开始处理记录以定义路径中的点。应用程序必须通过处理 EMR_ENDPATH 记录来关闭打开的路径括号。当应用程序处理 EMR_BEGINPATH 记录时，所有先前的路径必须从回放设备上下文中丢弃。"
type: docs
weight: 3330
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfbeginpath/
---
## EmfBeginPath class

此记录在当前回放设备上下文中打开路径括号。路径括号打开后，应用程序可以开始处理记录以定义路径中的点。应用程序必须通过处理 EMR_ENDPATH 记录来关闭打开的路径括号。当应用程序处理 EMR_BEGINPATH 记录时，所有先前的路径必须从回放设备上下文中丢弃。

```csharp
public sealed class EmfBeginPath : EmfPathBracketRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfBeginPath](emfbeginpath/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfPathBracketRecordType](../emfpathbracketrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


