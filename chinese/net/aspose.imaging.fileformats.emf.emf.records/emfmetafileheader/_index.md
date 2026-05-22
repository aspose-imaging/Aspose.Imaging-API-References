---
title: "类 EmfMetafileHeader"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfMetafileHeader 类。EMR_HEADER 记录类型定义了 EMF 元文件的起始点，并指定创建该元文件图像的设备属性。头记录中的信息使 EMF 元文件能够独立于任何特定输出设备。Size 字段的值可用于区分本节前面列出的不同 EMR_HEADER 记录类型。共有三种可能的头：基础头，即 EmfMetafileHeader 记录。此头的固定大小部分为 88 字节，包含一个 Header 对象。第一扩展头，即 EmfMetafileHeaderExtension1 记录。此头的固定大小部分为 100 字节，包含一个 Header 对象和一个 HeaderExtension1 对象（第 2.2.10 节）。第二扩展头，即 EmfMetafileHeaderExtension2 记录。此头的固定大小部分为 108 字节，包含一个 Header 对象、一个 HeaderExtension1 对象和一个 HeaderExtension2 对象（第 2.2.11 节）。"
type: docs
weight: 3910
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/
---
## EmfMetafileHeader class

EMR_HEADER 记录类型定义了 EMF 元文件的起始点，并指定创建该元文件图像的设备属性。头部记录中的信息使 EMF 元文件能够独立于任何特定输出设备。Size 字段的值可用于区分本节前面列出的不同 EMR_HEADER 记录类型。共有三种可能的头部：基础头部，即 EmfMetafileHeader 记录。该头部的固定大小部分为 88 字节，包含一个 Header 对象。第一扩展头部，即 EmfMetafileHeaderExtension1 记录。该头部的固定大小部分为 100 字节，包含一个 Header 对象和一个 HeaderExtension1 对象（第 2.2.10 节）。第二扩展头部，即 EmfMetafileHeaderExtension2 记录。该头部的固定大小部分为 108 字节，包含一个 Header 对象、一个 HeaderExtension1 对象和一个 HeaderExtension2 对象（第 2.2.11 节）。

```csharp
public class EmfMetafileHeader : EmfRecord
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfMetafileHeader](emfmetafileheader/#constructor)() | 初始化 `EmfMetafileHeader` 类的新实例。 |
| [EmfMetafileHeader](emfmetafileheader/#constructor_1)(EmfMetafileHeader) | 初始化 `EmfMetafileHeader` 类的新实例。 |
| [EmfMetafileHeader](emfmetafileheader/#constructor_2)(EmfRecord) | 初始化 `EmfMetafileHeader` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [EmfDescription](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescription/) { get; set; } | 获取或设置 EMF 描述。一个可选的、以空字符结尾的 Unicode UTF16-LE 字符串，长度和内容任意。其在记录中的位置和字符数分别由 EmfHeader 中的 offDescription 和 nDescription 字段指定。如果任一字段的值为零，则不存在描述字符串。 |
| [EmfDescriptionBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescriptionbuffer/) { get; set; } | 获取或设置 EMF 描述缓冲区。一个可选的字节数组，包含 EMF 描述字符串，该数组不需要与 EmfMetafileHeader 记录的固定部分连续。因此，此缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。 |
| [EmfHeader](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheader/) { get; set; } | 获取或设置 Header 对象（第 2.2.9 节），该对象包含有关元文件内容和结构的信息。 |
| [EmfHeaderRecordBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheaderrecordbuffer/) { get; set; } | 获取或设置一个可选的字节数组，包含 EMF 头记录的其余部分。此字段的大小必须是 4 字节的倍数。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfRecord](../emfrecord/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


