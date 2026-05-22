---
title: "类 EmfExtCreatePen"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfExtCreatePen 类。EMR_EXTCREATEPEN 记录定义了用于图形操作的扩展逻辑笔。可以指定可选的 DIB 作为线型。"
type: docs
weight: 3730
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/
---
## EmfExtCreatePen class

EMR_EXTCREATEPEN 记录定义用于图形操作的扩展逻辑笔。可以指定可选的 DIB 作为线型。

```csharp
public sealed class EmfExtCreatePen : EmfObjectCreationRecordType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfExtCreatePen](emfextcreatepen/#constructor)() | 初始化 `EmfExtCreatePen` 类的新实例。 |
| [EmfExtCreatePen](emfextcreatepen/#constructor_1)(EmfRecord) | 初始化 `EmfExtCreatePen` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BitmapBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/bitmapbuffer/) { get; set; } | 获取或设置一个可选缓冲区，包含以 WMF DeviceIndependentBitmap 对象（[MS-WMF] 第 2.2.2.9 节）形式打包的 DIB。它不需要与 EMR_EXTCREATEPEN 记录的固定部分连续。 |
| [Elp](../../aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/elp/) { get; set; } | 获取或设置一个 LogPenEx 对象（第 2.2.20 节），用于指定具有包括可选线型数组在内属性的扩展逻辑笔。 |
| [IhPen](../../aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/ihpen/) { get; set; } | 获取或设置一个 32 位无符号整数，指定 EMF 对象表（第 3.1.1.1 节）中扩展逻辑笔对象的索引。必须保存此索引，以便可以重新使用或修改该对象。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


