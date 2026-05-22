---
title: "类 EmfFormat"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfFormat 类。EmrFormat 对象包含用于识别 EMR_COMMENT_MULTIFORMATS 记录（第 2.3.3.4.3 节）中图像数据格式的信息。"
type: docs
weight: 3050
url: /zh/net/aspose.imaging.fileformats.emf.emf.objects/emfformat/
---
## EmfFormat class

EmrFormat 对象包含用于识别 EMR_COMMENT_MULTIFORMATS 记录（第 2.3.3.4.3 节）中图像数据格式的信息。

```csharp
public sealed class EmfFormat : EmfObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfFormat](emfformat/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [OffData](../../aspose.imaging.fileformats.emf.emf.objects/emfformat/offdata/) { get; set; } | 获取或设置 指定 EMR_COMMENT_PUBLIC 记录（第 2.3.3.4 节）中标识字段起始处到数据的偏移量的 32 位无符号整数。偏移量必须是 32 位对齐的。 |
| [Signature](../../aspose.imaging.fileformats.emf.emf.objects/emfformat/signature/) { get; set; } | 获取或设置 指定图像数据格式的 32 位无符号整数。该值必须属于 FormatSignature 枚举（第 2.1.14 节）。 |
| [SizeData](../../aspose.imaging.fileformats.emf.emf.objects/emfformat/sizedata/) { get; set; } | 获取或设置 指定数据大小（以字节为单位）的 32 位无符号整数 |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emfformat/version/) { get; set; } | 获取或设置 指定格式版本号的 32 位无符号整数。如果 Signature 字段指定封装的 PostScript（EPS），则该值必须为 0x00000001；否则，该值必须被忽略。 |

### 另请参见

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


