---
title: EmfMetafileHeaderExtension1
second_title: Aspose.Imaging for .NET API 参考
description: EmfMetafileHeaderExtension1 记录是在 EMF 元文件的第一个扩展中使用的标头记录 EmfHeaderExtension1 字段之后其余字段是可选的可以以任何顺序出现
type: docs
weight: 3820
url: /zh/net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/
---
## EmfMetafileHeaderExtension1 class

EmfMetafileHeaderExtension1 记录是在 EMF 元文件的第一个扩展中使用的标头记录。 EmfHeaderExtension1 字段之后，其余字段是可选的，可以以任何顺序出现。

```csharp
public class EmfMetafileHeaderExtension1 : EmfMetafileHeader
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [EmfMetafileHeaderExtension1](emfmetafileheaderextension1#constructor)(EmfMetafileHeader) | 初始化[`EmfMetafileHeaderExtension1`](../emfmetafileheaderextension1)类的新实例。 |
| [EmfMetafileHeaderExtension1](emfmetafileheaderextension1#constructor_1)(EmfMetafileHeaderExtension1) | 初始化[`EmfMetafileHeaderExtension1`](../emfmetafileheaderextension1)类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [EmfDescription](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescription) { get; set; } | 获取或设置 EMF 描述 一个可选的、以 null 结尾的、任意长度和内容的 Unicode UTF16-LE 字符串。 它在记录中的位置和字符数分别由 EmfHeader 中的 offDescription 和 nDescription 字段指定。如果任一字段 的值为零，则不存在描述字符串。 |
| [EmfDescriptionBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfdescriptionbuffer) { get; set; } | 获取或设置 EMF 描述缓冲区 包含 EMF 描述字符串的可选字节数组，即 不需要与 EmfMetafileHeader 记录的固定部分连续。因此，此缓冲区中标记为“UndefinedSpace” 的字段是可选的并且必须被忽略。 |
| [EmfHeader](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheader) { get; set; } | 获取或设置一个 Header 对象（第 2.2.9 节），其中包含有关内容 和元文件:::47 结构的信息::: |
| [EmfHeaderExtension1](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/emfheaderextension1) { get; set; } | 获取或设置 HeaderExtension1 对象，该对象指定有关图元文件中图像的附加信息。 |
| [EmfHeaderRecordBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/emfheaderrecordbuffer) { get; set; } | 获取或设置包含 EMF 标头记录剩余部分的可选字节数组。 该字段的大小必须是 4 个字节的倍数 |
| [EmfPixelFormatBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/emfpixelformatbuffer) { get; set; } | 获取或设置包含 EMF 像素格式描述符的可选字节数组， 不需要与EmfMetafileHeaderExtension1 记录或 EMF 描述字符串。因此，此缓冲区中标记为“UndefinedSpace”的字段是 可选的并且必须被忽略 |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | 获取或设置记录的大小 |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | 获取或设置类型。 |

### 也可以看看

* class [EmfMetafileHeader](../emfmetafileheader)
* 命名空间 [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->