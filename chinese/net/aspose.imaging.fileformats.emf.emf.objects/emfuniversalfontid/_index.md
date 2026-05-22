---
title: "类 EmfUniversalFontId"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfUniversalFontId 类。UniversalFontId 对象定义了一种在 EMF 元文件中识别字体的机制。"
type: docs
weight: 3270
url: /zh/net/aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---
## EmfUniversalFontId class

UniversalFontId 对象定义了一种在 EMF 元文件中识别字体的机制。

```csharp
public sealed class EmfUniversalFontId : EmfObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EmfUniversalFontId](emfuniversalfontid/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Checksum](../../aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/checksum/) { get; set; } | 获取或设置一个 32 位无符号整数，作为字体的校验和。校验和值具有以下含义。0x00000000 对象是设备字体。0x00000001 对象是已安装在客户端机器上并被 PostScript 打印机驱动程序枚举为设备字体的 Type 1 字体。0x00000002 对象不是字体，而是 Type 1 光栅化器。3 ≤ 值 对象是位图、矢量或 TrueType 字体，或由 Type 1 光栅化器创建的 Type 1 光栅化字体。 |
| [Index](../../aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/index/) { get; set; } | 获取或设置一个 32 位无符号整数，作为与字体对象关联的索引。此字段的含义取决于字体的类型。 |

### 另请参见

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


