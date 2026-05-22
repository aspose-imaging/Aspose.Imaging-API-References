---
title: "类 EmfMetafileHeaderExtension2"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfMetafileHeaderExtension2 类。EmfMetafileHeaderExtension2 记录是 EMF 元文件第二扩展中使用的头记录。在 EmfHeaderExtension2 字段之后，其余字段是可选的，且可以以任意顺序出现。"
type: docs
weight: 3930
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/
---
## EmfMetafileHeaderExtension2 class

EmfMetafileHeaderExtension2 记录是 EMF 元文件第二扩展中使用的头部记录。在 EmfHeaderExtension2 字段之后，其余字段为可选，可按任意顺序出现。

```csharp
public sealed class EmfMetafileHeaderExtension2 : EmfMetafileHeaderExtension1
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfMetafileHeaderExtension2](emfmetafileheaderextension2/#constructor)(EmfMetafileHeaderExtension1) | 初始化 `EmfMetafileHeaderExtension2` 类的新实例。 |
| [EmfMetafileHeaderExtension2](emfmetafileheaderextension2/#constructor_1)(EmfMetafileHeaderExtension2) | 初始化 `EmfMetafileHeaderExtension2` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [EmfDescription](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescription/) { get; set; } | 获取或设置 EMF 描述。一个可选的、以空字符结尾的 Unicode UTF16-LE 字符串，长度和内容任意。其在记录中的位置和字符数分别由 EmfHeader 中的 offDescription 和 nDescription 字段指定。如果任一字段的值为零，则不存在描述字符串。 |
| [EmfDescriptionBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescriptionbuffer/) { get; set; } | 获取或设置 EMF 描述缓冲区。一个可选的字节数组，包含 EMF 描述字符串，该数组不需要与 EmfMetafileHeader 记录的固定部分连续。因此，此缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。 |
| [EmfHeader](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheader/) { get; set; } | 获取或设置 Header 对象（第 2.2.9 节），该对象包含有关元文件内容和结构的信息。 |
| [EmfHeaderExtension1](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/emfheaderextension1/) { get; set; } | 获取或设置 HeaderExtension1 对象，该对象指定元文件中图像的附加信息。 |
| [EmfHeaderExtension2](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension2/emfheaderextension2/) { get; set; } | 获取或设置一个 HeaderExtension2 对象，该对象指定元文件中图像的附加信息。 |
| [EmfHeaderRecordBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheaderrecordbuffer/) { get; set; } | 获取或设置一个可选的字节数组，包含 EMF 头记录的其余部分。此字段的大小必须是 4 字节的倍数。 |
| [EmfPixelFormatBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/emfpixelformatbuffer/) { get; set; } | 获取或设置一个可选的字节数组，包含 EMF 像素格式描述符，该数组不需要与 EmfMetafileHeaderExtension1 记录的固定部分或 EMF 描述字符串连续。因此，此缓冲区中标记为 "UndefinedSpace" 的字段是可选的，必须被忽略。 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | 获取或设置类型。 |

### 另请参见

* class [EmfMetafileHeaderExtension1](../emfmetafileheaderextension1/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


